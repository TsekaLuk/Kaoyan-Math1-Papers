# 2004年数学(一）真题解析

# 一、填空题

（1）【答案】 $y = x - 1$

【解】设曲线 $y = \ln x$ 上切点坐标为 $(a, \ln a)$

因为 $x + y = 1$ 的斜率为 $-1$ ，所以切线的斜率为1.

令 $\frac{1}{a} = 1$ 得 $a = 1$ ，切点为(1，0)，切线为 $y - 0 = x - 1$ ，即 $y = x - 1$

(2)【答案】 $\frac{1}{2} (\ln x)^2$

【解】令 $\mathrm{e}^x = t$ ，由 $f^{\prime}(\mathrm{e}^{x}) = x\mathrm{e}^{-x}$ ，得 $f^{\prime}(t) = \frac{\ln t}{t}$ ，从而 $f^{\prime}(x) = \frac{\ln x}{x}$

于是 $f(x) = \frac{1}{2} (\ln x)^2 + C$ ，由 $f(1) = 0$ 得 $C = 0$ ，故 $f(x) = \frac{1}{2} (\ln x)^2$ .

(3)【答案】 $\frac{3\pi}{2}$ .

【解】 方法一 令 $A(\sqrt{2},0),B(0,\sqrt{2})$ ，则

$$
\int_ {L} x \mathrm {d} y - 2 y \mathrm {d} x = \oint_ {L + \overline {{B O}} + \overline {{O A}}} x \mathrm {d} y - 2 y \mathrm {d} x + \int_ {\overline {{O B}}} x \mathrm {d} y - 2 y \mathrm {d} x - \int_ {\overline {{O A}}} x \mathrm {d} y - 2 y \mathrm {d} x,
$$

$$
\oint_ {L + \overline {{B O}} + \overline {{O A}}} x \mathrm {d} y - 2 y \mathrm {d} x = 3 \iint_ {D} \mathrm {d} x \mathrm {d} y = 3 \times \frac {1}{4} \times 2 \pi = \frac {3 \pi}{2},
$$

$$
\int_ {\overline {{O B}}} x \mathrm {d} y - 2 y \mathrm {d} x = 0, \quad \int_ {\overline {{O A}}} x \mathrm {d} y - 2 y \mathrm {d} x = 0,
$$

于是 $\int_{L}x\mathrm{d}y - 2y\mathrm{d}x = \frac{3\pi}{2}$

方法二 令 $\left\{ \begin{array}{l} x = \sqrt{2} \cos \theta, \\ y = \sqrt{2} \sin \theta \end{array} \right.$ （起点 $\theta = 0$ ，终点 $\theta = \frac{\pi}{2}$ ），则

$$
\begin{array}{l} \int_ {L} x \mathrm {d} y - 2 y \mathrm {d} x = \int_ {0} ^ {\frac {\pi}{2}} (\sqrt {2} \cos \theta \cdot \sqrt {2} \cos \theta + 2 \sqrt {2} \sin \theta \cdot \sqrt {2} \sin \theta) \mathrm {d} \theta \\ = 2 \int_ {0} ^ {\frac {\pi}{2}} (1 + \sin^ {2} \theta) d \theta = \pi + 2 I _ {2} = \frac {3 \pi}{2}. \\ \end{array}
$$

（4）【答案】 $y = \frac{C_1}{x} +\frac{C_2}{x^2} (C_1,C_2$ 为任意常数).

【解】令 $x = \mathrm{e}^{t}$ ，则 $x^{2}\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}} = \mathrm{D}(\mathrm{D} - 1)y = \frac{\mathrm{d}^{2}y}{\mathrm{d}t^{2}} -\frac{\mathrm{d}y}{\mathrm{d}t},$ $x\frac{\mathrm{dy}}{\mathrm{dx}} = \mathrm{Dy} = \frac{\mathrm{dy}}{\mathrm{dt}},$

代入原方程得 $\frac{\mathrm{d}^2y}{\mathrm{d}t^2} + 3\frac{\mathrm{d}y}{\mathrm{d}t} + 2y = 0$ ，通解为 $y = C_1\mathrm{e}^{-t} + C_2\mathrm{e}^{-2t}$

故原方程的通解为 $y = \frac{C_1}{x} + \frac{C_2}{x^2} (C_1, C_2$ 为任意常数).

(5)【答案】 $\frac{1}{9}$ .

【解】 $|\mathbf{A}| = 3$ ，在 $\mathbf{ABA}^{*} = 2\dot{\mathbf{BA}}^{*} + \mathbf{E}$ 两边右乘 $\mathbf{A}$ ，得 $3\mathbf{AB} = 6\mathbf{B} + \mathbf{A}$ 或 $3(A - 2E)\mathbf{B} = \mathbf{A}$ 于是 $3^{3}|\mathbf{A} - 2\mathbf{E}|\cdot |\mathbf{B}| = |\mathbf{A}|$

而 $\mathbf{A} - 2\mathbf{E} = \begin{pmatrix} 0 & 1 & 0\\ 1 & 0 & 0\\ 0 & 0 & -1 \end{pmatrix}$ $|\mathbf{A} - 2\mathbf{E}| = 1$ ，故 $|\pmb {B}| = \frac{1}{9}$

方法点评：本题考查由矩阵关系等式确定的矩阵的行列式

本题的关键是要应用公式 $AA^{*} = A^{*}A = |A|E$

(6)【答案】 $\frac{1}{\mathrm{e}}$

【解】由 $X \sim E(\lambda)$ ，得 $D(X) = \frac{1}{\lambda^2}$ ，且其分布函数为 $F(x) = \begin{cases} 0, & x < 0, \\ 1 - \mathrm{e}^{-\lambda x}, & x \geqslant 0, \end{cases}$ 于是 $P\{X > \sqrt{D(X)}\} = P\left\{X > \frac{1}{\lambda}\right\} = 1 - P\left\{X \leqslant \frac{1}{\lambda}\right\} = 1 - F\left(\frac{1}{\lambda}\right) = \frac{1}{\mathrm{e}}.$

# 二、选择题

（7）【答案】 (B).

【解】方法一 由 $\lim_{x\to 0^{+}}\frac{\alpha}{x} = \lim_{x\to 0^{+}}\frac{\int_{0}^{x}\cos t^{2}\mathrm{d}t}{x} = \lim_{x\to 0^{+}}\cos x^{2} = 1$ ，得 $\alpha \sim x$

