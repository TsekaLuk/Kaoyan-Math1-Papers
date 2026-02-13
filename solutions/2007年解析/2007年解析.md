# 2007年数学(一）真题解析

# 一、选择题

(1)【答案】 (B).

【解】 $\ln \frac{1 + x}{1 - \sqrt{x}} = \ln (1 + x) - \ln (1 - \sqrt{x})$

由 $\ln (1 + x)\sim x,\ln (1 - \sqrt{x})\sim -\sqrt{x}$ ，得 $\ln {\frac{1 + x}{1 - \sqrt{x}}}\sim \sqrt{x}$ ，应选(B).

(2)【答案】 (D).

【解】由 $\lim_{x\to 0}f(x) = \infty$ ，得 $x = 0$ 为 $y = \frac{1}{x} +\ln (1 + \mathrm{e}^{x})$ 的铅直渐近线；

由 $\lim_{x\to -\infty}f(x) = 0,\lim_{x\to +\infty}f(x) = +\infty$ ，得 $y = 0$ 为 $y = \frac{1}{x} +\ln (1 + \mathrm{e}^{x})$ 的水平渐近线；

由 $\lim_{x\to +\infty}\frac{f(x)}{x} = 1,\lim_{x\to +\infty}[f(x) - x] = \lim_{x\to +\infty}\ln \frac{1 + \mathrm{e}^x}{\mathrm{e}^x} = 0$ ，得 $y = x$ 为 $y = \frac{1}{x} +\ln (1 + \mathrm{e}^{x})$

的斜渐近线，于是曲线 $y = \frac{1}{x} +\ln (1 + \mathrm{e}^{x})$ 有3条渐近线，应选(D).

方法点评：曲线的渐近线共有三种类型：

水平渐近线：若 $\lim_{x\to \infty}f(x) = A$ ，则 $y = A$ 为 $y = f(x)$ 的水平渐近线；

铅直渐近线：若 $\lim_{x\to a}f(x) = \infty$ ，则 $x = a$ 为 $y = f(x)$ 的铅直渐近线（ $f(x)$ 的间断点处才可能产生铅直渐近线）；

斜渐近线：设 $\lim_{x\to \infty}\frac{f(x)}{x} = a(\neq 0,\infty),\lim_{x\to \infty}[f(x) - ax] = b$ ，则 $y = ax + b$ 为曲线 $y = f(x)$ 的斜渐近线.

(3)【答案】 (C).

【解】方法一 因为 $f(x)$ 是奇函数，所以 $F(x) = \int_{0}^{x}f(t)\mathrm{d}t$ 为偶函数，

于是 $F(-3) = F(3), F(-2) = F(2)$ ，根据定积分的几何意义，得

$$
F (2) = \frac {1}{2} \cdot \pi \cdot 1 ^ {2} = \frac {\pi}{2}, \quad F (3) = \frac {\pi}{2} - \frac {1}{2} \cdot \pi \cdot \left(\frac {1}{2}\right) ^ {2} = \frac {3 \pi}{8}, \quad F (- 3) = \frac {3}{4} F (2),
$$

应选(C).

方法二 根据定积分的几何意义，得

$$
F (- 3) = \int_ {0} ^ {- 3} f (t) d t = - \int_ {- 3} ^ {0} f (t) d t = - \left(\frac {\pi}{8} - \frac {\pi}{2}\right) = \frac {3 \pi}{8},
$$

$$
F (- 2) = \int_ {0} ^ {- 2} f (t) \mathrm {d} t = - \int_ {- 2} ^ {0} f (t) \mathrm {d} t = - \left(- \frac {\pi}{2}\right) = \frac {\pi}{2},
$$

$F(2) = \int_{0}^{2}f(t)\mathrm{d}t = \frac{\pi}{2},\quad F(3) = \int_{0}^{3}f(t)\mathrm{d}t = \frac{\pi}{2} -\frac{\pi}{8} = \frac{3\pi}{8}$ 应选(C).

方法点评：本题考查定积分的几何意义.

当曲线位于 $x$ 轴上方时，定积分的值与曲边梯形面积的值相等；当曲线位于 $x$ 轴下方时，定积分的值与曲边梯形面积的值互为相反数.

（4）【答案】 (D).

【解】方法一 由 $\lim_{x\to 0}\frac{f(x)}{x}$ 存在，得 $\lim_{x\to 0}f(x) = 0$

由 $f(x)$ 在 $x = 0$ 处连续，得 $\lim_{x\to 0}f(x) = f(0) = 0$

由 $\lim_{x\to 0}\frac{f(x) + f(-x)}{x}$ 存在，得 $\lim_{x\to 0}[f(x) + f(-x)] = 0$

由 $f(x)$ 在 $x = 0$ 处连续，得 $\lim_{x\to 0}[f(x) + f(-x)] = 2f(0) = 0$ ，于是 $f(0) = 0$

由 $\lim_{x\to 0}\frac{f(x)}{x}$ 存在，得 $\lim_{x\to 0}f(x) = 0$ ，因为 $f(x)$ 在 $x = 0$ 处连续，所以 $\lim_{x\to 0}f(x) = f(0) = 0$

再由 $\lim_{x\to 0}\frac{f(x)}{x} = \lim_{x\to 0}\frac{f(x) - f(0)}{x}$ 存在，得 $f^{\prime}(0)$ 存在，应选(D).

方法二 取 $f(x) = \begin{cases} x^2, & x \neq 0, \\ 2, & x = 0, \end{cases}$ 显然 $\lim_{x \to 0} \frac{f(x) - f(-x)}{x} = 0$ ，但 $f(x)$ 在 $x = 0$ 处不可导，应选(D).

方法点评：本题考查连续与可导的概念

导数定义为 $f^{\prime}(x_0) = \lim_{\Delta x\to 0}\frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}$ ，其等价定义为

$$
f ^ {\prime} \left(x _ {0}\right) = \lim  _ {x \rightarrow x _ {0}} \frac {f (x) - f \left(x _ {0}\right)}{x - x _ {0}}.
$$

但导数定义要注意以下几点：

（1）趋于零的自变量必须保证从原点两侧趋于零

