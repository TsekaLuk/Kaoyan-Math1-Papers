# 2018年数学(一）真题解析

# 一、选择题

（1）【答案】 (D).

【解】 方法一 对 $f(x) = \cos \sqrt{|x|}$

$\lim_{x \to 0} \frac{f(x) - f(0)}{x} = \lim_{x \to 0} \frac{\cos \sqrt{|x|} - 1}{x} = -\frac{1}{2} \lim_{x \to 0} \frac{|x|}{x}$ 不存在，即 $f(x) = \cos \sqrt{|x|}$ 在 $x = 0$ 处不可导，应选(D).

方法二

当 $f(x) = |x|\sin |x|$ 时， $f(x) - f(0) \sim x^2, f(x)$ 在 $x = 0$ 处可导且导数为0，不选(A)；当 $f(x) = |x|\sin \sqrt{|x|}$ 时， $f(x) - f(0) \sim |x|^{\frac{3}{2}}, f(x)$ 在 $x = 0$ 处可导且导数为0，不选(B)；

当 $f(x) = \cos |x|$ 时， $f(x) - f(0) \sim -\frac{1}{2} x^2$ ， $f(x)$ 在 $x = 0$ 处可导且导数为 0，不选 (C)，应选 (D).

(2)【答案】 (B).

【解】 设切点为 $(x_0, y_0, z_0)$ ，则

$$
\left\{ \begin{array}{l} z _ {0} = x _ {0} ^ {2} + y _ {0} ^ {2}, \\ (2 x _ {0}, 2 y _ {0}, - 1) \cdot (1, - 1, 0) = 0, \\ (2 x _ {0}, 2 y _ {0}, - 1) \cdot (x _ {0} - 1, y _ {0}, z _ {0}) = 0, \end{array} \right.
$$

解之得 $\begin{cases} x_0 = 0, \\ y_0 = 0, \\ z_0 = 0, \end{cases}$ 或 $\begin{cases} x_0 = 1, \\ y_0 = 1, \\ z_0 = 2, \end{cases}$

故所求切平面为 $z = 0$ 或 $2x + 2y - z = 2$ . 应选(B).

（3）【答案】 (B).

【解】 $\sum_{n = 0}^{\infty}(-1)^{n}\frac{2n + 3}{(2n + 1)!} = \sum_{n = 0}^{\infty}(-1)^{n}\frac{1}{(2n)!} +2\sum_{n = 0}^{\infty}(-1)^{n}\frac{1}{(2n + 1)!}$

$$
= \cos 1 + 2 \sin 1,
$$

应选（B）.

（4）【答案】 (C).

【解】 $M = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{(1 + x)^{2}}{1 + x^{2}}\mathrm{d}x = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\left(1 + \frac{2x}{1 + x^{2}}\right)\mathrm{d}x = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\mathrm{d}x = \pi ,$

当 $-\frac{\pi}{2} \leqslant x \leqslant \frac{\pi}{2}$ 时, $1 + \sqrt{\cos x} > 1 > \frac{1 + x}{\mathrm{e}^x}$ ,

$\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}(1 + \sqrt{\cos x})\mathrm{d}x > \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}1\mathrm{d}x > \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{1 + x}{\mathrm{e}^x}\mathrm{d}x$ ，即 $K > M > N.$ 应选(C).

（5）【答案】 （A）.

【解】 方法一

令 $\pmb {M} = \left( \begin{array}{lll}1 & 1 & 0\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right),\pmb {A} = \left( \begin{array}{lll}1 & 1 & -1\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right),\pmb {B} = \left( \begin{array}{lll}1 & 0 & -1\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right),$

$$
\boldsymbol {C} = \left( \begin{array}{c c c} 1 & 1 & - 1 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{array} \right), \boldsymbol {D} = \left( \begin{array}{c c c} 1 & 0 & - 1 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{array} \right),
$$

显然矩阵 $A, B, C, D$ 的特征值都是 $\lambda_{1} = \lambda_{2} = \lambda_{3} = 1$

