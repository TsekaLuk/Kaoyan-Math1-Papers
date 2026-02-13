# 2012年数学(一）真题解析

# 一、选择题

(1)【答案】 (C).

【解】 由 $\lim_{x\to \infty}y = 1$ ，得 $y = 1$ 为曲线 $y = \frac{x^2 + x}{x^2 - 1}$ 的水平渐近线；

由 $\lim_{x\to 1}y = \infty$ ，得 $x = 1$ 为曲线 $y = \frac{x^2 + x}{x^2 - 1}$ 的铅直渐近线；

显然 $x = -1$ 不是曲线 $y = \frac{x^2 + x}{x^2 - 1}$ 的铅直渐近线，且曲线没有斜渐近线，

故曲线 $y = \frac{x^2 + x}{x^2 - 1}$ 有两条渐近线，应选(C).

方法点评：本题考查曲线的渐近线. 渐近线是基础而频繁的考点，需要熟练掌握其求法. 曲线的渐近线共有三种，即水平渐近线、铅直渐近线和斜渐近线.

若 $\lim_{x\to \infty}f(x) = A$ ，则 $y = A$ 为曲线 $y = f(x)$ 的水平渐近线；

若 $\lim_{x\to a}f(x) = \infty$ ，则 $x = a$ 为曲线 $y = f(x)$ 的铅直渐近线；

若 $\lim_{x\to \infty}\frac{f(x)}{x} = a(\neq 0,\infty),\lim_{x\to \infty}[f(x) - ax] = b$ ，则 $y = ax + b$ 为曲线 $y = f(x)$ 的斜渐近线.

（2）【答案】 （A）.

【解】 方法一 由

$$
\begin{array}{l} f ^ {\prime} (x) = \mathrm {e} ^ {x} (\mathrm {e} ^ {2 x} - 2) \dots (\mathrm {e} ^ {n x} - n) + 2 (\mathrm {e} ^ {x} - 1) \mathrm {e} ^ {2 x} (\mathrm {e} ^ {3 x} - 3) \dots (\mathrm {e} ^ {n x} - n) + \dots + \\ n \left(\mathrm {e} ^ {x} - 1\right) \left(\mathrm {e} ^ {2 x} - 2\right) \dots \left(\mathrm {e} ^ {(n - 1) x} - n + 1\right) \mathrm {e} ^ {n x}, \\ \end{array}
$$

得 $f^{\prime}(0) = (-1)^{n - 1}(n - 1)!$

应选(A).

方法二 由导数的定义，得

$$
f ^ {\prime} (0) = \lim  _ {x \rightarrow 0} \frac {f (x) - f (0)}{x} = \lim  _ {x \rightarrow 0} \frac {e ^ {x} - 1}{x} \left(e ^ {2 x} - 2\right) \dots \left(e ^ {n x} - n\right) = (- 1) ^ {n - 1} (n - 1)!
$$

应选(A).

（3）【答案】 (B).

【解】方法一 由 $f(x,y)$ 在 $(0,0)$ 连续及 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{x^2 + y^2}$ 存在，得 $f(0,0) = 0$

取 $y = 0$ ，由 $\lim_{x\to 0}\frac{f(x,0)}{x^2} = \lim_{x\to 0}\frac{f(x,0) - f(0,0)}{x}\cdot \frac{1}{x}$ 存在，得 $\lim_{x\to 0}\frac{f(x,0) - f(0,0)}{x} = 0$ 即 $f_{x}^{\prime}(0,0) = 0$ ，同理 $f_{y}^{\prime}(0,0) = 0$

由 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{\Delta z - f_x'(0,0)x - f_y'(0,0)y}{x^2 + y^2} = \lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{x^2 + y^2}$ 存在，得

