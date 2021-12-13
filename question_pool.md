# 核辐射探测器复习题
------

1. 叙述核辐射的种类，针对每种射线列举出至少两种适合对其测量的探测器。

**答案正文**：

习惯上将核辐射归纳为如下四大类：
- 带电粒子辐射
  - 重带电粒子：α、裂变碎片
  - 轻带电粒子：β
- 非带电辐射
  - 电磁辐射：X、γ
  - 中子

适合测量各射线的探测器：
| 射线 | 探测器 |
|---|---|
| 重带电粒子  | 金硅面垒探测器  |
|   | NaI(Tl)  |
| 轻带电粒子  | 硅面垒探测器  |
|   | 液体闪烁体  |
| 电磁辐射  | 电离室  |
|   | HPGe 探测器  |
| 中子  | <img src="https://render.githubusercontent.com/render/math?math=\text{BF}_3"> 正比计数管  |
|   | 核乳胶  |

**来源**：

- 叙述核辐射的种类
  - 《核辐射探测器》，P19
- 适合的探测器
  - 重带电粒子
    - 《核辐射探测器》，P34-35
  - 轻带电粒子
    - 《核辐射探测器》，P39-40
  - 电磁辐射
    - 《核辐射探测器》，P55
  - 中子
    - 《核辐射探测器》，P67-68

**讨论**：

- 或许各射线对应的探测器尽量写相同更好，毕竟好记一点

------

2. 根据利用的效应对核探测器进行分类，并列举出每一类型中的几种探测器，每类至少列举两种。

**答案正文**：

- 电离型：直接测量射线引起的电离
  - 正比计数管
  - 半导体探测器
- 发光型：测量由于射线入射而产生的光子
  - 闪烁体
  - 热释光探测器
- 物体变化型
  - 低温量热器
  - 核乳胶

**来源**：

- PPT 讲义《绪论 射线与物质相互作用(2)》P36

**讨论**：

------

3. 通常核探测器可以对核辐射进行哪几类测量？

**答案正文**：

共有四类测量，分别为：
- 计数测量
  - 活度，环境放射性水平，中子注量
  - 核反应截面，沟道效应等
- 能量测量
  - 带电粒子出射能谱，γ 能谱
- 时间测量
  - 各种寿命测量，飞行时间法，扰动角关联
- 位置测量
  - 径迹探测
    - 宇宙射线、高能物理
  - 位置探测
    - 角分布测量，背散射测量

**来源**：

- PPT 讲义《绪论 射线与物质相互作用(2)》P13

**讨论**：

------

4. 探测器的主要性能参数有哪些？并简述其概念。

**答案正文**：

- 能量分辨
  - 将不同粒子能量分辨开来的能力。
- 时间特性
  - 分辨时间
    - 探测器在时间上分辨两个脉冲的能力。
  - 上升时间
    - 输出脉冲高度值从10%达到90%的时间。
  - 下降时间
    - 输出脉冲高度值从90%回到10%的时间。
- 测量效率
  - 在一定探测条件下，测到的电离辐射粒子数与在同一时间间隔内由辐射源发射出的该种粒子总数的比值。

**来源**：

- 总体
  - PPT 讲义《绪论 射线与物质相互作用(2)》P37、P43
- 分辨时间的概念
  - 课程 第 5 次课，视频 2 约 00:44:35 ~ 00:44:42 处

**讨论**：

------

5. 简单回答下列问题并给出理由：
  
(1) 金硅面垒探测器是否适合测量 60Co 发射的 1173.2keV γ 射线的能量？

(2) 气体电离室是否适合测量 60Co 发射的 1173.2keV γ 射线的能量？

(3) 气体电离室的输出脉冲是电子和离子收集到电极上之后才形成的吗？

(4) 闪烁体和光电倍增管之间的光学耦合剂可以用水来代替吗？

(5) 半导体探测器是否适合使用电压灵敏前置放大器？

(6) 探测器灵敏物质的对射线的平均电离能的含义是什么，其是否等于单个靶核原子的电离能？

(7) 重带电粒子单位路程上产生的电子-离子对数目在整个路程上是均匀分布的吗？

(8) 核阻止效应所损失的能量能否被电离型探测器探测？

(9) 高能和低能 β 射线是否适合用含有重元素的探测器进行测量？

**答案正文**：

