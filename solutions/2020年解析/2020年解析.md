# 2020年数学(一）真题解析

# 一、填空题

（1）【答案】 (D).

【解】 当 $x \to 0^{+}$ 时， $\int_{0}^{x} (\mathrm{e}^{t^2} - 1) \, \mathrm{d}t \sim \int_{0}^{x} t^2 \, \mathrm{d}t = \frac{1}{3} x^3$ ；

$$
\begin{array}{l} \int_ {0} ^ {x} \ln (1 + \sqrt {t ^ {3}}) \mathrm {d} t \sim \int_ {0} ^ {x} t ^ {\frac {3}{2}} \mathrm {d} t = \frac {2}{5} x ^ {\frac {5}{2}}; \\ \int_ {0} ^ {\sin x} \sin t ^ {2} \mathrm {d} t \sim \int_ {0} ^ {x} t ^ {2} \mathrm {d} t = \frac {1}{3} x ^ {3}; \\ \int_ {0} ^ {1 - \cos x} \sqrt {\sin^ {3} t} \mathrm {d} t \sim \int_ {0} ^ {\frac {1}{2} x ^ {2}} t ^ {\frac {3}{2}} \mathrm {d} t = \frac {\sqrt {2}}{2 0} x ^ {5}, \\ \end{array}
$$

应选(D).

方法点评：确定变积分限型无穷小的阶数时，通常有如下方法：

（1）洛必达法则，如：

【例1】设 $f(x)$ 连续，且 $f(0) = 0, f'(0) = 4$ ，且 $\int_{0}^{x} t f(x - t) \mathrm{d}t \sim k x^n (x \to 0)$ ，求 $k, n$ .

【解】 $\int_0^x tf(x - t)\mathrm{d}t\stackrel {x - t = u}{=}\int_x^0 (x - u)f(u)(-\mathrm{d}u) = x\int_0^x f(u)\mathrm{d}u - \int_0^x uf(u)\mathrm{d}u,$

由 $\lim_{x\to 0}\frac{\int_0^xf(x - t)\mathrm{d}t}{x^n} = \lim_{x\to 0}\frac{x\int_0^xf(u)\mathrm{d}u - \int_0^xf(u)\mathrm{d}u}{x^n} = \lim_{x\to 0}\frac{\int_0^xf(u)\mathrm{d}u}{nx^{n - 1}} = \lim_{x\to 0}\frac{f(x) - f(0)}{n(n - 1)x^{n - 2}}$

得 $n - 2 = 1$ ，即 $n = 3$

由 $\lim_{x\to 0}\frac{\int_{0}^{x}tf(x - t)\mathrm{d}t}{x^3} = \frac{1}{6}\lim_{x\to 0}\frac{f(x) - f(0)}{x} = \frac{1}{6} f'(0) = \frac{2}{3}$ 得

$$
\int_ {0} ^ {x} t f (x - t) \mathrm {d} t \sim {\frac {2}{3}} x ^ {3}, \text {故} k = {\frac {2}{3}}, n = 3.
$$

（2）等价无穷小，即积分限及表达式用其等价无穷小代替，如：

【例2】设 $\alpha = \int_{0}^{e^x -1}\frac{\sin t^2}{t}\mathrm{d}t\sim ax^b (x\to 0)$ ，求 $a,b$

【解】 由 $\alpha = \int_{0}^{\mathrm{e}^{x^2} - 1}\frac{\sin t^2}{t}\mathrm{d}t\sim \int_{0}^{x^2}\frac{t^2}{t}\mathrm{d}t = \int_{0}^{x^2}t\mathrm{d}t = \frac{1}{2} x^4$ 得

$$
a = \frac {1}{2}, b = 4.
$$

（2）【答案】 (C).

方法一

若 $f(x)$ 在 $x = 0$ 处可导，则 $f(x)$ 在 $x = 0$ 处连续，由 $\lim_{x\to 0}f(x) = 0$ 得 $f(0) = 0$

因为 $\lim_{x\to 0}\frac{f(x) - f(0)}{x - 0} = \lim_{x\to 0}\frac{f(x)}{x}$ 存在，所以 $f(x)$ 为 $x$ 的同阶或高阶无穷小，故

$\lim_{x \to 0} \frac{f(x)}{\sqrt{|x|}} = 0$ ，应选（C）.

方法二

取 $f(x) = |x|$ ，显然 $\lim_{x\to 0}\frac{f(x)}{\sqrt{|x|}} = 0$ ，但 $f(x)$ 在 $x = 0$ 处不可导，（A）不对；

取 $f(x) = \begin{cases} 2, & x = 0, \\ x^2, & x \neq 0, \end{cases}$ 显然 $f(x)$ 在 $(-1,1)$ 内有定义且 $\lim_{x \to 0} f(x) = 0$ ，显然 $\lim_{x \to 0} \frac{f(x)}{x^2} = 0$ ，但 $f(x)$ 在 $x = 0$ 处不连续，从而 $f(x)$ 在 $x = 0$ 处不可导，(B) 不对；

取 $f(x) = 2x$ ，显然 $f(x)$ 在 $x = 0$ 处可导，但 $\lim_{x\to 0}\frac{f(x)}{x^2}$ 不存在，（D）不对，应选(C).

