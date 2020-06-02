---
layout: post
title: "虚假信息检测系统"
date: 2020-06-01
description: 
# image: /assets/images/rumor_wordcloud_original.png
image: /assets/images/rumor_wordcloud.png
author: Aishan Liu
tags:
  - Graduation Project
---
拟在展示各消息谣言概率的同时，可视化呈现从数据集到单个事件统计分析的结果，给予用户可靠的参考信息

---

> “流丸止于瓯臾，流言止于智者。”
> <cite>《荀子·大略》</cite>

*****

### 主页面
![Homepage](/assets/images/page_home.jpg)

1. 本模块负责展示事件的内容、点赞数目、转发数目和输入模型得到的谣言概率。
2. 用户通过点击上方导航栏可以跳转至其他功能页面，最下方可以换页查阅更多事件。
3. 当鼠标滑动时， 经过的事件信息会高亮显示，点击则可跳转至详情页面查看关于该事件的统计信息。

*****

### 事件详情页面
![Placeholder](/assets/images/page_detail_0.jpg)
![Placeholder](/assets/images/page_detail_1.jpg)

清晰呈现事件中消息级数对应转发评论数量，在传播拓扑图中不同层级的节点颜色不同，使得观察更加直观，当鼠标移动到节点上时，会出现节点的消息id。

*****

### 数据集统计页面
![Placeholder](/assets/images/page_dataset_0.jpg)
![Placeholder](/assets/images/page_dataset_1.jpg)

1. 从数据集整体出发展示分析成果，使用 WordCloud 工具选取出现频率最高的词语， 构造了谣言数据集的词云展示图。
2. 在用户认证情况饼状图中，当光标移动 到相应的区域会显示该群体对应的人数及占比。
<!-- 3. 通过图片展示可以发现未认证的谣言发布者明显多于经过认证的谣言发布者和未经认证的真实消息发布者，占发布消息总人数的 31.19%。 -->

*****

### 各系统性能比较模块
![Placeholder](/assets/images/page_model_0.jpg)
![Placeholder](/assets/images/page_model_1.jpg)

展示了不同模型性能之间的差异，在柱状图中标记了准确率最大的点，用户通过 滑动鼠标观察到各个指标的具体数值。

