# 1991年数学(一）真题解析

# 一、填空题

(1)【答案】 $\frac{\sin t - t\cos t}{4t^3}$ .

【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\mathrm{dy} / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = \frac{-\sin t}{2t}$

$$
\frac {\mathrm {d} ^ {2} y}{\mathrm {d} x ^ {2}} = \frac {\mathrm {d} \left(\frac {\mathrm {d} y}{\mathrm {d} x}\right)}{\mathrm {d} x} = \frac {\mathrm {d} \left(\frac {\mathrm {d} y}{\mathrm {d} x}\right) / \mathrm {d} t}{\mathrm {d} x / \mathrm {d} t} = - \frac {\frac {2 t \cos t - 2 \sin t}{4 t ^ {2}}}{2 t} = \frac {\sin t - t \cos t}{4 t ^ {3}}.
$$

(2)【答案】 $\mathrm{d}x - \sqrt{2}\mathrm{d}y$

【解】 方法一

$xyz + \sqrt{x^2 + y^2 + z^2} = \sqrt{2}$ 两边对 $x$ 求偏导得

$$
y z + x y \frac {\partial z}{\partial x} + \frac {x + z \frac {\partial z}{\partial x}}{\sqrt {x ^ {2} + y ^ {2} + z ^ {2}}} = 0, \text {解 得} \frac {\partial z}{\partial x} \Big | _ {(1, 0, - 1)} = 1;
$$

$xyz + \sqrt{x^2 + y^2 + z^2} = \sqrt{2}$ 两边对 $y$ 求偏导得

$$
x z + x y   {\frac {\partial z}{\partial y}} + {\frac {y + z   {\frac {\partial z}{\partial y}}}{\sqrt {x ^ {2} + y ^ {2} + z ^ {2}}}} = 0  , \text {解 得} {\frac {\partial z}{\partial y}}   \Big | _ {(1, 0, - 1)} = - {\sqrt {2}}  ,
$$

故 $\mathrm{d}z|_{(1,0,-1)} = \mathrm{d}x - \sqrt{2}\mathrm{d}y.$

方法二

$x y z + \sqrt{x^{2} + y^{2} + z^{2}} = \sqrt{2}$ 两边求微分得

$$
\mathrm {d} (x y z) + \mathrm {d} (\sqrt {x ^ {2} + y ^ {2} + z ^ {2}}) = 0,
$$

即 $yz \, \mathrm{d}x + xz \, \mathrm{d}y + xy \, \mathrm{d}z + \frac{x \, \mathrm{d}x + y \, \mathrm{d}y + z \, \mathrm{d}z}{\sqrt{x^2 + y^2 + z^2}} = 0,$

将 $(x,y,z) = (1,0, - 1)$ 代入得

$$
\mathrm {d} z \mid_ {(1, 0, - 1)} = \mathrm {d} x - \sqrt {2} \mathrm {d} y.
$$

(3)【答案】 $x - 3y + z + 2 = 0.$

【答案】 显然 $M_0(1,2,3)$ 为所求平面上的点，

所求平面的法向量为 $\pmb{n} = \{1,0, - 1\} \times \{2,1,1\} = \{1, - 3,1\}$

所求平面为 $\pi : (x - 1) - 3(y - 2) + (z - 3) = 0$ ，即 $\pi : x - 3y + z + 2 = 0$ .

（4）【答案】 $-\frac{3}{2}$

【解】由 $(1 + ax^2)^{\frac{1}{3}} - 1\sim \frac{a}{3} x^2,\cos x - 1\sim -\frac{1}{2} x^2$ ，得 $\frac{a}{3} = -\frac{1}{2}$ 故 $a = -\frac{3}{2}$

(5)【答案】 $\left[ \begin{array}{cccc}1 & -2 & 0 & 0\\ -2 & 5 & 0 & 0\\ 0 & 0 & \frac{1}{3} & \frac{2}{3}\\ 0 & 0 & -\frac{1}{3} & \frac{1}{3} \end{array} \right].$

【解】 令 $\pmb {B} = \left( \begin{array}{ll}5 & 2\\ 2 & 1 \end{array} \right),\pmb {C} = \left( \begin{array}{ll}1 & -2\\ 1 & 1 \end{array} \right)$ 则 $A^{-1} = \left( \begin{array}{cc}B^{-1} & O\\ O & C^{-1} \end{array} \right)$

