# 2021年数学(一）真题解析

# 一、选择题

（1）【答案】 (D).

【解】 由 $\lim_{x\to 0}f(x) = \lim_{x\to 0}\frac{\mathrm{e}^x - 1}{x} = 1 = f(0)$ 得 $f(x)$ 在 $x = 0$ 处连续；

再由 $\lim_{x\to 0}\frac{f(x) - f(0)}{x} = \lim_{x\to 0}\frac{\frac{\mathrm{e}^x - 1}{x} - 1}{x} = \lim_{x\to 0}\frac{\mathrm{e}^x - 1 - x}{x^2} = \lim_{x\to 0}\frac{\mathrm{e}^x - 1}{2x} = \frac{1}{2}$ 得

$f^{\prime}(0) = \frac{1}{2}\neq 0$ ，应选(D).

（2）【答案】 (C).

【解】 $f(x + 1, \mathrm{e}^x) = x(x + 1)^2$ 两边对 $x$ 求导得

$$
f _ {1} ^ {\prime} (x + 1, \mathrm {e} ^ {x}) + \mathrm {e} ^ {x} f _ {2} ^ {\prime} (x + 1, \mathrm {e} ^ {x}) = (x + 1) ^ {2} + 2 x (x + 1),
$$

取 $x = 0$ 得 $f_{1}^{\prime}(1,1) + f_{2}^{\prime}(1,1) = 1$

$f(x,x^{2}) = 2x^{2}\ln x$ 两边对 $x$ 求导得

$$
f _ {1} ^ {\prime} (x, x ^ {2}) + 2 x f _ {2} ^ {\prime} (x, x ^ {2}) = 4 x \ln x + 2 x,
$$

取 $x = 1$ 得 $f_{1}^{\prime}(1,1) + 2f_{2}^{\prime}(1,1) = 2$

解得 $f_{1}^{\prime}(1,1) = 0, f_{2}^{\prime}(1,1) = 1$ ，故 $\mathrm{d}f(1,1) = \mathrm{d}y$ ，应选(C).

（3）【答案】 （A）.

【解】因为 $f(x) = \frac{\sin x}{1 + x^2}$ 为奇函数，所以 $b = 0$

由 $\sin x = x - \frac{x^3}{6} + o(x^3), \frac{1}{1 + x^2} = 1 - x^2 + o(x^3)$ 得

$$
f (x) = \frac {\sin x}{1 + x ^ {2}} = x - \frac {7}{6} x ^ {3} + o \left(x ^ {3}\right),
$$

应选（A）.

（4）【答案】 （B）.

【解】 $\lim_{n\to \infty}\sum_{k = 1}^{n}f\left(\frac{2k - 1}{2n}\right)\frac{1}{n} = \lim_{n\to \infty}\sum_{k = 1}^{n}f\left(\frac{2k}{2n}\right)\frac{1}{n} = \lim_{n\to \infty}\frac{1}{n}\sum_{k = 1}^{n}f\left(\frac{k}{n}\right) = \int_{0}^{1}f(x)\mathrm{d}x$ ，应选(B).（5）【答案】 (B).

【解】 令 $\mathbf{A} = \begin{pmatrix} 0 & 1 & 1\\ 1 & 2 & 1\\ 1 & 1 & 0 \end{pmatrix} ,\mathbf{X} = \begin{pmatrix} x_{1}\\ x_{2}\\ x_{3} \end{pmatrix}$ ，则 $f = X^{\mathrm{T}}AX$

由 $|\lambda \pmb {E} - \pmb {A}| = \left| \begin{array}{rrr}\lambda & -1 & -1\\ -1 & \lambda -2 & -1\\ -1 & -1 & \lambda \end{array} \right| = (\lambda +1)\left| \begin{array}{rrr}1 & 0 & 0\\ -1 & \lambda -2 & -2\\ -1 & -1 & \lambda -1 \end{array} \right|$

$$
= (\lambda + 1) \left(\lambda^ {2} - 3 \lambda\right) = 0
$$

得 $\lambda_{1} = -1, \lambda_{2} = 0, \lambda_{3} = 3$ ，应选（B）.

（6）【答案】 （A）.

【解】由施密特正交化得 $l_{1} = \frac{(\pmb{\alpha}_{3},\pmb{\beta}_{1})}{(\pmb{\beta}_{1},\pmb{\beta}_{1})} = \frac{5}{2}, l_{2} = \frac{(\pmb{\alpha}_{3},\pmb{\beta}_{2})}{(\pmb{\beta}_{2},\pmb{\beta}_{2})} = \frac{2}{4} = \frac{1}{2}$ 应选(A).

