# 2008年数学(一）真题解析

# 一、选择题

（1）【答案】 （B）.

【解】由 $f^{\prime}(x) = 2x\ln (2 + x^{2}) = 0$ ，得 $x = 0$ ，即 $f^{\prime}(x)$ 只有一个零点，应选(B).

（2）【答案】 （A）.

【解】 $\frac{\partial f}{\partial x} = \frac{1}{1 + \frac{x^2}{y^2}}\cdot \frac{1}{y} = \frac{y}{x^2 + y^2},\quad \frac{\partial f}{\partial y} = \frac{1}{1 + \frac{x^2}{y^2}}\cdot \left(-\frac{x}{y^2}\right) = -\frac{x}{x^2 + y^2},$

由 $\frac{\partial f}{\partial x}\bigg|_{(0,1)} = 1,\frac{\partial f}{\partial y}\bigg|_{(0,1)} = 0$ ，则 $f(x,y)$ 在(0，1）处的梯度为 $\pmb{i}$ ，应选（A).

(3)【答案】 (D).

【解】由微分方程的通解为 $y = C_{1}\mathrm{e}^{x} + C_{2}\cos 2x + C_{3}\sin 2x$ ，得三阶常系数齐次线性微分方程的特征根为 $\lambda_1 = 1, \lambda_{2,3} = \pm 2\mathrm{i}$

特征方程为 $(\lambda - 1)(\lambda^2 + 4) = 0$ ，即 $\lambda^3 - \lambda^2 + 4\lambda - 4 = 0$

故所求微分方程为 $y^{\prime \prime} - y^{\prime \prime} + 4y^{\prime} - 4y = 0$ ，应选(D).

（4）【答案】 （B）.

# 【解】 方法一 极限存在定理

因为 $f(x)$ 单调，所以当 $\{x_{n}\}$ 单调时， $\{f(x_{n})\}$ 单调；

又因为 $f(x)$ 有界，所以 $\{f(x_{n})\}$ 单调有界，由极限存在定理得 $\{f(x_{n})\}$ 收敛，应选(B).

# 方法二 反例法