(1) 不适合。金硅面垒探测器灵敏体积不能做得很大，测量高能 γ 射线时探测效率及峰康比低。

(2) 不适合。当 γ 射线能量较高时，来自气体计数器的大部分 γ 射线感生的脉冲信号是由 γ 射线与气体探测器的固体外壳壁上发生相互作用产生的，这种情况产生的次级电子在它完全被挡住以前进入气体，而电子在器壁上损失的能量是可变和不确定的，它对探测器输出脉冲起到了不好的作用，影响了探测器的能量分辨率。所以气体电离室不适合测量 60Co 发射的 1173.2keV γ 射线的能量。

(3) 不是，电子-离子对在漂移过程中就在电极上产生感生电荷。

(4) 不可以。因为水的折射率比硅油低，以水为光学耦合剂会增加交界面上发生全反射的概率。而且，用水还会产生漏电流，会蒸发、腐蚀。

(5) 不适合。应使用电荷灵敏前置放大器，噪声低；电压灵敏放大器噪声高。

(6) 
- 平均电离能指一定条件下某一探测介质中产生一个载流子平均所需的能量。
- 因为带电粒子在介质中的电离存在一定的统计涨落，所以平均电离能不等于单个靶核原子的电离能。

(7) 不是。对特定靶物质，平均电离能是一定的，而重带电粒子在单位路程上损失的能量与其速度、电荷态有关，这些值在其射入靶物质后不断变化，所以重带电粒子在单位路程上产生的电子-离子对数目在整个路程上不是均匀分布的。

(8) 不能。核阻止效应较强时，离子能量较低、电荷态接近中性。所以核阻止可视为两自由粒子弹性碰撞，不产生载流子，转移的能量无法被电离型探测器探测。

(9) 不适用。因为高能 β 射线打到重元素靶上会发生较强的轫致辐射，低能 β 射线会发生大角度散射。

**来源**：

- (1)
  - 《核辐射探测器》，P57
  - 《原子核物理实验方法 修订第三版》，P140
- (2)
  - 《核辐射探测器》，P55
- (3)
  - PPT 讲义《气体探测器》P6
  - 课程 第 9 次课，视频 1 约 00:31:23 ~ 00:31:34 处
- (4)
  - PPT 讲义《闪烁体探测器》P24
  - 《核辐射探测器》，P112
  - 《原子核物理实验方法 修订第三版》，P109
  - https://en.wikipedia.org/wiki/List_of_refractive_indices
- (5)
- (6)
  - 《原子核物理实验方法 修订第三版》，P18-19
  - PPT 讲义《绪论 射线与物质相互作用(2)》P38
- (7)
  -  《原子核物理实验方法 修订第三版》，P47
  -  PPT 讲义《绪论 射线与物质相互作用(2)》P77-78
- (8)
  - PPT 讲义《绪论 射线与物质相互作用(2)》P83
- (9)
  - 《核辐射探测器》，P28-30 (图 2.12)

**讨论**：

- (5) 的答案缺乏来源，好像核电子学的书上有。
------

6. 简述带电粒子与靶原子碰撞的一般行为包括哪些，Bether-Block 公式
（<img src="https://render.githubusercontent.com/render/math?math=(-\frac{dE}{dx})_e = \frac{4 \pi z^2 e^4 NZ}{m_0 v^2}[\ln{(\frac{2m_0 v^2}{I})+\ln\frac{1}{1 - \beta^2}-\beta^2-\frac{C}{Z}}]">）
中各项的物理意义。为什么 dE/dx~E 曲线有极大值出现？重带电粒子阻止本领与粒子能量的关系曲线，并简述曲线各部分对应的效应，和对其描述的理论。

**答案正文**：

(1) 带电粒子与靶原子碰撞的一般行为包括：

- 与靶核外电子的非弹性碰撞
- 与靶原子核的非弹性碰撞
- 与靶核外电子的弹性碰撞
- 与靶原子核的弹性碰撞

(2) Bether-Block 公式中各项的物理意义