$$
\begin{array}{l} \boldsymbol {E} - \boldsymbol {M} = \left( \begin{array}{c c c} 0 & - 1 & 0 \\ 0 & 0 & - 1 \\ 0 & 0 & 0 \end{array} \right), \boldsymbol {E} - \boldsymbol {A} = \left( \begin{array}{c c c} 0 & - 1 & 1 \\ 0 & 0 & - 1 \\ 0 & 0 & 0 \end{array} \right), \boldsymbol {E} - \boldsymbol {B} = \left( \begin{array}{c c c} 0 & 0 & 1 \\ 0 & 0 & - 1 \\ 0 & 0 & 0 \end{array} \right), \\ \boldsymbol {E} - \boldsymbol {C} = \left( \begin{array}{c c c} 0 & - 1 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{array} \right), \boldsymbol {E} - \boldsymbol {D} = \left( \begin{array}{c c c} 0 & 0 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{array} \right), \\ \end{array}
$$

因为 $r(\pmb {E} - \pmb {M}) = r(\pmb {E} - \pmb {A}) = 2$ ，所以应选（A）.

方法二

取 $\pmb {P} = \left( \begin{array}{lll}1 & -1 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right)$ ，则 $P^{-1} = \left( \begin{array}{lll}1 & 1 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right),$

因为 $P^{-1}\left( \begin{array}{lll}1 & 1 & -1\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right)P = \left( \begin{array}{lll}1 & 1 & 0\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right)$ ，所以 $\left( \begin{array}{lll}1 & 1 & 0\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right)$ 与 $\left( \begin{array}{lll}1 & 1 & -1\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right)$ 相似，应选（A）.

（6）【答案】 （A）.

【解】 $(A,AB) = A(E,B)$

显然 $r(\mathbf{A},\mathbf{AB}) = r[\mathbf{A}(\mathbf{E},\mathbf{B})]\leqslant r(\mathbf{A}),$

又 $r(A, AB) \geqslant r(A)$ ,

于是 $r(\mathbf{A},\mathbf{AB}) = r(\mathbf{A})$ ，应选（A）.

（7）【答案】 （A）.

【解】 $\int_0^1 f(x)\mathrm{d}x = \int_1^2 f(x)\mathrm{d}x = \frac{1}{2}\int_0^2 f(x)\mathrm{d}x = 0.3,$

$P(X < 0) = \int_{-\infty}^{0} f(x) \, \mathrm{d}x = \int_{-\infty}^{1} f(x) \, \mathrm{d}x - \int_{0}^{1} f(x) \, \mathrm{d}x = 0.5 - 0.3 = 0.2$ ，应选(A).

（8）【答案】 (D).

【解】若 $\sigma^2$ 已知，则假设 $H_0$ 的接受域： $|u| < u_{\frac{\alpha}{2}}$ ，其中 $u_{\frac{\alpha}{2}}$ 为正态分布的 $\frac{\alpha}{2}$ （上）分位数。若 $\sigma^2$ 未知，则假设 $H_0$ 的接受域： $|t| < t_{\frac{\alpha}{2}}(n - 1)$ ，其中 $t_{\frac{\alpha}{2}}(n - 1)$ 为自由度是 $n - 1$ 的 $t$ 分布的 $\frac{\alpha}{2}$ （上）分位数。显然检验水平 $\alpha$ 变小，接受域都变大。应选(D)。

# 二、填空题

（9）【答案】 -2.

【解】因为 $\lim_{x\to 0}\frac{1}{\sin kx}\cdot \left(\frac{1 - \tan x}{1 + \tan x} -1\right) = \lim_{x\to 0}\frac{1}{\sin kx}\cdot \frac{-2\tan x}{1 + \tan x} = \lim_{x\to 0}\frac{1}{kx}\cdot \frac{-2x}{1 + \tan x} = -\frac{2}{k},$

故 $\lim_{x\to 0}\left(\frac{1 - \tan x}{1 + \tan x}\right)^{\frac{1}{\sin kx}} = \mathrm{e}^{-\frac{2}{k}} = \mathrm{e}$ 即 $k = -2$

(10)【答案】 $2(\ln 2 - 1)$

【解】 $f^{\prime}(1) = (2^{x})^{\prime}\big|_{x = 1} = 2\ln 2,$

$$
\begin{array}{l} \int_ {0} ^ {1} x f ^ {\prime \prime} (x) d x = \int_ {0} ^ {1} x d f ^ {\prime} (x) = x f ^ {\prime} (x) \left| _ {0} ^ {1} - \int_ {0} ^ {1} f ^ {\prime} (x) d x = f ^ {\prime} (1) - f (1) + f (0) \right. \\ = 2 \ln 2 - 2 = 2 (\ln 2 - 1). \\ \end{array}
$$

