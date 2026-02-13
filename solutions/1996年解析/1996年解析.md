# 1996年数学(一）真题解析

# 一、填空题

(1)【答案】 $\ln 2$

【解】 由 $\lim_{x\to \infty}\left(\frac{x + 2a}{x - a}\right)^{x} = \lim_{x\to \infty}\left[\left(1 + \frac{3a}{x - a}\right)^{\frac{x - a}{3a}}\right]^{x\frac{3a}{x - a}} = \mathrm{e}^{3a} = 8,$

得 $3a = 3\ln 2$ ，即得 $a = \ln 2$

(2)【答案】 $2x + 2y - 3z = 0$

【解】设所求的平面方程为 $\pi :Ax + By + Cz + D = 0$

因为该平面经过原点，所以 $D = 0$

又因为该平面经过点 $(6, -3, 2)$ ，所以 $6A - 3B + 2C = 0$

又因为该平面与平面 $4x - y + 2z = 8$ 垂直，则 $4A - B + 2C = 0$

解得 $B = A, C = -\frac{3}{2} A$ ，故所求平面为 $\pi: Ax + Ay - \frac{3}{2} Az = 0$ ，即 $\pi: 2x + 2y - 3z = 0$ .

(3)【答案】 $y = \mathrm{e}^{x}(C_{1}\cos x + C_{2}\sin x) + \mathrm{e}^{x}(C_{1},C_{2}$ 为任意常数).

【解】特征方程为 $\lambda^2 - 2\lambda + 2 = 0$ ，特征根为 $\lambda_{1,2} = 1 \pm \mathrm{i}$ ，

$y^{\prime \prime} - 2y^{\prime} + 2y = 0$ 的通解为 $y = \mathrm{e}^{x}(C_{1}\cos x + C_{2}\sin x)$

显然 $y = \mathrm{e}^{x}$ 为方程 $y^{\prime \prime} - 2y^{\prime} + 2y = \mathrm{e}^{x}$ 的一个特解，

故 $y^{\prime \prime} - 2y^{\prime} + 2y = \mathrm{e}^{x}$ 的通解为 $y = \mathrm{e}^{x}(C_{1}\cos x + C_{2}\sin x) + \mathrm{e}^{x}(C_{1},C_{2}$ 为任意常数).

(4)【答案】 $\frac{1}{2}$ .

【解】 $\frac{\partial u}{\partial x} = \frac{1}{x + \sqrt{y^2 + z^2}},$

$$
\begin{array}{l} \frac {\partial u}{\partial y} = \frac {1}{x + \sqrt {y ^ {2} + z ^ {2}}} \cdot \frac {y}{\sqrt {y ^ {2} + z ^ {2}}}, \\ \frac {\partial u}{\partial z} = \frac {1}{x + \sqrt {y ^ {2} + z ^ {2}}} \cdot \frac {z}{\sqrt {y ^ {2} + z ^ {2}}}, \\ \left. \frac {\partial u}{\partial x} \right| _ {(1, 0, 1)} = \frac {1}{2}, \quad \left. \frac {\partial u}{\partial y} \right| _ {(1, 0, 1)} = 0, \quad \left. \frac {\partial u}{\partial z} \right| _ {(1, 0, 1)} = \frac {1}{2}, \quad \overrightarrow {A B} = \{2, - 2, 1 \}, \\ \cos \alpha = \frac {2}{3}, \quad \cos \beta = - \frac {2}{3}, \quad \cos \gamma = \frac {1}{3}, \\ \end{array}
$$

则所求的方向导数为 $\frac{\partial u}{\partial x}\Big|_{(1,0,1)}\cos \alpha +\frac{\partial u}{\partial y}\Big|_{(1,0,1)}\cos \beta +\frac{\partial u}{\partial z}\Big|_{(1,0,1)}\cos \gamma = \frac{1}{2}.$

（5）【答案】2.