由 $\lim_{x\to 0^{+}}\frac{\beta}{x^{m}} = \lim_{x\to 0^{+}}\frac{\int_{0}^{x^{2}}\tan\sqrt{t}\mathrm{d}t}{x^{m}} = \lim_{x\to 0^{+}}\frac{2x\tan x}{mx^{m - 1}}$ ，得 $m - 1 = 2$ ，即 $m = 3$ ，且 $\lim_{x\to 0^{+}}\frac{\beta}{x^3} = \frac{2}{3}$

于是 $\beta \sim \frac{2}{3} x^3$

由 $\lim_{x\to 0^{+}}\frac{\gamma}{x^m} = \lim_{x\to 0^{+}}\frac{\int_0^{\sqrt{x}}\sin t^3\mathrm{d}t}{x^m} = \lim_{x\to 0^{+}}\frac{\frac{1}{2\sqrt{x}}\sin x\sqrt{x}}{mx^{m - 1}}$ 得 $m - 1 = 1$ ，即 $m = 2$ ，且 $\lim_{x\to 0^{+}}\frac{\gamma}{x^2} = \frac{1}{4}$ 于是 $\gamma \sim \frac{1}{4} x^2$

故无穷小量从低阶到高阶的次序为 $\alpha, \gamma, \beta$ ，应选（B）.

方法二 因为 $\lim_{x\to 0^{+}}\frac{\alpha}{\beta} = \lim_{x\to 0^{+}}\frac{\int_{0}^{x}\cos t^{2}\mathrm{d}t}{\int_{0}^{x^{2}}\tan\sqrt{t}\mathrm{d}t} = \lim_{x\to 0^{+}}\frac{\cos x^{2}}{2x\tan x} = +\infty$

$$
\lim  _ {x \rightarrow 0 ^ {+}} \frac {\beta}{\gamma} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {\int_ {0} ^ {x ^ {2}} \tan \sqrt {t} \mathrm {d} t}{\int_ {0} ^ {\sqrt {x}} \sin t ^ {3} \mathrm {d} t} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {2 x \tan x}{\frac {1}{2 \sqrt {x}} \cdot \sin x \sqrt {x}} = 0,
$$

$$
\lim  _ {x \rightarrow 0 ^ {+}} \frac {\gamma}{\alpha} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {\int_ {0} ^ {\sqrt {x}} \sin t ^ {3} \mathrm {d} t}{\int_ {0} ^ {x} \cos t ^ {2} \mathrm {d} t} = \lim  _ {x \rightarrow 0 ^ {+}} \frac {\frac {1}{2 \sqrt {x}} \cdot \sin x \sqrt {x}}{\cos x ^ {2}} = 0,
$$

所以无穷小量的阶数从低阶到高阶的次序为 $\alpha, \gamma, \beta$ ，应选（B）

方法三 由 $t \to 0^+$ 时， $\cos t^2 \to 1, \tan \sqrt{t} \sim \sqrt{t}, \sin t^3 \sim t^3$ 得

$$
\alpha \sim \int_ {0} ^ {x} 1 \mathrm {d} t = x, \beta \sim \int_ {0} ^ {x ^ {2}} \sqrt {t} \mathrm {d} t = \frac {2}{3} t ^ {\frac {3}{2}} | _ {0} ^ {x ^ {2}} = \frac {2}{3} x ^ {3}, \gamma \sim \int_ {0} ^ {\sqrt {x}} t ^ {3} \mathrm {d} t = \frac {1}{4} x ^ {2},
$$

显然无穷小量从低阶到高阶的次序为 $\alpha, \gamma, \beta$ ，应选（B）.

方法点评：本题考查无穷小量阶数的比较. 判断无穷小量的阶数有如下几种常用的方法：

（1）等价无穷小.如： $\sqrt[3]{1 + x^2} - 1 \sim \frac{1}{3} x^2$   
（2）麦克劳林公式.如： $x - \sin x = x - \left[x - \frac{x^3}{3!} +o(x^3)\right]\sim \frac{1}{6} x^3;$   
（3）待定阶数法.如： $\alpha = \int_{0}^{x^2}\frac{\tan t}{t}\mathrm{d}t$ ，由 $\lim_{x\to 0}\frac{\alpha}{x^m} = \lim_{x\to 0}\frac{2x\cdot\frac{\tan x^2}{x^2}}{mx^{m - 1}} = \lim_{x\to 0}\frac{2x}{mx^{m - 1}},$ 得 $m - 1 = 1$ ，即 $m = 2$ ，得 $\alpha \sim x^2$

（8）【答案】 (C).

【解】 根据导数的定义， $f^{\prime}(0) = \lim_{x\to 0}\frac{f(x) - f(0)}{x} >0.$

由极限保号性，存在 $\delta >0$ ，当 $0 < |x| < \delta$ 时， $\frac{f(x) - f(0)}{x} >0.$

于是当 $x\in (-\delta ,0)$ 时， $f(x) <   f(0)$ ；当 $x\in (0,\delta)$ 时， $f(x) > f(0)$ ，应选(C).

方法点评：本题考查极限保号性的应用。函数在一点导数大于（小于）零与函数在一个区间内大于（小于）零是不同的，需要作如下补充说明：

（1）函数在一点导数大于（小于）零的情形

