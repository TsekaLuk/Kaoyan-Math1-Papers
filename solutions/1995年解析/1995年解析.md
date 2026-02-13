# 1995年数学(一）真题解析

# 一、填空题

(1)【答案】 $\mathrm{e}^6$

【解】 $\lim_{x\to 0}(1 + 3x)^{\frac{2}{\sin x}} = \lim_{x\to 0}\left[(1 + 3x)^{\frac{1}{3x}}\right]^{\frac{6x}{\sin x}} = \mathrm{e}^{6}.$

(2)【答案】 $-\int_{0}^{x^{2}}\cos t^{2}\mathrm{d}t - 2x^{2}\cos x^{4}.$

【解】 $\frac{\mathrm{d}}{\mathrm{d}x}\int_{x^2}^{0}x\cos t^2\mathrm{d}t = -\frac{\mathrm{d}}{\mathrm{d}x}\left(x\int_0^{x^2}\cos t^2\mathrm{d}t\right) = -\int_0^{x^2}\cos t^2\mathrm{d}t - 2x^2\cos x^4.$

(3)【答案】 4.

【解】 $\left[(a + b) \times (b + c)\right] \cdot (c + a) = (a \times b + a \times c + b \times c) \cdot (c + a)$

$$
= (\boldsymbol {a} \times \boldsymbol {b}) \cdot \boldsymbol {c} + (\boldsymbol {b} \times \boldsymbol {c}) \cdot \boldsymbol {a} = 2 (\boldsymbol {a} \times \boldsymbol {b}) \cdot \boldsymbol {c} = 4.
$$

（4）【答案】 $\sqrt{3}$

【解】由 $\lim_{n\to \infty}\left|\frac{a_{n + 1}}{a_n}\right| = \lim_{n\to \infty}\frac{n + 1}{n}\cdot \left|\frac{2^n + (-3)^n}{2^{n + 1} + (-3)^{n + 1}}\right| = \frac{1}{3}$ 得收敛半径 $R = \sqrt{3}$

(5)【答案】 $\begin{pmatrix} 3 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 1 \end{pmatrix}$ .

【解】由 $A^{-1}BA = 6A + BA$ 得 $BA = 6A^2 + ABA$ ，然后右乘 $A^{-1}$ 得 $B = 6A + AB$ 解得 $B = 6(E - A)^{-1}A = 6[A^{-1}(E - A)]^{-1} = 6(A^{-1} - E)^{-1}$

由 $\mathbf{A}^{-1} - \mathbf{E} = \begin{pmatrix} 2 & 0 & 0 \\ 0 & 3 & 0 \\ 0 & 0 & 6 \end{pmatrix}$ , 得 $(\mathbf{A}^{-1} - \mathbf{E})^{-1} = \begin{bmatrix} \frac{1}{2} & 0 & 0 \\ 0 & \frac{1}{3} & 0 \\ 0 & 0 & \frac{1}{6} \end{bmatrix}$ , 故 $\mathbf{B} = \begin{pmatrix} 3 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 1 \end{pmatrix}$ .

# 二、选择题

（1）【答案】 (C).

【解】直线 $L$ 的方向向量为 $\pmb {s} = \{1,3,2\} \times \{2, - 1, - 10\} = \{-28,14, - 7\}$

$$
= - 7 \{4, - 2, 1 \},
$$

因为平面 $\pi$ 的法向量平行于 $L$ 的方向向量，所以 $L\perp \pi$ ，选(C).

(2)【答案】 (B).

【解】由拉格朗日中值定理得 $f(1) - f(0) = f'(c)$ ，其中 $0 < c < 1$

由 $f^{\prime \prime}(x) > 0$ 得 $f^{\prime}(x)$ 单调递增，再由 $0 < c < 1$ 得 $f^{\prime}(1) > f^{\prime}(c) > f^{\prime}(0)$ ，应选(B).

（3）【答案】 （A).

