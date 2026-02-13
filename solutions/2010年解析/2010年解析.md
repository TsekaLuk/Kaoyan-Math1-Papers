# 2010年数学(一）真题解析

# 一、选择题

（1）【答案】 (C).

【解】 $\lim_{x\to \infty}\left[\frac{x^2}{(x - a)(x + b)}\right]^x = \lim_{x\to \infty}\left\{\left[1 + \frac{(a - b)x + ab}{(x - a)(x + b)}\right]^{\frac{(x - a)(x + b)}{(a - b)x + ab}}\right\}^{\frac{x[(a - b)x + ab]}{(x - a)(x + b)}} = \mathrm{e}^{a - b},$

应选(C).

(2)【答案】 (B).

【解】 方法一 复合函数求导法则

$F\left(\frac{y}{x}, \frac{z}{x}\right) = 0$ 两边对 $x$ 求偏导，得 $-\frac{y}{x^2} F_1' + \frac{x \frac{\partial z}{\partial x} - z}{x^2} F_2' = 0$ ，解得 $\frac{\partial z}{\partial x} = \frac{1}{x F_2'} (y F_1' + z F_2')$

$F\left(\frac{y}{x}, \frac{z}{x}\right) = 0$ 两边对 $y$ 求偏导，得 $\frac{1}{x} F_{1}' + \frac{1}{x} F_{2}' \frac{\partial z}{\partial y} = 0$ ，解得 $\frac{\partial z}{\partial y} = -\frac{F_{1}'}{F_{2}'}.$

于是 $x\frac{\partial z}{\partial x} +y\frac{\partial z}{\partial y} = \frac{1}{F_2'} (yF_1' + zF_2') - \frac{yF_1'}{F_2'} = z$ ，应选(B).

方法二 公式法

令 $G(x,y,z) = F\left(\frac{y}{x},\frac{z}{x}\right)$

由 $G_{x}^{\prime} = -\frac{y}{x^{2}} F_{1}^{\prime} - \frac{z}{x^{2}} F_{2}^{\prime}$ ， $G_{y}^{\prime} = \frac{1}{x} F_{1}^{\prime}$ ， $G_{z}^{\prime} = \frac{1}{x} F_{2}^{\prime}$ ，得

$$
\frac {\partial z}{\partial x} = - \frac {G _ {x} ^ {\prime}}{G _ {z} ^ {\prime}} = \frac {\frac {y}{x ^ {2}} F _ {1} ^ {\prime} + \frac {z}{x ^ {2}} F _ {2} ^ {\prime}}{\frac {1}{x} F _ {2} ^ {\prime}} = \frac {1}{x F _ {2} ^ {\prime}} (y F _ {1} ^ {\prime} + z F _ {2} ^ {\prime}), \quad \frac {\partial z}{\partial y} = - \frac {G _ {y} ^ {\prime}}{G _ {z} ^ {\prime}} = - \frac {\frac {1}{x} F _ {1} ^ {\prime}}{\frac {1}{x} F _ {2} ^ {\prime}} = - \frac {F _ {1} ^ {\prime}}{F _ {2} ^ {\prime}},
$$

于是 $x\frac{\partial z}{\partial x} +y\frac{\partial z}{\partial y} = \frac{1}{F_2'} (yF_1' + zF_2') - \frac{yF_1'}{F_2'} = z$ ，应选(B).

方法三 全微分法

$F\left(\frac{y}{x}, \frac{z}{x}\right) = 0$ 两边求全微分，得 $F_{1}^{\prime} \mathrm{d}\left(\frac{y}{x}\right) + F_{2}^{\prime} \mathrm{d}\left(\frac{z}{x}\right) = 0$ ，整理得

$$
F _ {1} ^ {\prime} \cdot \frac {x \mathrm {d} y - y \mathrm {d} x}{x ^ {2}} + F _ {2} ^ {\prime} \cdot \frac {x \mathrm {d} z - z \mathrm {d} x}{x ^ {2}} = 0,
$$

从而有 $\mathrm{d}z = \frac{1}{xF_2'} (yF_1' + zF_2')\mathrm{d}x - \frac{F_1'}{F_2'}\mathrm{d}y,$

于是 $\frac{\partial z}{\partial x} = \frac{1}{xF_2'} (yF_1' + zF_2')$ ， $\frac{\partial z}{\partial y} = -\frac{F_1'}{F_2'}$

故 $x\frac{\partial z}{\partial x} +y\frac{\partial z}{\partial y} = \frac{1}{F_2'} (yF_1' + zF_2') - \frac{yF_1'}{F_2'} = z$ ，应选(B).

(3)【答案】 (D).

【解】 $x = 0$ 及 $x = 1$ 为反常积分 $\int_0^1\frac{\sqrt[m]{\ln^2(1 - x)}}{\sqrt[n]{x}}\mathrm{d}x$ 的瑕点，

$$
\int_ {0} ^ {1} \frac {\sqrt [ m ]{\ln^ {2} (1 - x)}}{\sqrt [ n ]{x}} d x = \int_ {0} ^ {\frac {1}{2}} \frac {\sqrt [ m ]{\ln^ {2} (1 - x)}}{\sqrt [ n ]{x}} d x + \int_ {\frac {1}{2}} ^ {1} \frac {\sqrt [ m ]{\ln^ {2} (1 - x)}}{\sqrt [ n ]{x}} d x,
$$

因为 $\lim_{x\to 0^{+}}x^{\frac{1}{n} -\frac{2}{m}}\cdot \frac{\sqrt[m]{\ln^{2}(1 - x)}}{\sqrt[n]{x}} = 1$ 且 $\alpha = \frac{1}{n} -\frac{2}{m} <  1$ ，所以 $\int_0^{\frac{1}{2}}\frac{\sqrt[m]{\ln^2(1 - x)}}{\sqrt[n]{x}}\mathrm{d}x$ 收敛；

又因为 $\lim_{x\to 1^{-}}(1 - x)^{\frac{1}{2}}\cdot \frac{\sqrt[m]{\ln^{2}(1 - x)}}{\sqrt[n]{x}} = \lim_{x\to 1^{-}}\sqrt{1 - x}\cdot \ln^{\frac{2}{m}}(1 - x)$

$$
\underline {{\underline {{1 - x = t}}}} \lim  _ {t \rightarrow 0 ^ {+}} \frac {\ln^ {\frac {2}{m}} t}{t ^ {- \frac {1}{2}}} = \left(\lim  _ {t \rightarrow 0 ^ {+}} \frac {\ln t}{t ^ {- \frac {m}{4}}}\right) ^ {\frac {2}{m}} = \left(- \frac {4}{m} \lim  _ {t \rightarrow 0 ^ {+}} \frac {\frac {1}{t}}{t ^ {- \frac {m}{4} - 1}}\right) ^ {\frac {2}{m}} = 0
$$

且 $\alpha = \frac{1}{2} < 1$ ，所以 $\int_{\frac{1}{2}}^{1}\frac{\sqrt[m]{\ln^2(1 - x)}}{\sqrt[n]{x}}\mathrm{d}x$ 收敛，故 $\int_0^1\frac{\sqrt[m]{\ln^2(1 - x)}}{\sqrt[n]{x}}\mathrm{d}x$ 收敛，应选(D).

方法点评：对积分区间有限但函数有无穷间断点的反常积分的敛散性判断通常有定义法和判别法.

（1）设 $f(x)\in C(a,b]$ ，且 $f(x)$ 在 $x = a$ 的右邻域内无界.

定义法：对任意的 $\varepsilon >0$ ，若 $\lim_{\varepsilon \to 0^{+}}\int_{a + \varepsilon}^{b}f(x)\mathrm{d}x$ 存在，则称反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 收敛，否则称为发散.

判别法：设 $\lim_{x\to a^{+}}(x - a)^{k}f(x) = A(\neq \infty)$ ，则当 $0 < k < 1, 0 \leqslant A < +\infty$ 时，反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 收敛；当 $k \geqslant 1, 0 < A \leqslant +\infty$ 时，反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 发散.

（2）设 $f(x)\in C[a,b)$ ，且 $f(x)$ 在 $x = b$ 的左邻域内无界.

定义法：对任意的 $\varepsilon >0$ ，若 $\lim_{\varepsilon \to 0^{+}}\int_{a}^{b - \varepsilon}f(x)\mathrm{d}x$ 存在，则称反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 收敛，否则称为发散.

判别法：设 $\lim_{x\to b^{-}}(b - x)^{k}f(x) = A(\neq \infty)$ ，则当 $0 < k < 1, 0 \leqslant A < +\infty$ 时，反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 收敛；当 $k \geqslant 1, 0 < A \leqslant +\infty$ 时，反常积分 $\int_{a}^{b}f(x)\mathrm{d}x$ 发散.

（4）【答案】 (D).

【解】取 $D = \{(x,y) \mid 0 \leqslant x \leqslant 1, 0 \leqslant y \leqslant 1\}$ , $f(x,y) = \frac{1}{(1 + x)(1 + y^2)}$

由 $\sum_{i=1}^{n}\sum_{j=1}^{n}\frac{n}{(n+i)(n^2+j^2)}=\frac{1}{n^2}\sum_{i=1}^{n}\sum_{j=1}^{n}\frac{1}{\left(1+\frac{i}{n}\right)\left[1+\left(\frac{j}{n}\right)^2\right]}$ , 根据二重积分的定义, 得

$$
\lim  _ {n \rightarrow \infty} \sum_ {i = 1} ^ {n} \sum_ {j = 1} ^ {n} \frac {n}{(n + i) (n ^ {2} + j ^ {2})} = \iint_ {D} f (x, y) d x d y = \int_ {0} ^ {1} d x \int_ {0} ^ {1} \frac {1}{(1 + x) (1 + y ^ {2})} d y,
$$

应选(D).

方法点评：用定积分、重积分等的定义求极限是极限计算的一种重要类型，重点考查定积分定义求极限.

（1）定积分的定义求极限： $\lim_{n\to \infty}\frac{1}{n}\sum_{i = 1}^{n}f\left(\frac{i}{n}\right) = \int_{0}^{1}f(x)\mathrm{d}x.$

【例】 求极限 $\lim_{n\to \infty}\left(\frac{1}{1 + \sqrt{n^2 - 1^2}} +\frac{1}{2 + \sqrt{n^2 - 2^2}} +\dots +\frac{1}{n + \sqrt{n^2 - n^2}}\right)$

【解】 $\lim_{n\to \infty}\left(\frac{1}{1 + \sqrt{n^2 - 1^2}} +\frac{1}{2 + \sqrt{n^2 - 2^2}} +\dots +\frac{1}{n + \sqrt{n^2 - n^2}}\right)$

$$
\begin{array}{l} = \lim  _ {n \rightarrow \infty} \frac {1}{n} \left[ \frac {1}{\frac {1}{n} + \sqrt {1 - \left(\frac {1}{n}\right) ^ {2}}} + \frac {1}{\frac {2}{n} + \sqrt {1 - \left(\frac {2}{n}\right) ^ {2}}} + \dots + \frac {1}{\frac {n}{n} + \sqrt {1 - \left(\frac {n}{n}\right) ^ {2}}} \right] \\ = \lim  _ {n \rightarrow \infty} \frac {1}{n} \sum_ {i = 1} ^ {n} \frac {1}{\frac {i}{n} + \sqrt {1 - \left(\frac {i}{n}\right) ^ {2}}} = \int_ {0} ^ {1} \frac {1}{x + \sqrt {1 - x ^ {2}}} d x \frac {x = \sin t}{\sin t + \cos t} \int_ {0} ^ {\frac {\pi}{2}} \frac {\cos t}{\sin t + \cos t} d t \\ = \int_ {0} ^ {\frac {\pi}{2}} \frac {\cos x}{\sin x + \cos x} d x \xlongequal {x + t = \frac {\pi}{2}} \int_ {0} ^ {\frac {\pi}{2}} \frac {\sin t}{\sin t + \cos t} d t = \int_ {0} ^ {\frac {\pi}{2}} \frac {\sin x}{\sin x + \cos x} d x, \\ \end{array}
$$

于是原式 $= \frac{1}{2}\left(\int_{0}^{\frac{\pi}{2}}\frac{\sin x}{\sin x + \cos x}\mathrm{d}x + \int_{0}^{\frac{\pi}{2}}\frac{\cos x}{\sin x + \cos x}\mathrm{d}x\right) = \frac{\pi}{4}.$

(2) 二重积分的定义求极限: $\lim_{\substack{m \to \infty \\ n \to \infty}} \frac{1}{mn} \sum_{i=1}^{m} \sum_{j=1}^{n} f\left(\frac{i}{m}, \frac{j}{n}\right) = \iint_{D} f(x, y) \, \mathrm{d}x \, \mathrm{d}y,$

其中 $D = \{(x,y)\mid 0\leqslant x\leqslant 1,0\leqslant y\leqslant 1\}$

（5）【答案】 （A）.

【解】 $r(\mathbf{AB}) = r(\mathbf{E}) = m$

因为 $r(\mathbf{AB}) \leqslant r(\mathbf{A})$ 且 $r(\mathbf{AB}) \leqslant r(\mathbf{B})$ ，所以 $r(\mathbf{A}) \geqslant m, r(\mathbf{B}) \geqslant m$ .

又显然 $r(\mathbf{A})\leqslant m,r(\mathbf{B})\leqslant m$ ，故 $r(A) = r(B) = m$ ，应选（A）.

方法点评：本题使用矩阵秩的两个性质：

(1) $r(\mathbf{AB}) \leqslant \min \{r(\mathbf{A}), r(\mathbf{B})\}$ , 研究矩阵秩的时候, 如果出现矩阵的积, 使用此性质;  
（2）设 $\mathbf{A}$ 为 $m\times n$ 矩阵，则 $r(A)\leqslant \min \{m,n\}$

（6）【答案】 (D).

【解】令 $AX = \lambda X(X\neq 0)$ ，由 $(A^2 +A)X = (\lambda^2 +\lambda)X = 0$ 且 $X\neq 0$ 得 $\lambda^2 +\lambda = 0$ ，于是 $\lambda = 0$ 或 $\lambda = -1.$ 因为 $\mathbf{A}$ 可对角化且 $r(A) = 3$ ，所以 $\lambda = -1$ 为三重特征值，

故 $\mathbf{A}\sim \left( \begin{array}{rrr} - 1 & & \\ & -1 & \\ & & -1 \end{array} \right),$ 应选(D).

（7）【答案】 (C).

【解】 $P\{X = 1\} = P\{X \leqslant 1\} - P\{X < 1\} = F(1) - F(1 - 0) = 1 - \mathrm{e}^{-1} - \frac{1}{2} = \frac{1}{2} - \mathrm{e}^{-1},$

应选(C).

方法点评：本题需要熟练掌握随机变量分布函数的性质，

设 $X$ 为随机变量， $F(x)$ 具有如下四个特征：

(1) $0 \leqslant F(x) \leqslant 1$   
(2) $F(x)$ 单调不减；  
(3) $F(x)$ 右连续；  
(4) $F(-\infty) = 0$ ， $F(+\infty) = 1$

反之，若 $F(x)$ 具有 $(1) \sim (4)$ 的特征，则 $F(x)$ 为分布函数.

另外，若 $F(x)$ 为分布函数，则

(1) $P\{X < a\} = F(a - 0)$   
(2) $P\{X = a\} = P\{X \leqslant a\} - \{X < a\} = F(a) - F(a - 0)$ ;   
(3) $P\{a < X \leqslant b\} = P\{X \leqslant b\} - P\{X \leqslant a\} = F(b) - F(a)$ ;   
(4) $P\{a < X < b\} = P\{X < b\} - P\{X \leqslant a\} = F(b - 0) - F(a)$ .

（8）【答案】 （A）.

【解】 $f_{1}(x) = \frac{1}{\sqrt{2\pi}}\mathrm{e}^{-\frac{x^{2}}{2}}(-\infty < x < + \infty),\quad f_{2}(x) = \left\{ \begin{array}{ll}\frac{1}{4}, & -1\leqslant x\leqslant 3,\\ 0, & \text{其他}. \end{array} \right.$

因为 $f(x)$ 为概率密度函数，所以 $\int_{-\infty}^{+\infty} f(x) \, \mathrm{d}x = 1$

而 $\int_{-\infty}^{+\infty}f(x)\mathrm{d}x = a\int_{-\infty}^{0}f_{1}(x)\mathrm{d}x + b\int_{0}^{+\infty}f_{2}(x)\mathrm{d}x = \frac{a}{2} +b\int_{0}^{3}\frac{1}{4}\mathrm{d}x = \frac{a}{2} +\frac{3}{4} b,$

所以 $\frac{a}{2} +\frac{3}{4} b = 1$ ，即 $2a + 3b = 4$ ，应选（A）.

# 二、填空题

（9）【答案】0.

【解】 $\frac{\mathrm{dy}}{\mathrm{dx}} = \frac{\mathrm{dy} / \mathrm{dt}}{\mathrm{dx} / \mathrm{dt}} = -\mathrm{e}^{t}\ln (1 + t^{2}),$

$$
\begin{array}{l} \frac {\mathrm {d} ^ {2} y}{\mathrm {d} x ^ {2}} = \frac {\mathrm {d} \left(\frac {\mathrm {d} y}{\mathrm {d} x}\right) / \mathrm {d} t}{\mathrm {d} x / \mathrm {d} t} = - \left[ \mathrm {e} ^ {t} \ln (1 + t ^ {2}) + \mathrm {e} ^ {t} \frac {2 t}{1 + t ^ {2}} \right] \cdot (- \mathrm {e} ^ {t}) \\ = \mathrm {e} ^ {2 t} \left[ \ln (1 + t ^ {2}) + \frac {2 t}{1 + t ^ {2}} \right], \\ \end{array}
$$

于是 $\left.\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\right|_{t = 0} = 0.$

（10）【答案】 $-4\pi$

【解】 $\int_0^{\pi^2}\sqrt{x}\cos \sqrt{x}\mathrm{d}x\stackrel {x = t^2}{= 2\int_0^\pi t^2\cos t\mathrm{d}t} = 2\int_0^\pi t^2\mathrm{d}(\sin t)$

$$
\begin{array}{l} = 2 t ^ {2} \sin t \left| _ {0} ^ {\pi} - 4 \int_ {0} ^ {\pi} t \sin t d t = - 4 \int_ {0} ^ {\pi} t \sin t d t \right. \\ = - 2 \pi \int_ {0} ^ {\pi} \sin t d t = - 4 \pi \int_ {0} ^ {\frac {\pi}{2}} \sin t d t = - 4 \pi . \\ \end{array}
$$

方法点评：本题考查定积分计算的方法和性质，

定积分计算主要使用两大工具，即定积分的性质及积分法。本题使用三角函数定积分性质，三角函数定积分的性质总结如下：

(1) $\int_{0}^{\frac{\pi}{2}} f(\sin x) \, \mathrm{d}x = \int_{0}^{\frac{\pi}{2}} f(\cos x) \, \mathrm{d}x$ ，特别地，

$$
I _ {n} = \int_ {0} ^ {\frac {\pi}{2}} \sin^ {n} x \mathrm {d} x = \int_ {0} ^ {\frac {\pi}{2}} \cos^ {n} x \mathrm {d} x  , \text {且}   I _ {n} = \frac {n - 1}{n} I _ {n - 2}  , I _ {0} = \frac {\pi}{2}  , I _ {1} = 1.
$$

(2) $\int_{0}^{\pi} f(\sin x) \, \mathrm{d}x = 2\int_{0}^{\frac{\pi}{2}} f(\sin x) \, \mathrm{d}x$ ，或 $\int_{0}^{\frac{\pi}{2}} f(\sin x) \, \mathrm{d}x = \int_{\frac{\pi}{2}}^{\pi} f(\sin x) \, \mathrm{d}x$ .  
(3) $\int_{0}^{\pi} f(|\cos x|) \mathrm{d}x = 2 \int_{0}^{\frac{\pi}{2}} f(\cos x) \mathrm{d}x.$   
(4) $\int_{0}^{\pi} x f(\sin x) \, \mathrm{d}x = \frac{\pi}{2} \int_{0}^{\pi} f(\sin x) \, \mathrm{d}x.$

（11）【答案】0.

【解】方法一 补充 $L_{1}:y = 0$ （起点 $(1,0)$ ，终点 $(-1,0))$ ，由格林公式

$$
\int_ {L} x y \mathrm {d} x + x ^ {2} \mathrm {d} y = \oint_ {L + L _ {1}} x y \mathrm {d} x + x ^ {2} \mathrm {d} y - \int_ {L _ {1}} x y \mathrm {d} x + x ^ {2} \mathrm {d} y,
$$

而 $\oint_{L + L_1}xy\mathrm{d}x + x^2\mathrm{d}y = \iint_Dx\mathrm{d}x\mathrm{d}y = \int_0^1\mathrm{d}y\int_{y - 1}^{1 - y}x\mathrm{d}x = 0,$

$$
\int_ {L _ {1}} x y \mathrm {d} x + x ^ {2} \mathrm {d} y = \int_ {L _ {1}} x y \mathrm {d} x = 0,
$$

所以原式 $= 0$

方法二 $\int_{L} xy \, \mathrm{d}x + x^2 \, \mathrm{d}y = \int_{-1}^{0} [x(1 + x) + x^2] \, \mathrm{d}x + \int_{0}^{1} [x(1 - x) - x^2] \, \mathrm{d}x = 0.$

(12)【答案】 $\frac{2}{3}$ .

【解】 方法一 $\overline{z} = \frac{\iiint_{\Omega} z \mathrm{d}v}{\iiint_{\Omega} \mathrm{d}v}$ ，而 $\iiint_{\Omega} z \mathrm{d}v = \int_{0}^{1} z \mathrm{d}z \iint_{x^2 + y^2 \leqslant z} \mathrm{d}x \mathrm{d}y = \pi \int_{0}^{1} z^2 \mathrm{d}z = \frac{\pi}{3}$

$$
\iiint_ {\Omega} \mathrm {d} v = \int_ {0} ^ {1} \mathrm {d} z \iint_ {x ^ {2} + y ^ {2} \leqslant z} \mathrm {d} x \mathrm {d} y = \pi \int_ {0} ^ {1} z \mathrm {d} z = \frac {\pi}{2}, \text {所 以} \overline {{z}} = \frac {2}{3}.
$$

方法二 $\overline{z} = \frac{\iiint_{\Omega} z \mathrm{~d} v}{\iiint_{\Omega} \mathrm{~d} v}$ ,

由 $\Omega = \{(x,y,z)\mid (x,y)\in D_{xy},x^2 +y^2\leqslant z\leqslant 1\}$ ，其中 $D_{xy} = \{(x,y)|x^2 +y^2\leqslant 1\}$ 得

$$
\begin{array}{l} \iiint_ {\Omega} \mathrm {d} v = \iint_ {D _ {x y}} \mathrm {d} x \mathrm {d} y \int_ {x ^ {2} + y ^ {2}} ^ {1} \mathrm {d} z = \iint_ {D _ {x y}} (1 - x ^ {2} - y ^ {2}) \mathrm {d} x \mathrm {d} y \\ = \int_ {0} ^ {2 \pi} d \theta \int_ {0} ^ {1} r (1 - r ^ {2}) d r = 2 \pi \int_ {0} ^ {1} (r - r ^ {3}) d r = 2 \pi \left(\frac {1}{2} - \frac {1}{4}\right) = \frac {\pi}{2}; \\ \end{array}
$$

$$
\begin{array}{l} \iiint_ {\Omega} z \mathrm {d} v = \iint_ {D _ {x y}} \mathrm {d} x \mathrm {d} y \int_ {x ^ {2} + y ^ {2}} ^ {1} z \mathrm {d} z = \frac {1}{2} \iint_ {D _ {x y}} [ 1 - (x ^ {2} + y ^ {2}) ^ {2} ] \mathrm {d} x \mathrm {d} y \\ = \frac {1}{2} \int_ {0} ^ {2 \pi} \mathrm {d} \theta \int_ {0} ^ {1} r (1 - r ^ {4}) \mathrm {d} r = \pi \int_ {0} ^ {1} (r - r ^ {5}) \mathrm {d} r = \pi \left(\frac {1}{2} - \frac {1}{6}\right) = \frac {\pi}{3}, \\ \end{array}
$$

故 $\overline{z} = \frac{2}{3}$

方法点评：形心的计算是重积分及线和面积分的物理应用之一.

（1）设 $D$ 为平面有限区域，其面密度为 $\rho (x,y)$ ，则

$$
\bar {x} = \frac {\iint_ {D} x \rho (x , y) \mathrm {d} \sigma}{\iint_ {D} \rho (x , y) \mathrm {d} \sigma}, \quad \bar {y} = \frac {\iint_ {D} y \rho (x , y) \mathrm {d} \sigma}{\iint_ {D} \rho (x , y) \mathrm {d} \sigma}.
$$

（2）设 $\Omega$ 为空间有限区域，其体密度为 $\rho (x,y,z)$ ，则

$$
\bar {x} = \frac {\iiint_ {\Omega} x \rho (x , y , z) \mathrm {d} v}{\iiint_ {\Omega} \rho (x , y , z) \mathrm {d} v}, \quad \bar {y} = \frac {\iiint_ {\Omega} y \rho (x , y , z) \mathrm {d} v}{\iiint_ {\Omega} \rho (x , y , z) \mathrm {d} v}, \quad \bar {z} = \frac {\iiint_ {\Omega} z \rho (x , y , z) \mathrm {d} v}{\iiint_ {\Omega} \rho (x , y , z) \mathrm {d} v}.
$$

（3）设 $L$ 为平面有限曲线段，其线密度为 $\rho (x,y)$ ，则

$$
\bar {x} = \frac {\int_ {L} x \rho (x , y) \mathrm {d} s}{\int_ {L} \rho (x , y) \mathrm {d} s}, \quad \bar {y} = \frac {\int_ {L} y \rho (x , y) \mathrm {d} s}{\int_ {L} \rho (x , y) \mathrm {d} s}.
$$

（4）设 $\Sigma$ 为空间有限曲面，其面密度为 $\rho (x,y,z)$ ，则

$$
\bar {x} = \frac {\iint_ {\Sigma} x \rho (x , y , z) \mathrm {d} S}{\iint_ {\Sigma} \rho (x , y , z) \mathrm {d} S}, \quad \bar {y} = \frac {\iint_ {\Sigma} y \rho (x , y , z) \mathrm {d} S}{\iint_ {\Sigma} \rho (x , y , z) \mathrm {d} S}, \quad \bar {z} = \frac {\iint_ {\Sigma} z \rho (x , y , z) \mathrm {d} S}{\iint_ {\Sigma} \rho (x , y , z) \mathrm {d} S}.
$$

（13）【答案】 6.

【解】 $(\pmb{\alpha}_{1},\pmb{\alpha}_{2},\pmb{\alpha}_{3}) = \begin{bmatrix} 1 & 1 & 2\\ 2 & 1 & 1\\ -1 & 0 & 1\\ 0 & 2 & a \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 1 & 2\\ 0 & -1 & -3\\ 0 & 1 & 3\\ 0 & 2 & a \end{bmatrix} \rightarrow \begin{bmatrix} 1 & 1 & 2\\ 0 & 1 & 3\\ 0 & 0 & 0\\ 0 & 0 & a - 6 \end{bmatrix}$

因为由 $\alpha_{1},\alpha_{2},\alpha_{3}$ 组成的向量组的秩为2，所以 $a = 6$

方法点评：向量组的秩与向量组所构成的矩阵的秩相等，因为向量组 $\alpha_{1},\alpha_{2},\alpha_{3}$ 的秩为2，所以其构成的矩阵的秩为2，经过初等行变换阶梯化后应为2个非零行，故可求出 $a$

（14）【答案】2.

【解】方法一 由概率的归一性得 $1 = \sum_{k=0}^{\infty} \frac{C}{k!} = C \sum_{k=0}^{\infty} \frac{1}{k!} = C \mathrm{e}$ , 则 $C = \frac{1}{\mathrm{e}}$

由 $P\{X = k\} = \frac{1}{k!}\mathrm{e}^{-1}(k = 0,1,2,\dots)$ 得 $X\sim P(1)$

于是 $E(X) = D(X) = 1$ ，故 $E(X^2) = D(X) + (EX)^2 = 2.$

方法二 由 $\sum_{k=0}^{\infty} \frac{C}{k!} = C \sum_{k=0}^{\infty} \frac{1}{k!} = C \mathrm{e} = 1$ 得 $C = \frac{1}{\mathrm{e}}$

则 $E(X^{2}) = \frac{1}{\mathrm{e}}\sum_{k = 0}^{\infty}\frac{k^{2}}{k!} = \frac{1}{\mathrm{e}}\sum_{k = 1}^{\infty}\frac{k^{2}}{k!} = \frac{1}{\mathrm{e}}\sum_{k = 1}^{\infty}\frac{k}{(k - 1)!} = \frac{1}{\mathrm{e}}\sum_{k = 1}^{\infty}\frac{(k - 1) + 1}{(k - 1)!}$

$$
\begin{array}{l} = \frac {1}{\mathrm {e}} \sum_ {k = 1} ^ {\infty} \frac {k - 1}{(k - 1) !} + \frac {1}{\mathrm {e}} \sum_ {k = 1} ^ {\infty} \frac {1}{(k - 1) !} = \frac {1}{\mathrm {e}} \sum_ {k = 2} ^ {\infty} \frac {1}{(k - 2) !} + \frac {1}{\mathrm {e}} \sum_ {k = 1} ^ {\infty} \frac {1}{(k - 1) !} \\ = 2. \\ \end{array}
$$

方法点评：随机变量的分布中若含有待定参数，则可以利用概率的归一性求出参数值.

# 三、解答题

(15)【解】 微分方程 $y^{\prime \prime} - 3y^{\prime} + 2y = 0$ 的特征方程为 $\lambda^2 - 3\lambda + 2 = 0$

特征值为 $\lambda_{1} = 1, \lambda_{2} = 2$ ，则方程 $y^{\prime \prime} - 3y^{\prime} + 2y = 0$ 的通解为 $y = C_1\mathrm{e}^x +C_2\mathrm{e}^{2x}$

令原方程的特解为 $y_0(x) = x(ax + b)\mathrm{e}^x = (ax^2 +bx)\mathrm{e}^x$ ，代入原方程得 $a = -1,b = -2$ 于是原方程的通解为 $y = C_{1}\mathrm{e}^{x} + C_{2}\mathrm{e}^{2x} - (x^{2} + 2x)\mathrm{e}^{x}(C_{1},C_{2}$ 为任意常数).

方法点评：求解二阶非齐次线性微分方程是常考的考点. 求解过程分两步：

第一步，求齐次线性微分方程的特征值，并求出齐次线性微分方程的通解；

第二步，按 $f(x)$ 的具体形式假设特解，代入原方程求出原方程的特解，齐次线性微分方程的通解与非齐次线性微分方程的特解之和即非齐次线性微分方程的通解.

(16)【解】 $f(x) = \int_{1}^{x^2}(x^2 - t)\mathrm{e}^{-t^2}\mathrm{d}t = x^2\int_{1}^{x^2}\mathrm{e}^{-t^2}\mathrm{d}t - \int_{1}^{x^2}t\mathrm{e}^{-t^2}\mathrm{d}t,$

令 $f^{\prime}(x) = 2x\int_{1}^{x^{2}}\mathrm{e}^{-t^{2}}\mathrm{d}t = 0$ ，得 $x = -1,x = 0,x = 1.$

$f^{\prime \prime}(x) = 2\int_{1}^{x^{2}}\mathrm{e}^{-t^{2}}\mathrm{d}t + 4x^{2}\mathrm{e}^{-x^{4}}$ ，因为 $f''(\pm 1) = \frac{4}{\mathrm{e}} >0,f''(0) = -2\int_0^1\mathrm{e}^{-t^2}\mathrm{d}t <   0$ ，所以 $x = -1,x = 1$ 为 $f(x)$ 的极小值点，极小值为 $f(\pm 1) = 0,x = 0$ 为 $f(x)$ 的极大值点，极大值为 $f(0) = \int_0^1 te^{-t^2}\mathrm{d}t = \frac{1}{2}\left(1 - \frac{1}{\mathrm{e}}\right).$

$f(x)$ 在 $(- \infty, -1]$ 及 $[0, 1]$ 上单调减少， $f(x)$ 在 $[-1, 0]$ 及 $[1, +\infty)$ 上单调增加.

方法点评：一元函数的单调性与极值是同一个问题的两个方面.

求一元函数的极值步骤为：

（1）求函数的定义域；  
（2）求函数的驻点及不可导点；  
（3）运用第一充分条件或第二充分条件判断所找到的点是否为极值点.

（17）【解】（I）因为当 $0 \leqslant t \leqslant 1$ 时， $\ln (1 + t) \leqslant t$

所以 $\left|\ln t\right|\left[\ln (1 + t)\right]^n\leqslant t^n\left|\ln t\right|$ ，于是 $\int_0^1 |\ln t|[\ln (1 + t)]^n\mathrm{d}t\leqslant \int_0^1 t^n |\ln t|\mathrm{d}t.$

（Ⅱ）因为 $0 \leqslant \int_{0}^{1} |\ln t| [\ln (1 + t)]^{n} \mathrm{d}t \leqslant \int_{0}^{1} t^{n} |\ln t| \mathrm{d}t$

而 $\int_0^1 t^n |\ln t|\mathrm{d}t = -\frac{1}{n + 1}\int_0^1\ln t\mathrm{d}(t^{n + 1}) = -\frac{1}{n + 1}\left[t^{n + 1}\ln t\Big|_0^1 -\int_0^1 t^n\mathrm{d}t\right]$

$$
= - \frac {1}{n + 1} t ^ {n + 1} \ln t \left| _ {0} ^ {1} + \frac {1}{(n + 1) ^ {2}}, \right.
$$

因为 $\lim_{t\to 0^{+}}t^{n + 1}\ln t = \lim_{t\to 0^{+}}\frac{\ln t}{\frac{1}{t^{n + 1}}} = \lim_{t\to 0^{+}}\frac{\frac{1}{t}}{-\frac{n + 1}{t^{n + 2}}} = -\frac{1}{n + 1}\lim_{t\to 0^{+}}t^{n + 1} = 0,$

所以 $\int_0^1 t^n |\ln t|\mathrm{d}t = \frac{1}{(n + 1)^2}$ ，从而 $0\leqslant \int_0^1 |\ln t|[\ln (1 + t)]^n\mathrm{d}t\leqslant \frac{1}{(n + 1)^2},$

由迫敛定理得 $\lim_{n\to \infty}\int_{0}^{1}|\ln t|[\ln (1 + t)]^{n}\mathrm{d}t = 0.$

(18)【解】 由 $\lim_{n\to \infty}\left|\frac{u_{n + 1}}{u_n}\right| = 1$ ，得幂级数 $\sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1} x^{2n}$ 的收敛半径为 $R = 1$

当 $x = \pm 1$ 时， $\sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1} x^{2n} = \sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1}$ ，由交错级数审敛法得 $\sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1}$ 收敛，故幂级数 $\sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1} x^{2n}$ 的收敛域为[一1,1].

令 $\sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1} x^{2n} = S(x)$