若 $f^{\prime}(a) > 0$ ，由导数的定义， $f^{\prime}(a) = \lim_{x\to a}\frac{f(x) - f(a)}{x - a} >0$ ，由极限的保号性，存在 $\delta >0$ 当 $0 < |x - a| < \delta$ 时 $\frac{f(x) - f(a)}{x - a} >0$ ，于是有 $\left\{ \begin{array}{ll}f(x) <   f(a), & x\in (a - \delta ,a),\\ f(x) > f(a), & x\in (a,a + \delta), \end{array} \right.$ 但 $f(x)$ 在 $x = a$ 的去心邻域内不一定单调增加；

若 $f^{\prime}(a) < 0$ ，由导数的定义， $f^{\prime}(a) = \lim_{x\to a}\frac{f(x) - f(a)}{x - a} < 0$ ，由极限的保号性，存在 $\delta >0$ 当 $0 < |x - a| < \delta$ 时， $\frac{f(x) - f(a)}{x - a} < 0$ ，于是有 $\left\{ \begin{array}{ll}f(x) > f(a), & x\in (a - \delta ,a),\\ f(x) <   f(a), & x\in (a,a + \delta), \end{array} \right.$ 但 $f(x)$ 在 $x = a$ 的去心邻域内不一定单调减少.

注意函数在一点处的导数大于(小于)零不能推出函数在该点邻域内单调递增(递减),

如： $f(x) = \left\{ \begin{array}{ll} \frac{1}{2} x + x^2\cos \frac{1}{x}, & x\neq 0,\\ 0, & x = 0, \end{array} \right.$ 显然 $f(x)$ 在 $x = 0$ 处连续.

又 $\lim_{x\to 0}\frac{f(x) - f(0)}{x} = \lim_{x\to 0}\left(\frac{1}{2} +x\cos \frac{1}{x}\right) = \frac{1}{2} >0,$

当 $x \neq 0$ 时， $f'(x) = \frac{1}{2} + 2x\cos \frac{1}{x} + \sin \frac{1}{x}$ ，

因为 $f^{\prime}\left(\frac{1}{2n\pi + \frac{\pi}{2}}\right) = \frac{3}{2} > 0, f^{\prime}\left(\frac{1}{2n\pi - \frac{\pi}{2}}\right) = -\frac{1}{2} < 0$ ，所以 $f^{\prime}(x)$ 在 $x = 0$ 的去心邻域内不保正号， $f(x)$ 在 $x = 0$ 的邻域内不单调.

（2）若 $f^{\prime}(x)$ 在 $x = a$ 的去心邻域内保正号或负号，则 $f(x)$ 在 $x = a$ 的去心邻域内单调增加或单调减少.

（9）【答案】 （B）.

【解】方法一 取 $a_{n} = \frac{1}{n\ln(n + 1)}$ ，显然 $\lim_{n\to \infty}na_n = 0$ ，但级数 $\sum_{n = 1}^{\infty}a_n = \sum_{n = 1}^{\infty}\frac{1}{n\ln(n + 1)}$ 发散，（A）不对；

取 $a_{n} = \frac{1}{n^{\frac{3}{2}}}$ ，级数 $\sum_{n = 1}^{\infty}a_n = \sum_{n = 1}^{\infty}\frac{1}{n^{\frac{3}{2}}}$ 收敛，但 $\lim_{n\to \infty}n^{2}a_{n} = \lim_{n\to \infty}\sqrt{n} = +\infty$ ，（C）不对；

取 $a_{n} = \frac{1}{\ln(n + 1)}$ ，级数 $\sum_{n = 1}^{\infty}a_n = \sum_{n = 1}^{\infty}\frac{1}{\ln(n + 1)}$ 发散，但 $\lim_{n\to \infty}na_n = +\infty$ ，(D)不对，应选(B).

方法二 设 $\lim_{n\to \infty}na_n = \lambda >0$ ，取 $\varepsilon_0 = \frac{\lambda}{2} >0$ ，因为 $\lim_{n\to \infty}na_n = \lambda$ ，所以存在 $N$ ，当 $n > N$ 时， $|na_{n} - \lambda| < \frac{\lambda}{2}$ ，于是 $na_{n} > \frac{\lambda}{2}$ 或 $a_{n} > \frac{\lambda}{2n}$

而 $\sum_{n = 1}^{\infty}\frac{\lambda}{2n}$ 发散，由正项级数的比较审敛法得 $\sum_{n = 1}^{\infty}a_{n}$ 发散，应选（B）.

(10)【答案】 (B).

【解】 方法一 交换积分次序，得

$$
F (t) = \int_ {1} ^ {t} d y \int_ {y} ^ {t} f (x) d x = \int_ {1} ^ {t} d x \int_ {1} ^ {x} f (x) d y = \int_ {1} ^ {t} (x - 1) f (x) d x,
$$

$F^{\prime}(t) = (t - 1)f(t)$ ，则 $F^{\prime}(2) = (2 - 1)f(2) = f(2)$ ，应选（B）.

方法二 令 $G(x) = \int_{1}^{x}f(t)\mathrm{d}t$ ，则

$$
\begin{array}{l} F (t) = \int_ {1} ^ {t} d y \int_ {y} ^ {t} f (x) d x = \int_ {1} ^ {t} [ G (t) - G (y) ] d y \\ = (t - 1) G (t) - \int_ {1} ^ {t} G (y) d y, \\ \end{array}
$$

$F^{\prime}(t) = G(t) + (t - 1)G^{\prime}(t) - G(t) = (t - 1)f(t)$ ，于是 $F^{\prime}(2) = f(2)$ ，应选(B).

(11)【答案】 (D).

【解】 由初等变换的定义，得

$$
\begin{array}{r} {\pmb {B} = \pmb {A} \left( \begin{array}{c c c} {0} & {1} & {0} \\ {1} & {0} & {0} \\ {0} & {0} & {1} \end{array} \right), \quad \pmb {C} = \pmb {B} \left( \begin{array}{c c c} {1} & {0} & {0} \\ {0} & {1} & {1} \\ {0} & {0} & {1} \end{array} \right),} \end{array}
$$

于是 $\pmb {C} = \pmb {A}\left( \begin{array}{lll}0 & 1 & 0\\ 1 & 0 & 0\\ 0 & 0 & 1 \end{array} \right)\left( \begin{array}{lll}1 & 0 & 0\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{array} \right),$

故 $Q = \begin{pmatrix} 0 & 1 & 0\\ 1 & 0 & 0\\ 0 & 0 & 1 \end{pmatrix} \begin{pmatrix} 1 & 0 & 0\\ 0 & 1 & 1\\ 0 & 0 & 1 \end{pmatrix} = \begin{pmatrix} 0 & 1 & 1\\ 1 & 0 & 0\\ 0 & 0 & 1 \end{pmatrix}$ ，应选(D).

（12）【答案】 (A).

【解】 方法一 设 $\mathbf{A}$ 为 $m\times n$ 矩阵， $\pmb{B}$ 为 $n\times s$ 矩阵

由 $\mathbf{AB} = \mathbf{0}$ ，得 $r(\mathbf{A}) + r(\mathbf{B})\leqslant n$

因为 $A, B$ 为非零矩阵，所以 $r(A) \geqslant 1, r(B) \geqslant 1$ ，于是 $r(A) < n, r(B) < n$

因为矩阵的秩、矩阵行向量组的秩、矩阵列向量组的秩都相等，于是 $\mathbf{A}$ 的列向量组的秩小于列数， $\mathbf{B}$ 的行向量组的秩小于行数， $\mathbf{A}$ 的列向量组线性相关， $\mathbf{B}$ 的行向量组线性相关，应选(A).

方法二

设 $\mathbf{A} = \begin{bmatrix} a_{11} & a_{12} & \dots & a_{1n}\\ a_{21} & a_{22} & \dots & a_{2n}\\ \vdots & \vdots & & \vdots \\ a_{m1} & a_{m2} & \dots & a_{mn} \end{bmatrix} = (\pmb {\alpha}_1,\pmb {\alpha}_2,\dots ,\pmb {\alpha}_n),\pmb {B} = \begin{bmatrix} b_{11} & b_{12} & \dots & b_{1s}\\ b_{21} & b_{22} & \dots & b_{2s}\\ \vdots & \vdots & & \vdots \\ b_{n1} & b_{n2} & \dots & b_{ns} \end{bmatrix} = \begin{bmatrix} \pmb {\beta}_1\\ \pmb {\beta}_2\\ \vdots \\ \pmb {\beta}_n \end{bmatrix}$

由 $AB = O$ 得

$$
\begin{array}{r l} & {\left\{ \begin{array}{l l} {b _ {1 1} \pmb {\alpha} _ {1} + b _ {2 1} \pmb {\alpha} _ {2} + \dots + b _ {n 1} \pmb {\alpha} _ {n} = \mathbf {0},} \\ {b _ {1 2} \pmb {\alpha} _ {1} + b _ {2 2} \pmb {\alpha} _ {2} + \dots + b _ {n 2} \pmb {\alpha} _ {n} = \mathbf {0},} \end{array} \right. \text {及}} \\ & {\vdots} \\ & {b _ {1 s} \pmb {\alpha} _ {1} + b _ {2 s} \pmb {\alpha} _ {2} + \dots + b _ {n s} \pmb {\alpha} _ {n} = \mathbf {0}.} \end{array}
$$

因为 $\mathbf{A},\mathbf{B}$ 为非零矩阵，所以存在不全为零的常数 $b_{1j},b_{2j},\dots ,b_{nj}$ 及 $a_{i1},a_{i2},\dots ,a_{in}$ ，使得 $b_{1j}\pmb{\alpha}_{1} + b_{2j}\pmb{\alpha}_{2} + \dots +b_{nj}\pmb{\alpha}_{n} = \mathbf{0}$ 及 $a_{i1}\pmb {\beta}_1 + a_{i2}\pmb {\beta}_2 + \dots +a_{in}\pmb {\beta}_n = \mathbf{0}$

即 $\alpha_{1},\alpha_{2},\dots ,\alpha_{n}$ 与 $\beta_{1},\beta_{2},\dots ,\beta_{n}$ 都线性相关，应选（A）.

方法点评：当研究矩阵的秩与向量相关性时，一般使用矩阵的秩、矩阵行向量组的秩、矩阵列向量组的秩相等的性质.

向量组线性相关的充要条件是该向量组的秩小于向量组所含向量的个数；向量组线性无关的充要条件是向量组的秩与向量组所含向量个数相等.

（13）【答案】 (C).

【解】由 $P\{|X| < x\} = 1 - P\{|X| \geqslant x\} = 1 - 2P\{X \geqslant x\} = \alpha$ ，得 $P\{X \geqslant x\} = \frac{1 - \alpha}{2}$

再由 $P\{X > u_{\alpha}\} = \alpha$ ，得 $x = u_{\frac{1 - \alpha}{2}}$ ，应选(C).

（14）【答案】 (A).

【解】 $\operatorname {Cov}(X_1,Y) = \frac{1}{n} [\operatorname {Cov}(X_1,X_1) + \operatorname {Cov}(X_1,X_2) + \dots +\operatorname {Cov}(X_1,X_n)]$

因为 $X_{1}, X_{2}, \dots, X_{n}$ 相互独立，所以 $\operatorname{Cov}(X_1, X_i) = 0 (i = 2, 3, \dots, n)$ ，

于是 $\operatorname{Cov}(X_1, Y) = \frac{1}{n} D(X_1) = \frac{\sigma^2}{n}$ ，应选（A）.

方法点评：随机变量数字特征计算中要熟练掌握如下几个性质：

（1）若 $X,Y$ 相互独立，则 $\operatorname {Cov}(X,Y) = 0$   
（2）若 $X_{1}, X_{2}, \dots, X_{n}$ 是总体 $X$ 的简单随机样本，则 $E(\overline{X}) = E(X), D(\overline{X}) = \frac{1}{n} D(X)$ .

# 三、解答题

（15）【证明】 方法一 辅助函数法（单调性）

$\ln^2 b - \ln^2 a > \frac{4}{\mathrm{e}^2} (b - a)$ 等价于 $\ln^2 b - \ln^2 a - \frac{4}{\mathrm{e}^2} (b - a) > 0$

令 $f(x) = \ln^2 x - \ln^2 a - \frac{4}{\mathrm{e}^2} (x - a), f(a) = 0.$

$f^{\prime}(x) = \frac{2\ln x}{x} -\frac{4}{\mathrm{e}^{2}}$ 因为 $f''(x) = \frac{2(1 - \ln x)}{x^2} < 0(x > \mathrm{e})$ ，所以当 $x > \mathrm{e}$ 时， $f^{\prime}(x)$ 单调减少.

由 $\left\{ \begin{array}{l} f^{\prime}(\mathrm{e}^{2}) = 0, \\ f^{\prime \prime}(x) < 0 (x > \mathrm{e}), \end{array} \right.$ 得 $f^{\prime}(x) > 0 (\mathrm{e} < x < \mathrm{e}^{2})$ ，即 $f(x)$ 在 $(\mathrm{e}, \mathrm{e}^{2})$ 内单调增加，由 $\mathrm{e} < a < b < \mathrm{e}^{2}$ 及 $f(a) = 0$ 得 $f(b) > 0$ ，故 $\ln^2 b - \ln^2 a > \frac{4}{\mathrm{e}^2} (b - a)$ .

# 方法二 中值定理法

$\ln^2 b - \ln^2 a > \frac{4}{\mathrm{e}^2} (b - a)$ 等价于 $\frac{\ln^2b - \ln^2a}{b - a} >\frac{4}{\mathrm{e}^2}.$

令 $f(x) = \ln^2 x, f'(x) = \frac{2\ln x}{x}$ ，由微分中值定理得

$$
\frac {\ln^ {2} b - \ln^ {2} a}{b - a} = \frac {2 \ln c}{c}, \text {其 中} c \in (a, b).
$$

令 $\varphi (x) = \frac{2\ln x}{x}$ ，因为 $\varphi^{\prime}(x) = \frac{2(1 - \ln x)}{x^{2}} < 0(x > e)$ ，所以 $\varphi (x)$ 在 $(\mathrm{e},\mathrm{e}^2)$ 内单调减少且 $\varphi (\mathrm{e}^2) = \frac{4}{\mathrm{e}^2}$ ，从而 $\frac{2\ln c}{c} >\frac{4}{\mathrm{e}^2}$ 即 $\frac{\ln^2b - \ln^2a}{b - a} >\frac{4}{\mathrm{e}^2}.$

（16）【解】方法一 设飞机着陆时 $t = 0$ ，从着陆开始的 $t$ 时刻飞机速度为 $v(t)$

由牛顿第二定律得 $F_{\text{阻}} = ma$ ，由题意得 $\left\{ \begin{array}{l} m \frac{\mathrm{d}v}{\mathrm{d}t} = -kv, \\ v(0) = 700. \end{array} \right.$

由 $m\frac{\mathrm{d}v}{\mathrm{d}t} = -kv$ ，得 $m\frac{\mathrm{d}v}{\mathrm{d}x}\cdot \frac{\mathrm{d}x}{\mathrm{d}t} = -kv$ ，即 $m\mathrm{d}v = -k\mathrm{d}x$ ，积分得 $mv = -kx + C$

由 $v(0) = 700, x(0) = 0$ ，得 $C = 700m$ ，于是 $x = \frac{1}{k} (700 - v)m$

取 $v = 0$ 得 $x = \frac{1}{6 \times 10^6} \times 700 \times 9000 = 1.05(\mathrm{km})$ ，即飞机从着陆到停止最长可以滑行1.05千米.

方法二 设从着陆 $(t = 0)$ 开始 $t$ 时刻飞机滑行的速度为 $v(t)$ ，根据题意得

$$
\left\{ \begin{array}{l} m \frac {\mathrm {d} v}{\mathrm {d} t} = - k v, \\ v (0) = 7 0 0. \end{array} \right.
$$

由 $m\frac{\mathrm{d}v}{\mathrm{d}t} = -kv$ ，得 $\frac{\mathrm{d}v}{\mathrm{d}t} +\frac{k}{m} v = 0$ ，解得 $v(t) = C\mathrm{e}^{-\int \frac{k}{m}\mathrm{d}t} = C\mathrm{e}^{-\frac{k}{m} t},$

由 $v(0) = 700$ 得 $C = 700$ ，于是 $v(t) = 700\mathrm{e}^{-\frac{k}{m} t}$

故飞机滑行的最大距离为

$$
\begin{array}{l} S = \int_ {0} ^ {+ \infty} v (t) d t = 7 0 0 \int_ {0} ^ {+ \infty} e ^ {- \frac {k}{m} t} d t \\ = \frac {7 0 0 m}{k} \int_ {0} ^ {+ \infty} \mathrm {e} ^ {- \frac {k}{m} t} \mathrm {d} \left(\frac {k}{m} t\right) = \frac {7 0 0 m}{k} \Gamma (1) = \frac {7 0 0 m}{k} = 1. 0 5 (\mathrm {k m}). \\ \end{array}
$$

（17）【解】补充 $\Sigma_0: z = 0 (x^2 + y^2 \leqslant 1)$ ，取下侧，

$$
I = (\iint_ {\Sigma + \Sigma_ {0}} - \iint_ {\Sigma_ {0}}) 2 x ^ {3} d y d z + 2 y ^ {3} d z d x + 3 (z ^ {2} - 1) d x d y,
$$

由高斯公式得

$$
\begin{array}{l} \oiint_ {\Sigma + \Sigma_ {0}} 2 x ^ {3} \mathrm {d} y \mathrm {d} z + 2 y ^ {3} \mathrm {d} z \mathrm {d} x + 3 (z ^ {2} - 1) \mathrm {d} x \mathrm {d} y = 6 \iiint_ {\Omega} (x ^ {2} + y ^ {2} + z) \mathrm {d} v, \\ = 6 \int_ {0} ^ {1} d z \iint_ {x ^ {2} + y ^ {2} \leqslant 1 - z} (x ^ {2} + y ^ {2} + z) d x d y = 6 \int_ {0} ^ {1} d z \int_ {0} ^ {2 \pi} d \theta \int_ {0} ^ {\sqrt {1 - z}} r (r ^ {2} + z) d r \\ = 1 2 \pi \int_ {0} ^ {1} \left[ \frac {(1 - z) ^ {2}}{4} + \frac {z (1 - z)}{2} \right] d z = 3 \pi \int_ {0} ^ {1} (1 - z ^ {2}) d z = 2 \pi , \\ \end{array}
$$

而 $\iint_{\Sigma_0} 2x^3 \, \mathrm{d}y \, \mathrm{d}z + 2y^3 \, \mathrm{d}z \, \mathrm{d}x + 3(z^2 - 1) \, \mathrm{d}x \, \mathrm{d}y = -3\iint_{\Sigma_0} \mathrm{d}x \, \mathrm{d}y = 3\iint_{D} \mathrm{d}x \, \mathrm{d}y = 3\pi,$

故 $\iint_{\Sigma} 2x^3 \, \mathrm{d}y \, \mathrm{d}z + 2y^3 \, \mathrm{d}z \, \mathrm{d}x + 3(z^2 - 1) \, \mathrm{d}x \, \mathrm{d}y = 2\pi - 3\pi = -\pi.$

（18）【证明】令 $f(x) = x^{n} + nx - 1$ ， $f(0) = -1$ ， $f(1) = n$

因为 $f(0)f(1) < 0$ ，所以由零点定理，存在 $x_{n} \in (0,1)$ ，使得 $f(x_{n}) = 0$ ，即方程 $x^{n} + nx - 1 = 0$ 有正根 $x_{n}$

因为 $f^{\prime}(x) = nx^{n - 1} + n > 0 (x > 0)$ ，所以 $f(x)$ 在 $[0, +\infty)$ 上单调增加，

故 $x^n + nx - 1 = 0$ 存在唯一的正根 $x_n$ .

由 $x_{n}^{n} + nx_{n} - 1 = 0$ 得 $0 < x_{n} = \frac{1}{n} (1 - x_{n}^{n}) < \frac{1}{n}$ ，于是 $0 < x_{n}^{\alpha} < \frac{1}{n^{\alpha}}$

因为 $\alpha > 1$ 时 $\sum_{n=1}^{\infty} \frac{1}{n^{\alpha}}$ 收敛, 所以由正项级数的比较审敛法得 $\sum_{n=1}^{\infty} x_{n}^{\alpha}$ 收敛.

(19)【解】方法一 $x^{2} - 6xy + 10y^{2} - 2yz - z^{2} + 18 = 0$ 两边对 $x$ 求偏导，

得 $2x - 6y - 2y\frac{\partial z}{\partial x} - 2z\frac{\partial z}{\partial x} = 0$ ，解得 $\frac{\partial z}{\partial x} = \frac{x - 3y}{y + z}$

$x^{2} - 6xy + 10y^{2} - 2yz - z^{2} + 18 = 0$ 两边对 $y$ 求偏导，

得 $-6x + 20y - 2z - 2y\frac{\partial z}{\partial y} - 2z\frac{\partial z}{\partial y} = 0$ ，解得 $\frac{\partial z}{\partial y} = \frac{-3x + 10y - z}{y + z}$

由 $\left\{ \begin{array}{l} \frac{\partial z}{\partial x} = \frac{x - 3y}{y + z} = 0, \\ \frac{\partial z}{\partial y} = \frac{-3x + 10y - z}{y + z} = 0, \end{array} \right.$ 得 $\left\{ \begin{array}{l} x = 9, \\ y = 3 \end{array} \right.$ 或 $\left\{ \begin{array}{l} x = -9, \\ y = -3. \end{array} \right.$

当 $(x,y) = (9,3)$ 时，

$$
A = \frac {\partial^ {2} z}{\partial x ^ {2}} \Bigg | _ {(9, 3)} = \frac {1}{6}, \quad B = \frac {\partial^ {2} z}{\partial x \partial y} \Bigg | _ {(9, 3)} = - \frac {1}{2}, \quad C = \frac {\partial^ {2} z}{\partial y ^ {2}} \Bigg | _ {(9, 3)} = \frac {5}{3},
$$

因为 $AC - B^2 = \frac{1}{36} > 0$ 且 $A > 0$ ，所以当 $(x, y) = (9, 3)$ 时，函数 $z = f(x, y)$ 取极小值 $f(9, 3) = 3$

当 $(x,y) = (-9, - 3)$ 时，

$$
A = \frac {\partial^ {2} z}{\partial x ^ {2}} \Bigg | _ {(- 9, - 3)} = - \frac {1}{6}, \quad B = \frac {\partial^ {2} z}{\partial x \partial y} \Bigg | _ {(- 9, - 3)} = \frac {1}{2}, \quad C = \frac {\partial^ {2} z}{\partial y ^ {2}} \Bigg | _ {(- 9, - 3)} = - \frac {5}{3},
$$

因为 $AC - B^2 = \frac{1}{36} > 0$ 且 $A < 0$ , 所以当 $(x, y) = (-9, -3)$ 时, 函数 $z = f(x, y)$ 取极大值 $f(-9, -3) = -3$ .

方法二 令 $F(x,y,z) = x^{2} - 6xy + 10y^{2} - 2yz - z^{2} + 18$

$$
F _ {x} ^ {\prime} = 2 x - 6 y, F _ {y} ^ {\prime} = - 6 x + 2 0 y - 2 z, F _ {z} ^ {\prime} = - 2 y - 2 z,
$$

由 $\begin{cases} \frac{\partial z}{\partial x} = -\frac{F_x'}{F_z'} = \frac{x - 3y}{y + z} = 0, \\ \frac{\partial z}{\partial y} = -\frac{F_y'}{F_z'} = \frac{-3x + 10y - z}{y + z} = 0, \\ x^2 - 6xy + 10y^2 - 2yz - z^2 + 18 = 0, \end{cases}$ 得 $(x,y) = (9,3)$ 或 $(x,y) = (-9, - 3)$

当 $(x,y) = (9,3)$ 时， $A = \frac{\partial^2z}{\partial x^2}\bigg|_{(9,3)} = \frac{1}{6},B = \frac{\partial^2z}{\partial x\partial y}\bigg|_{(9,3)} = -\frac{1}{2},C = \frac{\partial^2z}{\partial y^2}\bigg|_{(9,3)} = \frac{5}{3},$ 由 $AC - B^{2} = \frac{1}{36}$ 且 $A > 0$ 得 $(x,y) = (9,3)$ 为函数 $z = z(x,y)$ 的极小值点，极小值为当 $(x,y) = (-9, - 3)$ 时，

$$
A = \frac {\partial^ {2} z}{\partial x ^ {2}} \Big | _ {(- 9, - 3)} = - \frac {1}{6}, \quad B = \frac {\partial^ {2} z}{\partial x \partial y} \Big | _ {(- 9, - 3)} = \frac {1}{2}, \quad C = \frac {\partial^ {2} z}{\partial y ^ {2}} \Big | _ {(- 9, - 3)} = - \frac {5}{3},
$$

由 $AC - B^2 = \frac{1}{36}$ 且 $A < 0$ 得 $(x,y) = (-9, - 3)$ 为函数 $z = z(x,y)$ 的极大值点，极大值为-3.

（20）【解】 方法一

$$
\begin{array}{l} | \mathbf {A} | = \left| \begin{array}{c c c c} 1 + a & 1 & \dots & 1 \\ 2 & 2 + a & \dots & 2 \\ \vdots & \vdots & & \vdots \\ n & n & \dots & n + a \end{array} \right| = \left[ a + \frac {n (n + 1)}{2} \right] \left| \begin{array}{c c c c} 1 & 1 & \dots & 1 \\ 2 & 2 + a & \dots & 2 \\ \vdots & \vdots & & \vdots \\ n & n & \dots & n + a \end{array} \right| \\ = \left[ a + \frac {n (n + 1)}{2} \right] a ^ {n - 1}. \\ \end{array}
$$

当 $a = 0$ 或 $a = -\frac{n(n + 1)}{2}$ 时，方程组有非零解.

当 $a = 0$ 时，由 $\mathbf{A}\rightarrow \left[ \begin{array}{cccc}1 & 1 & \dots & 1\\ 0 & 0 & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & 0 \end{array} \right]$ 得方程组的通解为

$$
\pmb {X} = C _ {1} \left[ \begin{array}{c} {- 1} \\ {1} \\ {0} \\ {\vdots} \\ {0} \end{array} \right] + C _ {2} \left[ \begin{array}{c} {- 1} \\ {0} \\ {1} \\ {\vdots} \\ {0} \end{array} \right] + \dots + C _ {n - 1} \left[ \begin{array}{c} {- 1} \\ {0} \\ {0} \\ {\vdots} \\ {1} \end{array} \right] (C _ {1}, C _ {2}, \dots , C _ {n - 1} \text {为 任 意 常 数});
$$

当 $a = -\frac{n(n + 1)}{2}$ 时，

由 $\mathbf{A} = \begin{bmatrix} 1 + a & 1 & \dots & 1\\ 2 & 2 + a & \dots & 2\\ \vdots & \vdots & & \vdots \\ n & n & \dots & n + a \end{bmatrix} \to \begin{bmatrix} 1 + a & 1 & \dots & 1\\ -2a & a & \dots & 0\\ \vdots & \vdots & & \vdots \\ -na & 0 & \dots & a \end{bmatrix}$

$$
\rightarrow \left[\begin{array}{c c c c}1 + a&1&\dots&1\\- 2&1&\dots&0\\\vdots&\vdots&&\vdots\\- n&0&\dots&1\end{array}\right]\rightarrow \left[\begin{array}{c c c c c}- 2&1&0&\dots&0\\- 3&0&1&\dots&0\\\vdots&\vdots&\vdots&&\vdots\\- n&0&0&\dots&1\\0&0&0&\dots&0\end{array}\right],
$$

原方程组的通解为 $X = C\left[ \begin{array}{c}1\\ 2\\ \vdots \\ n \end{array} \right]$ （C为任意常数）.

方法二

$$
\mathbf {A} = \left[\begin{array}{c c c c}1 + a&1&\dots&1\\2&2 + a&\dots&2\\\vdots&\vdots&&\vdots\\n&n&\dots&n + a\end{array}\right]\rightarrow \left[\begin{array}{c c c c}a + \frac {n (n + 1)}{2}&a + \frac {n (n + 1)}{2}&\dots&a + \frac {n (n + 1)}{2}\\2&2 + a&\dots&2\\\vdots&\vdots&&\vdots\\n&n&\dots&n + a\end{array}\right],
$$

当 $a + \frac{n(n + 1)}{2} = 0$ ，即 $a = -\frac{n(n + 1)}{2}$ ，由 $r(\mathbf{A}) = n - 1 <   n$ 得原方程组有无数个解，显然 $\mathbf{A}\left[ \begin{array}{l}1\\ 2\\ \vdots \\ n \end{array} \right] = \mathbf{0}$ ，故方程组的通解为 $X = C\left[ \begin{array}{l}1\\ 2\\ \vdots \\ n \end{array} \right]$ （C为任意常数）；

当 $a + \frac{n(n + 1)}{2} \neq 0$ 时， $\mathbf{A} \rightarrow \left[ \begin{array}{cccc}1 & 1 & \dots & 1 \\ 2 & 2 + a & \dots & 2 \\ \vdots & \vdots & & \vdots \\ n & n & \dots & n + a \end{array} \right] \rightarrow \left[ \begin{array}{cccc}1 & 1 & \dots & 1 \\ 0 & a & \dots & 0 \\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & a \end{array} \right]$ ，

当 $a = 0$ 时，方程组有无数个解，由 $\mathbf{A}\rightarrow \left[ \begin{array}{cccc}1 & 1 & \dots & 1\\ 0 & 0 & \dots & 0\\ \vdots & \vdots & & \vdots \\ 0 & 0 & \dots & 0 \end{array} \right]$ 得通解为

$$
\pmb {X} = C _ {1} \left[ \begin{array}{c} {- 1} \\ {1} \\ {0} \\ {\vdots} \\ {0} \end{array} \right] + C _ {2} \left[ \begin{array}{c} {- 1} \\ {0} \\ {1} \\ {\vdots} \\ {0} \end{array} \right] + \dots + C _ {n - 1} \left[ \begin{array}{c} {- 1} \\ {0} \\ {0} \\ {\vdots} \\ {1} \end{array} \right] (C _ {1}, C _ {2}, \dots , C _ {n - 1} \text {为 任 意 常 数}).
$$

(21)【解】 $|\lambda E - A| = \left| \begin{array}{ccc}\lambda -1 & -2 & 3\\ 1 & \lambda -4 & 3\\ -1 & -a & \lambda -5 \end{array} \right| = (\lambda -2)(\lambda^2 -8\lambda +3a + 18),$

情形一： $\lambda = 2$ 为 $\mathbf{A}$ 的二重特征值，则当 $\lambda = 2$ 时， $\lambda^2 - 8\lambda + 3a + 18 = 0$ ，即 $4 - 16 + 3a + 18 = 0$ ，解得 $a = -2$ 。

$$
2 \boldsymbol {E} - \boldsymbol {A} = \left( \begin{array}{c c c} 1 & - 2 & 3 \\ 1 & - 2 & 3 \\ - 1 & 2 & - 3 \end{array} \right),
$$

因为 $r(2E - A) = 1$ ，所以方程组 $(2E - A)X = 0$ 的基础解系只含两个线性无关的解向量，即 $\lambda = 2$ 有两个线性无关的特征向量，故 $A$ 可相似对角化.

情形二： $\lambda = 2$ 为一重特征值，则 $\lambda^2 - 8\lambda + 3a + 18 = 0$ 有二重根，即 $\Delta = 64 - 4(3a + 18) = 0$ 解得 $a = -\frac{2}{3}$ ，二重特征值为 $\lambda_2 = \lambda_3 = -\frac{-8}{2} = 4.$

因为 $r(4E - A) = 2$ ，所以 $\mathbf{A}$ 不可相似对角化

方法点评：本题考查矩阵对角化.

设 $\mathbf{A}$ 是 $n$ 阶矩阵，若存在可逆矩阵 $\pmb{P}$ ，使得 $\pmb{P}^{-1}\pmb{A}\pmb{P}$ 为对角矩阵，称 $\mathbf{A}$ 可对角化，判断矩阵可否对角化有如下常见思路：

（1）若 $\mathbf{A}$ 的特征值都是单值，则 $\mathbf{A}$ 一定可以相似对角化；  
（2）若 $\mathbf{A}$ 为实对称矩阵，则 $\mathbf{A}$ 一定可以相似对角化；  
（3）若 $\mathbf{A}$ 存在 $n$ 个线性无关的特征向量，则 $\mathbf{A}$ 一定可以相似对角化；  
（4）若 $\mathbf{A}$ 的每个特征值的重数与该特征值对应的线性无关的特征向量个数相等，即若 $\lambda_0$ 为 $r$ 重特征值，且 $n - r(\lambda_0\pmb {E} - \pmb {A}) = r$ ，则 $\mathbf{A}$ 一定可相似对角化.

(22)【解】由 $P(B \mid A) = \frac{P(AB)}{P(A)}$ ，得 $P(AB) = P(A)P(B \mid A) = \frac{1}{12}$ .

又由 $P(A\mid B) = \frac{P(AB)}{P(B)}$ ，得 $P(B) = \frac{P(AB)}{P(A\mid B)} = \frac{1}{6}$

（I） $(X,Y)$ 的可能取值为 $(0,0),(0,1),(1,0),(1,1)$

$$
\begin{array}{l} P \{X = 0, Y = 0 \} = P (\overline {{A}} \overline {{B}}) = P (\overline {{A + B}}) = 1 - P (A + B) \\ = 1 - P (A) - P (B) + P (A B) = \frac {2}{3}; \\ \end{array}
$$

$$
\begin{array}{l} P \{X = 0, Y = 1 \} = P (\overline {{A}} B) = P (B) - P (A B) = \frac {1}{1 2}; \\ P \{X = 1, Y = 0 \} = P (A \overline {{B}}) = P (A) - P (A B) = \frac {1}{6}; \\ P \{X = 1, Y = 1 \} = P (A B) = \frac {1}{1 2}. \\ \end{array}
$$

$$
\begin{array}{l} (\text {I I}) X \sim \left( \begin{array}{l l} 0 & 1 \\ \frac {3}{4} & \frac {1}{4} \end{array} \right), \quad Y \sim \left( \begin{array}{l l} 0 & 1 \\ \frac {5}{6} & \frac {1}{6} \end{array} \right), \quad X Y \sim \left( \begin{array}{l l} 0 & 1 \\ \frac {1 1}{1 2} & \frac {1}{1 2} \end{array} \right), \\ E (X) = \frac {1}{4}, \quad E \left(X ^ {2}\right) = \frac {1}{4}, \quad D (X) = E \left(X ^ {2}\right) - [ E (X) ] ^ {2} = \frac {3}{1 6}, \\ E (Y) = \frac {1}{6}, \quad E \left(Y ^ {2}\right) = \frac {1}{6}, \quad D (Y) = E \left(Y ^ {2}\right) - \left[ E (Y) \right] ^ {2} = \frac {5}{3 6}, \\ \end{array}
$$

由 $E(XY) = \frac{1}{12}$ 得 $\operatorname {Cov}(X,Y) = E(XY) - E(X)E(Y) = \frac{1}{12} -\frac{1}{24} = \frac{1}{24},$

则 $\rho_{XY} = \frac{\operatorname{Cov}(X,Y)}{\sqrt{D(X)}\cdot\sqrt{D(Y)}} = \frac{\frac{1}{24}}{\frac{\sqrt{3}}{4}\times\frac{\sqrt{5}}{6}} = \frac{\sqrt{15}}{15}.$

(23)【解】（I）总体 $X$ 的密度函数为 $f(x;\beta) = \begin{cases} \frac{\beta}{x^{\beta + 1}}, & x > 1, \\ 0, & x \leqslant 1, \end{cases}$

$$
E (X) = \int_ {1} ^ {+ \infty} x f (x; \beta) d x = \beta \int_ {1} ^ {+ \infty} \frac {1}{x ^ {\beta}} d x = \frac {\beta}{\beta - 1},
$$

令 $E(X) = \overline{X}$ ，即 $\frac{\beta}{\beta - 1} = \overline{X}$ ，得 $\beta$ 的矩估计量为 $\hat{\beta} = \frac{\overline{X}}{\overline{X} - 1}$ .

（Ⅱ）似然函数为

$$
\begin{array}{l} L \left(x _ {1}, x _ {2}, \dots , x _ {n}; \beta\right) = f \left(x _ {1}, \beta\right) f \left(x _ {2}, \beta\right) \dots f \left(x _ {n}, \beta\right) \\ = \beta^ {n} \left(x _ {1} x _ {2} \dots x _ {n}\right) ^ {- \beta - 1}, \left(x _ {i} > 1, i = 1, 2, \dots , n\right), \\ \end{array}
$$

取对数得 $\ln L = n\ln \beta - (\beta + 1)\sum_{i=1}^{n}\ln x_i$

由 $\frac{\mathrm{d}\ln L}{\mathrm{d}\beta} = \frac{n}{\beta} -\sum_{i = 1}^{n}\ln x_{i} = 0$ ，得 $\beta$ 的最大似然估计值为 $\hat{\beta} = \frac{n}{\sum_{i = 1}^{n}\ln x_i}$

$\beta$ 的最大似然估计量为 $\hat{\beta} = \frac{n}{\sum_{i=1}^{n} \ln X_i}$ .