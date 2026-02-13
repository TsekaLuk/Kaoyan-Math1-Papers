# 1987年数学(一）真题解析

# 一、填空题

(1)【答案】 $x - y + z = 0$

【解】直线 $\left\{ \begin{array}{l}x = 1,\\ y = -1 + t, \end{array} \right.$ 的方向向量为 $s_1 = \{0,1,1\}$ ，直线 $\frac{x + 1}{1} = \frac{y + 2}{2} = \frac{z - 1}{1}$ 的方向向量为 $s_2 =$ $\{1,2,1\}$ ，所求平面的法向量为 $\pmb {n} = \{0,1,1\} \times \{1,2,1\} = \{-1,1, - 1\}$ 则所求平面方程为 $\pi :x - y + z = 0$

(2)【答案】 $-\frac{1}{\ln 2}$ .

【解】由 $y' = 2^x (1 + x \ln 2) = 0$ ，得 $x = -\frac{1}{\ln 2}$ .

当 $x < -\frac{1}{\ln 2}$ 时 $y' < 0$ ；当 $x > -\frac{1}{\ln 2}$ 时 $y' > 0$ ，故当 $x = -\frac{1}{\ln 2}$ 时，函数 $y = x^{2^x}$ 取得极小值.

(3)【答案】 $\frac{3}{2}$ .

【解】由 $\ln x = (\mathrm{e} + 1) - x$ 得出 $x = \mathrm{e}$ ，曲线 $y = \ln x$ 与直线 $y = (\mathrm{e} + 1) - x$ 的交点为 $(\mathrm{e}, 1)$ ，则所围成的平面图形的面积为

$$
A = \int_ {1} ^ {\mathrm {e}} \ln x \mathrm {d} x + \int_ {\mathrm {e}} ^ {\mathrm {e} + 1} (\mathrm {e} + 1 - x) \mathrm {d} x = x \ln x | _ {1} ^ {\mathrm {e}} - (\mathrm {e} - 1) + (\mathrm {e} + 1) - \frac {(\mathrm {e} + 1) ^ {2} - \mathrm {e} ^ {2}}{2} = \frac {3}{2}.
$$

(4)【答案】 $-18\pi$

【解】 方法一 由格林公式得

$$
\begin{array}{l} \oint_ {L} (2 x y - 2 y) \mathrm {d} x + (x ^ {2} - 4 x) \mathrm {d} y = \iint_ {D} (2 x - 4 - 2 x + 2) \mathrm {d} x \mathrm {d} y \\ = - 2 \iint_ {D} \mathrm {d} x \mathrm {d} y = - 1 8 \pi . \\ \end{array}
$$

方法二 令 $L: \left\{ \begin{array}{l} x = 3\cos t, \\ y = 3\sin t \end{array} \right.$ （起点 $t = 0$ ，终点 $t = 2\pi$ ），则

$$
\begin{array}{l} \oint_ {L} (2 x y - 2 y) \mathrm {d} x + (x ^ {2} - 4 x) \mathrm {d} y = \int_ {0} ^ {2 \pi} (1 8 \sin t \cos t - 6 \sin t) \cdot (- 3 \sin t) \mathrm {d} t + \\ \left(9 \cos^ {2} t - 1 2 \cos t\right) \cdot 3 \cos t d t \\ = \int_ {0} ^ {2 \pi} (- 5 4 \sin^ {2} t \cos t + 1 8 \sin^ {2} t + 2 7 \cos^ {3} t - 3 6 \cos^ {2} t) d t \\ = 1 8 \int_ {0} ^ {2 \pi} \sin^ {2} t d t - 3 6 \int_ {0} ^ {2 \pi} \cos^ {2} t d t \\ = 3 6 \int_ {0} ^ {\pi} \sin^ {2} t d t - 7 2 \int_ {0} ^ {\pi} \cos^ {2} t d t \\ = 7 2 I _ {2} - 1 4 4 I _ {2} = - 7 2 I _ {2} = - 1 8 \pi . \\ \end{array}
$$

（5）【答案】 $(1,1, - 1)$

【解】 令 $x_{1}\pmb{\alpha}_{1} + x_{2}\pmb{\alpha}_{2} + x_{3}\pmb{\alpha}_{3} = \pmb{\alpha}$

由 $\left( \begin{array}{rrr}1 & 1 & 0 & 2\\ 1 & 0 & 1 & 0\\ 0 & 1 & 1 & 0 \end{array} \right)\to \left( \begin{array}{rrr}1 & 1 & 0 & 2\\ 0 & 1 & -1 & 2\\ 0 & 0 & 1 & -1 \end{array} \right)\to \left( \begin{array}{rrr}1 & 0 & 0 & 1\\ 0 & 1 & 0 & 1\\ 0 & 0 & 1 & -1 \end{array} \right)$ ，得

向量 $\pmb{\alpha}$ 在基底 $\alpha_{1},\alpha_{2},\alpha_{3}$ 下的坐标为 $(1,1, - 1)$

二、【解】 由 $\lim_{x\to 0}\frac{\int_0^x\frac{t^2}{\sqrt{a + t^2}}\mathrm{d}t}{x^3} = \lim_{x\to 0}\frac{\frac{x^2}{\sqrt{a + x^2}}}{3x^2} = \frac{1}{3\sqrt{a}}$ 得 $\int_0^x\frac{t^2}{\sqrt{a + t^2}}\mathrm{d}t\sim \frac{1}{3\sqrt{a}} x^3$ ，从而 $b = 1$

再由 $\lim_{x\to 0}\frac{1}{bx - \sin x}\int_0^x\frac{t^2}{\sqrt{a + t^2}}\mathrm{d}t = \lim_{x\to 0}\frac{\frac{x^3}{3\sqrt{a}}}{x - \sin x} = \frac{1}{\sqrt{a}}\lim_{x\to 0}\frac{x^2}{1 - \cos x} = \frac{2}{\sqrt{a}} = 1$ ，得 $a = 4$

故 $a = 4, b = 1$

# 三、

(1)【解】 $\frac{\partial u}{\partial x} = f_x' + yf_y'$ , $\frac{\partial v}{\partial x} = g'\cdot (1 + y)$ , 故 $\frac{\partial u}{\partial x}\cdot \frac{\partial v}{\partial x} = g'(f_x' + yf_y')$ $(1 + y)$ .

(2)【解】由 $\mathbf{AB} = \mathbf{A} + 2\mathbf{B}$ 得 $(\mathbf{A} - 2\mathbf{E})\mathbf{B} = \mathbf{A}$ ，解得 $\mathbf{B} = (\mathbf{A} - 2\mathbf{E})^{-1}\mathbf{A}$

而 $\mathbf{A} - 2\mathbf{E} = \begin{pmatrix} 1 & 0 & 1\\ 1 & -1 & 0\\ 0 & 1 & 2 \end{pmatrix}$

由 $\left( \begin{array}{rrrrr}1 & 0 & 1 & 1 & 0 & 0\\ 1 & -1 & 0 & 0 & 1 & 0\\ 0 & 1 & 2 & 0 & 0 & 1 \end{array} \right)\to \left( \begin{array}{rrrrr}1 & 0 & 1 & 1 & 0 & 0\\ 0 & -1 & -1 & -1 & 1 & 0\\ 0 & 0 & 1 & -1 & 1 & 1 \end{array} \right)\to \left( \begin{array}{rrrrr}1 & 0 & 0 & 2 & -1 & -1\\ 0 & 1 & 0 & 2 & -2 & -1\\ 0 & 0 & 1 & -1 & 1 & 1 \end{array} \right)$

得 $(\mathbf{A} - 2\mathbf{E})^{-1} = \left( \begin{array}{rrr}2 & -1 & -1\\ 2 & -2 & -1\\ -1 & 1 & 1 \end{array} \right),$

于是 $\pmb{B} = \begin{pmatrix} 2 & -1 & -1 \\ 2 & -2 & -1 \\ -1 & 1 & 1 \end{pmatrix} \begin{pmatrix} 3 & 0 & 1 \\ 1 & 1 & 0 \\ 0 & 1 & 4 \end{pmatrix} = \begin{pmatrix} 5 & -2 & -2 \\ 4 & -3 & -2 \\ -2 & 2 & 3 \end{pmatrix}$ .

# 四、【解】 方法一

$y^{\prime \prime} + 6y^{\prime \prime} + (9 + a^{2})y^{\prime} = 1$ 两边积分得 $y'' + 6y' + (9 + a^2)y = x + C_0$

$y^{\prime \prime} + 6y^{\prime} + (9 + a^{2})y = 0$ 的特征方程为 $\lambda^2 +6\lambda +(9 + a^2) = 0$

解得 $\lambda_{1,2} = -3\pm a\mathrm{i}$

则方程 $y^{\prime \prime} + 6y^{\prime} + (9 + a^{2})y = 0$ 的通解为 $y = \mathrm{e}^{-3x}(C_1\cos ax + C_2\sin ax)$

设 $y^{\prime \prime} + 6y^{\prime} + (9 + a^{2})y = x + C_{0}$ 的特解为 $y^{*} = Ax + B$ ，代入得

$$
A = \frac {1}{9 + a ^ {2}}, \quad B = \frac {C _ {0}}{9 + a ^ {2}} - \frac {6}{(9 + a ^ {2}) ^ {2}},
$$

故原方程的通解为

$$
y = \mathrm {e} ^ {- 3 x} \left(C _ {1} \cos a x + C _ {2} \sin a x\right) + \frac {x}{9 + a ^ {2}} + \frac {C _ {0}}{9 + a ^ {2}} - \frac {6}{(9 + a ^ {2}) ^ {2}}.
$$

# 方法二

特征方程为 $\lambda^3 + 6\lambda^2 + (9 + a^2)\lambda = 0$

解得特征根为 $\lambda_{1} = 0$ ， $\lambda_{2} = -3 + a\mathrm{i}$ ， $\lambda_{3} = -3 - a\mathrm{i}$

$y^{\prime \prime} + 6y^{\prime \prime} + (9 + a^{2})y^{\prime} = 0$ 的通解为 $y = C_1 + \mathrm{e}^{-3x}(C_2\cos ax + C_3\sin ax)$

显然原方程有特解 $y_0(x) = \frac{x}{9 + a^2}$

故原方程通解为 $y = C_{1} + \mathrm{e}^{-3x}\left(C_{2}\cos ax + C_{3}\sin ax\right) + \frac{x}{9 + a^{2}}.$

# 五、选择题

(1)【答案】 (C).

【解】 $\sum_{n = 1}^{\infty}(-1)^{n}\frac{k + n}{n^{2}} = k\sum_{n = 1}^{\infty}(-1)^{n}\frac{1}{n^{2}} +\sum_{n = 1}^{\infty}(-1)^{n}\frac{1}{n},$

因为级数 $\sum_{n=1}^{\infty}(-1)^{n}\frac{1}{n^{2}}$ 绝对收敛，级数 $\sum_{n=1}^{\infty}(-1)^{n}\frac{1}{n}$ 条件收敛，所以原级数条件收敛，应选(C).

(2)【答案】 (D).

【解】 $I = t\int_{0}^{\frac{s}{t}}f(tx)\mathrm{d}x = \int_{0}^{\frac{s}{t}}f(tx)\mathrm{d}(tx)\stackrel {tx = u}{=}\int_{0}^{s}f(u)\mathrm{d}u,$

显然 $I$ 与 $s$ 有关，与 $t$ 无关，应选(D).

(3)【答案】 (B).

【解】由极限的保号性可知，存在 $\delta > 0$ ，当 $0 < |x - a| < \delta$ 时， $\frac{f(x) - f(a)}{(x - a)^2} < 0$

即 $f(x) < f(a)$ ，故 $x = a$ 为极大值点，应选(B).

（4）【答案】 (C).

【解】由 $AA^{*} = |A|E$ 得出 $|\pmb {A}|\cdot |\pmb{A}^{*}| = ||\pmb {A}|\pmb {E}| = |\pmb {A}|^{n}$

由 $|\mathbf{A}| = a \neq 0$ 得 $|\mathbf{A}^*| = a^{n-1}$ ，应选(C).

六、【解】 由 $\lim_{n\to \infty}\left|\frac{a_{n + 1}}{a_n}\right| = \frac{1}{2}$ ，得幂级数的收敛半径为 $R = 2$

当 $x = -2$ 时，级数 $\sum_{n=1}^{\infty} \frac{1}{n 2^n} (-2)^{n-1} = \frac{1}{2} \sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{n}$ 收敛；

当 $x = 2$ 时，级数 $\sum_{n=1}^{\infty} \frac{1}{n2^n} 2^{n-1} = \frac{1}{2} \sum_{n=1}^{\infty} \frac{1}{n}$ 发散，故收敛域为 $[-2,2)$ ；

令 $S(x) = \sum_{n=1}^{\infty} \frac{1}{n 2^n} x^{n-1}$ ,

当 $x = 0$ 时， $S(0) = \frac{1}{2}$

当 $x \neq 0$ 时， $S(x) = \frac{1}{x} \sum_{n=1}^{\infty} \frac{\left(\frac{x}{2}\right)^n}{n} = -\frac{1}{x} \ln \left(1 - \frac{x}{2}\right)$ ，

故 $S(x) = \left\{ \begin{array}{ll} \frac{1}{2}, & x = 0, \\ -\frac{1}{x}\ln \left(1 - \frac{x}{2}\right), & -2 \leqslant x < 2 \text{且} x \neq 0. \end{array} \right.$

七、【解】曲面 $S$ 的方程为 $S:y - 1 = x^{2} + z^{2}(1\leqslant y\leqslant 3)$ ，取外侧，

令 $S_0:y = 3(x^2 +z^2\leqslant 2)$ ，取右侧，则

$$
I = \left(\iint_ {S + S _ {0}} - \iint_ {S _ {0}}\right) x (8 y + 1) d y d z + 2 (1 - y ^ {2}) d z d x - 4 y z d x d y,
$$

由 $\iint_{S + S_0}x(8y + 1)\mathrm{d}y\mathrm{d}z + 2(1 - y^2)\mathrm{d}z\mathrm{d}x - 4yz\mathrm{d}x\mathrm{d}y$

$$
= \iiint_ {\Omega} \mathrm {d} v = \int_ {1} ^ {3} \mathrm {d} y \iint_ {x ^ {2} + z ^ {2} \leqslant y - 1} \mathrm {d} x \mathrm {d} z = \pi \int_ {1} ^ {3} (y - 1) \mathrm {d} y = 2 \pi ,
$$

$$
\begin{array}{l} \iint_ {S _ {0}} x (8 y + 1) \mathrm {d} y \mathrm {d} z + 2 (1 - y ^ {2}) \mathrm {d} z \mathrm {d} x - 4 y z \mathrm {d} x \mathrm {d} y \\ = \iint_ {S _ {0}} 2 \left(1 - y ^ {2}\right) \mathrm {d} z \mathrm {d} x = - 1 6 \iint_ {S _ {0}} \mathrm {d} z \mathrm {d} x = - 1 6 \iint_ {x ^ {2} + z ^ {2} \leqslant 2} \mathrm {d} z \mathrm {d} x = - 3 2 \pi , \\ \end{array}
$$

故 $I = 34\pi$

八、【证明】 令 $g(x) = f(x) - x$

因为 $0 < f(x) < 1 (0 \leqslant x \leqslant 1)$ ，所以 $g(0) = f(0) > 0, g(1) = f(1) - 1 < 0$

由零点定理， $g(x)$ 在 $(0,1)$ 内有零点，即存在 $x\in (0,1)$ ，使得 $g(x) = 0$ ，即 $f(x) = x$

$g^{\prime}(x) = f^{\prime}(x) - 1$ ，因为 $f^{\prime}(x)\neq 1$ ，所以 $g^{\prime}(x) > 0$ 或 $g^{\prime}(x) <   0$

即 $g(x)$ 在 $[0,1]$ 上严格单调，故 $g(x)$ 在 $(0,1)$ 内零点唯一，

即在(0,1)内有且仅有一个 $x$ ，使得 $f(x) = x$

九、【解】 $\overline{\mathbf{A}} = \begin{bmatrix} 1 & 1 & 1 & 1 \\ 0 & 1 & 2 & 2 \\ 0 & -1 & a - 3 & -2 \\ 3 & 2 & 1 & a \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 1 & 1 & 1 \\ 0 & 1 & 2 & 2 \\ 0 & -1 & a - 3 & -2 \\ 0 & -1 & -2 & a - 3 \end{bmatrix} \rightarrow \begin{bmatrix} 0 \\ 1 \\ 1 \\ b \\ -1 \end{bmatrix}$

$$
\rightarrow \left(\begin{array}{c c c c c c}1&1&1&1&0\\0&1&2&2&1\\0&0&a - 1&0&b + 1\\0&0&0&a - 1&0\end{array}\right),
$$

当 $a \neq 1, b$ 为任意常数时，方程组有唯一解；

当 $a = 1, b \neq -1$ 时，方程组无解；

当 $a = 1, b = -1$ 时，方程组有无数个解，将 $a, b$ 代入后得出

$\overline{\mathbf{A}} \rightarrow \begin{bmatrix} 1 & 0 & -1 & -1 \\ 0 & 1 & 2 & 2 \\ 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{bmatrix}$ , 得方程组的通解为

$$
\pmb {X} = k _ {1} \left[ \begin{array}{c} {{1}} \\ {{- 2}} \\ {{1}} \\ {{0}} \end{array} \right] + k _ {2} \left[ \begin{array}{c} {{1}} \\ {{- 2}} \\ {{0}} \\ {{1}} \end{array} \right] + \left[ \begin{array}{c} {{- 1}} \\ {{1}} \\ {{0}} \\ {{0}} \end{array} \right] (k _ {1}, k _ {2} \text {为 任 意 常 数}).
$$

# 十、填空题

(1)【答案】 $1 - (1 - p)^n$ ， $[1 + (n - 1)p](1 - p)^{n - 1}$ .

【解】设 $n$ 次试验中 $A$ 发生的次数为 $X$ ，显然 $X\sim B(n,p)$

则 $P\{X \geqslant 1\} = 1 - P\{X = 0\} = 1 - C_n^0 p^0 (1 - p)^n = 1 - (1 - p)^n$

$$
\begin{array}{l} P \{X \leqslant 1 \} = P \{X = 0 \} + P \{X = 1 \} = C _ {n} ^ {0} p ^ {0} (1 - p) ^ {n} + C _ {n} ^ {1} p (1 - p) ^ {n - 1} \\ = (1 - p) ^ {n - 1} [ 1 + (n - 1) p ]. \\ \end{array}
$$

(2)【答案】 $\frac{53}{120}, \frac{20}{53}$ .

【解】记 $A_{i} = \{$ 取的是第 $i$ 个箱子 $\}$ $(i = 1,2,3)$ ， $B = \{$ 从箱子中取出的是白球 $\}$ ，则

$$
P \left(A _ {1}\right) = P \left(A _ {2}\right) = P \left(A _ {3}\right) = \frac {1}{3}, P \left(B \mid A _ {1}\right) = \frac {1}{5}, P \left(B \mid A _ {2}\right) = \frac {3}{6} = \frac {1}{2}, P \left(B \mid A _ {3}\right) = \frac {5}{8}.
$$

① 由全概率公式知： $P(B) = P(A_{1})P(B\mid A_{1}) + P(A_{2})P(B\mid A_{2}) + P(A_{3})P(B\mid A_{3})$

$$
= \frac {1}{3} \times \frac {1}{5} + \frac {1}{3} \times \frac {1}{2} + \frac {1}{3} \times \frac {5}{8} = \frac {5 3}{1 2 0}.
$$

$$
\text {②} P \left(A _ {2} \mid B\right) = \frac {P \left(A _ {2} B\right)}{P (B)} = \frac {P \left(A _ {2}\right) P \left(B \mid A _ {2}\right)}{P (B)} = \frac {\frac {1}{3} \times \frac {1}{2}}{\frac {5 3}{1 2 0}} = \frac {2 0}{5 3};
$$

(3)【答案】1， $\frac{1}{2}$ .

【解】 方法一

由 $f(x) = \frac{1}{\sqrt{\pi}}\mathrm{e}^{-x^2 +2x - 1} = \frac{1}{\sqrt{2\pi}\cdot\frac{1}{\sqrt{2}}}\mathrm{e}^{-\frac{(x - 1)^2}{2\left(\frac{1}{\sqrt{2}}\right)^2}},$ 得 $X\sim N\left(1,\frac{1}{2}\right)$

故 $E(X) = 1$ ， $D(X) = \frac{1}{2}$

方法二

$$
\begin{array}{l} E (X) = \int_ {- \infty} ^ {+ \infty} x f (x) d x = \frac {1}{\sqrt {\pi}} \int_ {- \infty} ^ {+ \infty} x e ^ {- (x - 1) ^ {2}} d x \\ = \frac {1}{\sqrt {\pi}} \int_ {- \infty} ^ {+ \infty} [ 1 + (x - 1) ] e ^ {- (x - 1) ^ {2}} d (x - 1) = \frac {1}{\sqrt {\pi}} \int_ {- \infty} ^ {+ \infty} (1 + x) e ^ {- x ^ {2}} d x \\ = \frac {2}{\sqrt {\pi}} \int_ {0} ^ {+ \infty} e ^ {- x ^ {2}} d x \xlongequal {x ^ {2} = t} \frac {2}{\sqrt {\pi}} \int_ {0} ^ {+ \infty} \frac {1}{2 \sqrt {t}} e ^ {- t} d t = \frac {1}{\sqrt {\pi}} \int_ {0} ^ {+ \infty} t ^ {- \frac {1}{2}} e ^ {- t} d t = \frac {1}{\sqrt {\pi}} \Gamma \left(\frac {1}{2}\right) = 1. \\ \end{array}
$$

# 十一、【解】因为随机变量 $X, Y$ 相互独立，所以 $(X, Y)$ 的联合概率密度为

$$
f (x, y) = f _ {X} (x) f _ {Y} (y) = \left\{ \begin{array}{l l} \mathrm {e} ^ {- y}, & 0 <   x <   1, y > 0, \\ 0, & \text {其 他}. \end{array} \right.
$$

则 $F_{Z}(z) = P\{Z \leqslant z\} = P\{2X + Y \leqslant z\} = \iint_{2x + y \leqslant z} f(x, y) \, \mathrm{d}x \, \mathrm{d}y,$

当 $z < 0$ 时， $F_{Z}(z) = 0$

当 $0 \leqslant z < 2$ 时， $F_{Z}(z) = \int_{0}^{\frac{z}{2}} \mathrm{d}x \int_{0}^{z - 2x} \mathrm{e}^{-y} \mathrm{d}y = \int_{0}^{\frac{z}{2}} (1 - \mathrm{e}^{2x - z}) \mathrm{d}x = \frac{z}{2} - \frac{1}{2} + \frac{1}{2} \mathrm{e}^{-z}$ ;

当 $z \geqslant 2$ 时， $F_Z(z) = \int_0^1 \mathrm{d}x \int_0^{z - 2x} \mathrm{e}^{-y} \, \mathrm{d}y = \int_0^1 (1 - \mathrm{e}^{2x - z}) \, \mathrm{d}x = 1 - \frac{1}{2} (\mathrm{e}^2 - 1) \mathrm{e}^{-z}$ ，

故 $f_{Z}(z) = \left\{ \begin{array}{ll}0, & z <   0,\\ \frac{1}{2} (1 - \mathrm{e}^{-z}), & 0\leqslant z\leqslant 2,\\ \frac{1}{2}\mathrm{e}^{-z}(\mathrm{e}^{2} - 1), & z > 2. \end{array} \right.$