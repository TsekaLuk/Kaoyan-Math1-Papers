# 2017年数学(一)真题解析

# 一、选择题

(1)【答案】 (A).

【解】 $f(0 + 0) = \lim_{x\to 0^{+}}\frac{1 - \cos\sqrt{x}}{ax} = \frac{1}{2a},$ $f(0) = f(0 - 0) = b,$

因为 $f(x)$ 在 $x = 0$ 处连续，所以 $f(0 + 0) = f(0) = f(0 - 0)$

从而 $ab = \frac{1}{2}$ ，应选（A）.

(2)【答案】 (C).

【解】方法一 若 $f(x) > 0$ ，则 $f^{\prime}(x) > 0$ ，从而 $f(1) > f(-1) > 0$

若 $f(x) < 0$ ，则 $f^{\prime}(x) < 0$ ，从而 $f(1) < f(-1) < 0$

故 $|f(1)| > |f(-1)|$ ，应选(C).

方法二 由 $f(x) \cdot f'(x) = \left[\frac{1}{2} f^2(x)\right]' > 0$ 得 $f^2(x)$ 单调递增，

从而 $f^2 (1) > f^2 (-1)$ ，故 $|f(1)| > |f(-1)|$ ，应选(C).

(3)【答案】 (D).

【解】 $\frac{\partial f}{\partial x} = 2xy,\quad \frac{\partial f}{\partial y} = x^2,\quad \frac{\partial f}{\partial z} = 2z,$

$$
\left. \frac {\partial f}{\partial x} \right| _ {(1, 2, 0)} = 4, \quad \left. \frac {\partial f}{\partial y} \right| _ {(1, 2, 0)} = 1, \quad \left. \frac {\partial f}{\partial z} \right| _ {(1, 2, 0)} = 0,
$$

$$
\cos \alpha = \frac {1}{3}, \quad \cos \beta = \frac {2}{3}, \quad \cos \gamma = \frac {2}{3},
$$

所求的方向导数为 $\left.\frac{\partial f}{\partial\boldsymbol{n}}\right|_{(1,2,0)} = 4\times \frac{1}{3} +1\times \frac{2}{3} = 2$ ，应选(D).

（4）【答案】 (C).

【解】从 $t = 0$ 到 $t = t_0$ 的时间段上，甲、乙走过的距离分别为

$$
S _ {1} = \int_ {0} ^ {t _ {0}} v _ {1} (t) \mathrm {d} t, \quad S _ {2} = \int_ {0} ^ {t _ {0}} v _ {2} (t) \mathrm {d} t,
$$

在 $t = t_0$ 时， $S_{1} = S_{2} + 10$ ，即 $\int_{0}^{t_0} v_1(t) \, \mathrm{d}t = \int_{0}^{t_0} v_2(t) \, \mathrm{d}t + 10$

或 $\int_0^{t_0}\left[v_1(t) - v_2(t)\right]\mathrm{d}t = 10$ ，故 $t_0 = 25$ ，应选(C).

（5）【答案】 （A）.

【解】 方法一 令 $A = \alpha \alpha^{\mathrm{T}}$ ， $A^2 = A$

令 $AX = \lambda X$ ，由 $(A^2 - A)X = (\lambda^2 - \lambda)X = 0$ 得 $\lambda^2 - \lambda = 0, \lambda = 0$ 或 $\lambda = 1$

因为 $\operatorname{tr} \mathbf{A} = \boldsymbol{\alpha}^{\mathrm{T}} \boldsymbol{\alpha} = 1 = \lambda_{1} + \dots + \lambda_{n}$ 得 $\mathbf{A}$ 的特征值为 $\lambda_{1} = \dots = \lambda_{n-1} = 0, \lambda_{n} = 1$

$\mathbf{E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}$ 的特征值为 $\lambda_{1} = \dots = \lambda_{n - 1} = 1,\lambda_{n} = 0$ ，从而 $|\textbf{E} -\pmb {\alpha}\pmb{\alpha}^{\mathrm{T}}| = 0$

即 $\pmb {E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}$ 不可逆，应选（A）.

