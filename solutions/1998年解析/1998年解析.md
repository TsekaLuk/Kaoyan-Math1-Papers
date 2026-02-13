# 1998年数学（一）真题解析

# 一、填空题

(1)【答案】 $-\frac{1}{4}$ .

【解】 方法一

由 $(1 + x)^{a} = 1 + ax + \frac{a(a - 1)}{2!} x^{2} + o(x^{2})$ 得

$$
\sqrt {1 + x} = 1 + \frac {1}{2} x - \frac {1}{8} x ^ {2} + o (x ^ {2}), \quad \sqrt {1 - x} = 1 - \frac {1}{2} x - \frac {1}{8} x ^ {2} + o (x ^ {2}),
$$

于是 $\sqrt{1 + x} + \sqrt{1 - x} - 2 = -\frac{1}{4} x^2 + o(x^2) \sim -\frac{1}{4} x^2,$

故 $\lim_{x\to 0}\frac{\sqrt{1 + x} + \sqrt{1 - x} - 2}{x^2} = -\frac{1}{4}.$

方法二

$$
\begin{array}{l} \lim  _ {x \rightarrow 0} \frac {\sqrt {1 + x} + \sqrt {1 - x} - 2}{x ^ {2}} = \lim  _ {x \rightarrow 0} \frac {\frac {1}{2 \sqrt {1 + x}} - \frac {1}{2 \sqrt {1 - x}}}{2 x} \\ = \frac {1}{4} \lim  _ {x \rightarrow 0} \frac {\sqrt {1 - x} - \sqrt {1 + x}}{x \sqrt {1 - x ^ {2}}} = \frac {1}{4} \lim  _ {x \rightarrow 0} \frac {- 2 x}{x (\sqrt {1 + x} + \sqrt {1 - x})} = - \frac {1}{4}. \\ \end{array}
$$

(2)【答案】 $yf''(xy) + \varphi'(x + y) + y\varphi''(x + y).$

【解】 $\frac{\partial z}{\partial x} = -\frac{1}{x^2} f(xy) + \frac{y}{x} f'(xy) + y\varphi'(x + y),$

$$
\begin{array}{l} \frac {\partial^ {2} z}{\partial x \partial y} = - \frac {1}{x} f ^ {\prime} (x y) + \frac {1}{x} f ^ {\prime} (x y) + y f ^ {\prime \prime} (x y) + \varphi^ {\prime} (x + y) + y \varphi^ {\prime \prime} (x + y) \\ = y f ^ {\prime \prime} (x y) + \varphi^ {\prime} (x + y) + y \varphi^ {\prime \prime} (x + y). \\ \end{array}
$$

（3）【答案】 $12a$

【解】 由对称性得

$$
\begin{array}{l} \oint_ {L} (2 x y + 3 x ^ {2} + 4 y ^ {2}) \mathrm {d} s = \oint_ {L} (3 x ^ {2} + 4 y ^ {2}) \mathrm {d} s = 1 2 \oint_ {L} \left(\frac {x ^ {2}}{4} + \frac {y ^ {2}}{3}\right) \mathrm {d} s \\ = 1 2 \oint_ {L} d s = 1 2 a. \\ \end{array}
$$

(4)【答案】 $\left(\frac{|\mathbf{A}|}{\lambda}\right)^2 + 1.$

【解】设 $\mathbf{A}$ 的对应于特征值 $\lambda$ 的特征向量为 $\alpha$ ，则 $A\alpha = \lambda \alpha$

由 $\mathbf{A}^{*}\pmb {\alpha} = \frac{\left|\mathbf{A}\right|}{\lambda}\pmb{\alpha}$ 得 $[(\mathbf{A}^{*})^{2} + \mathbf{E}]\pmb {\alpha} = \left[\left(\frac{\left|\mathbf{A}\right|}{\lambda}\right)^{2} + 1\right]\pmb{\alpha},$

故 $(\mathbf{A}^{*})^{2} + \mathbf{E}$ 一定有特征值 $\left(\frac{|\mathbf{A}|}{\lambda}\right)^2 +1.$

(5)【答案】 $\frac{1}{4}$ .