由 $\left( \begin{array}{lll}5 & 2 & 1 & 0\\ 2 & 1 & 0 & 1 \end{array} \right)\to \left( \begin{array}{lll}1 & 0 & 1 & -2\\ 2 & 1 & 0 & 1 \end{array} \right)\to \left( \begin{array}{lll}1 & 0 & 1 & -2\\ 0 & 1 & -2 & 5 \end{array} \right),$ 得 $B^{-1} = \left( \begin{array}{cc}1 & -2\\ -2 & 5 \end{array} \right)$

由 $\left( \begin{array}{ccc}1 & -2 & 1 & 0\\ 1 & 1 & 0 & 1 \end{array} \right)\to \left( \begin{array}{ccc}1 & -2 & 1 & 0\\ 0 & 1 & -\frac{1}{3} & \frac{1}{3} \end{array} \right)\to \left( \begin{array}{ccccc}1 & 0 & \frac{1}{3} & \frac{2}{3}\\ 0 & 1 & -\frac{1}{3} & \frac{1}{3} \end{array} \right),$ 得 $C^{-1} = \left( \begin{array}{cc}\frac{1}{3} & \frac{2}{3}\\ -\frac{1}{3} & \frac{1}{3} \end{array} \right),$

故 $\mathbf{A}^{-1} = \left[ \begin{array}{rrr}1 & -2 & 0 & 0\\ -2 & 5 & 0 & 0\\ 0 & 0 & \frac{1}{3} & \frac{2}{3}\\ 0 & 0 & -\frac{1}{3} & \frac{1}{3} \end{array} \right].$

# 二、选择题

(1)【答案】 (D).

【解】由 $\lim_{x\to \infty}y = 1$ ，得 $y = 1$ 为曲线 $y = \frac{1 + \mathrm{e}^{-x^2}}{1 - \mathrm{e}^{-x^2}}$ 的水平渐近线；

由 $\lim_{x\to 0}y = \infty$ ，得 $x = 0$ 为曲线 $y = \frac{1 + \mathrm{e}^{-x^2}}{1 - \mathrm{e}^{-x^2}}$ 的铅直渐近线，应选(D).

(2)【答案】 (B).

【解】 $f(0) = \ln 2, f(x) = \int_{0}^{2x} f\left(\frac{t}{2}\right) \mathrm{d}t + \ln 2$ 两边对 $x$ 求导得 $f'(x) = 2f(x)$ ，

解得 $f(x) = C\mathrm{e}^{-\int -2\mathrm{d}x} = C\mathrm{e}^{2x}$

由 $f(0) = \ln 2$ 得 $C = \ln 2$ ，故 $f(x) = \mathrm{e}^{2x}\ln 2$ ，应选(B).

（3）【答案】 (C).

【解】 令 $S_{n}^{(1)} = a_{1} + a_{3} + \dots +a_{2n - 1}$ ， $S_{n}^{(2)} = a_{2} + a_{4} + \dots +a_{2n}$

$$
S _ {2 n} ^ {(3)} = a _ {1} - a _ {2} + \dots + a _ {2 n - 1} - a _ {2 n} = S _ {n} ^ {(1)} - S _ {n} ^ {(2)}, \quad S _ {n} = a _ {1} + a _ {2} + \dots + a _ {n},
$$

由题意得 $\lim_{n\to \infty}S_n^{(1)} = 5,\lim_{n\to \infty}S_{2n}^{(3)} = 2,$

于是 $\lim_{n\to \infty}S_{n}^{(2)} = \lim_{n\to \infty}S_{n}^{(1)} - \lim_{n\to \infty}S_{2n}^{(3)} = 3,$

因为 $\lim_{n\to \infty}S_{2n} = \lim_{n\to \infty}S_n^{(1)} + \lim_{n\to \infty}S_n^{(2)} = 8$ ，所以级数 $\sum_{n = 1}^{\infty}a_{n}$ 等于8，应选(C).

（4）【答案】 （A).