方法点评：将线性无关的向量组化为两两正交的规范向量组即施密特正交规范化，实对称矩阵的对角化的正交变换法需要将线性无关的特征向量进行正交化和单位化.设 $\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}$ 线性无关， $\pmb {\beta}_1 = \pmb {\alpha}_1,\pmb {\beta}_2 = \pmb {\alpha}_2 - l_1\pmb {\beta}_1,\pmb {\beta}_3 = \pmb {\alpha}_3 - k_1\pmb {\beta}_1 - k_2\pmb {\beta}_2$ ，且 $\pmb {\beta}_1,\pmb {\beta}_2,\pmb {\beta}_3$ 线性无关，则 $l_{1} = \frac{(\pmb{\alpha}_{2},\pmb{\beta}_{1})}{(\pmb{\beta}_{1},\pmb{\beta}_{1})},k_{1} = \frac{(\pmb{\alpha}_{3},\pmb{\beta}_{1})}{(\pmb{\beta}_{1},\pmb{\beta}_{1})},k_{2} = \frac{(\pmb{\alpha}_{3},\pmb{\beta}_{2})}{(\pmb{\beta}_{2},\pmb{\beta}_{2})}.$

（7）【答案】 (C).

【解】 $r\begin{pmatrix} \mathbf{A} & \mathbf{O}\\ \mathbf{O} & \mathbf{A}^{\mathrm{T}}\mathbf{A} \end{pmatrix} = r(\mathbf{A}) + r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = 2r(\mathbf{A});$

由 $\left( \begin{array}{ll}A & AB\\ O & A^{\mathrm{T}} \end{array} \right)\xrightarrow{\text{列}}\left( \begin{array}{ll}A & O\\ O & A^{\mathrm{T}} \end{array} \right)$ 得 $r\left( \begin{array}{ll}A & AB\\ O & A^{\mathrm{T}} \end{array} \right) = 2r(A)$

由 $r\left(\begin{array}{cc}\mathbf{A}&\mathbf{O}\\ \mathbf{B}\mathbf{A}&\mathbf{A}^{\mathrm{T}}\end{array}\right)\xrightarrow{\text{行}}r\left(\begin{array}{cc}\mathbf{A}&\mathbf{O}\\ \mathbf{O}&\mathbf{A}^{\mathrm{T}}\end{array}\right)$ 得 $r\left(\begin{array}{cc}\mathbf{A}&\mathbf{O}\\ \mathbf{B}\mathbf{A}&\mathbf{A}^{\mathrm{T}}\end{array}\right)=2r(\mathbf{A})$ ，应选(C).

（8）【答案】 (D).

【解】由 $P(A\mid B) = P(A)$ 得 $P(AB) = P(A)P(B)$ ，即事件 $A,B$ 独立，

于是 $P(A|\overline{B}) = \frac{P(A\overline{B})}{P(\overline{B})} = \frac{P(A)P(\overline{B})}{P(\overline{B})} = P(A)$

由 $P(A\mid B) > P(A)$ 得 $P(AB) > P(A)P(B)$

从而 $P(\overline{A}|\overline{B}) = \frac{P(\overline{A}\overline{B})}{P(\overline{B})} = \frac{1 - P(A) - P(B) + P(AB)}{1 - P(B)}$

$$
> \frac {1 - P (A) - P (B) + P (A) P (B)}{1 - P (B)} = 1 - P (A) = P (\overline {{A}});
$$

由 $P(A|B) > P(A|\overline{B})$ 得 $\frac{P(AB)}{P(B)} >\frac{P(A) - P(AB)}{1 - P(B)}$ 整理得 $P(AB) > P(A)P(B)$ 则 $P(A|B) = \frac{P(AB)}{P(B)} >\frac{P(A)P(B)}{P(B)} = P(A)$ ，应选(D).

（9）【答案】 (C).

【解】 $\overline{X} \sim N\left(\mu_1, \frac{\sigma_1^2}{n}\right), \overline{Y} \sim N\left(\mu_2, \frac{\sigma_2^2}{n}\right)$

则 $E(\hat{\theta}) = E(\overline{X}) - E(\overline{Y}) = \mu_1 - \mu_2 = \theta$

