# 2019年数学(一）真题解析

# 一、选择题

(1)【答案】 (C).

【解】 方法一

由 $\lim_{x\to 0}\frac{x - \tan x}{x^3} = \lim_{x\to 0}\frac{1 - \sec^2x}{3x^2} = -\frac{1}{3}$ 得

$x - \tan x\sim -\frac{1}{3} x^3$ ，故 $x - \tan x$ 为3阶无穷小，即 $k = 3$ ，应选(C).

方法二

由 $\tan x = x + \frac{1}{3} x^3 + o(x^3)$ 得 $x - \tan x \sim -\frac{1}{3} x^3 (x \to 0)$ ,

故 $k = 3$ ，应选（C）.

（2）【答案】 （B）.

【解】 由 $\lim_{x\to 0^{-}}\frac{f(x) - f(0)}{x - 0} = \lim_{x\to 0^{-}}|x| = 0$ 得 $f_{-}^{\prime}(0) = 0$

由 $\lim_{x\to 0^{+}}\frac{f(x) - f(0)}{x - 0} = \lim_{x\to 0^{+}}\ln x = -\infty$ 得 $f_{+}^{\prime}(0)$ 不存在，

故 $x = 0$ 为 $f(x)$ 的不可导点；

当 $x < 0$ 时， $f(x) < 0 = f(0)$ ，当 $0 < x < 1, f(x) < 0 = f(0)$

故 $x = 0$ 为 $f(x)$ 的极大值点，应选（B）.

（3）【答案】 (D).

【解】 因为 $\{u_{n}\}$ 单调增加有界，所以 $\{u_{n}\}$ 极限存在.

设 $\lim_{n\to \infty}u_n = A$ ，因为 $\sum_{k = 1}^{n}(u_{k + 1}^2 -u_k^2) = u_{n + 1}^2 -u_1^2.$

所以 $\lim_{n\to \infty}\sum_{k = 1}^{n}(u_{k + 1}^2 -u_k^2) = \lim_{n\to \infty}(u_{n + 1}^2 -u_1^2) = A^2 -u_1^2$ ，应选(D).

（4）【答案】 (D).

【解】因为曲线积分与路径无关，所以 $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x} = \frac{1}{y^2}$ ，且 $P(x, y), Q(x, y)$ 在上半平面内连续可偏导，所以可取 $P(x, y) = x - \frac{1}{y}$ ，应选(D).

（5）【答案】 (C).

【解】 令 $AX = \lambda X(X\neq 0)$

由 $A^2 + A = 2E$ 得 $(A^2 + A - 2E)X = (\lambda^2 + \lambda - 2)X = 0$ ,

从而有 $\lambda^2 +\lambda -2 = 0$ ，即 $\lambda = -2$ 或 $\lambda = 1$

因为 $|\mathbf{A}| = 4$ ，所以 $\lambda_1 = 1, \lambda_2 = \lambda_3 = -2$

故二次型 $\mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}$ 的规范形为 $y_{1}^{2} - y_{2}^{2} - y_{3}^{2}$ ，应选(C).

（6）【答案】 （A）.

【解】 $\mathbf{A} = \begin{pmatrix} a_{11} & a_{12} & a_{13}\\ a_{21} & a_{22} & a_{23}\\ a_{31} & a_{32} & a_{33} \end{pmatrix}$ ， $\overline{\mathbf{A}} = \begin{pmatrix} a_{11} & a_{12} & a_{13} & d_1\\ a_{21} & a_{22} & a_{23} & d_2\\ a_{31} & a_{32} & a_{33} & d_3 \end{pmatrix}$

因为任两个平面不平行，所以 $r(\mathbf{A})\geqslant 2$

又因为三个平面没有公共的交点，所以 $r(\mathbf{A}) < r(\overline{\mathbf{A}})$

再由 $r(\overline{\mathbf{A}})\leqslant 3$ 得 $r(\mathbf{A}) = 2,r(\overline{\mathbf{A}}) = 3$ ，应选（A）.

（7）【答案】 (C).

【解】由减法公式得 $P(A\overline{B}) = P(A) - P(AB)$ ， $P(B\overline{A}) = P(B) - P(AB)$ ，

则 $P(A) = P(B)$ 的充分必要条件是 $P(A) - P(AB) = P(B) - P(AB)$

即 $P(A\overline{B}) = P(B\overline{A})$ ，应选(C).

（8）【答案】 （A）.

【解】因为 $X \sim N(\mu, \sigma^2), Y \sim N(\mu, \sigma^2)$ 且 $X, Y$ 相互独立，

所以 $X - Y\sim N(0,2\sigma^2)$ ，或 $\frac{X - Y}{\sqrt{2}\sigma}\sim N(0,1)$