则 $S(x) = \sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{2n-1} x^{2n} = x \sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{2n-1} x^{2n-1} = x S_1(x)$ ,

其中 $S_{1}(x) = \sum_{n = 1}^{\infty}\frac{(-1)^{n - 1}}{2n - 1} x^{2n - 1}.$

而 $S_{1}^{\prime}(x) = \sum_{n = 1}^{\infty}(-1)^{n - 1}x^{2n - 2} = \frac{1}{1 + x^{2}},\quad S_{1}(0) = 0,$

所以 $S_{1}(x) = \int_{0}^{x} S_{1}'(x) \mathrm{d}x = \arctan x$ ，故 $S(x) = \sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{2n-1} x^{2n} = x S_{1}(x) = x \arctan x$ .

(19)【解】令 $P$ 的坐标为 $(x, y, z)$ ，由 $S: x^2 + y^2 + z^2 - yz - 1 = 0$ ，得 $S$ 在点 $P$ 处切平面的法向量为 $\pmb{n} = \{2x, 2y - z, 2z - y\}$ .

因为 $S$ 在点 $P$ 处的切平面与 $xOy$ 平面垂直，所以有 $y = 2z$ ，注意到 $P\in S$

所以 $P$ 点的轨迹方程为 $C: \left\{ \begin{array}{l} x^2 + y^2 + z^2 - yz = 1, \\ y = 2z. \end{array} \right.$

$$
I = \iint_ {\Sigma} \frac {(x + \sqrt {3}) | y - 2 z |}{\sqrt {4 + y ^ {2} + z ^ {2} - 4 y z}} d S = \iint_ {\Sigma} \frac {(x + \sqrt {3}) (2 z - y)}{\sqrt {4 + y ^ {2} + z ^ {2} - 4 y z}} d S,
$$

将 $S$ 向 $xOy$ 平面投影，得投影区域为 $D_{xy}$ ： $x^{2} + \frac{y^2}{4}\leq 1,$

$x^{2} + y^{2} + z^{2} - yz - 1 = 0$ 两边对 $x$ 求导，得 $2x + 2z\frac{\partial z}{\partial x} -y\frac{\partial z}{\partial x} = 0$ ，解得 $\frac{\partial z}{\partial x} = \frac{2x}{y - 2z}$

$x^{2} + y^{2} + z^{2} - yz - 1 = 0$ 两边对 $y$ 求导，得 $2y + 2z\frac{\partial z}{\partial y} -z - y\frac{\partial z}{\partial y} = 0$ ，解得 $\frac{\partial z}{\partial y} = \frac{z - 2y}{2z - y}$

$$
\mathrm {d} S = \sqrt {1 + \left(\frac {\partial z}{\partial x}\right) ^ {2} + \left(\frac {\partial z}{\partial y}\right) ^ {2}} \mathrm {d} x \mathrm {d} y = \frac {1}{2 z - y} \sqrt {4 x ^ {2} + 5 y ^ {2} + 5 z ^ {2} - 8 y z} \mathrm {d} x \mathrm {d} y
$$

$$
= \frac {1}{2 z - y} \sqrt {4 + y ^ {2} + z ^ {2} - 4 y z} d x d y,
$$

于是 $I = \iint_{\Sigma} \frac{(x + \sqrt{3})|y - 2z|}{\sqrt{4 + y^2 + z^2 - 4yz}} \, \mathrm{d}S = \iint_{D_{xy}} (x + \sqrt{3}) \, \mathrm{d}x \, \mathrm{d}y$

$$
= \sqrt {3} \iint_ {D _ {x y}} \mathrm {d} x \mathrm {d} y = \sqrt {3} \times \pi \times 1 \times \frac {2}{\sqrt {3}} = 2 \pi .
$$

(20)【解】（I）因为线性方程组 $AX = b$ 存在两个不同解，所以 $r(A) < 3$ ，即 $|\mathbf{A}| = 0$ ，解得 $\lambda = -1$ 或 $\lambda = 1$

当 $\lambda = -1$ 时， $\overline{\mathbf{A}} = \left( \begin{array}{rrr} - 1 & 1 & 1 \\ 0 & -2 & 0 \\ 1 & 1 & -1 \end{array} \right) \rightarrow \left( \begin{array}{rrr} 1 & 1 & -1 \\ 0 & 2 & 0 \\ 0 & 2 & 0 \end{array} \right) \rightarrow \left( \begin{array}{rrr} 1 & 1 & -1 \\ 0 & 2 & 0 \\ 0 & 0 & 0 \end{array} \right) \rightarrow \left( \begin{array}{rrr} 1 & 1 & -1 \\ 0 & -1 & -1 \\ 0 & 0 & a + 2 \end{array} \right)$ ，

因为 $r(\mathbf{A}) = r(\overline{\mathbf{A}}) < 3$ ，所以 $a = -2$

当 $\lambda = 1$ 时， $\overline{\mathbf{A}} = \begin{pmatrix} 1 & 1 & 1 \\ 0 & 0 & 0 \\ 1 & 1 & 1 \end{pmatrix} \to \begin{pmatrix} 1 & 1 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix} \to \begin{pmatrix} 1 & 1 & 1 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}$ ，