（3）【答案】 （A）.

【解】 因为 $f(x,y)$ 在 $(0,0)$ 处可微，

所以 $\Delta z = f(x,y) - f(0,0) = f(x,y) = \frac{\partial f}{\partial x} x + \frac{\partial f}{\partial y} y + o(\sqrt{x^2 + y^2})$

于是 $\frac{\partial f}{\partial x}x + \frac{\partial f}{\partial y}y - f(x,y) = o(\sqrt{x^2 + y^2})$ ，即 $\pmb{n} \cdot (x,y,f(x,y)) = o(\sqrt{x^2 + y^2})$

故 $\lim_{(x,y)\to (0,0)}\frac{|n\bullet(x,y,f(x,y))|}{\sqrt{x^2 + y^2}}$ 存在，应选(A).

（4）【答案】 （A）.

【解】因为幂级数 $\sum_{n=1}^{\infty} a_n x^n$ 的收敛半径为 $R$ , 所以当 $|x| < R$ 时, 级数绝对收敛, 进而, 级数 $\sum_{n=1}^{\infty} a_{2n} r^{2n}$ 收敛, 所以, 当 $\sum_{n=1}^{\infty} a_{2n} r^{2n}$ 发散时, $|r| \geqslant R$ , 应选(A).

（5）【答案】 （B）.

【解】矩阵 $\mathbf{A}$ 经过初等列变换得到 $\pmb{B}$ ，故存在初等矩阵 $P_{i}(i = 1,2\dots ,t)$ 使

$$
\boldsymbol {A} \boldsymbol {P} _ {1} \boldsymbol {P} _ {2} \dots \boldsymbol {P} _ {t} = \boldsymbol {B},
$$

因 $P_{i}$ 均可逆，故有 $\mathbf{A} = \mathbf{B}_{t}^{-1}\dots \mathbf{P}_{2}^{-1}\mathbf{P}_{1}^{-1}$ ，记 $\pmb {P} = \pmb {P}_t^{-1}\dots \pmb {P}_2^{-1}\pmb {P}_1^{-1}$ ，故应选(B).

方法点评：矩阵进行一次初等行变换或一次初等列变换等价于矩阵的左边乘以一个初等矩阵或右边乘以一个初等矩阵；矩阵进行若干次初等行变换等价于矩阵左乘可逆矩阵，矩阵进行若干次初等列变换等价于矩阵右乘可逆矩阵，故有如下结论：

（1）设 $A, B$ 为同型矩阵，则 $A$ 经过有限次初等行变换化为 $B$ 等价于存在可逆矩阵 $M$ ，使得 $B = MA$ ；  
（2）设 $A, B$ 为同型矩阵，则 $A$ 经过有限次初等列变换化为 $B$ 等价于存在可逆矩阵 $N$ ，使得 $B = AN$ ；  
（3）设 $A, B$ 为同型矩阵，则 $A$ 经过有限次初等变换化为 $B$ 等价于存在可逆矩阵 $P, Q$ ，使得 $B = P A Q$ .

（6）【答案】 (C).

