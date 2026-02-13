# 1994年数学（一）真题解析

# 一、填空题

(1)【答案】 $\frac{1}{6}$ .

【解】 $\lim_{x\to 0}\cot x\left(\frac{1}{\sin x} -\frac{1}{x}\right) = \lim_{x\to 0}\frac{x - \sin x}{x\sin x\tan x}$

$$
= \lim  _ {x \rightarrow 0} \frac {x - \sin x}{x ^ {3}} = \frac {1}{3} \lim  _ {x \rightarrow 0} \frac {1 - \cos x}{x ^ {2}} = \frac {1}{6}.
$$

(2)【答案】 $2x + y - 4 = 0$ .

【解】 令 $F = 2xy + z - \mathrm{e}^z -3$

法向量为 $n = \{2y, 2x, 1 - e^z\}_{(1,2,0)} = \{4, 2, 0\}$

则切平面为 $4(x - 1) + 2(y - 2) + 0(z - 0) = 0$ ，即 $2x + y - 4 = 0$

(3)【答案】 $\frac{\pi^2}{\mathrm{e}^2}$ .

【解】 $\frac{\partial u}{\partial x} = -\mathrm{e}^{-x}\sin \frac{x}{y} +\frac{\mathrm{e}^{-x}}{y}\cos \frac{x}{y},$

$$
\frac {\partial^ {2} u}{\partial x \partial y} = \frac {x e ^ {- x}}{y ^ {2}} \cos \frac {x}{y} - \frac {e ^ {- x}}{y ^ {2}} \cos \frac {x}{y} + \frac {x e ^ {- x}}{y ^ {3}} \sin \frac {x}{y},
$$

故 $\left.\frac{\partial^2u}{\partial x\partial y}\right|_{(2,\frac{1}{\pi})} = \left(\frac{\pi}{\mathrm{e}}\right)^2.$

(4)【答案】 $\frac{\pi R^4}{4}\left(\frac{1}{a^2} +\frac{1}{b^2}\right)$

【解】 由对称性得

$$
\iint_ {D} x ^ {2} \mathrm {d} x \mathrm {d} y = \iint_ {D} y ^ {2} \mathrm {d} x \mathrm {d} y = \frac {1}{2} \iint_ {D} \left(x ^ {2} + y ^ {2}\right) \mathrm {d} x \mathrm {d} y = \frac {1}{2} \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {R} r ^ {3} \mathrm {d} r = \frac {\pi R ^ {4}}{4},
$$

于是 $\iint_{D}\left(\frac{x^2}{a^2} +\frac{y^2}{b^2}\right)\mathrm{d}x\mathrm{d}y = \frac{1}{a^2}\iint_{D}x^2\mathrm{d}x\mathrm{d}y + \frac{1}{b^2}\iint_{D}y^2\mathrm{d}x\mathrm{d}y$

$$
= \left(\frac {1}{a ^ {2}} + \frac {1}{b ^ {2}}\right) \cdot \frac {\pi R ^ {4}}{4} = \frac {\pi R ^ {4}}{4} \left(\frac {1}{a ^ {2}} + \frac {1}{b ^ {2}}\right).
$$

(5)【答案】 $3^{n - 1}\left[ \begin{array}{ccc}1 & \frac{1}{2} & \frac{1}{3}\\ 2 & 1 & \frac{2}{3}\\ 3 & \frac{3}{2} & 1 \end{array} \right].$

【解】 因为 $(\pmb {\alpha},\pmb {\beta}) = 3$ ， $A = \binom{1}{2}\left(1,\frac{1}{2},\frac{1}{3}\right) = \begin{bmatrix} 1 & \frac{1}{2} & \frac{1}{3}\\ 2 & 1 & \frac{2}{3}\\ 3 & \frac{3}{2} & 1 \end{bmatrix} ,$

所以 $\mathbf{A}^n = 3^{n - 1}\mathbf{A} = 3^{n - 1}\left[ \begin{array}{ccc}1 & \frac{1}{2} & \frac{1}{3}\\ 2 & 1 & \frac{2}{3}\\ 3 & \frac{3}{2} & 1 \end{array} \right].$

# 二、选择题

（1）【答案】 （D）.

【解】 $M = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{\sin x}{1 + x^2}\cos^4 x\mathrm{d}x = 0,$

$$
N = \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} (\sin^ {3} x + \cos^ {4} x) d x = 2 \int_ {0} ^ {\frac {\pi}{2}} \cos^ {4} x d x > 0,
$$