【解】 $F_{-}^{\prime}(0) = \lim_{x\to 0^{-}}\frac{F(x) - F(0)}{x} = \lim_{x\to 0^{-}}\frac{f(x)(1 - \sin x) - f(0)}{x}$

$$
= \lim  _ {x \rightarrow 0 ^ {-}} \left[ \frac {f (x) - f (0)}{x} - f (x) \cdot \frac {\sin x}{x} \right] = f ^ {\prime} (0) - f (0);
$$

$$
F _ {+} ^ {\prime} (0) = \lim  _ {x \rightarrow 0 ^ {+}} \frac {F (x) - F (0)}{x} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {f (x) (1 + \sin x) - f (0)}{x}
$$

$$
= \lim  _ {x \rightarrow 0 ^ {+}} \left[ \frac {f (x) - f (0)}{x} + f (x) \cdot \frac {\sin x}{x} \right] = f ^ {\prime} (0) + f (0),
$$

$F(x)$ 在 $x = 0$ 处可导的充分必要条件是 $f^{\prime}(0) - f(0) = f^{\prime}(0) + f(0)$ ，即 $f(0) = 0$ ，即 $f(0) = 0$ 是 $F(x)$ 在 $x = 0$ 处可导的充分必要条件，应选(A).

（4）【答案】 (C).

【解】由 $\left\{\ln \left(1 + \frac{1}{\sqrt{n}}\right)\right\}$ 单调递减且 $\lim_{n\to \infty}\ln \left(1 + \frac{1}{\sqrt{n}}\right) = 0$ 得 $\sum_{n = 1}^{\infty}u_n$ 收敛，

由 $u_{n}^{2} = \ln^{2}\left(1 + \frac{1}{\sqrt{n}}\right)\sim \frac{1}{n}$ 且 $\sum_{n = 1}^{\infty}\frac{1}{n}$ 发散得 $\sum_{n = 1}^{\infty}u_n^2$ 发散，应选(C).

（5）【答案】 (C).

【解】将 $\mathbf{A}$ 的第1行加到第3行，再将第1行与第2行对调得 $\mathbf{B}$ ，即

$\pmb{B} = \left( \begin{array}{lll}0 & 1 & 0\\ 1 & 0 & 0\\ 0 & 0 & 1 \end{array} \right)\left( \begin{array}{lll}1 & 0 & 0\\ 0 & 1 & 0\\ 1 & 0 & 1 \end{array} \right)\pmb {A} = \pmb{P}_1\pmb{P}_2\pmb {A}$ ，应选(C).

# 三、

(1)【解】 $u = f(x,y,z)$ 两边对 $\mathcal{X}$ 求导得

$$
\frac {\mathrm {d} u}{\mathrm {d} x} = f _ {1} ^ {\prime} + f _ {2} ^ {\prime} \cdot \frac {\mathrm {d} y}{\mathrm {d} x} + f _ {3} ^ {\prime} \cdot \frac {\mathrm {d} z}{\mathrm {d} x};
$$

$\varphi (x^{2},\mathrm{e}^{y},z) = 0$ 两边对 $x$ 求导得

$$
2 x \varphi_ {1} ^ {\prime} + \varphi_ {2} ^ {\prime} \cdot e ^ {y} \cdot \frac {d y}{d x} + \varphi_ {3} ^ {\prime} \cdot \frac {d z}{d x} = 0,
$$

又 $y = \sin x, \frac{\mathrm{dy}}{\mathrm{dx}} = \cos x$ ，解得 $\frac{\mathrm{dz}}{\mathrm{dx}} = -2x\frac{\varphi_1'}{\varphi_3'} -\frac{\varphi_2'}{\varphi_3'}\mathrm{e}^{\sin x}\cos x,$