取 $f(x) = \left\{ \begin{array}{ll} - 1, & x <   0,\\ 0, & x = 0,\\ 1, & x > 0, \end{array} \right.$ $x_{n} = \frac{(-1)^{n}}{n^{2}}$ ，显然 $f(x)$ 单调增加， $\{x_{n}\}$ 收敛，

$f(x_{n}) = \left\{ \begin{array}{ll} - 1, & n = 1,3,5,\dots ,\\ 1, & n = 2,4,6,\dots , \end{array} \right.$ 显然 $\{f(x_n)\}$ 发散，（A）不对；

取 $f(x) = \frac{x^2}{1 + x^2},x_n = n,f(x_n) = \frac{n^2}{1 + n^2}$ ，显然 $\{f(x_{n})\}$ 收敛，但 $\{x_{n}\}$ 发散，（C）不对；

取 $f(x) = \arctan x, x_{n} = n$ ，显然 $\{f(x_{n})\}$ 单调增加，但 $\{x_{n}\}$ 发散，(D) 不对，应选(B).

(5)【答案】 (C).

# 【解】 方法一 逆矩阵的定义

由 $A^3 = 0$ ，得 $\pmb {E} = \pmb {E} - \pmb{A}^{3} = (\pmb {E} - \pmb {A})(\pmb {E} + \pmb {A} + \pmb{A}^2)$

由可逆矩阵的定义得 $\pmb{E} - \pmb{A}$ 可逆且 $(\pmb{E} - \pmb{A})^{-1} = \pmb{E} + \pmb{A} + \pmb{A}^2$

再由 $E = E + A^3 = (E + A)(E - A + A^2)$ 得 $E + A$ 可逆且 $(E + A)^{-1} = E - A + A^2$ 应选(C).

# 方法二 定义法求特征值

令 $AX = \lambda X(X\neq 0)$ ，则 $A^3 X = \lambda^3 X$ ，由 $A^3 = O$ 得 $\lambda^3 X = 0$ ，从而 $\mathbf{A}$ 的特征值为 $\lambda_1 = \lambda_2 = \lambda_3 = 0$ ，于是 $E - A$ 与 $E + A$ 的特征值为1，1，1，由 $|E - A| = |E + A| = 1\neq 0$ 得 $E - A$

与 $E + A$ 都可逆，应选（C）.

（6）【答案】 （B）.

【解】 题目图中的曲面是由 $L:\left\{ \begin{array}{l}\frac{x^2}{a^2} -\frac{y^2}{b^2} = 1,\\ z = 0 \end{array} \right.$ 绕 $x$ 轴旋转一周而成的曲面，

曲面方程为 $\Sigma: \frac{x^2}{a^2} - \frac{y^2}{b^2} - \frac{z^2}{b^2} = 1$ ，则 $\mathbf{A}$ 的正特征值个数为1个，应选(B).

方法点评：（1）平面曲线 $L$ $\left\{ \begin{array}{l}f(x,y) = 0,\\ z = 0 \end{array} \right.$ 绕 $x$ 轴旋转所得的旋转曲面为

$$
\Sigma_ {x}: f (x, \pm \sqrt {y ^ {2} + z ^ {2}}) = 0;
$$

平面曲线 $L$ 绕 $y$ 轴旋转所得的旋转曲面为

$$
\Sigma_ {y}: f (\pm \sqrt {x ^ {2} + z ^ {2}}, y) = 0.
$$

（2）二次型的标准形不唯一，但二次型的正、负惯性指数是唯一的，即二次型标准化后正、负惯性指数不变.

（7）【答案】 （A）.

【解】由分布函数的定义得 $F_{Z}(x) = P\{Z \leqslant x\} = P\{\max(X, Y) \leqslant x\}$ ，

由 $X,Y$ 独立同分布，得 $F_{Z}(x) = P\{X\leqslant x,Y\leqslant x\} = P\{X\leqslant x\} P\{Y\leqslant x\} = F^{2}(x)$ ，应选(A).

方法点评：设 $(X,Y)$ 为二维随机变量， $Z = \varphi (X,Y)$ 为 $(X,Y)$ 的函数.求 $Z$ 的分布时，一般采用定义法，即

$$
F _ {Z} (z) = P \{Z \leqslant z \} = P \{\varphi (X, Y) \leqslant z \}.
$$

如下两种常见的随机变量的函数的分布需要熟练掌握：

(1) $Z = \max \{X,Y\}$

$$
F _ {Z} (z) = P \{Z \leqslant z \} = P \{\max  \{X, Y \} \leqslant z \} = P \{X \leqslant z, Y \leqslant z \},
$$

若 $X,Y$ 相互独立，则 $F_{Z}(z) = P\{X\leqslant z,Y\leqslant z\} = P\{X\leqslant z\} P\{Y\leqslant z\} = F_{X}(z)F_{Y}(z).$

(2) $Z = \min \{X, Y\}$

$$
\begin{array}{l} F _ {Z} (z) = P \{Z \leqslant z \} = P \{\min  \{X, Y \} \leqslant z \} \\ = 1 - P \left\{\min  \{X, Y \} > z \right\} = 1 - P \left\{X > z, Y > z \right\}, \\ \end{array}
$$

若 $X, Y$ 相互独立，则

$$
\begin{array}{l} F _ {Z} (z) = 1 - P \{X > z \} P \{Y > z \} = 1 - [ 1 - P \{X \leqslant z \} ] \cdot [ 1 - P \{Y \leqslant z \} ] \\ = 1 - \left[ 1 - F _ {X} (z) \right] \cdot \left[ 1 - F _ {Y} (z) \right]. \\ \end{array}
$$

（8）【答案】 (D).

【解】因为 $\rho_{XY} = 1$ 的充分必要条件是 $P\{Y = aX + b\} = 1$ （其中 $a > 0$ ），排除(A)，(C)；由 $E(X) = 0, E(Y) = 1$ ，得 $E(2X + 1) = 1 = E(Y)$ ，应选(D).

方法点评：(1) $\rho_{XY} = 1$ 的充分必要条件是 $P\{Y = aX + b\} = 1 (a > 0)$

(2) $\rho_{XY} = -1$ 的充分必要条件是 $P\{Y = aX + b\} = 1 (a < 0)$ .

# 二、填空题

(9)【答案】 $\frac{1}{x}$ .

【解】方法一 由 $xy' + y = 0$ ，得 $\frac{\mathrm{dy}}{\mathrm{dx}} +\frac{1}{x} y = 0$ ，解得 $y = C\mathrm{e}^{-\int \frac{1}{x}\mathrm{d}x} = \frac{C}{x}$

由 $y(1) = 1$ ，得 $C = 1$ ，于是 $y = \frac{1}{x}$

方法二 由 $xy' + y = 0$ ，得 $(xy)' = 0$ ，即 $xy = C$

再由 $y(1) = 1$ ，得 $C = 1$ ，故所求的特解为 $y = \frac{1}{x}$

(10)【答案】 $y = x + 1$ .

【解】方法一 $\sin (xy) + \ln (y - x) = x$ 两边对 $x$ 求导数，得

$$
\cos (x y) \cdot \left(y + x \frac {\mathrm {d} y}{\mathrm {d} x}\right) + \frac {\frac {\mathrm {d} y}{\mathrm {d} x} - 1}{y - x} = 1,
$$

将 $x = 0, y = 1$ 代入得 $\left.\frac{\mathrm{dy}}{\mathrm{dx}}\right|_{x = 0} = 1.$

故曲线 $\sin (xy) + \ln (y - x) = x$ 在点(0,1)处的切线方程为 $y - 1 = x - 0$ ，即 $y = x + 1$

方法二 令 $F(x,y) = \sin (xy) + \ln (y - x) - x$

$$
\frac {\mathrm {d} y}{\mathrm {d} x} = - \frac {F _ {x} ^ {\prime}}{F _ {y} ^ {\prime}} = - \frac {y \cos x y - \frac {1}{y - x} - 1}{x \cos x y + \frac {1}{y - x}},
$$

切线的斜率为 $k = \frac{\mathrm{dy}}{\mathrm{dx}}\bigg|_{(0,1)} = 1$

故切线方程为 $y - 1 = x$ ，即 $y = x + 1$

(11)【答案】 (1,5].

【解】由 $\sum_{n=0}^{\infty} a_n (x + 2)^n$ 在 $x = 0$ 处收敛得 $\sum_{n=0}^{\infty} a_n x^n$ 的收敛半径 $R \geqslant |0 + 2| = 2$ 且 $\sum_{n=0}^{\infty} a_n 2^n$ 收敛；

由 $\sum_{n=0}^{\infty} a_n (x + 2)^n$ 在 $x = -4$ 处发散得 $\sum_{n=0}^{\infty} a_n x^n$ 的收敛半径 $R \leqslant |-4 + 2| = 2$ 且 $\sum_{n=0}^{\infty} a_n (-2)^n$ 发散，

即幂级数 $\sum_{n=0}^{\infty} a_n x^n$ 的收敛半径为 $R = 2$ , 收敛域为 $(-2, 2]$ ,

故 $\sum_{n=0}^{\infty} a_n (x - 3)^n$ 的收敛域为 $-2 < x - 3 \leqslant 2$ ，即(1,5].

(12)【答案】 $4\pi$

【解】 方法一 高斯公式法

补充 $\Sigma_0: z = 0 (x^2 + y^2 \leqslant 4)$ , $\Sigma_0$ 取下侧,

则 $\iint_{\Sigma} xy \, \mathrm{d}y \, \mathrm{d}z + x \, \mathrm{d}z \, \mathrm{d}x + x^2 \, \mathrm{d}x \, \mathrm{d}y$

$$
= \iint_ {\Sigma + \Sigma_ {0}} x y \mathrm {d} y \mathrm {d} z + x \mathrm {d} z \mathrm {d} x + x ^ {2} \mathrm {d} x \mathrm {d} y - \iint_ {\Sigma_ {0}} x y \mathrm {d} y \mathrm {d} z + x \mathrm {d} z \mathrm {d} x + x ^ {2} \mathrm {d} x \mathrm {d} y,
$$

而 $\iint_{\Sigma + \Sigma_0} xy \, \mathrm{d}y \, \mathrm{d}z + x \, \mathrm{d}z \, \mathrm{d}x + x^2 \, \mathrm{d}x \, \mathrm{d}y = \iiint_{\Omega} y \, \mathrm{d}v = 0,$

$$
\begin{array}{l} \iint_ {\Sigma_ {0}} x y \mathrm {d} y \mathrm {d} z + x \mathrm {d} z \mathrm {d} x + x ^ {2} \mathrm {d} x \mathrm {d} y = \iint_ {\Sigma_ {0}} x ^ {2} \mathrm {d} x \mathrm {d} y = - \iint_ {D} x ^ {2} \mathrm {d} x \mathrm {d} y \\ = - \frac {1}{2} \iint_ {D} \left(x ^ {2} + y ^ {2}\right) d x d y = - \frac {1}{2} \int_ {0} ^ {2 \pi} d \theta \int_ {0} ^ {2} r ^ {3} d r = - 4 \pi , \\ \end{array}
$$

故原式 $= 4\pi$

# 方法二 二重积分法

令 $\Sigma_{1}:x = \sqrt{4 - y^{2} - z^{2}} (y^{2} + z^{2}\leqslant 4(z\geqslant 0))$ ，取前侧，由对坐标的曲面积分及二重积分的奇偶性质得

$$
\begin{array}{l} \iint_ {\Sigma} x y \mathrm {d} y \mathrm {d} z = 2 \iint_ {\Sigma_ {1}} x y \mathrm {d} y \mathrm {d} z = 2 \iint_ {y ^ {2} + z ^ {2} \leqslant 4} y \sqrt {4 - y ^ {2} - z ^ {2}} \mathrm {d} y \mathrm {d} z = 0, \\ \iint_ {\Sigma} x \mathrm {d} z \mathrm {d} x = 0, \\ \iint_ {\Sigma} x ^ {2} \mathrm {d} x \mathrm {d} y = \iint_ {x ^ {2} + y ^ {2} \leqslant 4} x ^ {2} \mathrm {d} x \mathrm {d} y = \frac {1}{2} \iint_ {x ^ {2} + y ^ {2} \leqslant 4} (x ^ {2} + y ^ {2}) \mathrm {d} x \mathrm {d} y = \frac {1}{2} \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {2} r ^ {3} \mathrm {d} r = 4 \pi , \\ \end{array}
$$

故 $\iint_{\Sigma} xy \, \mathrm{d}y \, \mathrm{d}z + x \, \mathrm{d}z \, \mathrm{d}x + x^2 \, \mathrm{d}x \, \mathrm{d}y = 4\pi.$

(13)【答案】 1.

【解】方法一 令 $P = (\pmb{\alpha}_1, \pmb{\alpha}_2)$ ，因为 $\pmb{\alpha}_1, \pmb{\alpha}_2$ 线性无关，所以 $P$ 可逆.

由 $\mathbf{A}\mathbf{P} = (\mathbf{A}\pmb{\alpha}_{1},\mathbf{A}\pmb{\alpha}_{2}) = (\mathbf{0},2\pmb{\alpha}_{1} + \pmb{\alpha}_{2}) = \mathbf{P}\left( \begin{array}{cc}0 & 2\\ 0 & 1 \end{array} \right)$ 得 $\pmb{P}^{-1}\pmb {A}\pmb {P} = \left( \begin{array}{ll}0 & 2\\ 0 & 1 \end{array} \right)$ 即 $\mathbf{A}\sim \left( \begin{array}{ll}0 & 2\\ 0 & 1 \end{array} \right)$ 于是 $|\lambda E - A| = \left| \begin{array}{ll}\lambda & \lambda -2\\ 0 & \lambda -1 \end{array} \right| = \lambda (\lambda -1) = 0$ ，得 $\mathbf{A}$ 的非零特征值为 $\lambda = 1$

方法二 由 $A\pmb{\alpha}_{1} = \mathbf{0} = 0\pmb{\alpha}_{1}$ ，得 $\lambda_1 = 0$ 为 $\mathbf{A}$ 的一个特征值.

又由 $A\alpha_{1} = 0$ ， $A\alpha_{2} = 2\alpha_{1} + \alpha_{2}$ ，得 $A(2\alpha_{1} + \alpha_{2}) = 1(2\alpha_{1} + \alpha_{2})$ ，注意到 $2\alpha_{1} + \alpha_{2}$ 为非零向量，从而 $\lambda_{2} = 1$ 为 $A$ 的另一个特征值，故 $A$ 的非零特征值为1.

方法点评：求矩阵 $\mathbf{A}$ 的特征值通常有三种方法：

（1）公式法，即通过 $|\lambda E - A| = 0$ 求特征值，但前提是矩阵已知；  
(2) 定义法, 即令 $AX = \lambda X$ , 利用所给矩阵关系等式求特征值;  
（3）关联矩阵法，即通过 $P^{-1}AP = B$ 得 $\mathbf{A}\sim \mathbf{B}$ ，从而得 $\mathbf{A},\mathbf{B}$ 的特征值相同，求 $\pmb{B}$ 的特征值即可得 $\mathbf{A}$ 的特征值.

(14)【答案】 $\frac{1}{2\mathrm{e}}$

【解】由 $X\sim P(1)$ 得 $E(X) = D(X) = 1$ ，从而 $E(X^{2}) = D(X) + (EX)^{2} = 2$

于是 $P\{X = E(X^2)\} = P\{X = 2\} = \frac{1^2}{2!}\cdot \mathrm{e}^{-1} = \frac{1}{2\mathrm{e}}.$

# 三、解答题

（15）【解】 方法一

$$
\begin{array}{l} \lim  _ {x \rightarrow 0} \frac {\left[ \sin x - \sin (\sin x) \right] \sin x}{x ^ {4}} = \lim  _ {x \rightarrow 0} \frac {\sin x - \sin (\sin x)}{x ^ {3}} \cdot \frac {\sin x}{x} = \lim  _ {x \rightarrow 0} \frac {\sin x - \sin (\sin x)}{x ^ {3}} \\ = \lim  _ {x \rightarrow 0} \frac {\sin x - \sin (\sin x)}{\sin^ {3} x} \cdot \frac {\sin^ {3} x}{x ^ {3}} = \lim  _ {x \rightarrow 0} \frac {\sin x - \sin (\sin x)}{\sin^ {3} x} \\ \xlongequal {\sin x = t} \lim  _ {t \rightarrow 0} \frac {t - \sin t}{t ^ {3}} = \lim  _ {t \rightarrow 0} \frac {1 - \cos t}{3 t ^ {2}} = \frac {1}{6}. \\ \end{array}
$$

方法二 $\lim_{x\to 0}\frac{[\sin x - \sin(\sin x)]\sin x}{x^4} = \lim_{t\to 0}\frac{(t - \sin t)t}{\arcsin^4t}$

$$
= \lim  _ {t \rightarrow 0} \frac {(t - \sin t) t}{t ^ {4}} = \lim  _ {t \rightarrow 0} \frac {t - \sin t}{t ^ {3}} = \lim  _ {t \rightarrow 0} \frac {1 - \cos t}{3 t ^ {2}} = \frac {1}{6}.
$$

方法三 由 $\sin x = x - \frac{x^3}{3!} + o(x^3)$ 得

$$
\sin (\sin x) = \sin x - \frac {\sin^ {3} x}{3 !} + o (\sin^ {3} x),
$$

从而 $\sin x - \sin (\sin x)\sim \frac{1}{6}\sin^3 x\sim \frac{1}{6} x^3$

故 $\lim_{x\to 0}\frac{[\sin x - \sin(\sin x)]\sin x}{x^4} = \frac{1}{6}\lim_{x\to 0}\frac{\sin x}{x} = \frac{1}{6}.$

方法点评：计算不定型 $\frac{0}{0}$ 型的极限需要熟练掌握等价无穷小、麦克劳林公式、洛必达法则等工具. $\frac{0}{0}$ 型的极限需要补充如下两点：

(1) $x, \sin x, \tan x, \arcsin x, \arctan x$ 五个函数中任意两个函数之差为三阶无穷小.

【例】 求 $\lim_{x\to 0}\frac{\arctan{x} - \arcsin{x}}{x^3}$

【解】 $\lim_{x\to 0}\frac{\arctan x - \arcsin x}{x^3} = \lim_{x\to 0}\frac{\arctan x - x}{x^3} +\lim_{x\to 0}\frac{x - \arcsin x}{x^3},$

而 $\lim_{x\to 0}\frac{\arctan{x} - x}{x^3}\stackrel {x = \tan t}{=}\lim_{t\to 0}\frac{t - \tan t}{\tan^3t} = \lim_{t\to 0}\frac{t - \tan t}{t^3} = \lim_{t\to 0}\frac{1 - \sec^2t}{3t^2} = -\frac{1}{3},$

$$
\lim  _ {x \rightarrow 0} \frac {x - \arcsin x}{x ^ {3}} \xlongequal {x = \sin t} \lim  _ {t \rightarrow 0} \frac {\sin t - t}{\sin^ {3} t} = \lim  _ {t \rightarrow 0} \frac {\sin t - t}{t ^ {3}} = \lim  _ {t \rightarrow 0} \frac {\cos t - 1}{3 t ^ {2}} = - \frac {1}{6},
$$

故 $\lim_{x\to 0}\frac{\arctan x - \arcsin x}{x^3} = -\frac{1}{2}.$

（2）加减法使用等价无穷小时一定要保证精确度，否则会出现错误结果.

如 $\lim_{x\to 0}\frac{\arctan{x} - \arcsin{x}}{x^3}$ ，若分子使用 $\arctan x\sim x$ ， $\arcsin x\sim x$ 将导致错误结果，因为分母为三阶无穷小，分子等价无穷小的精确度不够.

(16)【解】方法一 设点 $A(\pi, 0), P(x, y) = \sin 2x, Q(x, y) = 2(x^2 - 1)y$ ，则

$$
\int_ {L} \sin 2 x d x + 2 \left(x ^ {2} - 1\right) y d y = \oint_ {L + \overline {{A O}}} \sin 2 x d x + 2 \left(x ^ {2} - 1\right) y d y + \int_ {\overline {{O A}}} \sin 2 x d x + 2 \left(x ^ {2} - 1\right) y d y,
$$

由格林公式得

$$
\begin{array}{l} \oint_ {L + \overline {{A O}}} \sin 2 x d x + 2 \left(x ^ {2} - 1\right) y d y = - \iint_ {D} 4 x y d x d y = - 4 \int_ {0} ^ {\pi} x d x \int_ {0} ^ {\sin x} y d y \\ = - 2 \int_ {0} ^ {\pi} x \sin^ {2} x d x = - 2 \cdot \frac {\pi}{2} \int_ {0} ^ {\pi} \sin^ {2} x d x \\ = - \pi \int_ {0} ^ {\pi} \sin^ {2} x d x = - 2 \pi \int_ {0} ^ {\frac {\pi}{2}} \sin^ {2} x d x \\ = - 2 \pi I _ {2} = - 2 \pi \cdot \frac {1}{2} \cdot \frac {\pi}{2} = - \frac {\pi^ {2}}{2}; \\ \end{array}
$$

$$
\int_ {\overline {{O A}}} \sin 2 x d x + 2 \left(x ^ {2} - 1\right) y d y = \int_ {0} ^ {\pi} \sin 2 x d x = - \frac {1}{2} \cos 2 x \Big | _ {0} ^ {\pi} = 0,
$$

故 $\int_{L}\sin 2x\mathrm{d}x + 2(x^{2} - 1)y\mathrm{d}y = -\frac{\pi^{2}}{2}.$

方法二 $\int_{L}\sin 2x\mathrm{d}x + 2(x^{2} - 1)y\mathrm{d}y = \int_{0}^{\pi}[\sin 2x + 2(x^{2} - 1)\sin x\cos x]\mathrm{d}x$

$$
\begin{array}{l} = \int_ {0} ^ {\pi} x ^ {2} \sin 2 x \mathrm {d} x = \int_ {0} ^ {\pi} x ^ {2} \mathrm {d} (\sin^ {2} x) \\ = x ^ {2} \sin^ {2} x \mid_ {0} ^ {\pi} - 2 \int_ {0} ^ {\pi} x \sin^ {2} x d x \\ = - 2 \cdot \frac {\pi}{2} \int_ {0} ^ {\pi} \sin^ {2} x \mathrm {d} x = - \pi \int_ {0} ^ {\pi} \sin^ {2} x \mathrm {d} x \\ = - 2 \pi \int_ {0} ^ {\frac {\pi}{2}} \sin^ {2} x d x = - 2 \pi \cdot \frac {1}{2} \cdot \frac {\pi}{2} \\ = - \frac {\pi^ {2}}{2}. \\ \end{array}
$$

(17)【解】设 $P(x,y,z)$ 为曲线 $C$ 上任意一点， $P$ 到 $xOy$ 平面的距离为 $d = |z|$ ，

令 $F(x,y,z) = z^2 +\lambda (x^2 +y^2 -2z^2) + \mu (x + y + 3z - 5)$

$\begin{cases} F_{x}^{\prime} = 2\lambda x + \mu = 0,\\ F_{y}^{\prime} = 2\lambda y + \mu = 0,\\ F_{z}^{\prime} = 2z - 4\lambda z + 3\mu = 0,\\ F_{\lambda}^{\prime} = x^{2} + y^{2} - 2z^{2} = 0,\\ F_{\mu}^{\prime} = x + y + 3z - 5 = 0, \end{cases}$ $x = 1$ ， $x = -5$ 中由 $\left\{ \begin{array}{l}x = 1,\\ y = 1,\\ z = 1 \end{array} \right.$ 或 $y = -5$ $z = 5$ $F_{\mu}^{\prime} = x + y + 3z - 5 = 0,$

故曲线 $C$ 到 $xOy$ 平面距离最近和最远的点分别为 $(1,1,1)$ 和 $(-5, - 5,5)$

(18)【证明】（I） $\Delta F(x) = F(x + \Delta x) - F(x) = \int_{0}^{x + \Delta x} f(t) \, \mathrm{d}t - \int_{0}^{x} f(t) \, \mathrm{d}t = \int_{x}^{x + \Delta x} f(t) \, \mathrm{d}t,$

因为 $f(x)$ 连续，所以由积分中值定理

$\Delta F(x) = \int_{x}^{x + \Delta x}f(t)\mathrm{d}t = f(\xi)\Delta x$ ，其中 $\xi$ 位于 $x$ 与 $x + \Delta x$ 之间，

从而 $\frac{\Delta F(x)}{\Delta x} = f(\xi)$ ，于是 $\lim_{\Delta x \to 0} \frac{\Delta F(x)}{\Delta x} = \lim_{\Delta x \to 0} f(\xi) = f(x)$ ，即 $F'(x) = f(x)$

（Ⅱ）设 $f(x + 2) = f(x)$ ，则

$$
G (x + 2) = 2 \int_ {0} ^ {x + 2} f (t) d t - (x + 2) \int_ {0} ^ {2} f (t) d t
$$

$$
\begin{array}{l} = 2 \int_ {0} ^ {x} f (t) d t - x \int_ {0} ^ {2} f (t) d t + 2 \int_ {x} ^ {x + 2} f (t) d t - 2 \int_ {0} ^ {2} f (t) d t \\ = G (x) + 2 \int_ {x} ^ {x + 2} f (t) d t - 2 \int_ {0} ^ {2} f (t) d t, \\ \end{array}
$$

由周期函数的平移性质得 $\int_{x}^{x + 2}f(t)\mathrm{d}t = \int_{0}^{2}f(t)\mathrm{d}t$ ，于是 $2\int_{x}^{x + 2}f(t)\mathrm{d}t - 2\int_{0}^{2}f(t)\mathrm{d}t = 0$ 故 $G(x + 2) = G(x)$ ，即 $G(x)$ 是以2为周期的函数.

（19）【解】 将 $f(x)$ 进行偶延拓，则

$$
\begin{array}{l} a _ {0} = \frac {2}{\pi} \int_ {0} ^ {\pi} f (x) d x = \frac {2}{\pi} \int_ {0} ^ {\pi} \left(1 - x ^ {2}\right) d x = 2 \left(1 - \frac {\pi^ {2}}{3}\right), \\ a _ {n} = \frac {2}{\pi} \int_ {0} ^ {\pi} f (x) \cos n x d x = \frac {2}{\pi} \int_ {0} ^ {\pi} \left(1 - x ^ {2}\right) \cos n x d x \\ = \frac {2}{\pi} \int_ {0} ^ {\pi} \cos n x d x - \frac {2}{\pi} \int_ {0} ^ {\pi} x ^ {2} \cos n x d x = - \frac {2}{n \pi} \int_ {0} ^ {\pi} x ^ {2} d (\sin n x) \\ = - \frac {2 x ^ {2} \sin n x}{n \pi} \Big | _ {0} ^ {\pi} + \frac {4}{n \pi} \int_ {0} ^ {\pi} x \sin n x d x = \frac {4}{n \pi} \int_ {0} ^ {\pi} x \sin n x d x \\ = - \frac {4}{n ^ {2} \pi} \int_ {0} ^ {\pi} x d (\cos n x) = - \left. \frac {4 x \cos n x}{n ^ {2} \pi} \right| _ {0} ^ {\pi} + \frac {4}{n ^ {2} \pi} \int_ {0} ^ {\pi} \cos n x d x \\ = \frac {4 (- 1) ^ {n + 1}}{n ^ {2}} (n = 1, 2, \dots); \\ \end{array}
$$

$b_{n} = 0(n = 1,2,\dots)$ ，于是 $f(x) = 1 - x^{2}$ 的余弦级数为

$$
1 - x ^ {2} = 1 - \frac {\pi^ {2}}{3} + \sum_ {n = 1} ^ {\infty} \frac {4 (- 1) ^ {n + 1}}{n ^ {2}} \cos n x \quad (0 \leqslant x \leqslant \pi),
$$

令 $x = 0$ ，则 $\sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{n^{2}} = \sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{n^{2}} = \frac{\pi^{2}}{12}$ .

（20）【证明】 $(\mathrm{I})r(\mathbf{A}) = r(\pmb {\alpha}\pmb{\alpha}^{\mathrm{T}} + \pmb {\beta}\pmb{\beta}^{\mathrm{T}})\leqslant r(\pmb {\alpha}\pmb{\alpha}^{\mathrm{T}}) + r(\pmb {\beta}\pmb{\beta}^{\mathrm{T}})$

$$
= r (\boldsymbol {\alpha}) + r (\boldsymbol {\beta}) \leqslant 1 + 1 = 2;
$$

（Ⅱ）若 $\alpha, \beta$ 线性相关，则 $\alpha, \beta$ 成比例，不妨设 $\beta = k\alpha$

则 $\mathbf{A} = \pmb{\alpha}\pmb{\alpha}^{\mathrm{T}} + \pmb{\beta}\pmb{\beta}^{\mathrm{T}} = (1 + k^{2})\pmb{\alpha}\pmb{\alpha}^{\mathrm{T}},$

于是 $r(\mathbf{A}) = r[(1 + k^2)\pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}] = r(\pmb{\alpha}\pmb{\alpha}^{\mathrm{T}}) = r(\pmb{\alpha})\leqslant 1 <   2.$

方法点评：本题需要熟悉矩阵秩的性质及向量相关性质，

研究矩阵秩时，注意以下性质的使用：

（1）当出现矩阵加减时，往往使用 $r(\mathbf{A} \pm \mathbf{B}) \leqslant r(\mathbf{A}) + r(\mathbf{B})$   
（2）若出现 $\mathbf{A}^{\mathrm{T}}\mathbf{A}$ 时，往往使用 $r(\mathbf{A}^{\mathrm{T}}\mathbf{A}) = r(\mathbf{A}\mathbf{A}^{\mathrm{T}}) = r(\mathbf{A})$   
（3）若出现 $\mathbf{AB}$ 时，往往使用 $r(\mathbf{AB})\leqslant \min \{r(\mathbf{A}),r(\mathbf{B})\}$   
（4）若出现 $\mathbf{AB} = \mathbf{0}$ 时，往往使用 $r(\mathbf{A}) + r(\mathbf{B})\leqslant n$

（21）【解】（I）方法一 数学归纳法

当 $n = 1$ 时， $\left|\mathbf{A}\right| = D_{1} = 2a$ ，结论显然成立；

设当 $n = k$ 时， $\left|\mathbf{A}\right| = D_k = (k + 1)a^k$

当 $n = k + 1$ 时， $\left|\mathbf{A}\right| = D_{k + 1} = 2aD_k - a^2 D_{k - 1} = 2a(k + 1)a^k -ka^{k + 1}$

$$
= 2 (k + 1) a ^ {k + 1} - k a ^ {k + 1} = (k + 2) a ^ {k + 1},
$$

由数学归纳法，对一切的自然数 $n$ ，有 $\mid A\mid = (n + 1)a^n$

方法二 $|\mathbf{A}| = \left| \begin{array}{ccccc}2a & 1 & 0 & \dots & 0\\ a^2 & 2a & 1 & \dots & 0\\ 0 & a^2 & 2a & \dots & 0\\ \vdots & \vdots & \vdots & & \vdots \\ 0 & 0 & 0 & \dots & 1\\ 0 & 0 & 0 & \dots & 2a \end{array} \right| = \left| \begin{array}{ccccc}2a & 1 & 0 & \dots & 0\\ 0 & \frac{3a}{2} & 1 & \dots & 0\\ 0 & a^2 & 2a & \dots & 0\\ \vdots & \vdots & \vdots & & \vdots \\ 0 & 0 & 0 & \dots & 1\\ 0 & 0 & 0 & \dots & 2a \end{array} \right|$

$$
= \dots = \left| \begin{array}{c c c c c} 2 a & 1 & 0 & \dots & 0 \\ 0 & \frac {3 a}{2} & 1 & \dots & 0 \\ 0 & 0 & \frac {4 a}{3} & \dots & 0 \\ \vdots & \vdots & \vdots & & \vdots \\ 0 & 0 & 0 & \dots & 1 \\ 0 & 0 & 0 & \dots & \frac {(n + 1) a}{n} \end{array} \right| = (n + 1) a ^ {n}.
$$

方法三 令 $D_{n} = |\mathbf{A}|$ ，将 $D_{n}$ 按第一列展开，得 $D_{n} = 2aD_{n - 1} - a^{2}D_{n - 2}$

从而 $D_{n} - aD_{n - 1} = a(D_{n - 1} - aD_{n - 2})$ ，由递推关系得

$$
D _ {n} - a D _ {n - 1} = a \left(D _ {n - 1} - a D _ {n - 2}\right) = \dots = a ^ {n - 2} \left(D _ {2} - a D _ {1}\right) = a ^ {n},
$$

于是 $D_{n} = aD_{n - 1} + a^{n} = a(aD_{n - 2} + a^{n - 1}) + a^{n} = a^{2}D_{n - 2} + 2a^{n}$

$$
= \dots = a ^ {n - 1} D _ {1} + (n - 1) a ^ {n} = (n + 1) a ^ {n}.
$$

（Ⅱ）当 $r(\mathbf{A}) = n$ 或 $|\mathbf{A}| \neq 0$ ，即 $a \neq 0$ 时，方程组有唯一解，

由 $D_{1} = \left| \begin{array}{ccccc}1 & 1 & 0 & \dots & 0\\ 0 & 2a & 1 & \dots & 0\\ 0 & a^{2} & 2a & \dots & 0\\ \vdots & \vdots & \vdots & & \vdots \\ 0 & 0 & 0 & \dots & 2a \end{array} \right| = na^{n - 1}$ ，得 $x_{1} = \frac{D_{1}}{D} = \frac{n}{(n + 1)a}.$

（Ⅲ）当 $r(\mathbf{A}) < n$ 或 $|\mathbf{A}| = 0$ ，即 $a = 0$ 时，方程组 $\mathbf{AX} = \mathbf{b}$ 有无数个解，

由 $\overline{\mathbf{A}} = \begin{bmatrix} 0 & 1 & 0 & \dots & 0 & 1 \\ 0 & 0 & 1 & \dots & 0 & 0 \\ \vdots & \vdots & \vdots & & \vdots & \vdots \\ 0 & 0 & 0 & \dots & 1 & 0 \\ 0 & 0 & 0 & \dots & 0 & 0 \end{bmatrix}$ , 得通解为 $\mathbf{X} = C\begin{bmatrix} 1 \\ 0 \\ 0 \\ \vdots \\ 0 \end{bmatrix} + \begin{bmatrix} 0 \\ 1 \\ 0 \\ \vdots \\ 0 \end{bmatrix}$ (C为任意常数).

方法点评：本题需要特别注意三对角行列式的计算方法，通常三对角行列式的计算方法有按行（或列）展开、归纳法等.

(22)【解】（I） $P\left\{Z \leqslant \frac{1}{2} \mid X = 0\right\} = P\left\{Y \leqslant \frac{1}{2}\right\} = \int_{0}^{\frac{1}{2}} 1 \, \mathrm{d}y = \frac{1}{2}$ .

$(\mathrm{II})F_{Z}(z) = P\{Z\leqslant z\} = P\{X + Y\leqslant z\}$

当 $z < -1$ 时， $F_{Z}(z) = 0$

当 $z \geqslant 2$ 时， $F_{Z}(z) = 1$

当 $-1\leqslant z <   2$ 时，

$$
\begin{array}{l} F _ {Z} (z) = P \{X = - 1 \} \cdot P \{X + Y \leqslant z \mid X = - 1 \} + P \{X = 0 \} \cdot P \{X + Y \leqslant z \mid X = 0 \} + \\ P \{X = 1 \} \cdot P \{X + Y \leqslant z \mid X = 1 \} \\ = \frac {1}{3} P \{Y \leqslant z + 1 \} + \frac {1}{3} P \{Y \leqslant z \} + \frac {1}{3} P \{Y \leqslant z - 1 \}, \\ \end{array}
$$

当 $-1\leqslant z <   0$ 时， $F_{Z}(z) = \frac{1}{3} P\{Y\leqslant z + 1\} = \frac{1}{3}\int_{0}^{z + 1}\mathrm{d}y = \frac{1}{3} (z + 1);$

当 $0 \leqslant z < 1$ 时， $F_{Z}(z) = \frac{1}{3} + \frac{1}{3} P\{Y \leqslant z\} = \frac{1}{3} + \frac{1}{3} \int_{0}^{z} \mathrm{d}y = \frac{1}{3} (z + 1)$

当 $1 \leqslant z < 2$ 时， $F_{Z}(z) = \frac{2}{3} + \frac{1}{3} P\{Y \leqslant z - 1\} = \frac{2}{3} + \frac{1}{3} \int_{0}^{z - 1} \mathrm{d}y = \frac{1}{3} (z + 1)$ ，

从而 $F_{Z}(z) = \left\{ \begin{array}{ll}0, & z < - 1,\\ \frac{1}{3} (z + 1), & -1\leqslant z < 2,\\ 1, & z\geqslant 2. \end{array} \right.$

故 $f_{Z}(z) = \left\{ \begin{array}{ll} \frac{1}{3}, & -1 < z < 2, \\ 0, & \text{其他}. \end{array} \right.$

方法点评：设随机变量 $X$ 为离散型，其分布律为 $P\{X = x_i\} = p_i (i = 1,2,\dots,m)$ ，而随机变量 $Y$ 为连续型，其分布函数为 $f(x)$ ，且 $X, Y$ 独立，求 $Z = X + Y$ 的分布函数时往往使用全概率公式，即

$$
\begin{array}{l} F _ {Z} (z) = P \{Z \leqslant z \} = P \{X + Y \leqslant z \} \\ = P \{X = x _ {1} \} P \{X + Y \leqslant z \mid X = x _ {1} \} + \dots + P \{X = x _ {m} \} P \{X + Y \leqslant z \mid X = x _ {n} \}. \\ \end{array}
$$

(23)【解】（I）由 $\overline{X} \sim N\left(\mu, \frac{\sigma^2}{n}\right)$ ，得 $E(\overline{X}^2) = D(\overline{X}) + [E(\overline{X})]^2 = \frac{\sigma^2}{n} + \mu^2$

再由 $E(S^2) = \sigma^2$ ，得 $E(T) = E(\overline{X}^2) - \frac{1}{n} E(S^2) = \frac{\sigma^2}{n} +\mu^2 -\frac{\sigma^2}{n} = \mu^2.$

于是 $T = \overline{X}^2 -\frac{1}{n} S^2$ 为 $\mu^2$ 的无偏估计量.

（Ⅱ）当 $\mu = 0, \sigma = 1$ 时， $\overline{X} \sim N\left(0, \frac{1}{n}\right)$ ，标准化得 $\sqrt{n}\overline{X} \sim N(0,1)$ ，于是 $n\overline{X}^2 \sim \chi^2(1)$

又 $\frac{(n - 1)S^2}{\sigma^2} = (n - 1)S^2 \sim \chi^2(n - 1)$ ，且 $\overline{X}$ 与 $S^2$ 独立，得

$$
\begin{array}{l} D (T) = D \left(\bar {X} ^ {2}\right) + \frac {1}{n ^ {2}} D \left(S ^ {2}\right) = \frac {1}{n ^ {2}} D \left(n \bar {X} ^ {2}\right) + \frac {1}{n ^ {2} (n - 1) ^ {2}} D [ (n - 1) S ^ {2} ] \\ = \frac {2}{n ^ {2}} + \frac {2 (n - 1)}{n ^ {2} (n - 1) ^ {2}} = \frac {2}{n ^ {2}} + \frac {2}{n ^ {2} (n - 1)} = \frac {2}{n (n - 1)}. \\ \end{array}
$$