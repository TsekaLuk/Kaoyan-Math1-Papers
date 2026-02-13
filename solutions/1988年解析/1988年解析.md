# 1988年数学（一）真题解析

# 一、

(1)【解】 由 $\lim_{n\to \infty}\left|\frac{a_{n + 1}}{a_n}\right| = \lim_{n\to \infty}\frac{1}{(n + 1)\cdot 3^{n + 1}}\Bigg{/}\frac{1}{n\cdot 3^n} = \frac{1}{3}$ ，得收敛半径 $R = 3$

当 $x - 3 = -3$ ，即 $x = 0$ 时， $\sum_{n = 1}^{\infty}\frac{(-1)^n}{n}$ 收敛；

当 $x - 3 = 3$ ，即 $x = 6$ 时， $\sum_{n = 1}^{\infty}\frac{1}{n}$ 发散，

故级数 $\sum_{n=1}^{\infty} \frac{(x-3)^n}{n \cdot 3^n}$ 的收敛域为 $[0,6)$ .

(2)【解】 由 $\mathrm{e}^{\varphi^2 (x)} = 1 - x$ ，得 $\varphi (x) = \sqrt{\ln(1 - x)}$

由 $1 - x \geqslant 1$ 得 $\varphi(x)$ 的定义域为 $(- \infty, 0]$ .

（3）【解】 由高斯公式得

$$
\begin{array}{l} I = \oiint_ {S} x ^ {3} d y d z + y ^ {3} d z d x + z ^ {3} d x d y = 3 \iiint_ {a} (x ^ {2} + y ^ {2} + z ^ {2}) d v \\ = 3 \int_ {0} ^ {2 \pi} d \theta \int_ {0} ^ {\pi} d \varphi \int_ {0} ^ {1} r ^ {4} \sin \varphi d r = \frac {6 \pi}{5} \int_ {0} ^ {\pi} \sin \varphi d \varphi = \frac {1 2 \pi}{5}. \\ \end{array}
$$

# 二、填空题

(1)【答案】 $(1 + 2t)\mathrm{e}^{2t}$

【解】 $f(t) = \lim_{x\to \infty}t\left(1 + \frac{1}{x}\right)^{2tx} = t\lim_{x\to \infty}\left[\left(1 + \frac{1}{x}\right)^x\right]^{2t} = te^{2t},$

则 $f^{\prime}(t) = \mathrm{e}^{2t} + 2t\mathrm{e}^{2t} = (1 + 2t)\mathrm{e}^{2t}$

(2)【答案】 $\frac{3}{2}$ .

【解】 $f(x)$ 的傅里叶级数在 $x = 1$ 处收敛于

$$
\frac {f (1 - 0) + f (1 + 0)}{2} = \frac {f (1 - 0) + f (- 1 + 0)}{2} = \frac {1 + 2}{2} = \frac {3}{2}.
$$

(3)【答案】 $\frac{1}{12}$ .

【解】 $\int_0^{x^3 -1}f(t)\mathrm{d}t = x$ 两边对 $x$ 求导得 $3x^{2}f(x^{3} - 1) = 1$

取 $x = 2$ 得 $f(7) = \frac{1}{12}$ .

（4）【答案】 40.

【解】 由 $\mathbf{A} + \mathbf{B} = (\pmb {\alpha} + \pmb {\beta},2\pmb{\gamma}_2,2\pmb{\gamma}_3,2\pmb{\gamma}_4)$ 得

$$
\begin{array}{l} \left| \boldsymbol {A} + \boldsymbol {B} \right| = \left| \boldsymbol {\alpha} + \boldsymbol {\beta}, 2 \gamma_ {2}, 2 \gamma_ {3}, 2 \gamma_ {4} \right| = 8 \left| \boldsymbol {\alpha} + \boldsymbol {\beta}, \gamma_ {2}, \gamma_ {3}, \gamma_ {4} \right| \\ = 8 \left(\left| \boldsymbol {\alpha}, \boldsymbol {\gamma} _ {2}, \boldsymbol {\gamma} _ {3}, \boldsymbol {\gamma} _ {4} \right| + \left| \boldsymbol {\beta}, \boldsymbol {\gamma} _ {2}, \boldsymbol {\gamma} _ {3}, \boldsymbol {\gamma} _ {4} \right|\right) = 8 \left(\left| \boldsymbol {A} \right| + \left| \boldsymbol {B} \right|\right) = 4 0. \\ \end{array}
$$

