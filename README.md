# 机械电子工程
**机械电子学**（英语：mechatronics），又称**机电整合学**、**机电工程学**，是一门利用微电子理论来控制机械装置的学科，也是一门[交叉学科](https://zh.wikipedia.org/wiki/%E4%BA%A4%E5%8F%89%E5%AD%A6%E7%A7%91 "交叉学科")，它的技术基础是来自[机械制造](https://zh.wikipedia.org/wiki/%E6%9C%BA%E6%A2%B0%E5%88%B6%E9%80%A0 "机械制造")和[微电子控制](https://zh.wikipedia.org/w/index.php?title=%E5%BE%AE%E9%9B%BB%E5%AD%90%E6%8E%A7%E5%88%B6&action=edit&redlink=1 "微电子控制（页面不存在）")，并配合[电脑](https://zh.wikipedia.org/wiki/%E7%94%B5%E8%84%91 "电脑")[软件](https://zh.wikipedia.org/wiki/%E8%BD%AF%E4%BB%B6 "软件")。

![](readme.assets/Pasted%20image%2020230730223623.png)
## 光机电整合
光机电整合工程（英语：Optomechatronic Integration Engineering）就是在[微电子技术](https://zh.wikipedia.org/wiki/%E5%BE%AE%E7%94%B5%E5%AD%90%E5%AD%A6 "微电子学")向机械工业领域渗透过程中逐渐形成并发展起来的由[光学](https://zh.wikipedia.org/wiki/%E5%85%89%E5%AD%B8 "光学")、[光电子学](https://zh.wikipedia.org/wiki/%E5%85%89%E9%9B%BB%E5%AD%90%E5%AD%B8 "光电子学")、[微电子](https://zh.wikipedia.org/wiki/%E5%BE%AE%E7%94%B5%E5%AD%90 "微电子")、资讯和机械及其他相关技术交叉与融合而构成的综合性高新技术。

系统包括机械本体、电脑控制器、驱动装置（包括执行装置和传动机构）、感测器。
- 机械系统（本文档将着重讲解材料，力学，结构，运动，设计，仿真，制造，维护）
- [电子系统](https://github.com/LeroyK111/electricNote)（已经独立出去，作为单项进行学习）
这两块已经全栈：
- 控制系统（已经有自己的一套开发库）
- 电脑（[微控制器](https://zh.wikipedia.org/wiki/%E5%BE%AE%E6%8E%A7%E5%88%B6%E5%99%A8 "微控制器")， 已经有自己一套熟悉的嵌入式开发板）

## 结构

### 设计
离不开CAD，CAE等之类的工业开发软件。想想自己年轻时手绘机械图纸痛苦啊。 。。

#### 二维设计
Autodesk CAD

#### ★三维设计

SolidWorks   (入门简单，通用）
UG              （模具设计）
CATIA          （汽车，飞机曲面设计）
Proe/Creo   （电子产品）
### ★仿真

ANSYS workbench (入门最简单,轻松实现多物理场耦合)
热流体仿真:fluent, starccm
结构仿真：ANSYS, ABAQUS
前处理软件: ansa (最快捷,偏小众) , hypermesh, Icem (流体网格划分)

## 制造

### ★工艺流程

### 标准

### 模具

### 铸造

### 锻造

### 钣金

### 焊接

### 热处理

### 表面处理

## 维护
单独拿出来，是因为工程机械需要使用很久，好的维护可以增效降本，巩固安全。

### 润滑

### 清洗

### 降温

### 保温


## 材料
[塑料](材料/塑料.md) , 


### 化学处理

#### 电化学处理

#### 化学处理


### 立体化学

### 超分子化学

## 力学


### 固体力学


### 流体力学

#### 液压

#### 气压


### 热力学和热科学



## 控制论
控制论与[系统论](https://zh.wikipedia.org/wiki/%E7%B3%BB%E7%BB%9F%E8%AE%BA "系统论")和[信息论](https://zh.wikipedia.org/wiki/%E4%BF%A1%E6%81%AF%E8%AE%BA "信息论")一起在中国大陆学术界曾被称作“老三论”，是现代资讯技术的理论基础。
在[控制理论](https://zh.wikipedia.org/wiki/%E6%8E%A7%E5%88%B6%E7%90%86%E8%AB%96 "控制理论")中，**经典控制理论**（Classical control theory）是以[拉普拉斯变换](https://zh.wikipedia.org/wiki/%E6%8B%89%E6%99%AE%E6%8B%89%E6%96%AF%E5%8F%98%E6%8D%A2 "拉普拉斯变换")为分析工具，探讨有[控制系统](https://zh.wikipedia.org/wiki/%E6%8E%A7%E5%88%B6%E7%B3%BB%E7%B5%B1 "控制系统")之特性、以及[反馈](https://zh.wikipedia.org/wiki/%E5%8F%8D%E9%A6%88 "反馈")对系统特性的影响。

控制理论中常见的目标是要控制特定系统（称为[受控体](https://zh.wikipedia.org/wiki/%E5%8F%97%E6%8E%A7%E9%AB%94 "受控体")），使其输出可以依照控制信号（称为参考信号，可能是定值或是变动量）。为了实现此目的，会设计[控制器](https://zh.wikipedia.org/wiki/%E6%8E%A7%E5%88%B6%E5%99%A8 "控制器")来监控输出，并且比较输出和参考信号。实际输出和参考信号的差（称为误差信号）会[反馈](https://zh.wikipedia.org/wiki/%E5%8F%8D%E9%A6%88 "反馈")到控制器中，再由控制器产生受控体的输入信号，使受控体的实际输出接近参考信号。

经典控制理论主要处理[线性时不变](https://zh.wikipedia.org/wiki/%E7%BA%BF%E6%80%A7%E6%97%B6%E4%B8%8D%E5%8F%98%E7%B3%BB%E7%BB%9F%E7%90%86%E8%AE%BA "线性时不变系统理论")的[单一输入单一输出系统](https://zh.wikipedia.org/wiki/SISO%E7%B3%BB%E7%B5%B1 "SISO系统")[[1]],可以计算系统输入信号及输出信号的拉普拉斯变换，而系统的[传递函数](https://zh.wikipedia.org/wiki/%E4%BC%A0%E9%80%92%E5%87%BD%E6%95%B0 "传递函数")和输入信号及输出信号的拉普拉斯变换有关。

### 经典控制论。
钱学森的一书足以概括《工程控制论》
常用工具：[根轨迹图](https://zh.wikipedia.org/wiki/%E6%A0%B9%E8%BB%8C%E8%B7%A1%E5%9C%96 "根轨迹图")、[奈奎斯特稳定判据](https://zh.wikipedia.org/wiki/%E5%A5%88%E5%A5%8E%E6%96%AF%E7%89%B9%E7%A8%B3%E5%AE%9A%E5%88%A4%E6%8D%AE "奈奎斯特稳定判据")、[波德图](https://zh.wikipedia.org/wiki/%E6%B3%A2%E5%BE%B7%E5%9C%96 "波德图")、[增益裕度](https://zh.wikipedia.org/wiki/%E5%A2%9E%E7%9B%8A%E8%A3%95%E5%BA%A6 "增益裕度")及[相位裕度](https://zh.wikipedia.org/wiki/%E7%9B%B8%E4%BD%8D%E8%A3%95%E5%BA%A6 "相位裕度")等。

#### 基本系统 
线性系统，非线性系统

#### 拉氏变换
拉氏变换法。拉氏变换解常系数常微分方程。
![](readme.assets/Pasted%20image%2020231227180954.png)

#### 函数和图
输入、输出和传递函数。波德图、奈奎斯特图；一阶系统、二阶系统；频率响应，超越传递函数。

![[readme.assets/Pasted image 20230730235044.png]]



#### 反馈伺服系统

#### 不互相影响的控制


#### 交流伺服系统与振荡控制伺服系统


#### 采样伺服系统


#### 有时滞的线性系统

#### 平稳随机输入下的线性系统

#### 继电器伺服系统

#### 非线性系统

#### 变系数线性系统

#### 利用摄动理论的控制设计

#### 满足指定积分条件的控制设计

#### 自动寻求最优运转点的控制系统

#### 噪声过滤的设计原理

#### 自行镇定和适应环境的系统

#### 误差的控制


### 现代控制论
“现代控制理论”的主要内容是“多输入多输出（Multi-input Multi-output, MIMO）的线性控制理论”。自动控制原理属于经典控制理论，基于传递函数来分析单输入、单输出（Single-input Single-output, SISO）系统；

而现代控制理论在此基础上扩展为，用状态空间方程（state space equation）分析多输入、输出的关系。也许因为这种分析方法更有普适性，更“高级”，所以被冠以了“现代”的名号。

1. 分析对象与系统方程
2. 系统的“五性”：稳定性、可控性、可稳定性、可观性、可检测性
3. 状态反馈稳定控制
4. 基于观测器的状态反馈稳定控制
5. 总结

#### 分析对象与系统方程

现代控制理论的分析对象是有限维线性时不变动态系统（a finite dimensional linear time invariant (FDLTI) dynamical system）。[线性时不变(LTI)系统](https://zhuanlan.zhihu.com/p/337275713)在[自控系列文章](https://zhuanlan.zhihu.com/p/336048279)中提到过，具备齐次性、线性和时不变特性，这里在LTI基础上增加“有限维”做定语。
明确对象后，用线性常微分方程（linear constant coefficient differential equations）来刻画系统。
![[readme.assets/Pasted image 20230730232649.png]]
式中x表示状态变量，u表示系统输入，y表示系统输出。“时不变”在方程中的体现就是A、B、C、D是常数矩阵，不随时间变化。上式也叫状态空间方程（state space equation），因为它刻画了系统状态随输入的演变情况。

状态空间方程是一阶方程组，对于实际的高阶系统，可以通过设置中间变量将其写成一阶形式，因此上述方程可以刻画高阶系统。另外，状态空间方程也能写成传递函数的形式。将状态空间方程进行拉普拉斯逆变换，第一行变换后可以用x表示u，代入第二行，就能得到 Y(s)/U(s)，即传递函数G(s)，此处X, Y都是矩阵形式。
![[readme.assets/Pasted image 20230730232705.png]]
#### **五性**

##### **1. 稳定性：Stability**
对于零输入系统， ![[readme.assets/Pasted image 20230730232840.png]]，稳定性的 判据是：**A的特征值的实部都在复平面左半平面。**

可以借助传递函数理解：
![[readme.assets/Pasted image 20230730232826.png]]
分母部分恰好是求A的特征值的公式，也刚好对应了传递函数的极点，因此可以用来判断稳定性。极点在复平面左半平面含义在自控[判断稳定性文章](https://zhuanlan.zhihu.com/p/350582223)中有详细讲解，这里不赘述。

##### **2. 可控性：controllability**

可控性的判据是**可控性矩阵 ![[readme.assets/Pasted image 20230730233435.png]]满秩**，对应的Matlab语句是：

```text
rank(ctro(A, B))
```

系统可控意味着可以通过反馈来进行任意的极点配置(The eigenvalues of A+BF can be freely assigned)。当系统输入 ![[readme.assets/Pasted image 20230730233452.png]]时，用于稳定性判断的A矩阵就变成了A+BF，当A+BF能任意配置极点时，可以让状态空间方程 ![[readme.assets/Pasted image 20230730233459.png]]有特定的解，达到控制系统的目的。

##### **3. 可稳定性：stabilizability**

这里可稳定性含义是，存在状态负反馈使得系统稳定，即state feedback stabilizability。判据是：**任意实部大于0的A的特征值 � ，矩阵 ![[readme.assets/Pasted image 20230730234135.png]]行满秩。

两个注意点：

- 可控性和可稳定性的关系：可控一定是可稳定的，因为可以任意配置A+BF的极点；可稳定但不一定可控，当不可控的模态本身是稳定（实部小于0）时，系统不可控，但是是可稳定的。
- state feedback stabilizability需要区别于output feedback stabilizability。后者的控制信号u来源于输出y；而前者来源于系统状态x，叫系统状态反馈。

##### **4. 可观性：Observability**

可观测性的含义是：是否可以**通过系统输入和输出来得到系统的状态**，只有系统是可观测的，才能设计观测器来实时观测（预测）系统状态。可观测性的判据是：可观测性矩阵![[readme.assets/Pasted image 20230730234201.png]]O列满秩 。对应的Matlab语句是：

```text
rank(obsv(A, C))
```

上述判据的等价描述是： **![[readme.assets/Pasted image 20230730234218.png]] 的极点可以任意配置**。背后的含义是：观测器的模拟的系统是具备可稳定性，能持续提供观测功能。观测器是原系统方程的复制，其状态方程是：

![[readme.assets/Pasted image 20230730234212.png]]
![[readme.assets/Pasted image 20230730234229.png]]

##### **5. 可检测性：Detectablility**

根据可控性和可观性是对偶的，同理，可检测性是可稳定性的对偶概念，含义是：**观测器系统是不是可稳定的**。判据是：**任意实部大于0的A的特征值** � **，矩阵** ![[readme.assets/Pasted image 20230730234240.png]]**列满秩。**

##### **6. 小结**

现代控制理论基于状态空间方程来分析系统。相比经典控制理论主要关注的稳定性，现代控制理论补充了四个特性：**“可控性、可稳定性、可观性、可检测性**”**，它们都是围绕稳定性展开。其中，可控性和可观性对偶，可稳定性和可检测性对偶；可控性、可稳定性描述的是引入状态反馈后的原系统；可观性、可检测性描述的是引入观测误差后的观测器系统。

#### 状态反馈稳定控制（State feedback stabilizing control）

自控里我们通过反馈来达到“自动”和“稳定”的目的。在现代控制里也一样，当输入u= Fx 时，反馈的量是系统状态x，因此叫做状态反馈控制。需要指出，自控里反馈一般是基于y，即输出的负反馈，与这里的状态反馈不同。

此外，本节的设计只是为了**稳定系统**，所以叫stabilizing control，这是为了呼应上面提出的四个特性，四个特性都围绕“稳定”展开。稳定是tracking的前提，要想使系统具备追踪特定信号的能力，需要此基础上添加新的控制策略。

下面进入状态反馈稳定控制器的设计，用如下两幅图直观表示。

![](https://pic4.zhimg.com/80/v2-14675701850fee819c8b1aea724f3697_1440w.webp)

图 1 基于状态方程的系统框图

![](https://pic4.zhimg.com/80/v2-b62174dec8141ee1271826ebabea8f6f_1440w.webp)

图 2 基于状态反馈稳定控制器
![[readme.assets/Pasted image 20230730234354.png]]

#### 基于观测器的状态反馈稳定控制

上一小节假设系统状态量可测，当状态量 X 不可测时就需要使用观测器了。观测器在可观性处有涉及，它复制了一遍系统的状态空间方程，并用预测的系统输出和实际系统输出来修正，直到误差为0。其框图如下，可以清晰地看到可观性矩阵的来源。

![](https://pic3.zhimg.com/80/v2-2d7a4a29d304db39ef9176571cd81cea_1440w.webp)

![[readme.assets/Pasted image 20230730234418.png]]

![](https://pic4.zhimg.com/80/v2-e5d61d91b5b5b35785e59864994a01a3_1440w.webp)

图 4 基于观测器的系统稳定控制器

#### **总结**

本文讲述了现代控制理论的一些基本概念，包括：分析对象与系统方程、系统的“五性”、状态反馈稳定控制、基于观测器的状态反馈稳定控制。这些概念相互关联，前后呼应。

系统状态空间方程刻画了系统状态、输出与输出的关系；方程中的矩阵A蕴含了系统的稳定特征，A与B结合反映了可控性、可稳定性，A与C结合反应了可观性、可检测性；进一步，这些特性指导了稳定控制器的设计；而设计的合理性又回归到方程来印证。

从实际抽象出理论（数学建模：系统方程），理论指导实践（模型应用：控制器设计），实践印证理论（证明模型的合理性），这种融会贯通后的循环，大概就就是做工程的“美学”。


## 电机
电机控制是工程师绕不开话题，合格的工程师在设计之前，一定对整个电机控制拥有丰富的心得体会。本文从同步、定时和软件三方面，详细梳理电机控制的流程及组成，并分享工程师在实际工作中的经验。

### 同步和定时

每个实时应用程序的首要任务是适当的定时、同步和确定性的系统响应，设计电机控制软件时必须特别注意这些方面。 从本质上讲，该过程听起来非常简单：系统读取传感器值、处理控制算法、监控系统安全并通过调整 PWM 输出的占空比来管理输出级。

微小的时序错误可能会导致严重的系统响应错误、运行不稳定和性能不佳。 为了确保一切按预期运行，保持同步并确保系统的确定性至关重要。 在这里，我要强调的是，我们正在处理一个“硬实时系统”，在严格的期限内完成任务绝对至关重要。

电机控制器软件可以使用合适的 RTOS（实时操作系统）作为没有操作系统的裸机解决方案来实现，或者作为多核混合解决方案来实现，其中一些 CPU 内核在裸机模式下运行，而其他内核则使用一个操作系统。 裸机解决方案始终基于中断驱动设计，其中中断处理时间关键型任务，确保一切都以精确的时间间隔发生。

无论是裸机、RTOS 还是混合解决方案，都必须执行时序分析、任务优先级划分和安全分析，以确保高效可靠的系统性能。

时序分析可确保所有任务均按时完成。 这包括考虑每个任务的最坏情况执行时间。 电机控制中的一些主要关键任务包括传感器数据采集、通过 PWM 信号生成执行控制算法、故障检测和处理、紧急停止和安全功能、与其他系统组件的实时通信以及与外部系统的同步。


### **锁相环**
如前所述，锁相环 (PLL) 无论是集成到 MCU/DSP 硬件中还是作为 FPGA 中的 IP 核实现，对于同步关键事件都至关重要。PLL 的主要功能是将 MCU/DSP/FPGA 的内部时钟与外部时钟源或信号同步。 这对于保持实时应用中的计时精度至关重要。PLL 有助于减少时钟抖动，这对于精确定时至关重要，在控制电机的速度和位置时尤其重要。PLL 可确保反馈信号采样（例如转子位置和电流测量）与控制算法执行之间的精确时序对齐，从而确保最佳同步和精度。 在多核系统中，PLL 可用于同步这些内核的操作。

通过锁相环 (PLL) 将脉冲宽度调制 (PWM) 与电流测量和模数转换 (ADC) 同步对于电机控制应用中确保精确高效的系统性能至关重要。 通过同步时钟，PLL 可确保所有系统组件（包括 PWM 发生器、ADC 和其他处理元件）在同步时钟上运行。 控制输送到电机的功率的 PWM 信号是根据该同步时钟生成的。 这些信号的时序直接影响电机性能。 电流传感器测量电机的电流。这些测量的时机至关重要，特别是在磁场定向控制 (FOC) 等系统中，其中电流反馈用于控制电机扭矩和速度。 使用 ADC 将电流传感器的模拟信号转换为数字值。PLL 有助于将 ADC 采样与 PWM 周期同步。 这种同步可确保 ADC 在相对于 PWM 信号的最佳时间（通常是在 PWM 既不完全开启也不完全关闭的点）对电流进行采样，以获得准确的电流。 然后将数字化的电流测量值输入控制算法中。PLL 确保以相对于 PWM 信号一致的间隔进行测量，使控制算法能够根据状态变量的变化精确修改 PWM 占空比，从而确保最佳电机性能。 通过将 ADC 采样与 PWM 同步，可以最大限度地减少开关噪声和失真的影响。 这在高功率电机控制应用中尤其重要，因为 PWM 信号可能会产生显着的噪声。


### **电流和位置测量**
准确测量电流并使其与 PWM 脉冲同步至关重要。 使用定期采样、电流过采样和平均等技术来提高精度。

定期采样的频率与 PWM 的频率相同，因此挑战是确定适当的采样时间。 这涉及到在 PWM 周期开始和模数转换之间设置合适的延迟。

电流过采样涉及以高于 PWM 频率（有时高 8-32 倍）的频率进行采样并对测量结果取平均值。ADC 中断服务例程 (ISR) 频率可以远高于 PWM 频率，从而可以收集详细的数据。

过采样受到电流传感器带宽的限制。 例如，大多数通常用于电机控制的霍尔传感器的带宽在 50 kHz 到 160 kHz 之间。 正确定时和同步是处理影响相电流高频振荡的关键。
![[readme.assets/Pasted image 20240412155935.png]]
图 1 显示了一个处理周期中的时序。 模数转换器 (ADC) 可配置为高频采样。 这需要设置 ADC 时钟并调整其采样率。 采样完成后，MCU或DSP处理这些样本以计算其平均值。 该计算通常在累积特定数量的样本后执行。 主处理中断服务程序 (ISR) 必须配置为在平均计算完成时触发。 此外，PWM模块的设置方式需要确保 ADC 采样、ISR 和 PWM 时序之间的同步。 现代 MCU 和 DSP 凭借其强大的处理能力、实时操作能力以及为管理 ADC、PWM 和 ISR 任务而设计的各种外设，擅长同时处理这些任务。

位置传感器数据的采样与主处理中断服务程序同步至关重要。 而且考虑数据传输引起的任何延迟，并且可以计算这些延迟以保持定时准确性。 应用任何滤波器时，重要的是要考虑相位延迟的影响。 在使用旋转变压器测量角速度的情况下，旋转变压器数据的处理必须是同步的，并且必须选择正弦和余弦信号幅度最小的点，以确保读数准确。此外，对旋转变压器信号进行过采样，并应用截止频率与 PWM 频率相匹配的带通滤波器。 这种方法有助于滤除不需要的频率，同时保持信号的完整性。

在高速系统中，必须推断位置以确保转子的准确性，从而使定子磁场相对于转子磁场正确对准。 精确的角度测量可确保在任何给定时间为电机提供适量的功率，从而减少能量损失、扭矩脉动、振动和发热。

本讨论主要集中于利用直接转子位置测量的磁场定向控制 (FOC) 应用。 它没有深入研究无传感器 FOC 应用，因为其中转子位置不是直接测量的，而是通过间接方法估计的。

### **安全功能**
  
电机控制应用中常见的一些常见安全功能包括：

**安全扭矩关闭 (STO)：**此功能立即切断电机驱动器的电源，使电机停止产生扭矩。 在紧急情况下，当需要尽快停止电机以防止伤害时，这是一个至关重要的功能。

**安全方向 (SDI)：**防止电机沿意外方向运行。

**安全操作停止 (SOS)：**此功能可在不切断电源的情况下使电机保持在停止状态。

**安全速度范围 (SSR) 或安全限速 (SLS)：**确保电机在安全速度范围内或低于安全最大速度运行。

**过流保护：**此功能可保护电机和电子设备免受因短路或过载等故障引起的过电流损坏。

**过压和欠压保护：**这些功能可防止电压过高或过低，从而损坏电机或控制电子设备。

**热保护：**监控电机和驱动器的温度，如果温度超过安全限值，系统可以关闭以防止过热。

**速度监控和限制：**确保电机不超过预定义的速度限制，这对于超过特定速度可能会产生危险的应用至关重要。

**紧急停止：**物理按钮或开关，可以立即使电机停止。 这是工业应用中必须的标准功能。

**安全制动控制：**对于配备制动器的电机，此功能可以安全地接合制动器以停止电机，特别是在重力作用下会垂直移动的应用中。 在激活安全制动功能之前，系统首先尝试使用电气制动来停止电机（如果可行），在此过程中，能量流被反转以使电机减速。

安全功能可以通过硬件 (HW)、软件 (SW) 或两者的组合来实现，具体取决于应用的具体要求和限制。 过压和欠压保护、过流保护、热保护和紧急停止等安全功能通常在硬件中实现，以确保强大、快速和可靠的系统保护。

速度监控和限制、故障检测算法和安全操作停止 (SOS) 则在软件中实现。

安全扭矩关闭 (STO)、安全方向 (SDI)、安全速度范围 (SSR)/安全限速 (SLS) 和安全制动控制等功能通常通过硬件和软件组合来实现。 这种混合方法通常涉及用于启动和控制的软件命令，同时依靠硬件组件来有效执行和执行。

电机控制中的安全设计和功能安全主题（包括 SIL3 等标准）则是另外一个专门的主题。

嵌入式系统和电机控制领域的各种制造商提供全面的设计包和工具，旨在促进和加速工业、交通、能源和医疗等关键领域的设计和认证流程。 这些软件包通常包括预先认证的软件库、详细的安全手册以及旨在符合 IEC 61508、ISO 13849 等严格安全标准的硬件模块。 此外，他们还经常提供广泛的文档和支持，以实现 SIL（安全完整性等级）评级等认证，这对于高可靠性和安全关键型应用至关重要。 这种帮助不仅简化了开发流程，而且还显着减少了这些高度监管行业的合规性和认证所需的时间和精力。


### **实时操作系统（RTOS）**
为电机控制应用选择正确的 RTOS 对于确保高性能、可靠性和安全性至关重要。 主要考虑因素包括 RTOS 的实时性能、资源效率（包括内存占用和 CPU 使用率）以及基于优先级的抢占式调度处理。 高效、快速的中断以及系统的可靠性和鲁棒性也是关键因素。 供应商支持和文档、与硬件的兼容性以及开发工具（如 IDE、调试器和分析器）和生态系统（包括库和代码示例）的可用性发挥着重要作用。 最后，还应考虑 RTOS 的许可条款和成本。

考虑到电机控制应用的各种因素和具体要求，FreeRTOS 这一广受好评的开源实时操作系统以其效率和多功能性而闻名，成为一个出色的选择。 在成本效益、运营效率、系统灵活性、可靠性和鲁棒性、易用性、广泛的硬件支持和资源效率等方面是关键考虑因素的场景中，这种选择特别有益。
![[readme.assets/Pasted image 20240412160021.png]]

电机控制应用的架构包括多个层和模块：

**硬件抽象层 (HAL)：**提供用于访问硬件外设（包括 ADC、PWM 控制器和通信接口）的标准化接口，促进可移植性和可扩展性。 它还包含板支持包 (BSP) 和各种硬件外设的驱动程序，从而实现无缝的硬件软件集成。

**核心实时运行层：**该层包含实时操作系统 (RTOS)，用于高效的任务调度和系统资源管理。 它还包括专门的内存管理，具有实时堆分配器，专为优化时间关键型应用程序中的内存分配而设计。 此外，该层集成了强大的内核间和进程间通信（IPC）机制，促进系统内不同内核和进程之间的无缝数据交换和同步。 该层作为核心操作功能的支柱，确保平稳高效的运行时性能。

**中间件层：**该层集成了如下几个关键功能：

  

- 通信接口：使用各种通信协议管理与外部系统或设备的交互。
    
- 跟踪和数据记录：专注于跟踪和记录特定的信号和事件，能够通过DAC、IO、以太网、UART、USB等通道实时输出数据。
    
- 软件上传：监督新软件版本或更新的上传，确保无缝集成和系统连续性。
    
- 配置管理：处理客户的系统配置设置优化和操作调整。
    
- 诊断和监控：提供系统诊断和持续监控工具，这对于维护系统健康和性能至关重要。
    
- 内置测试 (BIT)：包括自测试功能，用于检查硬件和软件组件的状态和功能。
    

  

**电机控制应用层：**位于所有层的顶端是电机控制应用程序，它是执行特定于应用程序的工作流程的关键组件。 该层封装了：

  

- 控制和信号处理算法：这包括 PID 控制和磁场定向控制 (FOC) 等核心控制算法，以及旨在优化电机性能的信号处理算法。
    
- 安全逻辑：该组件致力于系统的安全方面，针对紧急情况和例行安全检查实施必要的协议，确保系统在安全参数内运行。
    
- 应用特定的工作流程：该层还集成了根据电机控制应用的特定要求定制的附加、独特的工作流程，确保全面的功能和性能。

### **应用程序工作流程**
应用程序工作流程通常涉及几个关键步骤：

**第一阶段引导加载程序 (FSBL)：**这个重要组件负责引导过程的初始阶段，包括低级硬件初始化和加载主要软件组件。 其作用的一个关键部分是加载和启动用户应用程序。FSBL 与应用层分开运行，通常由MCU或DSP在其SDK中提供。 通常需要定制BSP，例如添加额外的内存检查或诊断功能，以确保 FSBL 满足特定的系统要求并增强整体可靠性。

**平台设置：**硬件组件的初始化：这包括设置 ADC（模数转换器）、系统中断、PWM（脉宽调制）模块、通信接口（如 SPI、I2C、UART）、看门狗定时器和任何其他必要的硬件外围设备。 设置中断处理机制以响应定时器溢出/输入更改或通信等事件。 配置系统时钟、电源模式，并确保控制器和电机的高效电源管理。

**应用程序配置：**此步骤包含定义操作参数的关键任务，这通常是通过读取配置文件来实现的。 这些文件指定了电机特性、控制参数和操作限制等基本细节。 此外，配置设置可以通过各种方式进行调整，包括数字输入、DIP 开关，或通过外部 PC 或主设备的通信接口进行动态调整。 这种多方面的方法可确保灵活且适应性强的配置管理，满足广泛的应用程序需求。

这一阶段还包括：

- 定义任务：创建主控制任务、通信任务、运行状况监控任务等任务，这些任务对于应用程序的功能至关重要。
    
- 设置优先级：根据这些任务在应用程序中的重要性和作用为这些任务分配优先级。 这对于确保关键任务（如主控制任务）比不太关键的任务获得必要的 CPU 响应至关重要。
    
- 配置任务属性：这可以包括设置堆栈大小、指定任务参数以及配置任何特定于任务的属性。
    
- 建立任务间通信：建立任务间通信的机制，例如队列、信号量或共享数据结构。
    

  

**传感器校准：**在传感器集成的应用中，其校准对于确保读数的准确性至关重要。 具体来说，常用的霍尔效应传感器表现出必须考虑的初始偏移。 在校准阶段，这些初始偏移被识别并随后从电流测量中减去以校正传感器输出。 此步骤对于保证传感器数据的精度至关重要。

通信和监控：处理与外部设备或系统的通信，以进行命令和控制、诊断或远程监控。

### **人机界面 (HMI)**
在电机控制应用中，HMI 可以表示简单的物理控件和指示器（例如按钮、LED 或显示器）或远程控制接口。

这部分工作流程包括：

传感器数据采集：实时读取和处理来自传感器的数据，这是控制回路反馈所必需的。

  

- 实时控制循环执行：这是执行主要控制算法（如 PID 控制或FOC）的地方，通常在主控制器中执行。响应定时器中断以获得一致的定时。
    
- 执行器命令生成：根据控制算法的输出，为电机驱动器等执行器生成命令。 它通常涉及设置特定的数字输出和 PWM 信号生成。
    
- 安全和紧急情况处理：为了确保立即响应安全和紧急事件（例如紧急停车），应在这个专用阶段按顺序并高度优先地处理这些事件。 这种方法不仅最大限度地减少了处理关键事件的延迟，而且还增强了系统的整体安全性和可靠性。 此外，此阶段还包括检测和响应各种类型的故障，包括过流、过压和硬件故障。 通过对这些任务进行优先级排序，系统能够更好地及时解决和减轻潜在风险，从而确保更安全的操作环境。
    

关键原则是维护一个简洁的中断服务例程（ISR），主要用于在需要进一步处理时通知主控制任务。 它的主要作用不是执行 ISR 内的整个控制逻辑，而是通知更高优先级的任务有关事件的发生。 为此，FreeRTOS 提供了各种通知方法，例如二进制信号量、任务通知或队列。 主控任务是一个RTOS任务，负责主控算法。 一旦收到 ISR 通知，该任务就会激活（或解锁）并执行前面描述的所有必要步骤。 为主控制任务分配适当的优先级以确保控制算法在 ISR 之后及时处理至关重要。

应使用看门狗定时器来确保主任务的运行，该任务被设计为定期重置看门狗定时器，展示其正确操作并防止定时器到期并触发系统重置或错误例程。

**系统健康监控：**持续监控系统是否存在过热或其他异常等故障，并在检测到任何问题时采取适当的措施。

**日志记录和数据记录：**记录重要事件、错误和系统性能指标，以供将来分析或故障排除。

![[readme.assets/Pasted image 20240412160103.png]]
**正常关闭：**确保应用程序停止时电机和控制器安全关闭。

如果应用程序运行在多核MCU/DSP/FPGA上，则必须确保适当的核间通信机制。 这可以使用片上共享 RAM 和软件中断来实现，但方法可能会因平台而异。 其他可能性包括消息传递接口、直接内存访问 (DMA) 通道或使用特定于架构的专用硬件通信块。

一种常见的方法是让一个内核专门处理通信任务，另一个内核用于主控制循环。 通常在两个内核上使用 RTOS 来实现高效的任务管理，但主控制内核通常在裸机环境中运行，以实现简化的低级控制。 包括德州仪器 (TI) 的CLA、ARM 的 Cortex-M DSP 扩展、意法半导体的 ART 加速器、Microchip 的 dsPIC、恩智浦 (NXP) 的电机控制协处理器以及英飞凌 (Infineon) 的 XMC 数字协处理器，都提供专门的处理单元， 以增强特定嵌入式系统应用的性能。 此类扩展增加了整体计算带宽，并释放 CPU 来执行其他任务，例如通信、监控和诊断。

### GaN 氮化镓加速电机驱动
无刷直流电机（BLDC）在机器人、电动工具、家电和无人机中的应用越来越多。这些应用要求设备具备轻便、小巧、低转矩脉动、低噪音和极高的精度控制。为了满足这些需求，驱动电机的逆变器需要以更高频率运行，同时需要先进的技术来减少由此产生的更高功率损耗。  

氮化镓（GaN）晶体管和集成电路能够在不显著增加损耗的情况下以更高频率运行，相比于基于硅的设备，它们能够显著降低成本、噪音、尺寸和重量。也正因此，GaN在电机驱动领域展现出了巨大的潜力。

同时，在快充市场，GaN早已被广泛使用，也证明了其足够的安全可靠性。

#### **GaN在电机驱动中的基本优势**

GaN相比传统硅具有显著的优势，包括更高的电子迁移率、更高的击穿电压和更低的导通电阻。这些特性使得GaN器件能够在更高频率下工作，同时降低功率损耗。

**高效率：**GaN器件的导通损耗和开关损耗显著低于传统硅器件。例如，TI的DRV7308 GaN IPM可以将逆变器效率提高到99%以上，而传统的IGBT解决方案只能达到97%。
![](readme.assets/Pasted%20image%2020240710204326.png)
**高功率密度：**GaN器件允许更高的开关频率，减少了被动元件的尺寸，从而提高了系统的功率密度。DRV7308 GaN IPM的封装尺寸仅为12mm x 12mm，比传统250W IPM小55%，可以将PCB尺寸减少65%以上。
![](readme.assets/Pasted%20image%2020240710204346.png)

**更好的热管理：**由于GaN器件的低功率损耗，许多应用中可以不需要散热器，同时进一步减小系统尺寸和成本。

**高频率操作：**GaN器件能够在高达3 MHz的频率下工作，满足高精度控制和低扭矩波动的要求。

**集成化设计：**例如，EPC2152 GaN ePower Stage集成了两个70V、10mΩ的FET和一个自包含的半桥栅极驱动器，极大地减少了公共源电感（CSI）和栅极环路电感。而TI的DRV7308 IPM则包含了六个FET和其他保护及驱动电路。

![](readme.assets/Pasted%20image%2020240710204356.png)
**降低成本：**由于GaN器件的高效率和高功率密度，系统设计可以更紧凑，从而减少PCB和散热器的成本。例如，在一个250W的HVAC压缩机系统中，使用DRV7308 GaN IPM可以节省超过2美元的系统成本。

#### **使用 GaN 消除电机驱动设计中的死区时间**
![](readme.assets/Pasted%20image%2020240710204418.png)
如图所示，GaN在BLDC上的优势可以分为两部分，一个是更高的效率，另外则是更低的死区时间。

在电源转换领域，死区时间是设计中必不可少但又繁重的方面，迫使工程师做出让步以确保可靠性。然而，最近的技术进步，尤其是GaN FET 的出现，可以降低死区时间，同时提升电机驱动器的性能。
```
死区时间是指关闭一个功率器件和打开另一个功率器件之间的延迟，这对于防止同时导通和潜在短路至关重要。例如，在同步降压转换器中，两个器件同时导通可能导致额外的损耗、更高的工作温度，甚至灾难性的故障。

控制死区时间由控制器插入，可确保正有效死区时间。计算此死区时间是一个复杂的过程，需要考虑传播延迟、栅极电阻值和 FET 开启/关闭时间等因素。由于 GaN 器件没有体二极管反向恢复且开关时间更快，因此与硅 MOSFET 相比，GaN 器件的死区时间更短。
```

**电机驱动死区时间**
死区时间的一个主要影响是零电流交叉期间失真增加。这是因为在死区时间内，逆变器支路中的高端和低端设备都处于关闭状态，因此施加到电机的实际电压取决于电流的符号。在零电流交叉处，该电压突然改变符号，产生电压失真，导致电机电流波形中出现高阶谐波。这些电流不会产生任何有用的扭矩，但会导致电机绕组损耗增加，整体效率降低。
![](readme.assets/Pasted%20image%2020240710204457.png)

减少电机驱动器中的死区时间对于提高效率至关重要。通过最小化死区时间，可以减少失真，从而实现更平滑的电流波形和更低的损耗。这最终会提高电机效率和整体系统性能。
![](readme.assets/Pasted%20image%2020240710204509.png)

GaN能够为电机驱动应用实现更好的死区时间优化：

**开关速度：**与硅 MOSFET 相比，GaN FET 具有更快的开关速度。这允许对死区时间进行更精确的控制，因为 GaN FET 的关断和开启时间明显更短。这种更快的开关速度允许对死区时间进行更严格的控制。

**降低栅极电容：**与硅 MOSFET 相比，GaN FET 具有更低的栅极电容。这意味着它们可以更快地打开和关闭，从而缩短死区时间，而不会产生击穿电流的风险。这可以实现更高效的运行，并更好地优化电机驱动应用中的死区时间。

**零反向恢复电荷：**GaN FET 没有像硅 MOSFET 那样的体二极管，从而消除了与硅器件相关的反向恢复电荷。这减少了电机驱动应用中所需的有效死区时间，因为无需考虑体二极管的恢复时间。

#### **在电机驱动器中使用宽禁带开关器件的机会**

**低电感电机**

低电感电机有许多不同应用，包括大气隙电机、无槽电机和低泄露感应电机。它们也可被用在使用 PCB 定子而非绕组定子的新电机类型中。这些电机需要高开关频率（50-100 kHz）来维持所需的纹波电流。

然而，使用标准的绝缘栅双极晶体管（IGBT）无法满足这些需求，因为它们只能实现最高频率为 20 KHz 的大功率开关。当采用硅 MOSFET 工作于这些频率时产生的损耗较大，这就为宽禁带器件开创了新的机会。

**高速电机**

由于拥有高基波频率，这些电机也需要高开关频率。它们适用于高功率密度电动汽车、高极数电机、拥有高扭矩密度的高速电机以及兆瓦级高速电机等应用。同样，MOSFET 和 IGBT 能够达到的最高开关频率受到限制，而通过使用宽禁带开关器件可能能够突破这些限制。

**恶劣工况**

在电机控制逆变器中使用宽禁带器件有两个引人关注的益处。第一，它们产生的热量比硅器件少，降低了散热需求。第二，它们能承受更高工作温度——SiC：600°C，GaN：300°C，而硅器件能承受的最高工作温度仅为 200°C。

虽然 GaN 器件目前存在一些与封装有关的问题，导致它们所适用的工作温度不能超过 200°C，但专注于解决这些问题的研究正在进行中。因此，宽禁带器件更适合可能面临恶劣工况的电机应用，比如混合动力电动汽车（HEV）中的集成电机驱动器、海底和井下应用、空间应用等。

#### **在电机驱动器中使用宽禁带器件的挑战**

虽然在电机驱动系统中使用宽禁带器件明显具有许多极具吸引力的益处，但其中仍有一些挑战需要克服。

**绕组绝缘**

第一个风险与匝间短路有关，因为宽禁带器件是以现用电机绕组绝缘所无法承受的速度进行开关，所以可能发生匝间短路。解决这一风险的潜在方法有两种。第一种是限制电压变化率（dv/dt），但这意味着无法充分发挥宽禁带器件的全部潜能，且提高了逆变器损耗。第二种是研究和进一步开发能够承受这些开关频率和电压变化率（dv/dt）的新型绝缘材料。

**轴承寿命**

更快开关速度会增加电机轴承的局部放电，这可能降低轴承（和电机）寿命，从而削弱了使用宽禁带器件能够实现的益处。解决这一问题的潜在方法之一是使用拥有陶瓷涂层的轴承。遗憾的是，它们非常昂贵，会导致电机造价增加。

**电缆长度**

更高开关频率会造成信号在较长的电缆上发生反射的问题。解决这一问题的方法之一是使用滤波器，但这会导致系统中新增了滤波器损耗。目前正在研究如何提高集成度，比如通过将逆变器置于离电机更近的位置，来缩短电缆长度，降低电缆上的信号反射影响。














## 数控机床编程

### G代码
主要是学的这个。

|特性|描述|
|---|---|
|**定义**|一种用于数控机床的标准化编程语言，主要用于控制机床的运动和操作。|
|**主要用途**|控制机床的运动路径（如直线、圆弧）、设置速度、开启/关闭主轴等。|
|**指令类型**|包括G指令（几何指令）、M指令（辅助功能）、T指令（刀具选择）、F指令（进给率）、S指令（主轴转速）等。|
|**常用指令**|G00（快速定位）、G01（直线插补）、G02（顺时针圆弧插补）、M03（主轴正转）、M05（主轴停止）等。|
|**优点**|简单明了，广泛应用，几乎所有的数控机床都支持。|
|**缺点**|功能有限，逻辑控制和复杂操作需要依赖宏编程。|
|**示例**|G00 X10 Y20;<br>G01 X30 Y40 F100;<br>M03 S500;|

### APT语言
这里还是要靠cam软件实现

|特性|描述|
|---|---|
|**定义**|一种高级编程语言，全称为“Automatically Programmed Tool”，用于描述数控机床的操作路径和工艺。|
|**主要用途**|高级编程，复杂路径和工艺的描述，能够生成G代码供数控机床使用。|
|**指令类型**|包括几何描述（点、线、面）、运动指令（直线、圆弧）、逻辑控制（条件、循环）、变量定义等。|
|**常用指令**|PPRINT（输出文本）、GOTO（移动到点）、FROM（起点）、TO（终点）、CIRCLE（圆弧）、LINE（直线）等。|
|**优点**|功能强大，适合复杂的几何和路径描述，支持条件和循环等高级编程结构。|
|**缺点**|复杂，学习曲线较陡，需要专门的软件进行翻译成G代码。|
|**示例**|PPRINT / 'START PROGRAM';<br>FROM / POINT1;<br>GOTO / POINT2;<br>LINE / POINT1, POINT2;|

### 比较

|特性|G代码|APT语言|
|---|---|---|
|**简洁性**|简单明了，易于学习和使用|复杂，需要更多的学习和理解|
|**功能性**|基本功能，适合简单和中等复杂度的操作|功能强大，适合复杂几何和路径的描述|
|**应用广泛性**|广泛应用于各种数控机床|较少使用，主要在高级应用和特定行业中使用|
|**可扩展性**|可通过宏编程扩展，但仍有一定限制|高度可扩展，支持变量、条件和循环等高级编程结构|
|**学习难度**|低至中|高|
|**使用工具**|通常不需要特殊工具，直接输入到数控机床|需要专门的软件将APT代码转换为G代码|


## 纳米技术
新材料。

## SOP标准作业流程
设备的可靠取决于驱动方式。

## 机器人学科
这里就是混合学科技术了。
包含系统工程、管理学在内知识，已经单列。[点我跳转](https://github.com/LeroyK111/Robot)

