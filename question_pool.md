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

**来源**：

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

- PPT 讲义《绪论 射线与物质相互作用(1)》P13

**讨论**：

------

4. 探测器的主要性能参数有哪些？并简述其概念。

------

5. 简单回答下列问题并给出理由：
  
  - 金硅面垒探测器是否适合测量 60Co 发射的 1173.2keV γ 射线的能量？

  - 气体电离室是否适合测量 60Co 发射的 1173.2keV γ 射线的能量？

  - 气体电离室的输出脉冲是电子和离子收集到电极上之后才形成的吗？

  - 闪烁体和光电倍增管之间的光学耦合剂可以用水来代替吗？

  - 半导体探测器是否适合使用电压灵敏前置放大器？

  - 探测器灵敏物质的对射线的平均电离能的含义是什么，其是否等于单个靶核原子的电离能？

  - 重带电粒子单位路程上产生的电子-离子对数目在整个路程上是均匀分布的吗？

  - 核阻止效应所损失的能量能否被电离型探测器探测？

  - 高能和低能 β 射线是否适合用含有重元素的探测器进行测量？

------

6. 简述带电粒子与靶原子碰撞的一般行为包括哪些，Bether-Block 公式
（<img src="https://render.githubusercontent.com/render/math?math=(-\frac{dE}{dx})_e = \frac{4 \pi z^2 e^4 NZ}{m_0 v^2}[\ln{(\frac{2m_0 v^2}{I})+\ln\frac{1}{1 - \beta^2}-\beta^2-\frac{C}{Z}}]">）
中各项的物理意义。为什么 dE/dx~E 曲线有极大值出现？重带电粒子阻止本领与粒子能量的关系曲线，并简述曲线各部分对应的效应，和对其描述的理论。

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

------

8. 请详细解释光电效应的发生为什么必须有“第三者”的参与。

------

9. 分别示意画出 α、单能电子、γ 射线的吸收曲线，并分别解释 $I/I0=1/2$ 对应吸收片厚度的意义。

------

10. 中子本身不带电，不能直接使物质电离，如何来探测和测量中子？简述各种方法的原理。

------

11. 简述电流电离室的工作特性参数及其意义，如何选择其工作电压？

------

12. 为什么正比计数器和 G-M 计数器中央丝必须是阳极。为什么正比计数管的脉冲形状与入射位置无关。

------

13. 叙述 G-M 计数器自猝息的机制，及其寿命的概念和影响因素。

------

14. 详细叙述 γ 射线从入射闪烁体到输出信号中的主要过程。（包括闪烁体中的次级过程，以及光收集和光电转换过程。）

------

15. 指出使用同样尺寸的塑料闪烁体、碘化钠、氟化钡和溴化镧闪烁体测量得到的0.662MeV γ 谱形状的不同之处，并定性分析其原因。（从总计数、峰康比、峰总比和能量分辨率方面回答）

------

16. 为什么在一片硅片上（电阻率 1000Ωcm）的两个面上制备欧姆接触不能构成核辐射探测器？N 型高纯锗为什么比 P 型高纯锗探测器具有更高的抗辐照性能？平面型高纯锗为什么比同轴型高纯锗有更高的能量分辨能力？高纯锗探测器的探测效率主要是由什么决定的？N 型高纯锗为什么比 P 型高纯锗具有更低的能量探测下限？

------

17. 叙述半导体探测器，闪烁体探测器和气体探测器各自的特点和适用场合。

------

……

------

25. 叙述核乳胶的优缺点。

------