$$
\begin{array}{l} D (\hat {\theta}) = D (\bar {X} - \bar {Y}) = D (\bar {X}) + D (\bar {Y}) - 2 \operatorname {C o v} (\bar {X}, \bar {Y}) \\ = \frac {\sigma_ {1} ^ {2}}{n} + \frac {\sigma_ {2} ^ {2}}{n} - \frac {2}{n} \left[ \operatorname {C o v} \left(X _ {1}, \bar {Y}\right) + \operatorname {C o v} \left(X _ {2}, \bar {Y}\right) + \dots + \operatorname {C o v} \left(X _ {n}, \bar {Y}\right) \right] \\ = \frac {\sigma_ {1} ^ {2}}{n} + \frac {\sigma_ {2} ^ {2}}{n} - \frac {2}{n ^ {2}} \left[ \operatorname {C o v} \left(X _ {1}, Y _ {1}\right) + \operatorname {C o v} \left(X _ {2}, Y _ {2}\right) + \dots + \operatorname {C o v} \left(X _ {n}, Y _ {n}\right) \right] \\ = \frac {\sigma_ {1} ^ {2}}{n} + \frac {\sigma_ {2} ^ {2}}{n} - \frac {2}{n ^ {2}} \cdot n \rho \sigma_ {1} \sigma_ {2} = \frac {\sigma_ {1} ^ {2} + \sigma_ {2} ^ {2} - 2 \rho \sigma_ {1} \sigma_ {2}}{n}, \text {应 选 (C)}. \\ \end{array}
$$

（10）【答案】 (B).

【解】由题 $\overline{X}\sim N\left(11.5,\frac{1}{4}\right)$ ，或 $\frac{\overline{X} - 11.5}{\frac{1}{2}}\sim N(0,1),$

犯第二类错误的概率为

$$
P \{\overline {{X}} <   1 1 \} = P \left\{\frac {\overline {{X}} - 1 1 . 5}{\frac {1}{2}} <   - 1 \right\} = \Phi (- 1) = 1 - \Phi (1),
$$

应选（B）.

# 二、填空题

(11)【答案】 $\frac{\pi}{4}$ .

【解】 $\int_{0}^{+\infty}\frac{\mathrm{d}x}{x^2 + 2x + 2} = \int_{0}^{+\infty}\frac{\mathrm{d}(x + 1)}{1 + (x + 1)^2} = \arctan (x + 1)\mid_{0}^{+\infty} = \frac{\pi}{2} -\frac{\pi}{4} = \frac{\pi}{4}.$

(12)【答案】 $\frac{2}{3}$ .

