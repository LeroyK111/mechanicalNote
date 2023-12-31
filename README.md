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

#### ★三维设计


### ★仿真

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
太经典了，我的大学毕业设计就是弯管机机床设计。

## 纳米技术
新材料。

## SOP标准作业流程
设备的可靠取决于驱动方式。


## 机器人学科
这里就是混合学科技术了。
包含系统工程、管理学在内知识，已经单列。[点我跳转](https://github.com/LeroyK111/Robot)