【解】 区域 $D$ 的面积为 $A = \int_{1}^{\mathrm{e}^{2}}\mathrm{d}x\int_{0}^{\frac{1}{x}}\mathrm{d}y = \int_{1}^{\mathrm{e}^{2}}\frac{1}{x}\mathrm{d}x = 2,$

则 $(X,Y)$ 的联合密度为

$$
f (x, y) = \left\{ \begin{array}{l l} \frac {1}{2}, & (x, y) \in D, \\ 0, & (x, y) \notin D. \end{array} \right.
$$

当 $x \leqslant 1$ 或 $x \geqslant \mathrm{e}^2$ 时， $f_{X}(x) = 0$

当 $1 < x < \mathrm{e}^2$ 时， $f_{X}(x) = \int_{0}^{\frac{1}{x}}\frac{1}{2}\mathrm{d}y = \frac{1}{2x},$

故 $f_{X}(2) = \frac{1}{4}$ .

# 二、选择题

（1）【答案】 （A).

【解】由 $\int_0^x tf(x^2 -t^2)\mathrm{d}t = -\frac{1}{2}\int_0^x f(x^2 -t^2)\mathrm{d}(x^2 -t^2)\frac{x^2 - t^2 = u}{2}\frac{1}{2}\int_0^{x^2}f(u)\mathrm{d}u,$

则 $\frac{\mathrm{d}}{\mathrm{d}x}\int_{0}^{x}tf(x^2 -t^2)\mathrm{d}t = xf(x^2)$ ，应选(A).

(2)【答案】 (B).

【解】 由 $\lim_{x\to -1}\frac{f(x) - f(-1)}{x + 1} = \lim_{x\to -1}\frac{(x + 1)(x - 2)\mid x^3 - x\mid}{x + 1}$

$$
= \lim  _ {[ - ]} (x - 2) \mid x ^ {3} - x \mid = 0,
$$

得 $f^{\prime}(-1) = 0$

$$
\lim  _ {x \rightarrow 0} \frac {f (x) - f (0)}{x - 0} = \lim  _ {x \rightarrow 0} \frac {| x |}{x} \cdot (x ^ {2} - x - 2) | x ^ {2} - 1 |,
$$

显然 $f_{-}^{\prime}(0) = \lim_{x\to 0^{-}}\frac{|x|}{x}\cdot (x^{2} - x - 2)|x^{2} - 1| = 2,$

$$
f _ {+} ^ {\prime} (0) = \lim  _ {x \rightarrow 0 ^ {+}} \frac {| x |}{x} \cdot (x ^ {2} - x - 2) | x ^ {2} - 1 | = - 2,
$$

因为 $f_{-}^{\prime}(0) \neq f_{+}^{\prime}(0)$ ，所以 $x = 0$ 为不可导的点；

$$
\lim  _ {x \rightarrow 1} \frac {f (x) - f (1)}{x - 1} = \lim  _ {x \rightarrow 1} \frac {| x - 1 |}{x - 1} \cdot (x ^ {2} - x - 2) | x (x + 1) |,
$$

显然 $f_{-}^{\prime}(1) = \lim_{x\to 1^{-}}\frac{|x - 1|}{x - 1}\cdot (x^{2} - x - 2)\mid x(x + 1)\mid = 4,$

$$
f _ {+} ^ {\prime} (1) = \lim  _ {x \rightarrow 1 ^ {+}} \frac {| x - 1 |}{x - 1} \cdot (x ^ {2} - x - 2) | x (x + 1) | = - 4,
$$

因为 $f_{-}^{\prime}(1) \neq f_{+}^{\prime}(1)$ ，所以 $x = 1$ 为不可导的点，即 $f(x)$ 有2个不可导的点，应选(B).

(3)【答案】 (D).

【解】由 $\Delta y = \frac{y\Delta x}{1 + x^2} +\alpha$ 得 $y = y(x)$ 可微，从而 $y = y(x)$ 可导，

且 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{y}{1 + x^2}$ 或 $\frac{\mathrm{dy}}{\mathrm{dx}} -\frac{1}{1 + x^2} y = 0$

解得 $y = C\mathrm{e}^{-\int \frac{-1}{1 + x^2}\mathrm{d}x} = C\mathrm{e}^{\arctan x},$

由 $y(0) = \pi$ 得 $C = \pi$ ，于是 $y(x) = \pi \mathrm{e}^{\arctan x}$ 故 $y(1) = \pi \mathrm{e}^{\frac{\pi}{4}}$ ，应选(D).