故 $\frac{\mathrm{d}u}{\mathrm{d}x} = f_1' + f_2' \cdot \cos x - f_3' \cdot \left(2x\frac{\varphi_1'}{\varphi_3'} + \frac{\varphi_2'}{\varphi_3'}\mathrm{e}^{\sin x}\cos x\right)$ .

(2)【解】 方法一 令 $F(x) = \int_{0}^{x}f(t)\mathrm{d}t,F(1) = A$ ，则

$$
\begin{array}{l} \int_ {0} ^ {1} \mathrm {d} x \int_ {x} ^ {1} f (x) f (y) \mathrm {d} y = \int_ {0} ^ {1} f (x) \mathrm {d} x \int_ {x} ^ {1} f (y) \mathrm {d} y = \int_ {0} ^ {1} f (x) [ F (1) - F (x) ] \mathrm {d} x \\ = A \int_ {0} ^ {1} f (x) d x - \int_ {0} ^ {1} f (x) F (x) d x = A ^ {2} - \int_ {0} ^ {1} F (x) d F (x) \\ = A ^ {2} - \frac {1}{2} F ^ {2} (x) \Big | _ {0} ^ {1} = \frac {1}{2} A ^ {2}. \\ \end{array}
$$

方法二

$$
\int_ {0} ^ {1} \mathrm {d} x \int_ {x} ^ {1} f (x) f (y) \mathrm {d} y = \int_ {0} ^ {1} f (x) \mathrm {d} x \int_ {x} ^ {1} f (y) \mathrm {d} y,
$$

又 $\int_0^1 f(x)\mathrm{d}x\int_x^1 f(y)\mathrm{d}y = \int_0^1\mathrm{d}y\int_0^y f(x)f(y)\mathrm{d}x = \int_0^1\mathrm{d}x\int_0^x f(y)f(x)\mathrm{d}y$

$$
= \int_ {0} ^ {1} f (x) d x \int_ {0} ^ {x} f (y) d y,
$$

于是 $2\int_{0}^{1}\mathrm{d}x\int_{x}^{1}f(x)f(y)\mathrm{d}y = \int_{0}^{1}f(x)\mathrm{d}x\int_{x}^{1}f(y)\mathrm{d}y + \int_{0}^{1}f(x)\mathrm{d}x\int_{0}^{x}f(y)\mathrm{d}y$

$$
= \int_ {0} ^ {1} f (x) d x \int_ {0} ^ {1} f (y) d y = \left[ \int_ {0} ^ {1} f (x) d x \right] ^ {2} = A ^ {2},
$$

故 $\int_0^1\mathrm{d}x\int_x^1 f(x)f(y)\mathrm{d}y = \frac{1}{2} A^2.$

四、

(1)【解】 $\Sigma :z = \sqrt{x^2 + y^2}$ ，其中 $x^{2} + y^{2}\leqslant 2x$

$$
\frac {\partial z}{\partial x} = \frac {x}{\sqrt {x ^ {2} + y ^ {2}}}, \quad \frac {\partial z}{\partial y} = \frac {y}{\sqrt {x ^ {2} + y ^ {2}}},
$$

则 $\iint_{\Sigma} z \, \mathrm{d}S = \iint_{x^2 + y^2 \leqslant 2x} \sqrt{x^2 + y^2} \cdot \sqrt{1 + \frac{x^2}{x^2 + y^2} + \frac{y^2}{x^2 + y^2}} \, \mathrm{d}x \, \mathrm{d}y = \iint_{x^2 + y^2 \leqslant 2x} \sqrt{x^2 + y^2} \cdot \sqrt{2} \, \mathrm{d}x \, \mathrm{d}y$

$$
= \sqrt {2} \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} d \theta \int_ {0} ^ {2 \cos \theta} r ^ {2} d r = \frac {8}{3} \sqrt {2} \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} \cos^ {3} \theta d \theta = \frac {1 6}{3} \sqrt {2} \int_ {0} ^ {\frac {\pi}{2}} \cos^ {3} \theta d \theta = \frac {3 2}{9} \sqrt {2}.
$$

(2)【解】 将 $f(x)$ 进行偶延拓再进行周期延拓，则