显然 $r(\mathbf{A})\neq r(\overline{\mathbf{A}})$ ，所以 $\lambda \neq 1$ ，故 $\lambda = -1,a = -2$

（Ⅱ）由 $\overline{A}\rightarrow \left( \begin{array}{lll}1 & 1 & -1\\ 0 & 2 & 0\\ 0 & 0 & 0 \end{array} \right)\rightarrow \left[ \begin{array}{ccc}1 & 0 & -1\\ 0 & 1 & 0\\ 0 & 0 & 0 \end{array} \right]$ ，得方程组 $AX = b$ 的通解为

$\mathbf{X} = k\left( \begin{array}{l}1\\ 0\\ 1 \end{array} \right) + \left[ \begin{array}{l}\frac{3}{2}\\ -\frac{1}{2}\\ 0 \end{array} \right](k$ 为任意常数）.

(21)【解】（I）因为二次型 $f(x_{1},x_{2},x_{3}) = \mathbf{X}^{\mathrm{T}}\mathbf{A}\mathbf{X}$ 在正交变换 $\pmb {X} = \pmb {Q}\pmb{Y}$ 下的标准形为

$y_{1}^{2} + y_{2}^{2}$ ，所以 $\mathbf{A}$ 的特征值为 $\lambda_1 = \lambda_2 = 1, \lambda_3 = 0, Q$ 的第3列为 $\left(\frac{\sqrt{2}}{2}, 0, \frac{\sqrt{2}}{2}\right)^{\mathrm{T}}$ 所以 $\lambda_3 = 0$ 对应的特征向量为 $\xi_{3} = \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix}$ .