【解】因为 $|\pmb {B}| = \left| \begin{array}{rrr}1 & 0 & 2\\ 0 & 2 & 0\\ -1 & 0 & 3 \end{array} \right| = 10\neq 0$ ，所以矩阵 $\pmb{B}$ 可逆，

由矩阵秩的性质得 $r(\mathbf{AB}) = r(\mathbf{A}) = 2$

# 二、选择题

(1)【答案】 (D).

【解】 $P(x,y) = \frac{x + ay}{(x + y)^2},\quad Q(x,y) = \frac{y}{(x + y)^2},$

$$
\frac {\partial P}{\partial y} = \frac {a (x + y) ^ {2} - 2 (x + y) (x + a y)}{(x + y) ^ {4}} = \frac {a (x + y) - 2 (x + a y)}{(x + y) ^ {3}}, \quad \frac {\partial Q}{\partial x} = \frac {- 2 y}{(x + y) ^ {3}},
$$

由 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$ 得 $a(x + y) - 2(x + ay) = -2y$ ，得 $a = 2$ ，应选(D).

(2)【答案】 (B).

【解】因为 $\lim_{x\to 0}\frac{f''(x)}{|x|} = 1 > 0$ ，所以由极限保号性，存在 $\delta >0$ ，当 $0 < |x| < \delta$ 时， $\frac{f''(x)}{|x|} >0$ ，即 $f''(x) > 0$ 从而 $f^{\prime}(x)$ 在 $(-\delta ,\delta)$ 内单调递增.

再由 $f^{\prime}(0) = 0$ 得 $\left\{ \begin{array}{l} f^{\prime}(x) < 0, x \in (-\delta, 0), \\ f^{\prime}(x) > 0, x \in (0, \delta) \end{array} \right.$ 得 $f(0)$ 为 $f(x)$ 的极小值，应选(B).

（3）【答案】 （A).

【解】 因为正项级数 $\sum_{n = 1}^{\infty}a_{n}$ 收敛，所以 $\sum_{n = 1}^{\infty}a_{2n}$ 收敛，

由 $\left|(-1)^n\left(n\tan \frac{\lambda}{n}\right)a_{2n}\right|\sim \lambda a_{2n}$ 得级数 $\sum_{n = 1}^{\infty}\left|(-1)^n\left(n\tan \frac{\lambda}{n}\right)a_{2n}\right|$ 收敛，

故 $\sum_{n = 1}^{\infty}(-1)^{n}\left(n\tan {\frac{\lambda}{n}}\right)a_{2n}$ 绝对收敛，应选（A）.

（4）【答案】 (C).

【解】 $F(x) = \int_{0}^{x}(x^{2} - t^{2})f(t)\mathrm{d}t = x^{2}\int_{0}^{x}f(t)\mathrm{d}t - \int_{0}^{x}t^{2}f(t)\mathrm{d}t,\quad F^{\prime}(x) = 2x\int_{0}^{x}f(t)\mathrm{d}t,$