（11）【答案】 $i - k$

【解】rot $\pmb {F}(1,1,0) = \left| \begin{array}{ccc}\pmb {i} & \pmb {j} & \pmb {k}\\ \frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z}\\ xy & -yz & zx \end{array} \right|_{(1,1,0)} = (y\pmb {i} - z\pmb {j} - x\pmb {k})\bigg|_{(1,1,0)} = \pmb {i} - \pmb {k}.$

(12)【答案】 $-\frac{\pi}{3}$ .

【解】 $\oint_{L}xy\mathrm{d}s = \frac{1}{3}\oint_{L}(xy + yz + xz)\mathrm{d}s = \frac{1}{6}\oint_{L}[(x + y + z)^{2} - (x^{2} + y^{2} + z^{2})]\mathrm{d}s$

$$
= - \frac {1}{6} \oint_ {L} d s = - \frac {\pi}{3}.
$$

（13）【答案】 -1.

【解】 $\pmb{\alpha}_{1},\pmb{\alpha}_{2}$ 是 $\mathbf{A}$ 的线性无关的特征向量，则 $\pmb{\alpha}_{1},\pmb{\alpha}_{2}$ 是 $A^2$ 的线性无关的特征向量.

由 $A^2 (\alpha_1 + \alpha_2) = \alpha_1 + \alpha_2$ ，得 $\alpha_{1} + \alpha_{2}$ 也为 $A^2$ 的特征向量，因此 $A^2$ 有二重特征值 $\lambda = 1$ 因为 $\mathbf{A}$ 有两个不同的特征值，所以 $\mathbf{A}$ 的特征值为 $\lambda_{1} = -1,\lambda_{2} = 1$ ，于是 $|\textbf{A}| = -1$

(14)【答案】 $\frac{1}{4}$ .

【解】由 $BC = \varnothing$ ，得 $P(BC) = 0$ ，因为 $ABC\subset BC$ ，所以 $P(ABC) = 0$

$$
\begin{array}{l} P (A C \mid A B \cup C) = \frac {P [ A C (A B \cup C) ]}{P (A B \cup C)} = \frac {P [ (A B C) \cup (A C) ]}{P (A B \cup C)} = \frac {P (A C)}{P (A B \cup C)} \\ = \frac {P (A) P (C)}{P (A) P (B) + P (C) - P (A B C)} = \frac {\frac {1}{2} P (C)}{\frac {1}{2} \times \frac {1}{2} + P (C) - 0} = \frac {1}{4}, \\ \end{array}
$$

解得 $P(C) = \frac{1}{4}$ .

# 三、解答题

(15)【解】 $\int \mathrm{e}^{2x}\arctan \sqrt{\mathrm{e}^x - 1}\mathrm{d}x$

$$
\begin{array}{l} = \frac {1}{2} \int \arctan \sqrt {\mathrm {e} ^ {x} - 1} \mathrm {d e} ^ {2 x} = \frac {1}{2} \mathrm {e} ^ {2 x} \arctan \sqrt {\mathrm {e} ^ {x} - 1} - \frac {1}{2} \int \mathrm {e} ^ {2 x} \operatorname {d a r c t a n} \sqrt {\mathrm {e} ^ {x} - 1} \\ = \frac {1}{2} \mathrm {e} ^ {2 x} \arctan \sqrt {\mathrm {e} ^ {x} - 1} - \frac {1}{4} \int \frac {\mathrm {e} ^ {2 x}}{\sqrt {\mathrm {e} ^ {x} - 1}} \mathrm {d} x = \frac {1}{2} \mathrm {e} ^ {2 x} \arctan \sqrt {\mathrm {e} ^ {x} - 1} - \frac {1}{2} \int \mathrm {e} ^ {x} \mathrm {d} \sqrt {\mathrm {e} ^ {x} - 1} \\ \end{array}
$$