$$
\lim  _ {\Delta x \rightarrow 0 ^ {+}} \frac {f (x _ {0} + \Delta x) - f (x _ {0})}{\Delta x} = f _ {+} ^ {\prime} (x _ {0}), \quad \lim  _ {\Delta x \rightarrow 0 ^ {-}} \frac {f (x _ {0} + \Delta x) - f (x _ {0})}{\Delta x} = f _ {-} ^ {\prime} (x _ {0}),
$$

$f^{\prime}(x_0)$ 存在的充要条件是 $f_{+}^{\prime}(x_0)$ 与 $f_{-}^{\prime}(x_0)$ 都存在且相等.

(2) 函数增量 $f(x_0 + \Delta x) - f(x_0)$ 中，后一项必须为 $f(x_0)$ ，

如：设 $f^{\prime}(x_0)$ 存在，则 $\lim_{h\to 0}\frac{f(x_0 + ah) - f(x_0 + bh)}{h} = (a - b)f'(x_0)$ ；反之，若 $\lim_{h\to 0}\frac{f(x_0 + ah) - f(x_0 + bh)}{h}$ 存在，则 $f^{\prime}(x_0)$ 不一定存在.

（5）【答案】 (D).

【解】方法一 取 $f(x) = -\ln x, f''(x) = \frac{1}{x^2} > 0, u_1 = f(1) = 0 > u_2 = f(2) = -\ln 2$ ，但 $\{u_n\}$ 发散，（A）不对；

取 $f(x) = \frac{1}{x^2}, f''(x) = \frac{6}{x^4} > 0, u_1 = 1 > u_2 = \frac{1}{4}$ ，但 $\{u_n\}$ 收敛，（B）不对；

取 $f(x) = x^3, f''(x) = 6x > 0, u_1 = 1 < u_2 = 8$ ，但 $\{u_n\}$ 发散，（C）不对，应选(D).

方法二 由拉格朗日中值定理，存在 $\xi_1\in (1,2),\xi_2\in (2,3),\dots ,\xi_{n - 1}\in (n - 1,n)$ ，使得

$$
\left\{ \begin{array}{l} u _ {2} - u _ {1} = f (2) - f (1) = f ^ {\prime} (\xi_ {1}), \\ u _ {3} - u _ {2} = f (3) - f (2) = f ^ {\prime} (\xi_ {2}), \\ \vdots \\ u _ {n} - u _ {n - 1} = f (n) - f (n - 1) = f ^ {\prime} (\xi_ {n - 1}), \end{array} \right.
$$

相加得 $u_{n} = u_{1} + f^{\prime}(\xi_{1}) + f^{\prime}(\xi_{2}) + \dots +f^{\prime}(\xi_{n - 1})$ ，因为 $f''(x) > 0$ ，所以 $f^{\prime}(x)$ 单调增加，从而 $f^{\prime}(\xi_1) <   f^{\prime}(\xi_2) <   \dots <  f^{\prime}(\xi_{n - 1})$ ，于是 $u_{n}\geqslant u_{1} + (n - 1)f^{\prime}(\xi_{1}) = u_{1} + n(u_{2} - u_{1})$ 当 $u_{1} <   u_{2}$ 时， $\lim_{n\to \infty}u_n = +\infty$ ，应选(D).

方法三 由 $f''(x) > 0$ 得 $f'(x)$ 在 $(0, +\infty)$ 内单调增加.

情形一：存在 $c \in (0, +\infty)$ ，使得 $f'(c) = 0$ ，当 $x > c$ 时， $f'(x) > f'(c)$ .

取 $x_{1} > c$ ，当 $x > x_{1}$ 时， $f(x) = f(x_{1}) + f'(\xi)(x - x_{1})$ ，其中 $\xi \in (x_{1}, x)$ .

由 $f(x) \geqslant f(x_1) + f'(x_1)(x - x_1)$ ，两边取极限得 $\lim_{x \to +\infty} f(x) = +\infty$ ，从而 $\lim_{n \to \infty} f(n) = +\infty$ ；情形二：对一切的 $x \in (0, +\infty)$ ，有 $f'(x) > 0$ ，由 $f(x) \geqslant f(1) + f'(1)(x - 1)$ ，两边取极限得 $\lim_{x \to +\infty} f(x) = +\infty$ ，从而 $\lim_{n \to \infty} f(n) = +\infty$ ；

情形三：对一切的 $x\in (0, + \infty)$ ，有 $f^{\prime}(x) < 0$ ，取 $x > 1$ ，由拉格朗日中值定理，

存在 $\xi \in (1, x)$ ，使得 $f(x) = f(1) + f'(\xi)(x - 1)$ ，两边取极限得 $\lim_{x \to +\infty} f(x) = -\infty$ ，从而 $\lim_{n \to \infty} f(n) = -\infty$ ，应选(D).

方法点评：本题考查数列极限的存在性，难度较大。涉及由可导函数生成的数列极限的存在性问题一般采用反例法或微分中值定理。

（6）【答案】 (B).

【解】 $\int_{\Gamma}f(x,y)\mathrm{d}x = \int_{\Gamma}\mathrm{d}x,\quad \int_{\Gamma}f(x,y)\mathrm{d}y = \int_{\Gamma}\mathrm{d}y,$

因为 $\mathrm{dx} > 0, \mathrm{dy} < 0$ ，所以 $\int_{\Gamma} f(x, y) \mathrm{d}y = \int_{\Gamma} \mathrm{d}y < 0$ ，应选(B).

方法点评：对坐标的曲线积分 $\int_{L} P(x, y) \mathrm{d}x + Q(x, y) \mathrm{d}y$ 中，当 $L$ 的方向是从左到右时， $\mathrm{d}x > 0$ ，当 $L$ 的方向是从右到左时， $\mathrm{d}x < 0$ ；当 $L$ 的方向是从下到上时， $\mathrm{d}y > 0$ ，当 $L$ 的方向是从上到下时， $\mathrm{d}y < 0$ 。

（7）【答案】 (A).

【解】方法一 由 $(\alpha_{1} - \alpha_{2}) + (\alpha_{2} - \alpha_{3}) + (\alpha_{3} - \alpha_{1}) = 0$ ，得向量组 $\alpha_{1} - \alpha_{2}, \alpha_{2} - \alpha_{3}, \alpha_{3} - \alpha_{1}$ 线性相关，应选（A）.

方法二 $(\pmb{\alpha}_{1} - \pmb{\alpha}_{2},\pmb{\alpha}_{2} - \pmb{\alpha}_{3},\pmb{\alpha}_{3} - \pmb{\alpha}_{1}) = (\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3})\cdot \left( \begin{array}{ccc}1 & 0 & -1\\ -1 & 1 & 0\\ 0 & -1 & 1 \end{array} \right),$

