# C系列火炮托管仓库 - 说明文档

## 目录
- [C系列火炮托管仓库 - 说明文档](#c系列火炮托管仓库---说明文档)
  - [目录](#目录)
  - [温馨提示](#温馨提示)
  - [C系列概述](#c系列概述)
  - [火炮型号一览](#火炮型号一览)
  - [火炮基座(附赠)](#火炮基座附赠)
  - [火炮编组(过时)](#火炮编组过时)
  - [火炮炮身右侧按钮功能](#火炮炮身右侧按钮功能)
  - [基座合并块右侧按钮功能](#基座合并块右侧按钮功能)
  - [重要提示](#重要提示)
  - [结论](#结论)

<!-- Github不支持TOC目录 -->
<!-- [TOC] -->

## 温馨提示

- SE默认本地蓝图位置 ```C:\Users\你的用户名\AppData\Roaming\SpaceEngineers\Blueprints\local``` 请将蓝图(文件夹)拷贝到此处.
- <font color="red"><b>遇到任何问题可以加入STPC主群探讨, 群号是: 320461590. 我们欢迎新朋友</b></font>

## C系列概述

C系列是什么? **有耐心可以看看, 没耐心可以直接跳过.**

当年群友```Block Moon```在我们群里放了活塞火炮的图, 我觉得很有意思, 之后从工坊找到了 ```YINKY``` 的那个著名的活塞炮坦克, 弄明白原理之后, 自己开始研究活塞炮. 这也是很久以前的事情了, 现在是2021年1月22日, 得一年了吧? 

我做出的第一门稳定的火炮是 ```C06```, 其实这之前还有```C00```,```C01```,```C02```之类的, 但基本上都是用来实验的. 总而言之, 经过了各种实验各种琢磨, ```C06```能工作了, 能工作得很好. 甚至直到今天, 历经了游戏内无数大小版本更替, 这门经典的火炮仍然可以正常工作, 这是我也不曾想到的.

自从成功设计了```C06```, C系列的发展就没有停止, 从 10 以内的版本, 到20以后的版本, 到现在最新的```C40```. 虽然各方面都有巨大的提升, 但还是能从新的版本上找到```C06```的影子.举个例子, 你能看到火炮前面的三个转子, 这个从```C06```开始就有了. 

说起祖传的三转子设计, 你可能猜不到我为什么这么做. 其实原因也简单, 当年我在研究```YINKY```的那个坦克炮的时候就发现了一点, 这炮作用力泄露得太厉害, 甚至到了一种不能忍受的地步. 因此我做了很多实验试图消除这种作用力, 最后我找到了办法, 那就是对称地在火炮拉伸活塞前面也装上转子. 没错, 这种设计完全消除了单轴活塞火炮的K力泄露. 顺带一提, 这种设计也能降低多轴火炮的作用力泄露, 但是做不到完全消除. 你如果把一根```C40```的炮身放到太空里去看, 它基本不怎么泄露作用力, 也归功于这种设计, 这算是C系列的特色了.

再后来呢, 提升火炮的炮弹初速成了一个不错的研究方向, 也因此我做了很多多轴的型号, 比如```C08``` ```C09```之类的, 这种多轴的版本初速能够更快, 当时这种版本的初速已经能到500+. 你可能会问这时候破限部件不是还没有么? 其实我那时候打了千速MOD.

直到某一天, ```Block Moon```在群里跟我们说活塞炮能破限速了. 这下又好玩了, 我拿到了破限的火炮之后开始研究, 把原理和特性摸清楚之后就设计了```C20```, 这是C系列中第一门能够破速度限制的火炮, 现在大概不能用了. 自从在火炮上装了破限机构, 花样就开始多起来, 这时候我设计了```C20```的改进版```C22```, 还有之后的```C24``` ```C26``` ```C28```等等. 

C系列最关键的版本应该是 ```C30```, 我在核心件上采用了新的结构, 非常稳定, ```C30```能称得上是一门现代活塞炮了. 在这种基础上, 我设计了```C40```, 以前是叫做```C34```. ```C40```毫无疑问是C系列中最为强大的火炮, 高速, 稳定, 结构简单, 可靠性好, 自从诞生以来便经常被装载到坦克等载具上. ```C40```能在80m/s高速行驶的坦克颠簸环境下随意走A, 甩狙, 这无疑是对其强大性能最好的证明.

除了以上这些, 你还能在C系列里发现一些神奇的火炮, 比如说```CR06```, 以及我前两天新设计的```CT06```, 受限于篇幅我就不啰嗦了, 感兴趣可以来群里交流交流 (\^_\^).

总之, 欢迎使用C系列的活塞火炮 (你也可以对其中任何一个版本进行改装(~~魔改~~)). 我也找寻找志同道合的合作者， 欢迎加入 ProjectC。

**如果你使用中遇到困难, 可以进群咨询.**


## 火炮型号一览

|                                                               型号                                                               | 类型  |    状态    |             说明              |   炮弹初速    | 稳定性 |                                备注                                 |
| :------------------------------------------------------------------------------------------------------------------------------: | :---: | :--------: | :---------------------------: | :-----------: | :----: | :-----------------------------------------------------------------: |
|      [Cannon_C-C06](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C06/bp.sbc)      | 常规  |  维护终止  |     中高速, 1 x 轴向4活塞     |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C07](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C07/bp.sbc)      | 常规  |  维护终止  |  中低速, 2 x 轴向2活塞(水平)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C08](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C08/bp.sbc)      | 常规  |  维护终止  |   高速, 2 x 轴向4活塞(垂直)   |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C09](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C09/bp.sbc)      | 常规  |  维护终止  |   高速, 2 x 轴向4活塞(垂直)   |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C10](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C10/bp.sbc)      | 常规  |  维护终止  |  中低速, 2 x 轴向2活塞(垂直)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C20](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C20/bp.sbc)      | 破限  |  维护终止  |   高速, 2 x 轴向4活塞(垂直)   |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C22](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C22/bp.sbc)      | 破限  |  维护终止  |   高速, 2 x 轴向4活塞(垂直)   |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C24](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C24/bp.sbc)      | 破限  |  维护终止  |  中低速, 2 x 轴向2活塞(垂直)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C26](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C26/bp.sbc)      | 破限  |  维护终止  |  高速, 2.5 x 轴向4活塞(水平)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C28](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C28/bp.sbc)      | 破限  |  维护终止  |  中低速, 2 x 轴向2活塞(水平)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C30](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C30/bp.sbc)      | 破限  |  维护终止  |  高速, 2.5 x 轴向4活塞(水平)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C32](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C32/bp.sbc)      | 破限  |  维护终止  |  中低速, 2 x 轴向2活塞(水平)  |     未知      |  未知  |                                废弃                                 |
|      [Cannon_C-C34](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C34/bp.sbc)      | 破限  |  维护终止  |  高速, 1.5 x 轴向4活塞(水平)  |     未知      |  未知  |                          废弃, 更名为 C40                           |
|      [Cannon_C-C36](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C36/bp.sbc)      | 破限  |  维护终止  |     中高速, 1 x 轴向4活塞     |     未知      |  未知  |                  经典 C06 的破限重制版, 不推荐使用                  |
|      [Cannon_C-C40](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C40/bp.sbc)      | 破限  | **维护中** |  高速, 1.5 x 轴向4活塞(水平)  | **约600m/s**  |   A    |       **结构可靠, 炮管轻巧, 性能良好, 稳定性卓越, 推荐使用**        |
|      [Cannon_C-C42](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-C42/bp.sbc)      | 破限  | **维护中** |  中低速, 1 x 轴向2活塞(水平)  | **约300m/s**  |   A    |        目前唯一维护中的短管火炮, 有短管需求的话**可以使用**         |
|     [Cannon_C-CH06](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CH06/bp.sbc)     | 破限  |  维护终止  |  特高速, 5 x 轴向6活塞(星型)  | **约730m/s**  |   C    |     炮管较长, 火炮较重, 量力而行 (稳定性不佳, 请使用新的CR系列)     |
|     [Cannon_C-CR06](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CR06/bp.sbc)     | 破限  |  维护终止  |   特高速, 4.5 x 轴向12活塞    | **约800m/s**  |   B-   | 炮管极长, 火炮极重, 量力而行 (因作用力泄露问题不提供不含基座的版本) |
|     [Cannon_C-CT06](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CT06/bp.sbc)     | 破限  | **维护中** | 特高速, 2.5 x 轴向4活塞(水平) | **约825m/s**  |   A-   |                新式的轻量级特高速火炮, **推荐使用**                 |
| [Cannon_C-CT06-dec](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CT06-dec/bp.sbc) | 破限  | **维护中** | 特高速, 2.5 x 轴向4活塞(水平) | **约825m/s**  |   A-   |          这是CT06的装饰版本(暂不确定装饰会不会影响稳定性)           |
|   [Cannon_C-CT08](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CT08/bp.sbc)   | 破限  |  维护终止  | 特高速, 2.5 x 轴向4活塞(水平) | **约905m/s**  |   A-   |                         CT08是过渡验证版本                          |
|   [Cannon_C-CT10](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CT10/bp.sbc)   | 破限  | **维护中** | 特高速, 3.5 x 轴向4活塞(水平) | **约1000m/s** |   A-   |               CT10, C系第一门破千速火炮, **推荐使用**               |
|   [Cannon_C-CT12](https://github.com/SiriusZ-BOTTLE/PistonCannonsOfSpaceEngineers/blob/main/c_series/Cannon_C-CT12/bp.sbc)   | 破限  | **维护中** | 特高速, 3.5 x 轴向4活塞(水平) | **约1000m/s** |   A-   |  CT12, CT10的修改版本, 些许提升稳定性, 微量减少体积, **推荐使用**   |

- 注:
  - 火炮活塞数量等于 "说明" 中两个数字的乘积, 比如说```C40```拥有6根活塞. 
  - "说明" 中第二个数字代表了这个火炮轴向上最长有几根活塞.
  - 维护终止的火炮不一定代表不能继续, 只是不再进行更新. 比如说```C06```.
  - 点击火炮名称会跳到对应的蓝图文件页面, 找到 ```raw```按钮, 之后右键```链接另存为```, 可单独下载蓝图文件, 非常方便(有时页面会直接显示下载按钮)


## 火炮基座(附赠)

|           型号           |             说明             |
| :----------------------: | :--------------------------: |
|  CannonPedestal_CP-C00   |    老式基座, 使用高级转子    |
|  CannonPedestal_CP-C10   | 新式基座, 使用铰链, 出力更大 |
| CannonPedestal_CP-C10-M2 | CP-C10的二联装版本, 火炮横置 |
| CannonPedestal_CP-C10-M3 |      CP-C10的三联装版本      |
|  CannonPedestal_CP-C20   |   通常情况下不要使用该基座   |
|  CannonPedestal_CP-C30   |       CP-10的前置版本        |
|  CannonPedestal_CP-C40   |       CP-10的修改版本        |
|  CannonPedestal_CP-C50   |         新的圆形基座         |
|  CannonPedestal_CP-C60   |         新的方形基座         |


## 火炮编组(过时)

|         编组名称          |        编组说明        |                                       备注                                        | 是否被定时器组影响 |           火炮开火过程中有何动作           |
| :-----------------------: | :--------------------: | :-------------------------------------------------------------------------------: | :----------------: | :----------------------------------------: |
|  **Decorations_cannon**   |         装饰品         |                                主要是显示器之类的                                 |         是         |     开炮时关闭编组, 装填完成后重新开启     |
|      **Guns_cannon**      |       加特林机枪       |                                   用于分离炮弹                                    |         是         | 先开启, 开炮中射击一次, 最后关闭(机枪保险) |
|     **Pistions_LIFT**     |       升降机活塞       |                                   便于拆装炮身                                    |         否         |                                            |
|    **Pistions_cannon**    |     火炮的蓄力活塞     | 活塞名称诸如 p0 p1 p2等等, p0是火炮最前端的(一个或多个)活塞, 编号越大距离前端越远 |         是         |       炮弹射出后伸展, 炮弹焊接后收缩       |
|   **Detachers_cannon**    |  炮管泄力转子(或铰链)  |                                 用来施放弹性势能                                  |         是         |         开炮时脱离, 活塞伸展后附着         |
|  **Rotors_cannon_FRONT**  |      火炮前部转子      |                  用于缓冲与抵消作用力泄露, 同时方便火炮调试改装                   |         否         |                                            |
|        **Turret**         | 用于脚本鼠标控制的编组 |                                                                                   |         -          |                                            |
|       **Hinges_V**        |   垂直旋转转子(铰链)   |                           基座上控制火炮垂直旋转的部件                            |         否         |                                            |
| **Warheads_cannon_shell** |       炮弹弹头组       |                                       炮弹                                        |         是         |          开炮后装备弹头(弹头保险)          |

## 火炮炮身右侧按钮功能

- 按钮主要用来拆卸, 调试, 修复火炮

| 位置(从右往左数) |         功能          |
| :--------------: | :-------------------: |
|        1         | 反转 Pistions_cannon  |
|        2         | Detachers_cannon 附着 |
|        3         | Detachers_cannon 脱离 |
|        4         |    开关红色瞄准线     |

## 基座合并块右侧按钮功能

| 位置  |                功能                |
| :---: | :--------------------------------: |
|  左   |   开关合并块, 用于拆卸和安装火炮   |
|  右   | 反转升降机活塞, 方便安装和拆卸火炮 |

## 重要提示

- 以上大部分火炮支持各种炮弹包括网格数较多的炮弹(可以堆叠较多弹头而不会导致炸膛, 比如**可以在炮弹上放座椅把工程师发射出去**, 不会导致炸膛)
- 你可以自己制造基座, **但我附赠了几个基座可以直接使用**. (我提供的基座未必能满足需求, 还请具体问题具体分析)
- **稳定性A及以上的火炮, 可以在高速移动下(100m/s)和按一定角速度旋转炮管时开火, 而不会轻易故障**, 稳定性A以下的火炮不保证走A和甩狙时的稳定性. CH和CR系列等重型火炮请于静止时开火. 
- 注意, 默认设置下的火炮无法在启用了**次级网格伤害**的环境下使用, 如有需求请自行降低初速, 降低蓄力活塞速度, 并延长火炮装填时间. 总之, 我不推荐你无聊到开启这个选项.

<!-- ## 更新日志

```
----------<2020.10.XX>----------
[0] C34 更名为 C40
[1] 新增 C40 的短版 C42

----------<2020.10.07>----------
[0] 翻新了一遍受维护的火炮, 修改了毫无可读性的编组
[1] 取消了控制器的冗余设计, 火炮性能提升
[2] 新增了 C06 的复刻版本 C36

----------<2020.09.30>----------
[0] 新增了全新结构的火炮CR06
[1] 停止维护老的火炮, 现在只有C30, C32, C34, CH06, CR06五门火炮接受维护

----------<2020.08.16>----------
[0] 新增了 Cannon_C-C30 和 Cannon_C-C32, C26和C28有一定小瑕疵
[1] 新增了坦克 Tank-X10-C32

----------<2020.08.14>----------
更新说明: 新版本SE的转子和铰链抗拉伸能力降低, 导致火炮基座稳定性降低, 
因为后座抖动问题导致三联装的火炮故障率较高, 最好是别用
[0] 新增了全新结构的 Cannon_C-C26 和 Cannon_C-C28
[1] 修复了三联装基座工具栏部分项目失效的问题

----------<2020.08.13>----------
更新说明: 新版本SE的转子和铰链抗拉伸能力降低, 导致火炮基座稳定性降低, 
对高速火炮(C-C22, CH-06)的多联装略有影响, 正在尝试进行补偿(只能说K社智障)
[0] 略微降低了 Cannon_C-C22 核心部件的质量, 试图提升稳定性
[1] 新增了 CannonPedestal_CP-C10-M2 双联装基座
[2] 把群友 小渣渣 的鼠式坦克打包进来了, 可以用来测试火炮(雾)

----------<2020.08.12>----------
小更新
[0] 修复了三联装基座中有两个焊接器没有开启的问题
[1] 修复了 Cannon_C-C08 的基座工具栏项(摄像头查看)的错误
[2] 增加了 CannonPedestal_CP-C20 单联装基座
[3] 更新了新版本游戏中的炮弹速度在文档中的记录
[4] 修正了一些文档错误(错别字等)
[5] 说明文档(此文档)添加了一些内容

----------<2020.08.11>----------
系列全面重制
[0] 焊接器位置调整, 结构更加紧凑
[1] 调整了火炮整体结构, 降低了火炮高度(一格)
[2] 重制了附赠的火炮基座, 大幅降低火炮基座的体积
[3] 炮弹结构调整
[4] 全部火炮型号侧面装饰及按钮调整

----------<2020.08.01>----------
之前没写更新日志, 基本忘记更新了啥
[0] 新增火炮 Cannon_C-C24
``` -->

## 结论
- 双数型号的炮是稳定版, 单数型号的炮不稳定, 用于测试和实验, 请使用双数型号的火炮.
- 推荐使用的炮型号是: ```C40```, ```C42```, ```CT06``` 不追求特别高的炮弹速度可以不用```CT06```. 
- 如果你不清楚要用哪一门, 请选择```C40```