因为 $\mathbf{A}$ 为实对称矩阵，所以 $\mathbf{A}$ 的不同特征值对应的特征向量正交，令 $\lambda_{1} = \lambda_{2} = 1$ 对应的特征向量为 $\pmb {\xi} = \begin{pmatrix} x_1\\ x_2\\ x_3 \end{pmatrix}$

由 $x_{1} + x_{3} = 0$ 得 $\lambda_1 = \lambda_2 = 1$ 对应的线性无关的特征向量为 $\pmb{\xi}_{1} = \begin{pmatrix} 0\\ 1\\ 0 \end{pmatrix},\pmb{\xi}_{2} = \begin{pmatrix} -1\\ 0\\ 1 \end{pmatrix}.$

令 $\pmb{\gamma}_{1} = \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix}, \pmb{\gamma}_{2} = \frac{1}{\sqrt{2}} \begin{pmatrix} -1 \\ 0 \\ 1 \end{pmatrix}, \pmb{\gamma}_{3} = \frac{1}{\sqrt{2}} \begin{pmatrix} 1 \\ 0 \\ 1 \end{pmatrix}$ , 则 $Q = (\pmb{\gamma}_{1}, \pmb{\gamma}_{2}, \pmb{\gamma}_{3})$

由 $\pmb{Q}^{\mathrm{T}}\pmb {A}\pmb {Q} = \left( \begin{array}{lll}1 & & \\ & 1 & \\ & & 0 \end{array} \right)$ ，得 $\mathbf{A} = \left[ \begin{array}{ccc}\frac{1}{2} & 0 & -\frac{1}{2}\\ 0 & 1 & 0\\ -\frac{1}{2} & 0 & \frac{1}{2} \end{array} \right].$