由 $\left| \begin{array}{ccc}1 & 0 & -1\\ -1 & 1 & 0\\ 0 & -1 & 1 \end{array} \right| = \left| \begin{array}{ccc}1 & 0 & -1\\ 0 & 1 & -1\\ 0 & -1 & 1 \end{array} \right| = 0,$

得 $|\alpha_{1} - \alpha_{2},\alpha_{2} - \alpha_{3},\alpha_{3} - \alpha_{1}| = |\alpha_{1},\alpha_{2},\alpha_{3}|\cdot 0 = 0,$

于是向量组 $\alpha_{1} - \alpha_{2},\alpha_{2} - \alpha_{3},\alpha_{3} - \alpha_{1}$ 线性相关，应选（A）.

方法三 令 $\mathbf{A} = (\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3)$ ，因为 $\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3$ 线性无关，所以 $r(\mathbf{A}) = 3$ .

$$
(\pmb {\alpha} _ {1} + \pmb {\alpha} _ {2}, \pmb {\alpha} _ {2} + \pmb {\alpha} _ {3}, \pmb {\alpha} _ {3} + \pmb {\alpha} _ {1}) = (\pmb {\alpha} _ {1}, \pmb {\alpha} _ {2}, \pmb {\alpha} _ {3}) \left( \begin{array}{l l l} 1 & 0 & 1 \\ 1 & 1 & 0 \\ 0 & 1 & 1 \end{array} \right),
$$

因为 $\left| \begin{array}{lll}1 & 0 & 1\\ 1 & 1 & 0\\ 0 & 1 & 1 \end{array} \right| = 2\neq 0$ ，所以 $\binom{1\quad 0\quad 1}{1\quad 1\quad 0}$ 可逆，

从而 $r(\pmb{\alpha}_1 + \pmb{\alpha}_2, \pmb{\alpha}_2 + \pmb{\alpha}_3, \pmb{\alpha}_3 + \pmb{\alpha}_1) = r(\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3) = 3$ ，即 $\pmb{\alpha}_1 + \pmb{\alpha}_2, \pmb{\alpha}_2 + \pmb{\alpha}_3, \pmb{\alpha}_3 + \pmb{\alpha}_1$ 线性无关，（B）不对；

$$
(\boldsymbol {\alpha} _ {1} - 2 \boldsymbol {\alpha} _ {2}, \boldsymbol {\alpha} _ {2} - 2 \boldsymbol {\alpha} _ {3}, \boldsymbol {\alpha} _ {3} - 2 \boldsymbol {\alpha} _ {1}) = (\boldsymbol {\alpha} _ {1}, \boldsymbol {\alpha} _ {2}, \boldsymbol {\alpha} _ {3}) \left( \begin{array}{c c c} 1 & 0 & - 2 \\ - 2 & 1 & 0 \\ 0 & - 2 & 1 \end{array} \right),
$$

因为 $\left| \begin{array}{ccc}1 & 0 & -2\\ -2 & 1 & 0\\ 0 & -2 & 1 \end{array} \right| = -7\neq 0$ ，所以 $\left( \begin{array}{rrr}1 & 0 & -2\\ -2 & 1 & 0\\ 0 & -2 & 1 \end{array} \right)$ 可逆，

从而 $r(\pmb{\alpha}_1 - 2\pmb{\alpha}_2, \pmb{\alpha}_2 - 2\pmb{\alpha}_3, \pmb{\alpha}_3 - 2\pmb{\alpha}_1) = r(\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3) = 3$ ，即 $\pmb{\alpha}_1 - 2\pmb{\alpha}_2, \pmb{\alpha}_2 - 2\pmb{\alpha}_3, \pmb{\alpha}_3 - 2\pmb{\alpha}_1$ 线性无关，（C）不对；

$$
(\boldsymbol {\alpha} _ {1} + 2 \boldsymbol {\alpha} _ {2}, \boldsymbol {\alpha} _ {2} + 2 \boldsymbol {\alpha} _ {3}, \boldsymbol {\alpha} _ {3} + 2 \boldsymbol {\alpha} _ {1}) = (\boldsymbol {\alpha} _ {1}, \boldsymbol {\alpha} _ {2}, \boldsymbol {\alpha} _ {3}) \left( \begin{array}{l l l} 1 & 0 & 2 \\ 2 & 1 & 0 \\ 0 & 2 & 1 \end{array} \right),
$$

因为 $\left| \begin{array}{lll}1 & 0 & 2\\ 2 & 1 & 0\\ 0 & 2 & 1 \end{array} \right| = 9\neq 0$ ，所以 $\binom{1}{2}\binom{0}{1}$ 可逆，

从而 $r(\pmb{\alpha}_1 + 2\pmb{\alpha}_2, \pmb{\alpha}_2 + 2\pmb{\alpha}_3, \pmb{\alpha}_3 + 2\pmb{\alpha}_1) = r(\pmb{\alpha}_1, \pmb{\alpha}_2, \pmb{\alpha}_3) = 3$

即 $\alpha_{1} + 2\alpha_{2},\alpha_{2} + 2\alpha_{3},\alpha_{3} + 2\alpha_{1}$ 线性无关，（D）不对，应选(A).

（8）【答案】 （B）.

【解】由 $|\lambda E - A| = \left| \begin{array}{ccc}\lambda -2 & 1 & 1\\ 1 & \lambda -2 & 1\\ 1 & 1 & \lambda -2 \end{array} \right| = \lambda (\lambda -3)^2 = 0$ ，得 $\mathbf{A}$ 的特征值为 $\lambda_1 = 0$ $\lambda_{2} = \lambda_{3} = 3;\pmb{B}$ 的特征值为 $\lambda_1 = \lambda_2 = 1,\lambda_3 = 0$ ，因为 $A,B$ 都是实对称矩阵，且正、负惯性指数相同，所以 $\mathbf{A}$ 与 $\pmb{B}$ 合同，又因为 $A,B$ 特征值不同，所以 $\mathbf{A}$ 与 $\pmb{B}$ 不相似，应选(B).