（4）【答案】 （A）.

【解】因为 $\left| \begin{array}{lll}a_{1} & b_{1} & c_{1}\\ a_{2} & b_{2} & c_{2}\\ a_{3} & b_{3} & c_{3} \end{array} \right| = \left| \begin{array}{ccc}a_{1} - a_{2} & b_{1} - b_{2} & c_{1} - c_{2}\\ a_{2} - a_{3} & b_{2} - b_{3} & c_{2} - c_{3}\\ a_{3} & b_{3} & c_{3} \end{array} \right|\neq 0,$

所以两条直线的方向向量不平行，（B）与（C）不对；

令 $s_1 = \{a_1 - a_2, b_1 - b_2, c_1 - c_2\}$ , $s_2 = \{a_2 - a_3, b_2 - b_3, c_2 - c_3\}$

$M_{1}(a_{3},b_{3},c_{3}),M_{2}(a_{1},b_{1},c_{1})$ 分别为两条直线上的点，

$$
\overrightarrow {M _ {1} M _ {2}} = \left\{a _ {1} - a _ {3}, b _ {1} - b _ {3}, c _ {1} - c _ {3} \right\},
$$

因为 $\overrightarrow{M_1M_2} \cdot (\pmb{s}_1 \times \pmb{s}_2) = \left| \begin{array}{ccc} a_1 - a_3 & b_1 - b_3 & c_1 - c_3 \\ a_1 - a_2 & b_1 - b_2 & c_1 - c_2 \\ a_2 - a_3 & b_2 - b_3 & c_2 - c_3 \end{array} \right| = 0$ ，所以两直线共面且不平行，即两直线交于一点，应选(A).

（5）【答案】 (C).

【解】由 $P(B\mid A) = P(B\mid \overline{A})$ 得 $\frac{P(AB)}{P(A)} = \frac{P(\overline{A}B)}{P(\overline{A})}$

由减法公式及补概率的公式得 $\frac{P(AB)}{P(A)} = \frac{P(B) - P(AB)}{1 - P(A)}$

整理得 $P(AB) = P(A)P(B)$ ，应选(C).