故 $P\{|X - Y| < 1\} = P\left\{-\frac{1}{\sqrt{2}\sigma} < \frac{X - Y}{\sqrt{2}\sigma} < \frac{1}{\sqrt{2}\sigma}\right\} = 2\Phi \left(\frac{1}{\sqrt{2}\sigma}\right) - 1,$

即 $P\{|X - Y| < 1\}$ 与 $\mu$ 无关，与 $\sigma^2$ 有关，应选(A).

# 二、填空题

(9)【答案】 $\frac{y}{\cos x} + \frac{x}{\cos y}$ .

【解】 由 $\frac{\partial z}{\partial x} = -\cos x \cdot f'(\sin y - \sin x) + y$

$$
\frac {\partial z}{\partial y} = \cos y \cdot f ^ {\prime} (\sin y - \sin x) + x,
$$

得 $\frac{1}{\cos x} \cdot \frac{\partial z}{\partial x} + \frac{1}{\cos y} \cdot \frac{\partial z}{\partial y} = \frac{y}{\cos x} + \frac{x}{\cos y}$ .

(10)【答案】 $\sqrt{3\mathrm{e}^x - 2}$

【解】方法一 由 $2yy' - y^2 - 2 = 0$ 得 $\frac{2y\mathrm{d}y}{y^2 + 2} = \mathrm{d}x$

积分得 $\ln (y^2 + 2) = x + C$

再由 $y(0) = 1$ 得 $C = \ln 3$ ，即 $\ln (y^2 +2) = \ln (3\mathrm{e}^x)$

从而 $y^{2} + 2 = 3\mathrm{e}^{x}$ ，故 $y = \sqrt{3\mathrm{e}^x - 2}$

方法二 令 $y^{2} = u$ ，则原方程化为 $\frac{\mathrm{d}u}{\mathrm{d}x} - u = 2$

解得 $u = \left(\int 2\mathrm{e}^{\int -\mathrm{d}x}\mathrm{d}x + C\right)\mathrm{e}^{-\int -\mathrm{d}x} = (-2\mathrm{e}^{-x} + C)\mathrm{e}^{x},$

即 $y^{2} = (-2\mathrm{e}^{-x} + C)\mathrm{e}^{x} = Ce^{x} - 2$

由 $y(0) = 1$ 得 $C = 3$ ，故 $y = \sqrt{3\mathrm{e}^x - 2}$

（11）【答案】 $\cos \sqrt{x}$

【解】 $S(x) = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n)!} x^n = \sum_{n=0}^{\infty} \frac{(-1)^n}{(2n)!} (\sqrt{x})^{2n} = \cos \sqrt{x}$ .

(12)【答案】 $\frac{32}{3}$ .

【解】 $\iint_{\Sigma} \sqrt{4 - x^2 - 4z^2} \, \mathrm{d}x \, \mathrm{d}y = \iint_{\Sigma} \sqrt{y^2} \, \mathrm{d}x \, \mathrm{d}y = \iint_{\Sigma} |y| \, \mathrm{d}x \, \mathrm{d}y,$

令 $D_{xy} = \{(x,y)\mid x^2 +y^2\leqslant 4\}$ ，则

$$
\begin{array}{l} \iint_ {\Sigma} \sqrt {4 - x ^ {2} - 4 z ^ {2}} d x d y = \iint_ {\Sigma} | y | d x d y = \iint_ {D _ {x y}} | y | d x d y \\ = 4 \int_ {0} ^ {\frac {\pi}{2}} d \theta \int_ {0} ^ {2} r ^ {2} \sin \theta d r = 4 \int_ {0} ^ {\frac {\pi}{2}} \sin \theta d \theta \int_ {0} ^ {2} r ^ {2} d r = \frac {3 2}{3}. \\ \end{array}
$$