方法点评：本题考查矩阵的相似与合同关系.

（1）设 $A, B$ 为 $n$ 阶实对称矩阵，则 $A \sim B$ 的充要条件是 $A, B$ 特征值相同； $A \cong B$ 的充要条件是 $A, B$ 特征值中正、负特征值个数相同，故若 $A, B$ 相似，则 $A, B$ 一定合同，反之不对.  
（2）设 $A, B$ 为 $n$ 阶不对称矩阵， $A \sim B$ 的必要条件是 $A, B$ 特征值相同，其中若 $A, B$ 都可对角化，则 $A \sim B$ ；若 $A, B$ 中一个可对角化，另一个不可对角化，则 $A, B$ 不相似.

（9）【答案】 (C).

【解】第4次射击为第2次命中的概率为 $\mathrm{C}_3^1 p(1 - p)^2 p = 3p^2 (1 - p)^2$ ，应选(C).

（10）【答案】 (A).

【解】因为 $(X,Y)$ 服从二维正态分布，所以 $X,Y$ 不相关的充分必要条件是 $X,Y$ 独立，于是 $f(x,y) = f_{X}(x)f_{Y}(y)$ ，故 $f_{X|Y}(x|y) = \frac{f(x,y)}{f_{Y}(y)} = f_{X}(x)$ ，应选(A).

# 二、填空题

(11)【答案】 $\frac{\sqrt{\mathrm{e}}}{2}$ .

【解】 $\int_{1}^{2}\frac{1}{x^3}\mathrm{e}^{\frac{1}{x}}\mathrm{d}x = -\int_{1}^{2}\frac{1}{x}\mathrm{e}^{\frac{1}{x}}\mathrm{d}\left(\frac{1}{x}\right) = \int_{\frac{1}{2}}^{1}t\mathrm{e}^{t}\mathrm{d}t = (t - 1)\mathrm{e}^{t}\Bigg{|}_{\frac{1}{2}}^{1} = \frac{\sqrt{\mathrm{e}}}{2}.$

(12)【答案】 $yx^{y - 1}f_1' + y^x\ln yf_2'$ .

【解】 $z = f(x^{y}, y^{x})$ 两边对 $x$ 求偏导，得 $\frac{\partial z}{\partial x} = yx^{y - 1}f_{1}' + y^{x}\ln yf_{2}'$