$$
P = \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} \left(x ^ {2} \sin^ {3} x - \cos^ {4} x\right) d x = - 2 \int_ {0} ^ {\frac {\pi}{2}} \cos^ {4} x d x <   0,
$$

则 $P <   M <   N$ ，应选（D）.

(2)【答案】 (D).

【解】 取 $f(x,y) = \left\{ \begin{array}{ll} \frac{xy}{x^2 + y^2}, & (x,y)\neq (0,0),\\ 0, & (x,y) = (0,0). \end{array} \right.$

由 $\lim_{x\to 0}\frac{f(x,0) - f(0,0)}{x - 0} = 0$ 得 $f_{x}^{\prime}(0,0) = 0$ ，同理 $f_{y}^{\prime}(0,0) = 0$ ，即 $f(x,y)$ 在(0，0）处可偏导.

因为 $\lim_{\substack{x\to 0\\ y = x}}f(x,y) = \frac{1}{2}\neq \lim_{\substack{x\to 0\\ y = -x}}f(x,y) = -\frac{1}{2}$ ，所以 $\lim_{x\to 0}\lim_{y\to 0}f(x,y)$ 不存在，故 $f(x,y)$ 在(0,0）处不连续；

令 $f(x,y) = |x| + |y|$ ，显然 $f(x,y)$ 在 $(0,0)$ 处连续，

因为 $\lim_{x\to 0}\frac{f(x,0) - f(0,0)}{x} = \lim_{x\to 0}\frac{|x|}{x}$ 不存在，所以 $f(x,y)$ 在(0，0）处对 $x$ 不可偏导，同理 $f(x,y)$ 在（0，0）处对 $y$ 也不可偏导.

故 $f(x,y)$ 在 $(x_0,y_0)$ 处可偏导既非 $f(x,y)$ 在 $(x_0,y_0)$ 处连续的充分条件也非必要条件，应选(D).

(3)【答案】 (C).

【解】 $\mid (-1)^n\frac{\mid a_n\mid}{\sqrt{n^2 + \lambda}}\mid \leqslant \frac{1}{2}\left(a_n^2 +\frac{1}{n^2 + \lambda}\right),$

因为 $\sum_{n=1}^{\infty} a_n^2$ 及 $\sum_{n=1}^{\infty} \frac{1}{n^2 + \lambda}$ 都收敛，由正项级数的比较审敛法得 $\sum_{n=1}^{\infty} (-1)^n \frac{|a_n|}{\sqrt{n^2 + \lambda}}$ 收敛，

即 $\sum_{n = 1}^{\infty}(-1)^{n}\frac{|a_{n}|}{\sqrt{n^{2} + \lambda}}$ 绝对收敛，应选(C).

(4)【答案】 (D).

【解】由 $2 = \lim_{x\to 0}\frac{a\tan x + b(1 - \cos x)}{c\ln(1 - 2x) + d(1 - e^{-x^2})} = \lim_{x\to 0}\frac{\frac{a\tan x}{x} + \frac{b(1 - \cos x)}{x}}{\frac{c\ln(1 - 2x)}{x} + \frac{d(1 - e^{-x^2})}{x}} = \frac{a}{-2c},$

得 $a = -4c$ ，应选(D).

（5）【答案】 (C).

【解】 方法一

由 $(\alpha_{1} + \alpha_{2}) - (\alpha_{2} + \alpha_{3}) + (\alpha_{3} + \alpha_{4}) - (\alpha_{4} + \alpha_{1}) = 0$ 得向量组 $\alpha_{1} + \alpha_{2}, \alpha_{2} + \alpha_{3}, \alpha_{3} + \alpha_{4}, \alpha_{4} + \alpha_{1}$ 线

性相关，（A）不对；

由 $(\alpha_{1} - \alpha_{2}) + (\alpha_{2} - \alpha_{3}) + (\alpha_{3} - \alpha_{4}) + (\alpha_{4} - \alpha_{1}) = 0$ 得向量组 $\alpha_{1} - \alpha_{2}, \alpha_{2} - \alpha_{3}, \alpha_{3} - \alpha_{4}, \alpha_{4} - \alpha_{1}$ 线性相关，(B）不对；

由 $(\alpha_{1} + \alpha_{2}) - (\alpha_{2} + \alpha_{3}) + (\alpha_{3} - \alpha_{4}) + (\alpha_{4} - \alpha_{1}) = 0$ 得向量组 $\alpha_{1} + \alpha_{2}, \alpha_{2} + \alpha_{3}, \alpha_{3} - \alpha_{4}, \alpha_{4} - \alpha_{1}$ 线性相关，(D) 不对，应选 (C).

方法二 令 $\mathbf{A} = (\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\alpha}_4)$ ，因为 $\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3, \pmb{\alpha}_4$ 线性无关，所以 $r(\mathbf{A}) = 4$ .

令 $\pmb{B} = (\pmb{\alpha}_{1} + \pmb{\alpha}_{2},\pmb{\alpha}_{2} + \pmb{\alpha}_{3},\pmb{\alpha}_{3} + \pmb{\alpha}_{4},\pmb{\alpha}_{4} - \pmb{\alpha}_{1})$ ，则 $\pmb {B} = \pmb {A}\left[ \begin{array}{cccc}1 & 0 & 0 & -1\\ 1 & 1 & 0 & 0\\ 0 & 1 & 1 & 0\\ 0 & 0 & 1 & 1 \end{array} \right],$

因为 $\left| \begin{array}{cccc}1 & 0 & 0 & -1\\ 1 & 1 & 0 & 0\\ 0 & 1 & 1 & 0\\ 0 & 0 & 1 & 1 \end{array} \right| = \left| \begin{array}{cccc}1 & 0 & 0 & -1\\ 0 & 1 & 0 & 1\\ 0 & 1 & 1 & 0\\ 0 & 0 & 1 & 1 \end{array} \right| = 2\neq 0$ ，得 $\left( \begin{array}{cccc}1 & 0 & 0 & -1\\ 1 & 1 & 0 & 0\\ 0 & 1 & 1 & 0\\ 0 & 0 & 1 & 1 \end{array} \right)$ 满秩，

所以 $r(\pmb {B}) = r(\pmb {A}) = 4$ ，故 $\alpha_{1} + \alpha_{2},\alpha_{2} + \alpha_{3},\alpha_{3} + \alpha_{4},\alpha_{4} - \alpha_{1}$ 线性无关，应选(C).

# 三、

(1)【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\mathrm{dy} / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = \frac{\cos t^2 - 2t^2\sin t^2 - 2t\cdot\frac{1}{2t}\cos t^2}{-2t\sin t^2} = t$ ，则 $\left.\frac{\mathrm{dy}}{\mathrm{dx}}\right|_{t = \sqrt{\frac{\pi}{2}}} = \sqrt{\frac{\pi}{2}};$

$\frac{\mathrm{d}^2y}{\mathrm{d}x^2} = -\frac{\mathrm{d}\left(\frac{\mathrm{dy}}{\mathrm{dx}}\right)}{\mathrm{d}x / \mathrm{d}t} = \frac{1}{-2t\sin t^2}$ 则 $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\Big|_{t = \sqrt{\frac{\pi}{2}}} = -\frac{1}{\sqrt{2\pi}}.$

(2)【解】 $f(x) = \frac{1}{4}\ln (1 + x) - \frac{1}{4}\ln (1 - x) + \frac{1}{2}\arctan x - x, \quad f(0) = 0,$

$$
\begin{array}{l} f ^ {\prime} (x) = \frac {1}{2 \left(1 - x ^ {2}\right)} + \frac {1}{2 \left(1 + x ^ {2}\right)} - 1 = \frac {1}{1 - x ^ {4}} - 1 \\ = \sum_ {n = 1} ^ {\infty} \left(x ^ {4}\right) ^ {n} = \sum_ {n = 1} ^ {\infty} x ^ {4 n} \quad (- 1 <   x <   1), \\ \end{array}
$$

于是 $f(x) = f(x) - f(0) = \int_{0}^{x}f^{\prime}(x)\mathrm{d}x = \sum_{n = 1}^{\infty}\frac{x^{4n + 1}}{4n + 1}\quad (-1 <   x <   1).$

(3)【解】 $\int \frac{\mathrm{d}x}{\sin 2x + 2\sin x} = \frac{1}{2}\int \frac{\mathrm{d}x}{\sin x(1 + \cos x)} = \frac{1}{2}\int \frac{(1 - \cos x)\mathrm{d}x}{\sin^3 x}$

$$
= \frac {1}{2} \int \csc^ {3} x \mathrm {d} x - \frac {1}{2} \int \frac {\mathrm {d} (\sin x)}{\sin^ {3} x} = \frac {1}{2} \int \csc^ {3} x \mathrm {d} x + \frac {1}{4 \sin^ {2} x},
$$

令 $I = \int \csc^3 x\mathrm{d}x$ ，则

$$
\begin{array}{l} I = - \int \csc x d (\cot x) = - \csc x \cot x - \int \csc x \cot^ {2} x d x \\ = - \csc x \cot x - I + \ln | \csc x - \cot x |, \\ \end{array}
$$

$$
I = \frac {1}{2} (- \csc x \cot x + \ln | \csc x - \cot x |) + C,
$$

故 $\int \frac{\mathrm{d}x}{\sin 2x + 2\sin x} = \frac{1}{4} (-\csc x\cot x + \ln |\csc x - \cot x|) + \frac{1}{4\sin^2x} +C.$

# 四、【解】 令 $\Sigma_{1}:z = -R(x^{2} + y^{2}\leqslant R^{2})$ ，取下侧，

$\Sigma_{2}:z = R(x^{2} + y^{2}\leqslant R^{2})$ ，取上侧，

$\Sigma_{3}:x^{2} + y^{2} = R^{2}(-R\leqslant z\leqslant R)$ ，取外侧，

显然 $\iint_{\Sigma_3} \frac{z^2 \, \mathrm{d}x \, \mathrm{d}y}{x^2 + y^2 + z^2} = 0,$

因为 $\frac{z^2}{x^2 + y^2 + z^2}$ 为 $z$ 的偶函数，所以 $\iint_{\Sigma_1 + \Sigma_2} \frac{z^2 \, \mathrm{d}x \, \mathrm{d}y}{x^2 + y^2 + z^2} = 0$ 故 $\iint_{S} \frac{z^2 \, \mathrm{d}x \, \mathrm{d}y}{x^2 + y^2 + z^2} = 0.$

于是 $I = \iint_{S} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} = \iint_{\Sigma_1} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} + \iint_{\Sigma_2} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} + \iint_{\Sigma_3} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2},$

