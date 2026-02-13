# 2011年数学(一)真题解析

# 一、选择题

（1）【答案】 (C).

【解】 由 $\frac{f(2) + f(3)}{2} = 0 > f\left(\frac{2 + 3}{2}\right)$ , $\frac{f(3) + f(4)}{2} = 0 < f\left(\frac{3 + 4}{2}\right)$

得（3，0）为曲线的拐点，应选(C).

（2）【答案】 (C).

【解】因为 $S_{n} = a_{1} + a_{2} + \dots +a_{n}$ 无界，所以 $\lim_{n\to \infty}S_n$ 不存在，

于是级数 $\sum_{n=1}^{\infty} a_n$ 发散，即级数 $\sum_{n=1}^{\infty} a_n x^n$ 在 $x = 1$ 处发散；

因为 $\{a_{n}\}$ 单调递减且 $\lim_{n\to \infty}a_n = 0$ ，所以由莱布尼茨审敛法得 $\sum_{n = 1}^{\infty}(-1)^n a_n$ 收敛，

即级数 $\sum_{n=1}^{\infty} a_n x^n$ 在 $x = -1$ 处收敛，从而级数 $\sum_{n=1}^{\infty} a_n x^n$ 的收敛半径为 $R = 1$ ，且收敛域为 $[-1,1)$ ，故级数 $\sum_{n=1}^{\infty} a_n (x - 1)^n$ 的收敛域为 $-1 \leqslant x - 1 < 1$ ，即 $[0,2)$ ，应选(C).

（3）【答案】 （A）.