（Ⅱ）因为 $\mathbf{A} + \mathbf{E} = \begin{bmatrix} \frac{3}{2} & 0 & -\frac{1}{2}\\ 0 & 2 & 0\\ -\frac{1}{2} & 0 & \frac{3}{2} \end{bmatrix}$ 是实对称矩阵，且 $\mathbf{A}$ 的特征值为 $\lambda_1 = \lambda_2 = 1,\lambda_3 = 0$

所以 $A + E$ 的特征值为 $\lambda_1 = \lambda_2 = 2, \lambda_3 = 1$ ，因为其特征值都大于零，所以 $A + E$ 为正定矩阵.

方法点评：本题需要掌握如下几个结论：

（1）二次型经过正交变换化为标准形时，其标准形的系数即特征值；  
（2）设 $\mathbf{A}$ 为实对称矩阵，存在正交矩阵 $Q$ 使得 $Q^{\mathrm{T}}AQ$ 为对角矩阵，则 $Q$ 的列为矩阵 $\mathbf{A}$ 的特征向量.  
（3）实对称矩阵不同特征值对应的特征向量正交；  
（4）由矩阵的特征值与特征向量可反推得矩阵 $\mathbf{A}$   
（5）判断实对称矩阵为正定矩阵可以通过定义法、特征值法、顺序主子式法等方法，本题通过特征值法证明矩阵正定.