再由 $\iint_{\Sigma_1} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} = 0, \iint_{\Sigma_2} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} = 0$ ，得 $I = \iint_{\Sigma_3} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2}$ .

令 $\Sigma_{3}^{(1)}: x^{2} + y^{2} = R^{2} (x \geqslant 0)$ ，取前侧，因为 $\frac{x}{x^2 + y^2 + z^2}$ 为 $x$ 的奇函数，

所以 $I = \iint_{\Sigma_3} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2} = 2 \iint_{\Sigma_3^{(1)}} \frac{x \, \mathrm{d}y \, \mathrm{d}z}{x^2 + y^2 + z^2}$

$$
\begin{array}{l} = 2 \int_ {- R} ^ {R} d y \int_ {- R} ^ {R} \frac {\sqrt {R ^ {2} - y ^ {2}}}{R ^ {2} + z ^ {2}} d z = 8 \int_ {0} ^ {R} \sqrt {R ^ {2} - y ^ {2}} d y \int_ {0} ^ {R} \frac {d z}{R ^ {2} + z ^ {2}} \\ = 8 \times \frac {\pi R ^ {2}}{4} \times \frac {1}{R} \arctan \frac {z}{R} \Bigg | _ {0} ^ {R} = \frac {\pi^ {2} R}{2}. \\ \end{array}
$$