【解】 令 $D_{2} = \{(x,y) | -1 \leqslant x \leqslant 0, x \leqslant y \leqslant -x\}$ ,

$$
D _ {3} = \{(x, y) | - y \leqslant x \leqslant y, 0 \leqslant y \leqslant 1 \},
$$

由对称性得

$$
\iint_ {D _ {2}} (x y + \cos x \sin y) \mathrm {d} x \mathrm {d} y = 0,
$$

$\iint_{D_3}(xy + \cos x\sin y)\mathrm{d}x\mathrm{d}y = \iint_{D_3}\cos x\sin y\mathrm{d}x\mathrm{d}y = 2\iint_{D_1}\cos x\sin y\mathrm{d}x\mathrm{d}y$ ，应选(A).

（5）【答案】 (D).

【解】由 $ABC = E$ 得 $BC = A^{-1}$ ，则 $BCA = A^{-1}A = E$ ，应选(D).

# 三、

(1)【解】 $\lim_{x\to 0^{+}}(\cos {\sqrt{x}})^{\frac{\pi}{x}} = \lim_{x\to 0^{+}}\left\{[1 + (\cos {\sqrt{x}} - 1)]^{\frac{1}{\cos{\sqrt{x}} - 1}}\right\}^{\frac{\pi}{x}}$

$$
= \mathrm {e} ^ {\lim  _ {x \to 0} \frac {\pi}{x} \cdot (\cos \sqrt {x} - 1)} = \mathrm {e} ^ {\pi \lim  _ {x \to 0} \frac {\cos \sqrt {x} - 1}{x}} = \mathrm {e} ^ {\pi \lim  _ {x \to 0} \frac {- \frac {1}{2} x}{x}} = \mathrm {e} ^ {- \frac {\pi}{2}}.
$$

(2)【解】 法向量 $n = \{4x,6y,2z\}_{(1,1,1)} = \{4,6,2\}$

方向余弦为 $\cos \alpha = \frac{2}{\sqrt{14}}$ ， $\cos \beta = \frac{3}{\sqrt{14}}$ ， $\cos \gamma = \frac{1}{\sqrt{14}}$

$$
\frac {\partial u}{\partial x} = \frac {6 x}{z \sqrt {6 x ^ {2} + 8 y ^ {2}}}, \quad \frac {\partial u}{\partial y} = \frac {8 y}{z \sqrt {6 x ^ {2} + 8 y ^ {2}}}, \quad \frac {\partial u}{\partial z} = - \frac {\sqrt {6 x ^ {2} + 8 y ^ {2}}}{z ^ {2}},
$$

$$
\left. \frac {\partial u}{\partial x} \right| _ {(1, 1, 1)} = \frac {6}{\sqrt {1 4}}, \quad \left. \frac {\partial u}{\partial y} \right| _ {(1, 1, 1)} = \frac {8}{\sqrt {1 4}}, \quad \left. \frac {\partial u}{\partial z} \right| _ {(1, 1, 1)} = - \sqrt {1 4},
$$

则 $\left.\frac{\partial u}{\partial \boldsymbol{n}}\right|_{P} = \frac{2}{\sqrt{14}} \cdot \frac{6}{\sqrt{14}} + \frac{3}{\sqrt{14}} \cdot \frac{8}{\sqrt{14}} - \frac{1}{\sqrt{14}} \cdot \sqrt{14} = \frac{11}{7}$ .