# 三、选择题

(1)【答案】 (B).

【解】因为 $f(x)$ 在 $x = x_0$ 处可导，所以 $f(x)$ 在 $x = x_0$ 处可微，

于是 $\mathrm{dy} = f^{\prime}(x_0)\Delta x = \frac{1}{2}\Delta x$ ，故函数在 $x = x_0$ 处的微分 $\mathrm{dy}$ 是与 $\Delta x$ 同阶而非等价的无穷小，应选(B).

（2）【答案】（A）.

【解】将 $x = x_0$ 代入 $y'' - 2y' + 4y = 0$ ，得 $f''(x_0) - 2f'(x_0) + 4f(x_0) = 0$

从而 $f^{\prime \prime}(x_0) = -4f(x_0) < 0$ ，由极值判别法得 $x = x_{0}$ 为 $f(x)$ 的极大值点，应选(A).

(3)【答案】 (C).

【解】 由奇偶性得

$\iiint_{\Omega_1}x\mathrm{d}v = \iiint_{\Omega_1}y\mathrm{d}v = 0,\quad \iiint_{\Omega_1}z\mathrm{d}v = 4\iiint_{\Omega_2}z\mathrm{d}v,\quad \iiint_{\Omega_1}xyz\mathrm{d}v = 0$ 显然选(C).

（4）【答案】 （B）.

【解】 因为级数 $\sum_{n = 0}^{\infty}a_n(x - 1)^n$ 在 $x = -1$ 处收敛，

所以其收敛半径 $R \geqslant |-1 - 1| = 2$ .

当 $x = 2$ 时，因为 $|2 - 1| = 1 < R$ ，所以该级数在 $x = 2$ 处绝对收敛，应选(B).

（5）【答案】 (D).

【解】 方法一

若 $\alpha_{1},\alpha_{2},\dots ,\alpha_{s}$ 线性相关，则存在不全为零的数 $k_{1},k_{2},\dots ,k_{s}$

使得 $k_{1}\pmb{\alpha}_{1} + k_{2}\pmb{\alpha}_{2} + \dots +k_{s}\pmb{\alpha}_{s} = \mathbf{0},$

不妨设 $k_{1} \neq 0$ ，则 $\pmb{\alpha}_{1} = -\frac{k_{2}}{k_{1}}\pmb{\alpha}_{2} - \dots - \frac{k_{s}}{k_{1}}\pmb{\alpha}_{s}$ ，即至少有一个向量可由其余向量线性表示，

故 $\alpha_{1},\alpha_{2},\dots ,\alpha_{s}$ 线性无关的充分必要条件是 $\alpha_{1},\alpha_{2},\dots ,\alpha_{s}$ 中任意一个向量都不可由其余向量线性表示，应选(D).

方法二

$\pmb{\alpha}_{1} = \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix}, \pmb{\alpha}_{2} = \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}, \pmb{\alpha}_{3} = \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix}$ , 显然 $2\pmb{\alpha}_{1} + \pmb{\alpha}_{2} - \pmb{\alpha}_{3} \neq \mathbf{0}$ 且其中任两个向量线性无关, 但向量组 $\pmb{\alpha}_{1}, \pmb{\alpha}_{2}, \pmb{\alpha}_{3}$ 线性相关, 排除(A), (B);

$\pmb{\alpha}_{1} = \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix}, \pmb{\alpha}_{2} = \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}, \pmb{\alpha}_{3} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix}$ , 显然 $\pmb{\alpha}_{1}$ 不可由 $\pmb{\alpha}_{2}, \pmb{\alpha}_{3}$ 线性表示, 但 $\pmb{\alpha}_{1}, \pmb{\alpha}_{2}, \pmb{\alpha}_{3}$ 线性相关, 排除(C), 应选(D).