由 $\lim_{x\to 0}\frac{F'(x)}{x^3} = 2\lim_{x\to 0}\frac{\int_0^xf(t)\mathrm{d}t}{x^2} = \lim_{x\to 0}\frac{f(x) - f(0)}{x} = f'(0)\neq 0$ 得 $k = 3$

（5）【答案】 (D).

【解】 将行列式按第一行展开，得

$$
\begin{array}{l} \left| \begin{array}{c c c c} a _ {1} & 0 & 0 & b _ {1} \\ 0 & a _ {2} & b _ {2} & 0 \\ 0 & b _ {3} & a _ {3} & 0 \\ b _ {4} & 0 & 0 & a _ {4} \end{array} \right| = a _ {1} A _ {1 1} + b _ {1} A _ {1 4} = a _ {1} M _ {1 1} - b _ {1} M _ {1 4} \\ = a _ {1} \left| \begin{array}{c c c} a _ {2} & b _ {2} & 0 \\ b _ {3} & a _ {3} & 0 \\ 0 & 0 & a _ {4} \end{array} \right| - b _ {1} \left| \begin{array}{c c c} 0 & a _ {2} & b _ {2} \\ 0 & b _ {3} & a _ {3} \\ b _ {4} & 0 & 0 \end{array} \right| \\ = a _ {1} a _ {4} \left(a _ {2} a _ {3} - b _ {2} b _ {3}\right) - b _ {1} b _ {4} \left(a _ {2} a _ {3} - b _ {2} b _ {3}\right) \\ = \left(a _ {1} a _ {4} - b _ {1} b _ {4}\right) \left(a _ {2} a _ {3} - b _ {2} b _ {3}\right), \\ \end{array}
$$

应选(D).

# 三、

(1)【解】 弧长 $l = 2\int_{0}^{\pi}\sqrt{r^{2}(\theta) + r^{\prime 2}(\theta)}\mathrm{d}\theta = 2\int_{0}^{\pi}\sqrt{a^{2}(1 + \cos\theta)^{2} + a^{2}\sin^{2}\theta}\mathrm{d}\theta$

$$
\begin{array}{l} = 2 \sqrt {2} a \int_ {0} ^ {\pi} \sqrt {1 + \cos \theta} d \theta = 4 a \int_ {0} ^ {\pi} \cos \frac {\theta}{2} d \theta \\ = 8 a \int_ {0} ^ {\pi} \cos \frac {\theta}{2} \mathrm {d} \left(\frac {\theta}{2}\right) = 8 a \int_ {0} ^ {\frac {\pi}{2}} \cos t \mathrm {d} t = 8 a. \\ \end{array}
$$

(2)【解】 令 $y = f(x) = \sqrt{6 + x}$

因为 $f^{\prime}(x) = \frac{1}{2\sqrt{6 + x}} >0$ ，所以 $\{x_{n}\}$ 单调.

由 $x_{1} = 10 > x_{2} = 4$ 得数列 $\{x_{n}\}$ 单调递减，

再由 $x_{n} > 0$ 得数列 $\{x_{n}\}$ 单调递减且有下界，故数列 $\{x_{n}\}$ 收敛.

令 $\lim_{n\to \infty}x_n = A$ ，由 $x_{n + 1} = \sqrt{6 + x_n}$ 得 $A = \sqrt{6 + A}$ ，解得 $A = 3$

四、

(1)【解】 令 $S_{1}:z = 1(x^{2} + y^{2}\leqslant 1)$ ，取下侧，则

$$
\iint_ {S} (2 x + z) \mathrm {d} y \mathrm {d} z + z \mathrm {d} x \mathrm {d} y = \iint_ {S + S _ {1}} (2 x + z) \mathrm {d} y \mathrm {d} z + z \mathrm {d} x \mathrm {d} y - \iint_ {S _ {1}} (2 x + z) \mathrm {d} y \mathrm {d} z + z \mathrm {d} x \mathrm {d} y,
$$

由高斯公式得

$$
\oiint_ {S + S _ {1}} (2 x + z) \mathrm {d} y \mathrm {d} z + z \mathrm {d} x \mathrm {d} y = - 3 \iiint_ {\Omega} \mathrm {d} v = - 3 \int_ {0} ^ {1} \mathrm {d} z \iint_ {x ^ {2} + y ^ {2} \leqslant z} \mathrm {d} x \mathrm {d} y = - 3 \pi \int_ {0} ^ {1} z \mathrm {d} z = - \frac {3 \pi}{2};
$$

$$
\iint_ {S _ {1}} (2 x + z) \mathrm {d} y \mathrm {d} z + z \mathrm {d} x \mathrm {d} y = - \iint_ {x ^ {2} + y ^ {2} \leqslant 1} \mathrm {d} x \mathrm {d} y = - \pi ,
$$

故 $\iint_{S} (2x + z) \, \mathrm{d}y \, \mathrm{d}z + z \, \mathrm{d}x \, \mathrm{d}y = -\frac{\pi}{2}$ .

(2)【解】 $\frac{\partial z}{\partial x} = \frac{\partial z}{\partial u} \cdot \frac{\partial u}{\partial x} + \frac{\partial z}{\partial v} \cdot \frac{\partial v}{\partial x} = \frac{\partial z}{\partial u} + \frac{\partial z}{\partial v}, \quad \frac{\partial z}{\partial y} = \frac{\partial z}{\partial u} \cdot \frac{\partial u}{\partial y} + \frac{\partial z}{\partial v} \cdot \frac{\partial v}{\partial y} = -2 \frac{\partial z}{\partial u} + a \frac{\partial z}{\partial v},$

$$
\frac {\partial^ {2} z}{\partial x ^ {2}} = \frac {\partial^ {2} z}{\partial u ^ {2}} \cdot \frac {\partial u}{\partial x} + \frac {\partial^ {2} z}{\partial u \partial v} \cdot \frac {\partial v}{\partial x} + \frac {\partial^ {2} z}{\partial v \partial u} \cdot \frac {\partial u}{\partial x} + \frac {\partial^ {2} z}{\partial v ^ {2}} \cdot \frac {\partial v}{\partial x} = \frac {\partial^ {2} z}{\partial u ^ {2}} + 2 \frac {\partial^ {2} z}{\partial v \partial u} + \frac {\partial^ {2} z}{\partial v ^ {2}},
$$

$$
\frac {\partial^ {2} z}{\partial x \partial y} = - 2 \frac {\partial^ {2} z}{\partial u ^ {2}} + a \frac {\partial^ {2} z}{\partial u \partial v} - 2 \frac {\partial^ {2} z}{\partial v \partial u} + a \frac {\partial^ {2} z}{\partial v ^ {2}} = - 2 \frac {\partial^ {2} z}{\partial u ^ {2}} + (a - 2) \frac {\partial^ {2} z}{\partial v \partial u} + a \frac {\partial^ {2} z}{\partial v ^ {2}},
$$

$$
\begin{array}{l} \frac {\partial^ {2} z}{\partial y ^ {2}} = - 2 \left(\frac {\partial^ {2} z}{\partial u ^ {2}} \cdot \frac {\partial u}{\partial y} + \frac {\partial^ {2} z}{\partial u \partial v} \cdot \frac {\partial v}{\partial y}\right) + a \left(\frac {\partial^ {2} z}{\partial v \partial u} \cdot \frac {\partial u}{\partial y} + \frac {\partial^ {2} z}{\partial v ^ {2}} \cdot \frac {\partial v}{\partial y}\right) \\ = - 2 \left(- 2 \frac {\partial^ {2} z}{\partial u ^ {2}} + a \frac {\partial^ {2} z}{\partial u \partial v}\right) + a \left(- 2 \frac {\partial^ {2} z}{\partial v \partial u} + a \frac {\partial^ {2} z}{\partial v ^ {2}}\right) \\ = 4 \frac {\partial^ {2} z}{\partial u ^ {2}} - 4 a \frac {\partial^ {2} z}{\partial u \partial v} + a ^ {2} \frac {\partial^ {2} z}{\partial v ^ {2}}, \\ \end{array}
$$

代入整理得

$$
(5 a + 1 0) \frac {\partial^ {2} z}{\partial v \partial u} + (- a ^ {2} + a + 6) \frac {\partial^ {2} z}{\partial v ^ {2}} = 0,
$$

于是 $\left\{ \begin{array}{l}5a + 10\neq 0,\\ -a^2 +a + 6 = 0, \end{array} \right.$ 解得 $a = 3$

五、【解】 令 $S(x) = \sum_{n=2}^{\infty} \frac{x^n}{n^2 - 1} (-1 < x < 1)$ ，

则 $S(x) = \frac{1}{2}\left(\sum_{n = 2}^{\infty}\frac{x^n}{n - 1} -\sum_{n = 2}^{\infty}\frac{x^n}{n + 1}\right),$

$$
S (0) = 0;
$$

当 $x \neq 0$ 时，

$$
\begin{array}{l} S (x) = \frac {x}{2} \sum_ {n = 2} ^ {\infty} \frac {x ^ {n - 1}}{n - 1} - \frac {1}{2 x} \sum_ {n = 2} ^ {\infty} \frac {x ^ {n + 1}}{n + 1} = \frac {x}{2} \sum_ {n = 1} ^ {\infty} \frac {x ^ {n}}{n} - \frac {1}{2 x} \sum_ {n = 3} ^ {\infty} \frac {x ^ {n}}{n} \\ = - \frac {x}{2} \ln (1 - x) - \frac {1}{2 x} \left(\sum_ {n = 1} ^ {\infty} \frac {x ^ {n}}{n} - x - \frac {x ^ {2}}{2}\right) \\ \end{array}
$$

$$
= \left(\frac {1}{2 x} - \frac {x}{2}\right) \ln (1 - x) + \frac {1}{2} + \frac {x}{4},
$$

故 $\sum_{n = 2}^{\infty}\frac{1}{(n^{2} - 1)2^{n}} = S\left(\frac{1}{2}\right) = \frac{5}{8} -\frac{3}{4}\ln 2.$

六、【解】 曲线 $y = f(x)$ 在点 $(x, f(x))$ 的切线为

$$
Y - f (x) = f ^ {\prime} (x) (X - x),
$$

令 $X = 0$ 得 $Y = f(x) - xf'(x)$

由题意得 $f(x) - xf'(x) = \frac{1}{x}\int_{0}^{x}f(t)\mathrm{d}t$ ，整理得 $xf(x) - x^{2}f^{\prime}(x) = \int_{0}^{x}f(t)\mathrm{d}t$

两边求导得 $f^{\prime}(x) + xf^{\prime \prime}(x) = 0$ ，即 $[xf'(x)]' = 0$

解得 $x f^{\prime}(x) = C_{1}$ ，或 $f^{\prime}(x) = \frac{C_{1}}{x}$ ，故 $f(x) = C_{1} \ln x + C_{2}$ （ $C_{1}, C_{2}$ 为任意常数）.

# 七、【证明】（1）由泰勒公式得

$$
f (0) = f (c) + f ^ {\prime} (c) (0 - c) + \frac {f ^ {\prime \prime} (\xi_ {1})}{2 !} (0 - c) ^ {2}, \quad 0 <   \xi_ {1} <   c,
$$

$$
f (1) = f (c) + f ^ {\prime} (c) (1 - c) + \frac {f ^ {\prime \prime} (\xi_ {2})}{2 !} (1 - c) ^ {2}, \quad c <   \xi_ {2} <   1,
$$

两式相减得

$$
f ^ {\prime} (c) = f (1) - f (0) + \frac {c ^ {2}}{2} f ^ {\prime \prime} (\xi_ {1}) - \frac {(1 - c) ^ {2}}{2} f ^ {\prime \prime} (\xi_ {2}).
$$

(2) $|f'(c)| \leqslant |f(1)| + |f(0)| + \frac{c^2}{2} |f''(\xi_1)| + \frac{(1 - c)^2}{2} |f''(\xi_2)|$

$$
\leqslant 2 a + \frac {b}{2} \left[ c ^ {2} + (1 - c) ^ {2} \right],
$$

由 $c^2 \leqslant c, (1 - c)^2 \leqslant 1 - c$ 得 $c^2 + (1 - c)^2 \leqslant 1$ ，故 $|f'(c)| \leqslant 2a + \frac{b}{2}$ 。

八、【证明】（1）令 $\pmb{\xi}^{\mathrm{T}}\pmb {\xi} = \pmb{k}$

$$
\boldsymbol {A} ^ {2} = (\boldsymbol {E} - \boldsymbol {\xi} \boldsymbol {\xi} ^ {\mathrm {T}}) (\boldsymbol {E} - \boldsymbol {\xi} \boldsymbol {\xi} ^ {\mathrm {T}}) = \boldsymbol {E} + (k - 2) \boldsymbol {\xi} \boldsymbol {\xi} ^ {\mathrm {T}},
$$

则 $\mathbf{A}^2 = \mathbf{A}$ 的充分必要条件是 $k = 1$ ，即 $\pmb{\xi}^{\mathrm{T}}\pmb {\xi} = 1$

（2）方法一 当 $\pmb{\xi}^{\mathrm{T}}\pmb {\xi} = 1$ 时，由 $A^2 = A$ 得 $A(E - A) = O$ ，从而 $r(A) + r(E - A)\leqslant n$

再由 $r(\mathbf{A}) + r(\mathbf{E} - \mathbf{A})\geqslant r(\mathbf{E}) = n$ 得 $r(\mathbf{A}) + r(\mathbf{E} - \mathbf{A}) = n$

因为 $\pmb{\xi}$ 为非零向量，所以 $\pmb {\xi}\pmb{\xi}^{\mathrm{T}}\neq \pmb{0}$ ，从而 $E - A = \xi \xi^{\mathrm{T}}\neq O$ ，即 $r(E - A)\geqslant 1$

故 $r(\mathbf{A}) < n$ ，即 $\mathbf{A}$ 是不可逆矩阵

方法二 令 $\pmb{B} = \pmb{\xi}\pmb{\xi}^{\mathrm{T}}$ ，矩阵 $\pmb{B}$ 的特征值为 $\lambda_1 = \pmb{\xi}^{\mathrm{T}}\pmb{\xi} = 1, \lambda_2 = \dots = \lambda_n = 0$

矩阵 $\mathbf{A}$ 的特征值为 $\lambda_{1} = 0, \lambda_{2} = \dots = \lambda_{n} = 1$ ，则 $|\mathbf{A}| = |\mathbf{E} - \mathbf{B}| = 0$

故 $r(\mathbf{A}) < n$ ，即 $\mathbf{A}$ 不可逆

九、【解】（1）令 $\mathbf{A} = \begin{pmatrix} 5 & -1 & 3 \\ -1 & 5 & -3 \\ 3 & -3 & c \end{pmatrix}, \mathbf{X} = \begin{pmatrix} x_1 \\ x_2 \\ x_3 \end{pmatrix}$ ，则 $f(x_{1},x_{2},x_{3}) = \mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}$

因为二次型的秩为2，所以 $|\mathbf{A}| = 0$

由 $|\mathbf{A}| = \left| \begin{array}{rrr}5 & -1 & 3\\ -1 & 5 & -3\\ 3 & -3 & c \end{array} \right| = 24c - 72 = 0$ ，得 $c = 3$

容易验证，此时 $\mathbf{A}$ 的秩是2.A的特征多项式为

$$
\left| \lambda E - A \right| = \left| \begin{array}{c c c} \lambda - 5 & 1 & - 3 \\ 1 & \lambda - 5 & 3 \\ - 3 & 3 & \lambda - 3 \end{array} \right| = \lambda (\lambda - 4) (\lambda - 9),
$$

故所求特征值为 $\lambda_1 = 0, \lambda_2 = 4, \lambda_3 = 9$ .

（2）二次型 $f$ 的标准形为 $f = 4y_{2}^{2} + 9y_{3}^{2}$

由此可知 $f(x_{1},x_{2},x_{3}) = 1$ 所表示的曲面是椭圆柱面

# 十、填空题

(1)【答案】 $\frac{3}{7}$ .

【解】设 $A_{1} = \{$ 抽取的为 $A$ 厂产品 $\}$ , $A_{2} = \{$ 抽取的为 $B$ 厂产品 $\}$ , $B = \{$ 抽取的为次品 $\}$ ,

$$
P \left(A _ {1}\right) = 0. 6, \quad P \left(A _ {2}\right) = 0. 4, \quad P \left(B \mid A _ {1}\right) = 0. 0 1, \quad P \left(B \mid A _ {2}\right) = 0. 0 2,
$$

则 $P(A_{1} \mid B) = \frac{P(A_{1}B)}{P(B)} = \frac{P(A_{1})P(B \mid A_{1})}{P(A_{1})P(B \mid A_{1}) + P(A_{2})P(B \mid A_{2})}$

$$
= \frac {0 . 6 \times 0 . 0 1}{0 . 6 \times 0 . 0 1 + 0 . 4 \times 0 . 0 2} = \frac {3}{7}.
$$

(2)【答案】 $\frac{2}{\sqrt{2\pi}}$

【解】 令 $U = \xi -\eta$

因为 $\xi, \eta$ 相互独立且都服从正态分布 $N\left(0, \left(\frac{1}{\sqrt{2}}\right)^2\right)$ ，所以 $U \sim N(0, 1)$

于是 $E(|\xi - \eta|) = E(|U|) = \int_{-\infty}^{+\infty}|u| \cdot \frac{1}{\sqrt{2\pi}} \mathrm{e}^{-\frac{u^2}{2}} \, \mathrm{d}u = \frac{2}{\sqrt{2\pi}} \int_{0}^{+\infty} u \mathrm{e}^{-\frac{u^2}{2}} \, \mathrm{d}u$

$$
= \frac {2}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} \mathrm {e} ^ {- \frac {u ^ {2}}{2}} \mathrm {d} \left(\frac {u ^ {2}}{2}\right) = \frac {2}{\sqrt {2 \pi}} \Gamma (1) = \frac {2}{\sqrt {2 \pi}}.
$$

十一、【解】 (1) $P\{X = 1, Y = 1\} = P\{\xi = 1, \eta = 1\} = P\{\xi = 1\} P\{\eta = 1\} = \frac{1}{9}$ ,

$$
P \{X = 1, Y = 2 \} = 0, \quad P \{X = 1, Y = 3 \} = 0;
$$

$$
P \{X = 2, Y = 1 \} = P \{\xi = 1, \eta = 2 \} + P \{\xi = 2, \eta = 1 \} = \frac {2}{9},
$$

$$
P \{X = 2, Y = 2 \} = P \{\xi = 2, \eta = 2 \} = P \{\xi = 2 \} P \{\eta = 2 \} = \frac {1}{9},
$$

$$
P \{X = 2, Y = 3 \} = 0;
$$

$$
P \{X = 3, Y = 1 \} = P \{\xi = 3, \eta = 1 \} + P \{\xi = 1, \eta = 3 \} = \frac {2}{9},
$$

$$
P \{X = 3, Y = 2 \} = P \{\xi = 3, \eta = 2 \} + P \{\xi = 2, \eta = 3 \} = \frac {2}{9},
$$

$$
P \{X = 3, Y = 3 \} = \frac {1}{9},
$$

故 $(X,Y)$ 的联合分布律为

<table><tr><td rowspan="2">X</td><td colspan="3">Y</td></tr><tr><td>1</td><td>2</td><td>3</td></tr><tr><td>1</td><td>1/9</td><td>0</td><td>0</td></tr><tr><td>2</td><td>2/9</td><td>1/9</td><td>0</td></tr><tr><td>3</td><td>2/9</td><td>2/9</td><td>1/9</td></tr></table>

（2）随机变量 $X$ 的边缘分布律为

$$
X \sim \left( \begin{array}{c c c} 1 & 2 & 3 \\ \frac {1}{9} & \frac {3}{9} & \frac {5}{9} \end{array} \right),
$$

故 $E(X) = \frac{1}{9} +\frac{6}{9} +\frac{15}{9} = \frac{22}{9}$