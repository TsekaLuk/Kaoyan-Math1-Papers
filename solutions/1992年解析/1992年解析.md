# 1992年数学(一）真题解析

# 一、填空题

(1)【答案】 $\frac{\mathrm{e}^{x + y} - y\sin(xy)}{x\sin(xy) - \mathrm{e}^{x + y}}.$

【解】 $\mathrm{e}^{x + y} + \cos (xy) = 0$ 两边对 $x$ 求导得

$\mathrm{e}^{x + y}\cdot \left(1 + \frac{\mathrm{dy}}{\mathrm{dx}}\right) - \sin (xy)\cdot \left(y + x\frac{\mathrm{dy}}{\mathrm{dx}}\right) = 0$ ，解得 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\mathrm{e}^{x + y} - y\sin(xy)}{x\sin(xy) - \mathrm{e}^{x + y}}.$

(2)【答案】 $\left\{\frac{2}{9}, \frac{4}{9}, -\frac{4}{9}\right\}$ .

【解】 $\frac{\partial u}{\partial x} = \frac{2x}{x^2 + y^2 + z^2}, \frac{\partial u}{\partial y} = \frac{2y}{x^2 + y^2 + z^2}, \frac{\partial u}{\partial z} = \frac{2z}{x^2 + y^2 + z^2},$

$\left.\frac{\partial u}{\partial x}\right|_{M} = \frac{2}{9},\quad \left.\frac{\partial u}{\partial y}\right|_{M} = \frac{4}{9},\quad \left.\frac{\partial u}{\partial z}\right|_{M} = -\frac{4}{9}$ 则 $\mathbf{grad}u\Big|_M = \left\{\frac{2}{9},\frac{4}{9}, - \frac{4}{9}\right\} .$

(3)【答案】 $\frac{\pi^2}{2}$ .

【解】 $f(x)$ 的傅里叶级数在 $x = \pi$ 处收敛于

$$
\frac {f (\pi - 0) + f (\pi + 0)}{2} = \frac {f (\pi - 0) + f (- \pi + 0)}{2} = \frac {\pi^ {2}}{2}.
$$

(4)【答案】 $y = (x + C)\cos x$ （ $C$ 为任意常数）.

【解】 微分方程 $y' + y \tan x = \cos x$ 的通解为