【解】令 $L_{1}: \frac{x - a_{2}}{a_{1}} = \frac{y - b_{2}}{b_{1}} = \frac{z - c_{2}}{c_{1}} = t$ 得 $L_{1}: \left\{ \begin{array}{l} x = a_{2} + a_{1}t, \\ y = b_{2} + b_{1}t, \\ z = c_{2} + c_{1}t, \end{array} \right.$ 即 $L_{1}: \binom{x}{y}=x_{2}+t\alpha_{1}$ ,

同理 $L_{2}:\left( \begin{array}{c}x\\ y\\ z \end{array} \right) = \pmb{\alpha}_{3} + t\pmb{\alpha}_{2},$

因为 $L_{1}$ 与 $L_{2}$ 相交，故存在 $t$ ，使得 $\alpha_{2} + t\alpha_{1} = \alpha_{3} + t\alpha_{2}$ ，即 $\alpha_{3} = t\alpha_{1} + (1 - t)\alpha_{2}$ 故 $\alpha_{3}$ 可由 $\alpha_{1},\alpha_{2}$ 线性表示，应选(C).

（7）【答案】 (D).

【解】 $P(A\overline{B}\overline{C}) = P(A\cdot \overline{B + C}) = P(A) - P(AB + AC)$

$$
= P (A) - P (A B) - P (A C) + P (A B C) = \frac {1}{4} - \frac {1}{1 2} = \frac {1}{6},
$$

$$
\begin{array}{l} P (\bar {A} B \bar {C}) = P (B \cdot \bar {A + C}) = P (B) - P (A B + B C) \\ = P (B) - P (A B) - P (B C) + P (A B C) = \frac {1}{4} - \frac {1}{1 2} = \frac {1}{6}, \\ \end{array}
$$

$$
\begin{array}{l} P (\bar {A} \bar {B} C) = P (C \cdot \bar {A + B}) = P (C) - P (A C + B C) \\ = P (C) - P (A C) - P (B C) + P (A B C) = \frac {1}{4} - \frac {2}{1 2} = \frac {1}{1 2}, \\ \end{array}
$$

故所求概率为 $P(A\overline{B}\overline{C}) + P(\overline{A} BC) + P(\overline{ABC}) = \frac{1}{6} +\frac{1}{6} +\frac{1}{12} = \frac{5}{12}$ ，应选(D).

（8）【答案】 (B).

【解】 $E(X) = \frac{1}{2}, E(X^2) = \frac{1}{2}$ ，则 $D(X) = E(X^2) - [E(X)]^2 = \frac{1}{4}$ .

由中心极限定理得 $\sum_{i = 1}^{100}X_{i}$ 近似服从 $N(50,25)$

从而 $\frac{\sum_{i=1}^{100} X_i - 50}{5}$ 近似服从 $N(0,1)$ ，故

$$
P \left\{\sum_ {i = 1} ^ {1 0 0} X _ {i} \leqslant 5 5 \right\} = P \left\{\frac {\sum_ {i = 1} ^ {1 0 0} X _ {i} - 5 0}{5} \leqslant 1 \right\} \approx \Phi (1), \text {应 选 (B)}.
$$

# 二、填空题

（9）【答案】 -1.

【解】 $\lim_{x\to 0}\left[\frac{1}{\mathrm{e}^x - 1} -\frac{1}{\ln(1 + x)}\right] = \lim_{x\to 0}\frac{\ln(1 + x) - \mathrm{e}^x + 1}{x^2}$

$$
\begin{array}{l} = \lim  _ {x \rightarrow 0} \frac {\frac {1}{1 + x} - e ^ {x}}{2 x} = \frac {1}{2} \lim  _ {x \rightarrow 0} \frac {1}{1 + x} \cdot \frac {1 - (x + 1) e ^ {x}}{x} = \frac {1}{2} \lim  _ {x \rightarrow 0} \frac {1 - (x + 1) e ^ {x}}{x} \\ = - \frac {1}{2} \lim  _ {x \rightarrow 0} (x + 2) e ^ {x} = - 1. \\ \end{array}
$$

（10）【答案】 $-\sqrt{2}$

【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\frac{1}{\sqrt{t^2 + 1}}}{\frac{t}{\sqrt{t^2 + 1}}} = \frac{1}{t},$

$$
\frac {\mathrm {d} ^ {2} y}{\mathrm {d} x ^ {2}} = \frac {\mathrm {d} \left(\frac {1}{t}\right) / \mathrm {d} t}{\mathrm {d} x / \mathrm {d} t} = \frac {- \frac {1}{t ^ {2}}}{\frac {t}{\sqrt {t ^ {2} + 1}}} = - \frac {\sqrt {t ^ {2} + 1}}{t ^ {3}},
$$

故 $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\bigg|_{t = 1} = -\sqrt{2}.$

(11)【答案】 $n + am$

【解】由 $f^{\prime \prime}(x) + af^{\prime}(x) + f(x) = 0$ 得特征方程为

$$
\lambda^ {2} + a \lambda + 1 = 0,
$$

因为 $\lambda_1 + \lambda_2 = -a < 0, \lambda_1\lambda_2 = 1 > 0$ ，所以 $\lambda_1 < 0, \lambda_2 < 0$

于是 $f(x) = C_{1}\mathrm{e}^{\lambda_{1}x} + C_{2}\mathrm{e}^{\lambda_{2}x},f^{\prime}(x) = C_{1}\lambda_{1}\mathrm{e}^{\lambda_{1}x} + C_{2}\lambda_{2}\mathrm{e}^{\lambda_{2}x},$

显然 $\lim_{x\to +\infty}f(x) = \lim_{x\to +\infty}f'(x) = 0,$

故 $\int_0^{+\infty}f(x)\mathrm{d}x = -\int_0^{+\infty}\left[f^{\prime \prime}(x) + af^{\prime}(x)\right]\mathrm{d}x = -f^{\prime}(x)\mid_{0}^{+\infty} - af(x)\mid_{0}^{+\infty} = n + am.$

(12)【答案】 4e.

【解】 $f(x,y) = \int_{0}^{xy}\mathrm{e}^{xt^2}\mathrm{d}t = \frac{1}{\sqrt{x}}\int_{0}^{xy}\mathrm{e}^{(\sqrt{x} t)^2}\mathrm{d}(\sqrt{x} t) = \frac{1}{\sqrt{x}}\int_{0}^{x^{\frac{3}{2} y}}\mathrm{e}^{t^2}\mathrm{d}t,$

$$
\frac {\partial f}{\partial x} = \frac {3}{2} y \mathrm {e} ^ {x ^ {3} y ^ {2}} - \frac {\int_ {0} ^ {x ^ {\frac {3}{2}} y} \mathrm {e} ^ {t ^ {2}} \mathrm {d} t}{2 x ^ {\frac {3}{2}}}, \quad \frac {\partial^ {2} f}{\partial x \partial y} = \frac {3}{2} \mathrm {e} ^ {x ^ {3} y ^ {2}} + 3 x ^ {3} y ^ {2} \mathrm {e} ^ {x ^ {3} y ^ {2}} - \frac {1}{2} \mathrm {e} ^ {x ^ {3} y ^ {2}},
$$

