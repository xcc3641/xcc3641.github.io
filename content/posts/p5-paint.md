---
title: "当代码遇上画布：探索 p5.js 的创意绘画"
date: "2023-12-11"
---

## 前言

今天翻动态的时候，看到了在 2022 年春天的时候，我学习 p5.js 画的作品。p5.js 简单来说是专为想要使用代码在网络上去表达想法，创意的 JavaScript 的库。

我一直羡慕那些能将脑海中的想象变为现实的画家。偶然间发现了 p5.js，我决定用自己熟悉的编程方式来尝试绘画创作。

## 学习参考

### 官网

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112354745.png)

先通过 p5.js 的官网，熟悉它的基础语法，同时跟随官方的基础检查过完所有的 Demo。

完成后我熟悉了：

- 基础语法
- 运作流程
- 简单的应用

🔗：[https://p5js.org/zh-Hans/get-started/](https://p5js.org/zh-Hans/get-started/)

### 进阶案例

后来我在探索好的教程和案例时，发现大家喜欢了一位喜欢的老师：吳哲宇。

他创建了一个关于互动艺术入门的网站，我特别喜欢他生动有趣的讲述方式和案例。

- 🔗：[https://course.creativecoding.in/notes](https://course.creativecoding.in/notes)

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112355429.png)

## 实战创作

### 创作1：SUMMER TREE

学习完成后，我开始了自己的创作过程。我首先尝试的是一些简单的随机点分布方式，后续慢慢进阶成模仿现实油画棒的方式，画一些简单的我喜欢的画。

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112355455.png)

图1 是我很喜欢的一个过程图，我把一个画板，分成了16 个小的正方图。在每个小方块图中，做单独的训练。

- 第一列中，我是在进行“随机”的练习。我有 N 个黑点，随机绘制在正方图中，同时练习添加分布的权重。从完全随机，分布到靠下位置，圆形随机且中心居多到圆形随机中心居少。
- 第二列中，我是在进行用点来绘制简单的图案。从圆环，格子，多圆环到模拟横线画圆。

这些随机的训练是非常有必要的，因为为了让画减少数字感，需要利用随机制造误差来尽量模拟出人用笔画画的视觉感。

- 第三列中，我开始进行画画。很简单图案，蓝天白云，草地和树。

最终成图放大后是这样的：

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112355856.png)


完成这幅画花了我大约 3-4 个小时，而如果用油画棒，可能只需10分钟。但编程的方式让我能批量创作，并增添更多随机性。比如，完成一幅画后，很方便就可以生成很多类似的图案：

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112355784.png)

### 创作2：MOUNTAIN

⛰

> "To see a World in a Grain of Sand
>
> And a Heaven in a Wild Flower
>
> Hold Infinity in the palm of your hand
>
> And Eternity in an hour ..."
>
> BY WILLIAM BLAKE


![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112356157.png)


该图的创作在 SUMMER TREE 的基础上顺利很多，大概花了2个小时，完成这个这幅关于山的画。灵感来自：威廉·布萊克的《天真的预兆》。

### 创作3：SAKURA

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112356881.JPG)


这幅 SAKURA 相当于是二创，我是用当初我在大理拍到的樱花作为底，对其进行加工。

加工的方式是：遍历整个照片的像素存储下来，随后随机对其中的像素画贝塞尔曲线。就得到了这样比较抽象的画作。

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112356279.png)


### 创作4： STARS

![](https://photo-recipe-1301515261.cos.ap-shanghai.myqcloud.com/img/202312112356472.png)


🔗： [https://imxie.itscoder.com/blue/](https://imxie.itscoder.com/blue/)

**⚠️ 注意：** 默认播放音乐，所以打开前注意音量。

这个是上线的一个网站，打开查看体验会比较好，因为这里的方块粒子都是动态的。


使用 p5.js 很方便就可以做到背景的这个动态效果。方块从底部往斜上方移动，在移动过程中伴随着大小和透明度的变化，像微光闪烁的星星。

## 总结

以上就是我使用 p5.js 玩的作品，个人感觉是很低门槛体验用代码创作的工具。

同时也通过这个学习和实践，深刻理解了数学的魅力。

以后有机会，再使用它写点好玩的东西。

🙇‍♂️

