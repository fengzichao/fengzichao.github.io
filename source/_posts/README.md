---
title: datasetREADME
---

# README

## 1.综述

本数据集是基于不同材质表面缺陷的数据集，并融入了人的认知因素，使本数据集在基础的缺陷属性之外，增添了更多的缺陷定位维度。

## 2.命名法及内容

以Sample1为例：

![7dc99bf69014ceee846a60e11bc19e2](C:\Users\zichao\Documents\WeChat Files\wxid_r2taml7vh85322\FileStorage\Temp\7dc99bf69014ceee846a60e11bc19e2.png)

其中，l1代表第一种光照方式，即正面光照，l2代表第二种光照方式，00，03，06，09，12分别代表水平，（以观察者方向）向3点钟，6点钟，9点钟，12点钟方向倾斜。采集装置简单示意图如下：

<img src="C:\Users\zichao\AppData\Roaming\Typora\typora-user-images\image-20231203154312936.png" alt="image-20231203154312936" style="zoom: 25%;" />

labels_pre包含了缺陷的原始属性，包括位置信息、缺陷类型、缺陷自身的属性等等。

labels_in包含了人与采集装置同时观察缺陷时，对缺陷各个维度的评级，以及一个综合的对缺陷严重程度的打分。

labels_post包含了人对采集到的缺陷图像的各个维度的评级，以及一个综合的对缺陷严重程度的打分。

## 3.关于

欢迎使用我们的数据集，它由北京航空航天大学人工智能研究院制作出品，如果它用于您的研究，请注明出处。