- <img src="https://render.githubusercontent.com/render/math?math=z">、<img src="https://render.githubusercontent.com/render/math?math=v"> 分别为入射带电粒子的电荷数和速度
- <img src="https://render.githubusercontent.com/render/math?math=NZ"> 分别为靶核的数密度及靶核的原子序数
- <img src="https://render.githubusercontent.com/render/math?math=\ln\frac{1}{1 - \beta^2}-\beta^2"> 为相对论修正项
- <img src="https://render.githubusercontent.com/render/math?math=-\frac{C}{Z}"> 为壳效应修正项
- <img src="https://render.githubusercontent.com/render/math?math=e">、<img src="https://render.githubusercontent.com/render/math?math=m_0"> 分别为电子的电荷和静止质量
- <img src="https://render.githubusercontent.com/render/math?math=c"> 为光速
- <img src="https://render.githubusercontent.com/render/math?math=\beta = \frac{v}{c}">
- <img src="https://render.githubusercontent.com/render/math?math=I"> 为靶原子的平均电离电位

(3) 重带电粒子阻止本领与粒子能量的关系曲线，以及曲线各部分对应的效应和对其描述的理论

![重带电粒子阻止本领与粒子能量的关系曲线](https://github.com/nuclear9725/RadiationDetectorQuestionPool/blob/f082515cc80dc7faf1fcb1fe8f7a52f3d50ca60a/image/dEdx%20-%20E.jpg)

| 曲线各部分 | 效应 | 理论 |
| -- | -- | -- |
| 1 | <img src="https://render.githubusercontent.com/render/math?math=\frac{z^2}{v^2}"> | 核阻止 |
| 2 | <img src="https://render.githubusercontent.com/render/math?math=v"> | LSS |
| 3 | <img src="https://render.githubusercontent.com/render/math?math=\frac{1}{v^2}"> | Bether-Block 公式 |
| 4 | <img src="https://render.githubusercontent.com/render/math?math=\ln\frac{1}{1 - \beta^2}"> | Bether-Block 公式 - 相对论修正 |

(4) dE/dx~E 曲线出现极大值的原因

- Bether-Block 公式描述的 <img src="https://render.githubusercontent.com/render/math?math=\frac{1}{v^2}"> 效应、与 <img src="https://render.githubusercontent.com/render/math?math=v"> 成正比的 LSS 理论描述的电子俘获以及壳修正共同作用的结果

**来源**：

- 带电粒子与靶原子碰撞的一般行为
  - PPT 讲义《绪论 射线与物质相互作用 (2)》P69
- Bether-Block 公式中各项的物理意义
  - 《核辐射探测器》，P21-22
- 重带电粒子阻止本领与粒子能量的关系曲线，以及曲线各部分对应的效应和对其描述的理论
  - PPT 讲义《绪论 射线与物质相互作用 (2)》P78
  - 课程 第 7 次课，视频 1 的 01:36 左右
- dE/dx~E 曲线出现极大值的原因
  - 课程 第 7 次课，视频 1 约 01:37:06 ~ 01:37:35 处

**讨论**：

- (2) 中 Bether-Block 公式中第 5-8 项的或许不需要写
- (3) 中曲线第 4 部份 "Bether-Block 公式 - 相对论修正" 对应的效应不一定是这么写
------

7. 简述 γ 射线与物质的三种主要相互作用，并说明这三种相互作用截面与靶物质核电荷数以及射线能量的数学关系，并用图示意之。

**答案正文**：

γ 射线与物质的三种主要相互作用分别为：

- 光电效应
  - 概念
    - 光子把全部能量转移给内层电子，形成光电子发射出去，光子本身消失。光子能量一部分用于光电子克服束缚的电离能，另一部分作为光电子动能
  - 总光电截面<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{ph}}">与靶物质核电荷数以及射线能量的数学关系
    - 非相对论 (<img src="https://render.githubusercontent.com/render/math?math=hv \ll m_0c^2">)：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{ph}} = \frac{5}{4} \sigma_K \approx \frac{5}{4}  Z^5 (\frac{1}{hv})^{7/2}">
    - 相对论 (<img src="https://render.githubusercontent.com/render/math?math=hv \gg m_0c^2">)：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{ph}} = \frac{5}{4} \sigma_K \approx  \frac{5}{4}  Z^5 \frac{1}{hv}">
- 康普顿散射
  - 概念
    - 入射光子一部分能量转移给靶核外层电子，使之电离成为反冲电子，而光子的运动方向和能量发生变化，成为散射光子。
  - 康普顿散射截面与靶物质核电荷数以及射线能量的数学关系
    - 低能 (<img src="https://render.githubusercontent.com/render/math?math=hv \ll m_0c^2">)：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{c}} \xrightarrow{hv \rightarrow 0} \sigma_{\text{Th}} = \frac{8}{3} Z \pi r_0^2">
    - 高能 (<img src="https://render.githubusercontent.com/render/math?math=hv \ll m_0c^2">)：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{c}} = Z \pi r_0^2 \frac{m_0c^2}{hv} (\ln{\frac{2hv}{m_0c^2}} %2B \frac{1}{2})">
