MathAnalysis | 数学分析

Calculus | 微积分

# 独创术语

- 咧：无穷（词源：阿列夫；并考虑无穷大本意即将本来很大的限（穷）咧（裂）开；并∞符号像咧嘴笑（牵强））
  - 例句：无穷级数は数列咧加。（正项级数）高咧小于敛则敛。

# Len

- 20190515建]数.调和级数 = 乐.泛音列
  - 驻波：驻波 （stationary wave（英）/standing wave （美）） 频率相同、传输方向相反的两种波（不一定是电波），沿传输线形成的一种分布状态。其中的一个波一般是另一个波的反射波。在两者电压（或电流）相加的点出现波腹，在两者电压（或电流）相减的点形成波节。在波形上，波节和波腹的位置始终是不变的，给人“驻立不动的印象，但它的瞬时值是随时间而改变的。如果这两种波的幅值相等，则波节的幅值为零。
    - 拨动两端固定张紧的弦，使波经两固定端反射可干涉产生驻波。弦的两固定端必为节点。当弦上产生驻波时，弦长L为半波长的正整数倍。
      - 当弦乐器的弦因振动发出声音时，振动频率最低者为 n = 1 时的情况，称为基频或基音(fundamental frequency)；频率较高的音称为泛音(overtones)，基音和泛音统称谐音(harmonics)。
      - 这个驻波所产生的基音，就是我们平常听到乐器发出的音，同一乐器所发出其他频率的声音皆不明显。
  - *还没查清楚原因，但总之，乐器发声都是产生了驻波。*
    - 只有形成驻波，弦振动的能量才会衰减得最慢（[乐器内部的驻波与声音的关系是什么？](https://www.zhihu.com/question/62279000)）
    - （前面说到，一根弦被弹拨/拉时，能量会向两端传播，最后反弹回来产生驻波，只有这些驻波对应的频率才会长久存在）……“所有的乐器，无论是弦乐还是管乐、或者鼓乐器都是驻驻波的振动而产生特定的音频。”——《普通物理学》高教版（[如何解释「泛音」？它是如何产生的？](https://www.zhihu.com/question/321383760/answer/662113383)）
  - 泛音也都是驻波，故频率都是基音的整数倍，波长则是其整数分之一，这个波长的比例序列就是调和数列
    - 基音影响音高、旋律，泛音影响音色
  - 调和数列的咧和は**调和级数**
  - 数列都是常数 p 次幂，则称**p 级数**か**超调和级数**




# 以下整理自马同学

> "数与形,本是相倚依,焉能分作两边飞。数无形时少直觉,形少数时难入微。数形结合百般好,隔离分家万事非;切莫忘,几何代数统一体,永远联系,切莫分离!"——华罗庚

## 微积分的历史（一），起源之背景

- > 微积分ﾊ高数ﾉ基础ﾅﾘ，各种需求ﾄ思想ﾉ交汇ﾃﾞ孕育
- 1 微积分产生的时代背景（需求）
  - > 兴趣或许是动力，不过我觉得需求是更好的动力。
  - 研究天文(托勒密👉第谷👉开普勒，开普勒三定律（椭圆、面积、调和）👉计算面积)；研究运动（位移、速度、加速度）；研究光学（切线、法线）；研究最值——射炮；还有很多问题
- 2 历史渊源：芝诺悖论（两分法、飞矢不动）——认识无穷；；割圆法计算圆周率，阿基米德；；计算抛物线下ﾉ面积，卡瓦列里说穷竭法不严但有用；；零星ﾅ微积分成果——费马、卡瓦列里分别给出$x^n$ﾉ定积分
- 3 总结：既有需求、思想渊源，两ﾂ大师归纳总结为学科

## 微积分的历史（二），起源之牛顿

- 1 牛顿的微积分
  - 微积分第一基本定理（证明求导是不定积分的逆运算，or 求积分上限函数的导数是被积函数）
  - 微积分第二基本定理（牛顿-莱布尼兹公式）
- 2 的一点问题
  - 2.1 可积性（定积分存在定理）（然后，可积则积分上限函数存在。）——两个充分条件。：闭区间连续则。闭区间有界且仅有限个间断点则。
  - 2.2 此变上限积分可导否。用**原函数存在定理**，连续定存原函数，有第一类跳跃间断点或第二类无穷间断点必不存，有第二类震荡间断点可能存（*原函数即其导数为被积函数f，即F可导；而f有跳'间'点则F固不可导（左右导数异），无穷间断点亦f不存，F不可导；故f无原函数。「原函数」之名晦甚，倡称被导函数*）
  - 2.3 有原函数的，不一定有积分上限函数，栗无界而震荡（而乘以x的幂让它收敛）（而定义零点为零）ﾅ被积函数f **¿¿(其构造不明就里)**
- 3 总结：为解积分上限函数ﾉ诸局限性，只消给定积分更好的定义，此需下章节出场ﾅ大师。**¿¿（什么局限性ｶ）**

## 微积分的历史（三），起源之莱布尼兹

- 1 莱布尼兹的微积分思想。积分：无穷小的加法。积分符号∫ﾊ此殊s(求和)。切线：距离无穷小dx，增量dy（曲线增量亦切线增量），商ﾊ斜率即导数。微分：名无穷小为微分
- 2 与近代微积分思想的对比
  - 2.1 无穷小是什么？：莱布尼兹不明确；莱布尼兹的思想基本正确，只要修正无穷小的定义
  - 2.2 现代微积分观点
    - 切线：用极'述无限接近
    - 微分：微分ﾊ切线增量，差分ﾊ曲线增量，导数ﾊ差分商极限
    - 以直代曲：dy为切线，以直代曲。以直代曲是微积分最重要的思想，围绕这个核心可以把知识串联起来
    - 积分：不是矩形的和，是黎曼和的极限
- 3 牛顿-莱布尼兹公式之莱布尼兹
- 4 总结：牛顿和莱布尼兹完成了普遍性或说抽象性的工作

## 微积分是什么？

- > 从小学开始我们就在学习数学，但是大学之前的数学只能算是思维训练。而微积分才算是数学真正的起点，是很多学科基础中的基础。
- 开普勒第二定律
- 面积计算：线性近似或说以直代曲；矩形逼近计算面积谓微积分，微分ﾊΔx无限近零时小矩形面积，积分ﾊ小矩形相加
- 问题：究竟何为「Δx无限近零」，尚待「极限」概念生 *（乔治·贝克莱之嘲）*

## 如何理解极限的精确定义？ 

- https://www.zhihu.com/question/20573378/answer/120029023
- > 数学中的函数极限ﾊ，对函数去到无穷远处和无限接近某一点的趋势ﾉ描述。
- 2 初见极限：看作无穷数列ﾉ极；必左右极存且等，极方存，否则不知听哪边。
- 3 邻域ﾄ去心邻域：一定范围内才趋近故`邻域`；仅逼近而不管此点，故`去心邻域`；
- 4 极限能否为+∞：+∞非个实数；收敛到实数才是有极，发散到+∞是发散，极不存；正无穷负无穷放在实数轴端点谓`超实数域`，其极不讨论
- 5 ε与δ：ε只述f(x)无限近L，δ只述x无限近c

## 如何能更好的理解（ε-δ）语言极限的定义？

- https://www.matongxue.com/madocs/18/
- 几何模型：凡提案制限ε，是否能觅合适ﾅδ，使所映（因变量）全在提案制限区内
  - *（新想法：émittree & destiny，每个提案，都有运命使在区）*
- 易知震荡函ﾉ震荡点无极，因为如 $\sin\frac{1}{x-2}$，所映区恒长1，对更小制限区失格

## 无穷小量究竟是否为零？（TOBE）

- https://www.matongxue.com/madocs/24/
- > 注：本文基于经典微积分，非标准分析不论。
- 1 无穷小的历史：咧小无严格定义引发了第二次数学危机。极'出现才有精确定义，理解之要先理解极'。
- 2 无穷小家族：0或常数0函数或常数0序列；无穷数列（收敛派系中收敛于0者）；极限值为0的函数
- 3 无穷小盍负无穷？：像力，正负都是力，0才是无力
- 4 总结：无穷小量非一ﾂ数，而指一堆ﾓﾉ

## 函数连续和一致连续有什么区别？开区间上的连续函数不一定是一致连续的，为什么？

- https://www.matongxue.com/madocs/21/
- 连续：`一点に连续`は$\displaystyle \lim_{x\to c}f(x)=f(c)$ 即$\displaystyle \lim_{x\to c}(f(x)-f(c))=0$，易见 x 越近 c，函值也近；；每点都连'则`函数が连续`
- 一致连续：∀ε，∃δ，使∀两点有两点距<δ时所映距<ε。比连续多了「任意两点」，即小船在x轴滑动。
  - > 几何理解：提出制限区和运命制限区形成矩形，函图在其内。∀提出制限（ε）都要找到对应的运命制限（小船），st函线不刺破矩形
  - 代数意义：$\displaystyle \lim_{x_1\to x_2}(f(x_1)-f(x_2))=0$，与普通的一致不同之处在于减数。
    - > 连续是一静一动，只关乎彼静点，一致连续是两动，与整个区间有关
  - > 不一致连续的例子：$f(x)=\frac{1}{x}$，找到 x1, x2 分别 1/n,1/(n+1) 这样的方式相互接近，而所映之距终为1
- 为什么会有一致连续
  - > 柯西定义连'时，用力过猛，先定义了一致连'，后发现此定义比连'更强，才转身定义了连'。学了拓扑会发现一'连'的更多应用。

## 微分是什么？

- https://www.matongxue.com/madocs/847/
- 1 积分：级数和
- 2 不使用微分存在问题：计算复杂；不够抽象
- 3 微分：微分为直，差分为曲，微'是差'的近似（线性近似），微'下的求和（即积'）为（lim使Δ趋零，即块数无穷）$积分=\lim\sum 微分$；矩形、三角形、弧様な微'一绪

## dx，dy是什么？

- https://www.matongxue.com/madocs/849/
- > 之前笼统地介绍了微分大概是什么？本节来认识第一个的微分：切线。（直线段近似曲线段）（怎么求；为啥是微分）
- 1 切线：割线ﾉ极限
- 2 导数（求切线）：须`斜率`，即割线斜率ﾉ极'，又谓`¡¡导数`，Δ因变量比Δ自变量，的极'，存曰`可导`；开区间内可导则`¡¡导函数`，诸斜率之函；有时 $D=\frac{d}{dx}$ 称`D算子`；
  - `算子`者函到函ﾅ映'，焉ﾊf到f'
- 3 切线函数与微分函数：点斜式得`切线函数`，换（移）坐标系（dxdy坐标系）则`x_0点的¡¡微分函数`；又`d算子`将f映射到微分函h
  - $g(x)=f'(x_0)Δx+f(x_0) \implies 微分函数 h(x)=f'(x_0)Δx$
  - 又∵ $dx=Δx$，∴微分函与导数 $dy=f'(x_0)dx \implies f'(x_0)=\frac{dy}{dx}$，导数又谓`微商`
  - 扩展到∀点，则用 d 算子得到`¡¡函数的微分` $dy=f'(x)dx$（二元函数，微分dx，与，切点x）
  - 微分ﾊ`线性映射`（齐次性、可加性，蕴含了必过原点）。故线代定理可用。
    - 如用正交向量点积零求`法线`斜率 -1/f'
- 4 为何切线即微分？
  - 微分は线性增量，差分は曲线增量
  - $Δy-dy=o(Δx)$故近似
  - 定义：函数增量在某点可示以$Δy=AΔx+o(Δx)$则`可微`，第一项谓`微分`（函数相对于自变量）
  - 可得结论：函在一点，可导充要可微（可导则有导数ﾄ咧小构可微；可微则一除一极构可导）

## 微分和导数的关系是什么？两者的几何意义有什么不同？为什么要定义微分 ?

- https://www.matongxue.com/madocs/15.html
- 1 古典微积分：基于无穷小量（缺陷严重，甚至违反阿基米德公理，致第二次数学危机）。古典的微分是无穷小量，导数基于无穷小量定义，
- 2 极限微积分：基于极限。用商的极'定义`导数`，意为变化率；再定义`微分`，线性函数，意为变化ﾉ数值；定积分亦非面积和而是黎曼和
- 3 疑问的解答：古典的直观但不抽象，带来认知问题
  - 链式法则不是约去，理解以d是二元操作符，操作因变量ﾄ自变量；黎曼和理解为左括号右括号；
- 4 无穷小量的逆袭：有兼容无穷小量不出问题的实数`超实数`，这门学科`非标准分析`

## y=e^x 无限求导每一次都等于自身有什么深层含义或是实际应用吗？

- https://www.zhihu.com/question/35220414
- 根据指数函数的特性：一顿操作，指数函数的斜率（导数）由原函数和 f'(0) 决定。
  - > 可以定义：对 f(x)=a^x ，使 f'(0)=1 的即 e 。自然有 $\frac{d}{dx}e^x=e^x$
  - 一番求解又可得 $\displaystyle e=\lim _{n \to \infty }(1+\frac{1}{n})^ n$，为常用定义
- 据线性变换ﾉ特征向量：微分$\frac{d}{dx}$ﾊ线性变换，
  - 据 $Av=λv$ ，对微分有 $\frac{d}{dx}e^{λx}=λe^{λx}$ ，即微分ﾉ特'向量（这个时候更多称为特'函'）ﾊ$e^{λx}$ 
  - > $e^x$ﾊ线'变'$\frac{d}{dx}$特'值$λ=1$时对应ﾅ特'向'。

## 微积分的历史（四），发展之伯努利兄弟

- > 有了技术，微积分ﾉ应用才更广
- 1 链式法则（复合函数求导）
  - 直观印象：二级皮带传动
  - 不是「消去」，看着像消去其实只是一个巧合。dy/du * du/dx = dy/dx，第一个du等于差分，第二个du是对于dx的切线增量
    - > 在一阶求导、积分的时候，把du看作可消似乎运转很好，但皆巧合（或说是微积分符号设计之妙，归功于莱布尼兹）。虽然这种误解有助于记忆某些定理、公式，但定要知为什么
  - 蕴含**一阶微分不变性**（不区分自变量、中间变量）
- 2 洛必达法则 *（约翰·伯努利发明）*：「以直代曲」之应用也
- 3 无穷级数：*雅各布·伯努利的又一些贡献*
  - 数学ﾉ基本元素；；积分ﾉ基；；更重要——泰勒级数

## 如何理解洛必达法则？

- https://www.matongxue.com/madocs/11/
- 1 洛必达法则：不定式极限求以上下导
  - 构关键函 $u(x)=(g(x),f(x))$，数轴→平面，原点到u上点连线为原点线，斜率f/g，u上点斜率f'/g'
  - 在原点（零零型）或无穷远（咧咧型），二斜相等
- 2 扩展洛必达法则（马同学法则w）：凡原点线和割线斜率相等就可用，如4x/2x

## 洛必达法则失效的情况？

- https://www.matongxue.com/madocs/22/
- 1 使用条件：未定式，可导，有极限（或咧大）。还有个初衷——简化计算。
- 2 有时求导无法简化函数：那要你何用。如分数次幂、e^x
- 3 有时解出极限不存：不能判原式（然按永乐，求出无穷可推原）

## 微积分的历史（五），发展之泰勒公式（上）

- 1 泰勒公式做什么：用幂级数近似（幂级数更易研）
- 2 插值法：线性插值；；多项式插值——线性方程组（问题：计算量大；新增加点要重新计算）、**牛顿插值法**（格雷戈里-牛顿公式）
  - 牛顿插值法ﾉ极限即泰'
    - n点插值对应泰'n-1阶展开（泰勒首项0阶故）
    - 插值点间越近，插值曲线和泰'越接近，∴可说插值曲线ﾉ极限形式即泰勒公式
- 3 牛顿插值法与泰勒公式的代数推导
  - 牛顿插值法：各种$Σ_0^k(x-x_i), k=0,...,n$相加，系数ﾊk+1阶均差
  - 泰勒公式：插值点距咧小，k+1阶均差带来了导数（迊差）ﾄ除以阶乘（迊均）

## 微积分的历史（六），发展之泰勒公式（下）

- 1 泰勒公式的代数形式
  - 定义：多项式、余项。
    - > 麦克劳伦公式，本尊亦言毫无创新。
  - 幂函数ﾉ特点：
    - > 幂函数是其最基础的部分
    - 特点：①只有原点对称、x轴对称两种形态②指数越大增速越快
    - 有了除以阶乘的帮助，可以更多显示低指数幂函数的特征
    - > 调整系数，图形像弯铁丝
  - 用多项式逼近sinx：展开点和展开阶数的作用
- 2 泰勒公式的收敛半径
  - 什么是收敛：f为无限阶可导的函数（有限则无收敛问题），展开到∞阶时，对某自变量x，泰勒级数和原函数的因变量值相距为∞，则发散，反之收敛
  - 泰勒公式的`奇点`：f在此不可导（如$x^{1/3}$）或无定义（如$1/x$）。奇点可能不在实轴（如$\frac{1}{1+x^2}$）
  - 奇点与`收敛圆`：
    - 柯西证了泰'级'ﾉ`收敛半径`，复平面上，以展开点a为圆心，最近的奇点为圆周一点画圆，为收敛圆，圆周及圆外均发散，圆内（不含圆周）收敛
      - > 非常漂亮的数学结论
    - ∴想用泰'估计值，需要在收敛域内
      - > 不喜技巧，不过仍然说一下如何合理的估算$30^{\frac{1}{3}}$。
      - > 故估计 $30^{1/3}$ 的值，要把 $x^{1/3}$ 在如 27（好算）处展开，不能在9处
  - 复数与实数的关系
    - $\frac{1}{1+x^2}$ 在实平面上依然被复平面的奇点 $i$ 影响其收敛性
    - > 我们学习的高等数学，都是在实数范围内，所以导致我很长时间认为复数只是一个表示$i=\sqrt{-1}$的一个技巧，而泰勒级数收敛圆向我展示了实数切切实实是复数的一部分，哪怕你只研究实数部分的问题，仍然会被复数所影响。这是我认为它非常美丽的原因。
    - > 我们还应该认识到泰勒级数只是对原函数的近似，并且这种近似是有条件的。
- 3 总结
  - > 我们通过几何直观发现了幂级数可以近似表示各种函数，但是最终我们通过代数发现了泰勒公式，这就是代数的洞察力。

## 如何通俗地解释泰勒公式？

- https://www.matongxue.com/madocs/7/
- > 用多项式函数逼近光滑函数
- 1 多项式的函数图像特点：轴或点对称，增速
- 2 泰勒公式与拉格朗日中值定理的关系：泰勒公式余项$R_n(x)=\frac{f^{(n+1)}(\theta)}{(n+1)!}(x-a)^{(n+1)}$当n=0。也可以用n=0看出泰勒公式几何意义，加上余项后是一根直线
- 3 泰勒公式是怎么推导的？：fx可全由一点和好多个差分得到，差分极限便是
- 4 用处：最直接是用于计算，如计算机。另可简化，如解$\displaystyle \lim_{x \to 0}\frac{sin(x)}{x}$
  - > 多项式这种函数是我们可以亲近的函数，它们很开放、很坦白

## 从牛顿插值法到泰勒公式

*（没啥新东西）*

## 使用泰勒公式进行估算时，在不同点有啥区别？

*（没啥新东西）*

## 泰勒级数为什么不可以展开？

- $\frac{1}{1+x^2}$ 泰勒展开有收敛半径，是被虚轴的奇点影响，复数域看真相$g(z)=\frac{1}{1+z^2},\quad(\color{red}{z\in\mathbb{C}})$（画了个三维图，只有实部值。）
- （乘以i就相当于旋转90^\circ）
- $g(x)=\frac{1}{1+x^2}\xrightarrow{\quad 自变量旋转90^\circ\quad }f(x)=g(ix)=\frac{1}{1-x^2}$
- 自变量任意旋转，收敛半径得收敛圆

## 如何理解三大微分中值定理？

- 1 罗尔中值定理：拉丶中の特例。闭区连续开区可导两端相等⟹有导数为零な点
- 2 拉格朗日中值定理：柯丶中の特例。闭区连续开区可导⟹有点导数=总割线斜率。
  - > 物理意义是，至少存一点，速=均速
- 3 柯西中值定理：个参数方程，描述二维空间运动，总运动方向$\frac{f(b)-f(a)}{g(b)-g(a)}$，途中点斜率$\frac{f'(\xi)}{g'(\xi)}$，必有一途中点方向等于总方向。


## 什么是黎曼和？什么是定积分？

- 1 抛物线下的曲边梯形：均分，取范围内左边界或右边界等果
- 2 狄利克雷函数的曲边梯形：用无理数划分并取高则结果异于有理数（是以黎曼积分不存）
- 3 黎曼和：∀な`划分`，∀高度；；有定义的区间内，插入分点，点集曰`划分`，定义了子区间，其上任取高，矩形和称`黎曼和`
  - $A_n=\sum_{k=1}^{n}f(\xi_k)\Delta x_k$
- 4 定积分：子区间长度最大值λ趋零ﾅ黎曼和极限存在，称`被积函数`が`积分区间`に`可积`，`积分上限`ﾄ`积分下限`，`定积分`，`积分变量`，∫意为sum的极限。

## 为什么定积分可以求面积？

- > 但罗马并非一日建成。大师也是人，除非是穿越的，否则也不可能一下就把数学发展到这么完善。追根溯源你会发现，这些数学概念也是肇始于各种直观的想象甚至是臆测，虽然稚嫩却极具启发性。
- > 我个人觉得学习过程中，直观是首要的，严格性可以放到后面去，看得懂总比看不懂要好。

## 如何通俗的解释全微分？

- https://www.matongxue.com/madocs/218/
- 1 一元函数中的微分：以直（切线）代曲（曲线）
- 2 全微分：二元微分即所有的切线都存在，并且都在一个平面。这样个平面存则它就是二元的微分，亦称“切平面”。

## 多元函数中全微分与偏导数、偏微分的直观区别是什么？

- https://www.matongxue.com/madocs/219/
- > 全导数这里暂时不讲，看名字好像和全微分关系很大，其实和“方向导数”的关系更大，所以留到讲“方向导数”的时候再一起来说。
- 1 偏微分：定y之线与曲面交的线的切线，称为f对x的偏微分（固定他，变换此）
- 2 偏导数：偏微分的斜率
- 3 全微分：与xy面垂直所有角度的面与之截线的切线都存，且诸切线（无数条）都在同平面上（不是曲面），得到的平面就是全微分（也叫切平面，或者切空间）
- 4 全微分与偏导数、偏微分的关系：有前者一定有后；后者则只是两个方向而非全部

## 什么是全导数？

- https://www.matongxue.com/madocs/236/
- 全导数的意义：曲面上∀曲线能做出来切线（除非不可），每一根切线都和一个全导数“相关”
- 1 参数方程：f(x,y)曲面上的曲线可用xy表示，这个xy再用参数t表示。t代进去，z就成了一元
- 2 全导数、偏导数、方向导数：过A点无数曲线每个曲线的切线和一个全导数相关；而方向导数（包括偏导数）属于特殊曲线（xy上直线），他们直接是切线的斜率
- 3 每根曲线的切线和一个全导数“相关”是什么意思？：方向导数，对应的曲线在平面中，一元化（拍扁）亦不变形，而普通的全导拍扁则变形，全导是zt平面中的切线的斜率，不等于xyz空间中的切线（实际上要是还原回去的话是一条曲线），xyz空间的切线需要全导数dz/dt及dy/dt、dx/dt共同决定，具体求解用到切向量

## 如何直观形象的理解方向导数与梯度以及它们之间的关系？

- https://www.matongxue.com/madocs/222/
- 1 方向导数：xy面上一个矢量为方向， 对应曲线斜率是方向导数
- 2 梯度：是一个矢量，其方向上的方向导数最大，其大小正好是此最大方向导数。前提：具有一阶连续偏导（意味着可微），此前提下只有一个最大，自行计算
- > 这个算法叫做梯度下降算法，我在这里只是描述了它的算法思想，真正实用中还需要很多的改进和优化，以及有它的局限性，这里就不展开讲了。

## 如何理解导数的概念 ?

- https://www.matongxue.com/madocs/243/
- 1 （片面）导数是变化率、是切线的斜率、是速度、是加速度：在多元函数中片面、不正确
- 2 导数是用来找到“线性近似”的数学工具：一元中，以之找到斜率即找到了切线
- 3 导数是线性变换：差分左乘导数A_i即切线（其实不在原点的话要仿射变换），A_i皆等则此点可导，导数即A。因为是线性变换所以共xy面的变化量们左乘完依然共面，切平面

## 如何解释曲面面积公式？

- https://www.matongxue.com/madocs/251/
- > 不同于《高等数学》书中的方法，本文通过线性变换的思想来推导一下曲面积分公式。
- 1 曲面面积公式：∫∫dS=∫∫ √(1+(pf/px)^2+(pf/py)^2) dxdy
- 2 基本思想：以直代曲（曲面面积换成切平面面积）
- 3 通过线性变换来计算小切平面面积：xy平面的投影，通过导数这一线'变'（实际是仿射变换），变成之。
  - 求面积即xy平面的dx,dy变换到切平面的du,dv二者叉积之模。
  - uv皆通过雅可比矩阵从xy变换过去
  - ![计算曲面面积](https://raw.githubusercontent.com/pusto-tauranth/pusto-kit/master/PicTemp/CurvePlaneCalcu.png)
  - **¿¿（没看懂雅可比矩阵里面为什么要对这三个函数求偏导）**

## 极坐标下的二重积分，化为二次积分后，每次积分的几何意义是什么？

- https://www.matongxue.com/madocs/255/
- 每次积分不一定有几何意义
- xy坐标系的扇形变成极坐标里的方块，这是线性变换，ρdρdθ前的系数ρﾊ线'变'ﾉ伸缩因子，即行列式，即雅可比矩阵ﾉ行列式。*(曲面面积公式ﾓ同理ｶﾅ)*
  - 只是个伸缩因子，不对单次积分有几何意义
- 4 关于换元进一步的例子……

## 散度和旋度的物理意义是什么

- https://www.matongxue.com/madocs/259/
- > 数学没有物理是瞎子，物理没有数学是跛子
- 1 通量与散度
  - 1.1 通量：曲面上的矢量加起来，只关注法向分量（点乘法向量）；
  - 1.2 散度：封闭曲面趋近零，的通量，除以所围体积.强度样。方向出正。
- 2 环流量与旋度
  - 环流量简单来说，就是单位时间内环绕的某个曲线的量。点乘切向量。
  - 环流量强度为旋度。
- 通量是单位时间内通过的某曲面的量；；散度是通量强度；；环流量是单位时间内环绕的某曲线的量；；旋度是环流量强度

## 如何理解格林公式？

- https://www.matongxue.com/madocs/265/
- （做功、环流量）问题：螺旋桨做功。建模：水流は力场，做功は一点沿圆形路径做功。旋转、路径方向：逆正。即，小段的力点乘切向量，的积分。
  - 数学计算：矢量转标量——F与t皆分解也；；“守恒”——任意路径边界的功 = 围成区内所有微分矩形边界ﾉ功；；微分矩形四个边界的功自然推出
- （通量）切线改法线，则求通量，**¿¿（具体计算为何是减号、又加号）**
- 对于数学有重要的意义，相当于把封闭曲线的线积分转为了二重积分

## 如何理解常微分方程的通解、特解以及所有解？

- https://www.matongxue.com/madocs/269/
- y' = f(x,y), y=f(x) だ
- 1 解常微分方程的几何意义：根据切线画出曲线
- 2 欧拉方法：隔Δx，导数作为斜率画切线，连接之
- 3 线素场：平面上等距取网眼，各个点画出切线
- 4 通解、特解和所有解：微分方程往往有无数ﾂ解；；些解，可以写成y=f(x,C)的形式，其中C为任意常数，称为通解；；对于通解，特定的初始值a_1点，可以得到一个特解；；通解并不包含所有解（如不包含零解）

## 如何理解线性微分方程？

- https://www.matongxue.com/madocs/513/
- 1 线性变换：直线变换到直线；；多项式函数以x^n为基可；；微分算子D，[[0，1，0][0，0，2]]，使降维，亦线性变换；；代数定义可加性齐次性；；D的多项式组合也是线性变换
  - $\mathcal{L}=a_0+a_1D+a_2D^2+\cdots+a_nD^n,a_0,a_1,\cdots,a_n\in\mathbb{C}$
- 2 线性微分方程：常系数线丶微丶方丶（a_i常数）$\mathcal L(y)=f(x)$，f=0则齐次，a_i非常数は变系数；；等同Ax=0；；解则特征值λ=0对应的特征向量；；D及L特征向量e^{nx}；；令特征值=0可得几个n，这几个特征向量线性无关可得解；；特征值相同则，另外讨论；；非齐次则先求齐次，再根据初始条件一个特解；；还可以灵活处理，一般比特解法复杂；；
- 因为\mathcal{L}是线性的，所以线'微'方'是线性的；；因为e^{nx}是\mathcal{L}的特'向量，所以通解里面有e^{nx}