(13)【答案】 $X = k\binom{1}{-2} (k$ 为任意常数）.

【解】因为 $\alpha_{1},\alpha_{2}$ 线性无关，且 $\pmb{\alpha}_{3} = -\pmb{\alpha}_{1} + 2\pmb{\alpha}_{2}$ ，所以 $r(A) = 2$

于是方程组 $AX = 0$ 的基础解系含一个线性无关的解向量，

由 $\pmb{\alpha}_{3} = -\pmb{\alpha}_{1} + 2\pmb{\alpha}_{2}$ 得 $\pmb{\alpha}_{1} - 2\pmb{\alpha}_{2} + \pmb{\alpha}_{3} = \mathbf{0}$

即 $\binom{1}{-2}$ 为 $AX = 0$ 的一个非零解，故 $AX = 0$ 的通解为 $X = k\binom{1}{-2} (k$ 为任意常数）.

(14)【答案】 $\frac{2}{3}$ .

【解】 $E(X) = \int_0^2 x\cdot \frac{x}{2}\mathrm{d}x = \frac{4}{3},$

$$
F (x) = \int_ {- \infty} ^ {x} f (x) \mathrm {d} x,
$$

当 $x < 0$ 时， $F(x) = 0$

当 $0 \leqslant x < 2$ 时， $F(x) = \int_{0}^{x} \frac{x}{2} \, \mathrm{d}x = \frac{x^2}{4}$

当 $x \geqslant 2$ 时， $F(x) = 1$ ，即

$$
F (x) = \left\{ \begin{array}{l l} 0, & x <   0, \\ \frac {x ^ {2}}{4}, & 0 \leqslant x <   2, \\ 1, & x \geqslant 2, \end{array} \right.
$$

故 $P\{F(X) > E(X) - 1\} = P\left\{F(X) > \frac{1}{3}\right\} = 1 - P\left\{F(X)\leqslant \frac{1}{3}\right\}$

$$
\begin{array}{l} = 1 - P \left\{\frac {X ^ {2}}{4} \leqslant \frac {1}{3} \right\} = 1 - P \left\{X \leqslant \frac {2}{\sqrt {3}} \right\} \\ = 1 - \int_ {0} ^ {\frac {2}{\sqrt {3}}} \frac {x}{2} d x = 1 - \left. \frac {x ^ {2}}{4} \right| _ {0} ^ {\frac {2}{\sqrt {3}}} = \frac {2}{3}. \\ \end{array}
$$

# 三、解答题

（15）【解】 $(\mathrm{I})y^{\prime} + xy = \mathrm{e}^{-\frac{x^{2}}{2}}$ 的通解为

$$
y = \left(\int \mathrm {e} ^ {- \frac {x ^ {2}}{2}} \cdot \mathrm {e} ^ {\int x \mathrm {d} x} \mathrm {d} x + C\right) \mathrm {e} ^ {- \int x \mathrm {d} x} = (x + C) \mathrm {e} ^ {- \frac {x ^ {2}}{2}},
$$

由 $y(0) = 0$ 得 $C = 0$ ，故 $y = x\mathrm{e}^{-\frac{x^2}{2}}$

$$
\left(\text {I I}\right) y ^ {\prime} = \left(1 - x ^ {2}\right) \mathrm {e} ^ {- \frac {x ^ {2}}{2}}, y ^ {\prime \prime} = \left(x ^ {3} - 3 x\right) \mathrm {e} ^ {- \frac {x ^ {2}}{2}} = x \left(x + \sqrt {3}\right) \left(x - \sqrt {3}\right) \mathrm {e} ^ {- \frac {x ^ {2}}{2}},
$$

令 $y^{\prime \prime} = 0$ 得 $x = -\sqrt{3}, x = 0, x = \sqrt{3}$

当 $x \in (-\infty, -\sqrt{3})$ 时， $y'' < 0$ ；当 $x \in (-\sqrt{3}, 0)$ 时， $y'' > 0$ ；当 $x \in (0, \sqrt{3})$ 时， $y'' < 0$ ；当 $x \in (\sqrt{3}, +\infty)$ 时， $y'' > 0$

故 $y = x\mathrm{e}^{-\frac{x^2}{2}}$ 的凸区间为 $(-\infty , - \sqrt{3})$ 及 $(0,\sqrt{3})$ ；凹区间为 $(- \sqrt{3},0)$ 及 $(\sqrt{3}, + \infty)$ 曲线 $y = x\mathrm{e}^{-\frac{x^2}{2}}$ 的拐点为 $(- \sqrt{3}, - \sqrt{3}\mathrm{e}^{-\frac{3}{2}}),(0,0)$ 及 $(\sqrt{3},\sqrt{3}\mathrm{e}^{-\frac{3}{2}})$

（16）【解】（I）grad $z = \{2ax, 2by\}$ ，grad $z|_{(3,4)} = \{6a, 8b\}$

因为梯度的方向即为方向导数最大的方向，

所以有 $\frac{6a}{-3} = \frac{8b}{-4}$ 即 $a = b$

再由 $\sqrt{36a^2 + 64b^2} = 10$ 得 $a = b = -1$ .

（Ⅱ）曲面 $\Sigma: z = 2 - x^2 - y^2, (x, y) \in D_{xy}$ ，其中 $D_{xy} = \{(x, y) | x^2 + y^2 \leqslant 2\}$ ，则曲面 $\Sigma$ 的面积为

$$
\begin{array}{l} S = \iint_ {D _ {x y}} \sqrt {1 + z _ {x} ^ {\prime 2} + z _ {y} ^ {\prime 2}} d x d y = \iint_ {D _ {x y}} \sqrt {1 + 4 x ^ {2} + 4 y ^ {2}} d x d y \\ = 2 \pi \int_ {0} ^ {\sqrt {2}} r \sqrt {1 + 4 r ^ {2}} d r = \frac {\pi}{4} \int_ {0} ^ {\sqrt {2}} (1 + 4 r ^ {2}) ^ {\frac {1}{2}} d (1 + 4 r ^ {2}) \\ = \frac {\pi}{4} \times \frac {2}{3} (1 + 4 r ^ {2}) ^ {\frac {3}{2}} \Big | _ {0} ^ {\sqrt {2}} = \frac {\pi}{6} (2 7 - 1) = \frac {1 3}{3} \pi . \\ \end{array}
$$

（17）【解】 所求的面积为

$$
\begin{array}{l} A = \int_ {0} ^ {+ \infty} \mathrm {e} ^ {- x} | \sin x | \mathrm {d} x \\ = \lim  _ {n \rightarrow \infty} \sum_ {k = 0} ^ {n} (- 1) ^ {k} \int_ {k \pi} ^ {(k + 1) \pi} \mathrm {e} ^ {- x} \sin x \mathrm {d} x \\ = \lim  _ {n \rightarrow \infty} \sum_ {k = 0} ^ {n} (- 1) ^ {k} \left[ - \frac {1}{2} e ^ {- x} (\sin x + \cos x) \right] \Bigg | _ {k \pi} ^ {(k + 1) \pi} \\ = \frac {1}{2} \lim  _ {n \rightarrow \infty} \sum_ {k = 0} ^ {n} (- 1) ^ {k + 1} \left[ e ^ {- (k + 1) \pi} (- 1) ^ {k + 1} - e ^ {- k \pi} (- 1) ^ {k} \right] \\ = \frac {1}{2} \lim  _ {n \rightarrow \infty} \sum_ {k = 0} ^ {n} \left[ e ^ {- (k + 1) \pi} + e ^ {- k \pi} \right] = \frac {1}{2} \lim  _ {n \rightarrow \infty} \left[ 1 + 2 \sum_ {k = 1} ^ {n} e ^ {- k \pi} + e ^ {- (n + 1) \pi} \right] \\ = \frac {1}{2} \left(1 + 2 \sum_ {k = 1} ^ {\infty} \mathrm {e} ^ {- k \pi}\right) = \frac {1}{2} \left(1 + \frac {2 \mathrm {e} ^ {- \pi}}{1 - \mathrm {e} ^ {- \pi}}\right) = \frac {1}{2} \left(1 + \frac {2}{\mathrm {e} ^ {\pi} - 1}\right) = \frac {1}{2} + \frac {1}{\mathrm {e} ^ {\pi} - 1}. \\ \end{array}
$$

(18)（I）【证明】因为当 $0 \leqslant x \leqslant 1$ 时， $x^{n+1} \sqrt{1 - x^2} \leqslant x^n \sqrt{1 - x^2}$ ，

所以 $\int_0^1 x^{n + 1}\sqrt{1 - x^2}\mathrm{d}x <   \int_0^1 x^n\sqrt{1 - x^2}\mathrm{d}x$ ，即 $a_{n + 1} <   a_n$ ，故 $\{a_{n}\}$ 单调递减.

$$
\begin{array}{l} a _ {n} \stackrel {x = \sin t} {=} \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n} t \cdot \cos^ {2} t d t = \int_ {0} ^ {\frac {\pi}{2}} (\sin^ {n} t - \sin^ {n + 2} t) d t \\ = \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n} t \mathrm {d} t - \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n + 2} t \mathrm {d} t = I _ {n} - \frac {n + 1}{n + 2} I _ {n} = \frac {1}{n + 2} I _ {n}, \\ \end{array}
$$