【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\mathrm{dy} / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = \frac{4te^{t} + 2t}{2e^{t} + 1} = 2t, \frac{\mathrm{d}^2y}{\mathrm{dx}^2} = \frac{\mathrm{d}(2t) / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = \frac{2}{2e^{t} + 1},$

则 $\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\bigg|_{t = 0} = \frac{2}{3}.$

（13）【答案】 $x^{2}$

【解】 令 $x = \mathrm{e}^{t},D = \frac{\mathrm{d}}{\mathrm{d}t}$ ，则

$$
x y ^ {\prime} = D y, x ^ {2} y ^ {\prime \prime} = D (D - 1) y,
$$

代入欧拉方程得

$$
\frac {\mathrm {d} ^ {2} y}{\mathrm {d} t ^ {2}} - 4 y = 0,
$$

特征方程为 $\lambda^2 - 4 = 0$ ，特征根为 $\lambda_1 = -2, \lambda_2 = 2$

$\frac{\mathrm{d}^2y}{\mathrm{d}t^2} - 4y = 0$ 的通解为 $y = C_1\mathrm{e}^{-2t} + C_2\mathrm{e}^{2t}$ ，原方程的通解为

$$
y = \frac {C _ {1}}{x ^ {2}} + C _ {2} x ^ {2},
$$

由 $y(1) = 1, y'(1) = 2$ 得 $C_1 + C_2 = 1, -2C_1 + 2C_2 = 2$ ，解得 $C_1 = 0, C_2 = 1$ ，故 $y = x^2$ .

方法点评：形如

$$
x ^ {n} y ^ {(n)} + a _ {n - 1} x ^ {n - 1} y ^ {(n - 1)} + \dots + a _ {1} x y ^ {\prime} + a _ {0} y = f (x)
$$

的方程称为欧拉方程.

令 $x = \mathrm{e}^{t}$ ，则 $xy^{\prime} = Dy = \frac{\mathrm{dy}}{\mathrm{dt}},x^{2}y^{\prime \prime} = D(D - 1)y = \frac{\mathrm{d}^{2}y}{\mathrm{d}t^{2}} -\frac{\mathrm{dy}}{\mathrm{dt}},$

$$
x ^ {n} y ^ {(n)} = D (D - 1) \dots (D - n + 1) y,
$$

代入原方程得高阶常系数线性微分方程，求出其通解，再将 $t = \ln x$ 代入即可得原方程的通解.

（14）【答案】 $4\pi$

【解】设 $\Sigma$ 所围成的几何体为 $\Omega$ ，由高斯公式得

$$
I = \iint_ {\Sigma} x ^ {2} \mathrm {d} y \mathrm {d} z + y ^ {2} \mathrm {d} z \mathrm {d} x + z \mathrm {d} x \mathrm {d} y = \iiint_ {\Omega} (2 x + 2 y + 1) \mathrm {d} v,
$$

由积分的奇偶性得

$$
I = \iiint_ {\Omega} \mathrm {d} v = 2 \iint_ {D _ {x y}} \mathrm {d} x \mathrm {d} y = 2 \cdot \pi \cdot 1 \cdot 2 = 4 \pi .
$$

(15)【答案】 $\frac{3}{2}$ .

【解】 $|\mathbf{A}| = 2\left| \begin{array}{lll}1 & a_{12} & a_{13}\\ 1 & a_{22} & a_{23}\\ 1 & a_{32} & a_{33} \end{array} \right| = 2(A_{11} + A_{21} + A_{31}) = 3$ ，则

$$
A _ {1 1} + A _ {2 1} + A _ {3 1} = \frac {3}{2}.
$$

(16)【答案】 $\frac{1}{5}$ .

【解】 $(X,Y)$ 的可能取值为 $(0,0),(0,1),(1,0),(1,1)$

$$
P \{X = 0, Y = 0 \} = \frac {1}{2} \cdot \frac {3}{5} = \frac {3}{1 0},
$$

$$
P \{X = 0, Y = 1 \} = \frac {1}{2} \cdot \frac {2}{5} = \frac {1}{5},
$$

$$
P \{X = 1, Y = 0 \} = \frac {1}{2} \cdot \frac {2}{5} = \frac {1}{5},
$$

$$
P \{X = 1, Y = 1 \} = \frac {1}{2} \cdot \frac {3}{5} = \frac {3}{1 0},
$$

由 $X \sim \left( \begin{array}{ll} 0 & 1 \\ \frac{1}{2} & \frac{1}{2} \end{array} \right)$ 得 $E(X) = \frac{1}{2}, E(X^2) = \frac{1}{2}, D(X) = \frac{1}{4}$ ;

由 $Y\sim \left( \begin{array}{ll}0 & 1\\ \frac{1}{2} & \frac{1}{2} \end{array} \right)$ 得 $E(Y) = \frac{1}{2},E(Y^2) = \frac{1}{2},D(Y) = \frac{1}{4};$

由 $XY \sim \left( \begin{array}{cc} 0 & 1 \\ \frac{7}{10} & \frac{3}{10} \end{array} \right)$ 得 $E(XY) = \frac{3}{10}$ ,

$\operatorname{Cov}(X,Y) = E(XY) - E(X)E(Y) = \frac{3}{10} - \frac{1}{4} = \frac{1}{20}$ ，则 $\rho_{XY} = \frac{\frac{1}{20}}{\frac{1}{2} \cdot \frac{1}{2}} = \frac{1}{5}$ .

# 三、解答题

（17）【解】 方法一

$$
\lim  _ {x \rightarrow 0} \left(\frac {1 + \int_ {0} ^ {x} \mathrm {e} ^ {t ^ {2}} \mathrm {d} t}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x}\right) = \lim  _ {x \rightarrow 0} \frac {\left(1 + \int_ {0} ^ {x} \mathrm {e} ^ {t ^ {2}} \mathrm {d} t\right) \sin x - \mathrm {e} ^ {x} + 1}{(\mathrm {e} ^ {x} - 1) \sin x}
$$

$$
\begin{array}{l} = \lim  _ {x \rightarrow 0} \frac {\left(1 + \int_ {0} ^ {x} e ^ {t ^ {2}} d t\right) \sin x - e ^ {x} + 1}{x ^ {2}} \\ = \lim  _ {x \rightarrow 0} \left(\frac {\sin x - x}{x ^ {2}} + \frac {\int_ {0} ^ {x} e ^ {t ^ {2}} d t \cdot \sin x - e ^ {x} + 1 + x}{x ^ {2}}\right) \\ = \lim  _ {x \rightarrow 0} \frac {\int_ {0} ^ {x} e ^ {t ^ {2}} d t \cdot \sin x - e ^ {x} + 1 + x}{x ^ {2}} \\ = \lim  _ {x \rightarrow 0} \frac {\sin x}{x} \cdot \frac {\int_ {0} ^ {x} \mathrm {e} ^ {t ^ {2}} \mathrm {d} t}{x} - \lim  _ {x \rightarrow 0} \frac {\mathrm {e} ^ {x} - 1 - x}{x ^ {2}} \\ = \lim  _ {x \rightarrow 0} \mathrm {e} ^ {x ^ {2}} - \lim  _ {x \rightarrow 0} \frac {\mathrm {e} ^ {x} - 1}{2 x} = 1 - \frac {1}{2} = \frac {1}{2}. \\ \end{array}
$$

方法二