$\Delta z - f_x'(0,0)x - f_y'(0,0)y = o(\rho)$ ，故 $f(x,y)$ 在(0，0）处可微，应选(B).

方法二 由 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{x^2 + y^2}$ 存在，得 $f(0,0) = 0$

令 $\rho = \sqrt{x^2 + y^2}$ ，设 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{x^2 + y^2} = A$ ，则 $\Delta z = f(x,y) - f(0,0) = 0\cdot x + 0\cdot y + o(\rho)$ ，由可微的定义得 $f(x,y)$ 在(0，0）处可微，应选(B).

方法三 取 $f(x, y) = |x| + |y|$ ， $\lim_{\substack{x \to 0 \\ y \to 0}} \frac{f(x, y)}{|x| + |y|} = 1$ ，因为 $\lim_{x \to 0} \frac{f(x, 0) - f(0, 0)}{x} = \lim_{x \to 0} \frac{|x|}{x}$ 不存在，所以 $f(x, y)$ 在 $(0, 0)$ 处对 $x$ 不可偏导，由对称性， $f(x, y)$ 在 $(0, 0)$ 处对 $y$ 也不可偏导，于是 $f(x, y)$ 在 $(0, 0)$ 处不可微，（A）不对；

取 $f(x,y) = x$ ，显然 $f(x,y)$ 在(0，0）处可微，因为 $\lim_{x\to 0}\frac{f(x,0)}{|x|} = \lim_{x\to 0}\frac{x}{|x|}$ 不存在，所以 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{|x| + |y|}$ 不存在，（C）不对；

取 $f(x,y) = xy$ ，因为 $f(x,y)$ 连续可偏导，所以 $f(x,y)$ 在(0,0)处可微，但 $\lim_{\substack{x\to 0\\ y\to 0}}\frac{f(x,y)}{x^2 + y^2}$ 不存在，（D）不对，应选(B).

方法点评：本题考查二元函数可微的判断. 判断二元函数 $f(x, y)$ 在点 $(x_0, y_0)$ 处可微一般有如下几个方法：

(1) 若 $f(x, y)$ 连续可偏导，则 $f(x, y)$ 在 $(x_0, y_0)$ 处可微；  
(2) 若 $\Delta z = f(x, y) - f(x_0, y_0) = A(x - x_0) + B(y - y_0) + o(\sqrt{(x - x_0)^2 + (y - y_0)^2})$ 则 $f(x, y)$ 在 $(x_0, y_0)$ 处可微；

(3) 若 $f(x, y)$ 在 $(x_0, y_0)$ 处可偏导，则 $f(x, y)$ 在 $(x_0, y_0)$ 处可微的充分必要条件是

$$
\lim  _ {x \rightarrow x _ {0} \atop y \rightarrow y _ {0}} \frac {f (x , y) - f (x _ {0} , y _ {0}) - f _ {x} ^ {\prime} (x _ {0} , y _ {0}) (x - x _ {0}) - f _ {y} ^ {\prime} (x _ {0} , y _ {0}) (y - y _ {0})}{\rho} = 0,
$$

其中 $\rho = \sqrt{(x - x_0)^2 + (y - y_0)^2}$

（4）【答案】 (D).

【解】 由 $I_{2} - I_{1} = \int_{\pi}^{2\pi}\mathrm{e}^{x^{2}}\sin x\mathrm{d}x <   0$ ，得 $I_{1} > I_{2}$

由 $I_{3} - I_{2} = \int_{2\pi}^{3\pi}\mathrm{e}^{x^{2}}\sin x\mathrm{d}x > 0$ ，得 $I_{2} <   I_{3}$

$$
I _ {3} - I _ {1} = \int_ {\pi} ^ {3 \pi} \mathrm {e} ^ {x ^ {2}} \sin x \mathrm {d} x = \int_ {\pi} ^ {2 \pi} \mathrm {e} ^ {x ^ {2}} \sin x \mathrm {d} x + \int_ {2 \pi} ^ {3 \pi} \mathrm {e} ^ {x ^ {2}} \sin x \mathrm {d} x,
$$

而 $\int_{2\pi}^{3\pi}\mathrm{e}^{x^2}\sin x\mathrm{d}x = \int_{\pi}^{2\pi}\mathrm{e}^{(t + \pi)^2}\sin (t + \pi)\mathrm{d}t = -\int_{\pi}^{2\pi}\mathrm{e}^{(x + \pi)^2}\sin x\mathrm{d}x,$

由 $I_{3} - I_{1} = \int_{\pi}^{2\pi}\left[\mathrm{e}^{x^{2}} - \mathrm{e}^{(x + \pi)^{2}}\right]\sin x\mathrm{d}x > 0$ ，得 $I_{1} < I_{3}$ ，于是 $I_{2} < I_{1} < I_{3}$ ，应选(D).

（5）【答案】 (C).

【解】方法一 $\pmb{\alpha}_{3} + \pmb{\alpha}_{4} = \binom{0}{c_{3} + c_{4}}$ ，因为 $\pmb{\alpha}_{3} + \pmb{\alpha}_{4}$ 与 $\pmb{\alpha}_{1}$ 成比例，所以 $\pmb{\alpha}_{1},\pmb{\alpha}_{3} + \pmb{\alpha}_{4}$ 线性相关，故 $\pmb{\alpha}_{1},\pmb{\alpha}_{3},\pmb{\alpha}_{4}$ 线性相关，应选(C).

方法二 因为 $|\pmb{\alpha}_1, \pmb{\alpha}_3, \pmb{\alpha}_4| = \left| \begin{array}{ccc} 0 & 1 & -1 \\ 0 & -1 & 1 \\ c_1 & c_3 & c_4 \end{array} \right| = 0$ ，所以 $\pmb{\alpha}_1, \pmb{\alpha}_3, \pmb{\alpha}_4$ 线性相关，应选(C).

（6）【答案】 (B).

【解】 由 $Q = (\pmb{\alpha}_1 + \pmb{\alpha}_2, \pmb{\alpha}_2, \pmb{\alpha}_3) = \pmb{P} \begin{pmatrix} 1 & 0 & 0 \\ 1 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}$ ,

得 $Q^{-1}AQ = \begin{pmatrix} 1 & 0 & 0\\ 1 & 1 & 0\\ 0 & 0 & 1 \end{pmatrix} ^{-1}\pmb{P}^{-1}\pmb {A}\pmb {P}\begin{pmatrix} 1 & 0 & 0\\ 1 & 1 & 0\\ 0 & 0 & 1 \end{pmatrix}$

$$
= \left( \begin{array}{c c c} 1 & 0 & 0 \\ - 1 & 1 & 0 \\ 0 & 0 & 1 \end{array} \right) \left( \begin{array}{c c c} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 2 \end{array} \right) \left( \begin{array}{c c c} 1 & 0 & 0 \\ 1 & 1 & 0 \\ 0 & 0 & 1 \end{array} \right) = \left( \begin{array}{c c c} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 2 \end{array} \right),
$$

应选(B).

（7）【答案】 （A).

【解】 $X$ 的密度函数为 $f_{X}(x) = \left\{ \begin{array}{ll}\mathrm{e}^{-x}, & x > 0,\\ 0, & x\leqslant 0; \end{array} \right.$

$Y$ 的密度函数为 $f_{Y}(y) = \left\{ \begin{array}{ll}4\mathrm{e}^{-4y}, & y > 0,\\ 0, & y\leqslant 0. \end{array} \right.$

因为 $X, Y$ 独立，所以 $X, Y$ 的联合密度为

$$
f (x  , y) = f _ {X} (x) f _ {Y} (y) = \left\{ \begin{array}{l l} 4 \mathrm {e} ^ {- (x + 4 y)}  , & x > 0, y > 0, \\ 0, & \text {其 他}, \end{array} \right.
$$

于是 $P\{X < Y\} = \iint_{x < y} f(x, y) \, \mathrm{d}x \, \mathrm{d}y = \int_{0}^{+\infty} \mathrm{e}^{-x} \, \mathrm{d}x \int_{x}^{+\infty} 4 \mathrm{e}^{-4y} \, \mathrm{d}y = \int_{0}^{+\infty} \mathrm{e}^{-5x} \, \mathrm{d}x = \frac{1}{5}$ ,

应选(A).

(8)【答案】 (D).

【解】方法一 设两段长度分别为 $X, Y$ ，则 $X + Y = 1$ 或 $Y = -X + 1$ .

由 $P\{Y = -X + 1\} = 1$ ，得 $\rho_{XY} = -1$ ，应选(D).

方法二

设两段长度为 $X, Y$ ，则 $X \sim U(0,1)$ ，且 $Y = -X + 1$ .

由 $X\sim U(0,1)$ 得 $f_{X}(x) = \left\{ \begin{array}{ll}1, & 0 <   x <   1,\\ 0, & \text{其他}. \end{array} \right.$

$$
E (X) = \int_ {0} ^ {1} x \mathrm {d} x = \frac {1}{2}, \quad E (Y) = E (- X + 1) = - E (X) + 1 = \frac {1}{2},
$$

$$
E (X Y) = E [ X (- X + 1) ] = - E (X ^ {2}) + E (X) = - \int_ {0} ^ {1} x ^ {2} \mathrm {d} x + \frac {1}{2} = \frac {1}{6},
$$

则 $\operatorname{Cov}(X, Y) = E(XY) - E(X)E(Y) = \frac{1}{6} - \frac{1}{4} = -\frac{1}{12}$ ;

由 $E(X^2) = \int_0^1 x^2\mathrm{d}x = \frac{1}{3}$ 得 $D(X) = E(X^{2}) - (EX)^{2} = \frac{1}{3} -\frac{1}{4} = \frac{1}{12},$

[ D(Y) = D(-X + 1) = D(X) = \frac{1}{12} ]，则 $\rho_{XY} = \frac{\operatorname{Cov}(X, Y)}{\sqrt{D(X)} \cdot \sqrt{D(Y)}} = -1$ ，应选(D).

方法点评：本题考查两个随机变量的相关系数.相关系数的计算公式为

$\rho_{XY} = \frac{\operatorname{Cov}(X,Y)}{\sqrt{D(X)}\cdot\sqrt{D(Y)}}$ ，注意以下两个结论：

(1) $\rho_{XY} = -1$ 的充分必要条件为 $P\{Y = aX + b\} = 1 (a < 0)$ ;  
(2) $\rho_{\mathrm{XY}} = 1$ 的充分必要条件为 $P\{Y = aX + b\} = 1 (a > 0)$ .

# 二、填空题

（9）【答案】 $\mathrm{e}^x$

【解】由观察知 $f^{\prime \prime}(x) + f(x) = 2\mathrm{e}^{x}$ 的一特解为 $f(x) = \mathrm{e}^{x}$

将其代入 $f^{\prime \prime}(x) + f^{\prime}(x) - 2f(x) = 0$ 中满足，故 $f(x) = \mathrm{e}^{x}$

(10)【答案】 $\frac{\pi}{2}$ .

【解】 $\int_0^2 x\sqrt{2x - x^2}\mathrm{d}x = \int_0^2 [(x - 1) + 1]\sqrt{1 - (x - 1)^2}\mathrm{d}(x - 1)$

$$
\begin{array}{l} = \int_ {- 1} ^ {1} (x + 1) \sqrt {1 - x ^ {2}} d x = \int_ {- 1} ^ {1} \sqrt {1 - x ^ {2}} d x \\ = 2 \int_ {0} ^ {1} \sqrt {1 - x ^ {2}} d x = \frac {\pi}{2}. \\ \end{array}
$$

方法点评：本题考查定积分的计算。当积分表达式中出现根号，且根号内为二次多项式，一般采用配方法，再换元。需要注意如下几个结论：

(1) $\int_{-a}^{a} f(x) \, \mathrm{d}x = \int_{0}^{a} [f(x) + f(-x)] \, \mathrm{d}x$ ;   
(2) 含 $\sqrt{a^2 - x^2}$ 的积分，注意使用三角代换 $x = a\sin t$

特别地，根据定积分的几何意义有 $\int_{0}^{a}\sqrt{a^2 - x^2}\mathrm{d}x = \frac{\pi}{4} a^2.$

（11）【答案】 $i + j + k$

【解】 令 $f(x,y,z) = xy + \frac{z}{y}$

$$
\operatorname {g r a d} \left(x y + \frac {z}{y}\right) = \left\{\frac {\partial f}{\partial x}, \frac {\partial f}{\partial y}, \frac {\partial f}{\partial z} \right\} = \left\{y, x - \frac {z}{y ^ {2}}, \frac {1}{y} \right\},
$$

于是 $\mathbf{grad}\left(xy + \frac{z}{y}\right)\big|_{(2,1,1)} = \{1,1,1\} = i + j + k.$

(12)【答案】 $\frac{\sqrt{3}}{12}$ .

【解】令 $\Sigma :z = 1 - x - y((x,y)\in D)$ ，其中 $D = \{(x,y)\mid x + y\leqslant 1,x\geqslant 0,y\geqslant 0\}$

则 $\iint_{\Sigma} y^2 \, \mathrm{d}S = \iint_{D} y^2 \cdot \sqrt{1 + \left(\frac{\partial z}{\partial x}\right)^2 + \left(\frac{\partial z}{\partial y}\right)^2} \, \mathrm{d}x \, \mathrm{d}y$

$$
= \sqrt {3} \iint_ {D} y ^ {2} d x d y = \sqrt {3} \int_ {0} ^ {1} y ^ {2} d y \int_ {0} ^ {1 - y} d x = \sqrt {3} \int_ {0} ^ {1} y ^ {2} (1 - y) d y = \frac {\sqrt {3}}{1 2}.
$$

（13）【答案】2.

【解】方法一 取 $\pmb{\alpha} = \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix}, \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}} = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}$ , 由 $\pmb{E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}} = \begin{pmatrix} 0 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{pmatrix}$ , 得 $\pmb{E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}$ 的秩为2.

