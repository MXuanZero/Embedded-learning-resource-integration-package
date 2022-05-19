# 嵌入式学习资源整合包（1.0.0）

> 这是我整理的嵌入式学习资源整合包，遇到不懂的或者想学的东西可以跟这个学习资源整合提到的教程进行学习。	——MXuan

### 电路

**基础元器件：**[郭天祥老师](https://space.bilibili.com/1042590734)(推荐)、[唐老师讲电赛](https://space.bilibili.com/28143041)

**模拟电路：**[华成英模拟电路](https://www.bilibili.com/video/BV19s411a7KL)

**数字电路：**[华中科技大学公开课](https://www.bilibili.com/video/BV197411u7dZ)

**电路设计：**

- 基础：郭天祥老师
- 电源电路：唐老师讲电赛
- 电机驱动：待补充

**PCB：**唐老师讲电赛

**高速PCB：**待补充

### 专业基础课

建议先不要看专业基础课，没有复变函数基础的人先补复变函数再看。这些东西刚学起来很难用到项目中，强行学习很大概率学着学着就放弃了。

**信号与系统：**[信号与线性系统分析  吴大正   郭宝龙](https://www.bilibili.com/video/BV16E411E7PA)

**数字信号处理：**[数字信号处理—东南大学](https://www.bilibili.com/video/BV1us411Y7fL)

**控制理论基础：**[现代控制理论（清华大学）](https://www.bilibili.com/video/BV16E411h7Cg)、[DR_CAN](https://space.bilibili.com/230105574)（极力推荐）

### 嵌入式

**51单片机：**[江科大自化协](https://www.bilibili.com/video/BV1Mb411e7re)

**STM32：**

- 标准库：[野火STM32F103教程](https://www.bilibili.com/video/BV1yW411Y7Gw)、[江科大自化协STM32入门教程](https://www.bilibili.com/video/BV1th411z7sn)

- HAL库：[STM32G4蓝桥杯嵌入式学习日记](https://www.bilibili.com/video/BV1ra411B7zT)（有些地方有错。视频没有分P，此处放合集链接）

> **补充1：**寄存器和 GPIO 江科大自化协讲的非常通俗易懂，推荐先将江科大自化协STM32入门教程**第三章**看完再去看野火的奖惩
>
> **补充2：**不要看野火和正点原子的HAL库教程，推荐直接去看蓝桥杯嵌入式的教程，看完不仅能基本把HAL库整明白，还能去参加蓝桥杯。之后如果用到没学过的东西去

**FPGA：**待补充

**单片机系统：**

推荐先学习 FreeRTOS，该系统历史悠久，有众多参考资料。

- FreeRTOS：待补充
- RT-thread：[韦东山freeRTOS快速入门视频教程](https://www.bilibili.com/video/BV1844y1g7ud)（只看了一部分）
- liteOS：华为的操作系统，资源太少，不建议初学者学这个。

**Linux系统：**

- Linux基础：[韩顺平 一周学会Linux](https://www.bilibili.com/video/BV1Sv411r7vd)
- Linux线程编程：[linux多线程编程](https://www.bilibili.com/video/BV1bJ41117ho)
- ARM 裸机编程：[正点原子【第二期】手把手教你学Linux之ARM（MX6U）裸机篇](https://www.bilibili.com/video/BV1yE411h7u)
- uboot：[正点原子【第三期】手把手教你学Linux之系统移植和根文件系统构建篇](https://www.bilibili.com/video/BV12E411h71h)
- Linux驱动开发：[正点原子【第四期】手把手教你学 Linux之驱动开发篇](https://www.bilibili.com/video/BV1fJ411i7PB)

> **补充1：**Linux基础没必要全看，先熟读目录，再看一半，剩下一半要用的时候再回来学也不迟。
>
> **补充2：**其实我没有完整看过正点原子的Linux驱动开发系列视频，查资料时偶尔看过一两个，觉得还不错，又是成系列的，因此放入推荐列表中。

### 计算机

#### 编程语言

- C语言：[【C语言】《带你学C带你飞》](https://www.bilibili.com/video/BV17s411N78s)、《C Primer Plus》
- C++：[【C++语法】《C++快速入门》](https://www.bilibili.com/video/BV1Ps411w73m)、《C++ Primer Plus》
- java：[【零基础 快速学Java】韩顺平 零基础30天学会Java](https://www.bilibili.com/video/BV1fh411y7R8)（零基础一个月不可能看完，起码两个月）

#### 理论

**计算机组成原理：**[计算机组成原理](https://www.bilibili.com/video/BV1Wv411x7zP)（没看过）

**计算机网络：**[中科大郑烇、杨坚全套《计算机网络（自顶向下方法 第7版）》](https://www.bilibili.com/video/BV1JV411t7ow)、《计算机网络》(黑皮书)

**计算机操作系统：**[南京大学2022操作系统-蒋炎岩](https://www.bilibili.com/video/BV1Cm4y1d7Ur)（该视频没有分P，此处放合集链接）

#### 算法与数据结构

先去看[马士兵的课（java）](https://www.bilibili.com/video/BV13g41157hK)或者[小甲鱼的课（C语言）](https://www.bilibili.com/video/BV1jW411K7yg)，边看便刷题。建议用 C++ 或者 Java 刷题，有些题用 C 语言写起来很麻烦。

#### 安卓（java）

Android 并没有很多优秀的教程，值得推荐的只有[【天哥】Android开发视频教程最新版 Android Studio开发](https://www.bilibili.com/video/BV1Rt411e76H)。但不错的书籍却有不少，比如：《第一行代码》第三版、《疯狂安卓讲义》第四版。

### 人工智能

最好把《高等数学》上下两册，《线性代数》，《概率与统计》学完之后再学下面的知识

**导论：**[【学习经历】如何入门人工智能？AI学习路线推荐](https://www.bilibili.com/video/BV16g4y1z773)

**机器学习基础：**[[中英字幕]吴恩达机器学习系列课程](https://www.bilibili.com/video/BV164411b7dx)

**机器视觉：**[从零入门到超神 机器视觉 全套课程](https://www.bilibili.com/video/BV13L411j7YA?p)

> 补充：机器视觉没找到特别好的中文课程。

### 机器人

待补充

### 其他

#### 转码

如果想要转码，推荐以下两个学习路线。另外再推荐两个程序员 up 主[程序员鱼皮](https://space.bilibili.com/12890453)和[汤姆还在写代码](https://space.bilibili.com/165087084)。

- C++方向学习路线：[【2022最新】个人整理 C++ 开发 校招 全面学习路线](https://www.bilibili.com/video/BV17L4y1V7JW)
- Java方向学习路线：[Java学习路线一条龙版，无脑通关大厂，不迷茫！](https://www.bilibili.com/video/BV15g41157NK)

#### 3D建模

待补充
