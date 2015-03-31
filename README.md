# SkyMicroblogDemo
利用自动布局模仿新浪微博的首页消息显示，可以根据文字内容和图片的张数来实现cell的自适应.

发现在网上类似新浪微博带有多张图片的cell自适应的资源非常少，所以自己研究了一下写了一个Demo，初步实现了想要的效果，以后会进一步的改善的。

欢迎大家提出宝贵的意见,谢谢。

问题:

1.由于刚刚在学习自动布局不久，所以在程序Debug下运行会有很多关于约束的警告。但是具体想要的效果还是实现了。
我会在将来继续修改同时也欢迎帮忙指正错误。

2.理论上cell上的图片张数是可以不做限制的,新浪微博和微信用的都是用的一到九张图片所以我也用了九张(*^__^*)。就实际情况而言，由于每一条信息的图片张数可能不确定所以StoryBoard和XIB的约束我还不会写，就用了手写的约束来达到目的。

3.之前我写过一个类似的项目，但是是用frame计算每张图片的位置，通过一系列计算得到cell的高度，但是滑动起来会非常卡。现在利用约束来让系统自动计算高度流畅了许多，但是我在模拟器上运行还是会有一些卡。希望大神赐教。


关于这个Demo以后的想法:

1.现在只是做了一些页面的显示并未对图片添加点击手势,未来会添加点击手势并实现图片的相册浏览。

2.现在的文字限制只是普通的文字显示,并不包括一些表情,网络连接等。未来会逐步添加的。

3.现在并未对一些模型和方法进行封装随着功能的添加会逐步进行封装方便大家使用。