方法二 令 $\mathbf{A} = \mathbf{E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}$ ，则 $A^{2} = (E - \alpha \alpha^{\mathrm{T}})(E - \alpha \alpha^{\mathrm{T}}) = E - \alpha \alpha^{\mathrm{T}} = A.$

由 $A(E - A) = O$ ，得 $r(A) + r(E - A)\leqslant 3.$

又由 $r(\mathbf{A}) + r(\mathbf{E} - \mathbf{A})\geqslant r(\mathbf{E}) = 3$ ，得 $r(A) + r(E - A) = 3.$

而 $r(\mathbf{E} - \mathbf{A}) = r(\pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}) = r(\pmb{\alpha}) = 1$ ，所以 $r(\mathbf{A}) = r(\mathbf{E} - \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}) = 2.$

方法点评：本题考查矩阵的秩

研究由向量乘法形成的矩阵的秩时，通常使用矩阵的幂阵，本题很容易想到计算 $A^2$ 与 $\pmb{A}$ 的关系.另外注意本题 $E - \alpha \alpha^{\mathrm{T}}$ 与具体的 $\pmb{\alpha}$ 无关，可以采用举例法.

(14)【答案】 $\frac{3}{4}$ .

【解】 因为 $A, C$ 互不相容，所以

$$
P (A B \mid \bar {C}) = \frac {P (A B \bar {C})}{P (\bar {C})} = \frac {P (A B) - P (A B C)}{1 - P (C)} = \frac {P (A B)}{1 - P (C)} = \frac {3}{4}.
$$