方法二 令 $A = E - \alpha \alpha^{\mathrm{T}}, A^{2} = (E - \alpha \alpha^{\mathrm{T}}) \cdot (E - \alpha \alpha^{\mathrm{T}}) = E - 2\alpha \alpha^{\mathrm{T}} + \alpha \alpha^{\mathrm{T}} = A$

由 $\mathbf{A}(\mathbf{E} - \mathbf{A}) = \mathbf{0}$ 得 $r(\mathbf{A}) + r(\mathbf{E} - \mathbf{A})\leqslant n$

再由 $r(\mathbf{A}) + r(\mathbf{E} - \mathbf{A})\geqslant r[\mathbf{A} + (\mathbf{E} - \mathbf{A})] = r(\mathbf{E}) = n$ 得

$$
r (\mathbf {A}) + r (\mathbf {E} - \mathbf {A}) = n,
$$

而 $\pmb {E} - \pmb {A} = \pmb {\alpha}\pmb{\alpha}^{\mathrm{T}},r(\pmb {E} - \pmb {A}) = r(\pmb {\alpha}\pmb{\alpha}^{\mathrm{T}}) = r(\pmb {\alpha}) = 1$

于是 $r(\mathbf{A}) = n - 1 <   n$ ，即 $\pmb {E} - \pmb {\alpha}\pmb{\alpha}^{\mathrm{T}}$ 不可逆，应选（A）.

（6）【答案】 （B）.

【解】 显然矩阵 $A, B, C$ 的特征值都是 $\lambda_{1} = \lambda_{2} = 2, \lambda_{3} = 1$

由 $2E - A = \begin{pmatrix} 0 & 0 & 0\\ 0 & 0 & -1\\ 0 & 0 & 1 \end{pmatrix}$ 得 $r(2E - A) = 1$ ，则 $\mathbf{A}$ 可相似对角化，从而 $A\sim C$

由 $2\pmb {E} - \pmb {B} = \left( \begin{array}{lll}0 & -1 & 0\\ 0 & 0 & 0\\ 0 & 0 & 1 \end{array} \right)$ 得 $r(2E - B) = 2$ ，则 $\pmb{B}$ 不可相似对角化，从而 $\pmb{B}$ 与 $\mathbf{A},\mathbf{C}$ 不相似，应选(B).

方法点评：设 $A, B$ 为 $n$ 阶矩阵，且 $|\lambda E - A| = |\lambda E - B|$ ，即 $A, B$ 的特征值相同，则

（1）若矩阵 $\mathbf{A},\mathbf{B}$ 都可相似对角化，则 $A\sim B$   
（2）若矩阵 $\mathbf{A},\mathbf{B}$ 中一个可相似对角化，一个不可相似对角化，则 $\mathbf{A}$ 与 $\pmb{B}$ 不相似.

（7）【答案】 （A）.

【解】由 $P(A|B) > P(A|\overline{B})$ 得 $\frac{P(AB)}{P(B)} >\frac{P(A\overline{B})}{P(\overline{B})} = \frac{P(A) - P(AB)}{1 - P(B)}$

$P(A|B) > P(A|\overline{B})$ 等价于 $P(AB) > P(A)P(B)$

由 $P(B|A) > P(B|\overline{A})$ 得 $\frac{P(AB)}{P(A)} >\frac{P(B) - P(AB)}{1 - P(A)}$

$P(B|A) > P(B|\overline{A})$ 等价于 $P(AB) > P(A)P(B)$ ，应选（A）.

(8)【答案】 (B).

【解】 若总体 $X \sim N(\mu, \sigma^2)$ ，则

$$
\frac {1}{\sigma^ {2}} \sum_ {i = 1} ^ {n} (X _ {i} - \mu) ^ {2} \sim \chi^ {2} (n), \quad \frac {1}{\sigma^ {2}} \sum_ {i = 1} ^ {n} (X _ {i} - \overline {{X}}) ^ {2} \sim \chi^ {2} (n - 1),
$$

因为总体 $X \sim N(\mu, 1)$ ，所以 $\sum_{i=1}^{n}(X_i - \mu)^2 \sim \chi^2(n)$ ， $\sum_{i=1}^{n}(X_i - \overline{X})^2 \sim \chi^2(n-1)$