$$
a _ {0} = \frac {2}{2} \int_ {0} ^ {2} f (x) \mathrm {d} x = \int_ {0} ^ {2} (x - 1) \mathrm {d} x = 0;
$$

$$
\begin{array}{l} a _ {n} = \frac {2}{2} \int_ {0} ^ {2} f (x) \cos \frac {n \pi x}{2} d x = \int_ {0} ^ {2} (x - 1) \cos \frac {n \pi x}{2} d x \\ = \frac {2}{n \pi} \int_ {0} ^ {2} (x - 1) d \left(\sin \frac {n \pi x}{2}\right) = \frac {2}{n \pi} (x - 1) \sin \frac {n \pi x}{2} \Bigg | _ {0} ^ {2} - \frac {2}{n \pi} \int_ {0} ^ {2} \sin \frac {n \pi x}{2} d x \\ = \frac {4}{n ^ {2} \pi^ {2}} \cos \frac {n \pi x}{2} \Big | _ {0} ^ {2} = \frac {4}{n ^ {2} \pi^ {2}} [ (- 1) ^ {n} - 1 ] = \left\{ \begin{array}{l l} - \frac {8}{n ^ {2} \pi^ {2}}, & n = 1, 3, 5, \dots , \\ 0, & n = 2, 4, 6, \dots , \end{array} \right. \\ \end{array}
$$

$b_{n} = 0, n = 1,2,3,\dots$ ，则

$x - 1 = -\frac{8}{\pi^2}\left(\frac{1}{1^2}\cos \frac{\pi x}{2} +\frac{1}{3^2}\cos \frac{3\pi x}{2} +\frac{1}{5^2}\cos \frac{5\pi x}{2} +\dots\right)$ ，其中 $0\leqslant x\leqslant 2$

# 五、【解】设 $M(x,y)$ 为 $L$ 上的任意一点， $L$ 上 $M$ 处的切线方程为

$$
Y - y = y ^ {\prime} (X - x),
$$

令 $X = 0$ 得 $Y = y - xy'$ ，即 $A(0, y - xy')$

$$
\left| \overline {{M A}} \right| = x \sqrt {1 + y ^ {\prime 2}}, \quad \left| \overline {{O A}} \right| = y - x y ^ {\prime},
$$

由 $|\overline{MA}| = |\overline{OA}|$ ，有

$$
\left| y - x y ^ {\prime} \right| = \sqrt {(x - 0) ^ {2} + (y - y + x y ^ {\prime}) ^ {2}},
$$

化简后得

$$
2 x y y ^ {\prime} - y ^ {2} + x ^ {2} = 0.
$$

再令 $z = y^2$ ，得 $\frac{\mathrm{d}z}{\mathrm{d}x} -\frac{z}{x} = -x$

解得

$$
z = \mathrm {e} ^ {\int \frac {1}{x} \mathrm {d} x} \left(- \int x \mathrm {e} ^ {\int - \frac {1}{x} \mathrm {d} x} \mathrm {d} x + C\right) = x (- x + C),
$$

即 $y^{2} = -x^{2} + Cx.$

由于所求曲线在第一象限内，知 $y > 0$ ，故

$$
y = \sqrt {C x - x ^ {2}}.
$$

将已知条件 $y\left(\frac{3}{2}\right) = \frac{3}{2}$ 代入上式，得 $C = 3$ ，于是曲线方程为

$$
y = \sqrt {3 x - x ^ {2}} (0 <   x <   3).
$$

六、【解】由 $\int_{L}2xy\mathrm{d}x + Q(x,y)\mathrm{d}y$ 与路径无关得 $\frac{\partial Q}{\partial x} = 2x$ ，则 $Q(x,y) = x^{2} + \varphi (y)$

$$
\int_ {(0, 0)} ^ {(t, 1)} 2 x y \mathrm {d} x + Q (x, y) \mathrm {d} y = \int_ {0} ^ {t} 0 \mathrm {d} x + \int_ {0} ^ {1} [ t ^ {2} + \varphi (y) ] \mathrm {d} y = t ^ {2} + \int_ {0} ^ {1} \varphi (y) \mathrm {d} y,
$$