$$
\begin{array}{l} a _ {n - 2} \stackrel {x = \sin t} {=} \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n - 2} t \cdot \cos^ {2} t d t = \int_ {0} ^ {\frac {\pi}{2}} (\sin^ {n - 2} t - \sin^ {n} t) d t \\ = \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n - 2} t \mathrm {d} t - \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n} t \mathrm {d} t = I _ {n - 2} - I _ {n}, \\ \end{array}
$$

因为 $I_{n} = \frac{n - 1}{n} I_{n - 2}$ ，所以 $I_{n - 2} = \frac{n}{n - 1} I_n$

于是 $a_{n - 2} = \frac{n}{n - 1} I_n - I_n = \frac{1}{n - 1} I_n$ ，故 $a_{n} = \frac{n - 1}{n + 2} a_{n - 2}(n = 2,3,\dots)$

（Ⅱ）【解】因为 $\{a_{n}\}$ 单调递减，所以 $a_{n} = \frac{n - 1}{n + 2} a_{n - 2} > \frac{n - 1}{n + 2} a_{n - 1}$

从而有 $\frac{n - 1}{n + 2} < \frac{a_n}{a_{n - 1}} < 1$ ，由夹逼定理得 $\lim_{n\to \infty}\frac{a_n}{a_{n - 1}} = 1.$