五、【解】令 $P(x,y) = xy(x + y) - f(x)y$ ， $Q(x,y) = f^{\prime}(x) + x^{2}y$

由 $[xy(x + y) - f(x)y]\mathrm{d}x + [f'(x) + x^2 y]\mathrm{d}y = 0$ 为全微分方程得 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$

即 $x^{2} + 2xy - f(x) = f^{\prime \prime}(x) + 2xy$ ，整理得 $f''(x) + f(x) = x^2$

特征方程为 $\lambda^2 + 1 = 0$ ，特征根为 $\lambda_1 = -\mathrm{i}, \lambda_2 = \mathrm{i}$

显然方程 $f^{\prime \prime}(x) + f(x) = x^{2}$ 有特解 $f_{0}(x) = x^{2} - 2$

则通解为 $f(x) = C_{1}\cos x + C_{2}\sin x + x^{2} - 2$ ，

由 $f(0) = 0, f'(0) = 1$ 得 $C_1 = 2, C_2 = 1$ ，故 $f(x) = 2\cos x + \sin x + x^2 - 2.$

于是原方程为

$$
\left[ x y ^ {2} - \left(2 \cos x + \sin x\right) y + 2 y \right] d x + \left(- 2 \sin x + \cos x + 2 x + x ^ {2} y\right) d y = 0,
$$

其通解是 $-2y\sin x + y\cos x + \frac{x^2y^2}{2} + 2xy = C$ ，其中 $C$ 为任意常数.

六、【证明】 由 $\lim_{x\to 0}\frac{f(x)}{x} = 0$ 得 $f(0) = 0,f^{\prime}(0) = 0$

由 $f(x)$ 在 $x = 0$ 的某一邻域内具有二阶连续导数得

$$
f (x) = f (0) + f ^ {\prime} (0) x + \frac {f ^ {\prime \prime} (0)}{2 !} x ^ {2} + o \left(x ^ {2}\right) = \frac {f ^ {\prime \prime} (0)}{2 !} x ^ {2} + o \left(x ^ {2}\right),
$$

从而 $f\left(\frac{1}{n}\right) = \frac{f''(0)}{2!} \cdot \frac{1}{n^2} + o\left(\frac{1}{n^2}\right)$ ，于是 $\left|f\left(\frac{1}{n}\right)\right| \sim \frac{\left|f''(0)\right|}{2!} \cdot \frac{1}{n^2}$ ，

因为 $\sum_{n = 1}^{\infty}\frac{|f''(0)|}{2!}\cdot \frac{1}{n^2}$ 收敛，所以由正项级数比较审敛法得 $\sum_{n = 1}^{\infty}\left|f\left(\frac{1}{n}\right)\right|$ 收敛，即 $\sum_{n = 1}^{\infty}f\left(\frac{1}{n}\right)$ 绝对收敛.

七、【解】 $\overrightarrow{AB} = \{-1, 1, 1\}$ , $AB$ 所在的直线 $L$ 的方程为 $\frac{x - 1}{-1} = \frac{y}{1} = \frac{z}{1}$ ,

任取 $M(x,y,z)\in S$ ，其所在的圆对应的直线 $L$ 上的点为 $M_0(x_0,y_0,z)$ ，圆心为 $T(0,0,z)$

由 $|MT| = |M_0T|$ 得 $x^{2} + y^{2} = x_{0}^{2} + y_{0}^{2}$

因为 $M_0(x_0, y_0, z) \in L$ ，所以 $\frac{x_0 - 1}{-1} = \frac{y_0}{1} = \frac{z}{1}$ ，解得 $x_0 = 1 - z, y_0 = z$

故曲面 $S$ 的方程为 $x^{2} + y^{2} = (1 - z)^{2} + z^{2}$ ，即 $S: x^{2} + y^{2} = 1 - 2z + 2z^{2}$ .

所求的体积为

$$
V = \int_ {0} ^ {1} \mathrm {d} z \iint_ {D _ {z}} \mathrm {d} x \mathrm {d} y = \int_ {0} ^ {1} \mathrm {d} z \iint_ {x ^ {2} + y ^ {2} \leqslant 1 - 2 z + 2 z ^ {2}} \mathrm {d} x \mathrm {d} y = \pi \int_ {0} ^ {1} (1 - 2 z + 2 z ^ {2}) \mathrm {d} z = \frac {2 \pi}{3}.
$$

八、【解】（1）由（I）有 $\left\{ \begin{array}{l}x_{1} = -x_{2},\\ x_{4} = x_{2}. \end{array} \right.$ 分别取 $\binom{x_2}{x_3}=\binom{0}{1}$ 和 $\binom{1}{0}$ ，得（I）的基础解系为

$$
(0, 0, 1, 0) ^ {T}, (- 1, 1, 0, 1) ^ {T}.
$$

（2）有非零公共解.（Ⅱ）的通解可表示为 $(x_{1},x_{2},x_{3},x_{4})^{\mathrm{T}} = (-k_{2},k_{1} + 2k_{2},k_{1} + 2k_{2},k_{2})^{\mathrm{T}}$ 将其代入（I）得

$$
\left\{ \begin{array}{l} - k _ {2} + (k _ {1} + 2 k _ {2}) = 0, \\ (k _ {1} + 2 k _ {2}) - k _ {2} = 0, \end{array} \right.
$$

解得 $k_{1} = -k_{2}$

当 $k_{1} = -k_{2}\neq 0$ 时，（Ⅱ）的通解化为

$$
k _ {1} (0, 1, 1, 0) ^ {\mathrm {T}} + k _ {2} (- 1, 2, 2, 1) ^ {\mathrm {T}} = k _ {2} \left[ (0, - 1, - 1, 0) ^ {\mathrm {T}} + (- 1, 2, 2, 1) ^ {\mathrm {T}} \right] = k _ {2} (- 1, 1, 1, 1) ^ {\mathrm {T}},
$$

此向量即是（I）与（Ⅱ）的非零公共解，故方程组（I）（Ⅱ）的所有非零公共解是

$k(-1,1,1,1)^{\mathrm{T}}(k$ 是不为零的任意常数）.

九、【证明】由 $\mathbf{A}^{*} = \mathbf{A}^{\mathrm{T}}$ 得 $a_{ij} = A_{ij}(i,j = 1,2,\dots ,n)$

因为 $\mathbf{A}$ 为非零矩阵，所以矩阵 $\mathbf{A}$ 中有非零元素，不妨设 $a_{11} \neq 0$

故 $|\mathbf{A}| = a_{11}A_{11} + a_{12}A_{12} + \dots +a_{1n}A_{1n} = a_{11}^{2} + a_{12}^{2} + \dots +a_{1n}^{2} > 0.$

# 十、填空题

（1）【答案】 $1 - p$

【解】 由 $P(AB) = P(\overline{A}\overline{B})$ 得

$$
P (A B) = P (\overline {{A + B}}) = 1 - P (A + B) = 1 - P (A) - P (B) + P (A B),
$$

即 $1 - P(A) - P(B) = 0$ ，解得 $P(B) = 1 - P(A) = 1 - p$

(2)【答案】 $Z \sim \left( \begin{array}{ll}0 & 1\\ \frac{1}{4} & \frac{3}{4} \end{array} \right).$

【解】 $Z$ 的可能取值为0，1，

$$
\begin{array}{l} P \{Z = 0 \} = P \{\max  (X, Y) = 0 \} = P \{X = 0, Y = 0 \} \\ = P \{X = 0 \} \cdot P \{Y = 0 \} = \frac {1}{4}, \\ \end{array}
$$

$P\{Z = 1\} = 1 - P\{Z = 0\} = \frac{3}{4}$ 则 $Z$ 的分布律为 $Z\sim \left( \begin{array}{cc}0 & 1\\ \frac{1}{4} & \frac{3}{4} \end{array} \right).$

十一、【解】 $(1)E(Z) = \frac{1}{3} E(X) + \frac{1}{2} E(Y) = \frac{1}{3},$

又 $D(X) = 9, D(Y) = 16, \operatorname{Cov}(X, Y) = \rho_{XY} \cdot \sqrt{D(X)} \cdot \sqrt{D(Y)} = \left(-\frac{1}{2}\right) \times 3 \times 4 = -6,$

则

$$
\begin{array}{l} D (Z) = \left(\frac {1}{3}\right) ^ {2} D (X) + \left(\frac {1}{2}\right) ^ {2} D (Y) + 2 \times \frac {1}{3} \times \frac {1}{2} \operatorname {C o v} (X, Y) \\ = \frac {1}{9} D (X) + \frac {1}{4} D (Y) + \frac {1}{3} \operatorname {C o v} (X, Y) = 1 + 4 - 2 = 3. \\ \end{array}
$$

(2) $\operatorname{Cov}(X, Z) = \operatorname{Cov}\left(X, \frac{X}{3}\right) + \operatorname{Cov}\left(X, \frac{Y}{2}\right) = \frac{1}{3} \operatorname{Cov}(X, X) + \frac{1}{2} \operatorname{Cov}(X, Y)$ ,

又 $\operatorname{Cov}(X, X) = D(X) = 9$ ， $\operatorname{Cov}(X, Y) = -6$

则 $\operatorname{Cov}(X,Z) = \frac{1}{3} \times 9 + \frac{1}{2} \times (-6) = 3 - 3 = 0.$

所以 $\rho_{XZ} = \frac{\operatorname{Cov}(X,Z)}{\sqrt{D(X)}\cdot\sqrt{D(Z)}} = 0.$

(3) $\binom{X}{Z} = \left( \begin{array}{cc}1 & 0\\ \frac{1}{3} & \frac{1}{2} \end{array} \right)\binom{X}{Y}\stackrel {\triangle}{=}\mathbf{A}\binom {X}{Y}$ . 因为 $\pmb{A}$ 可逆，且 $(X,Y)$ 服从二维正态分布，故 $(X,Z)$ 也服从二维正态分布，又因为 $\rho_{XZ} = 0$ ，所以 $X$ 与 $Z$ 相互独立.