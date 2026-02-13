# 1989年数学（一）真题解析

# 一、填空题

(1)【答案】 -1.

【解】 $\lim_{h\to 0}\frac{f(3 - h) - f(3)}{2h} = -\frac{1}{2}\lim_{h\to 0}\frac{f(3 - h) - f(3)}{-h} = -\frac{1}{2} f'(3) = -1.$

（2）【答案】 $x - 1$

【解】令 $A = \int_{0}^{1} f(x) \, \mathrm{d}x$ ，则 $f(x) = x + 2A$ ，对此等式两边从0到1积分得 $A = \frac{1}{2} + 2A$ ，解得 $A = -\frac{1}{2}$ ，故 $f(x) = x - 1$ 。

（3）【答案】 $\pi$

【解】 方法一 $\int_{L}(x^{2} + y^{2})\mathrm{d}s = \int_{L}\mathrm{d}s = \pi .$

方法二 令 $\left\{ \begin{array}{l}x = \cos t,\\ y = \sin t \end{array} \right.$ （ $\pi \leqslant t\leqslant 2\pi$ ，则

$$
\int_ {L} \left(x ^ {2} + y ^ {2}\right) d s = \int_ {\pi} ^ {2 \pi} \left(\cos^ {2} t + \sin^ {2} t\right) \cdot \sqrt {(- \sin t) ^ {2} + \cos^ {2} t} d t = \pi .
$$

（4）【答案】2.

【解】由 $\operatorname{div} u = \frac{\partial (xy^2)}{\partial x} + \frac{\partial (ye^z)}{\partial y} + \frac{\partial [x\ln(1 + z^2)]}{\partial z} = y^2 + e^z + \frac{2xz}{1 + z^2},$

得 $\operatorname{div} u\bigg|_{(1,1,0)} = 2.$

(5)【答案】 $\left( \begin{array}{ccc}1 & 0 & 0\\ -\frac{1}{2} & \frac{1}{2} & 0\\ 0 & 0 & 1 \end{array} \right).$

【解】 方法一 $A - 2E = \begin{pmatrix} 1 & 0 & 0\\ 1 & 2 & 0\\ 0 & 0 & 1 \end{pmatrix} ,$

由 $\left( \begin{array}{cccccc}1 & 0 & 0 & 1 & 0 & 0\\ 1 & 2 & 0 & 0 & 1 & 0\\ 0 & 0 & 1 & 0 & 0 & 1 \end{array} \right)\to \left( \begin{array}{cccccc}1 & 0 & 0 & 1 & 0 & 0\\ 0 & 2 & 0 & -1 & 1 & 0\\ 0 & 0 & 1 & 0 & 0 & 1 \end{array} \right)\to \left( \begin{array}{cccccc}1 & 0 & 0 & 1 & 0 & 0\\ 0 & 1 & 0 & -\frac{1}{2} & \frac{1}{2} & 0\\ 0 & 0 & 1 & 0 & 0 & 1 \end{array} \right)$ ，得

$$
(\mathbf {A} - 2 \mathbf {E}) ^ {- 1} = \left( \begin{array}{c c c} 1 & 0 & 0 \\ - \frac {1}{2} & \frac {1}{2} & 0 \\ 0 & 0 & 1 \end{array} \right).
$$

方法二 $\mathbf{A} - 2\mathbf{E} = \begin{pmatrix} 1 & 0 & 0\\ 1 & 2 & 0\\ 0 & 0 & 1 \end{pmatrix} = \begin{pmatrix} \mathbf{B} & \mathbf{O}\\ \mathbf{O} & \mathbf{C} \end{pmatrix}$ ，其中 $\pmb {B} = \left( \begin{array}{ll}1 & 0\\ 1 & 2 \end{array} \right),\pmb {C} = (1)$

由 $(\pmb {B}\vdots \pmb {E}) = \left( \begin{array}{lll}1 & 0 & 1 & 0\\ 1 & 2 & 0 & 1 \end{array} \right)\rightarrow \left( \begin{array}{lll}1 & 0 & 1 & 0\\ 0 & 2 & -1 & 1 \end{array} \right)\rightarrow \left( \begin{array}{lll}1 & 0 & 1 & 0\\ 0 & 1 & -\frac{1}{2} & \frac{1}{2} \end{array} \right)$ 得

$$
\pmb {B} ^ {- 1} = \left( \begin{array}{c c} {{1}} & {{0}} \\ {{-   \frac {1}{2}}} & {{\frac {1}{2}}} \end{array} \right), \text {故} (\pmb {A} - 2 \pmb {E}) ^ {- 1} = \left( \begin{array}{c c} {{\pmb {B} ^ {- 1}}} & {{\pmb {O}}} \\ {{\pmb {O}}} & {{\pmb {C} ^ {- 1}}} \end{array} \right) = \left( \begin{array}{c c c} {{1}} & {{0}} & {{0}} \\ {{-   \frac {1}{2}}} & {{\frac {1}{2}}} & {{0}} \\ {{0}} & {{0}} & {{1}} \end{array} \right).
$$

# 二、选择题

(1)【答案】 (A).

【解】由 $\lim_{x\to \infty}x\sin{\frac{1}{x}} = \lim_{x\to \infty}\frac{\sin{\frac{1}{x}}}{\frac{1}{x}} = 1$ ，得 $y = 1$ 为水平渐近线；

由 $\lim_{x\to 0}x\sin{\frac{1}{x}} = 0$ ，得曲线 $y = x\sin {\frac{1}{x}}$ 无铅直渐近线，应选(A).

(2)【答案】 (C).

【解】设点 $P$ 的坐标为 $(x_0, y_0, 4 - x_0^2 - y_0^2)$ ，该点法向量为 $\pmb{n} = \{2x_0, 2y_0, 1\}$ 由 $\frac{2x_0}{2} = \frac{2y_0}{2} = \frac{1}{1}$ 得 $x_0 = 1, y_0 = 1$ ，故所求的点为 $(1, 1, 2)$ ，应选(C).

(3)【答案】 (D).

【解】显然 $y_{1} - y_{3},y_{2} - y_{3}$ 为 $y^{\prime \prime} + p(x)y^{\prime} + q(x)y = 0$ 的两个线性无关解，

故 $y^{\prime \prime} + p(x)y^{\prime} + q(x)y = f(x)$ 的通解为

$$
y = C _ {1} \left(y _ {1} - y _ {3}\right) + C _ {2} \left(y _ {2} - y _ {3}\right) + y _ {3} = C _ {1} y _ {1} + C _ {2} y _ {2} + \left(1 - C _ {1} - C _ {2}\right) y _ {3},
$$

应选(D).

(4)【答案】 (B).

【解】对 $f(x)$ 进行奇延拓，将 $f(x)$ 展成正弦级数，则 $S\left(-\frac{1}{2}\right) = -S\left(\frac{1}{2}\right)$ ，因为 $x = \frac{1}{2}$ 为函数 $f(x)$ 的连续点，所以 $S = \left(\frac{1}{2}\right) = f\left(\frac{1}{2}\right) = \frac{1}{4}$ ，故 $S\left(-\frac{1}{2}\right) = -\frac{1}{4}$ ，应选(B).

（5）【答案】 (C).

【解】方法一 因为 $|\mathbf{A}| = 0$ ，所以 $r(\mathbf{A}) < 4$ ，从而矩阵 $\mathbf{A}$ 的列向量组线性相关，即必有一列可由其余列线性表示，应选(C).

方法二 取 $\mathbf{A} = \begin{bmatrix} 1 & 0 & 1 & 0\\ 0 & 1 & 1 & 0\\ 0 & 0 & 0 & 0\\ 0 & 0 & 0 & 1 \end{bmatrix}$ ，显然 $|\mathbf{A}| = 0$

矩阵 $\mathbf{A}$ 任何一列元素都不全为零，任何两列都不成比例，第4列不是第1,2,3列的线性组合，即排除(A)(B)(D)，应选(C).

三、

(1)【解】 $\frac{\partial z}{\partial x} = 2f' + g_1' + yg_2'$ , $\frac{\partial^2z}{\partial x\partial y} = -2f'' + xg_{12}'' + g_2' + xyg_{22}''.$

(2)【解】 方法一 $P = xy^{2}$ ， $Q = \varphi (x)y$

因为曲线积分与路径无关，所以 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$ 即 $\varphi^{\prime}(x) = 2x$

解得 $\varphi (x) = x^{2} + C$ ，由 $\varphi (0) = 0$ 得 $C = 0$ ，故 $\varphi (x) = x^2$

$$
\int_ {(0, 0)} ^ {(1, 1)} x y ^ {2} \mathrm {d} x + \varphi (x) y \mathrm {d} y = \int_ {(0, 0)} ^ {(1, 1)} x y ^ {2} \mathrm {d} x + x ^ {2} y \mathrm {d} y = \int_ {0} ^ {1} 0 \mathrm {d} x + \int_ {0} ^ {1} y \mathrm {d} y = \frac {1}{2}.
$$

方法二 $P = xy^{2},Q = \varphi (x)y,$

由 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$ 得 $\varphi^{\prime}(x) = 2x$

解得 $\varphi (x) = x^{2} + C$ ，由 $\varphi (0) = 0$ 得 $C = 0$ ，故 $\varphi (x) = x^2$

$$
\int_ {(0, 0)} ^ {(1, 1)} x y ^ {2} \mathrm {d} x + \varphi (x) y \mathrm {d} y = \int_ {(0, 0)} ^ {(1, 1)} x y ^ {2} \mathrm {d} x + x ^ {2} y \mathrm {d} y = \int_ {(0, 0)} ^ {(1, 1)} \mathrm {d} \left(\frac {1}{2} x ^ {2} y ^ {2}\right) = \frac {1}{2} x ^ {2} y ^ {2} \Bigg | _ {(0, 0)} ^ {(1, 1)} = \frac {1}{2}.
$$

（3）【解】 方法一

由 $\sqrt{x^2 + y^2} = \sqrt{1 - x^2 - y^2}$ 得 $\Omega$ 在 $xOy$ 平面上的投影区域为 $D: x^2 + y^2 \leqslant \frac{1}{2}$ ,

由对称性得 $\iiint_{\Omega} x \, \mathrm{d}v = 0$

于是 $\iiint_{\Omega}(x + z)\mathrm{d}v = \iiint_{\Omega}z\mathrm{d}v = \iint_{D}\mathrm{d}x\mathrm{d}y\int \limits_{\sqrt{x^2 + y^2}}^{\sqrt{1 - x^2 - y^2}}z\mathrm{d}z$

$$
\begin{array}{l} = \frac {1}{2} \iint_ {D} (1 - 2 x ^ {2} - 2 y ^ {2}) \mathrm {d} x \mathrm {d} y = \iint_ {D} \left(\frac {1}{2} - x ^ {2} - y ^ {2}\right) \mathrm {d} x \mathrm {d} y \\ = \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {\sqrt {\frac {1}{2}}} r \left(\frac {1}{2} - r ^ {2}\right) \mathrm {d} r = \frac {\pi}{8}. \\ \end{array}
$$

方法二

由对称性得 $\iiint_{\Omega} x \, \mathrm{d}v = 0$ ，即 $\iiint_{\Omega} (x + z) \, \mathrm{d}v = \iiint_{\Omega} z \, \mathrm{d}v$

令 $\left\{ \begin{array}{l}x = r\cos \theta \sin \varphi ,\\ y = r\sin \theta \sin \varphi ,\\ z = r\cos \varphi \end{array} \right.$ ， $0\leqslant \theta \leqslant 2\pi ,0\leqslant \varphi \leqslant \frac{\pi}{4},0\leqslant r\leqslant 1)$ ，则

$$
\begin{array}{l} \iiint_ {a} z \mathrm {d} v = \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {\frac {\pi}{4}} \mathrm {d} \varphi \int_ {0} ^ {1} r \cos \varphi \cdot r ^ {2} \sin \varphi \mathrm {d} r \\ = 2 \pi \int_ {0} ^ {\frac {\pi}{4}} \cos \varphi \cdot \sin \varphi d \varphi \int_ {0} ^ {1} r ^ {3} d r = \left. \frac {\pi}{2} \cdot \frac {1}{2} \sin^ {2} \varphi \right| _ {0} ^ {\frac {\pi}{4}} = \frac {\pi}{8}. \\ \end{array}
$$

四、【解】 $f^{\prime}(x) = \frac{1}{1 + \left(\frac{1 + x}{1 - x}\right)^{2}} \cdot \frac{(1 - x) + (1 + x)}{(1 - x)^{2}} = \frac{1}{1 + x^{2}},$

$f^{\prime}(x)$ 的幂级数为 $f^{\prime}(x) = \sum_{n = 0}^{\infty}(-1)^{n}x^{2n}(-1 <   x <   1),$

再由 $f(x) - f(0) = \int_0^x f'(t)\mathrm{d}t = \sum_{n = 0}^\infty \frac{(-1)^n}{2n + 1} x^{2n + 1}$ 得

$$
f (x) = f (0) + \int_ {0} ^ {x} f ^ {\prime} (t) d t = \frac {\pi}{4} + \sum_ {n = 0} ^ {\infty} \frac {(- 1) ^ {n}}{2 n + 1} x ^ {2 n + 1}.
$$

注意到 $x = -1$ 时 $f(x)$ 有定义且级数 $\frac{\pi}{4} +\sum_{n = 0}^{\infty}\frac{(-1)^n}{2n + 1} x^{2n + 1}$ 收敛，

故 $f(x)$ 关于 $x$ 的幂级数为 $f(x) = \frac{\pi}{4} +\sum_{n = 0}^{\infty}\frac{(-1)^n}{2n + 1} x^{2n + 1}(-1\leqslant x <   1).$

五、【解】 由 $\int_0^x (x - t)f(t)\mathrm{d}t = x\int_0^x f(t)\mathrm{d}t - \int_0^x tf(t)\mathrm{d}t$ 得

$$
f (x) = \sin x - x \int_ {0} ^ {x} f (t) d t + \int_ {0} ^ {x} t f (t) d t,
$$

两边求导得 $f^{\prime}(x) = \cos x - \int_{0}^{x}f(t)\mathrm{d}t$ ，或 $f^{\prime}(x) + \int_{0}^{x}f(t)\mathrm{d}t = \cos x,$

$f^{\prime}(x) + \int_{0}^{x}f(t)\mathrm{d}t = \cos x$ 两边再求导得

$$
f ^ {\prime \prime} (x) + f (x) = - \sin x,
$$

特征方程为 $\lambda^2 + 1 = 0$ ，特征根为 $\lambda_{1,2} = \pm \mathrm{i}$ ，

$f^{\prime \prime}(x) + f(x) = 0$ 的通解为 $f(x) = C_{1}\cos x + C_{2}\sin x$

令 $f''(x) + f(x) = -\sin x$ 的特解为 $f_0(x) = x(a\cos x + b\sin x)$

代入得 $a = \frac{1}{2}, b = 0$

则原方程的通解为 $f(x) = C_{1}\cos x + C_{2}\sin x + \frac{x}{2}\cos x$

再由 $f(0) = 0, f'(0) = 1$ ，得 $C_1 = 0, C_2 = \frac{1}{2}$ ，故 $f(x) = \frac{1}{2} \sin x + \frac{x}{2} \cos x$ .

六、【证明】 $\int_0^\pi \sqrt{1 - \cos 2x}\mathrm{d}x = \int_0^\pi \sqrt{2\sin^2x}\mathrm{d}x = \sqrt{2}\int_0^\pi \sin x\mathrm{d}x = 2\sqrt{2},$

原方程即为 $\ln x = \frac{x}{\mathrm{e}} - 2\sqrt{2}$

令 $f(x) = \ln x - \frac{x}{\mathrm{e}} + 2\sqrt{2}$ ，由 $f'(x) = \frac{1}{x} - \frac{1}{\mathrm{e}} = 0$ ，得 $x = \mathrm{e}$ ，

$f^{\prime \prime}(x) = -\frac{1}{x^2}$ ，由 $f^{\prime \prime}(\mathrm{e}) = -\frac{1}{\mathrm{e}^2} < 0$ 得 $x = \mathrm{e}$ 为 $f(x)$ 的最大值点，

最大值 $M = f(\mathrm{e}) = 2\sqrt{2} >0$

因为 $\lim_{x\to +\infty}f(x) = -\infty ,\lim_{x\to +\infty}f(x) = -\infty$ ，所以 $f(x)$ 在 $(0, + \infty)$ 内有且仅有两个零点，

从而方程 $\ln x = \frac{x}{e} -\int_{0}^{\pi}\sqrt{1 - \cos 2x}\mathrm{d}x$ 在区间 $(0, + \infty)$ 内有且仅有两个根.

七、【解】 $\overline{A} = \begin{pmatrix} 1 & 0 & 1 & \lambda \\ 4 & 1 & 2 & \lambda + 2 \\ 6 & 1 & 4 & 2\lambda + 3 \end{pmatrix} \rightarrow \begin{pmatrix} 1 & 0 & 1 & \lambda \\ 0 & 1 & -2 & 2 - 3\lambda \\ 0 & 1 & -2 & 3 - 4\lambda \end{pmatrix} \rightarrow \begin{pmatrix} 1 & 0 & 1 & \lambda \\ 0 & 1 & -2 & 2 - 3\lambda \\ 0 & 0 & 0 & 1 - \lambda \end{pmatrix},$

当 $\lambda = 1$ 时，方程组有解，

再由 $\lambda = 1$ 时 $\overline{A} \rightarrow \left( \begin{array}{cccc}1 & 0 & 1 & 1\\ 0 & 1 & -2 & -1\\ 0 & 0 & 0 & 0 \end{array} \right)$ ，得方程组的通解为

$$
\pmb {X} = k {\binom {- 1} {2}} + {\binom {1} {- 1}} \quad (k   \text {为 任 意 常 数}).
$$

八、【证明】（1）因为 $\pmb{A}$ 可逆，所以 $\lambda \neq 0$ ，设 $\pmb{A}$ 的属于特征值 $\lambda$ 的特征向量为 $\alpha$ ，即 $A\alpha = \lambda \alpha$ 将 $A\alpha = \lambda \alpha$ 两边左乘 $A^{-1}$ ，得 $A^{-1}A\alpha = \lambda A^{-1}\alpha$

于是 $A^{-1}\pmb {\alpha} = \frac{1}{\lambda}\pmb{\alpha}$ ，即 $\frac{1}{\lambda}$ 为 $A^{-1}$ 的特征值

（2）因为 $A^{*} = |A|A^{-1}$ ，所以 $A^{*}\alpha = |A|A^{-1}\alpha = \frac{|A|}{\lambda}\alpha$

即 $\frac{|A|}{\lambda}$ 为 $A$ 的伴随矩阵 $A^{*}$ 的特征值

九、【解】设 $\Sigma : x^2 + y^2 + (z - a)^2 = R^2$ （ $0 < R < 2a$ ），

由 $\left\{ \begin{array}{l}x^{2} + y^{2} + z^{2} = a^{2},\\ x^{2} + y^{2} + (z - a)^{2} = R^{2} \end{array} \right.$ 得 $x^{2} + y^{2} = R^{2} - \frac{R^{4}}{4a^{2}},$

位于定球面 $x^{2} + y^{2} + z^{2} = a^{2}$ 内的曲面为

$$
\Sigma : z = a - \sqrt {R ^ {2} - x ^ {2} - y ^ {2}},
$$

其中， $(x,y)\in D_{xy}\left(x^{2} + y^{2}\leqslant R^{2} - \frac{R^{4}}{4a^{2}}\right),$

$$
\begin{array}{l} S = \iint_ {D _ {x y}} \sqrt {1 + \left(\frac {\partial z}{\partial x}\right) ^ {2} + \left(\frac {\partial z}{\partial y}\right) ^ {2}} d x d y = R \iint_ {D _ {x y}} \frac {d x d y}{\sqrt {R ^ {2} - x ^ {2} - y ^ {2}}} \\ = 2 \pi R \int_ {0} ^ {\sqrt {R ^ {2} - \frac {R ^ {4}}{4 a ^ {2}}}} \frac {r \mathrm {d} r}{\sqrt {R ^ {2} - r ^ {2}}} = - 2 \pi R \int_ {0} ^ {\sqrt {R ^ {2} - \frac {R ^ {4}}{4 a ^ {2}}}} \frac {\mathrm {d} (R ^ {2} - r ^ {2})}{2 \sqrt {R ^ {2} - r ^ {2}}} \\ = 2 \pi \left(R ^ {2} - \frac {R ^ {3}}{2 a}\right), \\ \end{array}
$$

由 $\frac{\mathrm{d}S}{\mathrm{d}R} = 2\pi \left(2R - \frac{3R^2}{2a}\right) = 0$ ，得 $R = \frac{4}{3} a$

当 $0 < R < \frac{4}{3} a$ 时， $\frac{\mathrm{d}S}{\mathrm{d}R} > 0$ ；当 $R > \frac{4}{3} a$ 时， $\frac{\mathrm{d}S}{\mathrm{d}R} < 0$ ，故当 $R = \frac{4}{3} a$ 时， $\Sigma$ 位于定球面内的面积最大。十、填空题

（1）【答案】 0.7.

【解】由 $P(B\mid A) = 0.8$ ，即 $\frac{P(AB)}{P(A)} = 0.8$ 得 $P(AB) = 0.4$

于是 $P(A \cup B) = P(A) + P(B) - P(AB) = 0.5 + 0.6 - 0.4 = 0.7.$

（2）【答案】 0.75.

【解】设 $A = \{$ 甲命中目标 $\}$ ， $B = \{$ 乙命中目标 $\}$ ， $C = \{$ 目标被命中 $\}$ ，

$P(A) = 0.6, P(B) = 0.5$ ，且 $C = A + B$ ，则

$$
\begin{array}{l} P (A \mid C) = \frac {P (A C)}{P (C)} = \frac {P (A)}{P (A + B)} \\ = \frac {P (A)}{P (A) + P (B) - P (A) P (B)} = \frac {0 . 6}{0 . 6 + 0 . 5 - 0 . 3} = 0. 7 5. \\ \end{array}
$$

（3）【答案】 0.8.

【解】随机变量 $\xi$ 的概率密度为 $f(x) = \left\{ \begin{array}{ll} \frac{1}{5}, & 1 < x < 6, \\ 0, & \text{其他}, \end{array} \right.$

当 $\Delta = \xi^2 - 4 \geqslant 0$ ，即 $\xi \leqslant -2$ 或 $\xi \geqslant 2$ 时，方程 $x^2 + \xi x + 1 = 0$ 有实根，

则方程 $x^{2} + \xi x + 1 = 0$ 有实根的概率为 $P\{\xi \geqslant 2\} = \int_{2}^{6}\frac{1}{5}\mathrm{d}x = 0.8.$

# 十一、【解】因为相互独立的正态随机变量的线性组合仍服从正态分布，

所以随机变量 $Z = 2X - Y + 3$ 服从正态分布，

又因为 $E(Z) = 2E(X) - E(Y) + 3 = 5$ ， $D(Z) = 4D(X) + D(Y) = 9$

所以 $Z \sim N(5, 3^2)$

故随机变量 $Z$ 的概率密度为 $f_{Z}(z) = \frac{1}{3\sqrt{2\pi}}\mathrm{e}^{-\frac{(z - 5)^{2}}{18}}, - \infty < z + \infty .$