（19）【解】 设 $\Omega$ 的形心坐标为 $(\overline{x},\overline{y},\overline{z})$

由对称性得 $\overline{x} = 0$ ，且 $\overline{y} = \frac{\iiint_{\Omega} y \, \mathrm{d}x \, \mathrm{d}y \, \mathrm{d}z}{\iiint_{\Omega} \mathrm{d}x \, \mathrm{d}y \, \mathrm{d}z}, \overline{z} = \frac{\iiint_{\Omega} z \, \mathrm{d}x \, \mathrm{d}y \, \mathrm{d}z}{\iiint_{\Omega} \mathrm{d}x \, \mathrm{d}y \, \mathrm{d}z}$

$$
\iiint_ {\Omega} \mathrm {d} x \mathrm {d} y \mathrm {d} z = \int_ {0} ^ {1} \mathrm {d} z \iint_ {x ^ {2} + (y - z) ^ {2} \leqslant (1 - z) ^ {2}} \mathrm {d} x \mathrm {d} y = \pi \int_ {0} ^ {1} (1 - z) ^ {2} \mathrm {d} z = \frac {\pi}{3} (z - 1) ^ {3} \Big | _ {0} ^ {1} = \frac {\pi}{3};
$$

$$
\iiint_ {\Omega} y \mathrm {d} x \mathrm {d} y \mathrm {d} z = \int_ {0} ^ {1} \mathrm {d} z \iint_ {x ^ {2} + (y - z) ^ {2} \leqslant (1 - z) ^ {2}} y \mathrm {d} x \mathrm {d} y,
$$

$$
\begin{array}{l} \text {由} \iint_ {x ^ {2} + (y - z) ^ {2} \leqslant (1 - z) ^ {2}} y \mathrm {d} x \mathrm {d} y \xlongequal {y - z = u} \iint_ {x ^ {2} + u ^ {2} \leqslant (1 - z) ^ {2}} (u + z) \mathrm {d} x \mathrm {d} u \\ = \iint_ {x ^ {2} + u ^ {2} \leqslant (1 - z) ^ {2}} z \mathrm {d} x \mathrm {d} u = \pi z (1 - z) ^ {2} \text {得} \\ \end{array}
$$

$$
\begin{array}{l} \iiint_ {\Omega} y \mathrm {d} x \mathrm {d} y \mathrm {d} z = \pi \int_ {0} ^ {1} z (1 - z) ^ {2} \mathrm {d} z = \frac {\pi}{1 2}; \\ \iiint_ {\Omega} z \mathrm {d} x \mathrm {d} y \mathrm {d} z = \int_ {0} ^ {1} z \mathrm {d} z \iint_ {x ^ {2} + (y - z) ^ {2} \leqslant (1 - z) ^ {2}} \mathrm {d} x \mathrm {d} y = \pi \int_ {0} ^ {1} z (1 - z) ^ {2} \mathrm {d} z = \frac {\pi}{1 2}, \\ \end{array}
$$

故 $\Omega$ 的形心坐标为 $\left(0, \frac{1}{4}, \frac{1}{4}\right)$ .

（20）（I）【解】由题意得 $b\pmb{\alpha}_{1} + c\pmb{\alpha}_{2} + \pmb{\alpha}_{3} = \pmb{\beta}$ ，即 $\begin{cases} b + c + 1 = 1, \\ 2b + 3c + a = 1, \\ b + 2c + 3 = 1, \end{cases}$

解得 $a = 3, b = 2, c = -2$ .

（Ⅱ）【证明】因为 $|\pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\beta}| = \begin{vmatrix} 1 & 1 & 1 \\ 3 & 3 & 1 \\ 2 & 3 & 1 \end{vmatrix} = \begin{vmatrix} 1 & 1 & 1 \\ 0 & 0 & -2 \\ 0 & 1 & -1 \end{vmatrix} = 2 \neq 0$ ，所以 $\pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\beta}$ 线性无关，故 $\pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\beta}$ 为 $\mathbf{R}^3$ 的一个基.