$$
\lim  _ {x \rightarrow 0} \left(\frac {1 + \int_ {0} ^ {x} e ^ {t ^ {2}} d t}{e ^ {x} - 1} - \frac {1}{\sin x}\right) = \lim  _ {x \rightarrow 0} \left(\frac {\int_ {0} ^ {x} e ^ {t ^ {2}} d t}{e ^ {x} - 1} + \frac {1}{e ^ {x} - 1} - \frac {1}{\sin x}\right),
$$

由 $\lim_{x\to 0}\frac{\int_{0}^{x}\mathrm{e}^{t^2}\mathrm{d}t}{\mathrm{e}^x - 1} = \lim_{x\to 0}\frac{\mathrm{e}^{x^2}}{\mathrm{e}^x} = 1,$

$$
\begin{array}{l} \lim  _ {x \rightarrow 0} \left(\frac {1}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x}\right) = \lim  _ {x \rightarrow 0} \frac {\sin x - \mathrm {e} ^ {x} + 1}{(\mathrm {e} ^ {x} - 1) \sin x} = \lim  _ {x \rightarrow 0} \frac {\sin x - \mathrm {e} ^ {x} + 1}{x ^ {2}} \\ = \frac {1}{2} \lim  _ {x \rightarrow 0} \frac {\cos x - e ^ {x}}{x} = \frac {1}{2} \lim  _ {x \rightarrow 0} (- \sin x - e ^ {x}) = - \frac {1}{2}, \\ \end{array}
$$

得 $\lim_{x\to 0}\left(\frac{1 + \int_0^x\mathrm{e}^{t^2}\mathrm{d}t}{\mathrm{e}^x - 1} -\frac{1}{\sin x}\right) = 1 - \frac{1}{2} = \frac{1}{2}.$

方法三

由泰勒公式得 $\mathrm{e}^{t^2} = 1 + t^2 + o(t^2)$

从而 $\int_0^x\mathrm{e}^{t^2}\mathrm{d}t = x + \frac{x^3}{3} +o(x^3)$ ，于是有

$$
\begin{array}{l} \lim  _ {x \rightarrow 0} \left(\frac {1 + \int_ {0} ^ {x} \mathrm {e} ^ {t ^ {2}} \mathrm {d} t}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x}\right) = \lim  _ {x \rightarrow 0} \left[ \frac {1 + x + \frac {x ^ {3}}{3} + o \left(x ^ {3}\right)}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x} \right] = \lim  _ {x \rightarrow 0} \left(\frac {1 + x}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x}\right) \\ = \lim  _ {x \rightarrow 0} \frac {x}{\mathrm {e} ^ {x} - 1} + \lim  _ {x \rightarrow 0} \left(\frac {1}{\mathrm {e} ^ {x} - 1} - \frac {1}{\sin x}\right) \\ = 1 + \lim  _ {x \rightarrow 0} \frac {\sin x - e ^ {x} + 1}{\left(e ^ {x} - 1\right) \sin x} = 1 + \lim  _ {x \rightarrow 0} \frac {\sin x - e ^ {x} + 1}{x ^ {2}} \\ = 1 + \lim  _ {x \rightarrow 0} \frac {\cos x - e ^ {x}}{2 x} = 1 + \lim  _ {x \rightarrow 0} \frac {- \sin x - e ^ {x}}{2} = \frac {1}{2}. \\ \end{array}
$$

(18)【解】 $\sum_{n=1}^{\infty} u_n(x) = \sum_{n=1}^{\infty} \mathrm{e}^{-nx} + \sum_{n=1}^{\infty} \frac{x^{n+1}}{n(n+1)}$ ,

当 $\lim_{n\to \infty}\frac{\mathrm{e}^{-(n + 1)x}}{\mathrm{e}^{-nx}} = \mathrm{e}^{-x} <   1$ 即 $x > 0$ 时， $\sum_{n = 1}^{\infty}\mathrm{e}^{-nx}$ 收敛；

再由 $\lim_{n\to \infty}\frac{\frac{1}{(n + 1)(n + 2)}}{\frac{1}{n(n + 1)}} = 1$ 得 $\sum_{n = 1}^{\infty}\frac{x^{n + 1}}{n(n + 1)}$ 的收敛半径为 $R = 1$

当 $x = \pm 1$ 时， $\sum_{n = 1}^{\infty}\left|\frac{(\pm 1)^{n + 1}}{n(n + 1)}\right| = \sum_{n = 1}^{\infty}\frac{1}{n(n + 1)} = 1$ 故 $\sum_{n = 1}^{\infty}\frac{x^{n + 1}}{n(n + 1)}$ 的收敛域为[-1,1]，故级数 $\sum_{n = 1}^{\infty}u_n(x)$ 的收敛域为(0,1].

令 $S(x) = \sum_{n=1}^{\infty} u_n(x) = \sum_{n=1}^{\infty} \mathrm{e}^{-nx} + \sum_{n=1}^{\infty} \frac{x^{n+1}}{n(n+1)} = S_1(x) + S_2(x)$ ，