再由 $\overline{X} \sim N\left(\mu, \frac{1}{n}\right)$ 得 $\frac{\overline{X} - \mu}{\frac{1}{\sqrt{n}}} = \sqrt{n} (\overline{X} - \mu) \sim N(0, 1)$ ，从而 $n(\overline{X} - \mu)^2 \sim \chi^2(1)$ ，

不正确的是(B)，应选(B).

# 二、填空题

（9）【答案】0.

【解】方法一 $f(x) = \frac{1}{1 + x^2} = 1 - x^2 +x^4 -x^6 +x^8 +o(x^8),$

由 $\frac{f^{(3)}(0)}{3!} = 0$ 得 $f^{(3)}(0) = 0$ .

方法二 根据求导改变奇偶性的性质，因为 $f(x)$ 为偶函数，所以 $f^{(3)}(x)$ 为奇函数，故 $f^{(3)}(0) = 0$

(10)【答案】 $\mathrm{e}^{-x}(C_1\cos \sqrt{2} x + C_2\sin \sqrt{2} x)(C_1,C_2$ 为任意常数).

【解】 特征方程为 $\lambda^2 + 2\lambda + 3 = 0$ ，特征值为 $\lambda_{1,2} = -1 \pm \sqrt{2}\mathrm{i}$ ，

通解为 $y = \mathrm{e}^{-x}(C_1\cos \sqrt{2} x + C_2\sin \sqrt{2} x)(C_1,C_2$ 为任意常数).

（11）【答案】 -1.

【解】 $P = \frac{x}{x^2 + y^2 - 1},\quad Q = -\frac{ay}{x^2 + y^2 - 1},$

$$
\frac {\partial P}{\partial y} = - \frac {2 x y}{\left(x ^ {2} + y ^ {2} - 1\right) ^ {2}}, \quad \frac {\partial Q}{\partial x} = \frac {2 a x y}{\left(x ^ {2} + y ^ {2} - 1\right) ^ {2}},
$$

因为曲线积分与路径无关，所以 $\frac{\partial Q}{\partial x} = \frac{\partial P}{\partial y}$ 故 $a = -1$

(12)【答案】 $\frac{1}{(1 + x)^2}$ .

【解】方法一 $S(x) = \sum_{n=1}^{\infty} (-1)^{n-1} n x^{n-1} = -\left[\sum_{n=1}^{\infty} (-1)^{n} x^{n}\right]' = -\left(\frac{-x}{1+x}\right)' = \frac{1}{(1+x)^{2}}.$

方法二 令 $S(x) = \sum_{n=1}^{\infty} (-1)^{n-1} n x^{n-1}$ ,

则 $\int_0^x S(x)\mathrm{d}x = \sum_{n = 1}^\infty \int_0^x (-1)^{n - 1}nx^{n - 1}\mathrm{d}x = \sum_{n = 1}^\infty (-1)^{n - 1}x^n$

$$
= - \sum_ {n = 1} ^ {\infty} (- x) ^ {n} = - \frac {- x}{1 + x} = \frac {x}{1 + x},
$$

故 $S(x) = \left(\frac{x}{1 + x}\right)' = \frac{1}{(1 + x)^2}.$

（13）【答案】2.

【解】 $(A\alpha_{1}, A\alpha_{2}, A\alpha_{3}) = A(\alpha_{1}, \alpha_{2}, \alpha_{3})$

因为 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性无关，所以 $(\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3})$ 可逆，从而 $r(A\pmb{\alpha}_1,A\pmb{\alpha}_2,A\pmb{\alpha}_3) = r(\pmb {A})$

