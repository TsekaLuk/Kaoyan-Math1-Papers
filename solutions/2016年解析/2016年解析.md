# 2016年数学(一）真题解析

# 一、选择题

（1）【答案】 (C).

【解】 $\int_0^{+\infty}\frac{\mathrm{d}x}{x^a(1 + x)^b} = \int_0^1\frac{\mathrm{d}x}{x^a(1 + x)^b} +\int_1^{+\infty}\frac{\mathrm{d}x}{x^a(1 + x)^b},$

由 $\lim_{x\to 0^{+}}x^{a}\cdot \frac{1}{x^{a}(1 + x)^{b}} = 1$ 且 $\int_0^1\frac{\mathrm{d}x}{x^a(1 + x)^b}$ 收敛得 $a <   1$

再由 $\lim_{x\to +\infty}x^{a + b}\cdot \frac{1}{x^a(1 + x)^b} = 1$ 且 $\int_1^{+\infty}\frac{\mathrm{d}x}{x^a(1 + x)^b}$ 收敛得 $a + b > 1$

即 $a < 1$ 且 $a + b > 1$ ，应选(C).

(2)【答案】 (D).

【解】 $F(x) = \int f(x)\mathrm{d}x = \left\{ \begin{array}{ll}(x - 1)^2 +C, & x <   1,\\ x(\ln x - 1) + C + 1, & x\geqslant 1. \end{array} \right.$

取 $C = 0$ 得 $f(x)$ 的一个原函数为 $F(x) = \begin{cases} (x - 1)^2, & x < 1, \\ x(\ln x - 1) + 1, & x \geqslant 1. \end{cases}$ 应选(D).

（3）【答案】 （A）.

【解】设 $y_{1} = (1 + x^{2})^{2} - \sqrt{1 + x^{2}}$ ， $y_{2} = (1 + x^{2})^{2} + \sqrt{1 + x^{2}}$

由线性微分方程解的结构得 $y_{2} - y_{1} = 2\sqrt{1 + x^{2}}$ 为 $y^\prime +p(x)y = 0$ 的解，

代入得 $\frac{2x}{\sqrt{1 + x^2}} + p(x) \cdot 2\sqrt{1 + x^2} = 0$ ，解得 $p(x) = -\frac{x}{1 + x^2}$

再由线性微分方程解的结构，得 $\frac{y_1 + y_2}{2} = (1 + x^2)^2$ 为 $y^\prime +p(x)y = q(x)$ 的解，代入得 $4x(1 + x^{2}) - \frac{x}{1 + x^{2}}\bullet (1 + x^{2})^{2} = q(x)$ ，解得 $q(x) = 3x(1 + x^2)$ ，应选(A).

(4)【答案】 (D).

【解】 $f(0) = 0, \lim_{x \to 0^{-}} f(x) = 0, \lim_{x \to 0^{+}} f(x) = \lim_{n \to \infty} \frac{1}{n} = 0,$

由 $f(0) = f(0 - 0) = f(0 + 0) = 0$ 得 $f(x)$ 在 $x = 0$ 处连续.

由 $\lim_{x\to 0^{-}}\frac{f(x) - f(0)}{x} = \lim_{x\to 0^{-}}\frac{x}{x} = 1$ 得 $f_{-}^{\prime}(0) = 1$

$$
\lim  _ {x \rightarrow 0 ^ {+}} \frac {f (x) - f (0)}{x} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {\frac {1}{n}}{x},
$$

由 $\frac{1}{n + 1} < x < \frac{1}{n}$ 得 $\frac{n}{n + 1} < \frac{x}{\frac{1}{n}} < 1$ ，从而 $\lim_{x \to 0^+} \frac{x}{\frac{1}{n}} = 1$ ，于是 $f_+^\prime(0) = 1$

因为 $f_{-}^{\prime}(0) = f_{+}^{\prime}(0) = 1$ ，所以 $f(x)$ 在 $x = 0$ 处可导，应选(D).

（5）【答案】 (C).

【解】由 $\mathbf{A}$ 与 $\pmb{B}$ 相似可知，存在可逆矩阵 $P$ ，使得 $P^{-1}AP = B$

对 $P^{-1}AP = B$ 两边取转置得 $\pmb{P}^{\mathrm{T}}\pmb{A}^{\mathrm{T}}(\pmb{P}^{-1})^{\mathrm{T}} = \pmb{B}^{\mathrm{T}}$ ，或 $[(\pmb{P}^{\mathrm{T}})^{-1}]^{-1}\pmb{A}^{\mathrm{T}}[(\pmb{P}^{\mathrm{T}})^{-1}] = \pmb{B}^{\mathrm{T}}$

即 $\mathbf{A}^{\mathrm{T}}$ 与 $\pmb{B}^{\mathrm{T}}$ 相似，（A）正确；

由 $P^{-1}AP = B$ 得 $P^{-1}A^{-1}P = B^{-1}$ ，即 $A^{-1}$ 与 $B^{-1}$ 相似，（B）正确；

由 $P^{-1}AP = B$ 及 $P^{-1}A^{-1}P = B^{-1}$ 得 $P^{-1}(A + A^{-1})P = B + B^{-1}$

即 $\mathbf{A} + \mathbf{A}^{-1}$ 与 $\pmb {B} + \pmb{B}^{-1}$ 相似，（D）正确，应选(C).

（6）【答案】 （B）.

【解】 二次型的矩阵为 $\mathbf{A} = \begin{pmatrix} 1 & 2 & 2\\ 2 & 1 & 2\\ 2 & 2 & 1 \end{pmatrix}$

由 $|\lambda \pmb {E} - \pmb {A}| = \left| \begin{array}{ccc}\lambda -1 & -2 & -2\\ -2 & \lambda -1 & -2\\ -2 & -2 & \lambda -1 \end{array} \right| = (\lambda +1)^{2}(\lambda -5) = 0$ 得

矩阵 $\mathbf{A}$ 的特征值为 $\lambda_{1} = 5, \lambda_{2} = \lambda_{3} = -1$

二次型的规范形为 $f(x_{1},x_{2},x_{3}) = 5y_{1}^{2} - y_{2}^{2} - y_{3}^{2}$

从而 $f(x_{1},x_{2},x_{3}) = 2$ 表示的曲面为 $5y_{1}^{2} - y_{2}^{2} - y_{3}^{2} = 2$ ，该曲面表示双叶双曲面，应选(B).

（7）【答案】 (B).

【解】 由 $X \sim N(\mu, \sigma^2)$ 得 $\frac{X - \mu}{\sigma} \sim N(0,1)$ ,

$$
p = P \{X \leqslant \mu + \sigma^ {2} \} = P \left\{\frac {X - \mu}{\sigma} \leqslant \sigma \right\} = \Phi (\sigma),
$$

则 $p$ 随着 $\sigma$ 的增加而增加，应选（B）.

（8）【答案】 （A）.

【解】 方法一 $X\sim B\left(2,\frac{1}{3}\right),Y\sim B\left(2,\frac{1}{3}\right),$

$$
E (X) = E (Y) = \frac {2}{3}, D (X) = D (Y) = \frac {4}{9}, E (X Y) = 1 \times 1 \times P \{X = 1, Y = 1 \} = \frac {2}{9},
$$

$$
\operatorname {C o v} (X, Y) = E (X Y) - E (X) E (Y) = \frac {2}{9} - \frac {4}{9} = - \frac {2}{9},
$$

则 $\rho_{XY} = \frac{\operatorname{Cov}(X,Y)}{\sqrt{D(X)}\cdot\sqrt{D(Y)}} = -\frac{2}{9}\times \frac{9}{4} = -\frac{1}{2}$ ，应选（A）.

方法二 $P\{X = 0\} = \mathrm{C}_2^0\left(\frac{1}{3}\right)^0\left(\frac{2}{3}\right)^2 = \frac{4}{9},$

$$
P \{X = 1 \} = C _ {2} ^ {1} \frac {1}{3} \cdot \frac {2}{3} = \frac {4}{9}, \quad P \{X = 2 \} = C _ {2} ^ {2} \left(\frac {1}{3}\right) ^ {2} \left(\frac {2}{3}\right) ^ {0} = \frac {1}{9},
$$

$X\sim \left( \begin{array}{ccc}0 & 1 & 2\\ \frac{4}{9} & \frac{4}{9} & \frac{1}{9} \end{array} \right),$ 同理 $Y\sim \left( \begin{array}{ccc}0 & 1 & 2\\ \frac{4}{9} & \frac{4}{9} & \frac{1}{9} \end{array} \right),$

$$
E (X) = \frac {2}{3}, E \left(X ^ {2}\right) = \frac {8}{9}, D (X) = \frac {8}{9} - \frac {4}{9} = \frac {4}{9}, E (Y) = \frac {2}{3}, D (Y) = \frac {4}{9}.
$$

$$
P \{X Y = 1 \} = P \{X = 1, Y = 1 \} = \frac {2}{9},
$$

$P\{XY = 0\} = \frac{7}{9}$ 即 $XY\sim \left( \begin{array}{ll}0 & 1\\ \frac{7}{9} & \frac{2}{9} \end{array} \right).$

$$
E (X Y) = \frac {2}{9}, \operatorname {C o v} (X, Y) = E (X Y) - E (X) E (Y) = \frac {2}{9} - \frac {4}{9} = - \frac {2}{9},
$$

$$
\rho_ {X Y} = \frac {\operatorname {C o v} (X , Y)}{\sqrt {D (X)} \cdot \sqrt {D (Y)}} = - \frac {2}{9} \times \frac {9}{4} = - \frac {1}{2}.
$$

# 二、填空题

(9)【答案】 $\frac{1}{2}$ .

【解】

$$
\lim  _ {x \rightarrow 0} \frac {\int_ {0} ^ {x} t \ln (1 + t \sin t) \mathrm {d} t}{1 - \cos x ^ {2}} = \lim  _ {x \rightarrow 0} \frac {\int_ {0} ^ {x} t \ln (1 + t \sin t) \mathrm {d} t}{\frac {1}{2} x ^ {4}} = \lim  _ {x \rightarrow 0} \frac {x \ln (1 + x \sin x)}{2 x ^ {3}} = \frac {1}{2}.
$$

（10）【答案】 $j + (y - 1)k$

【解】rot $\mathbf{A} = \left| \begin{array}{ccc}i & j & k\\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z}\\ x + y + z & xy & z \end{array} \right| = j + (y - 1)\pmb {k}.$