$$
\int_ {(0, 0)} ^ {(1, t)} 2 x y \mathrm {d} x + Q (x, y) \mathrm {d} y = \int_ {0} ^ {1} 0 \mathrm {d} x + \int_ {0} ^ {t} [ 1 + \varphi (y) ] \mathrm {d} y = t + \int_ {0} ^ {t} \varphi (y) \mathrm {d} y,
$$

由 $t + \int_0^t\varphi (y)\mathrm{d}y = t^2 +\int_0^1\varphi (y)\mathrm{d}y$ 得 $\varphi (t) = 2t - 1$

故 $Q(x,y) = x^{2} + 2y - 1$

七、【证明】（1）（反证法）设存在 $c \in (a, b)$ ，使得 $g(c) = 0$

由罗尔定理，存在 $\xi_1\in (a,c),\xi_2\in (c,b)$ ，使得 $g^{\prime}(\xi_{1}) = g^{\prime}(\xi_{2}) = 0$

再由罗尔定理，存在 $\xi \in (a,b)$ ，使得 $g^{\prime \prime}(\xi) = 0$ ，矛盾，故在 $(a,b)$ 内 $g(x)\neq 0$

(2) 令 $\varphi(x) = f(x)g'(x) - f'(x)g(x)$ ,

则 $\varphi(a) = \varphi(b) = 0$ ，由罗尔定理知，存在 $\xi \in (a, b)$ ，使 $\varphi'(\xi) = 0$ ，即

$$
f (\xi) g ^ {\prime \prime} (\xi) - f ^ {\prime \prime} (\xi) g (\xi) = 0,
$$

因 $g(\xi)\neq 0,g^{\prime \prime}(\xi)\neq 0$ ，故得

$$
\frac {f (\xi)}{g (\xi)} = \frac {f ^ {\prime \prime} (\xi)}{g ^ {\prime \prime} (\xi)}, \quad \xi \in (a, b).
$$

八、【解】设 $\pmb {\xi} = (x_{1},x_{2},x_{3})^{\mathrm{T}}$ 为 $\lambda_{2} = \lambda_{3} = 1$ 对应的特征向量，

由 $\xi_1^{\mathrm{T}}\xi = 0$ 得 $x_{2} + x_{3} = 0$ ，则 $\lambda_{2} = \lambda_{3} = 1$ 对应的线性无关的特征向量为

$$
\pmb {\xi} _ {2} = \left( \begin{array}{c} 1 \\ 0 \\ 0 \end{array} \right), \quad \pmb {\xi} _ {3} = \left( \begin{array}{c} 0 \\ 1 \\ - 1 \end{array} \right),
$$

令 $\pmb{P} = \left( \begin{array}{rrr}0 & 1 & 0\\ 1 & 0 & 1\\ 1 & 0 & -1 \end{array} \right)$ ，由 $\pmb{P}^{-1}\pmb {A}\pmb {P} = \left( \begin{array}{rrr} - 1 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right)$ 得

$$
\mathbf {A} = \mathbf {P} \left( \begin{array}{c c c} - 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{array} \right) \mathbf {P} ^ {- 1} = \left( \begin{array}{c c c} 1 & 0 & 0 \\ 0 & 0 & - 1 \\ 0 & - 1 & 0 \end{array} \right).
$$

九、【解】方法一 由 $\mathbf{A}\mathbf{A}^{\mathrm{T}} = \mathbf{E}$ 得 $|\mathbf{A}|\cdot |\mathbf{A}^{\mathrm{T}}| = 1$ ，即 $|\mathbf{A}|^2 = 1$

再由 $|\mathbf{A}| < 0$ 得 $|\mathbf{A}| = -1$ .