$y = \left(\int \cos x\cdot \mathrm{e}^{\int \tan x\mathrm{d}x}\mathrm{d}x + C\right)\cdot \mathrm{e}^{-\int \tan x\mathrm{d}x} = (x + C)\cos x(C$ 为任意常数）.

（5）【答案】1.

【解】方法一 因为 $\mathbf{A}$ 的任意两行都成比例，所以 $r(\mathbf{A})\leqslant 1$

又因为 $\mathbf{A} \neq \mathbf{0}$ , 所以 $r(\mathbf{A}) \geqslant 1$ , 故 $r(\mathbf{A}) = 1$

方法二

$$
\mathbf {A} = \left[ \begin{array}{c} {a _ {1}} \\ {a _ {2}} \\ {\vdots} \\ {a _ {n}} \end{array} \right] (b _ {1}, b _ {2}, \dots , b _ {n}) = \pmb {\alpha} \pmb {\beta} ^ {\mathrm {T}}, \text {其 中} \pmb {\alpha} = \left[ \begin{array}{c} {a _ {1}} \\ {a _ {2}} \\ {\vdots} \\ {a _ {n}} \end{array} \right], \pmb {\beta} = \left[ \begin{array}{c} {b _ {1}} \\ {b _ {2}} \\ {\vdots} \\ {b _ {n}} \end{array} \right],
$$

$$
r (\mathbf {A}) = r (\boldsymbol {\alpha} \boldsymbol {\beta} ^ {\mathrm {T}}) \leqslant r (\boldsymbol {\alpha}) = 1,
$$

再由 $a_{i}\neq 0,b_{i}\neq 0,i = 1,2,\dots ,n$ 得 $\mathbf{A}\neq \mathbf{O}$ ，于是 $r(A)\geqslant 1$ ，故 $r(A) = 1$

# 二、选择题

(1)【答案】 (D).

【解】由 $\lim_{x\to 1^{-}}\frac{x^2 - 1}{x - 1}\mathrm{e}^{\frac{1}{x - 1}} = 2\lim_{x\to 1^{-}}\mathrm{e}^{\frac{1}{x - 1}} = 0,$ $\lim_{x\to 1^{+}}\frac{x^2 - 1}{x - 1}\mathrm{e}^{\frac{1}{x - 1}} = 2\lim_{x\to 1^{+}}\mathrm{e}^{\frac{1}{x - 1}} = +\infty ,$

得 $\lim_{x\to 1}\frac{x^2 - 1}{x - 1}\mathrm{e}^{\frac{1}{x - 1}}$ 不存在但不是 $\infty$ ，应选(D).

（2）【答案】 (C).

【解】 $\left|(-1)^n\left(1 - \cos \frac{\alpha}{n}\right)\right| = 2\sin^2\frac{\alpha}{2n} \sim \frac{\alpha^2}{2} \cdot \frac{1}{n^2},$

因为 $\sum_{n=1}^{\infty} \frac{\alpha^2}{2} \cdot \frac{1}{n^2}$ 收敛，所以 $\sum_{n=1}^{\infty} \left| (-1)^n \left(1 - \cos \frac{\alpha}{n}\right) \right|$ 收敛，即 $\sum_{n=1}^{\infty} (-1)^n \left(1 - \cos \frac{\alpha}{n}\right)$ 绝对收敛，应选(C).

（3）【答案】 （B）.

【解】 曲线的切线向量为 $\pmb{T} = \{1, -2t, 3t^2\}$

由 $\{1, -2t, 3t^2\} \cdot \{1, 2, 1\} = 0$ 得 $t_1 = \frac{1}{3}, t_2 = 1$ ，故与平面 $x + 2y + z = 4$ 平行的切线有2条，应选(B).

（4）【答案】 (C).

【解】 $f(x) = \left\{ \begin{array}{ll}2x^{3}, & x < 0,\\ 4x^{3}, & x\geqslant 0, \end{array} \right.$ $f^{\prime}(x) = \left\{ \begin{array}{ll}6x^{2}. & x < 0,\\ 12x^{2}, & x > 0, \end{array} \right.$

显然 $f^{\prime}(0) = f^{\prime \prime}(0) = 0$ ， $f''(x) = \left\{ \begin{array}{ll}12x, & x <   0,\\ 24x, & x\geqslant 0, \end{array} \right.$

$$
f _ {-} ^ {\prime \prime} (0) = \lim  _ {x \rightarrow 0 ^ {-}} \frac {f ^ {\prime \prime} (x)}{x} = 1 2, \quad f _ {+} ^ {\prime \prime} (0) = \lim  _ {x \rightarrow 0 ^ {+}} \frac {f ^ {\prime \prime} (x)}{x} = 2 4,
$$

因为 $f_{-}^{\prime \prime}(0)\neq f_{+}^{\prime \prime}(0)$ ，所以 $f^{(n)}(0)$ 存在的最高阶数 $n = 2$ ，应选(C).

（5）【答案】 （A).

【解】因为 $\xi_{1}$ 与 $\xi_{2}$ 线性无关，所以三元齐次线性方程组 $AX = 0$ 的基础解系中至少含2个解向量，即 $3 - r(A)\geqslant 2$ ，得 $r(\mathbf{A})\leqslant 1$ ，而选项(B)(C)(D)中矩阵的秩都大于1，所以均不对，只有选项（A）正确.三、

(1)【解】由 $1 - \sqrt{1 - x^2} = -[(1 - x^2)^{\frac{1}{2}} - 1] \sim \frac{1}{2} x^2 (x \to 0)$ ，得

$$
\lim  _ {x \rightarrow 0} \frac {\mathrm {e} ^ {x} - \sin x - 1}{1 - \sqrt {1 - x ^ {2}}} = \lim  _ {x \rightarrow 0} \frac {\mathrm {e} ^ {x} - \sin x - 1}{\frac {1}{2} x ^ {2}} = \lim  _ {x \rightarrow 0} \frac {\mathrm {e} ^ {x} - \cos x}{x} = \lim  _ {x \rightarrow 0} (\mathrm {e} ^ {x} + \sin x) = 1.
$$

(2)【解】 $\frac{\partial z}{\partial x} = f_1' \cdot \mathrm{e}^x \sin y + 2xf_2'$ ,

$$
\begin{array}{l} \frac {\partial^ {2} z}{\partial x \partial y} = e ^ {x} \sin y \cdot \left(f _ {1 1} ^ {\prime \prime} \cdot e ^ {x} \cos y + 2 y f _ {1 2} ^ {\prime \prime}\right) + f _ {1} ^ {\prime} \cdot e ^ {x} \cos y + 2 x \left(f _ {2 1} ^ {\prime \prime} \cdot e ^ {x} \cos y + 2 y f _ {2 2} ^ {\prime \prime}\right) \\ = \frac {1}{2} e ^ {2 x} \sin 2 y \cdot f _ {1 1} ^ {\prime \prime} + 2 e ^ {x} (y \sin y + x \cos y) f _ {1 2} ^ {\prime \prime} + f _ {1} ^ {\prime} \cdot e ^ {x} \cos y + 4 x y f _ {2 2} ^ {\prime \prime}. \\ \end{array}
$$

(3)【解】 $\int_{1}^{3} f(x - 2) \, \mathrm{d}x = \int_{1}^{3} f(x - 2) \, \mathrm{d}(x - 2) = \int_{-1}^{1} f(x) \, \mathrm{d}x$

$$
= \int_ {- 1} ^ {0} (1 + x ^ {2}) \mathrm {d} x + \int_ {0} ^ {1} \mathrm {e} ^ {- x} \mathrm {d} x = \frac {7}{3} - \frac {1}{\mathrm {e}}.
$$

四、【解】 特征方程为 $\lambda^2 + 2\lambda - 3 = 0$ ，特征根为 $\lambda_1 = -3, \lambda_2 = 1$

$y^{\prime \prime} + 2y^{\prime} - 3y = 0$ 的通解为 $y = C_1\mathrm{e}^{-3x} + C_2\mathrm{e}^x$

令 $y^{\prime \prime} + 2y^{\prime} - 3y = \mathrm{e}^{-3x}$ 的特解为 $y_0(x) = ax\mathrm{e}^{-3x}$ ，代入得 $a = -\frac{1}{4}$

故 $y^{\prime \prime} + 2y^{\prime} - 3y = \mathrm{e}^{-3x}$ 的通解为

$y = C_{1}\mathrm{e}^{-3x} + C_{2}\mathrm{e}^{x} - \frac{1}{4} x\mathrm{e}^{-3x}(C_{1},C_{2}$ 为任意常数）.

五、【解】补充 $\Sigma_{1}:z = 0(x^{2} + y^{2}\leqslant a^{2})$ ，取下侧，

$$
I = \iint_ {\Sigma} (x ^ {3} + a z ^ {2}) d y d z + (y ^ {3} + a x ^ {2}) d z d x + (z ^ {3} + a y ^ {2}) d x d y
$$

$$
= \left(\iint_ {\Sigma + \Sigma_ {1}} - \iint_ {\Sigma_ {1}}\right) (x ^ {3} + a z ^ {2}) d y d z + (y ^ {3} + a x ^ {2}) d z d x + (z ^ {3} + a y ^ {2}) d x d y,
$$

而 $\iint_{\Sigma + \Sigma_1} (x^3 + az^2) \, \mathrm{d}y \, \mathrm{d}z + (y^3 + ax^2) \, \mathrm{d}z \, \mathrm{d}x + (z^3 + ay^2) \, \mathrm{d}x \, \mathrm{d}y$

$$
\begin{array}{l} = 3 \iiint_ {\Omega} \left(x ^ {2} + y ^ {2} + z ^ {2}\right) \mathrm {d} v = 3 \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {\frac {\pi}{2}} \mathrm {d} \varphi \int_ {0} ^ {a} r ^ {4} \sin \varphi \mathrm {d} r = \frac {6 \pi}{5} a ^ {5}, \\ \iint_ {x _ {1}} \left(x ^ {3} + a z ^ {2}\right) d y d z + \left(y ^ {3} + a x ^ {2}\right) d z d x + \left(z ^ {3} + a y ^ {2}\right) d x d y \\ = \iint_ {\Sigma_ {1}} a y ^ {2} d x d y = - a \iint_ {x ^ {2} + y ^ {2} \leqslant a ^ {2}} y ^ {2} d x d y = - \frac {a}{2} \iint_ {x ^ {2} + y ^ {2} \leqslant a ^ {2}} (x ^ {2} + y ^ {2}) d x d y \\ = - \frac {a}{2} \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {a} r ^ {3} \mathrm {d} r = - \frac {\pi}{4} a ^ {5}, \\ \end{array}
$$

故 $\iint_{\Sigma} (x^3 + az^2) \, \mathrm{d}y \, \mathrm{d}z + (y^3 + ax^2) \, \mathrm{d}z \, \mathrm{d}x + (z^3 + ay^2) \, \mathrm{d}x \, \mathrm{d}y = \frac{6\pi}{5} a^5 + \frac{\pi}{4} a^5 = \frac{29}{20}\pi a^5.$

六、【解】 不妨设 $0 < x_{1} < x_{2}$ ，由拉格朗日中值定理得

$f(x_{1}) = f(x_{1}) - f(0) = f^{\prime}(\xi_{1})x_{1}$ ，其中 $0 < \xi_{1} < x_{1}$

$f(x_{1} + x_{2}) - f(x_{2}) = f^{\prime}(\xi_{2})x_{1}$ ，其中 $x_{2} <   \xi_{2} <   x_{1} + x_{2}$

因为 $f''(x) < 0$ ，所以 $f'(x)$ 单调递减，又因为 $\xi_1 < \xi_2$ ，所以 $f'(\xi_1) > f'(\xi_2)$

即 $f(x_{1}) > f(x_{1} + x_{2}) - f(x_{2})$ ，故 $f(x_{1} + x_{2}) <   f(x_{1}) + f(x_{2}).$

七、【解】 直线段 $OM: x = \xi t, y = \eta t, z = \zeta t, t$ 从0到1，功 $W$ 为

$$
W = \int_ {O M} y z \mathrm {d} x + z x \mathrm {d} y + x y \mathrm {d} z = \int_ {0} ^ {1} 3 \xi \eta \zeta t ^ {2} \mathrm {d} t = \xi \eta \zeta .
$$

下面求 $W = \xi \eta \zeta$ 在条件 $\frac{\xi^2}{a^2} +\frac{\eta^2}{b^2} +\frac{\zeta^2}{c^2} = 1(\xi \geqslant 0,\eta \geqslant 0,\zeta \geqslant 0)$ 下的最大值.

令 $F(\xi, \eta, \zeta, \lambda) = \xi \eta \zeta + \lambda \left(1 - \frac{\xi^2}{a^2} - \frac{\eta^2}{b^2} - \frac{\zeta^2}{c^2}\right)$ .

由 $\left\{ \begin{array}{l} \frac{\partial F}{\partial \xi} = 0, \\ \frac{\partial F}{\partial \eta} = 0, \\ \frac{\partial F}{\partial \zeta} = 0, \\ \frac{\partial F}{\partial \lambda} = 0, \end{array} \right.$ 得 $\left\{ \begin{array}{l} \eta \zeta = \frac{2\lambda}{a^2} \xi, \\ \xi \zeta = \frac{2\lambda}{b^2} \eta, \\ \xi \eta = \frac{2\lambda}{c^2} \zeta, \\ 1 - \frac{\xi^2}{a^2} - \frac{\eta^2}{b^2} - \frac{\zeta^2}{c^2} = 0. \end{array} \right.$

从而 $\frac{\xi^2}{a^2} = \frac{\eta^2}{b^2} = \frac{\zeta^2}{c^2}$ ，即得 $\frac{\xi^2}{a^2} = \frac{\eta^2}{b^2} = \frac{\zeta^2}{c^2} = \frac{1}{3}$ 。于是得

$$
\xi = \frac {a}{\sqrt {3}}, \quad \eta = \frac {b}{\sqrt {3}}, \quad \zeta = \frac {c}{\sqrt {3}},
$$

由问题的实际意义知 $W_{\max} = \frac{\sqrt{3}}{9} abc$

八、【证明】（1）因为 $\alpha_{2},\alpha_{3},\alpha_{4}$ 线性无关，所以 $\alpha_{2},\alpha_{3}$ 线性无关，

又因为 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性相关，所以 $\pmb{\alpha}_{1}$ 可由 $\alpha_{2},\alpha_{3}$ 线性表示

(2) $\pmb{\alpha}_{4}$ 不可由 $\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}$ 线性表示，

若 $\alpha_{4}$ 可由 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性表示，因为 $\alpha_{1}$ 可由 $\alpha_{2},\alpha_{3}$ 线性表示，

所以 $\alpha_{4}$ 可由 $\alpha_{2},\alpha_{3}$ 线性表示，从而 $\alpha_{2},\alpha_{3},\alpha_{4}$ 线性相关，矛盾，所以 $\alpha_{4}$ 不可由 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性表示.九、【解】（1）设

$$
\boldsymbol {\beta} = x _ {1} \boldsymbol {\xi} _ {1} + x _ {2} \boldsymbol {\xi} _ {2} + x _ {3} \boldsymbol {\xi} _ {3} = (\boldsymbol {\xi} _ {1}, \boldsymbol {\xi} _ {2}, \boldsymbol {\xi} _ {3}) \left( \begin{array}{l} x _ {1} \\ x _ {2} \\ x _ {3} \end{array} \right),
$$

对此方程组的增广矩阵作初等行变换

$$
(\pmb {\xi} _ {1}, \pmb {\xi} _ {2}, \pmb {\xi} _ {3}: \pmb {\beta}) = \left(\begin{array}{c c c c}1&1&1&1\\1&2&3&1\\1&4&9&3\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&2&0\\0&3&8&2\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&2&0\\0&0&1&1\end{array}\right),
$$

得唯一解 $(2, - 2,1)^{\mathrm{T}}$ ，故有 $\pmb {\beta} = 2\pmb{\xi}_{1} - 2\pmb{\xi}_{2} + \pmb{\xi}_{3}$

（2）由于 $\mathbf{A}\pmb{\xi}_i = \lambda_i\pmb{\xi}_i$ ，故 $\pmb{A}^n\pmb{\xi}_i = \lambda_i^n\pmb{\xi}_i,i = 1,2,3.$ 因此

$$
\begin{array}{l} \boldsymbol {A} ^ {n} \boldsymbol {\beta} = \boldsymbol {A} ^ {n} \left(2 \boldsymbol {\xi} _ {1} - 2 \boldsymbol {\xi} _ {2} + \boldsymbol {\xi} _ {3}\right) = 2 \boldsymbol {A} ^ {n} \boldsymbol {\xi} _ {1} - 2 \boldsymbol {A} ^ {n} \boldsymbol {\xi} _ {2} + \boldsymbol {A} ^ {n} \boldsymbol {\xi} _ {3} \\ = 2 \binom {1} {1} - 2 ^ {n + 1} \binom {1} {2} + 3 ^ {n} \binom {1} {3} = \binom {2 - 2 ^ {n + 1} + 3 ^ {n}} {2 - 2 ^ {n + 2} + 3 ^ {n + 1}}. \\ \end{array}
$$

# 十、填空题

(1)【答案】 $\frac{5}{12}$ .

【解】由 $ABC \subset AB$ 且 $P(AB) = 0$ 得 $P(ABC) = 0$ ，则

$$
\begin{array}{l} P (\overline {{A}} \overline {{B}} \overline {{C}}) = P (\overline {{A + B + C}}) = 1 - P (A + B + C) \\ = 1 - P (A) - P (B) - P (C) + P (A B) + P (A C) + P (B C) - P (A B C) \\ = 1 - \frac {3}{4} + \frac {1}{6} = \frac {5}{1 2}. \\ \end{array}
$$

(2)【答案】 $\frac{4}{3}$ .

【解】 随机变量 $X$ 的概率密度为

$$
f (x) = \left\{ \begin{array}{l l} \mathrm {e} ^ {- x}, & x > 0, \\ 0, & x \leqslant 0, \end{array} \right.
$$

则 $E(X + \mathrm{e}^{-2X}) = \int_{0}^{+\infty}(x + \mathrm{e}^{-2x})\mathrm{e}^{-x}\mathrm{d}x = \int_{0}^{+\infty}x\mathrm{e}^{-x}\mathrm{d}x + \int_{0}^{+\infty}\mathrm{e}^{-3x}\mathrm{d}x$

$$
= \Gamma (2) + \frac {1}{3} \int_ {0} ^ {+ \infty} \mathrm {e} ^ {- 3 x} \mathrm {d} (3 x) = 1 + \frac {1}{3} = \frac {4}{3}.
$$

# 十一、【解】 随机变量 $X$ 的概率密度为

$$
f _ {X} (x) = \frac {1}{\sqrt {2 \pi} \sigma} \mathrm {e} ^ {- \frac {(x - \mu) ^ {2}}{2 \sigma^ {2}}}, - \infty <   x <   + \infty ;
$$

随机变量 $Y$ 的概率密度为

$$
f _ {Y} (y) = \left\{ \begin{array}{l l} \frac {1}{2 \pi}, & - \pi <   y <   \pi , \\ 0, & \text {其 他} \end{array} \right.
$$

因为随机变量 $X, Y$ 相互独立，所以 $(X, Y)$ 的联合密度函数为

$$
f (x, y) = f _ {X} (x) f _ {Y} (y) = \left\{ \begin{array}{l l} \frac {1}{2 \pi \sqrt {2 \pi} \sigma} \mathrm {e} ^ {- \frac {(x - \mu) ^ {2}}{2 \sigma^ {2}}}, & - \infty <   x <   + \infty , - \pi <   y <   \pi , \\ 0, & \text {其 他}. \end{array} \right.
$$

$$
\begin{array}{l} F _ {Z} (z) = P \{X + Y \leqslant z \} = \iint_ {x + y \leqslant z} f (x, y) d x d y \\ = \frac {1}{2 \pi} \int_ {- \pi} ^ {\pi} d y \int_ {- \infty} ^ {z - y} \frac {1}{\sqrt {2 \pi} \sigma} e ^ {- \frac {(x - \mu) ^ {2}}{2 \sigma^ {2}}} d x = \frac {1}{2 \pi} \int_ {- \pi} ^ {\pi} d y \int_ {- \infty} ^ {z - y} \frac {1}{\sqrt {2 \pi}} e ^ {- \frac {1}{2} (\frac {x - \mu}{\sigma}) ^ {2}} d \left(\frac {x - \mu}{\sigma}\right) \\ \xlongequal {\frac {x - \mu}{\sigma} = t} \frac {1}{2 \pi} \int_ {- \pi} ^ {\pi} d y \int_ {- \infty} ^ {\frac {z - y - \mu}{\sigma}} \frac {1}{\sqrt {2 \pi}} e ^ {- \frac {t ^ {2}}{2}} d t = \frac {1}{2 \pi} \int_ {- \pi} ^ {\pi} \Phi \left(\frac {z - y - \mu}{\sigma}\right) d y \\ = - \frac {\sigma}{2 \pi} \int_ {- \pi} ^ {\pi} \Phi \left(\frac {z - y - \mu}{\sigma}\right) d \left(\frac {z - y - \mu}{\sigma}\right) \frac {\frac {z - y - \mu}{\sigma} = t}{2 \pi} \frac {\sigma}{2 \pi} \int_ {\frac {z - \pi - \mu}{\sigma}} ^ {\frac {z + \pi - \mu}{\sigma}} \Phi (t) d t, \\ \end{array}
$$

故随机变量 $Z$ 的概率密度为

$$
f _ {Z} (z) = \frac {1}{2 \pi} \left[ \Phi \left(\frac {z + \pi - \mu}{\sigma}\right) - \Phi \left(\frac {z - \pi - \mu}{\sigma}\right) \right].
$$