设由 $\alpha_{2},\alpha_{3},\beta$ 到 $\alpha_{1},\alpha_{2},\alpha_{3}$ 的过渡矩阵为 $Q$ ，即 $(\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}) = (\pmb{\alpha}_{2},\pmb{\alpha}_{3},\pmb{\beta})Q$

于是 $Q = (\pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\beta})^{-1}(\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3)$

由 $\begin{pmatrix} 1 & 1 & 1 & 1 & 0 & 0 \\ 3 & 3 & 1 & 0 & 1 & 0 \\ 2 & 3 & 1 & 0 & 0 & 1 \end{pmatrix} \to \begin{pmatrix} 1 & 1 & 1 & 1 & 0 & 0 \\ 0 & 0 & -2 & -3 & 1 & 0 \\ 0 & 1 & -1 & -2 & 0 & 1 \end{pmatrix} \to \begin{pmatrix} 1 & 1 & 1 & 1 & 0 & 0 \\ 0 & 1 & -1 & -2 & 0 & 1 \\ 0 & 0 & 1 & \frac{3}{2} & -\frac{1}{2} & 0 \end{pmatrix}$

$\rightarrow \left[ \begin{array}{lll}1 & 1 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right]\rightarrow \left[ \begin{array}{lll}1 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right]$

$(\pmb{\alpha}_{2}, \pmb{\alpha}_{3}, \pmb{\beta})^{-1} = \begin{bmatrix} 0 & 1 & -1 \\ -\frac{1}{2} & -\frac{1}{2} & 1 \\ \frac{3}{2} & -\frac{1}{2} & 0 \end{bmatrix}$ , 则

$$
\boldsymbol {Q} = \left[ \begin{array}{c c c} 0 & 1 & - 1 \\ - \frac {1}{2} & - \frac {1}{2} & 1 \\ \frac {3}{2} & - \frac {1}{2} & 0 \end{array} \right] \left( \begin{array}{c c c} 1 & 1 & 1 \\ 2 & 3 & 3 \\ 1 & 2 & 3 \end{array} \right) = \left[ \begin{array}{c c c} 1 & 1 & 0 \\ - \frac {1}{2} & 0 & 1 \\ \frac {1}{2} & 0 & 0 \end{array} \right].
$$

(21)【解】（I）因为 $A \sim B$ ，所以 $\operatorname{tr} A = \operatorname{tr} B$ ，即 $x - 4 = y + 1$ ，或 $y = x - 5$

再由 $|\mathbf{A}| = |\mathbf{B}|$ 得 $-2(-2x + 4) = -2y$ ，即 $y = -2x + 4$

解得 $x = 3, y = -2$

$$
(\text {I I}) \mathbf {A} = \left( \begin{array}{c c c} - 2 & - 2 & 1 \\ 2 & 3 & - 2 \\ 0 & 0 & - 2 \end{array} \right), \mathbf {B} = \left( \begin{array}{c c c} 2 & 1 & 0 \\ 0 & - 1 & 0 \\ 0 & 0 & - 2 \end{array} \right),
$$

显然矩阵 $\mathbf{A},\mathbf{B}$ 的特征值为 $\lambda_1 = -2,\lambda_2 = -1,\lambda_3 = 2$

