# 1990年数学（一）真题解析

# 一、填空题

(1)【答案】 $x - 3y - z + 4 = 0.$

【解】 显然所求平面的法向量为 $n = \{-1,3,1\}$

所求平面为 $-(x - 1) + 3(y - 2) + (z + 1) = 0$ ，即 $x - 3y - z + 4 = 0$

(2)【答案】 $\mathrm{e}^{2a}$ .

【解】 $\lim_{x\to \infty}\left(\frac{x + a}{x - a}\right)^x = \lim_{x\to \infty}\left[\left(1 + \frac{2a}{x - a}\right)^{\frac{x - a}{2a}}\right]^x\cdot \frac{2a}{x - a} = \mathrm{e}^{2a}.$

（3）【答案】1.

【解】 $f[f(x)] = \left\{ \begin{array}{ll}1, & |f(x)|\leqslant 1,\\ 0, & |f(x)| > 1. \end{array} \right.$

因为 $|f(x)| \leqslant 1$ ，所以 $f[f(x)] = 1$

(4)【答案】 $\frac{1}{2}\left(1 - \frac{1}{\mathrm{e}^4}\right)$ .

【解】 改变积分次序得

$$
\int_ {0} ^ {2} \mathrm {d} x \int_ {x} ^ {2} \mathrm {e} ^ {- y ^ {2}} \mathrm {d} y = \int_ {0} ^ {2} \mathrm {e} ^ {- y ^ {2}} \mathrm {d} y \int_ {0} ^ {y} \mathrm {d} x = \int_ {0} ^ {2} y \mathrm {e} ^ {- y ^ {2}} \mathrm {d} y = - \frac {1}{2} \mathrm {e} ^ {- y ^ {2}} \left| _ {0} ^ {2} = \frac {1}{2} \left(1 - \frac {1}{\mathrm {e} ^ {4}}\right). \right.
$$

（5）【答案】2.

【解】 $\mathbf{A} = (\pmb{\alpha}_{1}^{\mathrm{T}},\pmb{\alpha}_{2}^{\mathrm{T}},\pmb{\alpha}_{3}^{\mathrm{T}},\pmb{\alpha}_{4}^{\mathrm{T}}) = \begin{bmatrix} 1 & 2 & 3 & 4\\ 2 & 3 & 4 & 5\\ 3 & 4 & 5 & 6\\ 4 & 5 & 6 & 7 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & 3 & 4\\ 0 & -1 & -2 & -3\\ 0 & -2 & -4 & -6\\ 0 & -3 & -6 & -9 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 2 & 3 & 4\\ 0 & 1 & 2 & 3\\ 0 & 0 & 0 & 0\\ 0 & 0 & 0 & 0 \end{bmatrix},$

因为 $r(\mathbf{A}) = 2$ ，所以该向量组的秩为2.

# 二、选择题

(1)【答案】 (A).

【解】 $F^{\prime}(x) = f(\mathrm{e}^{-x})(\mathrm{e}^{-x})^{\prime} - f(x) = -\mathrm{e}^{-x}f(\mathrm{e}^{-x}) - f(x)$ ，应选(A).

(2)【答案】 (A).

【解】 由 $f^{\prime}(x) = [f(x)]^{2}$ 得

$$
\begin{array}{l} f ^ {\prime \prime} (x) = 2 f (x) f ^ {\prime} (x) = 2 [ f (x) ] ^ {3}, \\ f ^ {\prime \prime} (x) = 2 \times 3 [ f (x) ] ^ {2} f ^ {\prime} (x) = 3! [ f (x) ] ^ {4}, \\ \end{array}
$$

由归纳法得 $f^{(n)}(x) = n!\left[f(x)\right]^{n + 1}$ ，应选(A).

（3）【答案】 (C).

【解】因为 $\left|\frac{\sin n\alpha}{n^2}\right| \leqslant \frac{1}{n^2}$ 且 $\sum_{n=1}^{\infty} \frac{1}{n^2}$ 收敛，所以 $\sum_{n=1}^{\infty} \frac{\sin n\alpha}{n^2}$ 绝对收敛；

因为 $\sum_{n = 1}^{\infty}\frac{1}{\sqrt{n}}$ 发散，所以 $\sum_{n = 1}^{\infty}\left(\frac{\sin n\alpha}{n^2} -\frac{1}{\sqrt{n}}\right)$ 发散，应选(C).

（4）【答案】 (D).

【解】因为 $\lim_{x\to 0}\frac{f(x)}{1 - \cos{x}} = 2$ ，所以由极限保号性，存在 $\delta >0$ ，当 $0 < |x| < \delta$ 时， $\frac{f(x)}{1 - \cos{x}} >0.$

因为 $1 - \cos x > 0$ ，所以 $f(x) > 0 = f(0)$ ，故 $x = 0$ 为极小值点，应选(D).

（5）【答案】 （B）.

【解】令 $k_{1}\pmb{\alpha}_{1} + k_{2}(\pmb{\alpha}_{1} - \pmb{\alpha}_{2}) = \mathbf{0}$ ，即 $(k_{1} + k_{2})\pmb{\alpha}_{1} - k_{2}\pmb{\alpha}_{2} = \mathbf{0}$

因为 $\alpha_{1},\alpha_{2}$ 线性无关，所以 $k_{1} + k_{2} = 0, - k_{2} = 0$ ，或 $k_{1} = 0,k_{2} = 0$ ，即 $\alpha_{1},\alpha_{1} - \alpha_{2}$ 线性无关，

又因为 $\alpha_{1},\alpha_{1} - \alpha_{2}$ 为齐次线性方程组 $AX = 0$ 的解，所以 $\alpha_{1},\alpha_{1} - \alpha_{2}$ 为齐次线性方程组 $AX = 0$ 的基础解系；

而 $\frac{\pmb{\beta}_1 + \pmb{\beta}_2}{2}$ 为非齐次线性方程组 $AX = b$ 的解，故 $k_{1}\alpha_{1} + k_{2}(\alpha_{1} - \alpha_{2}) + \frac{\pmb{\beta}_{1} + \pmb{\beta}_{2}}{2}$ 为 $AX = b$ 的通解，应选(B).三、

(1)【解】 $\int_0^1\frac{\ln(1 + x)}{(2 - x)^2}\mathrm{d}x = \int_0^1\ln (1 + x)\mathrm{d}\left(\frac{1}{2 - x}\right)$

$$
\begin{array}{l} = \left. \frac {\ln (1 + x)}{2 - x} \right| _ {0} ^ {1} + \int_ {0} ^ {1} \frac {1}{(x - 2) (x + 1)} d x \\ = \ln 2 + \frac {1}{3} \ln \left| \frac {x - 2}{x + 1} \right| _ {0} ^ {1} = \ln 2 - \frac {2}{3} \ln 2 = \frac {1}{3} \ln 2. \\ \end{array}
$$

(2)【解】 $\frac{\partial z}{\partial x} = 2f_1' + y\cos x \cdot f_2'$ ,

$$
\begin{array}{l} \frac {\partial^ {2} z}{\partial x \partial y} = 2 \left(- f _ {1 1} ^ {\prime \prime} + \sin x \cdot f _ {1 2} ^ {\prime \prime}\right) + \cos x \cdot f _ {2} ^ {\prime} + y \cos x \left(- f _ {2 1} ^ {\prime \prime} + \sin x \cdot f _ {2 2} ^ {\prime \prime}\right) \\ = - 2 f _ {1 1} ^ {\prime \prime} + (2 \sin x - y \cos x) \cdot f _ {1 2} ^ {\prime \prime} + \cos x \cdot f _ {2} ^ {\prime} + y \sin x \cos x \cdot f _ {2 2} ^ {\prime \prime}. \\ \end{array}
$$

（3）【解】 特征方程为 $\lambda^2 + 4\lambda + 4 = 0$ ，特征根为 $\lambda_1 = \lambda_2 = -2$

$y^{\prime \prime} + 4y^{\prime} + 4y = 0$ 的通解为 $y = (C_1 + C_2x)\mathrm{e}^{-2x}$

令 $y^{\prime \prime} + 4y^{\prime} + 4y = \mathrm{e}^{-2x}$ 的特解为 $y_0(x) = ax^2\mathrm{e}^{-2x}$ ，代入得 $a = \frac{1}{2}$

故 $y^{\prime \prime} + 4y^{\prime} + 4y = \mathrm{e}^{-2x}$ 的通解为

$$
y = (C _ {1} + C _ {2} x) \mathrm {e} ^ {- 2 x} + \frac {1}{2} x ^ {2} \mathrm {e} ^ {- 2 x} (C _ {1}, C _ {2} \text {为 任 意 常 数}).
$$

四、【解】 由 $\lim_{n\to \infty}\left|\frac{a_{n + 1}}{a_n}\right| = 1$ 得幂级数的收敛半径 $R = 1$

当 $x = \pm 1$ 时， $(2n + 1)(\pm 1)^n \to \infty (n \to \infty)$ ，即 $x = \pm 1$ 时，幂级数发散，

故幂级数的收敛域为 $(-1, 1)$ .

令 $S(x) = \sum_{n=0}^{\infty}(2n+1)x^{n}$ ,

则 $S(x) = 2x\sum_{n = 1}^{\infty}nx^{n - 1} + \sum_{n = 0}^{\infty}x^{n} = 2x(\sum_{n = 1}^{\infty}x^{n})^{\prime} + \frac{1}{1 - x}$

$$
= 2 x \left(\frac {x}{1 - x}\right) ^ {\prime} + \frac {1}{1 - x} = \frac {1 + x}{(1 - x) ^ {2}}.
$$

# 五、【解】 方法一

令 $\Sigma_0: z = 0 (x^2 + y^2 \leqslant 4)$ ，取下侧，

$$
I = \iint_ {\Sigma + \Sigma_ {0}} y z \mathrm {d} z \mathrm {d} x + 2 \mathrm {d} x \mathrm {d} y - \iint_ {\Sigma_ {0}} y z \mathrm {d} z \mathrm {d} x + 2 \mathrm {d} x \mathrm {d} y,
$$

而 $\iint_{\Sigma + \Sigma_0} yz \, \mathrm{d}z \, \mathrm{d}x + 2 \, \mathrm{d}x \, \mathrm{d}y = \iiint_{\Omega} z \, \mathrm{d}v = \int_0^{2\pi} \, \mathrm{d}\theta \int_0^{\frac{\pi}{2}} \, \mathrm{d}\varphi \int_0^2 r^3 \sin \varphi \cos \varphi \, \mathrm{d}r$

$$
= 2 \pi \int_ {0} ^ {\frac {\pi}{2}} \sin \varphi \cos \varphi d \varphi \int_ {0} ^ {2} r ^ {3} d r = 4 \pi ;
$$

$$
\iint_ {\Sigma_ {0}} y z \mathrm {d} z \mathrm {d} x + 2 \mathrm {d} x \mathrm {d} y = \iint_ {\Sigma_ {0}} 2 \mathrm {d} x \mathrm {d} y = - 2 \iint_ {x ^ {2} + y ^ {2} \leqslant 4} \mathrm {d} x \mathrm {d} y = - 8 \pi ,
$$

故 $I = 12\pi$

方法二

$$
I = \iint_ {\Sigma} y z \mathrm {d} z \mathrm {d} x + 2 \mathrm {d} x \mathrm {d} y = \iint_ {\Sigma} y z \mathrm {d} z \mathrm {d} x + 2 \iint_ {\Sigma} \mathrm {d} x \mathrm {d} y,
$$

令曲面 $\Sigma$ 位于 $xOz$ 平面右侧的部分为 $\Sigma_{1}$ ，由对称性得

$$
\begin{array}{l} \iint_ {\Sigma} y z \mathrm {d} z \mathrm {d} x = 2 \iint_ {\Sigma_ {1}} y z \mathrm {d} z \mathrm {d} x = 2 \iint_ {D _ {x z}} z \sqrt {4 - x ^ {2} - z ^ {2}} \mathrm {d} z \mathrm {d} x \\ = 2 \int_ {0} ^ {\pi} \mathrm {d} \theta \int_ {0} ^ {2} r ^ {2} \sin \theta \cdot \sqrt {4 - r ^ {2}} \mathrm {d} r = 4 \int_ {0} ^ {2} r ^ {2} \sqrt {4 - r ^ {2}} \mathrm {d} r \\ \frac {r = 2 \sin t}{4} \int_ {0} ^ {\frac {\pi}{2}} 4 \sin^ {2} t \cdot 4 \cos^ {2} t d t = 6 4 \int_ {0} ^ {\frac {\pi}{2}} (\sin^ {2} t - \sin^ {4} t) d t \\ = 6 4 \left(\frac {1}{2} \cdot \frac {\pi}{2} - \frac {3}{4} \cdot \frac {1}{2} \cdot \frac {\pi}{2}\right) = 4 \pi ; \\ \end{array}
$$

$$
2 \iint_ {\Sigma} \mathrm {d} x \mathrm {d} y = 2 \iint_ {D _ {x y}} \mathrm {d} x \mathrm {d} y = 2 \times 4 \pi = 8 \pi ,
$$

故 $I = \iint_{\Sigma} yz \, \mathrm{d}z \, \mathrm{d}x + 2 \, \mathrm{d}x \, \mathrm{d}y = 12\pi.$

六、【证明】因为 $f(x)$ 不恒为常数，且 $f(a) = f(b)$ ，所以存在 $c \in (a, b)$ ，使得 $f(c) \neq f(a)$ ，不妨设 $f(c) > f(a)$ ，由拉格朗日中值定理，存在 $\xi \in (a, c) \subset (a, b)$ ，使得

$$
f ^ {\prime} (\xi) = \frac {f (c) - f (a)}{c - a} > 0.
$$

七、【解】由 $\mathbf{A}(\mathbf{E} - \mathbf{C}^{-1}\mathbf{B})^{\mathrm{T}}\mathbf{C}^{\mathrm{T}} = \mathbf{E}$ 得 $\mathbf{A}[C(\mathbf{E} - \mathbf{C}^{-1}\mathbf{B})]^{\mathrm{T}} = \mathbf{E}$ ，即 $\mathbf{A}(\mathbf{C} - \mathbf{B})^{\mathrm{T}} = \mathbf{E}$ ，解得

$$
\mathbf {A} = \left[ (\mathbf {C} - \mathbf {B}) ^ {\mathrm {T}} \right] ^ {- 1},
$$

$$
\text {而} \pmb {C} - \pmb {B} = \left[ \begin{array}{c c c c} {1} & {2} & {3} & {4} \\ {0} & {1} & {2} & {3} \\ {0} & {0} & {1} & {2} \\ {0} & {0} & {0} & {1} \end{array} \right], \quad (\pmb {C} - \pmb {B}) ^ {\mathrm {T}} = \left[ \begin{array}{c c c c} {1} & {0} & {0} & {0} \\ {2} & {1} & {0} & {0} \\ {3} & {2} & {1} & {0} \\ {4} & {3} & {2} & {1} \end{array} \right],
$$

$$
\text {由} \left[\begin{array}{c c c c c c c c}1&0&0&0&1&0&0&0\\2&1&0&0&0&1&0&0\\3&2&1&0&0&0&1&0\\4&3&2&1&0&0&0&1\end{array}\right]\rightarrow \left[\begin{array}{c c c c c c c c}1&0&0&0&1&0&0&0\\0&1&0&0&- 2&1&0&0\\0&0&1&0&1&- 2&1&0\\0&0&0&1&0&1&- 2&1\end{array}\right], \text {得}
$$

$$
\mathbf {A} = \left( \begin{array}{c c c c} 1 & 0 & 0 & 0 \\ - 2 & 1 & 0 & 0 \\ 1 & - 2 & 1 & 0 \\ 0 & 1 & - 2 & 1 \end{array} \right).
$$

八、【解】 令 $\mathbf{A} = \begin{pmatrix} 1 & -2 & 2 \\ -2 & 4 & -4 \\ 2 & -4 & 4 \end{pmatrix}, \mathbf{X} = \begin{pmatrix} x_1 \\ x_2 \\ x_3 \end{pmatrix}$ ，则 $f = \mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}$