(22)【解】 方法一 由归一性，得 $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}f(x,y)\mathrm{d}x\mathrm{d}y = 1,$

而 $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}f(x,y)\mathrm{d}x\mathrm{d}y = A\int_{-\infty}^{+\infty}\mathrm{d}x\int_{-\infty}^{+\infty}\mathrm{e}^{-2x^2 +2xy - y^2}\mathrm{d}y = A\int_{-\infty}^{+\infty}\mathrm{e}^{-x^2}\mathrm{d}x\int_{-\infty}^{+\infty}\mathrm{e}^{-(y - x)^2}\mathrm{d}(y - x),$

又 $\int_{-\infty}^{+\infty}\mathrm{e}^{-(y - x)^2}\mathrm{d}(y - x) = 2\int_0^{+\infty}\mathrm{e}^{-x^2}\mathrm{d}x\frac{x^2 = t}{\int_0^{+\infty}t^{-\frac{1}{2}}\mathrm{e}^{-t}\mathrm{d}t} = \Gamma \left(\frac{1}{2}\right) = \sqrt{\pi},$

所以 $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}f(x,y)\mathrm{d}x\mathrm{d}y = A\sqrt{\pi}\int_{-\infty}^{+\infty}\mathrm{e}^{-x^2}\mathrm{d}x = A\pi$ ，于是 $A = \frac{1}{\pi}$