$$
\begin{array}{l} = \frac {1}{2} e ^ {2 x} \arctan \sqrt {e ^ {x} - 1} - \frac {1}{2} (e ^ {x} \sqrt {e ^ {x} - 1} - \int \sqrt {e ^ {x} - 1} d e ^ {x}) \\ = \frac {1}{2} e ^ {2 x} \arctan \sqrt {e ^ {x} - 1} - \frac {1}{2} \left[ e ^ {x} \sqrt {e ^ {x} - 1} - \frac {2}{3} (e ^ {x} - 1) ^ {\frac {3}{2}} \right] + C \\ = \frac {1}{2} e ^ {2 x} \arctan \sqrt {e ^ {x} - 1} - \frac {1}{6} (e ^ {x} + 2) \sqrt {e ^ {x} - 1} + C. \\ \end{array}
$$

（16）【解】设铁丝分成的三段长分别是 $x, y, z$ ，则 $x + y + z = 2$ ，且依次围成的圆、正方形与正三角形三个图形的面积之和为

$$
f (x, y, z) = \pi \left(\frac {x}{2 \pi}\right) ^ {2} + \left(\frac {y}{4}\right) ^ {2} + \frac {\sqrt {3}}{4} \left(\frac {z}{3}\right) ^ {2} = \frac {x ^ {2}}{4 \pi} + \frac {y ^ {2}}{1 6} + \frac {\sqrt {3}}{3 6} z ^ {2},
$$

构造拉格朗日函数： $L(x,y,z,\lambda) = \frac{x^2}{4\pi} +\frac{y^2}{16} +\frac{\sqrt{3}}{36} z^2 +\lambda (x + y + z - 2)$