由 $|\lambda \pmb {E} - \pmb {A}| = \left| \begin{array}{ccc}\lambda -1 & 2 & -2\\ 2 & \lambda -4 & 4\\ -2 & 4 & \lambda -4 \end{array} \right| = \lambda^2 (\lambda -9) = 0$ ，得 $\lambda_1 = \lambda_2 = 0,\lambda_3 = 9$

由 $0E - A\to \left( \begin{array}{ccc}1 & -2 & 2\\ 0 & 0 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_{1} = \lambda_{2} = 0$ 对应的线性无关的特征向量为

$$
\pmb {\alpha} _ {1} = \binom {2} {1}, \quad \pmb {\alpha} _ {2} = \binom {- 2} {0};
$$

由 $9E - A \rightarrow \left( \begin{array}{ccc}1 & 0 & -\frac{1}{2}\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_{3} = 9$ 对应的特征向量为 $\pmb{\alpha}_{3} = \binom{1}{-2}$

令 $\pmb{\beta}_{1} = \pmb{\alpha}_{1} = \binom{2}{1}$ ， $\pmb{\beta}_{2} = \pmb{\alpha}_{2} - \frac{(\pmb{\alpha}_{2},\pmb{\beta}_{1})}{(\pmb{\beta}_{1},\pmb{\beta}_{1})}\pmb{\beta}_{1} = \binom{-2}{0} + \frac{4}{5}\binom{2}{1} = \frac{1}{5}\binom{-2}{4}$ ， $\pmb{\beta}_{3} = \binom{1}{-2}$ ，

规范化得 $\pmb{\gamma}_{1} = \frac{1}{\sqrt{5}}\binom{2}{0},\quad \pmb{\gamma}_{2} = \frac{1}{3\sqrt{5}}\binom{-2}{4},\quad \pmb{\gamma}_{3} = \frac{1}{3}\binom{1}{2},$

令 $Q = \left[ \begin{array}{ccc} \frac{2}{\sqrt{5}} & -\frac{2}{3\sqrt{5}} & \frac{1}{3}\\ \frac{1}{\sqrt{5}} & \frac{4}{3\sqrt{5}} & -\frac{2}{3}\\ 0 & \frac{5}{3\sqrt{5}} & \frac{2}{3} \end{array} \right]$ ，所求的正交变换为 $X = QY$

则 $f = \mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}\frac{\mathbf{X} = \mathbf{Q}\mathbf{Y}}{}9y_{3}^{2}.$

九、【解】设点 $P$ 的坐标为 $(x,y),\overrightarrow{OP} = \{x,y\}$ ， $|\pmb {F}| = \sqrt{x^2 + y^2}$

因为 $\pmb{F}$ 的方向垂直于 $OP$ 且与 $y$ 轴正向的夹角小于 $\frac{\pi}{2}$

所以 $\pmb{F}^{0} = \frac{1}{\sqrt{x^{2} + y^{2}}}\{-y,x\}$ ，则 $\pmb {F} = |\pmb {F}|\cdot \pmb{F}^{0} = \{-y,x\}$

$$
W = \int_ {L} (- y) d x + x d y = \oint_ {L + B A} (- y) d x + x d y + \int_ {\overline {{A B}}} (- y) d x + x d y,
$$

而 $\oint_{L + BA}(-y)\mathrm{d}x + x\mathrm{d}y = 2\iint_{D}\mathrm{d}x\mathrm{d}y = 2\times \frac{1}{2}\pi (\sqrt{2})^{2} = 2\pi ,$

$\overline{AB}$ ： $y = x + 1$ （起点 $x = 1$ ，终点 $x = 3$ )，则