且 $S_{1}(x) = \sum_{n = 1}^{\infty}\mathrm{e}^{-nx} = \frac{\mathrm{e}^{-x}}{1 - \mathrm{e}^{-x}} = \frac{1}{\mathrm{e}^{x} - 1};$

$$
\begin{array}{l} S _ {2} (x) = \sum_ {n = 1} ^ {\infty} \frac {x ^ {n + 1}}{n (n + 1)} = \sum_ {n = 1} ^ {\infty} \frac {x ^ {n + 1}}{n} - \sum_ {n = 1} ^ {\infty} \frac {x ^ {n + 1}}{n + 1} = x \sum_ {n = 1} ^ {\infty} \frac {x ^ {n}}{n} - \sum_ {n = 1} ^ {\infty} \frac {x ^ {n}}{n} + x \\ = (1 - x) \ln (1 - x) + x (0 <   x <   1), \\ \end{array}
$$

当 $x = 1$ 时，由 $S_{1}(1) = \frac{1}{\mathrm{e} - 1}, S_{2}(1) = 1$ 得 $S(1) = \frac{1}{\mathrm{e} - 1} + 1 = \frac{\mathrm{e}}{\mathrm{e} - 1}$ ，

故 $S(x) = \left\{ \begin{array}{ll} \frac{1}{\mathrm{e}^x - 1} + (1 - x)\ln (1 - x) + x, & 0 < x < 1, \\ \frac{\mathrm{e}}{\mathrm{e} - 1}, & x = 1. \end{array} \right.$

(19)【解】设 $M(x,y,z)\in C$ ，点 $M$ 到 $xOy$ 坐标面的距离 $d = |z|$

令 $F = z^2 + \lambda (x^2 + 2y^2 - z - 6) + \mu (4x + 2y + z - 30)$ ，

$\begin{cases} F_{x}^{\prime} = 2\lambda x + 4\mu = 0,\\ F_{y}^{\prime} = 4\lambda y + 2\mu = 0,\\ F_{z}^{\prime} = 2z - \lambda +\mu = 0,\\ F_{\lambda}^{\prime} = x^{2} + 2y^{2} - z - 6 = 0,\\ F_{\mu}^{\prime} = 4x + 2y + z - 30 = 0 \end{cases}$ 得 $\begin{cases} x = 4, \\ y = 1, \\ z = 12, \\ z = 66, \end{cases}$

故 $C$ 上的点 $(-8, -2, 66)$ 到 $xOy$ 面的距离最大为 66.

（20）【解】（I）显然 $I(D) = \iint_{D} (4 - x^{2} - y^{2}) \, \mathrm{d}x \, \mathrm{d}y$ 取最大值的区域为 $4 - x^{2} - y^{2} \geqslant 0$ ，即 $D_{1} = \{(x, y) \mid x^{2} + y^{2} \leqslant 4\}$ ，则

$$
\begin{array}{l} I \left(D _ {1}\right) = \iint_ {D _ {1}} \left(4 - x ^ {2} - y ^ {2}\right) \mathrm {d} x \mathrm {d} y = 2 \pi \int_ {0} ^ {2} r \left(4 - r ^ {2}\right) \mathrm {d} r \\ = 2 \pi \int_ {0} ^ {2} (4 r - r ^ {3}) \mathrm {d} r = 2 \pi (8 - 4) = 8 \pi ; \\ \end{array}
$$

（Ⅱ）令 $L_{0}:x^{2} + 4y^{2} = r^{2}(r > 0,L_{0}$ 在 $L$ 内，取逆时针)，设 $\partial D_1$ 与 $L_0^-$ 所围成的区域为 $D_0$ $L_{0}$ 围成的区域为 $D_{2}$ ，则

$$
\begin{array}{l} \int_ {\partial D _ {1}} \frac {(x e ^ {x ^ {2} + 4 y ^ {2}} + y) d x + (4 y e ^ {x ^ {2} + 4 y ^ {2}} - x) d y}{x ^ {2} + 4 y ^ {2}} \\ = \oint_ {\partial D _ {1} + L _ {0} ^ {-}} \frac {(x e ^ {x ^ {2} + 4 y ^ {2}} + y) d x + (4 y e ^ {x ^ {2} + 4 y ^ {2}} - x) d y}{x ^ {2} + 4 y ^ {2}} + \\ \int_ {L _ {0}} \frac {\left(x \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} + y\right) \mathrm {d} x + \left(4 y \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} - x\right) \mathrm {d} y}{x ^ {2} + 4 y ^ {2}}, \\ \end{array}
$$

