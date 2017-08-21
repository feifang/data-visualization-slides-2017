## DATA VISUALIZATION
## 数据可视化

<span style="font-size:0.7em; color:gray">大数据组</span> |
<span style="font-size:0.7em; color:gray">前端开发工程师</span> <span style="font-size:0.7em; color:#ef8526">方菲</span>

---

### Overview
- WHY  可视化的简史及作用 
- WHAT 什么是（<b>好的</b>）可视化？ 
- HOW  怎么做可视化？ 
- 大数据 x 可视化 
- BONUS！ 

---
## WHY
### 可视化的简史及作用

+++
#### CASE 1: The Cholera Epidemic in London, 1854
<span style="color: gray; font-size: 0.5em;">*Original map by Dr. John Snow's*</span>
![](http://img.mp.itc.cn/upload/20170718/8c0438041e594cb385ac1d66befe8dc1_th.jpg)

+++
<span style="color: gray; font-size: 0.5em;">*A simplified version by E.W.Gilbert*</span>
<span style="color: gray; font-size: 0.5em;">（1）用‘x’标识抽水井的位置（2）异常值分布更明显</span>
![](http://www.doghj.com/upload/editor/1549/image/20160223/1456193863286034542.jpg)


+++
#### CASE 2: The Causes of Mortality in 1858
<span style="color: gray; font-size: 0.5em;">*The graphic that saved lives by Florence Nightingale (1820-1910)*</span>
![](http://www.florence-nightingale-avenging-angel.co.uk/blog/wp-content/uploads/2012/01/Rose.jpg)

+++?image=http://www.florence-nightingale-avenging-angel.co.uk/blog/wp-content/uploads/2012/01/Column4.jpg&size=auto 95%

+++ 
### 可视化发展历程
- <span style="font-size: 0.5em;">17世纪前： 图表萌芽 - 地图<br></span>
- <span style="font-size: 0.5em;">1600-1699年：物理测量 - 第一幅天气图，small multiple<br></span>
- <span style="font-size: 0.5em;"><b>1700-1799年：图形符号</b> - 等高线图、折线图、柱状图<br></span>
- <span style="font-size: 0.5em;"><b>1800-1900年：数据图形</b> - 开始较多应用于社会、地理、医学和经济领域<br></span>
- <span style="font-size: 0.5em;">1900-1949年：现代启蒙 - 缺乏创新，但开始面向政府、商业和科学走向应用普及<br></span>
- <span style="font-size: 0.5em;"><b>1950-1974年：多维信息的可视编码</b> - 图形符号和表示理论的提出，如”视觉通道“和多维数据编码<br></span>
- <span style="font-size: 0.5em;">1975-1987年：多维统计图形 - Edward Tufte 等人的理论逐渐推动信息可视化发展为一门学科<br></span>
- <span style="font-size: 0.5em;"><b>1987-2004年：交互可视化</b> - TableLens 等交互手段、树图的发明；可视化学术会议的出现<br></span>
- <span style="font-size: 0.5em;">2004年至今：可视分析学 - 应对海量、高维、多源和动态数据的分析挑战，辅助用户从中快速挖掘有用的信息，以便做出有效决策的新兴学科。</span></span>

<span style="color: gray; font-size: 0.4em;">*引用自：《数据可视化》，陈为*</span>

+++ 
### 可视化的主要作用
<br>
#### <span style="color: gray;"> Explore 分析数据 </span>
<span style="font-size: 0.5em;">人脑对图形、图像的解析是并行的，而对文字、词语的读取则是串行的。</span>

<br>
#### <span style="color: gray;"> Explain 传达数据 </span>
<span style="font-size: 0.5em;">一图胜千言</span>

---
## WHAT
### 什么是（**好的**）可视化？

+++
### 好的可视化需要遵循哪些标准？
- 有效性 |
- 准确性 |

+++?image=assets/img/Graph-distortion.png&size=auto 95%

+++?image=assets/img/Graph-distortion2.png&size=auto 95%

+++
### 好的可视化需要遵循哪些标准？
- 有效性
- 准确性 
- 高效性 

![](assets/img/DataInk.png)

+++?image=assets/img/DataInk-bad.png&size=auto 95%

+++?image=assets/img/DataInk-good.png&size=auto 95%

+++
### 好的可视化需要遵循哪些标准？
- 有效性
- 准确性 
- 高效性 
- 层次性 
- 目的性 |

---
## HOW
### 怎么做可视化？

+++
### 如何选择合适的可视化图表类型？

+++?image=http://www.infographicsblog.com/wp-content/uploads/2011/11/chart-suggestion-infographic.jpg&size=auto 100%


+++
### 如何选择可视化工具？


+++?image=https://media.opennews.org/img/24tools/big_chart.png&size=auto 95%

--- 
### 大数据 x 可视化
- 学术案例：<span style="color:#ef8526">SwiftTuna</span> - Responsive and Incremental Visual Exploration of Large-scale Multidimensional Data
- 商业案例：阿里云 <span style="color:#63aeed">DataV</span> 数据可视化


+++
## <span style="color:#ef8526">SwiftTuna</span>
<span style="color:gray; font-size:0.7em">Responsive and Incremental Visual Exploration of <br><b>Large-scale Multidimensional Data</b></span>

<br><br>

<span style="color: gray; font-size: 0.5em;">*Jaemin Jo, Wonjae Kim, Seunghoon Yoo, Bohyoung Kim, and Jinwook Seo, Human-Computer Interaction Laboratory, Seoul National University and Hankuk University of Foreign Studies*</span>

+++?image=http://hcil.snu.ac.kr/system/researches/representative_images/37/retina/f811ad74c93c19adf1e9919be042726978c001bf.png&size=auto 90%

+++
#### 亮点1：增量式计算与快速响应的可视化
![](assets/img/SwiftTuna-Incre-Process.png)

+++?image=assets/img/SwiftTuna-vis1-1.png&size=auto 90%

+++?image=assets/img/SwiftTuna-vis1-2.png&size=auto 85%

+++
#### 亮点2：Scalable Visualization

+++?image=assets/img/SwiftTuna-vis2-1.png&size=auto 90%

+++?image=assets/img/SwiftTuna-vis2-2.png&size=auto 80%

+++
#### Benchmark Result 测试结果
![](assets/img/SwiftTuna-data-size.png)

+++?image=assets/img/SwiftTuna-result.png&size=auto 90%

+++
### 阿里云 <span style="color:#63aeed">DataV</span> 数据可视化
![](https://pic3.zhimg.com/v2-bca03f89bb13c89b5afc9673dd08b902_b.jpg)

<span style="color:gray; font-size:0.6em">阿里云出品的拖拽式可视化工具，专精于业务数据与地理信息融合的大数据可视化。</span>

+++?image=http://img2.tbcdn.cn/L1/461/1/c84ee736100d1c934dce12d324ba4b59e2542d61.png&size=auto 80%

+++
#### 亮点1：实时架构（以飞线的处理流程为例）
![](http://img2.tbcdn.cn/L1/461/1/d1509c755cfcc4a7708f2e0203452ec52b9d3ab2.png)


+++
#### 亮点2：创新的设计与开发模式
<span style="color:gray; font-size:0.6em">从(设计-> 开发) 到 (设计-> 开发 -> 设计-> 开发)</span>
![](http://img3.tbcdn.cn/L1/461/1/1b3a758d8bdbfb736f91cf7c85a740357d330619.png)

---
### BONUS！

+++
#### Storytelling：[新“口红效应”](https://feifang.github.io/New-Lipstick-Effect/)
![](http://image.dydata.io/519SPTzwKEvA2Qy2n5cCVi.gif)

+++
### Resource
- eagereyes — Visualization and Visual Communication: https://eagereyes.org/
- FlowingData: flowingdata.com
- Visualizing Data: www.visualisingdata.com
- information aesthetics - Data Visualization & Information Design: http://infosthetics.com/
- Information is Beautiful: www.informationisbeautiful.net/

---
## THANK YOU!