令 $\begin{cases} L_{x}^{\prime} = \frac{x}{2\pi} + \lambda = 0, \\ L_{y}^{\prime} = \frac{y}{8} + \lambda = 0, \\ L_{z}^{\prime} = \frac{\sqrt{3}}{18} z + \lambda = 0, \\ L_{\lambda}^{\prime} = x + y + z - 2 = 0, \end{cases}$ 得 $\left\{ \begin{array}{l} x_0 = \frac{2\pi}{\pi + 4 + 3\sqrt{3}}, \\ y_0 = \frac{8}{\pi + 4 + 3\sqrt{3}}, \\ z_0 = \frac{6\sqrt{3}}{\pi + 4 + 3\sqrt{3}}, \end{array} \right.$ 此时 $f(x_0, y_0, z_0) = \frac{1}{\pi + 4 + 3\sqrt{3}}$

又当 $x + y + z = 2,xyz = 0$ 时， $f(x,y,z)$ 的最小值为 $f\left(0,\frac{8}{4 + 3\sqrt{3}},\frac{6\sqrt{3}}{4 + 3\sqrt{3}}\right) = \frac{1}{4 + 3\sqrt{3}}.$ 所以三个图形的面积之和存在最小值，最小值为 $f(x_0,y_0,z_0) = \frac{1}{\pi + 4 + 3\sqrt{3}}.$

（17）【解】补曲面 $\Sigma_{1}:\left\{ \begin{array}{l}x = 0,\\ 3y^{2} + 3z^{2} = 1, \end{array} \right.$ 取后侧， $\Omega$ 为 $\Sigma$ 与 $\Sigma_{1}$ 所围成的立体.利用高斯公式可得

$$
\begin{array}{l} I = \iint_ {\Sigma + \Sigma_ {1}} x \mathrm {d} y \mathrm {d} z + (y ^ {3} + 2) \mathrm {d} z \mathrm {d} x + z ^ {3} \mathrm {d} x \mathrm {d} y - \iint_ {\Sigma_ {1}} x \mathrm {d} y \mathrm {d} z + (y ^ {3} + 2) \mathrm {d} z \mathrm {d} x + z ^ {3} \mathrm {d} x \mathrm {d} y \\ = \iiint_ {\Omega} (1 + 3 y ^ {2} + 3 z ^ {2}) d x d y d z - 0 = \iiint_ {\Omega} (1 + 3 y ^ {2} + 3 z ^ {2}) d x d y d z \\ \end{array}
$$

利用柱坐标变换 $y = r\cos \theta, z = r\sin \theta, x = x$ 得

$$
\begin{array}{l} \iiint_ {\Omega} (1 + 3 y ^ {2} + 3 z ^ {2}) \mathrm {d} x \mathrm {d} y \mathrm {d} z = \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {\frac {\sqrt {3}}{3}} \mathrm {d} r \int_ {0} ^ {\sqrt {1 - 3 r ^ {2}}} (1 + 3 r ^ {2}) r \mathrm {d} x \\ = 2 \pi \int_ {0} ^ {\frac {\sqrt {3}}{3}} \sqrt {1 - 3 r ^ {2}} (1 + 3 r ^ {2}) r d r = \frac {2 \pi}{3} \int_ {0} ^ {1} (2 - t ^ {2}) t ^ {2} d t = \frac {1 4 \pi}{4 5}. \\ \end{array}
$$

（18）【解】（I）当 $f(x) = x$ 时，方程化为 $y^\prime +y = x$ ，其通解为

$$
y = \mathrm {e} ^ {- x} (C + \int x \mathrm {e} ^ {x} \mathrm {d} x) = \mathrm {e} ^ {- x} (C + x \mathrm {e} ^ {x} - \mathrm {e} ^ {x}) = C \mathrm {e} ^ {- x} + x - 1.
$$

（Ⅱ）方程 $y' + y = f(x)$ 的通解为 $y = \mathrm{e}^{-\int_0^x \mathrm{d}t} \left[ C + \int_0^x \mathrm{e}^{\int_0^t \mathrm{d}s} f(t) \, \mathrm{d}t \right]$ ，

即 $y = \mathrm{e}^{-x}\left[C + \int_0^x\mathrm{e}^t f(t)\mathrm{d}t\right].$

得 $y(x + T) - y(x) = \mathrm{e}^{-x}\left[\left(\frac{1}{\mathrm{e}^T} - 1\right)C + \frac{1}{\mathrm{e}^T}\int_0^{x + T}\mathrm{e}^t f(t)\mathrm{d}t - \int_0^x\mathrm{e}^t f(t)\mathrm{d}t\right]$

若 $f(x)$ 是周期为 $T$ 的连续函数，则

$$
\begin{array}{l} \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {x + T} \mathrm {e} ^ {t} f (t) \mathrm {d} t = \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {T} \mathrm {e} ^ {t} f (t) \mathrm {d} t + \frac {1}{\mathrm {e} ^ {T}} \int_ {T} ^ {x + T} \mathrm {e} ^ {t} f (t) \mathrm {d} t \\ = \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {T} \mathrm {e} ^ {t} f (t) \mathrm {d} t + \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {x} \mathrm {e} ^ {u + T} f (u + T) \mathrm {d} u \\ = \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {T} \mathrm {e} ^ {t} f (t) \mathrm {d} t + \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {x} \mathrm {e} ^ {T} \mathrm {e} ^ {u} f (u) \mathrm {d} u = \frac {1}{\mathrm {e} ^ {T}} \int_ {0} ^ {T} \mathrm {e} ^ {t} f (t) \mathrm {d} t + \int_ {0} ^ {x} \mathrm {e} ^ {s} f (t) \mathrm {d} t \\ \end{array}
$$

于是 $y(x + T) - y(x) = \mathrm{e}^{-x}\left[\left(\frac{1}{\mathrm{e}^T} - 1\right)C + \frac{1}{\mathrm{e}^T}\int_0^T\mathrm{e}^t f(t)\mathrm{d}t\right]$ ,

因此当且仅当 $C = \frac{1}{\mathrm{e}^T - 1}\int_0^T\mathrm{e}^t f(t)\mathrm{d}t$ 时， $y(x + T) - y(x) = 0$ ，即方程存在唯一的以 $T$ 为周期的解.

（19）【证明】因为 $x_{1} \neq 0$ ，所以 $\mathrm{e}^{x_2} = \frac{\mathrm{e}^{x_1} - 1}{x_1}$

由微分中值定理，存在 $\xi \in (0,x_1)$ ，使得 $\frac{\mathrm{e}^{x_1} - 1}{x_1} = \mathrm{e}^{\xi}$ 即 $\mathrm{e}^{x_2} = \mathrm{e}^{\xi}$ ，因此 $0 < x_{2} < x_{1}$

假设 $0 < x_{n + 1} < x_n$ ，则 $\mathrm{e}^{x_{n + 2}} = \frac{\mathrm{e}^{x_{n + 1}} - 1}{x_{n + 1}} = \mathrm{e}^{\eta}(0 < \eta < x_{n + 1})$ ，得 $0 < x_{n + 2} < x_{n + 1}$ 。故 $\{x_n\}$ 是单调减少的数列，且有下界，从而 $\{x_n\}$ 收敛。

设 $\lim_{n\to \infty}x_n = a$ ，在等式 $x_{n}\mathrm{e}^{x_{n + 1}} = \mathrm{e}^{x_{n}} - 1$ 两边取极限，得 $a\mathrm{e}^a = \mathrm{e}^a -1$ ，显然 $a = 0$ 为其解又令 $f(x) = x\mathrm{e}^{x} - \mathrm{e}^{x} + 1$ ，则 $f^{\prime}(x) = x\mathrm{e}^{x}$

当 $x > 0$ 时， $f^{\prime}(x) = x\mathrm{e}^{x} > 0$ ，函数 $f(x)$ 在 $[0, + \infty)$ 上单调增加，

所以 $a = 0$ 是方程 $a\mathrm{e}^a = \mathrm{e}^a -1$ 在 $[0, + \infty)$ 上的唯一解，故 $\lim_{n\to \infty}x_n = 0$

(20)【解】（I） $f(x_{1},x_{2},x_{3}) = (x_{1} - x_{2} + x_{3})^{2} + (x_{2} + x_{3})^{2} + (x_{1} + ax_{3})^{2} = 0$ 的充分必要条件是 $\begin{cases} x_1 - x_2 + x_3 = 0,\\ x_2 + x_3 = 0,\\ x_1 + ax_3 = 0. \end{cases}$ 对齐次线性方程组的系数矩阵作初等行变换得

$$
\boldsymbol {A} = \left(\begin{array}{c c c}1&- 1&1\\0&1&1\\1&0&a\end{array}\right)\rightarrow \left(\begin{array}{c c c}1&- 1&1\\0&1&1\\0&1&a - 1\end{array}\right)\rightarrow \left(\begin{array}{c c c}1&- 1&1\\0&1&1\\0&0&a - 2\end{array}\right),
$$

$a \neq 2$ 时， $f(x_{1},x_{2},x_{3}) = 0$ 只有零解 $x = (x_{1},x_{2},x_{3})^{\mathrm{T}} = (0,0,0)^{\mathrm{T}}$

$a = 2$ 时， $\mathbf{A}\rightarrow \left( \begin{array}{lll}1 & 0 & 2\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right),$

$f(x_{1},x_{2},x_{3}) = 0$ 有非零解 $x = (x_{1},x_{2},x_{3})^{\mathrm{T}} = k(-2, - 1,1)^{\mathrm{T}}$ ，其中 $k\neq 0$

（Ⅱ） $a\neq 2$ 时，令 $\binom{y_1}{y_2}=\binom{1-1}{0}\binom{1}{1}\binom{x_1}{x_2},$

因 $\left| \begin{array}{ccc}1 & -1 & 1\\ 0 & 1 & 1\\ 1 & 0 & a \end{array} \right| = \left| \begin{array}{ccc}1 & -1 & 1\\ 0 & 1 & 1\\ 0 & 0 & a - 2 \end{array} \right| = a - 2\neq 0$ ，则矩阵 $\left( \begin{array}{ccc}1 & -1 & 1\\ 0 & 1 & 1\\ 1 & 0 & a \end{array} \right)$ 可逆，

所以 $f(x_{1},x_{2},x_{3})$ 的规范形为 $f(y_{1},y_{2},y_{3}) = y_{1}^{2} + y_{2}^{2} + y_{3}^{2}$

$a = 2$ 时，

$$
\begin{array}{l} f \left(x _ {1}, x _ {2}, x _ {3}\right) = \left(x _ {1} - x _ {2} + x _ {3}\right) ^ {2} + \left(x _ {2} + x _ {3}\right) ^ {2} + \left(x _ {1} + a x _ {3}\right) ^ {2} \\ = 2 x _ {1} ^ {2} + 2 x _ {2} ^ {2} + 6 x _ {3} ^ {2} - 2 x _ {1} x _ {2} + 6 x _ {1} x _ {3} \\ = 2 \left(x _ {1} - x _ {2} + x _ {3}\right) ^ {2} + \frac {3}{2} x _ {2} ^ {2} + \frac {3}{2} x _ {3} ^ {2} + 3 x _ {2} x _ {3} \\ = 2 \left(x _ {1} - x _ {2} + x _ {3}\right) ^ {2} + \frac {3}{2} \left(x _ {2} + x _ {3}\right) ^ {2} \\ \end{array}
$$

所以 $f(x_{1},x_{2},x_{3})$ 的规范形为 $f(y_{1},y_{2},y_{3}) = y_{1}^{2} + y_{2}^{2}$

（21）【解】（I）显然 $r(\mathbf{A}) = 2$ ，因为初等变换不改变矩阵的秩，所以 $r(\mathbf{B}) = 2$

而 $\pmb {B} = \left( \begin{array}{rrr}1 & a & 2\\ 0 & 1 & 1\\ -1 & 1 & 1 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & a & 2\\ 0 & 1 & 1\\ 0 & a + 1 & 3 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & a & 2\\ 0 & 1 & 1\\ 0 & 0 & 2 - a \end{array} \right),$ 故 $a = 2$

$(\mathrm{II})\mathbf{A} = \left( \begin{array}{lll}1 & 2 & 2\\ 1 & 3 & 0\\ 2 & 7 & -2 \end{array} \right),\mathbf{B} = \left( \begin{array}{lll}1 & 2 & 2\\ 0 & 1 & 1\\ -1 & 1 & 1 \end{array} \right),$

令 $P = (X_{1},X_{2},X_{3})$

由 $(\mathbf{A} \mid \mathbf{B}) = \begin{pmatrix} 1 & 2 & 2 & 1 & 2 & 2 \\ 1 & 3 & 0 & 0 & 1 & 1 \\ 2 & 7 & -2 & -1 & 1 & 1 \end{pmatrix} \rightarrow \begin{pmatrix} 1 & 0 & 6 & 3 & 4 & 4 \\ 0 & 1 & -2 & -1 & -1 & -1 \\ 0 & 0 & 0 & 0 & 0 & 0 \end{pmatrix}$ 得

$$
\mathbf {X} _ {1} = k _ {1} \binom {- 6} {2} + \binom {3} {- 1} = \binom {- 6 k _ {1} + 3} {2 k _ {1} - 1}, \mathbf {X} _ {2} = k _ {2} \binom {- 6} {2} + \binom {4} {- 1} = \binom {- 6 k _ {2} + 4} {2 k _ {2} - 1},
$$

$$
\boldsymbol {X} _ {3} = k _ {3} \binom {- 6} {2} + \binom {4} {- 1} = \binom {- 6 k _ {3} + 4} {2 k _ {3} - 1},
$$

则所求的可逆矩阵为 $P = \left( \begin{array}{ccc} - 6k_{1} + 3 & -6k_{2} + 4 & -6k_{3} + 4\\ 2k_{1} - 1 & 2k_{2} - 1 & 2k_{3} - 1\\ k_{1} & k_{2} & k_{3} \end{array} \right)(k_{1},k_{2},k_{3}$ 为任意常数且 $k_{2}\neq k_{3})$

（22）【解】（I）因为 $E(X) = 0, E(X^2) = 1, E(Y) = \lambda$ ，以及 $X, Y$ 相互独立，故

$$
\operatorname {C o v} (X, Z) = \operatorname {C o v} (X, X Y) = E \left(X ^ {2} Y\right) - E (X) E (X Y) = E \left(X ^ {2}\right) E (Y) - E ^ {2} (X) E (Y) = \lambda .
$$

（Ⅱ）由 $Y$ 服从参数为 $\lambda$ 的泊松分布，即 $P(Y = j) = \frac{\lambda^j}{j!}\mathrm{e}^{-\lambda}(j = 0,1,2,\dots)$ ，于是， $Z$ 的所有可能取值为全体整数。故 $Z$ 的概率分布为

1）当 $k$ 为正整数时，有

$$
P (Z = k) = P (X Y = k) = P (X = 1, Y = k) = P (X = 1) P (Y = k)
$$

$$
= \frac {1}{2} \cdot \frac {\lambda^ {k}}{k !} \mathrm {e} ^ {- \lambda} (k = 1, 2, 3, \dots),
$$

2）当 $k$ 为负整数时，有

$$
\begin{array}{l} P (Z = k) = P (X Y = k) = P (X = - 1, Y = - k) = P (X = - 1) P (Y = - k) \\ = \frac {1}{2} \cdot \frac {\lambda^ {- k}}{(- k) !} \mathrm {e} ^ {- \lambda} (k = - 1, - 2, - 3, \dots), \\ \end{array}
$$

3) 当 $k$ 为0时，有

$$
\begin{array}{l} P (Z = 0) = P (X Y = 0) = P (X = - 1, Y = 0) + P (X = 1) P (Y = 0) = P (X = - 1, Y = 0) \\ = \frac {1}{2} e ^ {- \lambda} + \frac {1}{2} e ^ {- \lambda} = e ^ {- \lambda}. \\ \end{array}
$$

故 $P(Z = k) = \left\{ \begin{array}{ll} \frac{1}{2} \cdot \frac{\lambda^k}{k!} \mathrm{e}^{-\lambda}, & k = 1, 2, 3, \dots \\ \mathrm{e}^{-\lambda}, & k = 0, \\ \frac{1}{2} \cdot \frac{\lambda^{-k}}{(-k)!} \mathrm{e}^{-\lambda}, & k = -1, -2, -3, \dots \end{array} \right.$

（23）【解】（I）似然函数为

$$
L \left(x _ {1}, x _ {2}, \dots , x _ {n}; \sigma\right) = \prod_ {i = 1} ^ {n} f \left(x _ {i}; \sigma\right) = \frac {1}{2 ^ {n} \sigma^ {n}} e ^ {- \frac {1}{\sigma} \sum_ {i = 1} ^ {n} | x _ {i} |}, - \infty <   x _ {i} <   + \infty , i = 1, 2, \dots
$$

于是 $\ln L = -n\ln 2 - n\ln \sigma -\frac{1}{\sigma}\sum_{i = 1}^{n}|x_i|$

令 $\frac{\mathrm{d}\ln L}{\mathrm{d}\sigma} = -\frac{n}{\sigma} + \frac{1}{\sigma^2} \sum_{i=1}^{n} |x_i| = 0$ ，得 $\sigma$ 的最大似然估计量为 $\hat{\sigma} = \frac{1}{n} \sum_{i=1}^{n} |X_i|$ .

$(\mathrm{II})E(\hat{\sigma}) = \frac{1}{n}\sum_{i = 1}^{n}E(|X_i|) = E(|X|) = \int_{-\infty}^{+\infty}|x|\frac{1}{2\sigma}\mathrm{e}^{-\frac{|x|}{\sigma}}\mathrm{d}x = \int_0^{+\infty}\frac{x}{\sigma}\mathrm{e}^{-\frac{x}{\sigma}}\mathrm{d}x$

$$
= - \int_ {0} ^ {+ \infty} x \mathrm {d e} ^ {- \frac {x}{\sigma}} = - x \mathrm {e} ^ {- \frac {x}{\sigma}} \Big | _ {0} ^ {+ \infty} + \int_ {0} ^ {+ \infty} \mathrm {e} ^ {- \frac {x}{\sigma}} \mathrm {d} x = \sigma .
$$

$$
\begin{array}{l} D (\hat {\sigma}) = \frac {1}{n ^ {2}} \sum_ {i = 1} ^ {n} D (| X _ {i} |) = \frac {D (| X |)}{n} = \frac {E [ | X | ^ {2} - E ^ {2} (| X |) ]}{n} \\ = \frac {1}{n} \left(\int_ {- \infty} ^ {+ \infty} | x | ^ {2} \frac {1}{2 \sigma} \mathrm {e} ^ {- \frac {| x |}{\sigma}} \mathrm {d} x - \sigma^ {2}\right) = \frac {1}{n} \left(\int_ {0} ^ {+ \infty} \frac {x ^ {2}}{\sigma} \mathrm {e} ^ {- \frac {x}{\sigma}} \mathrm {d} x - \sigma^ {2}\right) \\ = \frac {1}{n} \left(\int_ {0} ^ {+ \infty} - x ^ {2} \mathrm {d e} ^ {- \frac {x}{\sigma}} - \sigma^ {2}\right) \\ = \frac {1}{n} \left(\int_ {0} ^ {+ \infty} 2 x \mathrm {e} ^ {- \frac {x}{\sigma}} \mathrm {d} x - \sigma^ {2}\right) = \frac {1}{n} (2 \sigma^ {2} - \sigma^ {2}) = \frac {\sigma^ {2}}{n}. \\ \end{array}
$$