故 $\left.\frac{\partial^2f}{\partial x\partial y}\right|_{(1,1)} = 4\mathrm{e}.$

（13）【答案】 $a^4 - 4a^2$

【解】 $\left| \begin{array}{cccc}a & 0 & -1 & 1\\ 0 & a & 1 & -1\\ -1 & 1 & a & 0\\ 1 & -1 & 0 & a \end{array} \right| = -\left| \begin{array}{cccc}1 & 0 & -1 & a\\ -1 & a & 1 & 0\\ 0 & 1 & a & -1\\ a & -1 & 0 & 1 \end{array} \right| = -\left| \begin{array}{cccc}1 & 0 & -1 & a\\ 0 & a & 0 & a\\ 0 & 1 & a & -1\\ 0 & -1 & a & 1 - a^2 \end{array} \right|$

$$
\begin{array}{l} = - \left| \begin{array}{c c c} a & 0 & a \\ 1 & a & - 1 \\ - 1 & a & 1 - a ^ {2} \end{array} \right| = - a \left| \begin{array}{c c c} 1 & 0 & 1 \\ 1 & a & - 1 \\ - 1 & a & 1 - a ^ {2} \end{array} \right| \\ = - a \left| \begin{array}{c c c} 1 & 0 & 1 \\ 0 & a & - 2 \\ 0 & a & 2 - a ^ {2} \end{array} \right| = - 4 a ^ {2} + a ^ {4}. \\ \end{array}
$$

(14)【答案】 $\frac{2}{\pi}$ .

【解】 $X$ 的概率密度为

$$
f (x) = \left\{ \begin{array}{l l} \frac {1}{\pi}, & - \frac {\pi}{2} <   x <   \frac {\pi}{2}, \\ 0, & \text {其 他}, \end{array} \right.
$$

$$
E (X) = 0,
$$

$$
\begin{array}{l} E (X Y) = E (X \sin X) = \frac {1}{\pi} \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} x \sin x d x = - \frac {2}{\pi} \int_ {0} ^ {\frac {\pi}{2}} x d (\cos x) \\ = - \frac {2}{\pi} \left(x \cos x \left| _ {0} ^ {\frac {\pi}{2}} - \int_ {0} ^ {\frac {\pi}{2}} \cos x d x \right.\right) = \frac {2}{\pi}, \\ \end{array}
$$

故 $\operatorname{Cov}(X, Y) = E(XY) - E(X)E(Y) = E(XY) = \frac{2}{\pi}$ .

# 三、解答题