# 三、解答题

(15)【证明】 方法一 令 $f(x) = x\ln \frac{1 + x}{1 - x} +\cos x - \frac{x^2}{2} -1,$

$$
f ^ {\prime} (x) = \ln \frac {1 + x}{1 - x} + \frac {2 x}{1 - x ^ {2}} - \sin x - x, \quad f ^ {\prime \prime} (x) = \frac {4}{(1 - x ^ {2}) ^ {2}} - 1 - \cos x.
$$

当 $-1 < x < 1$ 时，因为 $\frac{4}{(1 - x^2)^2} \geqslant 4, 1 + \cos x \leqslant 2$ ，所以 $f''(x) > 0$ .

又因为 $f^{\prime}(0) = 0$ ，所以 $\left\{ \begin{array}{ll}f^{\prime}(x) <   0, & -1 <   x <   0,\\ f^{\prime}(x) > 0, & 0 <   x <   1, \end{array} \right.$ 于是 $x = 0$ 为 $f(x)$ 在 $(-1,1)$ 内的最小值点，而 $f(0) = 0$ ，故当一 $1 <   x <   1$ 时， $f(x)\geqslant 0$ ，即 $x\ln {\frac{1 + x}{1 - x}} + \cos x\geqslant 1 + \frac{x^2}{2}$

方法二 令 $f(x) = x \ln \frac{1 + x}{1 - x} + \cos x - \frac{x^2}{2} - 1$ ， $f(0) = 0$ .

因为 $f(-x) = f(x)$ ，所以 $f(x)$ 为偶函数，只需要研究[0,1）内的情形.

$$
f ^ {\prime} (x) = \ln \frac {1 + x}{1 - x} + \frac {2 x}{1 - x ^ {2}} - \sin x - x = \ln \frac {1 + x}{1 - x} + \frac {1}{1 - x} - \frac {1}{1 + x} - \sin x - x, f ^ {\prime} (0) = 0,
$$

$$
f ^ {\prime \prime} (x) = \frac {1}{1 + x} + \frac {1}{1 - x} + \frac {1}{(1 - x) ^ {2}} + \frac {1}{(1 + x) ^ {2}} - \cos x - 1, \quad f ^ {\prime \prime} (0) = 2,
$$

$$
f ^ {\prime \prime} (x) = \frac {1}{(1 - x) ^ {2}} - \frac {1}{(1 + x) ^ {2}} + \frac {2}{(1 - x) ^ {3}} - \frac {2}{(1 + x) ^ {3}} + \sin x > 0,
$$

由 $\left\{ \begin{array}{l} f^{\prime \prime}(0) = 2, \\ f^{\prime \prime}(x) > 0 (0 < x < 1), \end{array} \right.$ 得 $f^{\prime \prime}(x) > 2 > 0 (0 < x < 1)$ ;

再由 $\left\{ \begin{array}{l} f^{\prime}(0) = 0, \\ f^{\prime \prime}(x) > 0 (0 < x < 1), \end{array} \right.$ 得 $f^{\prime}(x) > 0 (0 < x < 1)$ ;

由 $\left\{ \begin{array}{l} f(0) = 0, \\ f'(x) > 0 (0 < x < 1), \end{array} \right.$ 得 $f(x) > 0 (0 < x < 1)$ ，

故当 $-1 < x < 1$ 时， $x\ln \frac{1 + x}{1 - x} + \cos x \geqslant 1 + \frac{x^2}{2}$ .

方法点评：证明函数不等式是重要考查点，一般采用单调性进行证明，根据导数或高阶导数符号最终确定函数的单调性，根据函数在某一点的符号情况得到所证的不等式.

(16)【解】 令 $\left\{ \begin{array}{l} f_{x}^{\prime} = (1 - x^{2})\mathrm{e}^{-\frac{x^{2} + y^{2}}{2}} = 0, \\ f_{y}^{\prime} = -xy\mathrm{e}^{-\frac{x^{2} + y^{2}}{2}} = 0, \end{array} \right.$ 得 $\left\{ \begin{array}{l} x = 1, \\ y = 0 \end{array} \right.$ 或 $\left\{ \begin{array}{l} x = -1, \\ y = 0. \end{array} \right.$

$$
f _ {x x} ^ {\prime \prime} = x (x ^ {2} - 3) \mathrm {e} ^ {- \frac {x ^ {2} + y ^ {2}}{2}}, \quad f _ {x y} ^ {\prime \prime} = y (x ^ {2} - 1) \mathrm {e} ^ {- \frac {x ^ {2} + y ^ {2}}{2}}, \quad f _ {y y} ^ {\prime \prime} = x (y ^ {2} - 1) \mathrm {e} ^ {- \frac {x ^ {2} + y ^ {2}}{2}},
$$

当 $(x,y) = (1,0)$ 时，

$$
A = f _ {x x} ^ {\prime \prime} (1, 0) = - 2 \mathrm {e} ^ {- \frac {1}{2}}, \quad B = f _ {x y} ^ {\prime \prime} (1, 0) = 0, \quad C = f _ {y y} ^ {\prime \prime} (1, 0) = - \mathrm {e} ^ {- \frac {1}{2}},
$$

由 $AC - B^2 > 0$ 且 $A < 0$ ，得(1,0)为 $f(x,y)$ 的极大值点，极大值为 $f(1,0) = \mathrm{e}^{-\frac{1}{2}}$ 当 $(x,y) = (-1,0)$ 时，

$$
A = f _ {x x} ^ {\prime \prime} (- 1, 0) = 2 \mathrm {e} ^ {- \frac {1}{2}}, \quad B = f _ {x y} ^ {\prime \prime} (- 1, 0) = 0, \quad C = f _ {y y} ^ {\prime \prime} (- 1, 0) = \mathrm {e} ^ {- \frac {1}{2}},
$$

由 $AC - B^2 >0$ 且 $A > 0$ 得 $(-1,0)$ 为 $f(x,y)$ 的极小值点，极小值为 $f(-1,0) = -\mathrm{e}^{-\frac{1}{2}}.$ (17）【解】由 $\lim_{n\to \infty}\left|\frac{a_{n + 1}}{a_n}\right| = 1$ ，得级数的收敛半径为 $R = 1$

当 $x = \pm 1$ 时，由 $\lim_{n\to \infty}\frac{4n^2 + 4n + 3}{2n + 1} (\pm 1)^{2n}\neq 0$ ，得 $x = \pm 1$ 时级数发散，故幂级数的收敛域为 $(-1,1)$

令 $S(x) = \sum_{n=0}^{\infty} \frac{4n^{2} + 4n + 3}{2n + 1} x^{2n} = \sum_{n=0}^{\infty} (2n + 1) x^{2n} + 2 \sum_{n=0}^{\infty} \frac{x^{2n}}{2n + 1}$ ,

而 $\sum_{n=0}^{\infty}(2n+1)x^{2n}=\left(\sum_{n=0}^{\infty}x^{2n+1}\right)'=\left(\frac{x}{1-x^{2}}\right)'=\frac{1+x^{2}}{(1-x^{2})^{2}}(-1<x<1)$ ,

令 $S_{1}(x) = \sum_{n = 0}^{\infty}\frac{x^{2n}}{2n + 1},S_{1}(0) = 1,$

当 $0 < |x| < 1$ 时， $S_{1}(x) = \frac{1}{x}\sum_{n=0}^{\infty}\frac{x^{2n+1}}{2n+1} = \frac{1}{x}\int_{0}^{x}\left(\sum_{n=0}^{\infty}x^{2n}\right)\mathrm{d}x$

$$
= \frac {1}{x} \int_ {0} ^ {x} \frac {1}{1 - x ^ {2}} d x = \frac {1}{2 x} \ln \frac {1 + x}{1 - x},
$$

于是 $S(x) = \left\{ \begin{array}{ll}3, & x = 0,\\ \frac{1 + x^2}{(1 - x^2)^2} +\frac{1}{x}\ln \frac{1 + x}{1 - x}, & 0 <   |x| <   1. \end{array} \right.$

(18)【解】曲线 $L$ 的切线的斜率为 $k = \frac{\mathrm{dy} / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = -\frac{\sin t}{f'(t)}$ ，切线方程为

$$
y - \cos t = - \frac {\sin t}{f ^ {\prime} (t)} [ x - f (t) ].
$$

令 $y = 0$ ，得切线与 $x$ 轴交点的横坐标为 $x = f(t) + \frac{\cos t}{\sin t} f'(t)$ ，由题意得

$$
\cot^ {2} t \cdot f ^ {\prime 2} (t) + \cos^ {2} t = 1,
$$

因为 $f^{\prime}(t) > 0$ ，所以 $f^{\prime}(t) = \frac{\sin^{2}t}{\cos t} = \sec t - \cos t$

于是 $f(t) = \ln (\sec t + \tan t) - \sin t + C$

再由 $f(0) = 0$ 得 $C = 0$ ，故 $f(t) = \ln (\sec t + \tan t) - \sin t.$

由 $f(0) = 0$ ， $\lim_{t\to \frac{\pi}{2}}f(t) = +\infty$ 得曲线 $L$ 及 $x$ 轴及 $y$ 轴围成的无界区域的面积为

$$
A = \int_ {0} ^ {+ \infty} y \mathrm {d} x = \int_ {0} ^ {\frac {\pi}{2}} \cos t \cdot f ^ {\prime} (t) \mathrm {d} t = \int_ {0} ^ {\frac {\pi}{2}} \sin^ {2} t \mathrm {d} t = \frac {\pi}{4}.
$$

(19)【解】补充 $L_{0}:x = 0$ （起点 $y = 2$ ，终点 $y = 0$ )，记 $L$ 与 $L_{0}$ 围成的区域为 $D$ ，由格林公式得

$$
\begin{array}{l} I = \oint_ {L + L _ {0}} 3 x ^ {2} y d x + (x ^ {3} + x - 2 y) d y - \int_ {L _ {0}} 3 x ^ {2} y d x + (x ^ {3} + x - 2 y) d y \\ = \iint_ {D} \left(\frac {\partial Q}{\partial x} - \frac {\partial P}{\partial y}\right) d \sigma - \int_ {2} ^ {0} - 2 y d y = \iint_ {D} d x d y - \int_ {0} ^ {2} 2 y d y = \frac {\pi}{2} - 4. \\ \end{array}
$$

（20）【解】（I）由行列式按行或列展开的性质得

$$
| \mathbf {A} | = 1 \times A _ {1 1} + a \cdot A _ {4 1} = M _ {1 1} - a M _ {4 1} = 1 - a ^ {4}.
$$

（Ⅱ）若 $AX = \beta$ 有无数个解，则 $|\mathbf{A}| = 0$ ，即 $a = -1$ 或 $a = 1$

当 $a = -1$ 时， $(\mathbf{A}\vdots \mathbf{\beta}) = \left[ \begin{array}{cccc}1 & -1 & 0 & 0\\ 0 & 1 & -1 & 0\\ 0 & 0 & 1 & -1\\ -1 & 0 & 0 & 1 \end{array} \right]\rightarrow \left[ \begin{array}{cccc}1 & 0 & 0 & -1\\ 0 & 1 & 0 & -1\\ 0 & 0 & 1 & -1\\ 0 & 0 & 0 & 0 \end{array} \right],$

因为 $r(\mathbf{A}) = r(\overline{\mathbf{A}}) = 3 < 4$ ，所以方程组 $\mathbf{AX} = \pmb{\beta}$ 有无数个解，通解为

$\mathbf{X} = C\left[ \begin{array}{l}1\\ 1\\ 1\\ 1 \end{array} \right] + \left[ \begin{array}{l}0\\ -1\\ 0\\ 0 \end{array} \right]$ （C为任意常数）；

当 $a = 1$ 时， $(\mathbf{A}\vdots \pmb {\beta}) = \begin{bmatrix} 1 & 1 & 0 & 0 & 1\\ 0 & 1 & 1 & 0 & -1\\ 0 & 0 & 1 & 1 & 0\\ 1 & 0 & 0 & 1 & 0 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 1 & 0 & 0 & 1\\ 0 & 1 & 1 & 0 & -1\\ 0 & 0 & 1 & 1 & 0\\ 0 & 0 & 0 & 0 & -2 \end{bmatrix} ,$

因为 $r(\mathbf{A})\neq r(\overline{\mathbf{A}})$ ，所以方程组 $\mathbf{AX} = \pmb{\beta}$ 无解

方法点评：行列式虽然不是考查的重点内容，但有几种特殊行列式需要熟练掌握其计算方法：

（1）三对角行列式，如本题矩阵对应的行列式，这种行列式的计算一般采用行列式按行或列的方法展开计算或找递推关系.

（2）对称矩阵对应的行列式，一般采用所有行加到第一行，提取公因子，再将行列式上（下）三角化计算.

非齐次线性方程组解的讨论，首先运用方程组解的理论确定解的存在性，然后利用初等行变换求方程组通解，这个方法一定要反复练习，熟能生巧.

(21)【解】 (I) $\mathbf{A} = \begin{bmatrix} 1 & 0 & 1 \\ 0 & 1 & 1 \\ -1 & 0 & a \\ 0 & a & -1 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 0 & 1 \\ 0 & 1 & 1 \\ 0 & 0 & a + 1 \\ 0 & 0 & -1 - a \end{bmatrix}$ ,

由 $r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = 2$ 及 $r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = r(\mathbf{A})$ 得 $a = -1$

（Ⅱ）当 $a = -1$ 时， $\mathbf{A}^{\mathrm{T}}\mathbf{A} = \begin{pmatrix} 2 & 0 & 2\\ 0 & 2 & 2\\ 2 & 2 & 4 \end{pmatrix}$

由 $|\lambda \pmb {E} - \pmb{A}^{\mathrm{T}}\pmb {A}| = \left| \begin{array}{ccc}\lambda -2 & 0 & -2\\ 0 & \lambda -2 & -2\\ -2 & -2 & \lambda -4 \end{array} \right| = \lambda (\lambda -2)(\lambda -6) = 0$ ，得 $\mathbf{A}^{\mathrm{T}}\mathbf{A}$ 的特征值为 $\lambda_1 = 0,\lambda_2 = 2,\lambda_3 = 6.$

当 $\lambda_{1} = 0$ 时，由 $(0E - A^{\mathrm{T}}A)X = 0$ 即 $A^{\mathrm{T}}AX = 0$ 得 $\lambda_{1} = 0$ 对应的特征向量为 $\pmb {\xi}_1 = \begin{pmatrix} -1\\ -1\\ 1 \end{pmatrix}$ 当 $\lambda_2 = 2$ 时，由 $(2E - A^{\mathrm{T}}A)X = 0$ 得 $\lambda_{2} = 2$ 对应的特征向量为 $\pmb {\xi}_2 = \left( \begin{array}{l}1\\ -1\\ 0 \end{array} \right)$

当 $\lambda_3 = 6$ 时，由 $(6\pmb {E} - \pmb{A}^{\mathrm{T}}\pmb {A})\pmb {X} = \pmb{0}$ 得 $\lambda_{3} = 6$ 对应的特征向量为 $\xi_{3} = \left( \begin{array}{l}1\\ 1\\ 2 \end{array} \right)$

单位化得 $\gamma_{1} = \frac{1}{\sqrt{3}}\binom{-1}{-1}$ ， $\gamma_{2} = \frac{1}{\sqrt{2}}\binom{1}{0}$ ， $\gamma_{3} = \frac{1}{\sqrt{6}}\binom{1}{2}$ ，

令 $Q = \left[ \begin{array}{ccc} - \frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}}\\ -\frac{1}{\sqrt{3}} & -\frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}}\\ \frac{1}{\sqrt{3}} & 0 & \frac{2}{\sqrt{6}} \end{array} \right]$ ，在正交变换 $X = QY$ 下，二次型 $f$ 的标准形为

$$
f = 2 y _ {2} ^ {2} + 6 y _ {3} ^ {2}.
$$

方法点评：本题综合考查了矩阵的性质、特征值与特征向量理论、正交变换法化二次型为标准形等重要知识点，综合性高、覆盖面广，且涉及的都是线性代数的重点内容，需要熟练掌握所涉及知识的理论体系的方法体系.

在解读条件 $r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = 2$ 时，一般做法是，先进行矩阵的乘法，再阶梯化，根据矩阵的秩求出 $a$ ，但这样做比较费时，如果想到性质 $r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = r(\mathbf{A})$ ，则本题运算量会大幅下降，所以熟练掌握线性代数有关方法对解题非常重要.

(22)【解】 $(\mathrm{I})P\{X = 2Y\} = P\{X = 0,Y = 0\} +P\{X = 2,Y = 1\} = \frac{1}{4}.$

（Ⅱ）由 $(X,Y)$ 的联合分布律得 $X,Y,XY$ 的分布律为

$$
X \sim \left( \begin{array}{c c c} 0 & 1 & 2 \\ \frac {1}{2} & \frac {1}{3} & \frac {1}{6} \end{array} \right), \quad Y \sim \left( \begin{array}{c c c} 0 & 1 & 2 \\ \frac {1}{3} & \frac {1}{3} & \frac {1}{3} \end{array} \right), \quad X Y \sim \left( \begin{array}{c c c} 0 & 1 & 4 \\ \frac {7}{1 2} & \frac {1}{3} & \frac {1}{1 2} \end{array} \right),
$$

于是 $E(X) = \frac{2}{3}, E(Y) = 1, E(Y^2) = \frac{5}{3}, D(Y) = E(Y^2) - [E(Y)]^2 = \frac{2}{3}, E(XY) = \frac{2}{3}$ ,

$$
\operatorname {C o v} (X, Y) = E (X Y) - E (X) E (Y) = 0,
$$

故 $\operatorname{Cov}(X - Y, Y) = \operatorname{Cov}(X, Y) - D(Y) = -\frac{2}{3}$ .

(23)【解】（I）因为 $X, Y$ 相互独立，所以 $Z = X - Y$ 服从正态分布.

因为 $E(Z) = E(X) - E(Y) = 0, D(Z) = D(X) + D(Y) = 3\sigma^2$ ，所以 $Z \sim N(0, 3\sigma^2)$ ，故 $Z$ 的密度为

$$
f _ {Z} (z) = \frac {1}{\sqrt {6 \pi} \sigma} \mathrm {e} ^ {- \frac {z ^ {2}}{6 \sigma^ {2}}} (- \infty <   z <   + \infty).
$$

（Ⅱ）似然函数为 $L = f(z_{1})f(z_{2})\dots f(z_{n}) = (6\pi \sigma^{2})^{-\frac{n}{2}}\mathrm{e}^{-\frac{1}{6\sigma^{2}}\sum_{i = 1}^{n}z_{i}^{2}},$

取对数得 $\ln L = -\frac{n}{2}\ln 6\pi -\frac{n}{2}\ln \sigma^2 -\frac{1}{6\sigma^2}\sum_{i = 1}^{n}z_i^2,$

由 $\frac{\mathrm{d}}{\mathrm{d}(\sigma^2)}\ln L = -\frac{n}{2\sigma^2} +\frac{1}{6\sigma^4}\sum_{i = 1}^{n}z_i^2 = 0$ ，得 $\sigma^2 = \frac{1}{3n}\sum_{i = 1}^{n}z_i^2$

故 $\sigma^2$ 的最大似然估计量为 $\hat{\sigma}^2 = \frac{1}{3n}\sum_{i = 1}^{n}Z_i^2$

（Ⅲ）因为 $E(\hat{\sigma}^2) = \frac{1}{3n}\sum_{i = 1}^{n}E(Z_i^2) = \frac{1}{3} E(Z^2) = \frac{1}{3} [D(Z) + (E(Z))^2 ] = \sigma^2,$

所以 $\hat{\sigma}^2 = \frac{1}{3n}\sum_{i = 1}^{n}Z_i^2$ 是 $\sigma^2$ 的无偏估计量.