- 电子对效应
  - 概念
    - 光子在原子核库伦场作用下，γ 光子转化为一个正负电子对
  - 电子对效应截面与靶物质核电荷数以及射线能量的数学关系
    - 能量稍大于<img src="https://render.githubusercontent.com/render/math?math=2m_0c^2">：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{p}} \propto Z^2E_\gamma">
    - 能量远远大于<img src="https://render.githubusercontent.com/render/math?math=2m_0c^2">：<img src="https://render.githubusercontent.com/render/math?math=\sigma_{\text{p}} \propto Z^2 \ln{E_\gamma}">

三种相互作用截面与靶物质核电荷数以及射线能量关系的示意图如下：
![三种相互作用截面与靶物质核电荷数以及射线能量关系的示意图](https://github.com/nuclear9725/RadiationDetectorQuestionPool/blob/5d70befc8ba154bd5a847f005a46f16c02c5eea3/image/%E6%8C%89%E5%85%89%E5%AD%90%E8%83%BD%E9%87%8F%E5%92%8C%E5%8E%9F%E5%AD%90%E5%BA%8F%E6%95%B0%E6%9D%A5%E8%A1%A8%E7%A4%BA%E7%9A%84%E4%B8%89%E7%A7%8D%E7%9B%B8%E4%BA%92%E4%BD%9C%E7%94%A8%E5%8D%A0%E4%BC%98%E5%8A%BF%E7%9A%84%E5%8C%BA%E5%9F%9F.jpg)

**来源**：

- γ 射线与物质的三种主要相互作用
  - 光电效应
    - PPT 讲义《绪论 射线与物质相互作用 (2)》P94-95
  - 康普顿散射
    - PPT 讲义《绪论 射线与物质相互作用 (2)》P96-97
  - 电子对产生
    - PPT 讲义《绪论 射线与物质相互作用 (2)》P99 
- 三种相互作用截面与靶物质核电荷数以及射线能量关系的示意图
  - PPT 讲义《绪论 射线与物质相互作用 (2)》P100

**讨论**：

- 虽然使用的图片与 "三种相互作用截面与靶物质核电荷数以及射线能量关系" 这一描述不严格相符，但老师说这里是八字图。

------

8. 请详细解释光电效应的发生为什么必须有“第三者”的参与。

**答案正文**：

若光电效应发生于真空中的自由电子，则无法同时满足能量守恒及动量守恒。因此，光电效应的发生必须有 "第三者" 的参与，"第三者" 受到一定的反冲，以满足动量守恒。

**来源**：

- https://en.wikipedia.org/wiki/Pair_production#Photon_to_electron_and_positron

**讨论**：

- 或许需要再详细一点

------

9. 分别示意画出 α、单能电子、γ 射线的吸收曲线，并分别解释 $I/I0=1/2$ 对应吸收片厚度的意义。

**答案正文**：

**来源**：

**讨论**：

------

10. 中子本身不带电，不能直接使物质电离，如何来探测和测量中子？简述各种方法的原理。

**答案正文**：

四种探测和测量中子的方法及其原理如下：
- 核反应法
  - 中子与原子核的反应中，中子与<img src="https://render.githubusercontent.com/render/math?math=^3\text{He}"> 、<img src="https://render.githubusercontent.com/render/math?math=^6\text{Li}"> 、<img src="https://render.githubusercontent.com/render/math?math=^{10}\text{B}"> 反应释放的能量较大，反应截面也很大，所以可以通过探测这三种反应来探测中子。
- 核反冲法
  - 能量为 E 的入射快中子和原子核发生弹性散射，将一部分能量和动量传递给原子核。中子能量减小、方向改变，原子核受到反冲而以一定的速度运动，被称为 "反冲核"。最后通过 "反冲核" 测量中子。反冲核质量越小获得能量越大，所以一般用氢反冲。
- 核裂变法
  - 中子与重核发生裂变反应，通过记录裂变碎片来测量中子。
- 活化法
  - 中子很容易发生 A(n,γ)B* 反应，其生成物不稳定，通常是一种放射性核素。这种放射性核素的放射性活度与中子通量密度成正比，因此通过测量它的放射性活度可以求得中子通量密度。

**来源**：

- 四种探测和测量中子的方法及其原理
  - PPT 讲义《绪论 射线与物质相互作用 (2)》P106-109
  - 《核辐射探测器》，P63-66

**讨论**：

------

11. 简述电流电离室的工作特性参数及其意义，如何选择其工作电压？

**答案正文**：

- 电流电离室的工作特性
  - 饱和特性
    - 实际的电流电离室其饱和区内的电离电流仍随电压升高而略为增大，表现在饱和区内有一定的斜率，一般以电压每百伏变化时，输出电流变化的百分率来量度。
  - 灵敏度
    - 电离室的灵敏度以单位强度的射线辐照下输出的电离电流来量度。
  - 线性范围
    - 线性范围指电离室输出电流与辐射强度保持线性关系的范围
- 如何选择工作电压
  - 辐射强度一定时，工作电压越高，线性范围越大。但过高的电压会引起放电等问题。应根据待测辐射确定线性范围，再选择恰当的工作电压。

**来源**：

- 电流电离室的工作特性
  - 《原子核物理实验方法 修订第三版》，P81-82
  - PPT 讲义《气体探测器》P20-21
- 如何选择其工作电压
  - 《原子核物理实验方法 修订第三版》，P82

**讨论**：

------

12. 为什么正比计数器和 G-M 计数器中央丝必须是阳极。为什么正比计数管的脉冲形状与入射位置无关。

**答案正文**：

- 为什么正比计数器和 G-M 计数器中央丝必须是阳极
  - 因为只有被阳极吸引的进入高电场区的电子才能倍增，而一定电压下以中央丝为阳极能在其附近产生更高强度的电场。另一方面，即使令中央丝为阴极，正离子也不足以发生雪崩。
- 为什么正比计数管的脉冲形状与入射位置无关
  - 因为脉冲形状主要由增殖电子离子对决定，原电离对脉冲贡献不大。而绝大多数增殖电子离子对产生于阳极丝附近很小范围内，所以正比计数管的脉冲形状与入射位置无关。

**来源**：

- 为什么正比计数器和 G-M 计数器中央丝必须是阳极
  - PPT 讲义《气体探测器》P23
  - 《核辐射探测器》，P95-96
- 为什么正比计数管的脉冲形状与入射位置无关
  - PPT 讲义《气体探测器》P27
  - 《核辐射探测器》，P96

**讨论**：

------

13. 叙述 G-M 计数器自猝息的机制，及其寿命的概念和影响因素。

**答案正文**：

- G-M 计数器自猝息的机制
  - 在单原子或双原子气体重加入少量的猝熄气体，使计数管在放电后自行猝熄。
  - 根据所用猝熄气体，可将自猝熄分为机制略有区别的两类：
    - 有机自猝熄
      - 吸收紫外光
      - 抑制正电子发射
    - 卤素自猝熄
      - 消除 Ne 原子压稳态妨碍电子增殖
      - 影响放电的终止与输出回路的参量
      - 卤素猝熄分子解离后会重新复合
- G-M 计数器的寿命
  - 概念
    - 计数管的寿命决定于猝熄气体的损耗。放电次数越多，猝熄气体含量越少。计数管在失去猝熄作用之前所能计数的次数，即为计数器的寿命。
  - 影响因素
    - 使用的猝熄气体类型
    - 使用计数管时施加的电压

**来源**：

- G-M 计数管自猝熄的机制
  - 《原子核物理实验方法 修订第三版》，P90-92
- G-M 计数管的寿命及影响因素
  - 《原子核物理实验方法 修订第三版》，P96-97

**讨论**：

------

14. 详细叙述 γ 射线从入射闪烁体到输出信号中的主要过程。（包括闪烁体中的次级过程，以及光收集和光电转换过程。）

**答案正文**：

- γ 射线进入闪烁体，使闪烁体的原子或分子激发，γ 射线损失能量。
- 闪烁体中受激发的原子或分子在退激时发射荧光光子。
- 利用反射物和光导将荧光光子尽可能多地收集到光电倍增管的光阴极上，由于光电效应，光子在光阴极上击出光电子。
- 光电子在光电倍增管中经多级倍增极倍增，数量由一个增加到 <img src="https://render.githubusercontent.com/render/math?math=10^4 \sim 10^9"> 个。
- 电子流在阳极负载上产生电信号，此信号由电子仪器记录和分析。

**来源**：

- PPT 讲义《闪烁体探测器》P44-49
- 《原子核物理实验方法 修订第三版》，P100
- 《核辐射探测器》，P103-104

**讨论**：

- 按老师课上的说法，这一题需包含 PPT 讲义《闪烁体探测器》P44-49 中的内容，即计算闪烁探测器的脉冲输出的一些式子，但上课时老师也说了这些式子不需要记。
------

15. 指出使用同样尺寸的塑料闪烁体、碘化钠、氟化钡和溴化镧闪烁体测量得到的0.662MeV γ 谱形状的不同之处，并定性分析其原因。（从总计数、峰康比、峰总比和能量分辨率方面回答）

**答案正文**：

以碘化钠为比较对象。
- 塑料闪烁体：碳氢化合物密度小、原子序数低， 0.662MeV γ  射线与之主要发生康普顿散射，只有康普顿连续谱，发光效率也低，所以总计数不如 NaI 高，谱形也不如 NaI 丰富。(NaI 有全能峰、康普顿坪、特征 X 射线峰、反散射峰等。)
- 氟化钡：光衰减时间最小，故探测效率高，总计数大。但是，它发光效率低，能量分辨率不高，谱形总计数多，但全能峰不明显。
- 溴化镧：晶体通常小于 NaI，导致峰总比较小，但能量分辨率好于 NaI，且具有更高峰康比。探测效率低于 NaI，因此谱形总计数较小，但全能峰明显好于 NaI。

**来源**：

- 《原子核物理实验方法 修订第三版》，P103、110、127

**讨论**：

- 答案来自上一届。
------

16. 为什么在一片硅片上（电阻率 1000Ωcm）的两个面上制备欧姆接触不能构成核辐射探测器？N 型高纯锗为什么比 P 型高纯锗探测器具有更高的抗辐照性能？平面型高纯锗为什么比同轴型高纯锗有更高的能量分辨能力？高纯锗探测器的探测效率主要是由什么决定的？N 型高纯锗为什么比 P 型高纯锗具有更低的能量探测下限？

**答案正文**：

- 为什么在一片硅片上（电阻率 1000Ωcm）的两个面上制备欧姆接触不能构成核辐射探测器？
  - 因为电阻率过低。如果在一片硅片的两个面上制备欧姆接触，在接触处不会产生载流子浓度的变化，不能形成没有自由截流子只有剩下固定杂质离化中心对电导没有贡献的耗尽区。
- N 型高纯锗为什么比 P 型高纯锗探测器具有更高的抗辐照性能？
  - 因为中子与锗相互作用时会形成空穴陷阱，这时对 N 型锗的影响要小些。
  - 当 γ 源照射 HPGe 的整个灵敏体积时，可以粗略地认为刚刚产生的载流子均匀地分布在灵敏体积中，由于从外面 算起的厚度为 ΔR 的灵敏体积比从里算起同样厚度 ΔR 的灵敏体积大，也就是说靠近外表面的载流子更多。对 N 型 高纯锗外面电极收集空穴，可以说大部分空穴漂移的距离比 P 型要小，因而被陷阱俘获的概率也要小。
- 平面型高纯锗为什么比同轴型高纯锗有更高的能量分辨能力?
  - 探测器的电容直接影响到噪声，从而影响到探测系统的能量分辨率。对同轴型高纯锗而言，同轴芯越细其电容越小。但受工艺条件的限制，同轴芯不可能做得太细，所以同轴型高纯锗电容较大，可达 40-50 pF 乃至更高。故平面型高纯锗比同轴型高纯锗有更高的能量分辨能力。
- 高纯锗探测器的探测效率主要是由什么决定的?
  - 高纯锗探测器的探测效率主要是由探测器的几何条件决定。
  - 一般来说，体积越大探测效率就越高，但也会受锗单晶的直径、长度及 P 层 (或 P 芯) 的直径等几何因素的限制。
- N 型高纯锗为什么比 P 型高纯锗具有更低的能量探测下限？
  - 能量探测下限与灵敏区体积和死层厚度有关。灵敏区体积一定时，死层越薄，能量探测下限越低。
  - P 型高纯锗入射窗是锂扩散层，死层较厚；而 N 型高纯锗的入射窗是 <img src="https://render.githubusercontent.com/render/math?math=\text{B}^%2B"> 离子注入层，死层较薄。所以N 型高纯锗比 P 型高纯锗具有更低的能量探测下限。

**来源**：

- 在一片硅片上（电阻率 1000Ωcm）的两个面上制备欧姆接触不能构成核辐射探测器
  - 《核辐射探测器》，P145
- N 型高纯锗为什么比 P 型高纯锗探测器具有更高的抗辐照性能
  - 《原子核物理实验方法 修订第三版》，P151
  - 《核辐射探测器》，P274
- 平面型高纯锗为什么比同轴型高纯锗有更高的能量分辨能力
  - 《核辐射探测器》，P254、P257
  - 《原子核物理实验方法 修订第三版》，P149
- 高纯锗探测器的探测效率主要是由什么决定的
  - 《核辐射探测器》，P260
- N 型高纯锗为什么比 P 型高纯锗具有更低的能量探测下限
  - 《核辐射探测器》，P254-255

**讨论**：

- "不能形成没有自由截流子只有剩下固定杂质离化中心对电导没有贡献的耗尽区" 或许应省略为 "不能形成耗尽区"。
------

17. 叙述半导体探测器，闪烁体探测器和气体探测器各自的特点和适用场合。

**答案正文**：

- 半导体探测器
  - 优点：能量分辨率高；高空间分辨，快时间响应；线性范围宽
  - 缺点：对辐照损伤灵敏，需要液氮温度冷却
  - 适用场合：能量测量、时间测量、计数测量
- 闪烁体探测器
  - 优点：时间相应快、探测效率高
  - 缺点：能量分辨较低、价格较高
  - 适用场合：应用最广的核探测型类型。可测带电离子和中性粒子；多用于时间测量、计数测量，也可用于低水平放射性与能谱测量；适用于高温场合
- 气体探测器
  - 优点：结构简单，使用方便可靠，成本低，可做很大
  - 缺点：能量分辨不高，响应速度慢，阻止能力差
  - 适用场合：传统类型逐步被取代，较多在工业上应用；新型气体探测器用于核物理、高能物理和宇宙射线探测

**来源**：

- 半导体探测器
  - PPT 讲义《半导体探测器》P2
- 闪烁体探测器
  - PPT 讲义《闪烁体探测器》P2
- 气体探测器
  - PPT 讲义《气体探测器》P2

**讨论**：

------
18. 用一台 NaI(Tl) 探测器测量 <img src="https://render.githubusercontent.com/render/math?math=\^{137}\text{Cs}"> 662 keV γ 谱。若已知平均光能产额 <img src="https://render.githubusercontent.com/render/math?math=\bar{Y_{\text{ph}}} = 4.37 \times 10^{-2}">，光收集效率 <img src="https://render.githubusercontent.com/render/math?math=F_{\text{ph}} = 0.35">，光电子收集效率 <img src="https://render.githubusercontent.com/render/math?math=g_c \sim 1">，量子效率 <img src="https://render.githubusercontent.com/render/math?math=\bar{Q_{K}} = 0.22">，光电倍增管第一打拿级 <img src="https://render.githubusercontent.com/render/math?math=\delta_1 = 25">，后面各级 <img src="https://render.githubusercontent.com/render/math?math=\delta = 6">，并认为 <img src="https://render.githubusercontent.com/render/math?math=\eta_T = \eta_I = 4\%25">，计算探测器的能量分辨率 <img src="https://render.githubusercontent.com/render/math?math=\eta">。

**答案正文**：

<img src="https://render.githubusercontent.com/render/math?math=\begin{align*}\eta_{\text{eM}}^2 %26= \frac{5.56}{\bar{n}_{\text{ph}} F_{\text{ph}} g_c \bar{Q}_{k}}  (1 %2B \frac{\delta}{\delta_1}\frac{1}{\delta-1})\\%26= \frac{5.56}{4.37 \times 10^{-2} \times 6.62 \times 10^{5} \times 0.35 \times 1 \times 0.22}(1 %2B \frac{6}{25}\frac{1}{6-1})\\%26= 0.00262\end{align*}">

<img src="https://render.githubusercontent.com/render/math?math=\begin{align*}\eta %26= \sqrt{\eta_{\text{eM}}^2 %2B \eta_{T}^2 %2B \eta_{I}^2}\\%26=\sqrt{0.00262 %2B 0.04^2 %2B 0.04^2}\\%26=7.63\%25\end{align*}">

**来源**：

- 《原子核物理实验方法 修订第三版》，P132

**讨论**：
题目更改(Y_ph )=4.37×10^4  (1⁄MeV)

------

19. <img src="https://render.githubusercontent.com/render/math?math=\^{14}\text{C}"> 的 β 射线源发射的 β 粒子的平均能量为 50 keV，活度为 5000 Bq（发射粒子个数/秒），置于充 Ar（<img src="https://render.githubusercontent.com/render/math?math=\omega_\beta = 26.4\text{eV}">）的 4π 电流电离室中，若全部离子能量都消耗在电离室灵敏体积内，求饱和电流。

**答案正文**：

<img src="https://render.githubusercontent.com/render/math?math=\begin{align*}I_{\text{S}} %26= \frac{E_0}{\omega_\beta} \times n \times q\\%26= \frac{5 \times 10^4}{26.4} \times 5000 \times 1.6 \times 10^{-19}\\%26= 1.515 \times 10^{-12} \text{A}\end{align*}">

**来源**：

- 《核辐射探测器》，P93

**讨论**：
题目更改(Y_ph )=4.37×10^4  (1⁄MeV)
------

20. 试根据 G-M 计数管的坪曲线选择工作电压，图示并叙述出起始电压、坪长和坪斜的概念。

**答案正文**：

**来源**：

- 

**讨论**：

------

21. 一个金硅面垒探测器 <img src="https://render.githubusercontent.com/render/math?math=\rho = 1000\Omega \cdot \text{cm}">，外加偏压 <img src="https://render.githubusercontent.com/render/math?math=100\text{V}">，灵敏区直径 <img src="https://render.githubusercontent.com/render/math?math=\varphi = 20\text{mm}">，试求灵敏区厚度和结电容。

**答案正文**：

灵敏区厚度：
<img src="https://render.githubusercontent.com/render/math?math=W \approx 0.5 \sqrt{\rho u} = 0.5 \sqrt{1000 \times 100} = 158.11 \mu m">

结电容：
<img src="https://render.githubusercontent.com/render/math?math=C_d \approx 210  \frac{S}{\sqrt{\rho u}} = 210  \frac{\pi \frac{\phi^2}{4}}{\sqrt{\rho u}} = 210  \frac{100\pi}{\sqrt{1000 \times 100}} = 208.63\text{pF}">

**来源**：
 
- 灵敏区厚度
  - 《核辐射探测器》，P172
- 结电容
  - 《核辐射探测器》，P188

**讨论**：

------

22. 下图为 HPGe 测量得到的 <img src="https://render.githubusercontent.com/render/math?math=\^{24}\text{Na}\text{-}\gamma">  能谱，请给出各部分的名称（不光是线状峰），简述其成峰原理。

**答案正文**：



**来源**：
 
- 

**讨论**：

------

23. 用 HPGe 探测器测量 1MeV 的 γ 射线，由于电子-空穴对的统计涨落引起的能量展宽是多少？已知：法诺因子 <img src="https://render.githubusercontent.com/render/math?math=F=0.13">，<img src="https://render.githubusercontent.com/render/math?math=\bar{\omega} = 2.9\,\text{eV}">。

**答案正文**：

由于电子-空穴对的统计涨落引起的能量展宽为：

<img src="https://render.githubusercontent.com/render/math?math=W \approx 0.5 \sqrt{\rho u} = 0.5 \sqrt{1000 \times 100} = 158.11 \mu m">

**来源**：
 
- 《核辐射探测器》，P255

**讨论**：

------

24. 叙述热释光探测器工作原理。

**答案正文**：



**来源**：
 
- 

**讨论**：

------

25. 叙述核乳胶的优缺点。


**答案正文**：

- 优点
  - 空间分辨率极高，可用于研究极短寿命粒子
  - 体积小
  - 轻便
  - 能将高能粒子的径迹永久保存
- 缺点
  - 根据径迹测量粒子能量时精确度较低
  - 无法形成电信号，径迹不便读取

**来源**：

- PPT 讲义《绪论 射线与物质相互作用 (2)》P45
- https://cerncourier.com/a/nuclear-emulsions/

**讨论**：

------