三、【解】 方法一 $L$ 的参数方程为 $L:\left\{ \begin{array}{ll}x = 1 + t,\\ y = t,\\ z = 1 - t, \end{array} \right.$ 代入 $\pi$ 得 $L$ 与 $\pi$ 的交点为 $M_{1}(2,1,0)$

$M_0(1,0,1)\in L$ ，过 $M_0$ 且与 $\pi$ 垂直的直线为 $L^{\prime}$ ： $\frac{x - 1}{1} = \frac{y}{-1} = \frac{z - 1}{2},$

$L^{\prime}$ 的参数方程为 $L^{\prime}$ $\begin{cases} x = 1 + t,\\ y = -t,\\ z = 1 + 2t, \end{cases}$ 代入 $\pi$ 得垂足坐标为 $M_2\left(\frac{2}{3},\frac{1}{3},\frac{1}{3}\right)$

$\overrightarrow{M_2M_1} = \left\{\frac{4}{3},\frac{2}{3}, - \frac{1}{3}\right\}$ 故 $L_{0}: \frac{x - 2}{4} = \frac{y - 1}{2} = \frac{z}{-1}.$

设 $L_{0}$ 绕 $y$ 轴旋转一周所得的旋转曲面为 $\Sigma$ ，任取 $P(x,y,z)\in \Sigma$ ，其所在的圆周对应的 $L_{0}$ 上的点为 $P_0(x_0,y,z_0)$ ，圆心为 $T(0,y,0)$

由 $|PT| = |P_0T|$ 得 $x^{2} + z^{2} = x_{0}^{2} + z_{0}^{2}$

再由 $P_{0}(x_{0},y,z_{0})\in L_{0}$ 得 $\frac{x_0 - 2}{4} = \frac{y - 1}{2} = \frac{z_0}{-1}$ 解得 $x_0 = 2y,z_0 = -\frac{y - 1}{2}$

故 $\Sigma$ 的方程为 $4x^{2} - 17y^{2} + 4z^{2} + 2y - 1 = 0.$

方法二

直线 $L: \frac{x - 1}{1} = \frac{y}{1} = \frac{z - 1}{-1}$ 的一般形式为 $L: \left\{ \begin{array}{l} \frac{x - 1}{1} = \frac{y}{1}, \\ \frac{y}{1} = \frac{z - 1}{-1}, \end{array} \right.$ $L: \left\{ \begin{array}{l} x - y - 1 = 0, \\ y + z - 1 = 0, \end{array} \right.$

过直线 $L$ 的平面束为 $\pi_0:(x - y - 1) + \lambda (y + z - 1) = 0$ ，即

$$
\pi_ {0}: x + (\lambda - 1) y + \lambda z - 1 - \lambda = 0,
$$

由 $\{1, - 1,2\} \cdot \{1,\lambda -1,\lambda \} = 0$ 得 $\lambda = -2$

则投影直线为 $L_{0}$ $\left\{ \begin{array}{l}x - 3y - 2z + 1 = 0,\\ x - y + 2z - 1 = 0. \end{array} \right.$

显然 $M_0(2,1,0)\in L_0,L_0$ 的方向向量为

$$
s = \{1, - 3, - 2 \} \times \{1, - 1, 2 \} = \{- 8, - 4, 2 \},
$$

直线 $L_{0}$ 的点向式方程为 $L_{0}:\frac{x - 2}{4} = \frac{y - 1}{2} = \frac{z}{-1}.$

设 $L_{0}$ 绕 $y$ 轴旋转一周所得的旋转曲面为 $\Sigma$ ，任取 $P(x,y,z)\in \Sigma$ ，其所在的圆周对应的 $L_{0}$ 上的点为 $P_0(x_0,y,z_0)$ ，圆心为 $T(0,y,0)$

由 $|PT| = |P_0T|$ 得 $x^{2} + z^{2} = x_{0}^{2} + z_{0}^{2}$

再由 $P_{0}(x_{0},y,z_{0})\in L_{0}$ 得 $\frac{x_0 - 2}{4} = \frac{y - 1}{2} = \frac{z_0}{-1}$ 解得 $x_0 = 2y,z_0 = -\frac{y - 1}{2}$

故 $\Sigma$ 的方程为 $4x^{2} - 17y^{2} + 4z^{2} + 2y - 1 = 0.$

四、【解】 $P(x,y) = 2xy(x^4 +y^2)^{\lambda},\quad Q(x,y) = -x^2 (x^4 +y^2)^{\lambda},$

$$
\frac {\partial Q}{\partial x} = - 2 x \left(x ^ {4} + y ^ {2}\right) ^ {\lambda} - 4 \lambda x ^ {5} \left(x ^ {4} + y ^ {2}\right) ^ {\lambda - 1},
$$

$$
\frac {\partial P}{\partial y} = 2 x \left(x ^ {4} + y ^ {2}\right) ^ {\lambda} + 4 \lambda x y ^ {2} \left(x ^ {4} + y ^ {2}\right) ^ {\lambda - 1},
$$

由 $\frac{\partial P}{\partial y} = \frac{\partial Q}{\partial x}$ 得 $4x(\lambda + 1)(x^4 + y^2) = 0$ ，解得 $\lambda = -1$

则 $u(x,y) = \int_{(1,0)}^{(x,y)}\frac{2xy\mathrm{d}x - x^2\mathrm{d}y}{x^4 + y^2} = \int_1^x 0\mathrm{d}x + \int_0^y\frac{-x^2\mathrm{d}y}{x^4 + y^2} = -\arctan \frac{y}{x^2} +C,$

故所求的二元函数为 $u(x,y) = -\arctan \frac{y}{x^2} +C(C$ 为任意常数).

五、【解】 取沉放点为坐标原点， $y$ 轴铅直向下，由牛顿第二定律得

$$
m \frac {\mathrm {d} ^ {2} y}{\mathrm {d} t ^ {2}} = m g - B \rho - k v,
$$

令 $\frac{\mathrm{dy}}{\mathrm{dt}} = v$ ，则 $\frac{\mathrm{d}^2y}{\mathrm{d}t^2} = v\frac{\mathrm{d}v}{\mathrm{d}y}$ 代人得 $\frac{mv\mathrm{d}v}{\mathrm{d}y} = mg - B\rho -kv$

变量分离得 $\frac{mv\mathrm{d}v}{mg - B\rho - kv} = \mathrm{dy}$ ，积分得

$$
y = - \frac {m}{k} v - \frac {m (m g - B \rho)}{k ^ {2}} \ln (m g - B \rho - k v) + C _ {0},
$$

由 $y|_{t = 0} = 0, v|_{t = 0} = 0$ 得 $C_0 = \frac{m(mg - B\rho)}{k^2}\ln (mg - B\rho)$

故 $y = -\frac{m}{k} v - \frac{m(mg - B\rho)}{k^2}\ln \frac{mg - B\rho - kv}{mg - B\rho}.$

六、【解】 $I = \iint_{\Sigma} \frac{ax \, \mathrm{d}y \, \mathrm{d}z + (z + a)^2 \, \mathrm{d}x \, \mathrm{d}y}{\sqrt{x^2 + y^2 + z^2}} = \frac{1}{a} \iint_{\Sigma} ax \, \mathrm{d}y \, \mathrm{d}z + (z + a)^2 \, \mathrm{d}x \, \mathrm{d}y,$

令 $\Sigma_0: z = 0 (x^2 + y^2 \leqslant a^2)$ ，取下侧，则

$$
\iint_ {\Sigma} a x \mathrm {d} y \mathrm {d} z + (z + a) ^ {2} \mathrm {d} x \mathrm {d} y = \iint_ {\Sigma + \Sigma_ {0}} a x \mathrm {d} y \mathrm {d} z + (z + a) ^ {2} \mathrm {d} x \mathrm {d} y - \iint_ {\Sigma_ {0}} a x \mathrm {d} y \mathrm {d} z + (z + a) ^ {2} \mathrm {d} x \mathrm {d} y,
$$

而 $\iint_{\Sigma + \Sigma_0} ax \, \mathrm{d}y \, \mathrm{d}z + (z + a)^2 \, \mathrm{d}x \, \mathrm{d}y = -\iiint_{\Omega} (2z + 3a) \, \mathrm{d}v = -2\iiint_{\Omega} z \, \mathrm{d}v - 3a \cdot \frac{2}{3}\pi a^3$

$$
\begin{array}{l} = - 2 \int_ {0} ^ {2 \pi} d \theta \int_ {\frac {\pi}{2}} ^ {\pi} d \varphi \int_ {0} ^ {a} r ^ {3} \sin \varphi \cos \varphi d r - 2 \pi a ^ {4} \\ = \frac {\pi a ^ {4}}{2} - 2 \pi a ^ {4} = - \frac {3 \pi a ^ {4}}{2}; \\ \end{array}
$$

又 $\iint_{\Sigma_0} ax \, \mathrm{d}y \, \mathrm{d}z + (z + a)^2 \, \mathrm{d}x \, \mathrm{d}y = -\iint_{x^2 + y^2 \leqslant a^2} a^2 \, \mathrm{d}x \, \mathrm{d}y = -\pi a^4,$

故 $I = \frac{1}{a}\left(-\frac{3\pi a^4}{2} + \pi a^4\right) = -\frac{1}{2}\pi a^3.$

七、【解】 $b_{n} = \frac{\sin\frac{\pi}{n}}{n + 1} +\frac{\sin\frac{2\pi}{n}}{n + \frac{1}{2}} +\dots +\frac{\sin\frac{n\pi}{n}}{n + \frac{1}{n}},$

$$
\frac {1}{n + 1} \sum_ {i = 1} ^ {n} \sin \frac {\pi i}{n} \leqslant b _ {n} \leqslant \frac {1}{n} \sum_ {i = 1} ^ {n} \sin \frac {\pi i}{n},
$$

因为 $\lim_{n\to \infty}\frac{1}{n + 1}\sum_{i = 1}^{n}\sin \frac{\pi i}{n} = \lim_{n\to \infty}\frac{n}{n + 1}\cdot \frac{1}{n}\sum_{i = 1}^{n}\sin \frac{\pi i}{n} = \lim_{n\to \infty}\frac{1}{n}\sum_{i = 1}^{n}\sin \frac{\pi i}{n} = \int_0^1\sin \pi x\mathrm{d}x,$

所以由夹逼定理得

$$
\begin{array}{l} \lim  _ {n \rightarrow \infty} \left(\frac {\sin \frac {\pi}{n}}{n + 1} + \frac {\sin \frac {2 \pi}{n}}{n + \frac {1}{2}} + \dots + \frac {\sin \frac {n \pi}{n}}{n + \frac {1}{n}}\right) = \int_ {0} ^ {1} \sin \pi x d x = \frac {1}{\pi} \int_ {0} ^ {1} \sin \pi x d (\pi x) \\ = \frac {1}{\pi} \int_ {0} ^ {\pi} \sin x d x = \frac {2}{\pi}. \\ \end{array}
$$

八、【解】因为 $\{a_{n}\}$ 单调递减且 $a_{n} > 0$ ，所以 $\lim_{n\to \infty}a_n$ 存在，设 $\lim_{n\to \infty}a_n = A$ ，显然 $A\geqslant 0$

因为交错级数 $\sum_{n=1}^{\infty}(-1)^{n}a_{n}$ 发散且 $\{a_{n}\}$ 单调递减，所以 $A > 0$

对正项级数 $\sum_{n=1}^{\infty}\left(\frac{1}{a_n + 1}\right)^n$

因为 $\lim_{n\to \infty}\sqrt[n]{\left(\frac{1}{a_n + 1}\right)^n} = \lim_{n\to \infty}\frac{1}{a_n + 1} = \frac{1}{A + 1} < 1$ ，所以级数 $\sum_{n = 1}^{\infty}\left(\frac{1}{a_n + 1}\right)^n$ 收敛.

九、【证明】 $(1)S_{1}(x_{0}) = x_{0}f(x_{0}),\quad S_{2}(x_{0}) = \int_{x_{0}}^{1}f(x)\mathrm{d}x,$

令 $\varphi (x) = xf(x) - \int_{x}^{1}f(t)\mathrm{d}t$

显然 $F(x) = x\int_{x}^{x}f(t)\mathrm{d}t$ 为 $\varphi (x)$ 的原函数，即 $F^{\prime}(x) = \varphi (x)$

$F(0) = F(1) = 0$ ，由罗尔定理，存在 $x_0\in (0,1)$ ，使得 $F^{\prime}(x_0) = 0$ ，即 $\varphi (x_0) = 0$

故存在 $x_0 \in (0,1)$ ，使得 $S_{1}(x_{0}) = S_{2}(x_{0})$

$$
(2) \varphi^ {\prime} (x) = f (x) + x f ^ {\prime} (x) + f (x) = x f ^ {\prime} (x) + 2 f (x),
$$

由 $f^{\prime}(x) > - \frac{2f(x)}{x}$ 得 $xf^{\prime}(x) + 2f(x) > 0$ ，即 $\varphi '(x) > 0(0 <   x <   1)$

则 $\varphi (x)$ 在(0，1）内严格递增，故（1）中的 $x_0$ 是唯一的

十、【解】 令 $\mathbf{A} = \begin{pmatrix} 1 & b & 1 \\ b & a & 1 \\ 1 & 1 & 1 \end{pmatrix}, \mathbf{X} = \begin{pmatrix} x \\ y \\ z \end{pmatrix}$ ，则二次曲面表示为 $\mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X} = 4$

因为 $\mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}$ 经过正交变换可以化为 $\eta^2 +4\xi^2$ ，所以矩阵 $\mathbf{A}$ 的特征值为 $\lambda_1 = 0,\lambda_2 = 1,\lambda_3 = 4$ 由 $\operatorname {tr}\mathbf{A} = \lambda_{1} + \lambda_{2} + \lambda_{3}$ 得 $a + 2 = 5$ ，解得 $a = 3$

由 $|\mathbf{A}| = \lambda_1\lambda_2\lambda_3$ 得 $b = 1$ ，即 $\mathbf{A} = \begin{pmatrix} 1 & 1 & 1\\ 1 & 3 & 1\\ 1 & 1 & 1 \end{pmatrix} .$

由 $0E - A \rightarrow \left( \begin{array}{ccc}1 & 0 & 1\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_{1} = 0$ 对应的特征向量为 $\pmb{\alpha}_{1} = \left( \begin{array}{c} - 1\\ 0\\ 1 \end{array} \right)$

由 $\pmb {E} - \pmb {A}\rightarrow \left( \begin{array}{lll}1 & 0 & -1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_{2} = 1$ 对应的特征向量为 $\pmb{\alpha}_{2} = \left( \begin{array}{l}1\\ -1\\ 1 \end{array} \right)$

由 $4\pmb {E} - \pmb {A}\rightarrow \left( \begin{array}{rrr}1 & 0 & -1\\ 0 & 1 & -2\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_3 = 4$ 对应的特征向量为 $\alpha_{3} = \binom{1}{2}$

规范化得 $\gamma_{1} = \frac{1}{\sqrt{2}}\binom{-1}{0},\quad \gamma_{2} = \frac{1}{\sqrt{3}}\binom{1}{-1},\quad \gamma_{3} = \frac{1}{\sqrt{6}}\binom{1}{2},$

得正交矩阵 $\pmb{P} = \left[ \begin{array}{ccc} - \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{6}}\\ 0 & -\frac{1}{\sqrt{3}} & \frac{2}{\sqrt{6}}\\ \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{6}} \end{array} \right].$

十一、【证明】 显然 $\mathbf{A}^k\pmb {\alpha} = \mathbf{0}$ ，令 $l_0\pmb {\alpha} + l_1\pmb {A}\pmb {\alpha} + \dots +l_{k - 1}\pmb{A}^{k - 1}\pmb {\alpha} = \mathbf{0},$

将 $l_0\pmb {\alpha} + l_1\pmb {A}\pmb {\alpha} + \dots +l_{k - 1}\pmb{A}^{k - 1}\pmb {\alpha} = \mathbf{0}$ 两边左乘 $\mathbf{A}^{k - 1}$ 得 $l_0\pmb{A}^{k - 1}\pmb {\alpha} = \mathbf{0}$

因为 $A^{k - 1}\alpha \neq 0$ ，所以 $l_0 = 0$

将 $l_{1}\mathbf{A}\pmb{\alpha} + \dots + l_{k - 1}\mathbf{A}^{k - 1}\pmb{\alpha} = \mathbf{0}$ 两边左乘 $\mathbf{A}^{k - 2}$ 得 $l_{1}\mathbf{A}^{k - 1}\pmb{\alpha} = \mathbf{0}$ ，从而 $l_{1} = 0$

依次类推，可得 $l_{2} = \dots = l_{k - 1} = 0$ ，故 $\alpha ,A\alpha ,\dots ,A^{k - 1}\alpha$ 线性无关.

十二、【解】 令 $\mathbf{A} = \begin{bmatrix} a_{11} & a_{12} & \dots & a_{1,2n}\\ a_{21} & a_{22} & \dots & a_{2,2n}\\ \vdots & \vdots & & \vdots \\ a_{n1} & a_{n2} & \dots & a_{n,2n} \end{bmatrix},\mathbf{X} = \begin{bmatrix} x_1\\ x_2\\ \vdots \\ x_{2n} \end{bmatrix},\mathbf{B} = \begin{bmatrix} b_{11} & b_{21} & \dots & b_{n1}\\ b_{12} & b_{22} & \dots & b_{n2}\\ \vdots & \vdots & & \vdots \\ b_{1,2n} & b_{2,2n} & \dots & b_{n,2n} \end{bmatrix},$

因为 $(b_{11}, b_{12}, \dots, b_{1,2n})^{\mathrm{T}}, (b_{21}, b_{22}, \dots, b_{2,2n})^{\mathrm{T}}, \dots, (b_{n1}, b_{n2}, \dots, b_{n,2n})^{\mathrm{T}}$ 为方程组 $\mathbf{A}\mathbf{X} = \mathbf{0}$ 的基础解系，所以 $r(\mathbf{A}) = 2n - n = n$ 且 $\mathbf{AB} = \mathbf{O}$ .

又因为 $(b_{11}, b_{12}, \dots, b_{1,2n})^{\mathrm{T}}, (b_{21}, b_{22}, \dots, b_{2,2n})^{\mathrm{T}}, \dots, (b_{n1}, b_{n2}, \dots, b_{n,2n})^{\mathrm{T}}$ 线性无关，

所以 $r(\mathbf{B}) = n$

令 $\mathbf{Y} = (y_{1}, y_{2}, \dots, y_{2n})^{\mathrm{T}}$ ，方程组（Ⅱ）表示为 $\mathbf{B}^{\mathrm{T}}\mathbf{Y} = \mathbf{0}$ ，

由 $\mathbf{AB} = \mathbf{0}$ 得 $\mathbf{B}^{\mathrm{T}}\mathbf{A}^{\mathrm{T}} = \mathbf{0}$ ，即 $(a_{11}, a_{12}, \dots, a_{1,2n})^{\mathrm{T}}, (a_{21}, a_{22}, \dots, a_{2,2n})^{\mathrm{T}}, \dots, (a_{n1}, a_{n2}, \dots, a_{n,2n})^{\mathrm{T}}$ 为方程组 $\mathbf{B}^{\mathrm{T}}\mathbf{Y} = \mathbf{0}$ 的解.

因为 $r(\mathbf{A}) = n$ ，所以 $(a_{11}, a_{12}, \dots, a_{1,2n})^{\mathrm{T}}, (a_{21}, a_{22}, \dots, a_{2,2n})^{\mathrm{T}}, \dots, (a_{n1}, a_{n2}, \dots, a_{n,2n})^{\mathrm{T}}$ 线性无关，又因为 $r(\mathbf{B}^{\mathrm{T}}) = n$ ，所以 $(a_{11}, a_{12}, \dots, a_{1,2n})^{\mathrm{T}}, (a_{21}, a_{22}, \dots, a_{2,2n})^{\mathrm{T}}, \dots, (a_{n1}, a_{n2}, \dots, a_{n,2n})^{\mathrm{T}}$ 为方程组（Ⅱ）的一个基础解系.

十三、【解】 令 $Z = X - Y$

因为 $X, Y$ 相互独立且都服从正态分布 $N\left(0, \frac{1}{2}\right)$ ，所以 $X - Y \sim N(0, 1)$ ，即 $Z \sim N(0, 1)$

于是 $E(|X - Y|) = E(|Z|) = \frac{1}{\sqrt{2\pi}} \int_{-\infty}^{+\infty} |z| \mathrm{e}^{-\frac{z^2}{2}} \, \mathrm{d}z$

$$
= \frac {2}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} z e ^ {- \frac {z ^ {2}}{2}} d z = \frac {2}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} e ^ {- \frac {z ^ {2}}{2}} d \left(\frac {z ^ {2}}{2}\right) = \frac {2}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} e ^ {- t} d t = \frac {2}{\sqrt {2 \pi}},
$$

又 $E(|X - Y|^2) = E(|Z|^2) = E(Z^2) = D(Z) + [E(Z)]^2 = 1$

故 $D(|X - Y|) = E(|X - Y|^2) - [E(|X - Y|)]^2 = 1 - \frac{2}{\pi}.$

十四、【解】设 $\overline{X}$ 为样本均值，则 $\overline{X} \sim N\left(3.4, \frac{6^2}{n}\right)$ 或 $\frac{\overline{X} - 3.4}{\sqrt{n}} \sim N(0,1)$

由 $P\{1.4 < \overline{X} < 5.4\} = P\left\{-\frac{2}{\frac{6}{\sqrt{n}}} < \frac{\overline{X} - 3.4}{\frac{6}{\sqrt{n}}} < \frac{2}{\frac{6}{\sqrt{n}}}\right\} = 2\Phi \left(\frac{\sqrt{n}}{3}\right) - 1 > 0.95$ 得

$\Phi \left(\frac{\sqrt{n}}{3}\right) > 0.975$ ，即 $\frac{\sqrt{n}}{3} >1.96$

解得 $n > 34.57$ ，故 $n$ 至少取35.

十五、【解】 设总体 $X \sim N(\mu, \sigma^2)$

令 $H_0: \mu = 70, \quad H_1: \mu \neq 70,$

取统计量 $t = \frac{\overline{X} - 70}{\frac{s}{\sqrt{36}}}\sim t(35)$

由 $t_{0.975}(35) = 2.0301$ 得 $H_0$ 的接受域为 $(-2.0301, 2.0301)$ ，

因为 $\frac{66.5 - 70}{\frac{15}{6}} = -1.4 \in (-2.0301, 2.0301)$ ，所以接受 $H_0$ ，即可以认为该批考生的平均成绩为70分。