(11)【答案】 $-\mathrm{d}x + 2\mathrm{d}y$

【解】 将 $x = 0, y = 1$ 代入得 $z = 1$ .

$(x + 1)z - y^{2} = x^{2}f(x - z,y)$ 两边关于 $x$ 求偏导得

$$
z + (x + 1) z _ {x} ^ {\prime} = 2 x f (x - z, y) + x ^ {2} f _ {1} ^ {\prime} (x - z, y) \cdot \left(1 - z _ {x} ^ {\prime}\right),
$$

将 $x = 0, y = 1, z = 1$ 代入得 $z_x'(0,1) = -1$

$(x + 1)z - y^{2} = x^{2}f(x - z,y)$ 两边关于 $y$ 求偏导得

$$
(x + 1) z _ {y} ^ {\prime} - 2 y = x ^ {2} \left[ f _ {1} ^ {\prime} (x - z, y) \left(- z _ {y} ^ {\prime}\right) + f _ {y} ^ {\prime} (x - z, y) \right],
$$

将 $x = 0, y = 1, z = 1$ 代入得 $z_{y}^{\prime}(0,1) = 2$ ，故 $\mathrm{d}z|_{(0,1)} = -\mathrm{d}x + 2\mathrm{d}y$

(12)【答案】 $\frac{1}{2}$ .