由 $2\pmb {E} + \pmb {A}\rightarrow \left( \begin{array}{ccc}0 & -2 & 1\\ 2 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left[ \begin{array}{ccc}1 & 0 & \frac{1}{4}\\ 0 & 1 & -\frac{1}{2}\\ 0 & 0 & 0 \end{array} \right]$ 得 $\mathbf{A}$ 的属于特征值 $\lambda_{1} = -2$ 的特征向量为

$$
\boldsymbol {\alpha} _ {1} = \left( \begin{array}{c} - 1 \\ 2 \\ 4 \end{array} \right);
$$

由 $\pmb {E} + \pmb {A}\rightarrow \left( \begin{array}{lll}1 & 2 & -1\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left( \begin{array}{lll}1 & 2 & 0\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $\mathbf{A}$ 的属于特征值 $\lambda_{2} = -1$ 的特征向量为

$$
\boldsymbol {\alpha} _ {2} = \left( \begin{array}{c} - 2 \\ 1 \\ 0 \end{array} \right);
$$

由 $2E - A\to \left( \begin{array}{ccc}2 & 1 & -2\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right)\to \left[ \begin{array}{ccc}1 & \frac{1}{2} & 0\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right]$ 得 $\mathbf{A}$ 的属于特征值 $\lambda_3 = 2$ 的特征向量为

$$
\boldsymbol {\alpha} _ {3} = \left( \begin{array}{c} - 1 \\ 2 \\ 0 \end{array} \right),
$$

令 $\pmb{P}_{1} = \left( \begin{array}{ccc} - 1 & -2 & -1\\ 2 & 1 & 2\\ 4 & 0 & 0 \end{array} \right)$ 则 $\pmb {P}_1^{-1}\pmb {A}\pmb {P}_1 = \left( \begin{array}{ccc} - 2 & 0 & 0\\ 0 & -1 & 0\\ 0 & 0 & 2 \end{array} \right);$

由 $2\pmb {E} + \pmb {B} = \left( \begin{array}{lll}4 & 1 & 0\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left( \begin{array}{lll}1 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得 $\pmb{B}$ 的属于特征值 $\lambda_{1} = -2$ 的特征向量为 $\pmb {\beta}_1 = \begin{pmatrix} 0\\ 0\\ 1 \end{pmatrix}$

由 $\pmb {E} + \pmb {B} = \left( \begin{array}{lll}3 & 1 & 0\\ 0 & 0 & 0\\ 0 & 0 & -1 \end{array} \right)\rightarrow \left[ \begin{array}{ccc}1 & \frac{1}{3} & 0\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right]$ 得 $\pmb{B}$ 的属于特征值 $\lambda_{2} = -1$ 的特征向量为

$$
\boldsymbol {\beta} _ {2} = \left( \begin{array}{c} - 1 \\ 3 \\ 0 \end{array} \right);
$$

由 $2\pmb {E} - \pmb {B} = \left( \begin{array}{rrr}0 & -1 & 0\\ 0 & 3 & 0\\ 0 & 0 & 4 \end{array} \right)\rightarrow \left( \begin{array}{rrr}0 & 1 & 0\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $\pmb{B}$ 的属于特征值 $\lambda_{2} = 2$ 的特征向量为 $\pmb {\beta}_3 = \left( \begin{array}{l}1\\ 0\\ 0 \end{array} \right),$

令 $\pmb{P}_{2} = \begin{pmatrix} 0 & -1 & 1\\ 0 & 3 & 0\\ 1 & 0 & 0 \end{pmatrix}$ 则 $\pmb {P}_2^{-1}\pmb {B}\pmb {P}_2 = \left( \begin{array}{rrr} - 2 & 0 & 0\\ 0 & -1 & 0\\ 0 & 0 & 2 \end{array} \right)$

由 $P_{1}^{-1}AP_{1} = P_{2}^{-1}BP_{2}$ 得 $(P_{1}P_{2}^{-1})^{-1}A(P_{1}P_{2}^{-1}) = B$

故 $\pmb {P} = \pmb {P}_1\pmb{P}_2^{-1} = \left( \begin{array}{rrr} - 1 & -1 & -1\\ 2 & 1 & 2\\ 0 & 0 & 4 \end{array} \right).$

(22)【解】（I）因为 $X \sim E(1)$ ，所以 $X$ 的分布函数为 $F(x) = \begin{cases} 1 - \mathrm{e}^{-x}, & x \geqslant 0, \\ 0, & x < 0. \end{cases}$

$$
\begin{array}{l} F _ {Z} (z) = P \{X Y \leqslant z \} = P \{Y = - 1 \} P \{X Y \leqslant z \mid Y = - 1 \} + P \{Y = 1 \} P \{X Y \leqslant z \mid Y = 1 \} \\ = p P \{- X \leqslant z \} + (1 - p) P \{X \leqslant z \} = p P \{X \geqslant - z \} + (1 - p) P \{X \leqslant z \} \\ = p [ 1 - P \{X \leqslant - z \} ] + (1 - p) P \{X \leqslant z \} = p [ 1 - F (- z) ] + (1 - p) F (z), \\ \end{array}
$$

当 $z < 0$ 时， $F_{Z}(z) = p\mathrm{e}^{z}$

当 $z \geqslant 0$ 时， $F_{Z}(z) = p + (1 - p)(1 - \mathrm{e}^{-z})$

故 $f_{Z}(z) = \left\{ \begin{array}{ll} p \mathrm{e}^{z}, & z < 0, \\ (1 - p) \mathrm{e}^{-z}, & z \geqslant 0. \end{array} \right.$

$$
\begin{array}{l} (\mathrm {I I}) \operatorname {C o v} (X, Z) = \operatorname {C o v} (X, X Y) = E \left(X ^ {2} Y\right) - E (X) \cdot E (X Y) \\ = E \left(X ^ {2}\right) E (Y) - \left[ E (X) \right] ^ {2} E (Y) = D (X) \cdot E (Y), \\ \end{array}
$$

因为 $X \sim E(1)$ ，所以 $E(X) = 1, D(X) = 1$

又因为 $Y\sim \left( \begin{array}{cc} - 1 & 1\\ p & 1 - p \end{array} \right)$ ，所以 $E(Y) = (-1)p + (1 - p) = 1 - 2p$

$X$ 与 $Z$ 不相关的充分必要条件是 $\operatorname{Cov}(X,Z) = 0$

故当 $p = \frac{1}{2}$ 时， $X$ 与 $Z$ 不相关.

（Ⅲ）设 $F(x,y)$ 为 $(X,Z)$ 的联合分布函数，

$$
\begin{array}{l} F (1, 1) = P \{X \leqslant 1, Z \leqslant 1 \} = P \{X \leqslant 1, X Y \leqslant 1 \} \\ = P \{Y = - 1 \} P \{X \leqslant 1, X Y \leqslant 1 \mid Y = - 1 \} + P \{Y = 1 \} P \{X \leqslant 1, X Y \leqslant 1 \mid Y = 1 \} \\ = \frac {1}{2} P \{X \leqslant 1, - X \leqslant 1 \} + \frac {1}{2} P \{X \leqslant 1 \} = \frac {1}{2} P \{- 1 \leqslant X \leqslant 1 \} + \frac {1}{2} P \{X \leqslant 1 \} \\ = P \{X \leqslant 1 \} = F (1) = 1 - \frac {1}{\mathrm {e}}, \\ \end{array}
$$

$$
F _ {X} (1) = P \{X \leqslant 1 \} = 1 - \frac {1}{\mathrm {e}},
$$

$$
\begin{array}{l} F _ {Z} (1) = P \{X Y \leqslant 1 \} = P \{Y = - 1 \} P \{X Y \leqslant 1 \mid Y = - 1 \} + P \{Y = 1 \} P \{X Y \leqslant 1 \mid Y = 1 \} \\ = \frac {1}{2} P \{- X \leqslant 1 \} + \frac {1}{2} P \{X \leqslant 1 \} = \frac {1}{2} P \{X \geqslant - 1 \} + \frac {1}{2} P \{X \leqslant 1 \} \\ = \frac {1}{2} + \frac {1}{2} \left(1 - \frac {1}{\mathrm {e}}\right) = 1 - \frac {1}{2 \mathrm {e}}, \\ \end{array}
$$

因为 $F(1,1)\neq F_{X}(1)\cdot F_{Z}(1)$ ，所以 $X$ 与 $Z$ 不相互独立.

（23）【解】（I）由归一性得

$$
\begin{array}{l} 1 = \int_ {\mu} ^ {+ \infty} \frac {A}{\sigma} e ^ {- \frac {(x - \mu) ^ {2}}{2 \sigma^ {2}}} d x = A \int_ {\mu} ^ {+ \infty} e ^ {- \frac {1}{2} (\frac {x - \mu}{\sigma}) ^ {2}} d \left(\frac {x - \mu}{\sigma}\right) = A \int_ {0} ^ {+ \infty} e ^ {- \frac {x ^ {2}}{2}} d x \\ = \sqrt {2 \pi} A \int_ {0} ^ {+ \infty} \frac {1}{\sqrt {2 \pi}} e ^ {- \frac {x ^ {2}}{2}} d x = \frac {\sqrt {2 \pi}}{2} A \int_ {- \infty} ^ {+ \infty} \frac {1}{\sqrt {2 \pi}} e ^ {- \frac {x ^ {2}}{2}} d x = \frac {\sqrt {2 \pi}}{2} A, \\ \end{array}
$$

解得 $A = \sqrt{\frac{2}{\pi}}$

$\left(\mathrm{II}\right)L\left(\sigma^{2}\right) = \frac{A^{n}}{\left(\sigma^{2}\right)^{\frac{n}{2}}}\mathrm{e}^{-\frac{1}{2\sigma^{2}}\sum_{i = 1}^{n}(x_{i} - \mu)^{2}},$

$$
\ln L (\sigma^ {2}) = n \ln A - \frac {n}{2} \ln \sigma^ {2} - \frac {1}{2 \sigma^ {2}} \sum_ {i = 1} ^ {n} (x _ {i} - \mu) ^ {2},
$$

由 $\frac{\mathrm{d}}{\mathrm{d}\sigma^2}\ln L(\sigma^2) = -\frac{n}{2} \cdot \frac{1}{\sigma^2} + \frac{1}{2\sigma^4}\sum_{i=1}^{n}(x_i - \mu)^2 = 0$ 得

$\sigma^2$ 的最大似然估计值为 $\hat{\sigma}^2 = \frac{1}{n}\sum_{i = 1}^{n}(x_i - \mu)^2,$

故 $\sigma^2$ 的最大似然估计量为 $\hat{\sigma}^2 = \frac{1}{n}\sum_{i = 1}^{n}(X_i - \mu)^2.$