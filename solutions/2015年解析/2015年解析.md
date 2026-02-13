# 2015年数学(一）真题解析

# 一、选择题

(1)【答案】 (C).

【解】设 $f^{\prime \prime}(x) = 0$ 左边的零点为 $x = a$ ，右边的零点为 $x = b$

又在 $x = 0$ 处 $f''(x)$ 不存在.

因为 $x = a$ 的左、右两侧 $f''(x)$ 都大于零，所以 $(a, f(a))$ 不是拐点；

因为 $x = 0$ 左、右两侧 $f''(x)$ 异号，所以 $(0, f(0))$ 为拐点；

因为 $x = b$ 左、右两侧 $f''(x)$ 异号，所以 $(b, f(b))$ 为拐点，

故 $y = f(x)$ 有两个拐点，应选(C).

方法点评：本题考查拐点的判别法. 判断曲线的拐点时，首先找出二阶导数为零的点及二阶不可导的点，其次判断该点两侧二阶导数的符号情况，若该点两侧二阶导数异号，则曲线上对应的点为拐点.

(2)【答案】 (A).

【解】因为 $y = \frac{1}{2}\mathrm{e}^{2x} + \left(x - \frac{1}{3}\right)\mathrm{e}^x$ 为 $y'' + ay' + by = ce^x$ 的特解，

所以 $y^{\prime \prime} + ay^{\prime} + by = 0$ 的特征方程的特征值为 $\lambda_1 = 1, \lambda_2 = 2$ ，则 $a = -3, b = 2$ .

显然 $y = x \mathrm{e}^{x}$ 为原方程的特解，将 $y = x \mathrm{e}^{x}$ 代入原方程得 $c = -1$ ，应选(A).

（3）【答案】 （B）.

【解】 因为 $\sum_{n=1}^{\infty} a_{n}$ 条件收敛，所以 $\sum_{n=1}^{\infty} a_{n} x^{n}$ 的收敛半径为 1，

$\sum_{n=1}^{\infty} a_n (x - 1)^n$ 的收敛区间为 $-1 < x - 1 < 1$ ，即 $0 < x < 2$

因为 $\sqrt{3} - 1 \in (-1, 1)$ , $3 - 1 \notin [-1, 1]$ ,

所以级数 $\sum_{n=1}^{\infty} a_n (x - 1)^n$ 在 $x = \sqrt{3}$ 处绝对收敛，在 $x = 3$ 处发散，

因为 $\sum_{n=1}^{\infty} n a_n (x - 1)^n$ 与 $\sum_{n=1}^{\infty} a_n (x - 1)^n$ 收敛半径相同、收敛区间相同，

所以 $\sum_{n=1}^{\infty} n a_n (x - 1)^n$ 在 $x = \sqrt{3}$ 处绝对收敛，在 $x = 3$ 处发散，应选(B).

（4）【答案】 （B）.