【解】 $\begin{array}{l}\left\{\frac{\partial z}{\partial x} = f^{\prime}(x)\ln f(y),\right.\\ \left\{\frac{\partial z}{\partial y} = \frac{f(x)f^{\prime}(y)}{f(y)},\right. \end{array}$

显然 $\frac{\partial z}{\partial x}\bigg|_{(0,0)} = 0,\frac{\partial z}{\partial y}\bigg|_{(0,0)} = 0$ ，即（0，0）为函数 $z = f(x)\ln f(y)$ 的驻点.

$$
A = \frac {\partial^ {2} z}{\partial x ^ {2}} \Bigg | _ {(0, 0)} = f ^ {\prime \prime} (0) \ln f (0), \quad B = \frac {\partial^ {2} z}{\partial x \partial y} \Bigg | _ {(0, 0)} = 0, \quad C = \frac {\partial^ {2} z}{\partial y ^ {2}} \Bigg | _ {(0, 0)} = f ^ {\prime \prime} (0),
$$

$AC - B^{2} = f^{\prime \prime 2}(0)\ln f(0)$ ，则（0，0）为 $z = f(x)\ln f(y)$ 的极小值点的一个充分条件为 $f(0) > 1,f''(0) > 0$ ，应选(A).

（4）【答案】 （B）.

【解】当 $0 < x < \frac{\pi}{4}$ 时，由 $\sin x < \cos x < \cot x$ 得 $\ln \sin x < \ln \cos x < \ln \cot x$ ，从而 $\int_{0}^{\frac{\pi}{4}} \ln \sin x \, \mathrm{d}x < \int_{0}^{\frac{\pi}{4}} \ln \cos x \, \mathrm{d}x < \int_{0}^{\frac{\pi}{4}} \ln \cot x \, \mathrm{d}x$ ，即 $I < K < J$ ，应选(B).

# 方法点评：

（1）积分限相同的几个定积分比较大小，一般比较其被积函数即可；  
(2）本题中 $\int_0^{\frac{\pi}{4}}\ln \sin x\mathrm{d}x$ 与 $\int_0^{\frac{\pi}{4}}\ln \cot x\mathrm{d}x$ 都是反常积分， $x = 0$ 为其瑕点，

$$
\int_ {0} ^ {\frac {\pi}{4}} \ln \sin x \mathrm {d} x = x \ln \sin x \left| _ {0} ^ {\frac {\pi}{4}} - \int_ {0} ^ {\frac {\pi}{4}} \frac {x \cos x}{\sin x} \mathrm {d} x, \right.
$$

因为 $\lim_{x\to 0^{+}}x\ln{\sin{x}} = \lim_{x\to 0^{+}}{\frac{x}{\sin{x}}}\cdot \sin{x}\ln{\sin{x}}\xrightarrow{t = \sin{x}}\lim_{t\to 0^{+}}{\frac{\ln{t}}{\frac{1}{t}}} = 0,$

又 $\int_0^{\frac{\pi}{4}}\frac{x\cos x}{\sin x}\mathrm{d}x$ 为正常积分，

所以 $\int_0^{\frac{\pi}{4}}\ln \sin x\mathrm{d}x$ 收敛.

$\int_0^{\frac{\pi}{4}}\ln \cot x\mathrm{d}x = \int_0^{\frac{\pi}{4}}\ln \cos x\mathrm{d}x - \int_0^{\frac{\pi}{4}}\ln \sin x\mathrm{d}x$ ，因为 $\int_0^{\frac{\pi}{4}}\ln \cos x\mathrm{d}x$ 为正常积分，所以 $\int_0^{\frac{\pi}{4}}\ln \cot x\mathrm{d}x$ 收敛，故本题按正常积分比较大小的方法比较.

（5）【答案】 (D).

【解】 由题意得 $\pmb {B} = \pmb {A}\left( \begin{array}{lll}1 & 0 & 0\\ 1 & 1 & 0\\ 0 & 0 & 1 \end{array} \right),\pmb {E} = \left( \begin{array}{lll}1 & 0 & 0\\ 0 & 0 & 1\\ 0 & 1 & 0 \end{array} \right)\pmb{B}$ ，即 $E = P_{2}AP_{1}$

从而 $\mathbf{A} = \mathbf{P}_2^{-1}\mathbf{P}_1^{-1}$ ，再由 $\pmb{P}_2^{-1} = \pmb{P}_2$ 得 $A = P_{2}P_{1}^{-1}$ ，应选(D).

方法点评：矩阵的初等变换分为初等行变换和初等列变换.其中初等行（列）变换包含：

（1）对调两行（列）；  
（2）某行（列）的非零常数倍；  
（3）某行（列）的倍数加到另一行（列）

初等矩阵有三种，即

(1) $\pmb{E}_{ij}$ ——对调 $\pmb{E}$ 的 $i, j$ 行（列）；  
(2) $\mathbf{E}_i(c)(c\neq 0)$ —— $\mathbf{E}$ 的 $i$ 行（列） $c$ 倍；  
(3) $\pmb{E}_{ij}(k)$ —— $\pmb{E}$ 的第 $j$ 行 $k$ 倍加到第 $i$ 行或 $\pmb{E}$ 的第 $i$ 列 $k$ 倍加到第 $j$ 列.

矩阵的左边乘三个初等矩阵相当于进行三种初等行变换，矩阵的右边乘三个初等矩阵相当于进行三种初等列变换，另外： $E_{ij}^{-1} = E_{ij}$ ， $\pmb{E}_i^{-1}(c) = \pmb {E}_i\left(\frac{1}{c}\right)$ ， $E_{ij}^{-1}(k) = E_{ij}(-k)$

（6）【答案】 (D).

【解】因为 $AX = 0$ 的基础解系含一个线性无关的解向量，所以 $r(A) = 3$ ，于是 $r(\mathbf{A}^{*}) = 1$ 齐次线性方程组 $\mathbf{A}^{*}\mathbf{X} = \mathbf{0}$ 的基础解系含3个线性无关的解向量，排除（A），（B）；

由 $A^{*}A = |A|E = 0$ ，得 $\alpha_{1},\alpha_{2},\alpha_{3},\alpha_{4}$ 为 $A^{*}X = 0$ 的一组解.

由 $(1,0,1,0)^{\mathrm{T}}$ 为方程组 $AX = 0$ 的解，得 $\mathbf{A}\begin{bmatrix} 1\\ 0\\ 1\\ 0 \end{bmatrix} = (\pmb {\alpha}_1,\pmb {\alpha}_2,\pmb {\alpha}_3,\pmb {\alpha}_4)\begin{bmatrix} 1\\ 0\\ 1\\ 0 \end{bmatrix} = \mathbf{0}$ ，即 $\pmb {\alpha}_1 + \pmb {\alpha}_3 = \pmb {0}$

或 $\alpha_{1} = -\alpha_{3}$ ，从而 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性相关，于是 $\alpha_{2},\alpha_{3},\alpha_{4}$ 线性无关，故 $\alpha_{2},\alpha_{3},\alpha_{4}$ 为方程组 $A^{*}X = 0$ 的一个基础解系，应选(D).

方法点评：本题是一道综合考查齐次线性方程组系数矩阵的秩与基础解系的关系及向量组相关性概念，需要熟练掌握如下重要知识点：

(1) $r(\mathbf{A}^{*}) = \left\{ \begin{array}{ll}n, & r(\mathbf{A}) = n,\\ 1, & r(\mathbf{A}) = n - 1,\\ 0, & r(\mathbf{A}) <   n - 1; \end{array} \right.$

（2）对齐次线性方程组 $AX = 0$ ，其基础解系所含的线性无关解向量的个数为 $n - r(A)$   
（3）若 $AB = O$ ，则矩阵 $\pmb{B}$ 的列向量为方程组 $AX = 0$ 的解；  
（4）向量组中，若一个向量可由其余向量线性表示，则该向量组一定线性相关.

（7）【答案】 (D).

【解】方法一 由 $F_{1}^{\prime}(x) = f_{1}(x)$ ， $F_{2}^{\prime}(x) = f_{2}(x)$ 得

$$
f _ {1} (x) F _ {2} (x) + f _ {2} (x) F _ {1} (x) = \left[ F _ {1} (x) F _ {2} (x) \right] ^ {\prime},
$$

再由 $F_{1}(-\infty) = F_{2}(-\infty) = 0$ ， $F_{1}(+\infty) = F_{2}(+\infty) = 1$ 得

$$
\int_ {- \infty} ^ {+ \infty} [ f _ {1} (x) F _ {2} (x) + f _ {2} (x) F _ {1} (x) ] d x = F _ {1} (x) F _ {2} (x) \Big | _ {- \infty} ^ {+ \infty} = 1,
$$

又 $f_{1}(x)F_{2}(x) + f_{2}(x)F_{1}(x)\geqslant 0$ ，故 $f_{1}(x)F_{2}(x) + f_{2}(x)F_{1}(x)$ 为某个随机变量的密度函数，应选(D).

方法二 取 $f_{1}(x) = \begin{cases} \mathrm{e}^{-x}, & x > 0, \\ 0, & x \leqslant 0, \end{cases} \quad f_{2}(x) = \begin{cases} 2\mathrm{e}^{-2x}, & x > 0, \\ 0, & x \leqslant 0, \end{cases}$ 显然 $f_{1}(x), f_{2}(x)$ 分别为参数为1和2的指数分布的密度函数， $f_{1}(x)f_{2}(x) = \begin{cases} 2\mathrm{e}^{-3x}, & x > 0, \\ 0, & x \leqslant 0. \end{cases}$

因为 $\int_{-\infty}^{+\infty}f_1(x)f_2(x)\mathrm{d}x = 2\int_0^{+\infty}\mathrm{e}^{-3x}\mathrm{d}x = \frac{2}{3}\neq 1$ ，所以 $f_{1}(x)f_{2}(x)$ 不是概率密度，（A）不对；取 $f_{1}(x) = \left\{ \begin{array}{ll}\mathrm{e}^{-x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$ $f_{2}(x) = \left\{ \begin{array}{ll}2\mathrm{e}^{-2x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$ 则 $F_{1}(x) = \left\{ \begin{array}{ll}1 - \mathrm{e}^{-x}, & x\geqslant 0,\\ 0, & x <   0, \end{array} \right.$ （20于是 $2f_{2}(x)F_{1}(x) = \left\{ \begin{array}{ll}4(\mathrm{e}^{-2x} - \mathrm{e}^{-3x}), & x > 0,\\ 0, & x <   0, \end{array} \right.$

因为 $\int_{-\infty}^{+\infty}2f_2(x)F_1(x)\mathrm{d}x = 4\int_{0}^{+\infty}(\mathrm{e}^{-2x} - \mathrm{e}^{-3x})\mathrm{d}x = \frac{2}{3}\neq 1$ ，所以 $2f_{2}(x)F_{1}(x)$ 不是概率密度，（B）不对；

取 $f_{1}(x) = \left\{ \begin{array}{ll}\mathrm{e}^{-x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$ $f_{2}(x) = \left\{ \begin{array}{ll}2\mathrm{e}^{-2x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$ $F_{2}(x) = \left\{ \begin{array}{ll}1 - \mathrm{e}^{-2x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$

$f_{1}(x)F_{2}(x) = \left\{ \begin{array}{ll}\mathrm{e}^{-x} - \mathrm{e}^{-3x}, & x > 0,\\ 0, & x\leqslant 0, \end{array} \right.$ 因为 $\int_{-\infty}^{+\infty}f_1(x)F_2(x)\mathrm{d}x = \int_0^{+\infty}(\mathrm{e}^{-x} - \mathrm{e}^{-3x})\mathrm{d}x = \frac{2}{3}\neq 1,$ 所以 $f_{1}(x)F_{2}(x)$ 不是概率密度，(C）不对，应选(D).

（8）【答案】 (B).

【解】 因为 $UV = XY$ ，所以 $E(UV) = E(XY)$

又因为 $X, Y$ 独立，所以 $E(UV) = E(XY) = E(X)E(Y)$ ，应选(B).

# 二、填空题

(9)【答案】 $\ln (1 + \sqrt{2})$

【解】由 $\mathrm{ds} = \sqrt{1 + \left(\frac{\mathrm{dy}}{\mathrm{dx}}\right)^2}\mathrm{dx} = \sqrt{1 + \tan^2x}\mathrm{dx} = \sec x\mathrm{dx},$

得 $s = \int_{0}^{\frac{\pi}{4}}\sqrt{1 + \left(\frac{\mathrm{dy}}{\mathrm{dx}}\right)^{2}}\mathrm{d}x = \int_{0}^{\frac{\pi}{4}}\sec x\mathrm{d}x = \ln (\sec x + \tan x)\Bigg{|}_{0}^{\frac{\pi}{4}} = \ln (1 + \sqrt{2}).$

方法点评：本题考查变积分限函数求导、弧微分的公式、定积分的计算.

需要熟练掌握曲线的弧长计算公式：

(1) 若 $L: y = f(x) (a \leqslant x \leqslant b)$ , 则 $\mathrm{d}s = \sqrt{1 + f'^2(x)} \, \mathrm{d}x$ , $s = \int_{a}^{b} \sqrt{1 + f'^2(x)} \, \mathrm{d}x$ ;   
(2) 若 $L: \left\{ \begin{array}{l} x = \varphi(t), \\ y = \psi(t) \end{array} \right.$ ( $\alpha \leqslant t \leqslant \beta$ ), 则 $\mathrm{ds} = \sqrt{\varphi'^2(t) + \psi'^2(t)} \, \mathrm{d}t$ , $s = \int_{\alpha}^{\beta} \sqrt{\varphi'^2(t) + \psi'^2(t)} \, \mathrm{d}t$ ;   
（3）若 $L: r = r(\theta) (\alpha \leqslant \theta \leqslant \beta)$ ，则 $\mathrm{d}s = \sqrt{r'^2(\theta) + r^2(\theta)}\mathrm{d}\theta, s = \int_{\alpha}^{\beta} \sqrt{r'^2(\theta) + r^2(\theta)}\mathrm{d}\theta.$

(10)【答案】 $\mathrm{e}^{-x}\sin x$

【解】 方法一 由 $y^\prime +y = \mathrm{e}^{-x}\cos x$ ，得

$$
y = \left(\int \mathrm {e} ^ {- x} \cos x \cdot \mathrm {e} ^ {\int \mathrm {d} x} \mathrm {d} x + C\right) \mathrm {e} ^ {- \int \mathrm {d} x} = (\sin x + C) \mathrm {e} ^ {- x} = C \mathrm {e} ^ {- x} + \mathrm {e} ^ {- x} \sin x,
$$

因为 $y(0) = 0$ ，所以 $C = 0$ ，于是 $y = \mathrm{e}^{-x}\sin x$

方法二 $y^{\prime} + y = 0$ 的通解为 $y = Ce^{-\int \mathrm{d}x} = Ce^{-x}$

令原方程的通解为 $y = C(x)\mathrm{e}^{-x}$ ，代入原方程得 $C^\prime (x)\mathrm{e}^{-x} = \mathrm{e}^{-x}\cos x$

解得 $C(x) = \sin x + C$ ，即原方程的通解为 $y = (\sin x + C)\mathrm{e}^{-x}$

由 $y(0) = 0$ 得 $C = 0$ ，故原方程满足初始条件的特解为 $y = \mathrm{e}^{-x}\sin x$

（11）【答案】4.

【解】 $\frac{\partial F}{\partial x} = \frac{y \sin xy}{1 + (xy)^2}, \quad \frac{\partial^2 F}{\partial x^2} = y \cdot \frac{y(1 + x^2y^2) \cos xy - 2xy^2 \sin xy}{(1 + x^2y^2)^2},$

则 $\frac{\partial^2F}{\partial x^2}\Big|_{\substack{x = 0\\ y = 2}} = 4.$

(12)【答案】 $\pi$

【解】方法一 设 $L$ 所在的截面为 $\Sigma$ ，按右手法则， $\Sigma$ 的法向量指向上侧，

$\Sigma$ 的法向量为 $\pmb{n} = (-1, -1, 1)$ ，方向余弦为 $\cos \alpha = -\frac{1}{\sqrt{3}}$ ， $\cos \beta = -\frac{1}{\sqrt{3}}$ ， $\cos \gamma = \frac{1}{\sqrt{3}}$

$$
\begin{array}{l} \oint_ {L} x z \mathrm {d} x + x \mathrm {d} y + \frac {y ^ {2}}{2} \mathrm {d} z = \iint_ {\Sigma} \left| \begin{array}{c c c} \cos \alpha & \cos \beta & \cos \gamma \\ \frac {\partial}{\partial x} & \frac {\partial}{\partial y} & \frac {\partial}{\partial z} \\ x z & x & \frac {y ^ {2}}{2} \end{array} \right| \mathrm {d} S = \frac {1}{\sqrt {3}} \iint_ {\Sigma} \left| \begin{array}{c c c} - 1 & - 1 & 1 \\ \frac {\partial}{\partial x} & \frac {\partial}{\partial y} & \frac {\partial}{\partial z} \\ x z & x & \frac {y ^ {2}}{2} \end{array} \right| \mathrm {d} S \\ = \frac {1}{\sqrt {3}} \iint_ {\Sigma} (- x - y + 1) d S = \frac {1}{\sqrt {3}} \iint_ {D} \sqrt {3} (- x - y + 1) d x d y \\ = \iint_ {D} (- x - y + 1) d x d y = \iint_ {D} d x d y = \pi . \\ \end{array}
$$

方法二 令 $L: \begin{cases} x = \cos t, \\ y = \sin t, \\ z = \sin t + \cos t \end{cases}$ （起点 $t = 0$ ，终点 $t = 2\pi$ ），则

$$
\begin{array}{l} \oint_ {L} x z \mathrm {d} x + x \mathrm {d} y + \frac {y ^ {2}}{2} \mathrm {d} z \\ = \int_ {0} ^ {2 \pi} \cos t (\sin t + \cos t) (- \sin t) d t + \cos^ {2} t d t + \frac {1}{2} \sin^ {2} t (\cos t - \sin t) d t \\ = \int_ {0} ^ {2 \pi} \left(- \frac {1}{2} \sin^ {2} t \cos t - \sin t \cos^ {2} t + \cos^ {2} t - \frac {1}{2} \sin^ {3} t\right) d t \\ = \int_ {- \pi} ^ {\pi} \left(- \frac {1}{2} \sin^ {2} t \cos t - \sin t \cos^ {2} t + \cos^ {2} t - \frac {1}{2} \sin^ {3} t\right) d t \\ = \int_ {- \pi} ^ {\pi} \left(- \frac {1}{2} \sin^ {2} t \cos t + \cos^ {2} t\right) d t = - \int_ {0} ^ {\pi} \sin^ {2} t \cos t d t + 2 \int_ {0} ^ {\pi} \cos^ {2} t d t \\ = 2 \int_ {0} ^ {\pi} \cos^ {2} t \mathrm {d} t = 4 I _ {2} = 4 \times \frac {1}{2} \times \frac {\pi}{2} = \pi . \\ \end{array}
$$

方法点评：本题考查三维空间对坐标的曲线积分的计算.

三维空间对坐标的曲线积分 $\int_{L} P \mathrm{d}x + Q \mathrm{d}y + R \mathrm{d}z$ 常用的计算方法有：

方法一 定积分法

设 $L:\left\{ \begin{array}{l}x = \varphi (t),\\ y = \psi (t),(\text{起点} t = \alpha ,\text{终点} t = \beta),\\ z = \omega (t) \end{array} \right.$ 则

$$
\int_ {L} P \mathrm {d} x + Q \mathrm {d} y + R \mathrm {d} z = \int_ {\alpha} ^ {\beta} \left[ P \varphi^ {\prime} (t) + Q \psi^ {\prime} (t) + R \omega^ {\prime} (t) \right] \mathrm {d} t.
$$

方法二 斯托克斯公式

$$
\oint_ {L} P \mathrm {d} x + Q \mathrm {d} y + R \mathrm {d} z = \iint_ {\Sigma} \left| \begin{array}{c c c} \cos \alpha & \cos \beta & \cos \gamma \\ \frac {\partial}{\partial x} & \frac {\partial}{\partial y} & \frac {\partial}{\partial z} \\ P & Q & R \end{array} \right| \mathrm {d} S,
$$

其中 $\cos \alpha, \cos \beta, \cos \gamma$ 为曲面 $\Sigma$ 的法向量的方向余弦.

(13)【答案】 1.

【解】 令 $\mathbf{A} = \begin{pmatrix} 1 & a & 1 \\ a & 3 & 1 \\ 1 & 1 & 1 \end{pmatrix}, \mathbf{X} = \begin{pmatrix} x \\ y \\ z \end{pmatrix}$ ，则二次曲面表示为 $\mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X} = 4$

因为 $X^T A X = 4$ 经过正交变换化为 $y_{1}^{2} + 4y_{2}^{2} = 4$ ，所以 $\mathbf{A}$ 的特征值为 $\lambda_1 = 0, \lambda_2 = 1, \lambda_3 = 4$ 于是 $r(A) = 2$

而 $\mathbf{A} = \begin{pmatrix} 1 & a & 1 \\ a & 3 & 1 \\ 1 & 1 & 1 \end{pmatrix} \rightarrow \begin{pmatrix} 1 & 1 & 1 \\ 1 & a & 1 \\ a & 3 & 1 \end{pmatrix} \rightarrow \begin{pmatrix} 1 & 1 & 1 \\ 0 & a - 1 & 0 \\ 0 & 3 - a & 1 - a \end{pmatrix}$ , 故 $a = 1$ .

（14）【答案】 $\mu \sigma^2 +\mu^3$

【解】因为 $(X,Y)\sim N(\mu ,\mu ;\sigma^2,\sigma^2;0)$ ，所以 $X\sim N(\mu ,\sigma^2),Y\sim N(\mu ,\sigma^2).$

又因为 $\rho = 0$ ，所以 $X,Y$ 相互独立，于是

$$
E \left(X Y ^ {2}\right) = E (X) \cdot E \left(Y ^ {2}\right) = \mu \left\{D (Y) + [ E (Y) ] ^ {2} \right\} = \mu \sigma^ {2} + \mu^ {3}.
$$

# 三、解答题

(15)【解】 方法一 $\lim_{x\to 0}\left[\frac{\ln(1 + x)}{x}\right]^{\frac{1}{e^x - 1}} = \lim_{x\to 0}\left\{\left[1 + \frac{\ln(1 + x) - x}{x}\right]^{\frac{x}{\ln(1 + x) - x}}\right\}^{\frac{1}{e^x - 1}}\cdot \frac{\ln(1 + x) - x}{x}$

$$
\begin{array}{l} = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {1}{\mathrm {e} ^ {x} - 1} \cdot \frac {\ln (1 + x) - x}{x}} = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {\ln (1 + x) - x}{x ^ {2}}} = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {1}{\frac {1 + x}{2 x}} - 1} \\ = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {- \frac {x}{1 + x}}{2 x}} = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {- \frac {1}{1 + x}}{2}} = \mathrm {e} ^ {- \frac {1}{2}} = \frac {1}{\sqrt {\mathrm {e}}}. \\ \end{array}
$$

方法二 由 $\ln (1 + x) = x - \frac{x^2}{2} + o(x^2)$ 得 $\frac{\ln(1 + x)}{x} = 1 - \frac{x}{2} + o(x)$ ，

于是 $\lim_{x\to 0}\left[\frac{\ln(1 + x)}{x}\right]^{\frac{1}{e^x - 1}} = \lim_{x\to 0}\left[1 - \frac{x}{2} +o(x)\right]^{\frac{1}{e^x - 1}} = \lim_{x\to 0}\left\{\left[1 - \frac{x}{2} +o(x)\right]^{\frac{1}{-\frac{x}{2} + o(x)}}\right\}^{\frac{-\frac{x}{2} + o(x)}{e^x - 1}}$

$$
= \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {- \frac {x}{2} + o (x)}{\mathrm {e} ^ {x} - 1}} = \mathrm {e} ^ {\lim  _ {x \rightarrow 0} \frac {- \frac {x}{2} + o (x)}{x}} = \mathrm {e} ^ {- \frac {1}{2}}.
$$

（16）【解】 方法一 由题意得 $g^{\prime}(1) = 0$

$$
\begin{array}{l} \frac {\partial z}{\partial x} = y f _ {1} ^ {\prime} + y f _ {2} ^ {\prime} \cdot g ^ {\prime} (x), \\ \frac {\partial^ {2} z}{\partial x \partial y} = f _ {1} ^ {\prime} + y [ x f _ {1 1} ^ {\prime \prime} + f _ {1 2} ^ {\prime \prime} \cdot g (x) ] + f _ {2} ^ {\prime} \cdot g ^ {\prime} (x) + y g ^ {\prime} (x) [ x f _ {2 1} ^ {\prime \prime} + f _ {2 2} ^ {\prime \prime} \cdot g (x) ], \\ \end{array}
$$

将 $x = 1, g(1) = 1, g'(1) = 0$ 代入，得 $\left.\frac{\partial^2 z}{\partial x \partial y}\right|_{(1,1)} = f_1'(1,1) + f_{11}''(1,1) + f_{12}''(1,1)$ .

方法二 由题意得 $g^{\prime}(1) = 0, \frac{\partial z}{\partial x} = y f_{1}^{\prime} + y f_{2}^{\prime} \cdot g^{\prime}(x)$ , 将 $x = 1$ 代入得

$$
\begin{array}{l} \left. \frac {\partial z}{\partial x} \right| _ {x = 1} = y f _ {1} ^ {\prime} (y, y), \\ \left. \frac {\partial^ {2} z}{\partial x \partial y} \right| _ {(1, 1)} = \frac {\mathrm {d}}{\mathrm {d} y} [ y f _ {1} ^ {\prime} (y, y) ] \Bigg | _ {y = 1} = f _ {1} ^ {\prime} (1, 1) + f _ {1 1} ^ {\prime \prime} (1, 1) + f _ {1 2} ^ {\prime \prime} (1, 1). \\ \end{array}
$$

(17)【解】令 $f(x) = k\arctan x - x$ ，显然 $f(x)$ 在 $(- \infty, + \infty)$ 内为奇函数，且 $f(0) = 0$ ，现研究 $f(x)$ 在 $(0, + \infty)$ 内零点个数.

$$
f ^ {\prime} (x) = \frac {k}{1 + x ^ {2}} - 1 = \frac {k - 1 - x ^ {2}}{1 + x ^ {2}},
$$

当 $k \leqslant 1$ 时，因为 $f^{\prime}(x) < 0$ ，所以 $f(x)$ 在 $(0, +\infty)$ 内单调减少，从而当 $x \in (0, +\infty)$ 时， $f(x) < f(0) = 0$ ，即 $f(x)$ 在 $(0, +\infty)$ 内无零点，

故方程 $k\arctan x - x = 0$ 在 $(-\infty, +\infty)$ 内只有唯一的实根 $x = 0$

当 $k > 1$ 时，由 $f^{\prime}(x) = 0$ 得 $x = \sqrt{k - 1}$

当 $x \in (0, \sqrt{k - 1})$ 时， $f'(x) > 0$ ；当 $x \in (\sqrt{k - 1}, +\infty)$ 时， $f'(x) < 0$ ，则 $x = \sqrt{k - 1}$ 为 $f(x)$ 在 $(0, +\infty)$ 内的最大值点，最大值 $M = f(\sqrt{k - 1}) > f(0) = 0$

因为 $\lim_{x\to +\infty}f(x) = -\infty$ ，所以 $f(x)$ 在 $(0, + \infty)$ 内有且仅有一个零点，从而当 $k > 1$ 时，方程 $k\arctan x - x = 0$ 有且仅有三个实根，其中一个根位于 $(- \infty ,0)$ 内，一个根为 $x = 0$ 一个根位于 $(0, + \infty)$ 内.

# （18）【证明】（I）方法一 单调性

令 $f(x) = \ln (1 + x) - \frac{x}{1 + x},\quad f(0) = 0,$

$$
f ^ {\prime} (x) = \frac {1}{1 + x} - \frac {1}{(1 + x) ^ {2}} > 0 (x > 0),
$$

由 $\left\{ \begin{array}{l} f(0) = 0, \\ f'(x) > 0 (x > 0), \end{array} \right.$ 得 $f(x) > 0 (x > 0)$ ，即当 $x > 0$ 时， $\frac{x}{1 + x} < \ln (1 + x)$ ；

令 $g(x) = x - \ln (1 + x)$ ， $g(0) = 0$ ， $g'(x) = 1 - \frac{1}{1 + x} > 0 (x > 0)$ ，

由 $\left\{ \begin{array}{l} g(0) = 0, \\ g'(x) > 0 (x > 0) \end{array} \right.$ 得 $g(x) > 0 (x > 0)$ ，即当 $x > 0$ 时， $\ln (1 + x) < x$

于是当 $x > 0$ 时， $\frac{x}{1 + x} < \ln (1 + x) < x$ ，取 $x = \frac{1}{n}$ ，则有 $\frac{1}{n + 1} < \ln \left(1 + \frac{1}{n}\right) < \frac{1}{n}$

# 方法二 中值定理

令 $f(t) = \ln (1 + t)(t > 0)$ ， $f(0) = 0$ ， $f'(t) = \frac{1}{1 + t}$ .

由拉格朗日中值定理，存在 $\xi \in \left(0, \frac{1}{n}\right)$ ，使得 $f\left(\frac{1}{n}\right) - f(0) = \frac{f'(\xi)}{n}$ ，即

$$
\ln \left(1 + \frac {1}{n}\right) = \frac {1}{n (1 + \xi)},
$$

因为 $\frac{1}{1 + \frac{1}{n}} < \frac{1}{1 + \xi} < \frac{1}{1 + 0}$ , 即 $\frac{n}{n + 1} < \frac{1}{1 + \xi} < 1$ , 所以 $\frac{1}{n + 1} < \ln \left(1 + \frac{1}{n}\right) < \frac{1}{n}$ .

方法三 因为当 $x \in [n, n + 1]$ 时， $\frac{1}{n + 1} \leqslant \frac{1}{x} \leqslant \frac{1}{n}$ 且不恒等，

所以 $\int_{n}^{n + 1}\frac{1}{n + 1}\mathrm{d}x <   \int_{n}^{n + 1}\frac{1}{x}\mathrm{d}x <   \int_{n}^{n + 1}\frac{1}{n}\mathrm{d}x$ ，即 $\frac{1}{n + 1} <  \ln (n + 1) - \ln n <   \frac{1}{n}$ 整理得

$$
\frac {1}{n + 1} <   \ln \left(1 + \frac {1}{n}\right) <   \frac {1}{n}.
$$

（Ⅱ）由（I）得 $a_{n + 1} - a_n = \frac{1}{n + 1} -\ln \left(1 + \frac{1}{n}\right) <   0$ ，则 $\{a_{n}\}$ 单调减少.

因为 $a_{n} = 1 + \frac{1}{2} +\dots +\frac{1}{n} -\ln n$

$$
> \ln (1 + 1) + \ln \left(1 + \frac {1}{2}\right) + \dots + \ln \left(1 + \frac {1}{n}\right) - \ln n = \ln (n + 1) - \ln n > 0,
$$

所以 $\{a_{n}\}$ 单调减少且有下界，故 $\{a_{n}\}$ 收敛

方法点评：在本题基础上需要掌握不等式证明中使用的放缩法：

【例】 证明： $\ln (1 + n)\leqslant 1 + \frac{1}{2} +\dots +\frac{1}{n}\leqslant 1 + \ln n.$

【证明】当 $x \in [1,2]$ 时，由 $\frac{1}{1} \geqslant \frac{1}{x}$ ，得 $\int_{1}^{2} \frac{1}{1} \mathrm{d}x \geqslant \int_{1}^{2} \frac{1}{x} \mathrm{d}x$ ，即 $1 \geqslant \int_{1}^{2} \frac{1}{x} \mathrm{d}x$ .

当 $x \in [2,3]$ 时，由 $\frac{1}{2} \geqslant \frac{1}{x}$ ，得 $\int_{2}^{3} \frac{1}{2} \mathrm{d}x \geqslant \int_{2}^{3} \frac{1}{x} \mathrm{d}x$ ，即 $\frac{1}{2} \geqslant \int_{2}^{3} \frac{1}{x} \mathrm{d}x$ .

同理 $\frac{1}{3} \geqslant \int_{3}^{4} \frac{1}{x} \mathrm{d}x, \dots, \frac{1}{n} \geqslant \int_{n}^{n+1} \frac{1}{x} \mathrm{d}x$ ，相加得 $1 + \frac{1}{2} + \dots + \frac{1}{n} \geqslant \int_{1}^{n+1} \frac{1}{x} \mathrm{d}x = \ln(1 + n)$ ；

又当 $x \in [1,2]$ 时，由 $\frac{1}{2} \leqslant \frac{1}{x}$ ，得 $\int_{1}^{2} \frac{1}{2} \mathrm{d}x \leqslant \int_{1}^{2} \frac{1}{x} \mathrm{d}x$ ，即 $\frac{1}{2} \leqslant \int_{1}^{2} \frac{1}{x} \mathrm{d}x$ ；

当 $x \in [2,3]$ 时，由 $\frac{1}{3} \leqslant \frac{1}{x}$ ，得 $\int_{2}^{3} \frac{1}{3} \mathrm{d}x \leqslant \int_{2}^{3} \frac{1}{x} \mathrm{d}x$ ，即 $\frac{1}{3} \leqslant \int_{2}^{3} \frac{1}{x} \mathrm{d}x$ ；

同理 $\frac{1}{4} \leqslant \int_{3}^{4} \frac{1}{x} \mathrm{d}x, \dots, \frac{1}{n} \leqslant \int_{n-1}^{n} \frac{1}{x} \mathrm{d}x$ ，相加得 $\frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n} \leqslant \int_{1}^{n} \frac{1}{x} \mathrm{d}x = \ln n$ ，于是

$$
1 + \frac {1}{2} + \frac {1}{3} + \dots + \frac {1}{n} \leqslant 1 + \ln n, \text {故} \ln (1 + n) \leqslant 1 + \frac {1}{2} + \dots + \frac {1}{n} \leqslant 1 + \ln n.
$$

(19)【解】 $I = \int_{0}^{1}x\mathrm{d}x\int_{0}^{1}yf_{xy}^{\prime \prime}(x,y)\mathrm{d}y = \int_{0}^{1}x\mathrm{d}x\int_{0}^{1}y\mathrm{d}f_{x}^{\prime}(x,y),$

由 $\int_0^1 y\mathrm{d}f_x'(x,y) = yf_x'(x,y)\Big|_0^1 -\int_0^1 f_x'(x,y)\mathrm{d}y = f_x'(x,1) - \int_0^1 f_x'(x,y)\mathrm{d}y,$

得 $I = \int_{0}^{1}x f^{\prime}_{x}(x,1)\mathrm{d}x - \int_{0}^{1}x\mathrm{d}x\int_{0}^{1}f^{\prime}_{x}(x,y)\mathrm{d}y = \int_{0}^{1}x\mathrm{d}f(x,1) - \int_{0}^{1}x\mathrm{d}x\int_{0}^{1}f^{\prime}_{x}(x,y)\mathrm{d}y,$

由 $f(x,1) = 0$ 得

$$
I = - \int_ {0} ^ {1} x \mathrm {d} x \int_ {0} ^ {1} f _ {x} ^ {\prime} (x, y) \mathrm {d} y = - \int_ {0} ^ {1} \mathrm {d} y \int_ {0} ^ {1} x f _ {x} ^ {\prime} (x, y) \mathrm {d} x,
$$

$$
\int_ {0} ^ {1} x f _ {x} ^ {\prime} (x, y) \mathrm {d} x = \int_ {0} ^ {1} x \mathrm {d} f (x, y) = x f (x, y) | _ {0} ^ {1} - \int_ {0} ^ {1} f (x, y) \mathrm {d} x = f (1, y) - \int_ {0} ^ {1} f (x, y) \mathrm {d} x,
$$

由 $f(1,y) = 0$ 得 $\int_0^1 xf'_x(x,y)\mathrm{d}x = -\int_0^1 f(x,y)\mathrm{d}x,$

故 $I = \int_{0}^{1}\mathrm{d}y\int_{0}^{1}f(x,y)\mathrm{d}x = \iint_{D}f(x,y)\mathrm{d}x\mathrm{d}y = a.$

方法点评：本题主要考查二重积分转化为累次积分及改变累次积分的积分次序，抽象函数的定积分的分部积分法.

(20)【解】（I）方法一 $\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}$ 为3个3维向量，因为 $|\pmb{\alpha}_1,\pmb{\alpha}_2,\pmb{\alpha}_3| = \begin{vmatrix} 1 & 0 & 1\\ 0 & 1 & 3\\ 1 & 1 & 5 \end{vmatrix} = 1\neq 0,$

所以 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性无关.因为 $\beta_{1},\beta_{2},\beta_{3}$ 一定可由 $\alpha_{1},\alpha_{2},\alpha_{3}$ 线性表示，而 $\alpha_{1},\alpha_{2},\alpha_{3}$ 不能由 $\beta_{1},\beta_{2},\beta_{3}$ 线性表示，所以 $\beta_{1},\beta_{2},\beta_{3}$ 的秩小于 $\alpha_{1},\alpha_{2},\alpha_{3}$ 的秩，

从而 $|\pmb{\beta}_1, \pmb{\beta}_2, \pmb{\beta}_3| = \left| \begin{array}{ccc} 1 & 1 & 3 \\ 1 & 2 & 4 \\ 1 & 3 & a \end{array} \right| = \left| \begin{array}{ccc} 1 & 1 & 3 \\ 0 & 1 & 1 \\ 0 & 2 & a - 3 \end{array} \right| = a - 5 = 0$ ，故 $a = 5$ .

方法二 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3},\pmb{\alpha}_{i}(i = 1,2,3)$ 为4个3维向量，则 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3},\pmb{\alpha}_{i}(i = 1,2,3)$ 一定线性相关.

若 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}$ 线性无关，而 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3},\pmb{\alpha}_{i}(i = 1,2,3)$ 线性相关，则 $\pmb{\alpha}_{i}(i = 1,2,3)$ 可由向量组 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}$ 线性表示，矛盾，于是 $|\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}| = 0$

由 $|\pmb{\beta}_1, \pmb{\beta}_2, \pmb{\beta}_3| = \left| \begin{array}{lll} 1 & 1 & 3 \\ 1 & 2 & 4 \\ 1 & 3 & a \end{array} \right| = a - 5 = 0$ ，得 $a = 5$ .

（Ⅱ）将矩阵 $(\alpha_{1},\alpha_{2},\alpha_{3},\beta_{1},\beta_{2},\beta_{3})$ 进行初等行变换得

$$
\left(\boldsymbol {\alpha} _ {1}, \boldsymbol {\alpha} _ {2}, \boldsymbol {\alpha} _ {3}, \boldsymbol {\beta} _ {1}, \boldsymbol {\beta} _ {2}, \boldsymbol {\beta} _ {3}\right) = \left(\begin{array}{c c c c c c}1&0&1&1&1&3\\0&1&3&1&2&4\\1&1&5&1&3&5\end{array}\right)\rightarrow \left(\begin{array}{c c c c c c}1&0&0&2&1&5\\0&1&0&4&2&1 0\\0&0&1&- 1&0&- 2\end{array}\right),
$$

于是 $\begin{cases} \pmb{\beta}_{1} = 2\pmb{\alpha}_{1} + 4\pmb{\alpha}_{2} - \pmb{\alpha}_{3}, \\ \pmb{\beta}_{2} = \pmb{\alpha}_{1} + 2\pmb{\alpha}_{2} + 0\pmb{\alpha}_{3}, \\ \pmb{\beta}_{3} = 5\pmb{\alpha}_{1} + 10\pmb{\alpha}_{2} - 2\pmb{\alpha}_{3}. \end{cases}$

方法点评：本题使用向量组的如下性质：

（1）若一个向量组的向量个数大于向量的维数，则该向量组一定线性相关；  
（2）若一个向量组的个数与维数相等，则该向量组线性相关的充分必要条件是该向量组构成的行列式为零；  
（3）若向量组 $\mathbf{A}$ 可由向量组 $\pmb{B}$ 线性表示，但向量组 $\pmb{B}$ 不可由向量组 $\mathbf{A}$ 线性表示，则向量组 $\mathbf{A}$ 的秩小于向量组 $\pmb{B}$ 的秩.

(21)【解】（I）由 $r(\mathbf{A}) = 2 < 3$ ，得 $\left|\mathbf{A}\right| = 0$ ，于是 $\lambda_{1} = 0$ 为 $\mathbf{A}$ 的一个特征值.

又由已知条件，得 $A\left( \begin{array}{l}1\\ 0\\ -1 \end{array} \right) = -\left( \begin{array}{l}1\\ 0\\ -1 \end{array} \right),A\left( \begin{array}{l}1\\ 0\\ 1 \end{array} \right) = \left( \begin{array}{l}1\\ 0\\ 1 \end{array} \right)$ 根据特征值与特征向量的定义得 $\lambda_{2} = -1$ 为 $\mathbf{A}$ 的特征值，其对应的特征向量为 $\xi_{2} = \left( \begin{array}{l}1\\ 0\\ -1 \end{array} \right)$

$\lambda_{3} = 1$ 为 $\mathbf{A}$ 的特征值，其对应的特征向量为 $\xi_{3} = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix}$ .

令 $\xi_{1} = \begin{pmatrix} x_{1}\\ x_{2}\\ x_{3} \end{pmatrix}$ 为 $\lambda_1 = 0$ 对应的一个特征向量，由实对称矩阵不同特征值对应的特征向量正

交得 $\left\{ \begin{array}{l} \xi_1^{\mathrm{T}} \xi_2 = 0, \\ \xi_1^{\mathrm{T}} \xi_3 = 0, \end{array} \right.$ 即 $\left\{ \begin{array}{l} x_1 - x_3 = 0, \\ x_1 + x_3 = 0, \end{array} \right.$ 基础解系为 $\xi_1 = \binom{0}{1}$ , 即 $\xi_1 = \binom{0}{1}$ 为 $\lambda_1 = 0$ 对应的一个特征向量. 故 $A$ 的特征值为 $\lambda_1 = 0, \lambda_2 = -1, \lambda_3 = 1$ , 其对应的所有特征向量为 $C_1 \xi_1, C_2 \xi_2, C_3 \xi_3 (C_1, C_2, C_3$ 为不为零的任意常数).

（Ⅱ）方法一 令 $P = (\xi_{1},\xi_{2},\xi_{3}) = \begin{pmatrix} 0 & 1 & 1\\ 1 & 0 & 0\\ 0 & -1 & 1 \end{pmatrix}$ ，由 $P^{-1}AP = \begin{pmatrix} 0 & 0 & 0\\ 0 & -1 & 0\\ 0 & 0 & 1 \end{pmatrix}$ ，得

$$
\mathbf {A} = \mathbf {P} \left( \begin{array}{c c c} 0 & 0 & 0 \\ 0 & - 1 & 0 \\ 0 & 0 & 1 \end{array} \right) \mathbf {P} ^ {- 1} = \left( \begin{array}{c c c} 0 & 0 & 1 \\ 0 & 0 & 0 \\ 1 & 0 & 0 \end{array} \right).
$$

方法二 由 $A(\xi_1, \xi_2, \xi_3) = (A\xi_1, A\xi_2, A\xi_3) = (0, -\xi_2, \xi_3)$ ，得

$$
\mathbf {A} = (\mathbf {0}, - \xi_ {2}, \xi_ {3}) (\xi_ {1}, \xi_ {2}, \xi_ {3}) ^ {- 1} = \left( \begin{array}{c c c} 0 & - 1 & 1 \\ 0 & 0 & 0 \\ 0 & 1 & 1 \end{array} \right) \left( \begin{array}{c c c} 0 & 1 & 1 \\ 1 & 0 & 0 \\ 0 & - 1 & 1 \end{array} \right) ^ {- 1} = \left( \begin{array}{c c c} 0 & 0 & 1 \\ 0 & 0 & 0 \\ 1 & 0 & 0 \end{array} \right).
$$

方法点评：本题注重考查特征值与特征向量的定义，很多考生忽视了定义而不知道本题所给已知条件如何解读。事实上求特征值常用方法有：

（1）公式法，即由 $|\lambda E - A| = 0$ 求出特征值；

（2）定义法，即令 $AX = \lambda X$ ，根据矩阵的关系式，求出矩阵 $\mathbf{A}$ 的特征值；

（3）关联矩阵法，即找矩阵 $\pmb{B}$ ，使得 $P^{-1}AP = B$ ，即 $\mathbf{A}\sim \mathbf{B}$ ，从而 $|\lambda E - A| = |\lambda E - B|$ ，于是求出 $\mathbf{A}$ 的特征值.

求特征向量常用方法有：

（1）设 $\lambda_0$ 为 $\mathbf{A}$ 的特征值，则属于 $\lambda_0$ 的特征向量为 $(\lambda_0 E - A) X = 0$ 的非零解；

（2）定义法，满足 $AX = \lambda_0X$ 的非零 $X$ 即为 $\lambda_0$ 对应的特征向量；

（3）利用矩阵关系求特征向量，如 $A^{-1}\pmb {\alpha} = \lambda_0\pmb{\alpha}$ ，则 $\pmb{\alpha}$ 为 $\mathbf{A}$ 的属于特征值 $\frac{1}{\lambda_0}$ 的特征向量.

（22）【解】（I）由 $P\{X^2 = Y^2\} = 1$ ，得 $P\{X^2 \neq Y^2\} = 0$

于是 $P\{X = 0,Y = -1\} = P\{X = 0,Y = 1\} = P\{X = 1,Y = 0\} = 0$

故 $(X,Y)$ 的联合分布律为

<table><tr><td rowspan="2">X</td><td colspan="3">Y</td></tr><tr><td>-1</td><td>0</td><td>1</td></tr><tr><td>0</td><td>0</td><td>1/3</td><td>0</td></tr><tr><td>1</td><td>1/3</td><td>0</td><td>1/3</td></tr></table>

（Ⅱ） $Z = XY$ 的可能取值为 $-1,0,1$ ，且

$$
P \{Z = - 1 \} = P \{X = 1, Y = - 1 \} = \frac {1}{3},
$$

$$
\begin{array}{l} P \{Z = 0 \} = P \{X = 0, Y = - 1 \} + P \{X = 0, Y = 0 \} + \\ P \{X = 0, Y = 1 \} + P \{X = 1, Y = 0 \} \\ = \frac {1}{3}, \\ \end{array}
$$

$P\{Z = 1\} = 1 - P\{Z = -1\} - P\{Z = 0\} = \frac{1}{3}$ , 则 $Z$ 的分布律为 $Z \sim \left( \begin{array}{ccc} -1 & 0 & 1 \\ \frac{1}{3} & \frac{1}{3} & \frac{1}{3} \end{array} \right)$ .

（Ⅲ）由 $E(X) = \frac{2}{3}, E(Y) = 0, E(XY) = E(Z) = 0,$

得 $\operatorname{Cov}(X, Y) = E(XY) - E(X)E(Y) = 0$ ，于是 $\rho_{XY} = 0$

(23)【解】（I）似然函数为 $L(\sigma^2) = f(x_1)f(x_2)\dots f(x_n) = (2\pi \sigma^2)^{-\frac{n}{2}}\mathrm{e}^{-\frac{1}{2\sigma^2}\sum_{i = 1}^{n}(x_i - \mu_0)^2},$

取对数得 $\ln L(\sigma^2) = -\frac{n}{2}\ln 2\pi -\frac{n}{2}\ln \sigma^2 -\frac{1}{2\sigma^2}\sum_{i = 1}^{n}(x_i - \mu_0)^2,$

由 $\frac{\mathrm{d}}{\mathrm{d}(\sigma^2)}\ln L(\sigma^2) = -\frac{n}{2\sigma^2} +\frac{1}{2\sigma^4}\sum_{i = 1}^{n}(x_i - \mu_0)^2 = 0$ ，得 $\sigma^2 = \frac{1}{n}\sum_{i = 1}^{n}(x_i - \mu_0)^2$ 故 $\sigma^2$ 的最大似然估计量为 $\hat{\sigma}^2 = \frac{1}{n}\sum_{i = 1}^{n}(X_i - \mu_0)^2.$

（Ⅱ）方法一 $E(\hat{\sigma}^2) = \frac{1}{n}\sum_{i = 1}^{n}E(X_i - \mu_0)^2 = E(X - \mu_0)^2$

$$
\begin{array}{l} = D \left(X - \mu_ {0}\right) + \left[ E \left(X - \mu_ {0}\right) \right] ^ {2} = D (X) = \sigma^ {2}, \\ D \left(\hat {\sigma} ^ {2}\right) = \frac {1}{n ^ {2}} \sum_ {i = 1} ^ {n} D \left(X _ {i} - \mu_ {0}\right) ^ {2} = \frac {1}{n} D \left(X - \mu_ {0}\right) ^ {2} = \frac {\sigma^ {4}}{n} D \left(\frac {X - \mu_ {0}}{\sigma}\right) ^ {2}, \\ \end{array}
$$

因为 $\frac{X - \mu_0}{\sigma} \sim N(0,1)$ ，所以 $\left(\frac{X - \mu_0}{\sigma}\right)^2 \sim \chi^2(1)$ ，于是 $D\left(\frac{X - \mu_0}{\sigma}\right)^2 = 2$ 故 $D(\hat{\sigma}^2) = \frac{2\sigma^4}{n}$ .

方法二 因为 $\sum_{i=1}^{n}\left(\frac{X_i - \mu_0}{\sigma}\right)^2 \sim \chi^2(n)$ ，所以 $\sum_{i=1}^{n}D\left(\frac{X_i - \mu_0}{\sigma}\right)^2 = 2n$

$$
D \left(\hat {\sigma} ^ {2}\right) = D \left[ \frac {\sigma^ {2}}{n} \sum_ {i = 1} ^ {n} \left(\frac {X _ {i} - \mu_ {0}}{\sigma}\right) ^ {2} \right] = \frac {\sigma^ {4}}{n ^ {2}} \sum_ {i = 1} ^ {n} D \left(\frac {X _ {i} - \mu_ {0}}{\sigma}\right) ^ {2} = \frac {2 \sigma^ {4}}{n}.
$$