$$
\int_ {\overline {{A B}}} (- y) \mathrm {d} x + x \mathrm {d} y = \int_ {1} ^ {3} - (x + 1) \mathrm {d} x + x \mathrm {d} x = - 2,
$$

故 $W = 2(\pi -1)$

# 十、填空题

(1)【答案】 $\left\{ \begin{array}{ll} \frac{1}{2}\mathrm{e}^{x}, & x < 0, \\ 1 - \frac{1}{2}\mathrm{e}^{-x}, & x \geqslant 0. \end{array} \right.$

【解】 $F(x) = P\{X \leqslant x\} = \int_{-\infty}^{x} f(x) \, \mathrm{d}x,$

当 $x < 0$ 时， $F(x) = \frac{1}{2}\int_{-\infty}^{x}\mathrm{e}^{x}\mathrm{d}x = \frac{1}{2}\mathrm{e}^{x}$

当 $x \geqslant 0$ 时， $F(x) = \int_{-\infty}^{0} f(x) \, \mathrm{d}x + \int_{0}^{x} f(x) \, \mathrm{d}x = \frac{1}{2} + \frac{1}{2} \int_{0}^{x} \mathrm{e}^{-x} \, \mathrm{d}x = 1 - \frac{1}{2} \mathrm{e}^{-x}$ ，

故 $F(x) = \left\{ \begin{array}{ll} \frac{1}{2}\mathrm{e}^{x}, & x < 0,\\ 1 - \frac{1}{2}\mathrm{e}^{-x}, & x\geqslant 0. \end{array} \right.$

(2)【答案】0.3.

【解】由 $P(A) = 0.4, P(B) = 0.3, P(A + B) = 0.6$ 得

$$
P (A B) = P (A) + P (B) - P (A + B) = 0. 1,
$$

故 $P(A\overline{B}) = P(A) - P(AB) = 0.4 - 0.1 = 0.3.$

(3)【答案】4.

【解】因为 $X$ 服从参数为2的泊松分布，所以 $E(X) = 2$

于是 $E(Z) = 3E(X) - 2 = 6 - 2 = 4.$

十一、【解】区域 $D$ 的面积 $S = 1$ ，则 $(X,Y)$ 的联合概率密度为

$$
f (x, y) = \left\{ \begin{array}{l l} 1, & (x, y) \in D, \\ 0, & (x, y) \notin D. \end{array} \right.
$$

$$
f _ {X} (x) = \int_ {- \infty} ^ {+ \infty} f (x, y) d y,
$$

当 $x \leqslant 0$ 或 $x \geqslant 1$ 时， $f_{X}(x) = 0$

当 $0 < x < 1$ 时， $f_{X}(x) = \int_{-x}^{x} 1 \, \mathrm{d}y = 2x$

则随机变量 $X$ 的边缘概率密度为 $f_{X}(x) = \left\{ \begin{array}{ll}2x, & 0 < x < 1,\\ 0, & \text{其他}. \end{array} \right.$

由 $E(X) = \int_0^1 xf_X(x)\mathrm{d}x = \int_0^1 2x^2\mathrm{d}x = \frac{2}{3}$

$$
E (X ^ {2}) = \int_ {0} ^ {1} x ^ {2} f _ {X} (x) \mathrm {d} x = \int_ {0} ^ {1} 2 x ^ {3} \mathrm {d} x = \frac {1}{2}, \text {得} D (X) = \frac {1}{2} - \frac {4}{9} = \frac {1}{1 8},
$$

故 $D(Z) = D(2X + 1) = 4D(X) = \frac{2}{9}.$