【解】 令 $\left\{ \begin{array}{l}x = r\cos \theta ,\\ y = r\sin \theta , \end{array} \right.\left(\frac{\pi}{4}\leqslant \theta \leqslant \frac{\pi}{3},\frac{1}{\sqrt{2\sin 2\theta}}\leqslant r\leqslant \frac{1}{\sqrt{\sin 2\theta}}\right)$ ，则

$\iint_{D} f(x, y) \mathrm{d}x \mathrm{~d}y = \int_{\frac{\pi}{4}}^{\frac{\pi}{3}} \mathrm{d}\theta \int_{\frac{1}{\sqrt{2\sin 2\theta}}}^{\frac{1}{\sqrt{\sin 2\theta}}} f(r \cos \theta, r \sin \theta) r \mathrm{d}r$ ，应选（B）.

(5)【答案】 (D).

【解】 因为 $AX = b$ 有无数个解，所以 $r(A) = r(\overline{A}) < 3$

由 $|\mathbf{A}| = (a - 1)(a - 2) = 0$ 得 $a = 1, a = 2$

当 $a = 1$ 时，

$$
\overline {{A}} = \left(\begin{array}{c c c c}1&1&1&1\\1&2&1&d\\1&4&1&d ^ {2}\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&0&d - 1\\0&3&0&d ^ {2} - 1\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&0&d - 1\\0&0&0&d ^ {2} - 3 d + 2\end{array}\right),
$$

因为方程组有无数个解，所以 $d = 1$ 或 $d = 2$

当 $a = 2$ 时，

$$
\overline {{A}} = \left(\begin{array}{c c c c}1&1&1&1\\1&2&2&d\\1&4&4&d ^ {2}\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&1&d - 1\\0&3&3&d ^ {2} - 1\end{array}\right)\rightarrow \left(\begin{array}{c c c c}1&1&1&1\\0&1&1&d - 1\\0&0&0&d ^ {2} - 3 d + 2\end{array}\right),
$$

因为方程组有无数个解，所以 $d = 1$ 或 $d = 2$ ，应选(D).

方法点评：本题考查非齐次线性方程组的基本理论. 本题非齐次线性方程组有无数个解的两个关键点为： $r(\mathbf{A}) < 3$ 及 $r(\mathbf{A}) = r(\overline{\mathbf{A}})$

（6）【答案】 （A）.

【解】因为 $f(x_{1},x_{2},x_{3})$ 经过正交变换 $\mathbf{X} = \mathbf{P}\mathbf{Y}$ 化为标准形 $2y_{1}^{2} + y_{2}^{2} - y_{3}^{2}$

所以 $\mathbf{A}$ 的特征值为 $\lambda_1 = 2, \lambda_2 = 1, \lambda_3 = -1$ ，其对应的特征向量为 $e_1, e_2, e_3$

因为 $e_1, - e_3,e_2$ 为特征值2，一1，1对应的特征向量，

所以 $X = QY$ 下二次型的标准形为 $2y_{1}^{2} - y_{2}^{2} + y_{3}^{2}$ ，应选(A).

方法点评：本题考查实对称矩阵对角化及二次型理论

二次型标准化有配方法和正交变换法，配方法化二次型为标准形时，其系数不一定为矩阵的特征值；正交变换法化二次型为标准形时，其系数一定为特征值，注意特征向量与特征值的次序要保持一致.

（7）【答案】 (C).

【解】 $P(A + B) = P(A) + P(B) - P(AB)$

因为 $P(A + B) \geqslant P(AB)$ ，所以 $P(A) + P(B) - P(AB) \geqslant P(AB)$

故 $P(AB) \leqslant \frac{P(A) + P(B)}{2}$ , 应选(C).

(8)【答案】 (D).

【解】由 $X, Y$ 不相关得 $\operatorname{Cov}(X, Y) = 0$ ，从而 $E(XY) = E(X)E(Y)$

$$
\begin{array}{l} E [ X (X + Y - 2) ] = E \left(X ^ {2}\right) + E (X Y) - 2 E (X) \\ = D (X) + \left[ E (X) \right] ^ {2} + E (X) E (Y) - 2 E (X) = 3 + 4 + 2 - 4 = 5, \\ \end{array}
$$

应选(D).

# 二、填空题

(9)【答案】 $-\frac{1}{2}$ .

【解】方法一 $\lim_{x\to 0}\frac{\ln(\cos x)}{x^2} = \lim_{x\to 0}\frac{\ln[1 + (\cos x - 1)]}{x^2} = \lim_{x\to 0}\frac{\cos x - 1}{x^2} = -\frac{1}{2}.$

方法二 $\lim_{x\to 0}\frac{\ln(\cos x)}{x^2} = \lim_{x\to 0}\frac{-\frac{\sin x}{\cos x}}{2x} = -\frac{1}{2}\lim_{x\to 0}\frac{\sin x}{x}\cdot \frac{1}{\cos x} = -\frac{1}{2}.$

（10）【答案】 $\frac{\pi^2}{4}$

【解】 $\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\left(\frac{\sin x}{1 + \cos x} + |x|\right) \mathrm{d}x = \int_{-\frac{\pi}{2}}^{\frac{\pi}{2}} |x| \mathrm{d}x = 2\int_{0}^{\frac{\pi}{2}} x \mathrm{d}x = \frac{\pi^2}{4}$ .

方法点评：本题考查定积分的奇偶性质，即

$\int_{-a}^{a}f(x)\mathrm{d}x = \int_{0}^{a}\left[f(x) + f(-x)\right]\mathrm{d}x$ ，特别地，

当 $f(-x) = f(x)$ 时， $\int_{-a}^{a}f(x)\mathrm{d}x = 2\int_{0}^{a}f(x)\mathrm{d}x;$

当 $f(-x) = -f(x)$ 时， $\int_{-a}^{a}f(x)\mathrm{d}x = 0.$

(11)【答案】 $-\mathrm{d}x$

【解】方法一 将 $x = 0, y = 1$ 代入 $\mathrm{e}^z + xyz + x + \cos x = 2$ 中，得 $z = 0, \mathrm{e}^z + xyz + x + \cos x = 2$ 两边分别对 $x, y$ 求偏导得

$$
\mathrm {e} ^ {z} \cdot \frac {\partial z}{\partial x} + y (z + x \frac {\partial z}{\partial x}) + 1 - \sin x = 0, \quad \mathrm {e} ^ {z} \cdot \frac {\partial z}{\partial y} + x (z + y \frac {\partial z}{\partial y}) = 0,
$$

代入得 $\left.\frac{\partial z}{\partial x}\right|_{(0,1)} = -1,\left.\frac{\partial z}{\partial y}\right|_{(0,1)} = 0,$

故 $\mathrm{d}z\Big|_{(0,1)} = \frac{\partial z}{\partial x}\Big|_{(0,1)}\mathrm{d}x + \frac{\partial z}{\partial y}\Big|_{(0,1)}\mathrm{d}y = -\mathrm{d}x.$

方法二 将 $x = 0, y = 1$ 代入 $\mathrm{e}^z + xyz + x + \cos x = 2$ 中得 $z = 0$ .

$\mathrm{e}^z + xyz + x + \cos x = 2$ 两边求全微分得

$$
\mathrm {e} ^ {z} \mathrm {d} z + y z \mathrm {d} x + x z \mathrm {d} y + x y \mathrm {d} z + \mathrm {d} x - \sin x \mathrm {d} x = 0,
$$

将 $x = 0, y = 1, z = 0$ 代入得 $\mathrm{d}z|_{(0,1)} = -\mathrm{d}x$

(12)【答案】 $\frac{1}{4}$ .

【解】 方法一 由对称性得

$$
\begin{array}{l} \iiint_ {\Omega} (x + 2 y + 3 z) \mathrm {d} v = 6 \iiint_ {\Omega} z \mathrm {d} v \\ = 6 \int_ {0} ^ {1} \mathrm {d} x \int_ {0} ^ {1 - x} \mathrm {d} y \int_ {0} ^ {1 - x - y} z \mathrm {d} z = 3 \int_ {0} ^ {1} \mathrm {d} x \int_ {0} ^ {1 - x} (1 - x - y) ^ {2} \mathrm {d} y \\ = \int_ {0} ^ {1} (1 - x) ^ {3} d x = - \frac {(1 - x) ^ {4}}{4} \Big | _ {0} ^ {1} = \frac {1}{4}. \\ \end{array}
$$

方法二 $\Omega = \{(x,y,z) \mid (x,y) \in D, 0 \leqslant z \leqslant 1 - x - y\}$ ,

其中 $D = \{(x,y)\mid 0\leqslant x\leqslant 1,0\leqslant y\leqslant 1 - x\}$ ，则

$$
\begin{array}{l} \iiint_ {\Omega} (x + 2 y + 3 z) \mathrm {d} v = \iint_ {D} \mathrm {d} x \mathrm {d} y \int_ {0} ^ {1 - x - y} (x + 2 y + 3 z) \mathrm {d} z \\ = \iint_ {D} \left[ (x + 2 y) (1 - x - y) + \frac {3}{2} (1 - x - y) ^ {2} \right] d x d y \\ = \int_ {0} ^ {1} \mathrm {d} x \int_ {0} ^ {1 - x} \left[ (x + 2 y) (1 - x - y) + \frac {3}{2} (1 - x - y) ^ {2} \right] \mathrm {d} y = \frac {1}{4}. \\ \end{array}
$$

(13)【答案】 $2^{n + 1} - 2$

【解】 $D_{n} = \left| \begin{array}{ccccc}2 & 0 & \dots & 0 & 2\\ -1 & 2 & \dots & 0 & 2\\ \vdots & \vdots & & \vdots & \vdots \\ 0 & 0 & \dots & 2 & 2\\ 0 & 0 & \dots & -1 & 2 \end{array} \right| = 2D_{n - 1} + 2\times A_{1n}$

$$
\begin{array}{l} = 2 D _ {n - 1} + 2 \times (- 1) ^ {n + 1} \times (- 1) ^ {n - 1} = 2 D _ {n - 1} + 2 \\ = 2 \left(2 D _ {n - 2} + 2\right) + 2 = 2 ^ {2} D _ {n - 2} + 2 ^ {2} + 2 \\ = \dots = 2 ^ {n} + \dots + 2 ^ {2} + 2 = \frac {2 (1 - 2 ^ {n})}{1 - 2} = 2 ^ {n + 1} - 2. \\ \end{array}
$$

(14)【答案】 $\frac{1}{2}$ .

【解】因为 $\rho = 0$ ，所以 $X,Y$ 独立且不相关，且 $X\sim N(1,1),Y\sim N(0,1)$

$$
\begin{array}{l} P \{X Y - Y <   0 \} = P \{(X - 1) Y <   0 \} \\ = P \{X <   1 \} P \{Y > 0 \} + P \{X > 1 \} P \{Y <   0 \} \\ = \frac {1}{2} (P \{X <   1 \} + P \{X > 1 \}) = \frac {1}{2}. \\ \end{array}
$$

方法点评：本题考查二维正态分布的性质.设 $(X,Y)$ 服从二维正态分布，则 $X,Y$ 独立与 $X,Y$ 不相关等价.

# 三、解答题

(15)【解】方法一 由 $\ln (1 + x) = x - \frac{x^2}{2} + \frac{x^3}{3} + o(x^3)$ , $\sin x = x - \frac{x^3}{6} + o(x^3)$ 得

$$
f (x) = x + a x - \frac {a x ^ {2}}{2} + \frac {a x ^ {3}}{3} + b x ^ {2} + o (x ^ {3}) = (1 + a) x + \left(b - \frac {a}{2}\right) x ^ {2} + \frac {a}{3} x ^ {3} + o (x ^ {3}),
$$

因为 $f(x)\sim g(x)$

所以 $1 + a = 0, b - \frac{a}{2} = 0, \frac{a}{3} = k$ ，解得 $a = -1, b = -\frac{1}{2}, k = -\frac{1}{3}$

方法二 由 $1 = \lim_{x\to 0}\frac{f(x)}{g(x)} = \lim_{x\to 0}\frac{x + a\ln(1 + x) + bx\sin x}{kx^3}$

$$
= \lim  _ {x \rightarrow 0} \frac {1 + \frac {a}{1 + x} + b \sin x + b x \cos x}{3 k x ^ {2}}, \text {得} a = - 1,
$$

再由 $1 = \lim_{x\to 0}\frac{1 - \frac{1}{1 + x} + b\sin{x} + bx\cos{x}}{3kx^2} = \lim_{x\to 0}\frac{\frac{x}{1 + x} + b\sin{x} + bx\cos{x}}{3kx^2}$   
$\lim_{x \to 0} \frac{\frac{1}{(1 + x)^2} + 2b\cos x - bx\sin x}{6kx}$ , 得 $b = -\frac{1}{2}$

再由 $1 = \lim_{x\to 0}\frac{\frac{1}{(1 + x)^2} - \cos{x} + \frac{1}{2}x\sin{x}}{6kx} = \lim_{x\to 0}\frac{\frac{1}{(1 + x)^2} - \cos{x}}{6kx}$

$$
= \lim  _ {x \to 0} - \frac {- \frac {2}{(1 + x) ^ {3}} + \sin x}{6 k} = - \frac {1}{3 k}, \text {得} k = - \frac {1}{3}.
$$

（16）【解】 $y = f(x)$ 在点 $(x_0, f(x_0))$ 处的切线方程为

$$
y - f \left(x _ {0}\right) = f ^ {\prime} \left(x _ {0}\right) \left(x - x _ {0}\right),
$$

令 $y = 0$ ，则 $x = x_0 - \frac{f(x_0)}{f'(x_0)}$

切线、 $x = x_{0}$ 及 $x$ 轴所围成区域的面积为

$$
S = \frac {1}{2} f (x _ {0}) \left[ x _ {0} - \left(x _ {0} - \frac {f (x _ {0})}{f ^ {\prime} (x _ {0})}\right) \right] = 4,
$$

即 $\frac{1}{2} y^2 = 4y'$ ，变量分离得 $\frac{8\mathrm{d}y}{y^2} = \mathrm{d}x$ ，积分得 $-\frac{8}{y} = x + C$

因为 $y(0) = 2$ ，所以 $C = -4$ ，故所求的曲线为 $y = \frac{8}{4 - x}$

(17)【解】 $f_{x}^{\prime}(x,y) = 1 + y$ ， $f_{y}^{\prime} = 1 + x$

$f(x,y)$ 在点 $(x,y)$ 的方向导数取的最大值的方向即梯度的方向，且最大值即梯度的模，则最大值为 $g(x,y) = |\mathbf{grad}f(x,y)| = \sqrt{(x + 1)^2 + (y + 1)^2}$ .

令 $F = (x + 1)^2 +(y + 1)^2 +\lambda (x^2 +y^2 +xy - 3)$

由 $\begin{cases} F_{x}^{\prime} = 2(x + 1) + 2\lambda x + \lambda y = 0 \\ F_{y}^{\prime} = 2(y + 1) + 2\lambda y + \lambda x = 0 \\ F_{\lambda}^{\prime} = x^{2} + y^{2} + xy - 3 = 0 \end{cases}$ 解得

$$
\left\{ \begin{array}{l} x = 1, \left\{ \begin{array}{l} x = - 1, \\ y = 1, \end{array} \right. \left\{ \begin{array}{l} x = - 1, \\ y = - 1, \end{array} \right. \left\{ \begin{array}{l} x = - 1, \\ y = - 1, \end{array} \right. \right.
$$

由 $g(1,1) = \sqrt{8}, g(-1, - 1) = 0,g(2, - 1) = \sqrt{9} = 3,g(-1,2) = \sqrt{9} = 3$ 得方向导数的最大值为3.

方法点评：本题考查方向导数与梯度的关系，

方向导数为 $\frac{\partial f}{\partial l} = \frac{\partial f}{\partial x} \cdot \cos \alpha + \frac{\partial f}{\partial y} \cdot \cos \beta = \left\{\frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}\right\} \cdot \{\cos \alpha, \cos \beta\}$ ,

其中 $\left\{\frac{\partial f}{\partial x}, \frac{\partial f}{\partial y}\right\} = \mathbf{grad} f, \{\cos \alpha, \cos \beta\} = e$ 为与射线 $l$ 方向相同的单位向量，

设梯度grad $f$ 与 $\pmb{e}$ 的夹角为 $\theta$ ，则

$$
\frac {\partial f}{\partial l} = | \mathbf {g r a d} f | \cdot | e | \cdot \cos \theta = \sqrt {\left(\frac {\partial f}{\partial x}\right) ^ {2} + \left(\frac {\partial f}{\partial y}\right) ^ {2}} \cdot \cos \theta ,
$$

当 $\cos \theta = 1$ ，即 $\theta = 0$ 或 $\mathbf{grad}f$ 与 $\pmb{e}$ 同向时，方向导数达到最大值.

故梯度的方向即为方向导数取最大值的方向，且方向导数的最大值为梯度的模。

（18）【证明】（I）令 $f(x) = u(x)v(x)$

$$
\begin{array}{l} \Delta f = u (x + \Delta x) v (x + \Delta x) - u (x) v (x) \\ = u (x + \Delta x) v (x + \Delta x) - u (x) v (x + \Delta x) + u (x) v (x + \Delta x) - u (x) v (x) \\ = [ u (x + \Delta x) - u (x) ] v (x + \Delta x) + u (x) [ v (x + \Delta x) - v (x) ] \\ = \Delta u v (x + \Delta x) + u (x) \Delta v, \\ \end{array}
$$

则 $\left[u(x)v(x)\right]' = \lim_{\Delta x\to 0}\frac{\Delta f}{\Delta x}$

$$
\begin{array}{l} = \lim  _ {\Delta x \rightarrow 0} \frac {\Delta u}{\Delta x} v (x + \Delta x) + \lim  _ {\Delta x \rightarrow 0} u (x) \frac {\Delta v}{\Delta x} \\ = u ^ {\prime} (x) v (x) + u (x) v ^ {\prime} (x). \\ \end{array}
$$

$(\mathrm{II})f^{\prime}(x) = u_{1}^{\prime}(x)u_{2}(x)\dots u_{n}(x) + u_{1}(x)u_{2}^{\prime}(x)\dots u_{n}(x) + \dots +u_{1}(x)u_{2}(x)\dots u_{n}^{\prime}(x).$

（19）【解】 $L$ 的参数方程为 $L:\left\{ \begin{array}{l}x = \cos t,\\ y = \sqrt{2}\sin t,\\ z = \cos t, \end{array} \right.$ 其中起点 $t = \frac{\pi}{2}$ 终点 $t = -\frac{\pi}{2}$ 则

$$
\begin{array}{l} I = \int_ {\frac {\pi}{2}} ^ {- \frac {\pi}{2}} (\sqrt {2} \sin t + \cos t) (- \sin t) d t + \sqrt {2} \sin t \cdot \sqrt {2} \cos t d t + 2 \sin^ {2} t \cos^ {2} t (- \sin t) d t \\ = 2 \sqrt {2} \int_ {0} ^ {\frac {\pi}{2}} \sin^ {2} t \mathrm {d} t = 2 \sqrt {2} \times \frac {1}{2} \times \frac {\pi}{2} = \frac {\sqrt {2}}{2} \pi . \\ \end{array}
$$

(20)【解】 $(\mathrm{I})(\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}) = (\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3})\left( \begin{array}{ccc}2 & 0 & 1\\ 0 & 2 & 0\\ 2k & 0 & k + 1 \end{array} \right),$

因为 $\left| \begin{array}{ccc}2 & 0 & 1\\ 0 & 2 & 0\\ 2k & 0 & k + 1 \end{array} \right| = 4\neq 0$ ，所以 $r(\pmb {\beta}_1,\pmb {\beta}_2,\pmb {\beta}_3) = r(\pmb {\alpha}_1,\pmb {\alpha}_2,\pmb {\alpha}_3) = 3$

即 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}$ 线性无关，所以 $\pmb{\beta}_{1},\pmb{\beta}_{2},\pmb{\beta}_{3}$ 为 $\mathbf{R}^3$ 的一组基

（Ⅱ）令 $\xi$ 在两组基下的坐标都是 $(x_{1}, x_{2}, x_{3})$

由 $x_{1}\pmb{\alpha}_{1} + x_{2}\pmb{\alpha}_{2} + x_{3}\pmb{\alpha}_{3} = x_{1}\pmb{\beta}_{1} + x_{2}\pmb{\beta}_{2} + x_{3}\pmb{\beta}_{3}$ ，或

$x_{1}(\pmb{\beta}_{1} - \pmb{\alpha}_{1}) + x_{2}(\pmb{\beta}_{2} - \pmb{\alpha}_{2}) + x_{3}(\pmb{\beta}_{3} - \pmb{\alpha}_{3}) = 0$ ，整理得

$$
x _ {1} \left(\boldsymbol {\alpha} _ {1} + 2 k \boldsymbol {\alpha} _ {3}\right) + x _ {2} \boldsymbol {\alpha} _ {2} + x _ {3} \left(\boldsymbol {\alpha} _ {1} + k \boldsymbol {\alpha} _ {3}\right) = \mathbf {0},
$$

因为 $\xi$ 为非零向量，所以 $x_{1}(\alpha_{1} + 2k\alpha_{3}) + x_{2}\alpha_{2} + x_{3}(\alpha_{1} + k\alpha_{3}) = 0$ 有非零解，从而 $|\alpha_{1} + 2k\alpha_{3},\alpha_{2},\alpha_{1} + k\alpha_{3}| = 0$

而 $|\pmb{\alpha}_{1} + 2k\pmb{\alpha}_{3}, \pmb{\alpha}_{2}, \pmb{\alpha}_{1} + k\pmb{\alpha}_{3}| = |\pmb{\alpha}_{1}, \pmb{\alpha}_{2}, \pmb{\alpha}_{3}| \cdot \left| \begin{array}{ccc} 1 & 0 & 1 \\ 0 & 1 & 0 \\ 2k & 0 & k \end{array} \right|$ 且 $|\pmb{\alpha}_{1}, \pmb{\alpha}_{2}, \pmb{\alpha}_{3}| \neq 0$

则 $\left| \begin{array}{lll}1 & 0 & 1\\ 0 & 1 & 0\\ 2k & 0 & k \end{array} \right| = 0$ ，故 $k = 0$

当 $k = 0$ 时，由 $x_{1}(\alpha_{1} + 2k\alpha_{3}) + x_{2}\alpha_{2} + x_{3}(\alpha_{1} + k\alpha_{3}) = 0,$

即 $\pmb{\alpha}_{1}x_{1} + \pmb{\alpha}_{2}x_{2} + \pmb{\alpha}_{3}x_{3} = 0$ ，或 $(\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3})\left( \begin{array}{lll}1 & 0 & 1\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)\left( \begin{array}{l}x_{1}\\ x_{2}\\ x_{3} \end{array} \right) = \mathbf{0}$

因为 $\alpha_{1},\alpha_{2},\alpha_{3}$ 为一个基，所以 $(\pmb {\alpha}_1,\pmb {\alpha}_2,\pmb {\alpha}_3)$ 可逆，

于是 $\left( \begin{array}{lll}1 & 0 & 1\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right)\left( \begin{array}{l}x_{1}\\ x_{2}\\ x_{3} \end{array} \right) = 0$ ，故 $\xi$ 在基 $\alpha_{1},\alpha_{2},\alpha_{3}$ 或 $\beta_{1},\beta_{2},\beta_{3}$ 下坐标为

$$
\binom {x _ {1}} {x _ {2}} = C \binom {- 1} {0} (C \text {为 任 意 常 数}).
$$

方法点评：本题考查向量空间的理论.

向量空间理论是数学一的专门考查内容，包括：

向量空间的概念、基、过渡矩阵、向量在基下的坐标.

（21）【解】（I）因为 $A\sim B$ ，所以 $\left\{ \begin{array}{l}\operatorname {tr}A = \operatorname {tr}B,\\ |\boldsymbol {A}| = |\boldsymbol {B}|, \end{array} \right.$

从而 $\left\{ \begin{array}{l}a + 3 = b + 2,\\ 2a - 3 = b, \end{array} \right.$ 解得 $a = 4,b = 5$

（Ⅱ）因为 $A\sim B$ ，所以 $A,B$ 的特征值相同，

由 $|\lambda \pmb {E} - \pmb {B}| = \left| \begin{array}{ccc}\lambda -1 & 2 & 0\\ 0 & \lambda -5 & 0\\ 0 & -3 & \lambda -1 \end{array} \right| = (\lambda -1)^{2}(\lambda -5) = 0$ 得

$\mathbf{A}, \mathbf{B}$ 的特征值为 $\lambda_{1} = \lambda_{2} = 1, \lambda_{3} = 5$

将 $\lambda = 1$ 代入 $(\lambda E - A)X = 0$ ，即 $(E - A)X = 0$

由 $\pmb {E} - \pmb {A} = \left( \begin{array}{rrr}1 & -2 & 3\\ 1 & -2 & 3\\ -1 & 2 & -3 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & -2 & 3\\ 0 & 0 & 0\\ 0 & 0 & 0 \end{array} \right)$ 得

A的属于特征值 $\lambda = 1$ 的线性无关的特征向量为 $\pmb{\alpha}_{1} = \begin{pmatrix} 2\\ 1\\ 0 \end{pmatrix},\pmb{\alpha}_{2} = \begin{pmatrix} -3\\ 0\\ 1 \end{pmatrix}$

将 $\lambda = 5$ 代入 $(\lambda E - A)X = 0$ ，即 $(5E - A)X = 0$

由 $5\pmb {E} - \pmb {A} = \left( \begin{array}{rrr}5 & -2 & 3\\ 1 & 2 & 3\\ -1 & 2 & 1 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & -2 & -1\\ 1 & 2 & 3\\ 5 & -2 & 3 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & -2 & -1\\ 0 & 4 & 4\\ 0 & 8 & 8 \end{array} \right)\rightarrow \left( \begin{array}{rrr}1 & 0 & 1\\ 0 & 1 & 1\\ 0 & 0 & 0 \end{array} \right)$ 得

$\mathbf{A}$ 的属于特征值 $\lambda = 5$ 的特征向量为 $\pmb{\alpha}_{3} = \begin{pmatrix} -1 \\ -1 \\ 1 \end{pmatrix}$ ,

令 $\pmb{P} = \begin{pmatrix} 2 & -3 & -1 \\ 1 & 0 & -1 \\ 0 & 1 & 1 \end{pmatrix}$ , 则 $\pmb{P}^{-1}\pmb{A}\pmb{P} = \begin{pmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 5 \end{pmatrix}$ .

(22)【解】（I）令 $p = P\{X > 3\} = \int_{3}^{+\infty}2^{-x}\ln 2\mathrm{d}x = -2^{-x}\mid_{3}^{+\infty} = \frac{1}{8},$

$Y$ 的可能取值为 $2,3,\dots ,Y$ 的分布律为

$$
P \{Y = k \} = p \cdot C _ {k - 1} ^ {1} \cdot p \cdot (1 - p) ^ {k - 2} = (k - 1) p ^ {2} (1 - p) ^ {k - 2} (k = 2, 3, \dots).
$$

$(\mathrm{II})E(Y) = \sum_{k = 2}^{\infty}kP\{Y = k\} = p^{2}\sum_{k = 2}^{\infty}k(k - 1)(1 - p)^{k - 2}$

$$
= p ^ {2} \left(\sum_ {k = 2} ^ {\infty} x ^ {k}\right) ^ {\prime \prime} \Big | _ {x = \frac {7}{8}} = p ^ {2} \left(\frac {x ^ {2}}{1 - x}\right) ^ {\prime \prime} \Big | _ {x = \frac {7}{8}} = \frac {2 p ^ {2}}{(1 - x) ^ {3}} \Big | _ {x = \frac {7}{8}} = 1 6.
$$

(23)【解】 $(\mathrm{I})E(X) = \int_{\theta}^{1}\frac{x}{1 - \theta}\mathrm{d}x = \frac{1 + \theta}{2},$

令 $E(X) = \overline{X}$ ，则 $\theta$ 的矩估计量为 $\hat{\theta} = 2\overline{X} - 1$

（Ⅱ）似然函数为

$$
L (\theta) = f (x _ {1}) f (x _ {2}) \dots f (x _ {n}) = \frac {1}{(1 - \theta) ^ {n}} (\theta \leqslant x _ {i} \leqslant 1, i = 1, 2, \dots , n),
$$

因为 $\frac{\mathrm{d}}{\mathrm{d}\theta} L(\theta) = \frac{n}{(1 - \theta)^{n + 1}} >0$ ，所以 $L(\theta)$ 关于 $\theta$ 为增函数，

故 $\theta$ 的最大似然估计量为 $\hat{\theta} = \min_{1\leqslant i\leqslant n}\{X_i\}$