(3)【解】 $\left\{ \begin{array}{l} y^{2} = 2z, \\ x = 0 \end{array} \right.$ 绕 $z$ 轴旋转而成的曲面为 $\Sigma: x^{2} + y^{2} = 2z$

则 $\Omega = \{(x,y,z) \mid (x,y) \in D_z, 0 \leqslant z \leqslant 4\}$ ，其中 $D_z = \{(x,y) \mid x^2 + y^2 \leqslant 2z\}$ ，

$$
\begin{array}{l} \iiint_ {\Omega} \left(x ^ {2} + y ^ {2} + z\right) d v = \int_ {0} ^ {4} d z \iint_ {D _ {z}} \left(x ^ {2} + y ^ {2} + z\right) d x d y \\ = \int_ {0} ^ {4} d z \int_ {0} ^ {2 \pi} d \theta \int_ {0} ^ {\sqrt {2 z}} r (r ^ {2} + z) d r = 2 \pi \int_ {0} ^ {4} d z \int_ {0} ^ {\sqrt {2 z}} (r ^ {3} + r z) d r \\ = 4 \pi \int_ {0} ^ {4} z ^ {2} \mathrm {d} z = 4 \pi \cdot \frac {6 4}{3} = \frac {2 5 6 \pi}{3}. \\ \end{array}
$$

# 四、【解】 方法一

$$
\begin{array}{l} I (a) = \int_ {L} (1 + y ^ {3}) d x + (2 x + y) d y = \int_ {0} ^ {\pi} (1 + a ^ {3} \sin^ {3} x) d x + (2 x + a \sin x) \cdot a \cos x d x \\ = \pi + a ^ {3} \int_ {0} ^ {\pi} \sin^ {3} x d x + 2 a \int_ {0} ^ {\pi} x d (\sin x) + a ^ {2} \int_ {0} ^ {\pi} \sin x d (\sin x) \\ = \pi + 2 a ^ {3} \cdot \frac {2}{3} + 2 a \left(x \sin x \left| _ {0} ^ {\pi} - \int_ {0} ^ {\pi} \sin x d x\right) = \pi + \frac {4}{3} a ^ {3} - 4 a, \right. \\ \end{array}
$$

令 $I^{\prime}(a) = 4a^{2} - 4 = 0$ 得 $a = 1$

因为 $I''(1) = 8 > 0$ ，所以 $a = 1$ 时 $\int_{L}(1 + y^{3})\mathrm{d}x + (2x + y)\mathrm{d}y$ 最小，故所求曲线为 $y = \sin x$

方法二

$$
I = \int_ {L} (1 + y ^ {3}) d x + (2 x + y) d y = \left(\oint_ {L + \overline {{A O}}} + \int_ {\overline {{O A}}}\right) (1 + y ^ {3}) d x + (2 x + y) d y,
$$

而 $\oint_{L + \overline{AO}}(1 + y^3)\mathrm{d}x + (2x + y)\mathrm{d}y = -\iint \limits_{D}(2 - 3y^2)\mathrm{d}x\mathrm{d}y = \iint \limits_{D}(3y^2 -2)\mathrm{d}x\mathrm{d}y$

$$
\begin{array}{l} = \int_ {0} ^ {\pi} d x \int_ {0} ^ {a \sin x} (3 y ^ {2} - 2) d y = \int_ {0} ^ {\pi} \left(a ^ {3} \sin^ {3} x - 2 a \sin x\right) d x \\ = \frac {4}{3} a ^ {3} - 4 a, \\ \end{array}
$$

$$
\int_ {\overline {{O A}}} (1 + y ^ {3}) \mathrm {d} x + (2 x + y) \mathrm {d} y = \int_ {0} ^ {\pi} \mathrm {d} x = \pi ,
$$

则 $I = \frac{4}{3} a^3 - 4a + \pi$ .

令 $I^{\prime}(a) = 4a^{2} - 4 = 0$ ，得 $a = 1$

因为 $I''(1) = 8 > 0$ ，所以 $a = 1$ 时 $\int_{L}(1 + y^{3})\mathrm{d}x + (2x + y)\mathrm{d}y$ 最小，故所求曲线为 $y = \sin x$ 五、【解】 显然 $f(x)$ 满足狄利克雷充分条件，

$$
a _ {0} = 2 \int_ {0} ^ {1} (2 + x) d x = 2 \times \left(2 + \frac {1}{2}\right) = 5,
$$

$$
\begin{array}{l} a _ {n} = 2 \int_ {0} ^ {1} (2 + x) \cos n \pi x d x = 2 \left(2 \int_ {0} ^ {1} \cos n \pi x d x + \int_ {0} ^ {1} x \cos n \pi x d x\right) \\ = 2 \int_ {0} ^ {1} x \cos n \pi x d x = \frac {2}{n \pi} \int_ {0} ^ {1} x d (\sin n \pi x) \\ = \frac {2}{n \pi} x \sin n \pi x \left| _ {0} ^ {1} - \frac {2}{n \pi} \int_ {0} ^ {1} \sin n \pi x d x = - \frac {2}{n \pi} \int_ {0} ^ {1} \sin n \pi x d x \right. \\ = \frac {2}{n ^ {2} \pi^ {2}} \cos n \pi x \Big | _ {0} ^ {1} = \frac {2 [ (- 1) ^ {n} - 1 ]}{n ^ {2} \pi^ {2}} = \left\{ \begin{array}{l l} - \frac {4}{n ^ {2} \pi^ {2}}, & n = 1, 3, 5, \dots , \\ 0, & n = 2, 4, 6, \dots , \end{array} \right. \\ \end{array}
$$

$b_{n} = 0$

故 $2 + |x| = \frac{5}{2} -\frac{4}{\pi^2}\left(\frac{1}{1^2}\cos \pi x + \frac{1}{3^2}\cos 3\pi x + \dots\right)\quad (-\infty <  x <   + \infty),$

取 $x = 0$ ，得 $\frac{1}{1^2} +\frac{1}{3^2} +\dots = \sum_{n = 0}^{\infty}\frac{1}{(2n + 1)^2} = \frac{\pi^2}{8}.$

令 $S = \sum_{n=1}^{\infty} \frac{1}{n^{2}}$ , 则

$$
S = \left(\frac {1}{1 ^ {2}} + \frac {1}{3 ^ {2}} + \frac {1}{5 ^ {2}} + \dots\right) + \left(\frac {1}{2 ^ {2}} + \frac {1}{4 ^ {2}} + \frac {1}{6 ^ {2}} + \dots\right) = \frac {\pi^ {2}}{8} + \frac {1}{4} S,
$$

解得 $S = \frac{\pi^2}{6}$ 即 $\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$ .

六、【证明】 由积分中值定理可知，存在 $x_0 \in \left[\frac{2}{3}, 1\right]$ ，使得

$$
3 \int_ {\frac {2}{3}} ^ {1} f (x) \mathrm {d} x = 3 \cdot f \left(x _ {0}\right) \cdot \left(1 - \frac {2}{3}\right) = f \left(x _ {0}\right),
$$

从而有 $f(0) = f(x_0)$ .

由罗尔定理可知，存在 $c \in (0, x_0) \subset (0, 1)$ ，使得 $f'(c) = 0$

七、【解】 令 $x_{1}\pmb{\alpha}_{1} + x_{2}\pmb{\alpha}_{2} + x_{3}\pmb{\alpha}_{3} + x_{4}\pmb{\alpha}_{4} = \pmb{\beta}$

$$
\left(\boldsymbol {\alpha} _ {1} ^ {\mathrm {T}}, \boldsymbol {\alpha} _ {2} ^ {\mathrm {T}}, \boldsymbol {\alpha} _ {3} ^ {\mathrm {T}}, \boldsymbol {\alpha} _ {4} ^ {\mathrm {T}}; \boldsymbol {\beta} ^ {\mathrm {T}}\right) = \left(\begin{array}{c c c c c c c}1&1&1&1&1\\0&1&- 1&2&1\\2&3&a + 2&4&b + 3\\3&5&1&a + 8&5\end{array}\right)\rightarrow \left(\begin{array}{c c c c c c c}1&1&1&1&1\\0&1&- 1&2&1\\0&0&a + 1&0&b\\0&0&0&a + 1&0\end{array}\right),
$$

（1）当 $a = -1, b \neq 0$ 时，

因为 $r(\mathbf{A}) \neq r(\overline{\mathbf{A}})$ ，所以方程组 $x_{1}\pmb{\alpha}_{1} + x_{2}\pmb{\alpha}_{2} + x_{3}\pmb{\alpha}_{3} + x_{4}\pmb{\alpha}_{4} = \pmb{\beta}$ 无解，

即 $\pmb{\beta}$ 不可由 $\alpha_{1},\alpha_{2},\alpha_{3},\alpha_{4}$ 线性表示

（2）当 $a \neq -1$ 时，

因为 $r(\mathbf{A}) = r(\overline{\mathbf{A}}) = 4$ ，所以方程组 $x_{1}\pmb{\alpha}_{1} + x_{2}\pmb{\alpha}_{2} + x_{3}\pmb{\alpha}_{3} + x_{4}\pmb{\alpha}_{4} = \pmb{\beta}$ 有唯一解，

且 $x_{1} = -\frac{2b}{a + 1}, x_{2} = \frac{a + b + 1}{a + 1}, x_{3} = \frac{b}{a + 1}, x_{4} = 0,$

故 $\pmb{\beta}$ 可由 $\alpha_{1},\alpha_{2},\alpha_{3},\alpha_{4}$ 唯一线性表示，

且 $\pmb {\beta} = -\frac{2b}{a + 1}\pmb{\alpha}_{1} + \frac{a + b + 1}{a + 1}\pmb{\alpha}_{2} + \frac{b}{a + 1}\pmb{\alpha}_{3} + 0\pmb{\alpha}_{4}.$

八、【证明】方法一 因为 $A$ 为正定矩阵，所以矩阵 $A$ 的特征值 $\lambda_{i} > 0 (i = 1,2,\dots ,n)$

从而 $A + E$ 的特征值为 $\lambda_1 + 1, \lambda_2 + 1, \dots, \lambda_n + 1$

故 $|\mathbf{A} + \mathbf{E}| = (\lambda_1 + 1)(\lambda_2 + 1)\dots (\lambda_n + 1) > 1.$

方法二 因为 $A$ 是 $n$ 阶正定矩阵，所以其特征值 $\lambda_{i} > 0(i = 1,2,\dots ,n)$

存在正交矩阵 $Q$ ，使得 $Q^{\mathrm{T}}AQ = \begin{bmatrix} \lambda_1 & 0 & \dots & 0\\ 0 & \lambda_2 & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & \lambda_n \end{bmatrix}$ ，或 $\mathbf{A} = \mathbf{Q}\left[ \begin{array}{cccc}\lambda_{1} & 0 & \dots & 0\\ 0 & \lambda_{2} & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & \lambda_n \end{array} \right]Q^{\mathrm{T}},$

于是 $\mathbf{A} + \mathbf{E} = \mathbf{Q}\left[ \begin{array}{cccc}\lambda_{1} & 0 & \dots & 0\\ 0 & \lambda_{2} & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & \lambda_{n} \end{array} \right]\mathbf{Q}^{\mathrm{T}} + \mathbf{QQ}^{\mathrm{T}} = \mathbf{Q}\left[ \begin{array}{cccc} \lambda_{1} + 1 & 0 & \dots & 0\\ 0 & \lambda_{2} + 1 & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & \lambda_{n} + 1 \end{array} \right]\mathbf{Q}^{\mathrm{T}},$

故 $|\mathbf{A} + \mathbf{E}| = |\mathbf{Q}|\cdot \left| \begin{array}{cccc}\lambda_{1} + 1 & 0 & \dots & 0\\ 0 & \lambda_{2} + 1 & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & \lambda_{n} + 1 \end{array} \right|\cdot |\mathbf{Q}^{\mathrm{T}}|$

$$
= (\lambda_ {1} + 1) (\lambda_ {2} + 1) \dots (\lambda_ {n} + 1) > 1.
$$

九、【解】 设曲线为 $y = y(x)$

曲线在点 $P(x,y)$ 处的曲率为 $k = \frac{|y^{\prime\prime}|}{(1 + y^{\prime 2})^{\frac{3}{2}}}$

曲线在点 $P(x,y)$ 的法线为 $Y - y = -\frac{1}{y'} (X - x)$

令 $Y = 0$ 得 $X = x + yy'$ ，即 $Q(x + yy', 0)$

$$
| P Q | = \sqrt {y ^ {2} y ^ {\prime 2} + y ^ {2}} = y \sqrt {1 + y ^ {\prime 2}},
$$

由题意得 $\frac{|y''|}{(1 + y'^2)^{\frac{3}{2}}} = \frac{1}{y\sqrt{1 + y'^2}}$ 整理得 $yy^{\prime \prime} = 1 + y^{\prime 2}$

令 $y^\prime = p$ ，则 $y p \frac{\mathrm{d}p}{\mathrm{d}y} = 1 + p^2$ ，变量分离得 $\frac{2p\mathrm{d}p}{1 + p^2} = \frac{2\mathrm{d}y}{y}$

积分得 $\ln (1 + p^2) = \ln y^2 + \ln C_1$ ，即 $1 + p^2 = C_1y^2$

由 $y(1) = 1, y'(1) = 0$ 得 $C_1 = 1$

解得 $y^\prime = \pm \sqrt{y^2 - 1}$ 变量分离得 $\frac{\mathrm{dy}}{\sqrt{y^2 - 1}} = \pm \mathrm{dx}$

积分得 $\ln (y + \sqrt{y^2 - 1}) = \pm x + C_2$

由 $y(1) = 1$ 得 $C_2 = \mp 1$ ，即 $\ln (y + \sqrt{y^2 - 1}) = \pm (x - 1)$

由 $\left\{ \begin{array}{l} y + \sqrt{y^2 - 1} = \mathrm{e}^{\pm (x - 1)} \\ y - \sqrt{y^2 - 1} = \mathrm{e}^{\mp (x - 1)} \end{array} \right.$ 得 $y = \frac{\mathrm{e}^{x - 1} + \mathrm{e}^{1 - x}}{2}$ ,

故所求的曲线为 $y = \frac{\mathrm{e}^{x - 1} + \mathrm{e}^{1 - x}}{2}$

# 十、填空题

（1）【答案】 0.2.

【解】 显然 $X \sim N(2, \sigma^2)$ ，标准化得 $\frac{X - 2}{\sigma} \sim N(0,1)$

由 $P\{2 < X < 4\} = P\left\{0 < \frac{X - 2}{\sigma} < \frac{2}{\sigma}\right\} = \Phi \left(\frac{2}{\sigma}\right) - \Phi (0) = 0.3$ 得

$\Phi \left(\frac{2}{\sigma}\right) - 0.5 = 0.3$ ，即 $\Phi \left(\frac{2}{\sigma}\right) = 0.8.$

故 $P\{X < 0\} = P\{X \leqslant 0\} = P\left\{\frac{X - 2}{\sigma} \leqslant -\frac{2}{\sigma}\right\} = \Phi\left(-\frac{2}{\sigma}\right) = 1 - \Phi\left(\frac{2}{\sigma}\right) = 0.2.$

(2)【答案】 $\frac{1}{2} +\frac{1}{\pi}$

【解】 所求概率 $p = \frac{\iint_{D} \mathrm{d}x \, \mathrm{d}y}{\frac{\pi a^2}{2}} = \frac{2}{\pi a^2} \int_{0}^{\frac{\pi}{4}} \mathrm{d}\theta \int_{0}^{2a\cos \theta} r \, \mathrm{d}r$

$$
= \frac {4}{\pi} \int_ {0} ^ {\frac {\pi}{4}} \cos^ {2} \theta d \theta = \frac {2}{\pi} \int_ {0} ^ {\frac {\pi}{4}} (1 + \cos 2 \theta) d \theta = \frac {1}{2} + \frac {1}{\pi}.
$$

十一、【解】 $F_{Z}(z) = P\{Z \leqslant z\} = P\{X + 2Y \leqslant z\} = \iint_{x + 2y \leqslant z} f(x, y) \, \mathrm{d}x \, \mathrm{d}y,$

当 $z \leqslant 0$ 时， $F_Z(z) = 0$

当 $z > 0$ 时， $F_{Z}(z) = \int_{0}^{z}\mathrm{d}x\int_{0}^{\frac{z - x}{2}}2\mathrm{e}^{-(x + 2y)}\mathrm{d}y = \int_{0}^{z}\mathrm{e}^{-x}\mathrm{d}x\int_{0}^{\frac{z - x}{2}}2\mathrm{e}^{-2y}\mathrm{d}y$

$$
= \int_ {0} ^ {z} \left(\mathrm {e} ^ {- x} - \mathrm {e} ^ {- z}\right) \mathrm {d} x = 1 - \mathrm {e} ^ {- z} - z \mathrm {e} ^ {- z},
$$

故随机变量 $Z$ 的分布函数为 $F_{Z}(z) = \left\{ \begin{array}{ll}1 - \mathrm{e}^{-z} - z\mathrm{e}^{-z}, & z > 0,\\ 0, & z\leqslant 0. \end{array} \right.$