(15)【解】 由 $\left\{ \begin{array}{l}3x^{2} - y = 0,\\ 24y^{2} - x = 0 \end{array} \right.$ 得 $\left\{ \begin{array}{l}x = 0,\\ y = 0, \end{array} \right.$ $\left\{ \begin{array}{l}x = \frac{1}{6},\\ y = \frac{1}{12}; \end{array} \right.$

$$
\frac {\partial^ {2} f}{\partial x ^ {2}} = 6 x, \quad \frac {\partial^ {2} f}{\partial x \partial y} = - 1, \quad \frac {\partial^ {2} f}{\partial y ^ {2}} = 4 8 y,
$$

当 $(x,y) = (0,0)$ 时， $A = 0,B = -1,C = 0$

因为 $AC - B^2 < 0$ ，所以点 $(0,0)$ 不是函数 $f(x,y)$ 的极值点；

当 $(x,y) = \left(\frac{1}{6},\frac{1}{12}\right)$ 时， $A = 1,B = -1,C = 4$

因为 $AC - B^2 = 3 > 0$ 且 $A > 0$ ，所以点 $\left(\frac{1}{6},\frac{1}{12}\right)$ 为函数 $f(x,y)$ 的极小值点，极小值为

$$
f \left(\frac {1}{6}, \frac {1}{1 2}\right) = \frac {1}{6 ^ {3}} + 8 \times \frac {1}{1 2 ^ {3}} - \frac {1}{6} \times \frac {1}{1 2} = - \frac {1}{2 1 6}.
$$

(16)【解】 $P(x,y) = \frac{4x - y}{4x^2 + y^2},\quad Q(x,y) = \frac{x + y}{4x^2 + y^2},$

$$
\begin{array}{l} \frac {\partial Q}{\partial x} = \frac {- 4 x ^ {2} + y ^ {2} - 8 x y}{(4 x ^ {2} + y ^ {2}) ^ {2}}, \quad \frac {\partial P}{\partial y} = \frac {- 4 x ^ {2} + y ^ {2} - 8 x y}{(4 x ^ {2} + y ^ {2}) ^ {2}}, \\ \frac {\partial Q}{\partial x} = \frac {\partial P}{\partial y} ((x, y) \neq (0, 0)). \\ \end{array}
$$

取 $L_{0}:4x^{2} + y^{2} = r^{2}(r > 0,L_{0}$ 在 $L$ 内，逆时针)，且设 $L$ 与 $L_0^-$ 所围成的区域为 $D_{1},L_{0}$ 围成的区域为 $D_{2}$ ，

由 $\oint_{L + L_0^-}P\mathrm{d}x + Q\mathrm{d}y = \iint_{D_1}0\mathrm{d}x\mathrm{d}y = 0$ 得

$$
\begin{array}{l} I = \int_ {L} \frac {4 x - y}{4 x ^ {2} + y ^ {2}} d x + \frac {x + y}{4 x ^ {2} + y ^ {2}} d y = \oint_ {L _ {0}} \frac {4 x - y}{4 x ^ {2} + y ^ {2}} d x + \frac {x + y}{4 x ^ {2} + y ^ {2}} d y \\ = \frac {1}{r ^ {2}} \oint_ {L _ {0}} (4 x - y) d x + (x + y) d y = \frac {2}{r ^ {2}} \iint_ {D _ {2}} d x d y = \frac {2}{r ^ {2}} \times \pi \times r \times \frac {r}{2} = \pi . \\ \end{array}
$$

(17)【解】由 $(n + 1)a_{n + 1} = \left(n + \frac{1}{2}\right)a_n$ 得 $\frac{a_{n + 1}}{a_n} = \frac{n + \frac{1}{2}}{n + 1},$

从而 $\lim_{n\to \infty}\frac{a_{n + 1}}{a_n} = 1$ ，即幂级数 $\sum_{n = 1}^{\infty}a_{n}x^{n}$ 的收敛半径为 $R = 1$

故当 $|x| < 1$ 时，幂级数 $\sum_{n=1}^{\infty} a_n x^n$ 收敛.

令 $S(x) = \sum_{n=1}^{\infty} a_n x^n$ ，则

$$
\begin{array}{l} S ^ {\prime} (x) = 1 + \sum_ {n = 1} ^ {\infty} (n + 1) a _ {n + 1} x ^ {n} = 1 + \sum_ {n = 1} ^ {\infty} \left(n + \frac {1}{2}\right) a _ {n} x ^ {n} \\ = 1 + x \sum_ {n = 1} ^ {\infty} n a _ {n} x ^ {n - 1} + \frac {1}{2} \sum_ {n = 1} ^ {\infty} a _ {n} x ^ {n} = 1 + x S ^ {\prime} (x) + \frac {1}{2} S (x), \\ \end{array}
$$

即 $S^{\prime}(x) - \frac{1}{2(1 - x)} S(x) = \frac{1}{1 - x}$ ，解得

$$
S (x) = (- 2 \sqrt {1 - x} + C) \frac {1}{\sqrt {1 - x}} = \frac {C}{\sqrt {1 - x}} - 2,
$$

由 $S(0) = 0$ 得 $C = 2$ ，故 $S(x) = \frac{2}{\sqrt{1 - x}} - 2.$

(18)【解】因为 $\Sigma$ 的法向量为 $(x, y, -z)$ ，所以

$$
\begin{array}{l} I = \iint_ {\Sigma} \frac {1}{\sqrt {2 (x ^ {2} + y ^ {2})}} \left[ \left(x ^ {2} + y ^ {2} - z ^ {2}\right) f (x y) + 2 x ^ {2} + 2 y ^ {2} - z ^ {2} \right] d S \\ = \frac {\sqrt {2}}{2} \iint_ {\Sigma} \sqrt {x ^ {2} + y ^ {2}} d S. \\ \end{array}
$$

记 $D = \{(x,y)\mid 1\leqslant x^2 +y^2\leqslant 4\}$ ，又

$$
\sqrt {\left(\frac {\partial z}{\partial x}\right) ^ {2} + \left(\frac {\partial z}{\partial y}\right) ^ {2} + 1} = \sqrt {\left(\frac {x}{\sqrt {x ^ {2} + y ^ {2}}}\right) ^ {2} + \left(\frac {y}{\sqrt {x ^ {2} + y ^ {2}}}\right) ^ {2} + 1} = \sqrt {2}.
$$

故

$$
\begin{array}{l} I = \iint_ {D} \sqrt {x ^ {2} + y ^ {2}} d x d y \\ = \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {1} ^ {2} r ^ {2} \mathrm {d} r \\ = \frac {1 4}{3} \pi . \\ \end{array}
$$

(19)【证明】（I）令 $M = \max_{x\in [0,2]}\left|f(x)\right| = \left|f(c)\right|$ ，其中 $c\in [0,2]$

由拉格朗日中值定理，存在 $\xi_1\in (0,c),\xi_2\in (c,2)$ ，使得

$$
\begin{array}{l} f (c) - f (0) = f ^ {\prime} \left(\xi_ {1}\right) c, \\ f (2) - f (c) = f ^ {\prime} (\xi_ {2}) (2 - c), \\ \end{array}
$$

则 $\left|f^{\prime}(\xi_{1})\right|c = M,\left|f^{\prime}(\xi_{2})\right|(2 - c) = M,$

当 $c\in (0,1]$ 时，由 $\left|f^{\prime}(\xi_{1})\right|c = M$ 得 $\left|f^{\prime}(\xi_1)\right|\geqslant M$ ，取 $\xi = \xi_{1}$

当 $c \in [1,2)$ 时， $2 - c \in (0,1]$ ，由 $\left|f'(\xi_2)\right|(2 - c) = M$ 得 $\left|f'(\xi_2)\right| \geqslant M$ ，取 $\xi = \xi_2$ 则存在 $\xi \in (0,2)$ ，使 $\left|f'(\xi)\right| \geqslant M$ .

（Ⅱ）（反证法）不妨设 $M > 0$ ，则 $c\in (0,2)$ ，当 $c\neq 1$ 时，由拉格朗日中值定理，存在 $\xi_1\in (0,c),\xi_2\in (c,2)$ ，使得

$$
\begin{array}{l} f (c) = f (c) - f (0) = f ^ {\prime} (\xi_ {1}) c \text {, 其 中} 0 <   \xi_ {1} <   c \\ - f (c) = f (2) - f (c) = f ^ {\prime} \left(\xi_ {2}\right) (2 - c), \text {其 中} c <   \xi_ {2} <   2, \\ \end{array}
$$

则 $M = |f(c)| = |f'(\xi_1)|c\leqslant Mc,M = |f(c)| = |f'(\xi_2)|(2 - c)\leqslant M(2 - c)$ 皆成立，

若 $0 < c < 1$ ，显然 $M = |f(c)| = |f'(\xi_1)|c \leqslant Mc$ 不对；

若 $1 < c < 2$ ，显然 $M = |f(c)| = |f'(\xi_2)|(2 - c) \leqslant M(2 - c)$ 不对，

即上述式子至少有一个不成立，矛盾，故 $M = 0$

当 $c = 1$ 时，此时 $\mid f(1)\mid = M$ ，易知 $f^{\prime}(1) = 0$

若 $f(1) = M$ ，设 $G(x) = f(x) - Mx,0\leqslant x\leqslant 1,G^{\prime}(x) = f^{\prime}(x) - M\leqslant 0,$

从而 $G(x)$ 单调递减又 $G(0) = G(1) = 0$ ，从而 $G(x) = 0$ ，即 $f(x) = Mx, 0 \leqslant x \leqslant 1.$

因此， $f^{\prime}(1) = M$ ，从而 $M = 0$ ；同理，当 $f(1) = -M$ 时， $M = 0$ 综上， $M = 0$

(20)【解】（I）令 $\mathbf{A} = \begin{pmatrix} 1 & -2 \\ -2 & 4 \end{pmatrix}, \mathbf{X} = \begin{pmatrix} x_1 \\ x_2 \end{pmatrix}$ ，则 $f(x_{1},x_{2}) = X^{\mathrm{T}}AX$

$$
| \lambda \pmb {E} - \pmb {A} | = \left| \begin{array}{c c} \lambda - 1 & 2 \\ 2 & \lambda - 4 \end{array} \right| = \lambda (\lambda - 5) = 0,
$$

解得 $\mathbf{A}$ 的特征值为 $\lambda_1 = 0, \lambda_2 = 5$

令 $\pmb {B} = \left( \begin{array}{ll}a & 2\\ 2 & b \end{array} \right),\pmb {Y} = \left( \begin{array}{l}y_1\\ y_2 \end{array} \right)$ 则 $g(y_{1},y_{2}) = Y^{\mathrm{T}}BY$

因为 $\mathbf{A}\sim \mathbf{B}$ ，所以 $\left\{ \begin{array}{l}\operatorname {tr}\mathbf{A} = \operatorname {tr}\mathbf{B},\\ |\mathbf{A}| = |\mathbf{B}|, \end{array} \right.$ 即 $\left\{ \begin{array}{ll}a + b = 5,\\ ab = 4, \end{array} \right.$ 解得 $a = 4,b = 1$

（Ⅱ）由 $0E - A = \binom{-1}{2}\rightarrow \binom{1}{0}$ 得

矩阵 $\mathbf{A}$ 的属于 $\lambda_{1} = 0$ 的特征向量 $\alpha_{1} = \binom{2}{1}$

由 $5\pmb {E} - \pmb {A} = \binom{4}{2}\rightarrow \binom{1}{0}\frac{1}{2}$ 得

矩阵 $\mathbf{A}$ 的属于 $\lambda_{2} = 5$ 的特征向量 $\pmb{\alpha}_{2} = \left( \begin{array}{c} - 1\\ 2 \end{array} \right)$

令 $Q_{1} = \frac{1}{\sqrt{5}}\binom{2}{1}\binom{-1}{2}$ ，则 $Q_{1}^{\mathrm{T}}AQ_{1} = \binom{0}{0}$

由 $0\pmb {E} - \pmb {B} = \left( \begin{array}{ll} - 4 & -2\\ -2 & -1 \end{array} \right)\rightarrow \left( \begin{array}{ll}1 & \frac{1}{2}\\ 0 & 0 \end{array} \right)$ 得

矩阵 $\pmb{B}$ 的属于 $\lambda_{1} = 0$ 的特征向量 $\pmb{\beta}_{1} = \left( \begin{array}{c} - 1\\ 2 \end{array} \right)$

由 $5\pmb {E} - \pmb {B} = \binom{1}{-2}\rightarrow \binom{1}{0}$ 得

矩阵 $\pmb{B}$ 的属于 $\lambda_{2} = 5$ 的特征向量 $\pmb{\beta}_{2} = \binom{2}{1}$

令 $Q_{2} = \frac{1}{\sqrt{5}}\left( \begin{array}{cc} - 1 & 2\\ 2 & 1 \end{array} \right)$ 则 $Q_{2}^{\mathrm{T}}BQ_{2} = \binom {0}{0},$

由 $Q_{1}^{T}AQ_{1} = Q_{2}^{T}BQ_{2}$ 得 $\pmb {B} = \pmb {Q}_2\pmb {Q}_1^{\mathrm{T}}\pmb {A}\pmb {Q}_1\pmb {Q}_2^{\mathrm{T}}$

所求的正交矩阵为 $Q = Q_{1}Q_{2}^{\mathrm{T}} = \frac{1}{\sqrt{5}}\binom{2}{1}\cdot \frac{1}{\sqrt{5}}\binom{-1}{2}\cdot \binom{2}{1} = \frac{1}{5}\binom{-4}{3}\cdot \binom{3}{4}.$

（21）【解】（I）方法一

（反证法）设 $P$ 不可逆，则 $\alpha, A\alpha$ 线性相关，即 $\alpha, A\alpha$ 成比例，

于是 $\alpha = kA\alpha$ 或 $A\alpha = l\alpha$

因为 $\alpha$ 不是 $A$ 的特征向量，所以 $A\alpha = l\alpha$ 不可能；

若 $\alpha = kA\alpha$ ，因为 $\pmb{\alpha}$ 为非零向量，所以 $k\neq 0$ ，于是 $A\alpha = \frac{1}{k}\alpha$ ，矛盾，

故 $\alpha, A\alpha$ 线性无关，即 $P$ 可逆

方法二

（反证法）设 $P$ 不可逆，即 $\alpha, A\alpha$ 线性相关，则存在不全为零的常数 $k_{1}, k_{2}$ ，使得

$$
k _ {1} \boldsymbol {\alpha} + k _ {2} \boldsymbol {A} \boldsymbol {\alpha} = \mathbf {0},
$$

显然 $k_{2} \neq 0$ ，因为若 $k_{2} = 0$ ，则 $k_{1}\pmb{\alpha} = \mathbf{0}$ ，由 $\pmb{\alpha} \neq \mathbf{0}$ 得 $k_{1} = 0$ ，矛盾，故 $k_{2} \neq 0$

由 $k_{1}\pmb {\alpha} + k_{2}\pmb {A}\pmb {\alpha} = \pmb{0}$ 得 $A\pmb {\alpha} = -\frac{k_1}{k_2}\pmb {\alpha}$ ，矛盾，故 $\pmb{P}$ 可逆.

（Ⅱ）由 $\mathbf{A}\mathbf{P} = \mathbf{A}(\pmb{\alpha},\mathbf{A}\pmb{\alpha}) = (\mathbf{A}\pmb{\alpha},\mathbf{A}^2\pmb{\alpha}) = (\mathbf{A}\pmb{\alpha},6\pmb{\alpha} - \mathbf{A}\pmb{\alpha}) = \mathbf{P}\left( \begin{array}{cc}0 & 6\\ 1 & -1 \end{array} \right)$ 得

$$
\boldsymbol {P} ^ {- 1} \boldsymbol {A} \boldsymbol {P} = \left( \begin{array}{c c} 0 & 6 \\ 1 & - 1 \end{array} \right).
$$

设 $\mathbf{B} = \begin{pmatrix} 0 & 6 \\ 1 & -1 \end{pmatrix}$ , 则 $\mathbf{A} \sim \mathbf{B}$ .

由 $|\lambda \pmb {E} - \pmb {B}| = \left| \begin{array}{cc}\lambda & -6\\ -1 & 1 + \lambda \end{array} \right| = (\lambda +3)(\lambda -2) = 0.$

得 $\lambda_{1} = -3, \lambda_{2} = 2$ ，因为 $\lambda_{1} \neq \lambda_{2}$ ，所以 $\pmb{B}$ 可以相似对角化，则 $\mathbf{A}$ 也可以相似对角化.（22）【解】（I）二维随机变量 $(X_{1}, Y)$ 的分布函数为

$$
\begin{array}{l} F (x, y) = P \left\{X _ {1} \leqslant x, Y \leqslant y \right\} \\ = \frac {1}{2} P \left\{X _ {1} \leqslant x, Y \leqslant y \mid X _ {3} = 0 \right\} + \frac {1}{2} P \left\{X _ {1} \leqslant x, Y \leqslant y \mid X _ {3} = 1 \right\} \\ = \frac {1}{2} P \left\{X _ {1} \leqslant x, X _ {2} \leqslant y \right\} + \frac {1}{2} P \left\{X _ {1} \leqslant x, X _ {1} \leqslant y \right\} \\ = \frac {1}{2} P \left\{X _ {1} \leqslant x \right\} P \left\{X _ {2} \leqslant y \right\} + \frac {1}{2} P \left\{X _ {1} \leqslant x, X _ {1} \leqslant y \right\}, \\ \end{array}
$$

当 $x < y$ 时，

$$
F (x, y) = \frac {1}{2} \Phi (x) \Phi (y) + \frac {1}{2} \Phi (x);
$$

当 $x \geqslant y$ 时，同理可得

$$
F (x, y) = \frac {1}{2} \Phi (x) \Phi (y) + \frac {1}{2} \Phi (y),
$$

即 $F(x,y) = \left\{ \begin{array}{ll} \frac{1}{2}\Phi (x)\Phi (y) + \frac{1}{2}\Phi (x), & x < y,\\  \frac{1}{2}\Phi (x)\Phi (y) + \frac{1}{2}\Phi (y), & x\geqslant y. \end{array} \right.$

（Ⅱ）Y的分布函数为

$$
\begin{array}{l} F _ {Y} (y) = P \left\{Y \leqslant y \right\} = \frac {1}{2} P \left\{Y \leqslant y \mid X _ {3} = 0 \right\} + \frac {1}{2} P \left\{Y \leqslant y \mid X _ {3} = 1 \right\} \\ = \frac {1}{2} P \left\{X _ {2} \leqslant y \right\} + \frac {1}{2} P \left\{X _ {1} \leqslant y \right\} = \frac {1}{2} \Phi (y) + \frac {1}{2} \Phi (y) = \Phi (y), \\ \end{array}
$$

则 $Y\sim N(0,1)$

(23)【解】（I） $P\{T > t\} = 1 - P\{T \leqslant t\} = 1 - F(t) = \mathrm{e}^{-\left(\frac{t}{\theta}\right)^m}$ ;

$$
\begin{array}{l} P \{T > s + t \mid T > s \} = \frac {P \{T > s , T > s + t \}}{P \{T > s \}} = \frac {P \{T > s + t \}}{P \{T > s \}} \\ = \frac {1 - P \{T \leqslant s + t \}}{1 - P \{T \leqslant s \}} = \frac {\mathrm {e} ^ {- \left(\frac {s + t}{\theta}\right) ^ {m}}}{\mathrm {e} ^ {- \left(\frac {s}{\theta}\right) ^ {m}}} = \mathrm {e} ^ {\left(\frac {s}{\theta}\right) ^ {m} - \left(\frac {s + t}{\theta}\right) ^ {m}}. \\ \end{array}
$$

（Ⅱ） $T$ 的概率密度为

$L(\theta) = f(t_{1})f(t_{2})\dots f(t_{n}) = m^{n}\theta^{-mn}(t_{1}t_{2}\dots t_{n})^{m - 1}\mathrm{e}^{-\theta^{-m}\sum_{i = 1}^{n}t_{i}^{m}}$ ，其中 $t_1 > 0,t_2 > 0,\dots ,t_n > 0$

$$
\ln L (\theta) = n \ln m - m n \ln \theta + (m - 1) \sum_ {i = 1} ^ {n} \ln t _ {i} - \theta^ {- m} \sum_ {i = 1} ^ {n} t _ {i} ^ {m},
$$

令 $\frac{\mathrm{d}}{\mathrm{d}\theta}\ln L(\theta) = -\frac{mn}{\theta} +m\theta^{-(m + 1)}\sum_{i = 1}^{n}t_i^m = 0$ 得

故 $\theta$ 的最大似然估计值为 $\hat{\theta} = \sqrt[m]{\frac{1}{n}\sum_{i=1}^{n}t_i^m}$ .

$$
\begin{array}{l} F _ {Y} (y) = P \left\{Y \leqslant y \right\} = \frac {1}{2} P \left\{Y \leqslant y \mid X _ {3} = 0 \right\} + \frac {1}{2} P \left\{Y \leqslant y \mid X _ {3} = 1 \right\} \\ = \frac {1}{2} P \left\{X _ {2} \leqslant y \right\} + \frac {1}{2} P \left\{X _ {1} \leqslant y \right\} = \frac {1}{2} \Phi (y) + \frac {1}{2} \Phi (y) = \Phi (y), \\ P \{T > s + t \mid T > s \} = \frac {P \{T > s , T > s + t \}}{P \{T > s \}} = \frac {P \{T > s + t \}}{P \{T > s \}} \\ = \frac {1 - P \{T \leqslant s + t \}}{1 - P \{T \leqslant s \}} = \frac {\mathrm {e} ^ {- \left(\frac {s + t}{\theta}\right) ^ {m}}}{\mathrm {e} ^ {- \left(\frac {s}{\theta}\right) ^ {m}}} = \mathrm {e} ^ {\left(\frac {s}{\theta}\right) ^ {m} - \left(\frac {s + t}{\theta}\right) ^ {m}}. \\ f (t) = F ^ {\prime} (t) = \left\{ \begin{array}{l l} \frac {m t ^ {m - 1}}{\theta^ {m}} \mathrm {e} ^ {- \left(\frac {t}{\theta}\right) ^ {m}}, t > 0, \\ 0, & \text {其 他}. \end{array} \right. \\ \hat {\theta} ^ {m} = \frac {1}{n} \sum_ {i = 1} ^ {n} t _ {i} ^ {m}, \\ \end{array}
$$