四、【解】 $\frac{\partial u}{\partial x} = f^{\prime}\left(\frac{x}{y}\right) + g\left(\frac{y}{x}\right) - \frac{y}{x} g^{\prime}\left(\frac{y}{x}\right),$

$$
\frac {\partial^ {2} u}{\partial x ^ {2}} = \frac {1}{y} f ^ {\prime \prime} \left(\frac {x}{y}\right) - \frac {y}{x ^ {2}} g ^ {\prime} \left(\frac {y}{x}\right) + \frac {y}{x ^ {2}} g ^ {\prime} \left(\frac {y}{x}\right) + \frac {y ^ {2}}{x ^ {3}} g ^ {\prime \prime} \left(\frac {y}{x}\right) = \frac {1}{y} f ^ {\prime \prime} \left(\frac {x}{y}\right) + \frac {y ^ {2}}{x ^ {3}} g ^ {\prime \prime} \left(\frac {y}{x}\right),
$$

$$
\frac {\partial^ {2} u}{\partial x \partial y} = - \frac {x}{y ^ {2}} f ^ {\prime \prime} \left(\frac {x}{y}\right) + \frac {1}{x} g ^ {\prime} \left(\frac {y}{x}\right) - \frac {1}{x} g ^ {\prime} \left(\frac {y}{x}\right) - \frac {y}{x ^ {2}} g ^ {\prime \prime} \left(\frac {y}{x}\right) = - \frac {x}{y ^ {2}} f ^ {\prime \prime} \left(\frac {x}{y}\right) - \frac {y}{x ^ {2}} g ^ {\prime \prime} \left(\frac {y}{x}\right),
$$

则 $x\frac{\partial^2u}{\partial x^2} +y\frac{\partial^2u}{\partial x\partial y} = \frac{x}{y} f''\left(\frac{x}{y}\right) + \frac{y^2}{x^2} g''\left(\frac{y}{x}\right) - \frac{x}{y} f''\left(\frac{x}{y}\right) - \frac{y^2}{x^2} g''\left(\frac{y}{x}\right) = 0.$

五、【解】 特征方程为 $\lambda^2 - 3\lambda + 2 = 0$ ，特征根为 $\lambda_1 = 1, \lambda_2 = 2$

$y^{\prime \prime} - 3y^{\prime} + 2y = 0$ 的通解为 $y = C_{1}\mathrm{e}^{x} + C_{2}\mathrm{e}^{2x}$

设原方程的特解为 $y_0(x) = ax\mathrm{e}^x$ ，代入得 $a = -2$

故原方程的通解为 $y = C_{1} \mathrm{e}^{x} + C_{2} \mathrm{e}^{2x} - 2x \mathrm{e}^{x}$ ( $C_{1}, C_{2}$ 为任意常数).

因为曲线 $y = y(x)$ 经过点(0,1)，所以 $C_1 + C_2 = 1$

$y = y(x)$ 在 $x = 0$ 处切线的斜率为 $k = (2x - 1)\mid_{x = 0} = -1$

又由 $y' = C_1 e^x + 2C_2 e^{2x} - 2(x + 1) e^x$ ，得 $C_1 + 2C_2 - 2 = -1$ ，即 $C_1 + 2C_2 = 1$

从而 $C_1 = 1, C_2 = 0$ ，故所求函数为 $y = (1 - 2x)\mathrm{e}^x$

六、【解】设 $M(x,y)$ ，则 $\overrightarrow{MA} = \{-x,1 - y\}$

$$
\overrightarrow {M A} ^ {0} = \boldsymbol {F} ^ {0} = \frac {1}{\sqrt {x ^ {2} + (1 - y) ^ {2}}} \{- x, 1 - y \},
$$

则 $F(x,y) = |F|\cdot F^0 = \frac{k}{[x^2 + (1 - y)^2]^{\frac{3}{2}}}\{-x,1 - y\} ,$

设 $M$ 沿 $y = \sqrt{2x - x^2}$ 从点 $B(2,0)$ 到点 $O(0,0)$ 的有向曲线段为 $L$