而 $\oint_{\partial D_1 + L_0^-} \frac{(x \mathrm{e}^{x^2 + 4y^2} + y) \mathrm{d}x + (4y \mathrm{e}^{x^2 + 4y^2} - x) \mathrm{d}y}{x^2 + 4y^2} = \iint_{D_0} \left( \frac{\partial Q}{\partial x} - \frac{\partial P}{\partial y} \right) \mathrm{d}x \mathrm{d}y = 0,$

$$
\begin{array}{l} \int_ {L _ {0}} \frac {\left(x \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} + y\right) \mathrm {d} x + \left(4 y \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} - x\right) \mathrm {d} y}{x ^ {2} + 4 y ^ {2}} \\ = \frac {1}{r ^ {2}} \int_ {L _ {0}} (x \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} + y) \mathrm {d} x + (4 y \mathrm {e} ^ {x ^ {2} + 4 y ^ {2}} - x) \mathrm {d} y \\ = \frac {1}{r ^ {2}} \iint_ {D _ {2}} (8 x y e ^ {x ^ {2} + 4 y ^ {2}} - 1 - 8 x y e ^ {x ^ {2} + 4 y ^ {2}} - 1) d x d y \\ = \frac {- 2}{r ^ {2}} \iint_ {D _ {2}} \mathrm {d} x \mathrm {d} y = \frac {- 2}{r ^ {2}} \cdot \pi \cdot r \cdot \frac {r}{2} = - \pi . \\ \end{array}
$$

故 $\int_{\partial D_1} \frac{(x \mathrm{e}^{x^2 + 4y^2} + y) \mathrm{d}x + (4y \mathrm{e}^{x^2 + 4y^2} - x) \mathrm{d}y}{x^2 + 4y^2} = -\pi.$

（21）【解】（I）由

$$
\begin{array}{l} \left| \lambda E - A \right| = \left| \begin{array}{c c c} \lambda - a & - 1 & 1 \\ - 1 & \lambda - a & 1 \\ 1 & 1 & \lambda - a \end{array} \right| = \left| \begin{array}{c c c} \lambda - a + 1 & - (\lambda - a + 1) & 0 \\ - 1 & \lambda - a & 1 \\ 1 & 1 & \lambda - a \end{array} \right| \\ = (\lambda - a + 1) \left| \begin{array}{c c c} 1 & - 1 & 0 \\ - 1 & \lambda - a & 1 \\ 1 & 1 & \lambda - a \end{array} \right| \\ = (\lambda - a + 1) \left| \begin{array}{c c c} 1 & 0 & 0 \\ - 1 & \lambda - a - 1 & 1 \\ 1 & 2 & \lambda - a \end{array} \right| \\ = (\lambda - a + 1) ^ {2} (\lambda - a - 2) = 0, \\ \end{array}
$$

得 $\lambda_{1} = \lambda_{2} = a - 1, \lambda_{3} = a + 2$

由 $(a - 1)\pmb {E} - \pmb {A} = \left( \begin{array}{rrr} - 1 & -1 & 1\\ -1 & -1 & 1\\ 1 & 1 & -1 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 1 & -1\\ 0 & 0 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_1 = \lambda_2 = a - 1$ 对应的线性无关

的特征向量为 $\pmb{\alpha}_{1} = \left( \begin{array}{c} - 1\\ 1\\ 0 \end{array} \right),\pmb{\alpha}_{2} = \left( \begin{array}{c}1\\ 0\\ 1 \end{array} \right);$

由 $(a + 2)\pmb {E} - \pmb {A} = \left( \begin{array}{rrr}2 & -1 & 1\\ -1 & 2 & 1\\ 1 & 1 & 2 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & -2 & -1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & 1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得 $\lambda_3 = a + 2$ 对应的

特征向量为 $\pmb{\alpha}_{3} = \begin{pmatrix} -1\\ -1\\ 1 \end{pmatrix}$

令 $\pmb{\beta}_{1} = \pmb{\alpha}_{1} = \begin{pmatrix} -1 \\ 1 \\ 0 \end{pmatrix}, \pmb{\beta}_{2} = \pmb{\alpha}_{2} - \frac{(\pmb{\alpha}_{2},\pmb{\beta}_{1})}{(\pmb{\beta}_{1},\pmb{\beta}_{1})}\pmb{\beta}_{1} = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix} + \frac{1}{2}\begin{pmatrix} -1 \\ 1 \\ 0 \end{pmatrix} = \frac{1}{2}\begin{pmatrix} 1 \\ 1 \\ 2 \end{pmatrix}, \pmb{\beta}_{3} = \pmb{\alpha}_{3} = \begin{pmatrix} -1 \\ -1 \\ 1 \end{pmatrix},$

再令 $\pmb{\gamma}_{1} = \frac{1}{\sqrt{2}}\binom{-1}{0},\pmb{\gamma}_{2} = \frac{1}{\sqrt{6}}\binom{1}{1}$ $\pmb{\gamma}_{3} = \frac{1}{\sqrt{3}}\binom{-1}{-1}$

得正交矩阵 $\pmb{P} = \left[ \begin{array}{ccc} - \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} & -\frac{1}{\sqrt{3}}\\ \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}} & -\frac{1}{\sqrt{3}}\\ 0 & \frac{2}{\sqrt{6}} & \frac{1}{\sqrt{3}} \end{array} \right],$