(13)【答案】 $C_1\mathrm{e}^x + C_2\mathrm{e}^{3x} - 2\mathrm{e}^{2x}(C_1, C_2$ 为任意常数）.

【解】 $y^{\prime \prime} - 4y^{\prime} + 3y = 0$ 的特征方程为 $\lambda^2 - 4\lambda + 3 = 0$ ，特征值为 $\lambda_1 = 1, \lambda_2 = 3$ ， $y^{\prime \prime} - 4y^{\prime} + 3y = 0$ 的通解为 $y = C_1\mathrm{e}^x + C_2\mathrm{e}^{3x}$ （ $C_1, C_2$ 为任意常数）.

令原方程的特解为 $y_0(x) = a\mathrm{e}^{2x}$ ，代入原方程得 $a = -2$ ，于是原方程的通解为

$y = C_{1}\mathrm{e}^{x} + C_{2}\mathrm{e}^{3x} - 2\mathrm{e}^{2x}(C_{1},C_{2}$ 为任意常数）.

(14)【答案】 $\frac{4\sqrt{3}}{3}$ .

【解】 由对称性及奇偶性得

$$
\begin{array}{l} \oiint_ {\Sigma} (x + | y |) \mathrm {d} S = \oiint_ {\Sigma} | y | \mathrm {d} S = \frac {1}{3} \oiint_ {\Sigma} (| x | + | y | + | z |) \mathrm {d} S \\ = \frac {1}{3} \oiint_ {\Sigma} d S = \frac {1}{3} \times 8 \times \frac {1}{2} \times \sqrt {2} \times \sqrt {2} \times \frac {\sqrt {3}}{2} = \frac {4 \sqrt {3}}{3}. \\ \end{array}
$$

方法点评：本题考查对面积的曲面积分的奇偶性与对称性

对面积的曲面积分的对称性质如下：

(1) 若 $\Sigma$ 关于 $xOy$ 平面对称, 且位于 $xOy$ 平面上方的部分为 $\Sigma_{1}$ ,

当 $f(x,y, - z) = -f(x,y,z)$ 时， $\iint_{S} f(x,y,z) \mathrm{d}S = 0$

当 $f(x,y, - z) = f(x,y,z)$ 时 $\iint_{\Sigma}f(x,y,z)\mathrm{d}S = 2\iint_{\Sigma}f(x,y,z)\mathrm{d}S.$

(2) 若 $\Sigma$ 关于 $yOz$ 平面对称, 且位于 $yOz$ 平面前侧的部分为 $\Sigma_{1}$ ,

当 $f(-x,y,z) = -f(x,y,z)$ 时， $\iint_{S} f(x,y,z) \, \mathrm{d}S = 0$

当 $f(-x,y,z) = f(x,y,z)$ 时 $\iint_{\Sigma}f(x,y,z)\mathrm{d}S = 2\iint_{\Sigma_i}f(x,y,z)\mathrm{d}S.$

（3）若 $\Sigma$ 关于 $xOz$ 平面对称，且位于 $xOz$ 平面右侧的部分为 $\Sigma_{1}$

当 $f(x, -y, z) = -f(x, y, z)$ 时 $\iint_{\Sigma} f(x, y, z) \mathrm{d}S = 0$

当 $f(x, -y, z) = f(x, y, z)$ 时 $\iint_{\Sigma} f(x, y, z) \mathrm{d}S = 2 \iint_{\Sigma_1} f(x, y, z) \mathrm{d}S.$

（15）【答案】 1.

【解】 由 $\mathbf{A} = \begin{bmatrix} 0 & 1 & 0 & 0\\ 0 & 0 & 1 & 0\\ 0 & 0 & 0 & 1\\ 0 & 0 & 0 & 0 \end{bmatrix}$ ，得 $A^3 = \begin{bmatrix} 0 & 0 & 0 & 1\\ 0 & 0 & 0 & 0\\ 0 & 0 & 0 & 0\\ 0 & 0 & 0 & 0 \end{bmatrix}$ ，于是 $r(\mathbf{A}^3) = 1$

(16)【答案】 $\frac{3}{4}$ .

【解】设 $X, Y$ 为 $(0,1)$ 内任取的两个数，令 $D = \{(x, y) \mid 0 < x < 1, 0 < y < 1\}$ ，则二维随机变量 $(X, Y)$ 在区域 $D$ 内服从均匀分布，联合密度函数为

$$
f (x, y) = \left\{ \begin{array}{l l} 1, & (x, y) \in D, \\ 0, & (x, y) \notin D. \end{array} \right.
$$

则 $P\left\{\mid X - Y\mid <  \frac{1}{2}\right\} = \iint \limits_{|x - y| <   \frac{1}{2}}f(x,y)\mathrm{d}x\mathrm{d}y = \frac{3}{4}.$

# 三、解答题

（17）【解】方法一 当 $x^{2} + y^{2} < 4(y > 0)$ 时，由 $\left\{ \begin{array}{l} \frac{\partial f}{\partial x} = 2x - 2xy^2 = 0, \\ \frac{\partial f}{\partial y} = 4y - 2x^2y = 0, \end{array} \right.$ 得 $\left\{ \begin{array}{l} x = \pm \sqrt{2}, \\ y = 1; \end{array} \right.$

当 $x^{2} + y^{2} = 4(y\geqslant 0)$ 时，令 $F(x,y,\lambda) = x^2 +2y^2 -x^2 y^2 +\lambda (x^2 +y^2 -4)$

由 $\left\{ \begin{array}{l} F_{x}^{\prime} = 2x - 2xy^{2} + 2\lambda x = 0, \\ F_{y}^{\prime} = 4y - 2x^{2}y + 2\lambda y = 0, \\ F_{\lambda}^{\prime} = x^{2} + y^{2} - 4 = 0, \end{array} \right.$ 得 $\left\{ \begin{array}{l} x = 0, \\ y = 2, \end{array} \right.$ $\left\{ \begin{array}{l} x = \pm 2, \\ y = 0, \end{array} \right.$ $\left\{ \begin{array}{l} x = \pm \frac{\sqrt{10}}{2}, \\ y = \frac{\sqrt{6}}{2}; \end{array} \right.$

当 $y = 0(-2 < x < 2)$ 时， $f(x, 0) = x^2$ ，由 $\frac{\mathrm{d}}{\mathrm{d}x} f(x, 0) = 2x = 0$ 得 $\left\{ \begin{array}{l} x = 0, \\ y = 0. \end{array} \right.$

而 $f(\pm \sqrt{2},1) = 2,f(0,2) = 8,f(\pm 2,0) = 4,f\left(\pm \frac{\sqrt{10}}{2},\frac{\sqrt{6}}{2}\right) = \frac{7}{4},f(0,0) = 0,$

故 $f(x,y)$ 在 $D$ 上的最小值为 $f(0,0) = 0$ ，最大值为 $f(0,2) = 8$

方法二 当 $x^{2} + y^{2} < 4$ 且 $y > 0$ 时，

由 $\left\{ \begin{array}{l} \frac{\partial f}{\partial x} = 2x - 2xy^2 = 0, \\ \frac{\partial f}{\partial y} = 4y - 2x^2y = 0. \end{array} \right.$ 得驻点为 $\left\{ \begin{array}{l} x = -\sqrt{2}, \\ y = 1 \end{array} \right.$ 及 $\left\{ \begin{array}{l} x = \sqrt{2}, \\ y = 1. \end{array} \right.$

$f(-\sqrt{2},1) = f(\sqrt{2},1) = 2;$

当 $y = 0(-2 \leqslant x \leqslant 2)$ 时， $f(x, 0) = x^2$

最小值为 $f(0,0) = 0$ ，最大值为 $f(\pm 2,0) = 4$

当 $x^{2} + y^{2} = 4(y > 0)$ 时，令 $\left\{ \begin{array}{l} x = 2\cos t, \\ y = 2\sin t \end{array} \right.$ （ $0 < t < \pi$ ），

则 $f(x,y) = 4\cos^2 t + 8\sin^2 t - 16\sin^2 t(1 - \sin^2 t)$

$$
= 1 6 \left(\sin^ {2} t - \frac {3}{8}\right) ^ {2} + \frac {7}{4},
$$

当 $\sin^2 t = \frac{3}{8}$ 时， $f(x, y)$ 取最小值 $\frac{7}{4}$ ，当 $\sin^2 t = 1$ 时， $f(x, y)$ 取最大值 8，

故函数 $f(x,y)$ 在区域 $D$ 上的最小值为 $m = 0$ ，最大值为 $M = 8$

(18)【解】补充 $\Sigma_0: z = 0\left(x^2 + \frac{y^2}{4} \leqslant 1\right)$ ，取下侧，则

$$
I = \iint_ {\Sigma + \Sigma_ {0}} x z \mathrm {d} y \mathrm {d} z + 2 y z \mathrm {d} z \mathrm {d} x + 3 x y \mathrm {d} x \mathrm {d} y - \iint_ {\Sigma_ {0}} x z \mathrm {d} y \mathrm {d} z + 2 y z \mathrm {d} z \mathrm {d} x + 3 x y \mathrm {d} x \mathrm {d} y,
$$

由高斯公式得

$$
\begin{array}{l} \oiint_ {\Sigma + \Sigma_ {0}} x z \mathrm {d} y \mathrm {d} z + 2 y z \mathrm {d} z \mathrm {d} x + 3 x y \mathrm {d} x \mathrm {d} y = \iiint_ {\Omega} (z + 2 z) \mathrm {d} v = 3 \iiint_ {\Omega} z \mathrm {d} v \\ = 3 \int_ {0} ^ {1} z \mathrm {d} z \iint_ {x ^ {2} + \frac {y ^ {2}}{4} \leqslant 1 - z} \mathrm {d} x \mathrm {d} y = 3 \pi \int_ {0} ^ {1} z \cdot \sqrt {1 - z} \cdot 2 \sqrt {1 - z} \mathrm {d} z = 6 \pi \int_ {0} ^ {1} (z - z ^ {2}) \mathrm {d} z = \pi ; \\ \iint_ {\Sigma_ {0}} x z \mathrm {d} y \mathrm {d} z + 2 y z \mathrm {d} z \mathrm {d} x + 3 x y \mathrm {d} x \mathrm {d} y = \iint_ {\Sigma_ {0}} 3 x y \mathrm {d} x \mathrm {d} y = - 3 \iint_ {x ^ {2} + \frac {y ^ {2}}{4} \leqslant 1} x y \mathrm {d} x \mathrm {d} y = 0, \\ \end{array}
$$

于是 $I = \pi$

(19)【证明】令 $h(x) = f(x) - g(x)$ ，则 $h(x)$ 在 $[a,b]$ 上连续，在 $(a,b)$ 内二阶可导，

且 $h(a) = h(b) = 0$

设 $f(x),g(x)$ 在 $(a,b)$ 内的相同最大值为 $M$ ，且令 $M = f(x_{1}) = \max_{a\leqslant x\leqslant b}f(x)$

$M = g(x_{2}) = \max_{a\leqslant x\leqslant b}g(x)$ ，其中 $x_{1}\in (a,b),x_{2}\in (a,b)$ ，不妨设 $x_{1}\leqslant x_{2}$

情形一：当 $x_{1} = x_{2}$ 时， $h(x_{1}) = 0, h(a) = h(x_{1}) = h(b) = 0.$

由罗尔中值定理，存在 $\xi_1\in (a,x_1),\xi_2\in (x_1,b)$ ，使得 $h^\prime (\xi_1) = h^\prime (\xi_2) = 0$

再由罗尔中值定理，存在 $\xi \in (\xi_1, \xi_2) \subset (a, b)$ ，使得 $h''(\xi) = 0$ ，即 $f''(\xi) = g''(\xi)$ .

情形二：当 $x_{1} <   x_{2}$ 时， $h(x_{1}) = M - g(x_{1}) > 0,h(x_{2}) = f(x_{2}) - M <   0$

因为 $h(x_{1})h(x_{2}) < 0$ ，所以由零点定理，存在 $c \in (x_1, x_2) \subset (a, b)$ ，使得 $h(c) = 0$ ，于是 $h(a) = h(c) = h(b) = 0$ .

由罗尔中值定理，存在 $\xi_1\in (a,c),\xi_2\in (c,b)$ ，使得 $h^\prime (\xi_1) = h^\prime (\xi_2) = 0$

再由罗尔中值定理，存在 $\xi \in (\xi_1, \xi_2) \subset (a, b)$ ，使得 $h''(\xi) = 0$ ，即 $f''(\xi) = g''(\xi)$ .

方法点评：证明形如 $F^{(n)}(\xi) = 0$ 往往采用罗尔定理进行证明，关键是证明函数满足罗尔定理的第三个条件.

【例】设 $f(x) \in C[a, b]$ ，在 $(a, b)$ 内二阶可导，且 $f(a) = f(b) = 0, f_{+}^{\prime}(a)f_{-}^{\prime}(b) > 0$ 证明：存在 $\xi \in (a, b)$ ，使得 $f''(\xi) = 0$

【证明】设 $f_{+}^{\prime}(a) > 0, f_{-}^{\prime}(b) > 0.$

由 $f_{+}^{\prime}(a) > 0$ ，存在 $x_{1}\in (a,b)$ ，使得 $f(x_{1}) > f(a) = 0$

由 $f_{-}^{\prime}(b) > 0$ ，存在 $x_{2}\in (a,b)$ ，使得 $f(x_{2}) <   f(b) = 0$

由 $f(x_{1})f(x_{2}) < 0$ ，存在 $c \in (a, b)$ ，使得 $f(c) = 0$

由罗尔定理，存在 $\xi_1\in (a,c),\xi_2\in (c,b)$ ，使得 $f^{\prime}(\xi_{1}) = f^{\prime}(\xi_{2}) = 0$

再由罗尔定理，存在 $\xi \in (\xi_1, \xi_2) \subset (a, b)$ ，使得 $f''(\xi) = 0$

(20)【解】（I）令 $y(x) = \sum_{n=0}^{\infty} a_n x^n$ ，则

$$
y ^ {\prime} (x) = \sum_ {n = 1} ^ {\infty} n a _ {n} x ^ {n - 1},
$$

$$
y ^ {\prime \prime} (x) = \sum_ {n = 2} ^ {\infty} n (n - 1) a _ {n} x ^ {n - 2} = \sum_ {n = 0} ^ {\infty} (n + 1) (n + 2) a _ {n + 2} x ^ {n},
$$

由 $y(0) = 0, y'(0) = 1$ 得 $a_0 = 0, a_1 = 1$

于是 $y^{\prime \prime} - 2xy^{\prime} - 4y = \sum_{n = 0}^{\infty}(n + 1)(n + 2)a_{n + 2}x^{n} - 2\sum_{n = 1}^{\infty}na_{n}x^{n} - 4\sum_{n = 0}^{\infty}a_{n}x^{n}$

$$
\begin{array}{l} = \sum_ {n = 0} ^ {\infty} (n + 1) (n + 2) a _ {n + 2} x ^ {n} - 2 \sum_ {n = 0} ^ {\infty} n a _ {n} x ^ {n} - 4 \sum_ {n = 0} ^ {\infty} a _ {n} x ^ {n} \\ = \sum_ {n = 0} ^ {\infty} [ (n + 1) (n + 2) a _ {n + 2} - 2 (n + 2) a _ {n} ] x ^ {n}. \\ \end{array}
$$

因为 $y(x) = \sum_{n=0}^{\infty} a_n x^n$ 满足微分方程 $y'' - 2xy' - 4y = 0$

所以 $(n + 1)(n + 2)a_{n + 2} - 2(n + 2)a_n = 0$

故 $a_{n + 2} = \frac{2}{n + 1} a_n (n = 0,1,2,\dots)$

（Ⅱ）由 $a_0 = 0$ 及 $a_{n + 2} = \frac{2}{n + 1} a_n(n = 0,1,2,\dots)$ 得 $a_{2k} = 0(k = 1,2,\dots)$

由 $a_{1} = 1$ 及归纳法得 $a_{2n + 1} = \frac{1}{n!} (n = 0,1,2,\dots)$

故 $y(x) = \sum_{n=0}^{\infty} \frac{x^{2n+1}}{n!} = x \sum_{n=0}^{\infty} \frac{(x^2)^n}{n!} = x \mathrm{e}^{x^2}$ .

(21)【解】 令

$$
\left\{ \begin{array}{l} x _ {1} + x _ {2} + x _ {3} = 0, \\ x _ {1} + 2 x _ {2} + a x _ {3} = 0, \\ x _ {1} + 4 x _ {2} + a ^ {2} x _ {3} = 0, \\ x _ {1} + 2 x _ {2} + x _ {3} = a - 1. \end{array} \right. \tag {③}
$$

方程组 ①、② 有公共解的充分必要条件是方程组 ③ 有解.

$$
\overline {{\boldsymbol {C}}} = \left(\begin{array}{l l l l}1&1&1&0\\1&2&a&0\\1&4&a ^ {2}&0\\1&2&1&a - 1\end{array}\right)\rightarrow \left(\begin{array}{l l l l}1&1&1&0\\0&1&a - 1&0\\0&3&a ^ {2} - 1&0\\0&1&0&a - 1\end{array}\right)\rightarrow \left(\begin{array}{l l l l}1&1&1&0\\0&1&a - 1&0\\0&0&(a - 1) (a - 2)&0\\0&0&1 - a&a - 1\end{array}\right),
$$

当 $a = 1$ 时，方程组 ③ 为齐次线性方程组，两个方程组一定有公共解，

由 $\pmb{C} = \begin{bmatrix} 1 & 1 & 1\\ 1 & 2 & 1\\ 1 & 4 & 1\\ 1 & 2 & 1 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 1 & 1\\ 0 & 1 & 0\\ 0 & 3 & 0\\ 0 & 0 & 0 \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 0 & 1\\ 0 & 1 & 0\\ 0 & 0 & 0\\ 0 & 0 & 0 \end{bmatrix}$ 得

两方程组的公共解为 $X = C\left( \begin{array}{c} - 1\\ 0\\ 1 \end{array} \right)$ （ $C$ 为任意常数）；

当 $a \neq 1$ 时，

$$
\overline {{C}} \rightarrow \left(\begin{array}{c c c c}1&1&1&0\\0&1&a - 1&0\\0&0&a - 2&0\\0&0&1&- 1\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&0\\0&1&a - 1&0\\0&0&1&- 1\\0&0&0&a - 2\end{array}\right),
$$

情形一：当 $a \neq 2$ 时，因为 $r(\mathbf{C}) \neq r(\overline{\mathbf{C}})$ ，所以两个方程组没有公共解；  
情形二：当 $a = 2$ 时，由 $r(\mathbf{C}) = r(\overline{\mathbf{C}}) = 3$ 得两个方程组有唯一的公共解

由 $\overline{\pmb{C}}\rightarrow \begin{bmatrix} 1 & 1 & 1 & 0\\ 0 & 1 & 1 & 0\\ 0 & 0 & 1 & -1\\ 0 & 0 & 0 & 0 \end{bmatrix}\rightarrow \begin{bmatrix} 1 & 0 & 0 & 0\\ 0 & 1 & 0 & 1\\ 0 & 0 & 1 & -1\\ 0 & 0 & 0 & 0 \end{bmatrix}$ 得唯一公共解为 $X = \left( \begin{array}{c}0\\ 1\\ -1 \end{array} \right)$

（22）【解】（I）由 $A\pmb{\alpha}_{1} = \pmb{\alpha}_{1}$ ，得

$$
\boldsymbol {B} \boldsymbol {\alpha} _ {1} = (\boldsymbol {A} ^ {5} - 4 \boldsymbol {A} ^ {3} + \boldsymbol {E}) \boldsymbol {\alpha} _ {1} = \boldsymbol {A} ^ {5} \boldsymbol {\alpha} _ {1} - 4 \boldsymbol {A} ^ {3} \boldsymbol {\alpha} _ {1} + \boldsymbol {\alpha} _ {1} = (1 - 4 + 1) \boldsymbol {\alpha} _ {1} = - 2 \boldsymbol {\alpha} _ {1},
$$

则 $\pmb{\alpha}_{1}$ 为矩阵 $\pmb{B}$ 的属于特征值 $\mu_{1} = -2$ 的特征向量

$\pmb{B}$ 的其他两个特征值为 $\mu_{2} = \lambda_{2}^{5} - 4\lambda_{2}^{3} + 1 = 1, \mu_{3} = \lambda_{3}^{5} - 4\lambda_{3}^{3} + 1 = 1$ ，即 $\mu_{2} = \mu_{3} = 1$ 。因为 $\pmb{A}$ 为实对称矩阵，所以 $\pmb{B}$ 为实对称矩阵，不妨设 $\pmb{B}$ 的属于特征值 $\mu_{2} = \mu_{3} = 1$ 的特征向量为 $\pmb{\alpha} = (x_{1}, x_{2}, x_{3})^{\mathrm{T}}$ 。

因为实对称矩阵不同特征值对应的特征向量正交，所以 $\pmb{\alpha}_{1}^{\mathrm{T}}\pmb{\alpha} = 0$ ，即 $x_{1} - x_{2} + x_{3} = 0$ ，于是 $\pmb{B}$ 的属于特征值 $\mu_{2} = \mu_{3} = 1$ 的线性无关的特征向量为 $\pmb{\alpha}_{2} = \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix}, \pmb{\alpha}_{3} = \begin{pmatrix} -1 \\ 0 \\ 1 \end{pmatrix}$ ，

故 $\pmb{B}$ 的属于特征值 $\mu_{1} = -2$ 的全部特征向量为 $k_{1}\alpha_{1}(k_{1}$ 为任意的非零常数），

$\pmb{B}$ 的属于特征值 $\mu_{2} = \mu_{3} = 1$ 的全部特征向量为 $k_{2}\pmb{\alpha}_{2} + k_{3}\pmb{\alpha}_{3}(k_{2},k_{3}$ 为任意的不全为零的常数).

（Ⅱ）方法一 令 $\pmb{\beta}_{1} = \pmb{\alpha}_{1} = \begin{pmatrix} 1 \\ -1 \\ 1 \end{pmatrix}$ ， $\pmb{\beta}_{2} = \begin{pmatrix} 1 \\ 1 \\ 0 \end{pmatrix}$ ， $\pmb{\beta}_{3} = \pmb{\alpha}_{3} - \frac{(\pmb{\alpha}_{3}, \pmb{\beta}_{2})}{(\pmb{\beta}_{2}, \pmb{\beta}_{2})} \pmb{\beta}_{2} = \frac{1}{2} \begin{pmatrix} -1 \\ 1 \\ 2 \end{pmatrix}$ ，

单位化得 $\gamma_{1} = \frac{1}{\sqrt{3}}\binom{1}{-1}$ ， $\gamma_{2} = \frac{1}{\sqrt{2}}\binom{1}{0}$ ， $\gamma_{3} = \frac{1}{\sqrt{6}}\binom{-1}{2}$ ，

令 $\pmb{P} = \left[ \begin{array}{ccc}\frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}} & -\frac{1}{\sqrt{6}}\\ -\frac{1}{\sqrt{3}} & \frac{1}{\sqrt{2}} & \frac{1}{\sqrt{6}}\\ \frac{1}{\sqrt{3}} & 0 & \frac{2}{\sqrt{6}} \end{array} \right],$ 则 $\pmb {P}^{\mathrm{T}}\pmb {B}\pmb {P} = \left( \begin{array}{rrr} - 2 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right),$

于是 $\pmb {B} = \pmb{P}\left( \begin{array}{lll} - 2 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right)\pmb{P}^{\mathrm{T}} = \left( \begin{array}{lll}0 & 1 & -1\\ 1 & 0 & 1\\ -1 & 1 & 0 \end{array} \right).$

方法二 令 $\pmb{P} = (\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}) = \begin{pmatrix} 1 & 1 & -1\\ -1 & 1 & 0\\ 1 & 0 & 1 \end{pmatrix}$

由 $\pmb{P}^{-1}\pmb {B}\pmb {P} = \left( \begin{array}{rrr} - 2 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right)$ ，得 $\pmb {B} = \pmb {P}\left( \begin{array}{rrr} - 2 & 0 & 0\\ 0 & 1 & 0\\ 0 & 0 & 1 \end{array} \right)\pmb{P}^{-1} = \left( \begin{array}{rrr}0 & 1 & -1\\ 1 & 0 & 1\\ -1 & 1 & 0 \end{array} \right).$

(23)【解】（I） $P\{X > 2Y\} = \iint_{x > 2y} f(x, y) \, \mathrm{d}x \, \mathrm{d}y = \int_{0}^{1} \mathrm{d}x \int_{0}^{\frac{x}{2}} (2 - x - y) \, \mathrm{d}y = \frac{7}{24}$ .

$(\mathrm{II})F_{Z}(z) = P\{Z\leqslant z\} = P\{X + Y\leqslant z\} = \iint \limits_{x + y\leqslant z}f(x,y)\mathrm{d}x\mathrm{d}y,$

当 $z < 0$ 时， $F_{Z}(z) = 0$

当 $0 \leqslant z < 1$ 时， $F_Z(z) = \int_0^z \mathrm{d}x \int_0^{z - x} (2 - x - y) \, \mathrm{d}y = z^2 - \frac{1}{3} z^3$ ;

当 $1 \leqslant z < 2$ 时， $F_{Z}(z) = 1 - \int_{z-1}^{1} \mathrm{d}x \int_{z-x}^{1} (2 - x - y) \mathrm{d}y = 1 - \frac{1}{3} (2 - z)^{3}$ ;

当 $z \geq 2$ 时， $F_{Z}(z) = 1$

于是 $f_{Z}(z) = \left\{ \begin{array}{ll}2z - z^{2}, & 0 <   z <   1,\\ z^{2} - 4z + 4, & 1\leqslant z <   2,\\ 0, & \text{其他}. \end{array} \right.$

(24)【解】（I） $E(X) = \int_{0}^{\theta} x \cdot \frac{1}{2\theta} \, \mathrm{d}x + \int_{\theta}^{1} x \cdot \frac{1}{2(1 - \theta)} \, \mathrm{d}x = \frac{\theta}{4} + \frac{1 + \theta}{4} = \frac{\theta}{2} + \frac{1}{4},$

令 $E(X) = \overline{X}$ ，得 $\theta$ 的矩估计量为 $\hat{\theta} = 2\overline{X} - \frac{1}{2}$ .

（Ⅱ）方法一 $E(4\overline{X}^2) = 4E(\overline{X}^2) = 4\{D(\overline{X}) + [E(\overline{X})]^2\}$

因为 $E(X^2) = \int_0^\theta x^2\cdot \frac{1}{2\theta}\mathrm{d}x + \int_\theta^1 x^2\cdot \frac{1}{2(1 - \theta)}\mathrm{d}x = \frac{\theta^2}{6} +\frac{1 + \theta + \theta^2}{6} = \frac{\theta^2}{3} +\frac{\theta}{6} +\frac{1}{6},$

所以 $D(X) = E(X^2) - [E(X)]^2 = \frac{\theta^2}{12} -\frac{\theta}{12} +\frac{5}{48},$

从而 $E(\overline{X}) = E(X) = \frac{\theta}{2} +\frac{1}{4},D(\overline{X}) = \frac{D(X)}{n} = \frac{1}{n}\Big(\frac{\theta^2}{12} -\frac{\theta}{12} +\frac{5}{48}\Big),$

于是 $E(4\overline{X}^2) = \frac{3n + 1}{3n}\theta^2 +\frac{3n - 1}{3n}\theta +\frac{3n + 5}{12n}\neq \theta^2$ ，故 $4\overline{X}^2$ 不是 $\theta^2$ 的无偏估计量.

方法二

$$
\begin{array}{l} E \left(4 \bar {X} ^ {2}\right) = 4 E (\bar {X} ^ {2}) = 4 D (\bar {X}) + 4 [ E (\bar {X}) ] ^ {2} \\ = \frac {4}{n} D (X) + 4 [ E (X) ] ^ {2} \\ = 4 \left[ \frac {1}{4} (2 \theta + 1) \right] ^ {2} + \frac {4}{n} D (X) \\ = \theta^ {2} + \theta + \frac {1}{4} + \frac {4}{n} D (X) > \theta^ {2}, \\ \end{array}
$$

故 $4\overline{X}^2$ 不是 $\theta^2$ 的无偏估计量.