方法二 $\int_{-\infty}^{+\infty}\int_{-\infty}^{+\infty}f(x,y)\mathrm{d}x\mathrm{d}y = A\int_{-\infty}^{+\infty}\mathrm{d}x\int_{-\infty}^{+\infty}\mathrm{e}^{-2x^2 +2xy - y^2}\mathrm{d}y = A\int_{-\infty}^{+\infty}\mathrm{e}^{-x^2}\mathrm{d}x\int_{-\infty}^{+\infty}\mathrm{e}^{-(y - x)^2}\mathrm{d}(y - x)$

$$
= A \int_ {- \infty} ^ {+ \infty} \mathrm {e} ^ {- x ^ {2}} \mathrm {d} x \int_ {- \infty} ^ {+ \infty} \mathrm {e} ^ {- y ^ {2}} \mathrm {d} y = A \iint_ {D} \mathrm {e} ^ {- x ^ {2} - y ^ {2}} \mathrm {d} x \mathrm {d} y,
$$

其中 $D$ 为 $xOy$ 平面，

而 $A\iint_{D}\mathrm{e}^{-x^2 -y^2}\mathrm{d}x\mathrm{d}y = A\int_{0}^{2\pi}\mathrm{d}\theta \int_{0}^{+\infty}r\mathrm{e}^{-r^2}\mathrm{d}r = \pi A\int_{0}^{+\infty}\mathrm{e}^{-r^2}\mathrm{d}(r^2) = \pi A\Gamma (1) = \pi A$

