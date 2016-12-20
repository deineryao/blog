---
title: 基于JavaScript的机器学习系统
date: 2016-12-20 22:16:18
tags:
---


阿特伍德（Atwood Wikipedia）定律：任何能用JavaScript实现的应用，终将会用JavaScript实现


<!-- more -->
我喜欢基于web应用来工作。实现一个从任何地方、任何设备都可运行的应用，是十分有吸引力。在过去的几个月，我一直在尝试获取一些在Javascript上运行的基础轻量级机器学习算法，然后用它们构建”智能的”web应用。随着Node的出现，(基于js)在服务器端训练模型进而用这些模型在客户端做预测已经成为可能。我研究了一些类库（工具），它们确实有助于实现基于Javascript的机器学习。现在我们看看都有哪些类库：

* [Brain.js](https://github.com/harthur/brain)  神经网络类库
* [svmjs](https://github.com/karpathy/svmjs)  支持向量机类库
* [Forest.js](https://github.com/karpathy/forestjs) 实现随机树Javascript类库
* [Numeric.js](http://www.numericjs.com/)  运行复杂的数值计算
* [Node-sylvester](https://github.com/NaturalNode/node-sylvester) 线性代数类库
* [Lineareg.js](https://github.com/lastlegion/linearReg.js) 基于Javascript的线性回归类库

这些库中绝大多数都使用Node.js在服务器端训练模型。它们（通常用JSON）生成一个能在服务器端做预测的分类器。通常来讲，生成的分类器一般都太过于笨重，以至于没什么实际用处，但也并非一无是处。希望不久的将来我可以构建出简洁优雅的应用。



原文链接：http://web.jobbole.com/79487/