【解】方法一 $\arctan x = x - \frac{x^3}{3} + o(x^3), \frac{1}{1 + ax^2} = 1 - ax^2 + o(x^2)$

则 $\arctan x - \frac{x}{1 + ax^2} = \left(a - \frac{1}{3}\right)x^3 + o(x^3)$

再由 $f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!} x^2 +\frac{f'''(0)}{3!} x^3 +o(x^3)$ 得

$\frac{f^{\prime\prime}(0)}{3!} = a - \frac{1}{3}$ 解得 $a = \frac{1}{2}$

方法二 $f^{\prime}(x) = \frac{1}{1 + x^{2}} -\frac{1 - ax^{2}}{(1 + ax^{2})^{2}},$

$$
\begin{array}{l} f ^ {\prime \prime} (x) = - \frac {2 x}{\left(1 + x ^ {2}\right) ^ {2}} + \frac {6 a x - 2 a ^ {2} x ^ {3}}{\left(1 + a x ^ {2}\right) ^ {3}}, \\ f ^ {\prime \prime} (x) = - \frac {2 - 6 x ^ {2}}{(1 + x ^ {2}) ^ {3}} - \frac {(6 a - 6 a ^ {2} x ^ {2}) (1 + a x ^ {2}) - 6 a x (6 a x - 2 a ^ {2} x ^ {3})}{(1 + a x ^ {2}) ^ {4}}, \\ \end{array}
$$

所以 $f^{\prime \prime}(0) = -2 + 6a$ ，由 $-2 + 6a = 1$ 得 $a = \frac{1}{2}$

(13)【答案】 $\lambda^4 +\lambda^3 +2\lambda^2 +3\lambda +4.$

【解】 $\begin{array}{r}\left| \begin{array}{cccc} \lambda & -1 & 0 & 0\\ 0 & \lambda & -1 & 0\\ 0 & 0 & \lambda & -1\\ 4 & 3 & 2 & \lambda +1 \end{array} \right| = \lambda \cdot \left| \begin{array}{ccc}\lambda & -1 & 0\\ 0 & \lambda & -1\\ 3 & 2 & \lambda +1 \end{array} \right| + \left| \begin{array}{ccc}0 & -1 & 0\\ 0 & \lambda & -1\\ 4 & 2 & \lambda +1 \end{array} \right| \end{array}$

$$
\begin{array}{l} = \lambda \left[ \lambda \left| \begin{array}{c c} \lambda & - 1 \\ 2 & \lambda + 1 \end{array} \right| + \left| \begin{array}{c c} 0 & - 1 \\ 3 & \lambda + 1 \end{array} \right| \right] + \left| \begin{array}{c c} 0 & - 1 \\ 4 & \lambda + 1 \end{array} \right| \\ = \lambda \left[ \lambda (\lambda^ {2} + \lambda + 2) + 3 \right] + 4 \\ = \lambda^ {4} + \lambda^ {3} + 2 \lambda^ {2} + 3 \lambda + 4. \\ \end{array}
$$

（14）【答案】 (8.2, 10.8).

【解】 $P\left\{-u_{0.025} < \frac{\overline{x} - \mu}{\frac{\sigma}{\sqrt{n}}} < u_{0.025}\right\} = 0.95,$

得 $P\left\{\overline{x} - \frac{\sigma}{\sqrt{n}} u_{0.025} < \mu < \overline{x} + \frac{\sigma}{\sqrt{n}} u_{0.025}\right\} = 0.95,$

由 $\overline{x} +\frac{\sigma}{\sqrt{n}} u_{0.025} = 10.8$ 得 $\frac{\sigma}{\sqrt{n}} u_{0.025} = 10.8 - \overline{x} = 1.3$ ，从而 $\overline{x} -\frac{\sigma}{\sqrt{n}} u_{0.025} = 8.2,$

故 $\mu$ 的置信度为0.95的双侧置信区间为(8.2，10.8).

# 三、解答题

（15）【解】 $\iint_{D}x\mathrm{d}x\mathrm{d}y = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\mathrm{d}\theta \int_{2}^{2(1 + \cos \theta)}r^{2}\cos \theta \mathrm{d}r$

$$
\begin{array}{l} = \frac {8}{3} \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} \left(\cos^ {4} \theta + 3 \cos^ {3} \theta + 3 \cos^ {2} \theta\right) d \theta \\ = \frac {1 6}{3} \int_ {0} ^ {\frac {\pi}{2}} (\cos^ {4} \theta + 3 \cos^ {3} \theta + 3 \cos^ {2} \theta) d \theta \\ = \frac {1 6}{3} \left(I _ {4} + 3 I _ {3} + 3 I _ {2}\right) = 5 \pi + \frac {3 2}{3}. \\ \end{array}
$$

（16）【证明】（I）微分方程 $y^{\prime \prime} + 2y^{\prime} + ky = 0$ 的特征方程为 $\lambda^2 +2\lambda +k = 0$

解得 $\lambda_{1} = -1 + \sqrt{1 - k}$ ， $\lambda_{2} = -1 - \sqrt{1 - k}$

因为 $0 < k < 1$ ，所以 $\lambda_1 < 0, \lambda_2 < 0$ ，从而 $\int_{0}^{+\infty} \mathrm{e}^{\lambda_1 x} \mathrm{d}x$ 与 $\int_{0}^{+\infty} \mathrm{e}^{\lambda_2 x} \mathrm{d}x$ 都收敛.

该方程的通解为 $y = C_{1}\mathrm{e}^{\lambda_{1}x} + C_{2}\mathrm{e}^{\lambda_{2}x}$

由 $\int_{0}^{+\infty}y(x)\mathrm{d}x = C_{1}\int_{0}^{+\infty}\mathrm{e}^{\lambda_{1}x}\mathrm{d}x + C_{2}\int_{0}^{+\infty}\mathrm{e}^{\lambda_{2}x}\mathrm{d}x$ ，得 $\int_0^{+\infty}y(x)\mathrm{d}x$ 收敛.

（Ⅱ）方法一 由 $\lambda_1 < 0, \lambda_2 < 0$ 得 $\lim_{x \to +\infty} y(x) = \lim_{x \to +\infty} (C_1 e^{\lambda_1 x} + C_2 e^{\lambda_2 x}) = 0,$

$$
\lim  _ {x \rightarrow + \infty} y ^ {\prime} (x) = \lim  _ {x \rightarrow + \infty} \left(C _ {1} \lambda_ {1} e ^ {\lambda_ {1} x} + C _ {2} \lambda_ {2} e ^ {\lambda_ {2} x}\right) = 0,
$$

于是 $\int_0^{+\infty}y(x)\mathrm{d}x = -\frac{1}{k}\left[\int_0^{+\infty}y''(x)\mathrm{d}x + 2\int_0^{+\infty}y'(x)\mathrm{d}x\right],$

再由 $\int_{0}^{+\infty}y^{\prime \prime}(x)\mathrm{d}x = y^{\prime}(x)\Big|_{0}^{+\infty} = -y^{\prime}(0) = -1,$

$$
\int_ {0} ^ {+ \infty} y ^ {\prime} (x) \mathrm {d} x = y (x) \Big | _ {0} ^ {+ \infty} = - y (0) = - 1,
$$

得 $\int_{0}^{+\infty}y(x)\mathrm{d}x = \frac{3}{k}$

方法二 将 $y(0) = 1, y'(0) = 1$ 代入 $y = C_1 \mathrm{e}^{\lambda_1 x} + C_2 \mathrm{e}^{\lambda_2 x}$ 得 $\left\{ \begin{array}{l} C_1 + C_2 = 1, \\ \lambda_1 C_1 + \lambda_2 C_2 = 1. \end{array} \right.$

解得 $C_1 = \frac{1 - \lambda_2}{\lambda_1 - \lambda_2} = \frac{2 + \sqrt{1 - k}}{2\sqrt{1 - k}}, C_2 = \frac{\lambda_1 - 1}{\lambda_1 - \lambda_2} = \frac{-2 + \sqrt{1 - k}}{2\sqrt{1 - k}},$

故 $\int_0^{+\infty}y(x)\mathrm{d}x = -\left(\frac{C_1}{\lambda_1} +\frac{C_1}{\lambda_1}\right) = \frac{3}{k}.$

(17)【解】 方法一 由 $\frac{\partial f(x,y)}{\partial x} = (2x + 1)\mathrm{e}^{2x - y}$ 得

$$
\begin{array}{l} f (x, y) = \frac {1}{2} \mathrm {e} ^ {- y} \int (2 x + 1) \mathrm {d} \left(\mathrm {e} ^ {2 x}\right) + \varphi (y) = \frac {1}{2} \mathrm {e} ^ {- y} \left[ (2 x + 1) \mathrm {e} ^ {2 x} - 2 \int \mathrm {e} ^ {2 x} \mathrm {d} x \right] + \varphi (y) \\ = x \mathrm {e} ^ {2 x - y} + \varphi (y). \\ \end{array}
$$

由 $f(0,y) = y + 1$ 得 $\varphi (y) = y + 1$ ，于是 $f(x,y) = x\mathrm{e}^{2x - y} + y + 1.$

$$
\frac {\partial f (x , y)}{\partial y} = - x \mathrm {e} ^ {2 x - y} + 1,
$$

令 $P(x,y) = \frac{\partial f(x,y)}{\partial x},\quad Q(x,y) = \frac{\partial f(x,y)}{\partial y},$

$$
\frac {\partial P}{\partial y} = - (2 x + 1) \mathrm {e} ^ {2 x - y}, \quad \frac {\partial Q}{\partial x} = - (2 x + 1) \mathrm {e} ^ {2 x - y},
$$

因为 $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x}$ 所以曲线积分与路径无关，

于是 $I(t) = \int_{0}^{1}(2x + 1)\mathrm{e}^{2x}\mathrm{d}x + \int_{0}^{t}(1 - \mathrm{e}^{2 - y})\mathrm{d}y = t + \mathrm{e}^{2 - t}.$

由 $I^{\prime}(t) = 1 - \mathrm{e}^{2 - t} = 0$ 得 $t = 2$

因为 $I''(t) = \mathrm{e}^{2 - t} > 0$ ，所以当 $t = 2$ 时， $I(t)$ 取最小值，最小值为 $I(2) = 3$

方法二 由 $\frac{\partial f(x,y)}{\partial x} = (2x + 1)\mathrm{e}^{2x - y}$ 得 $f(x,y) = x\mathrm{e}^{2x - y} + \varphi (y)$

由 $f(0,y) = y + 1$ 得 $\varphi (y) = y + 1$ ，从而 $f(x,y) = x\mathrm{e}^{2x - y} + y + 1.$

于是 $I(t) = \int_{L_t} \mathrm{d}f(x, y) = f(1, t) - f(0, 0) = \mathrm{e}^{2 - t} + t$ .

由 $I^{\prime}(t) = 1 - \mathrm{e}^{2 - t} = 0$ 得 $t = 2$

当 $t < 2$ 时， $I'(t) < 0$ ；当 $t > 2$ 时， $I'(t) > 0$ ，则 $t = 2$ 时 $I(t)$ 取最小值，且最小值为

$$
I (2) = 3.
$$

（18）【解】由高斯公式得 $I = \iint_{\Sigma}(x^{2} + 1)\mathrm{d}y\mathrm{d}z - 2y\mathrm{d}z\mathrm{d}x + 3z\mathrm{d}x\mathrm{d}y = \iiint_{\Omega}(2x + 1)\mathrm{d}v,$

而 $\iiint_{\Omega} \mathrm{d}v = \frac{1}{3} \times \frac{1}{2} \times 2 \times 1 \times 1 = \frac{1}{3}$ ,

$$
\begin{array}{l} \iiint_ {\Omega} x \mathrm {d} v = \int_ {0} ^ {1} x \mathrm {d} x \int_ {0} ^ {2 (1 - x)} \mathrm {d} y \int_ {0} ^ {1 - x - \frac {y}{2}} \mathrm {d} z = \int_ {0} ^ {1} x \mathrm {d} x \int_ {0} ^ {2 (1 - x)} \left(1 - x - \frac {y}{2}\right) \mathrm {d} y \\ = \int_ {0} ^ {1} x (1 - x) ^ {2} d x = \frac {1}{1 2}, \\ \end{array}
$$

故 $I = \frac{1}{3} +2\times \frac{1}{12} = \frac{1}{2}$

（19）【证明】

(I) $|x_{n+1} - x_n| = |f(x_n) - f(x_{n-1})| = |f'(\xi)(x_n - x_{n-1})|$ ，其中 $\xi$ 介于 $x_{n-1}$ 与 $x_n$ 之间.

因为 $0 < f'(x) < \frac{1}{2}$ ，所以 $\left|x_{n+1} - x_n\right| \leqslant \frac{1}{2}\left|x_n - x_{n-1}\right|$ ，

由递推关系得 $|x_{n + 1} - x_n| \leqslant \frac{1}{2^{n - 1}} |x_2 - x_1|$ .

因为级数 $\sum_{n=1}^{\infty} \frac{1}{2^{n-1}} |x_2 - x_1|$ 收敛，所以 $\sum_{n=1}^{\infty} |x_{n+1} - x_n|$ 收敛，

故级数 $\sum_{n = 1}^{\infty}(x_{n + 1} - x_n)$ 绝对收敛.

（Ⅱ）级数 $\sum_{n = 1}^{\infty}(x_{n + 1} - x_n)$ 的部分和为

$$
S _ {n} = \left(x _ {2} - x _ {1}\right) + \left(x _ {3} - x _ {2}\right) + \dots + \left(x _ {n + 1} - x _ {n}\right) = x _ {n + 1} - x _ {1},
$$

因为级数 $\sum_{n=1}^{\infty}(x_{n+1}-x_n)$ 收敛，即 $\lim_{n\to\infty}S_n$ 存在，所以 $\lim_{n\to\infty}x_n$ 存在.

令 $\lim_{n\to \infty}x_n = a,x_{n + 1} = f(x_n)$ 及函数 $f(x)$ 的连续性得 $a = f(a)$

令 $\varphi (x) = x - f(x)$ ，即 $x = a$ 为 $\varphi (x)$ 的零点

因为 $\varphi (0) = -f(0) = -1$

$\varphi (2) = 2 - f(2) = 1 - [f(2) - f(0)] = 1 - 2f'(\eta) > 0$ ，其中 $\eta \in (0,2)$

所以 $\varphi (x)$ 在(0，2）内有零点

又因为 $\varphi'(x) = 1 - f'(x) > 0$ ，所以 $\varphi(x)$ 只有唯一的一个零点，且位于 $(0,2)$ 内，于是 $0 < a < 2$ ，即 $0 < \lim_{n\to \infty}x_n < 2$

（20）【解】 方法一

$$
(\mathbf {A} \mid \mathbf {B}) = \left(\begin{array}{c c c c c c}1&- 1&- 1&2&2\\2&a&1&1&a\\- 1&1&a&- a - 1&- 2\end{array}\right)\rightarrow \left(\begin{array}{c c c c c c}1&- 1&- 1&2&2\\0&a + 2&3&- 3&a - 4\\0&0&a - 1&1 - a&0\end{array}\right)
$$

当 $a \neq -2$ 且 $a \neq 1$ 时，

$$
(\mathbf {A} \vdots \mathbf {B}) \rightarrow \left(\begin{array}{c c c c c}1&- 1&- 1&2&2\\0&a + 2&3&- 3&a - 4\\0&0&1&- 1&0\end{array}\right)\rightarrow \left(\begin{array}{c c c c c}1&0&0&1&\frac {3 a}{a + 2}\\0&1&0&0&\frac {a - 4}{a + 2}\\0&0&1&- 1&0\end{array}\right),
$$

$\mathbf{AX} = \mathbf{B}$ 有唯一解， $X = A^{-1}B = \left[ \begin{array}{cc}1 & \frac{3a}{a + 2}\\ 0 & \frac{a - 4}{a + 2}\\ -1 & 0 \end{array} \right];$

当 $a = 1$ 时， $(\mathbf{A}\vdots \mathbf{B})\rightarrow \left( \begin{array}{ccc}1 & -1 & -1\\ 0 & 3 & 3\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left( \begin{array}{ccc}1 & 0 & 0\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right),$

由 $r(\mathbf{A}) = r(\mathbf{A} \mid \mathbf{B}) = 2 < 3$ 得 $\mathbf{AX} = \mathbf{B}$ 有无数个解，

令 $X = (X_{1},X_{2})$

由 $X_{1} = k_{1}\binom{0}{-1} + \binom{1}{-1} = \binom{1}{-k_{1} - 1},$ $X_{2} = k_{2}\binom{0}{-1} + \binom{1}{-1} = \binom{1}{-k_{2} - 1}$ 得

$\mathbf{X} = \left( \begin{array}{cc}1 & 1\\ -k_1 - 1 & -k_2 - 1\\ k_1 & k_2 \end{array} \right)(k_1,k_2$ 为任意常数）.

$a = -2$ 时， $(\mathbf{A}\mid \mathbf{B})\to \left( \begin{array}{cccc}1 & -1 & -1 & 2\\ 0 & 0 & 3 & -3\\ 0 & 0 & -3 & 3 \end{array} \right)\to \left( \begin{array}{cccc}1 & -1 & -1 & 2\\ 0 & 0 & 1 & -1\\ 0 & 0 & 0 & 0 \end{array} \right),$

因为 $r(\mathbf{A})\neq r(\mathbf{A}\vdots \mathbf{B})$ ，所以 $\mathbf{AX} = \mathbf{B}$ 无解.

方法二 $|\mathbf{A}| = \left| \begin{array}{ccc}1 & -1 & -1\\ 2 & a & 1\\ -1 & 1 & a \end{array} \right| = \left| \begin{array}{ccc}1 & -1 & -1\\ 0 & a + 2 & 3\\ 0 & 0 & a - 1 \end{array} \right| = (a + 2)(a - 1),$

当 $a \neq -2$ 且 $a \neq 1$ 时，因为 $r(\mathbf{A}) = r(\mathbf{A} \mid \mathbf{B}) = 3$ ，所以 $\mathbf{AX} = \mathbf{B}$ 有唯一解，

由 $(\mathbf{A}\vdots \mathbf{B})\rightarrow \left( \begin{array}{cccc}1 & -1 & -1 & 2 & 2\\ 0 & a + 2 & 3 & -3 & a - 4\\ 0 & 0 & 1 & -1 & 0 \end{array} \right)\rightarrow \left[ \begin{array}{cccc}1 & 0 & 0 & 1 & \frac{3a}{a + 2}\\ 0 & 1 & 0 & 0 & \frac{a - 4}{a + 2}\\ 0 & 0 & 1 & -1 & 0 \end{array} \right],$

得 $\mathbf{X} = \mathbf{A}^{-1}\mathbf{B} = \left[ \begin{array}{cc}1 & \frac{3a}{a + 2}\\ 0 & \frac{a - 4}{a + 2}\\ -1 & 0 \end{array} \right];$

当 $a = 1$ 时， $(A\mid B)\rightarrow \left( \begin{array}{rrrr}1 & -1 & -1 & 2 & 2\\ 0 & 3 & 3 & -3 & -3\\ 0 & 0 & 0 & 0 & 0 \end{array} \right)\rightarrow \left( \begin{array}{rrrr}1 & 0 & 0 & 1 & 1\\ 0 & 1 & 1 & -1 & -1\\ 0 & 0 & 0 & 0 & 0 \end{array} \right),$

由 $r(\mathbf{A}) = r(\mathbf{A} \vdots \mathbf{B}) = 2 < 3$ 得 $\mathbf{AX} = \mathbf{B}$ 有无数个解，

令 $X = (X_{1},X_{2})$

由 $X_{1} = k_{1}\left( \begin{array}{l}0\\ -1\\ 1 \end{array} \right) + \left( \begin{array}{l}1\\ -1\\ 0 \end{array} \right) = \left( \begin{array}{l}1\\ -k_{1} - 1\\ k_{1} \end{array} \right),$ $X_{2} = k_{2}\left( \begin{array}{l}0\\ -1\\ 1 \end{array} \right) + \left( \begin{array}{l}1\\ -1\\ 0 \end{array} \right) = \left( \begin{array}{l}1\\ -k_{2} - 1\\ k_{2} \end{array} \right)$ 得

$\pmb {X} = \left( \begin{array}{cc}1 & 1\\ -k_1 - 1 & -k_2 - 1\\ k_1 & k_2 \end{array} \right)(k_1,k_2$ 为任意常数）.

$a = -2$ 时， $(\mathbf{A}\mid \mathbf{B})\to \left( \begin{array}{ccc}1 & -1 & -1\\ 0 & 0 & 3\\ 0 & 0 & -3 \end{array} \right)\to \left( \begin{array}{ccc}1 & -1 & -1\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right),$

因为 $r(\mathbf{A})\neq r(\mathbf{A}\vdots \mathbf{B})$ ，所以 $\mathbf{AX} = \mathbf{B}$ 无解.

（21）【解】（I）由 $|\lambda E - A| = \left| \begin{array}{ccc}\lambda & 1 & -1\\ -2 & \lambda +3 & 0\\ 0 & 0 & \lambda \end{array} \right| = \lambda (\lambda +1)(\lambda +2) = 0$ 得

矩阵 $\mathbf{A}$ 的特征值为 $\lambda_{1} = -1, \lambda_{2} = -2, \lambda_{3} = 0$

将 $\lambda_{1} = -1$ 代入 $(\lambda E - A)X = 0$ ，由 $-E - A = \begin{pmatrix} -1 & 1 & -1 \\ -2 & 2 & 0 \\ 0 & 0 & -1 \end{pmatrix} \rightarrow \begin{pmatrix} 1 & -1 & 0 \\ 0 & 0 & 1 \\ 0 & 0 & 0 \end{pmatrix}$ 得 $\lambda_{1} = -1$ 对

应的特征向量为 $\xi_{1} = \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix}$

将 $\lambda_{2} = -2$ 代入 $(\lambda E - A)X = 0$ ，由 $-2E - A = \begin{pmatrix} -2 & 1 & -1 \\ -2 & 1 & 0 \\ 0 & 0 & -2 \end{pmatrix} \rightarrow \begin{bmatrix} 1 & -\frac{1}{2} & 0 \\ 0 & 0 & 1 \\ 0 & 0 & 0 \end{bmatrix}$ 得

$\lambda_{2} = -2$ 对应的特征向量为 $\xi_{2} = \begin{pmatrix} 1 \\ 2 \\ 0 \end{pmatrix}$

将 $\lambda_{3} = 0$ 代入 $(\lambda E - A)X = 0$ ，由 $-A = \begin{pmatrix} 0 & 1 & -1 \\ -2 & 3 & 0 \\ 0 & 0 & 0 \end{pmatrix} \rightarrow \begin{bmatrix} 1 & 0 & -\frac{3}{2} \\ 0 & 1 & -1 \\ 0 & 0 & 0 \end{bmatrix}$ 得 $\lambda_{3} = 0$ 对应

的特征向量为 $\xi_{3} = \begin{pmatrix} 3\\ 2\\ 2 \end{pmatrix} .$

令 $\pmb{P} = \begin{pmatrix} 1 & 1 & 3 \\ 1 & 2 & 2 \\ 0 & 0 & 2 \end{pmatrix}$ , 由 $\pmb{P}^{-1}\pmb{A}\pmb{P} = \begin{pmatrix} -1 & 0 & 0 \\ 0 & -2 & 0 \\ 0 & 0 & 0 \end{pmatrix}$ 得

$$
\begin{array}{l} \boldsymbol {A} ^ {9 9} = \boldsymbol {P} \left( \begin{array}{c c c} (- 1) ^ {9 9} & 0 & 0 \\ 0 & (- 2) ^ {9 9} & 0 \\ 0 & 0 & 0 \end{array} \right) \boldsymbol {P} ^ {- 1} = \left( \begin{array}{c c c} 1 & 1 & 3 \\ 1 & 2 & 2 \\ 0 & 0 & 2 \end{array} \right) \left( \begin{array}{c c c} (- 1) ^ {9 9} & 0 & 0 \\ 0 & (- 2) ^ {9 9} & 0 \\ 0 & 0 & 0 \end{array} \right) \left( \begin{array}{c c c} 2 & - 1 & - 2 \\ - 1 & 1 & \frac {1}{2} \\ 0 & 0 & \frac {1}{2} \end{array} \right) \\ = \left( \begin{array}{c c c} 2 ^ {9 9} - 2 & 1 - 2 ^ {9 9} & 2 - 2 ^ {9 8} \\ 2 ^ {1 0 0} - 2 & 1 - 2 ^ {1 0 0} & 2 - 2 ^ {9 9} \\ 0 & 0 & 0 \end{array} \right). \\ \end{array}
$$

（Ⅱ）由 $\pmb{B}^{2} = \pmb{BA}$ 得 $\pmb{B}^{100} = \pmb{B}^{98}\pmb{B}^{2} = \pmb{B}^{99}\pmb{A} = \dots = \pmb{BA}^{99}$

即 $(\pmb{\beta}_1, \pmb{\beta}_2, \pmb{\beta}_3) = (\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3)\left( \begin{array}{ccc} 2^{99} - 2 & 1 - 2^{99} & 2 - 2^{98} \\ 2^{100} - 2 & 1 - 2^{100} & 2 - 2^{99} \\ 0 & 0 & 0 \end{array} \right),$

$\begin{array}{l}\pmb {\beta}_1 = (2^{99} - 2)\pmb {\alpha}_1 + (2^{100} - 2)\pmb {\alpha}_2 + 0\pmb {\alpha}_3,\\ \pmb {\beta}_2 = (1 - 2^{99})\pmb {\alpha}_1 + (1 - 2^{100})\pmb {\alpha}_2 + 0\pmb {\alpha}_3,\\ \pmb {\beta}_3 = (2 - 2^{98})\pmb {\alpha}_1 + (2 - 2^{99})\pmb {\alpha}_2 + 0\pmb {\alpha}_3. \end{array}$ 故

（22）【解】（I）区域 $D$ 的面积为 $A = \int_{0}^{1}(\sqrt{x} -x^{2})\mathrm{d}x = \frac{2}{3} -\frac{1}{3} = \frac{1}{3},$

随机变量 $(X,Y)$ 的联合密度为 $f(x,y) = \left\{ \begin{array}{ll}3, & (x,y)\in D,\\ 0, & (x,y)\notin D. \end{array} \right.$

（Ⅱ）设 $(U,X)$ 的联合分布函数为 $G(u,x)$

$$
G \left(0, \frac {1}{2}\right) = P \left\{U \leqslant 0, X \leqslant \frac {1}{2} \right\} = P \left\{X > Y, X \leqslant \frac {1}{2} \right\} = \int_ {0} ^ {\frac {1}{2}} d x \int_ {x ^ {2}} ^ {x} 3 d y = \frac {1}{4},
$$

$$
P \{U \leqslant 0 \} = P \{X > Y \} = \int_ {0} ^ {1} \mathrm {d} x \int_ {x ^ {2}} ^ {x} 3 \mathrm {d} y = \frac {1}{2},
$$

$$
P \left\{X \leqslant \frac {1}{2} \right\} = \int_ {0} ^ {\frac {1}{2}} d x \int_ {x ^ {2}} ^ {\sqrt {x}} 3 d y = \frac {\sqrt {2}}{2} - \frac {1}{8},
$$

因为 $\frac{1}{4} \neq \frac{1}{2} \times \left(\frac{\sqrt{2}}{2} - \frac{1}{8}\right)$ , 所以 $U$ 与 $X$ 不独立.

（Ⅲ）当 $z < 0$ 时， $F(z) = 0$

当 $0 \leqslant z < 1$ 时，

$$
F (z) = P \{Z \leqslant z \} = P \{U = 0, X \leqslant z \} = P \{X > Y, X \leqslant z \} = \int_ {0} ^ {z} d x \int_ {x ^ {2}} ^ {x} 3 d y = \frac {3}{2} z ^ {2} - z ^ {3};
$$

当 $1 \leqslant z < 2$ 时，

$$
\begin{array}{l} F (z) = P \{U + X \leqslant z \} = P \{U = 0, X \leqslant z \} + P \{U = 1, X \leqslant z - 1 \} \\ = \frac {1}{2} + 2 (z - 1) ^ {\frac {3}{2}} - \frac {3}{2} (z - 1) ^ {2}; \\ \end{array}
$$

当 $z \geqslant 2$ 时， $F(z) = 1$

故 $F(z) = \left\{ \begin{array}{ll}0, & z <   0,\\ \frac{3}{2} z^2 -z^3, & 0\leqslant z <   1,\\ \frac{1}{2} +2(z - 1)^{\frac{3}{2}} - \frac{3}{2} (z - 1)^2, & 1\leqslant z <   2,\\ 1, & z\geqslant 2. \end{array} \right.$

(23)【解】（I）总体 $X$ 的分布函数为 $F(x) = \int_{-\infty}^{x}f(t)\mathrm{d}t.$

当 $x < 0$ 时， $F(x) = 0$

当 $x \geqslant \theta$ 时， $F(x) = 1$

当 $0 \leqslant x < \theta$ 时， $F(x) = \int_{0}^{x} \frac{3x^2}{\theta^3} \, \mathrm{d}x = \frac{x^3}{\theta^3}$ ，

即 $F(x) = \left\{ \begin{array}{ll}0, & x <   0,\\ \frac{x^3}{\theta^3}, & 0\leqslant x <   \theta ,\\ 1, & x\geqslant \theta . \end{array} \right.$

设 $T$ 的分布函数为 $F_{T}(t)$ ，则

$$
\begin{array}{l} F _ {T} (t) = P \{T \leqslant t \} = P \{\max  \left\{X _ {1}, X _ {2}, X _ {3} \right\} \leqslant t \} \\ = P \left\{X _ {1} \leqslant t, X _ {2} \leqslant t, X _ {3} \leqslant t \right\} \\ = P \left\{X _ {1} \leqslant t \right\} P \left\{X _ {2} \leqslant t \right\} P \left\{X _ {3} \leqslant t \right\} \\ = P ^ {3} \{X \leqslant t \} = F ^ {3} (t) = \left\{ \begin{array}{l l} 0, & t <   0, \\ \frac {t ^ {9}}{\theta^ {9}}, & 0 \leqslant t <   \theta , \\ 1, & t \geqslant \theta . \end{array} \right. \\ \end{array}
$$

随机变量 $T$ 的概率密度为 $f_{T}(t) = \begin{cases} \frac{9t^{8}}{\theta^{9}}, & 0 < t < \theta, \\ 0, & \text{其他.} \end{cases}$

$(\mathrm{II})E(aT) = aE(T) = a\int_{0}^{\theta}t\cdot \frac{9t^{8}}{\theta^{9}}\mathrm{d}t = \frac{9a}{10}\theta ,$

由 $E(aT) = \theta$ 得 $a = \frac{10}{9}$ ，即当 $a = \frac{10}{9}$ 时， $aT$ 为参数 $\theta$ 的无偏估计.