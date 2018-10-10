# TensorFlow学习

主要来源和参考的资料为：炼数成金视频《深度学习框架TensorFlow学习与应用》

视频目录：

``` xml
第 1周 Tensorflow简介，Anaconda安装，Tensorflow的CPU版本安装
第 2周 Tensorflow的基础使用，包括对图(graphs),会话(session),张量(tensor),变量(Variable)的一些解释和操作
第 3周 Tensorflow线性回归以及分类的简单使用
第 4周 softmax，交叉熵(cross-entropy)，dropout以及Tensorflow中各种优化器的介绍
第 5周 卷积神经网络CNN的讲解，以及用CNN解决MNIST分类问题
第 6周 使用Tensorboard进行结构可视化，以及网络运算过程可视化
第 7周 递归神经网络LSTM的讲解，以及LSTM网络的使用
第 8周 保存和载入模型，使用Google的图像识别网络inception-v3进行图像识别
第 9周 Tensorflow的GPU版本安装。设计自己的网络模型，并训练自己的网络模型进行图像识别
第10周 使用Tensorflow进行验证码识别
第11周 Tensorflow在NLP中的使用(一)
第12周 Tensorflow在NLP中的使用(二)
```

—— 说明：实际第 5 周讲的是 Tensorborad 结构可视化，第 6 周讲的是 CNN。修正：下载链接里的文件夹顺序，我已修正。

1）在线观看：

- YouTube：[tensorflow教程（十课）](https://www.youtube.com/watch?v=eAtGqz8ytOI&list=PLjSwXXbVlK6IHzhLOMpwHHLjYmINRstrk&index=2&t=0s)
- 或 B 站：[《深度学习框架TensorFlow学习与应用》](https://www.bilibili.com/video/av20542427/)

2）下载：

- 《深度学习框架Tensorflow学习与应用》（含视频+代码+课件，视频总时长：13小时31分钟）

  > 链接: https://pan.baidu.com/s/16OINOrFiRXbqmqOFjCFzLQ 密码: 1a8j

- 《深度学习框架Tensorflow学习与应用[只有videos-720p]》（该份资料只有视频文件）

  > 链接: https://pan.baidu.com/s/1oQLgWFEBsVrcKJN4swEdzg 密码: i3e2

*其他学习视频（觉得有必要可以去看看）：* 

- 油管视频：[TF Girls 修炼指南](https://www.youtube.com/watch?v=TrWqRMJZU8A&list=PLwY2GJhAPWRcZxxVFpNhhfivuW0kX15yG&index=2) 、或 B 站观看： [TF Girls 修炼指南](https://space.bilibili.com/16696495/#/channel/detail?cid=1588) 
- 油管视频：51CTO视频 [深度学习框架-Tensorflow案例实战视频课程](https://www.youtube.com/watch?v=-pYU4ub7g0c&list=PL8LR_PrSuIRhpEYA3sJ-J5hYGYUSwZwdS)、或 B 站观看：[深度学习框架-Tensorflow案例实战视频课程](https://www.bilibili.com/video/av29663946/?p=1)

## 笔记索引

《深度学习框架Tensorflow学习与应用》笔记：

- [01-Tensorflow简介，Anaconda安装，Tensorflow的CPU版本安装](/week01/01-Tensorflow简介，Anaconda安装，Tensorflow的CPU版本安装.md)
- [02-Tensorflow的基础使用，包括对图(graphs),会话(session),张量(tensor),变量(Variable)的一些解释和操作](/week02/02-Tensorflow的基础使用，包括对图\(graphs\),会话\(session\),张量\(tensor\),变量\(Variable\)的一些解释和操作.md)
- [03-Tensorflow线性回归以及分类的简单使用](/week03/03-Tensorflow线性回归以及分类的简单使用.md)
- [04-softmax，交叉熵(cross-entropy)，dropout以及Tensorflow中各种优化器的介绍](/week04/04-softmax，交叉熵\(cross-entropy\)，dropout以及Tensorflow中各种优化器的介绍.md)
- [05-使用Tensorboard进行结构可视化，以及网络运算过程可视化](/week05/05-使用Tensorboard进行结构可视化，以及网络运算过程可视化.md)
- [06-卷积神经网络CNN的讲解，以及用CNN解决MNIST分类问题-](/week06/06-卷积神经网络CNN的讲解，以及用CNN解决MNIST分类问题.md)
- [07-递归神经网络LSTM的讲解，以及LSTM网络的使用](/week07/07-递归神经网络LSTM的讲解，以及LSTM网络的使用.md)
- [08-保存和载入模型，使用Google的图像识别网络inception-v3进行图像识别](/week08/08-保存和载入模型，使用Google的图像识别网络inception-v3进行图像识别.md)
- [09-Tensorflow的GPU版本安装。设计自己的网络模型，并训练自己的网络模型进行图像识别](/week09/09-Tensorflow的GPU版本安装。设计自己的网络模型，并训练自己的网络模型进行图像识别.md)
- [10-使用Tensorflow进行验证码识别](/week10/10-使用Tensorflow进行验证码识别.md)
- [11-Tensorflow在NLP中的使用(一)](/week11/11-Tensorflow在NLP中的使用\(一\).md)
- [12-Tensorflow在NLP中的使用(二)](/week12/12-Tensorflow在NLP中的使用\(二\).md)



---

## TensorFlow快速入门总结

参考「机器之心」编译文章：

- [令人困惑的TensorFlow！](https://zhuanlan.zhihu.com/p/38812133)
- [令人困惑的 TensorFlow！(II)](https://zhuanlan.zhihu.com/p/46008208)