使得 $P^{\mathrm{T}}AP = \left( \begin{array}{ccc}a - 1 & 0 & 0\\ 0 & a - 1 & 0\\ 0 & 0 & a + 2 \end{array} \right).$

（Ⅱ）由 $\pmb{P}^{\mathrm{T}}[(a + 3)\pmb {E} - \pmb {A}] \pmb {P} = \left( \begin{array}{lll}4 & 0 & 0\\ 0 & 4 & 0\\ 0 & 0 & 1 \end{array} \right)$ 得

$$
(a + 3) \boldsymbol {E} - \boldsymbol {A} = \boldsymbol {P} \left( \begin{array}{l l l} 4 & 0 & 0 \\ 0 & 4 & 0 \\ 0 & 0 & 1 \end{array} \right) \boldsymbol {P} ^ {\mathrm {T}} = \boldsymbol {P} \left( \begin{array}{l l l} 2 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 1 \end{array} \right) \boldsymbol {P} ^ {\mathrm {T}} \cdot \boldsymbol {P} \left( \begin{array}{l l l} 2 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 1 \end{array} \right) \boldsymbol {P} ^ {\mathrm {T}},
$$

令 $C = P\left( \begin{array}{lll}2 & 0 & 0\\ 0 & 2 & 0\\ 0 & 0 & 1 \end{array} \right)P^{\mathrm{T}}$

$$
\begin{array}{l} = \left[ \begin{array}{c c c} - \frac {1}{\sqrt {2}} & \frac {1}{\sqrt {6}} & - \frac {1}{\sqrt {3}} \\ \frac {1}{\sqrt {2}} & \frac {1}{\sqrt {6}} & - \frac {1}{\sqrt {3}} \\ 0 & \frac {2}{\sqrt {6}} & \frac {1}{\sqrt {3}} \end{array} \right] \left( \begin{array}{c c c} 2 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 1 \end{array} \right) \left[ \begin{array}{c c c} - \frac {1}{\sqrt {2}} & \frac {1}{\sqrt {2}} & 0 \\ \frac {1}{\sqrt {6}} & \frac {1}{\sqrt {6}} & \frac {2}{\sqrt {6}} \\ - \frac {1}{\sqrt {3}} & - \frac {1}{\sqrt {3}} & \frac {1}{\sqrt {3}} \end{array} \right] \\ = \frac {1}{3} \left( \begin{array}{c c c} 5 & - 1 & 1 \\ - 1 & 5 & 1 \\ 1 & 1 & 5 \end{array} \right). \\ \end{array}
$$

则 $\mathbf{C}^2 = (a + 3)\mathbf{E} - \mathbf{A}$

（22）【解】（I） $X$ 的密度函数为

$$
f _ {X} (x) = \left\{ \begin{array}{l l} 1, & 0 <   x <   1, \\ 0, & \text {其 他}. \end{array} \right.
$$

（Ⅱ）由 $Y = 2 - X$ 得 $Z = \frac{2 - X}{X}$

$$
F _ {Z} (z) = P \{Z \leqslant z \} = P \left\{\frac {2}{X} - 1 \leqslant z \right\},
$$

当 $z < 1$ 时， $F_{Z}(z) = 0$

当 $z \geqslant 1$ 时， $F_{Z}(z) = P\left\{X \geqslant \frac{2}{z + 1}\right\} = \int_{\frac{2}{z + 1}}^{1} 1 \, \mathrm{d}x = 1 - \frac{2}{z + 1} = \frac{z - 1}{z + 1}$ ，

即 $F_{Z}(z) = \left\{ \begin{array}{ll}0, & z < 1,\\ \frac{z - 1}{z + 1}, & z\geqslant 1, \end{array} \right.$

故 $Z$ 的密度函数为

$$
f _ {Z} (z) = \left\{ \begin{array}{l l} 0, & z \leqslant 1, \\ \frac {2}{(z + 1) ^ {2}}, & z > 1. \end{array} \right.
$$

$(\text{III}) E\left(\frac{X}{Y}\right) = E\left(\frac{X}{2 - X}\right) = \int_{0}^{1} \frac{x}{2 - x} \mathrm{d}x = 2 \ln 2 - 1.$