则 $W = k\int_{L}\frac{-x\mathrm{d}x + (1 - y)\mathrm{d}y}{[x^2 + (1 - y)^2]^{\frac{3}{2}}},$

令 $P(x,y) = -\frac{x}{[x^2 + (1 - y)^2]^{\frac{3}{2}}},$ $Q(x,y) = \frac{1 - y}{[x^2 + (1 - y)^2]^{\frac{3}{2}}},$

因为 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$ 所以曲线积分与路径无关，

故 $W = k\int_{\overline{BO}}\frac{-x\mathrm{d}x + (1 - y)\mathrm{d}y}{[x^2 + (1 - y)^2]^{\frac{3}{2}}} = k\int_{2}^{0}\frac{-x\mathrm{d}x}{(x^2 + 1)^{\frac{3}{2}}} = k\left(1 - \frac{1}{\sqrt{5}}\right).$

七、【解】 $P^{-1} = \left( \begin{array}{rrr}1 & 0 & 0\\ 2 & -1 & 0\\ -4 & 1 & 1 \end{array} \right),\quad A = PBP^{-1} = \left( \begin{array}{rrr}1 & 0 & 0\\ 2 & 0 & 0\\ 6 & -1 & -1 \end{array} \right);$

$$
\mathbf {A} ^ {5} = \mathbf {P B} ^ {5} \mathbf {P} ^ {- 1} = \mathbf {P B P} ^ {- 1} = \mathbf {A}.
$$

八、【解】（1）因为矩阵 $\mathbf{A}$ 与 $\pmb{B}$ 相似，所以 $\operatorname {tr}\mathbf{A} = \operatorname {tr}\mathbf{B}$ ，即 $x + 2 = y + 1$ ，或 $x = y - 1$

再由矩阵 $\mathbf{A}$ 与 $\pmb{B}$ 相似得 $|\mathbf{A}| = |\mathbf{B}|$ ，即 $-2 = -2y$ ，解得 $y = 1$ 故 $x = 0, y = 1$ .

（2）显然矩阵 $\mathbf{A}$ 及 $\pmb{B}$ 的特征值为 $\lambda_1 = 2, \lambda_2 = 1, \lambda_3 = -1$

由 $2E - A = \begin{pmatrix} 0 & 0 & 0\\ 0 & 2 & -1\\ 0 & -1 & 2 \end{pmatrix} \to \begin{pmatrix} 0 & 1 & 0\\ 0 & 0 & 1\\ 0 & 0 & 0 \end{pmatrix}$ 得

矩阵 $\mathbf{A}$ 的相应于 $\lambda_{1} = 2$ 的特征向量为 $\pmb{\alpha}_{1} = (1,0,0)^{\mathrm{T}}$

由 $\pmb {E} - \pmb {A} = \left( \begin{array}{rrr} - 1 & 0 & 0\\ 0 & 1 & -1\\ 0 & -1 & 1 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & 0\\ 0 & 1 & -1\\ 0 & 0 & 0 \end{array} \right)$ 得

矩阵 $\mathbf{A}$ 的相应于 $\lambda_{2} = 1$ 的特征向量为 $\pmb{\alpha}_{2}=(0,1,1)^{\mathrm{T}}$ ;