由 $\mathbf{A}\rightarrow \left( \begin{array}{lll}1 & 0 & 1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $r(\mathbf{A}) = 2$ ，故向量组 $A\pmb{\alpha}_{1},A\pmb{\alpha}_{2},A\pmb{\alpha}_{3}$ 的秩为2.

（14）【答案】2.

【解】 $X$ 的密度为 $f(x) = 0.5\varphi (x) + 0.25\varphi \left(\frac{x - 4}{2}\right)$

$$
\begin{array}{l} E (X) = \int_ {- \infty} ^ {+ \infty} x f (x) d x = 0. 5 \int_ {- \infty} ^ {+ \infty} x \varphi (x) d x + 0. 2 5 \int_ {- \infty} ^ {+ \infty} x \varphi \left(\frac {x - 4}{2}\right) d x \\ = 0 + \int_ {- \infty} ^ {+ \infty} \left(\frac {x - 4}{2} + 2\right) \varphi \left(\frac {x - 4}{2}\right) \mathrm {d} \left(\frac {x - 4}{2}\right) \\ = \int_ {- \infty} ^ {+ \infty} (x + 2) \varphi (x) d x = 2 \int_ {- \infty} ^ {+ \infty} \varphi (x) d x = 2. \\ \end{array}
$$

方法点评：本题考查连续型随机变量的分布函数、密度函数及数字特征，需要注意以下几点：

（1）若随机变量的分布函数为 $F(x)$ ，则其密度函数为

$$
f (x) = \left\{ \begin{array}{l l} F ^ {\prime} (x), & x \text {为} F (x) \text {的 可 导 点 ,} \\ 0, & x \text {为} F (x) \text {的 不 可 导 点 .} \end{array} \right.
$$

(2) 若 $f(x)$ 为随机变量的密度函数, 则 $\int_{-\infty}^{+\infty} f(x) \mathrm{d}x = 1$ .

（3）标准正态分布的密度函数 $\varphi (x)$ 为奇函数，即 $\int_{-\infty}^{+\infty}x^k\varphi (x)\mathrm{d}x = 0(k$ 为正奇数).

# 三、解答题

(15)【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \mathrm{e}^{x}f_{1}^{\prime} - \sin x\cdot f_{2}^{\prime},\quad \frac{\mathrm{dy}}{\mathrm{dx}}\bigg|_{x = 0} = f_{1}^{\prime}(1,1);$

$$
\frac {\mathrm {d} ^ {2} y}{\mathrm {d} x ^ {2}} = \mathrm {e} ^ {x} f _ {1} ^ {\prime} + \mathrm {e} ^ {x} \left(\mathrm {e} ^ {x} f _ {1 1} ^ {\prime \prime} - \sin x \cdot f _ {1 2} ^ {\prime \prime}\right) - \cos x \cdot f _ {2} ^ {\prime} - \sin x \left(\mathrm {e} ^ {x} f _ {2 1} ^ {\prime \prime} - \sin x \cdot f _ {2 2} ^ {\prime \prime}\right),
$$

则 $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\Big|_{x = 0} = f_1'(1,1) + f_{11}''(1,1) - f_2'(1,1).$

(16)【解】 $\lim_{n\to \infty}\sum_{k = 1}^{n}\frac{k}{n^2}\ln \left(1 + \frac{k}{n}\right) = \lim_{n\to \infty}\frac{1}{n}\sum_{k = 1}^{n}\frac{k}{n}\ln \left(1 + \frac{k}{n}\right) = \int_0^1 x\ln (1 + x)\mathrm{d}x$

$$
\begin{array}{l} = \frac {1}{2} \int_ {0} ^ {1} \ln (1 + x) d \left(x ^ {2}\right) = \frac {1}{2} x ^ {2} \ln (1 + x) \Big | _ {0} ^ {1} - \frac {1}{2} \int_ {0} ^ {1} \frac {\left(x ^ {2} - 1\right) + 1}{1 + x} d x \\ = \frac {1}{2} \ln 2 - \frac {1}{2} \int_ {0} ^ {1} (x - 1 + \frac {1}{1 + x}) d x = \frac {1}{2} \ln 2 - \frac {1}{4} + \frac {1}{2} - \frac {1}{2} \ln 2 = \frac {1}{4}. \\ \end{array}
$$

方法点评：本题考查定积分的定义求极限

$n$ 项和求极限一般分为两种类型：

(1) 分子次数齐、分母次数齐，且分母的次数高于分子一次，采用定积分定义求极限，即

$$
\lim  _ {n \rightarrow \infty} \frac {1}{n} \sum_ {k = 1} ^ {n} f \left(\frac {k}{n}\right) = \int_ {0} ^ {1} f (x) d x.
$$

（2）若分子次数或分母次数不齐，一般使用迫敛定理

(17)【解】 $x^{3} + y^{3} - 3x + 3y - 2 = 0$ 两边对 $x$ 求导得 $3x^{2} + 3y^{2}y^{\prime} - 3 + 3y^{\prime} = 0$

令 $y^\prime = 0$ 得 $x_{1} = -1,x_{2} = 1$ ，对应的函数值为 $y_{1} = 0,y_{2} = 1$

$3x^{2} + 3y^{2}y^{\prime} - 3 + 3y^{\prime} = 0$ 两边再对 $x$ 求导得 $6x + 6yy^{\prime 2} + 3y^{2}y^{\prime \prime} + 3y^{\prime \prime} = 0$

由 $y^{\prime \prime}(-1) = 2 > 0$ 得 $x = -1$ 为极小值点，极小值为 $y = 0$

由 $y''(1) = -1 < 0$ 得 $x = 1$ 为极大值点，极大值为 $y = 1$

（18）【证明】（I）根据极限保号性，因为 $\lim_{x\to 0^{+}}\frac{f(x)}{x} < 0$ ，所以存在 $\delta >0$

当 $x \in (0, \delta)$ 时， $\frac{f(x)}{x} < 0$ ，即当 $x \in (0, \delta)$ 时 $f(x) < 0$

于是存在 $c \in (0, \delta)$ ，使得 $f(c) < 0$

因为 $f(c)f(1) < 0$ ，所以存在 $x_0 \in (c,1) \subset (0,1)$ ，使得 $f(x_0) = 0$

（Ⅱ）令 $F(x) = f(x)f'(x)$ ，则 $F'(x) = f(x)f''(x) + f'^2(x)$ ，

由 $f(0) = f(c) = 0$ ，得存在 $x\in (0,c)$ ，使得 $f^{\prime}(\xi_{1}) = 0$

因 $f(0) = f(c) = 0$ ，所以 $F(0) = F(\xi_1) = F(c)$

由罗尔定理，存在 $\eta_1\in (0,\xi_1)$ ，存在 $\eta_{2}\in (\xi_{1},c)$ ，使 $F^{\prime}(\eta_{1}) = 0,F^{\prime}(\eta_{2}) = 0$

即方程 $f(x)f''(x) + f'^2(x) = 0$ 在 $(0,1)$ 内至少有两个不同的实根.

（19）【解】（I）由 $\left\{ \begin{array}{l} z = \sqrt{x^2 + y^2}, \\ z^2 = 2x, \end{array} \right.$ 得 $x^2 + y^2 = 2x$

故 $C$ 在 $xOy$ 平面上的投影曲线为 $L:\left\{ \begin{array}{l}(x - 1)^2 +y^2 = 1,\\ z = 0, \end{array} \right.$

（Ⅱ） $M = \iint_{S} 9\sqrt{x^2 + y^2 + z^2} \, \mathrm{d}S$

由 $z_{x}^{\prime} = \frac{x}{\sqrt{x^{2} + y^{2}}}, z_{y}^{\prime} = \frac{y}{\sqrt{x^{2} + y^{2}}}$ 得 $\mathrm{d}S = \sqrt{1 + z_{x}^{\prime 2} + z_{y}^{\prime 2}}\mathrm{d}x\mathrm{d}y = \sqrt{2}\mathrm{d}x\mathrm{d}y,$

则 $M = \iint_{S} 9\sqrt{x^2 + y^2 + z^2} \, \mathrm{d}S = 9\sqrt{2} \iint_{D} \sqrt{x^2 + y^2} \cdot \sqrt{2} \, \mathrm{d}x \, \mathrm{d}y$

$$
\begin{array}{l} = 1 8 \iint_ {D} \sqrt {x ^ {2} + y ^ {2}} d x d y = 1 8 \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} d \theta \int_ {0} ^ {2 \cos \theta} r ^ {2} d r \\ = 1 8 \times \frac {8}{3} \int_ {- \frac {\pi}{2}} ^ {\frac {\pi}{2}} \cos^ {3} \theta d \theta = 1 8 \times \frac {1 6}{3} \int_ {0} ^ {\frac {\pi}{2}} \cos^ {3} \theta d \theta = 6 4. \\ \end{array}
$$

（20）【证明】（I）设 $\mathbf{A}$ 的特征值为 $\lambda_1, \lambda_2, \lambda_3$

因为 $\mathbf{A}$ 有三个不同的特征值，所以 $\mathbf{A}$ 可以相似对角化，即存在可逆矩阵 $\pmb{P}$ ，使得

$$
\boldsymbol {P} ^ {- 1} \boldsymbol {A} \boldsymbol {P} = \left( \begin{array}{c c c} \lambda_ {1} & & \\ & \lambda_ {2} & \\ & & \lambda_ {3} \end{array} \right),
$$

因为 $\lambda_1, \lambda_2, \lambda_3$ 两两不同，所以 $r(A) \geqslant 2$

又因为 $\pmb{\alpha}_{3} = \pmb{\alpha}_{1} + 2\pmb{\alpha}_{2}$ ，所以 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性相关，从而 $r(A) <   3$ ，于是 $r(A) = 2$

（Ⅱ）因为 $r(\mathbf{A}) = 2$ ，所以 $\mathbf{AX} = \mathbf{0}$ 基础解系含一个线性无关的解向量，

由 $\left\{ \begin{array}{l} \alpha_{1} + 2\alpha_{2} - \alpha_{3} = 0, \\ \alpha_{1} + \alpha_{2} + \alpha_{3} = \beta, \end{array} \right.$ 得 $AX = \beta$ 的通解为

$X = k\binom{1}{2} + \binom{1}{1}$ （ $k$ 为任意常数）.

(21)【解】 $\mathbf{A} = \left( \begin{array}{rrr}2 & 1 & -4\\ 1 & -1 & 1\\ -4 & 1 & a \end{array} \right),\quad \mathbf{X} = \left( \begin{array}{l}x_{1}\\ x_{2}\\ x_{3} \end{array} \right),\quad f(x_{1},x_{2},x_{3}) = \mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X},$

因为 $\lambda_3 = 0$ ，所以 $|\mathbf{A}| = 0$

由 $|\mathbf{A}| = \left| \begin{array}{ccc}2 & 1 & -4\\ 1 & -1 & 1\\ -4 & 1 & a \end{array} \right| = -3(a - 2) = 0$ ，得 $a = 2$

由 $|\lambda E - A| = \left| \begin{array}{ccc}\lambda -2 & -1 & 4\\ -1 & \lambda +1 & -1\\ 4 & -1 & \lambda -2 \end{array} \right| = \lambda (\lambda +3)(\lambda -6) = 0$ ，得 $\lambda_{1} = -3,\lambda_{2} = 6,\lambda_{3} = 0.$

由 $-3\pmb {E} - \pmb {A}\rightarrow \left( \begin{array}{rrr}5 & 1 & -4\\ 1 & 2 & 1\\ -4 & 1 & 5 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & -1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得

$\lambda_{1} = -3$ 对应的线性无关的特征向量为 $\pmb{\alpha}_{1} = \begin{pmatrix} 1 \\ -1 \\ 1 \end{pmatrix}$ ;

由 $6\pmb {E} - \pmb {A} = \left( \begin{array}{rrr}4 & -1 & 4\\ -1 & 7 & -1\\ 4 & -1 & 4 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & 1\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得

$\lambda_{2} = 6$ 对应的线性无关的特征向量为 $\pmb{\alpha}_{2} = \begin{pmatrix} -1 \\ 0 \\ 1 \end{pmatrix}$ ;

由 $0E - A \rightarrow \left( \begin{array}{ccc}1 & 0 & -1\\ 0 & 1 & -2\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_{3} = 0$ 对应的线性无关的特征向量为 $\pmb{\alpha}_{3} = \binom{1}{2}$ .

规范化得 $\gamma_{1} = \frac{1}{\sqrt{3}}\binom{1}{-1}$ ， $\gamma_{2} = \frac{1}{\sqrt{2}}\binom{-1}{0}$ ， $\gamma_{3} = \frac{1}{\sqrt{6}}\binom{1}{2}$ ，

故正交矩阵为 $Q = \left[ \begin{array}{ccc} \frac{1}{\sqrt{3}} & -\frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} \\ -\frac{1}{\sqrt{3}} & 0 & \frac{2}{\sqrt{6}} \\ \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} \end{array} \right]$

$$
f \left(x _ {1}, x _ {2}, x _ {3}\right) = \boldsymbol {X} ^ {\mathrm {T}} \boldsymbol {A} \boldsymbol {X} \xlongequal {\boldsymbol {X} = Q \boldsymbol {Y}} - 3 y _ {1} ^ {2} + 6 y _ {2} ^ {2}.
$$

(22)【解】 $(\mathrm{I})E(Y) = \int_{0}^{1}y\cdot 2y\mathrm{d}y = \frac{2}{3},$

$$
P \left\{Y \leqslant E (Y) \right\} = P \left\{Y \leqslant \frac {2}{3} \right\} = \int_ {0} ^ {\frac {2}{3}} 2 y \mathrm {d} y = \frac {4}{9}.
$$

（Ⅱ）方法一 $F_{Z}(z) = P\{Z \leqslant z\} = P\{X + Y \leqslant z\}$ ，

当 $z < 0$ 时， $F_{Z}(z) = 0$

当 $z \geq 3$ 时， $F_Z(z) = 1$

当 $0 \leqslant z < 1$ 时， $F_Z(z) = P\{X = 0, Y \leqslant z\} = P\{X = 0, Y \leqslant z\}$

$$
= P \{X = 0 \} P \{Y \leqslant z \} = \frac {1}{2} \int_ {0} ^ {z} 2 y \mathrm {d} y = \frac {z ^ {2}}{2};
$$

当 $1 \leqslant z < 2$ 时， $F_{Z}(z) = P\{X = 0, Y \leqslant z\} = P\{X = 0\} P\{Y \leqslant 1\} = \frac{1}{2}$

当 $2 \leqslant z < 3$ 时， $F_{Z}(z) = P\{X = 0, Y \leqslant z\} + P\{X = 2, Z \leqslant z - 2\}$

$$
\begin{array}{l} = P \{X = 0 \} P \{Y \leqslant 1 \} + P \{X = 2 \} P \{Y \leqslant z - 2 \} \\ = \frac {1}{2} + \frac {1}{2} \int_ {0} ^ {z - 2} 2 y d y = \frac {1}{2} + \frac {1}{2} (z - 2) ^ {2}, \\ \end{array}
$$

即 $F_{Z}(z) = \left\{ \begin{array}{ll}0, & z <   0,\\ \frac{z^{2}}{2}, & 0\leqslant z <   1,\\ \frac{1}{2} +\frac{1}{2} (z - 2)^{2}, & 2\leqslant z <   3,\\ 1, & z\geqslant 3, \end{array} \right.$

概率密度为 $f_{Z}(z) = \left\{ \begin{array}{ll} z, & 0 < z < 1, \\ z - 2, & 2 < z < 3, \\ 0, & \text{其他}. \end{array} \right.$

方法二 由全概率公式得

$$
\begin{array}{l} F _ {Z} (z) = P \{Z \leqslant z \} = P \{X + Y \leqslant z \} \\ = P \{X = 0 \} P \{X + Y \leqslant z \mid X = 0 \} + P \{X = 2 \} P \{X + Y \leqslant z \mid X = 2 \} \\ = \frac {1}{2} P \{Y \leqslant z \} + \frac {1}{2} P \{Y \leqslant z - 2 \}, \\ \end{array}
$$

当 $z < 0$ 时， $F_{Z}(z) = 0$

当 $0 \leqslant z < 1$ 时， $F_{Z}(z) = \frac{1}{2} P\{Y \leqslant z\} = \frac{1}{2} \int_{0}^{z} 2y \, \mathrm{d}y = \frac{z^2}{2}$

当 $1 \leqslant z < 2$ 时， $F_{Z}(z) = \frac{1}{2} P\{Y \leqslant 1\} = \frac{1}{2}$

当 $2 \leqslant z < 3$ 时， $F_{Z}(z) = \frac{1}{2} + \frac{1}{2} P\{Y \leqslant z - 2\}$

$$
= \frac {1}{2} + \frac {1}{2} \int_ {0} ^ {z - 2} 2 y d y = \frac {1}{2} + \frac {(z - 2) ^ {2}}{2};
$$

当 $z \geqslant 3$ 时， $F_Z(z) = 1$

故 $f_{Z}(z) = F^{\prime}(z) = \left\{ \begin{array}{ll}z, & 0 <   z <   1,\\ z - 2, & 2 <   z <   3,\\ 0, & \text{其他}. \end{array} \right.$

(23)【解】（I）由 $X_{1} \sim N(\mu, \sigma^{2})$ 得 $\frac{X_{1} - \mu}{\sigma} \sim N(0, 1)$ ，

$Z_{1}$ 的分布函数为 $F(z) = P\{Z_1\leqslant z\}$

当 $z < 0$ 时， $F(z) = 0$

当 $z \geqslant 0$ 时， $F(z) = P\left\{\left|\frac{X_1 - \mu}{\sigma}\right| \leqslant \frac{z}{\sigma}\right\} = \Phi\left(\frac{z}{\sigma}\right) - \Phi\left(-\frac{z}{\sigma}\right) = 2\Phi\left(\frac{z}{\sigma}\right) - 1,$

$$
F (z) = \left\{ \begin{array}{l l} 0, & z <   0, \\ 2 \Phi \left(\frac {z}{\sigma}\right) - 1, & z \geqslant 0, \end{array} \right.
$$

$Z_{1}$ 的密度函数为 $f(z) = \left\{ \begin{array}{ll}0, & z\leqslant 0,\\ \frac{2}{\sigma}\varphi \left(\frac{z}{\sigma}\right), & z > 0. \end{array} \right.$

$(\mathrm{II})E(Z) = E(|X_i - \mu |) = E(|X_1 - \mu |)$

$$
\begin{array}{l} = \int_ {0} ^ {+ \infty} z \cdot \frac {2}{\sigma} \varphi (\frac {z}{\sigma}) d z = 2 \sigma \int_ {0} ^ {+ \infty} \frac {z}{\sigma} \varphi (\frac {z}{\sigma}) d \left(\frac {z}{\sigma}\right) \\ = 2 \sigma \int_ {0} ^ {+ \infty} t \varphi (t) d t = \frac {2 \sigma}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} t e ^ {- \frac {t ^ {2}}{2}} d t = \frac {2 \sigma}{\sqrt {2 \pi}} \int_ {0} ^ {+ \infty} e ^ {- \frac {t ^ {2}}{2}} d \left(\frac {t ^ {2}}{2}\right) = \frac {2 \sigma}{\sqrt {2 \pi}}, \\ \end{array}
$$

由 $\frac{2\sigma}{\sqrt{2\pi}} = \frac{1}{n}\sum_{i = 1}^{n}Z_{i} = \overline{Z}$ ，得 $\sigma$ 的矩估计量为 $\hat{\sigma} = \sqrt{\frac{\pi}{2}}\overline{Z}$

（Ⅲ）似然函数为

$$
L = f \left(z _ {1}\right) \dots f \left(z _ {n}\right) = \frac {2 ^ {n}}{\sigma^ {n}} \cdot \left(\frac {1}{\sqrt {2 \pi}}\right) ^ {n} \cdot e ^ {- \frac {1}{2 \sigma^ {2}} \left(z _ {1} ^ {2} + \dots + z _ {n} ^ {2}\right)} \left(z _ {i} > 0, i = 1, 2, \dots , n\right),
$$

$$
\ln L = n \ln 2 - n \ln \sigma - n \ln \sqrt {2 \pi} - \frac {1}{2 \sigma^ {2}} \left(z _ {1} ^ {2} + \dots + z _ {n} ^ {2}\right),
$$

由 $\frac{\mathrm{d}}{\mathrm{d}\sigma}\ln L = -\frac{n}{\sigma} +\frac{1}{\sigma^3} (z_1^2 +\dots +z_n^2) = 0$ 得 $\hat{\sigma} = \sqrt{\frac{1}{n}\sum_{i = 1}^{n}z_i^2},$

故 $\sigma$ 的最大似然估计量为 $\hat{\sigma} = \sqrt{\frac{1}{n}\sum_{i = 1}^{n}Z_i^2}$