由归一性得 $A = \frac{1}{\pi}$

$$
f _ {Y \mid X} (y \mid x) = \frac {f (x , y)}{f _ {X} (x)},
$$

而 $f_{X}(x) = \int_{-\infty}^{+\infty} f(x, y) \mathrm{d}y = \frac{1}{\pi} \mathrm{e}^{-x^2} \int_{-\infty}^{+\infty} \mathrm{e}^{-(y - x)^2} \mathrm{d}y = \frac{1}{\sqrt{\pi}} \mathrm{e}^{-x^2}$ ,

所以 $f_{Y|X}(y|x) = \frac{f(x,y)}{f_X(x)} = \frac{1}{\sqrt{\pi}}\mathrm{e}^{-(x - y)^2}, - \infty <  x <   + \infty , - \infty <  y <   + \infty .$

方法点评：二维连续型随机变量的联合密度、边缘密度及条件密度关系如下：设 $(X,Y)$ 的联合密度函数为 $f(x,y)$ ，则

（1）边缘密度函数

$$
f _ {X} (x) = \int_ {- \infty} ^ {+ \infty} f (x, y) d y, \quad f _ {Y} (y) = \int_ {- \infty} ^ {+ \infty} f (x, y) d x,
$$

若 $X, Y$ 独立，则 $f(x, y) = f_{X}(x)f_{Y}(y)$ .

（2）条件密度

在 $X = x$ 的条件下， $Y$ 的条件密度为 $f_{Y|X}(y|x)$ ，且 $f_{Y|X}(y|x) = \frac{f(x,y)}{f_X(x)}$ ；在 $Y = y$ 的条件下， $X$ 的条件密度为 $f_{X|Y}(x|y)$ ，且 $f_{X|Y}(x|y) = \frac{f(x,y)}{f_Y(y)}$ .

（23）【解】 显然 $N_{1}\sim B(n,1 - \theta)$ ， $N_{2}\sim B(n,\theta -\theta^{2})$ ， $N_{3}\sim B(n,\theta^{2})$

$$
E \left(N _ {1}\right) = n (1 - \theta), \quad E \left(N _ {2}\right) = n \left(\theta - \theta^ {2}\right), \quad E \left(N _ {3}\right) = n \theta^ {2},
$$

由 $E(T) = a_{1}E(N_{1}) + a_{2}E(N_{2}) + a_{3}E(N_{3})$

$= a_{1}n(1 - \theta) + a_{2}n(\theta -\theta^{2}) + a_{3}n\theta^{2} = \theta$ ，得

$$
a _ {1} = 0, \quad a _ {2} = \frac {1}{n}, \quad a _ {3} = \frac {1}{n}.
$$

因为 $N_{1} + N_{2} + N_{3} = n$ ，所以 $T = \frac{1}{n} (N_2 + N_3) = 1 - \frac{1}{n} N_1$

故 $D(T) = \frac{1}{n^2} D(N_1) = \frac{\theta(1 - \theta)}{n}$ .