由 $-\mathbf{E} - \mathbf{A} = \left( \begin{array}{rrr} - 3 & 0 & 0\\ 0 & -1 & -1\\ 0 & -1 & -1 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & 0\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得

矩阵 $\mathbf{A}$ 的相应于 $\lambda_{3} = -1$ 的特征向量为 $\pmb{\alpha}_{3} = (0, - 1,1)^{\mathrm{T}}$

令 $\pmb{P} = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & -1 \\ 0 & 1 & 1 \end{pmatrix}$ , 则 $\pmb{P}^{-1}\pmb{A}\pmb{P} = \pmb{B}$ .

九、【证明】 令 $S_{1}(x) = \int_{a}^{x}[f(x) - f(t)]\mathrm{d}t$ ， $S_{2}(x) = \int_{x}^{b}[f(t) - f(x)]\mathrm{d}t$

再令 $\varphi (x) = S_{1}(x) - 3S_{2}(x) = \int_{a}^{x}[f(x) - f(t)]\mathrm{d}t - 3\int_{x}^{b}[f(t) - f(x)]\mathrm{d}t,$

则 $\varphi (x) = (x - a)f(x) - \int_{a}^{x}f(t)\mathrm{d}t + 3\int_{b}^{x}f(t)\mathrm{d}t - 3(x - b)f(x),$

因为 $f^{\prime}(x) > 0$ ，所以 $f(x)$ 在 $[a,b]$ 上严格递增，

从而 $\varphi (a) = -3\int_{a}^{b}[f(t) - f(a)]\mathrm{d}t < 0,\quad \varphi (b) = \int_{a}^{b}[f(b) - f(t)]\mathrm{d}t > 0,$

即存在 $\xi \in (a,b)$ ，使得 $\varphi (\xi) = 0$ ，即 $S_{1}(\xi) = 3S_{2}(\xi)$

因为 $\varphi^{\prime}(x) = (x - a)f^{\prime}(x) - 3(x - b)f^{\prime}(x)$

$$
= f ^ {\prime} (x) \lceil (x - a) + 3 (b - x) \rceil > 0 \quad (a <   x <   b),
$$

所以 $\varphi (x)$ 在 $[a,b]$ 上严格递增，故 $\xi$ 是唯一的.

# 十、填空题

(1)【答案】 $\frac{1}{3}$ .

【解】令 $P(A) = p$ ，设三次试验中 $A$ 出现的次数为 $X$ ，则 $X \sim B(3, p)$

由 $P\{X \geqslant 1\} = \frac{19}{27}$ , 得 $P\{X = 0\} = C_3^0 p^0 (1 - p)^3 = (1 - p)^3 = \frac{8}{27}$ , 解得 $p = \frac{1}{3}$ , 故事件 $A$ 在一次试验中出现的概率为 $\frac{1}{3}$ .

(2)【答案】 $\frac{17}{25}$ .

【解】设(0,1)中任取的两个数为 $X,Y$ ，令 $D = \{(x,y)\mid 0 <   x <   1,0 <   y <   1\}$ 则 $(X,Y)$ 在 $D$ 上服从均匀分布，即 $(X,Y)$ 的联合概率密度为

$$
f (x, y) = \left\{ \begin{array}{l l} 1, & (x, y) \in D, \\ 0, & (x, y) \notin D, \end{array} \right.
$$

则 $P\left\{X + Y < \frac{6}{5}\right\} = \iint_{x + y \leqslant \frac{6}{5}} f(x, y) \mathrm{d}x \mathrm{~d}y = 1 - \iint_{x + y > \frac{6}{5}} f(x, y) \mathrm{d}x \mathrm{~d}y$

$$
= 1 - \frac {1}{2} \times \left(\frac {4}{5}\right) ^ {2} = \frac {1 7}{2 5}.
$$

(3)【答案】 0.9876.

【解】 由 $X \sim N(10, 0.02^2)$ 得 $\frac{X - 10}{0.02} \sim N(0, 1)$ ,

则 $P\{9.95 < X < 10.05\} = P\left\{-2.5 < \frac{X - 10}{0.02} < 2.5\right\}$

$$
= \Phi (2. 5) - \Phi (- 2. 5) = 2 \Phi (2. 5) - 1 = 0. 9 8 7 6.
$$

十一、【解】 $F_{Y}(y) = P\{Y \leqslant y\} = P\{1 - \sqrt[3]{X} \leqslant y\} = P\{X \geqslant (1 - y)^{3}\}$

$$
= 1 - P \{X \leqslant (1 - y) ^ {3} \} = 1 - \int_ {- \infty} ^ {(1 - y) ^ {3}} \frac {1}{\pi (1 + x ^ {2})} d x,
$$

则 $f_{Y}(y) = \frac{3(1 - y)^{2}}{\pi[1 + (1 - y)^{6}]}.$