于是 $|\mathbf{A} + \mathbf{E}| = |\mathbf{A} + \mathbf{A}\mathbf{A}^{\mathrm{T}}| = |\mathbf{A}|\cdot |\mathbf{E} + \mathbf{A}^{\mathrm{T}}| = -|\left(\mathbf{E} + \mathbf{A}\right)^{\mathrm{T}}| = -|\mathbf{E} + \mathbf{A}|$

故 $|\mathbf{E} + \mathbf{A}| = 0$

方法二 令 $AX = \lambda X(X\neq 0)$

由 $\mathbf{A}\mathbf{X} = \lambda \mathbf{X}$ 得 $\mathbf{X}^{\mathrm{T}}\mathbf{A}^{\mathrm{T}} = \lambda \mathbf{X}^{\mathrm{T}}$ ，两边右乘 $\mathbf{A}\mathbf{X}$ 得

$\mathbf{X}^{\mathrm{T}}\mathbf{A}^{\mathrm{T}}\cdot \mathbf{A}\mathbf{X} = \lambda \mathbf{X}^{\mathrm{T}}\cdot \mathbf{A}\mathbf{X}$ ，即 $\pmb {X}^{\mathrm{T}}\pmb {X} = \lambda^{2}\pmb{X}^{\mathrm{T}}\pmb {X}$ ，或 $(\lambda^2 -1)\pmb{X}^{\mathrm{T}}\pmb {X} = \mathbf{0}$

由 $\mathbf{X}^{\mathrm{T}}\mathbf{X} = \| \mathbf{X}\|^2 >0$ 得 $\lambda^2 -1 = 0$ ，即 $\lambda = \pm 1$

因为 $|\mathbf{A}| < 0$ ，所以 $\mathbf{A}$ 至少有一个特征值为 $-1$ ，从而 $\mathbf{A} + \mathbf{E}$ 的特征值至少有一个为0，

故 $|\mathbf{A} + \mathbf{E}| = 0$

# 十、填空题

（1）【答案】 18.4.

【解】 显然 $X\sim B(10,0.4)$

由 $E(X) = np = 4$ ， $D(X) = np(1 - p) = 10 \times 0.4 \times 0.6 = 2.4$ ，得

$$
E \left(X ^ {2}\right) = D (X) + \left[ E (X) \right] ^ {2} = 2. 4 + 1 6 = 1 8. 4.
$$

(2)【答案】 $\frac{5}{7}$ .

【解】令 $A = \{X\geqslant 0\} ,B = \{Y\geqslant 0\}$ ，则 $P(A) = P(B) = \frac{4}{7},P(AB) = \frac{3}{7},$

于是 $P\{\max (X,Y)\geqslant 0\} = 1 - P\{\max (X,Y) <   0\} = 1 - P\{X <   0,Y <   0\}$

$$
\begin{array}{l} = 1 - P (\bar {A} \cdot \bar {B}) = 1 - P (\bar {A + B}) = P (A + B) \\ = P (A) + P (B) - P (A B) = \frac {5}{7}. \\ \end{array}
$$

十一、【解】 $F_{Y}(y) = P\{Y \leqslant y\} = P\{\mathrm{e}^{X} \leqslant y\}$ ，

当 $y < 1$ 时， $F_{Y}(y) = 0$

当 $y \geqslant 1$ 时， $F_{Y}(y) = P\{X \leqslant \ln y\} = \int_{0}^{\ln y} \mathrm{e}^{-x} \, \mathrm{d}x = -\mathrm{e}^{-x}\left| \begin{array}{c} \ln y \\ 0 \end{array} \right| = 1 - \frac{1}{y}$ ，

即 $F_{Y}(y) = \left\{ \begin{array}{ll}0, & y < 1,\\ 1 - \frac{1}{y}, & y\geqslant 1, \end{array} \right.$ 故 $Y = \mathrm{e}^{X}$ 的概率密度为

$$
f _ {Y} (y) = \left\{ \begin{array}{l l} 0, & y <   1, \\ \frac {1}{y ^ {2}}, & y \geqslant 1. \end{array} \right.
$$