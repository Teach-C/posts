---
title: 0.本章前言
date: 2017-04-26 15:13:04
categories:
-  1 Chapter
tags:
- 前言
- 常见问题
---

&emsp;  从这一篇开始，我们就要进行C语言的学习了，在开始之前，我想拿出一章（或者加上附录）来讲一讲编程之外的内容，让大家在开始学习之前对计算机和程序有一些认识。

&emsp;  什么？这么快就进入学习状态让你很不适应？哦，不要担心，这一章我要慢悠悠的和大家谈一些基本的概念，并不涉及太多编程的内容，所以深呼吸～放轻松～

&emsp; 喂，别睡着了诶！！！
<!---more--->

# 说在前面的话

&emsp;  在这里说明一下，我发起这个项目并不是单纯给大学生（也就是我的同学们）提供一个学习C语言的平台，而是希望更多人能够接触计算机技术和计算机编程，我希望我写的东西可以让有一些计算机基础的人都能学会C语言。

&emsp;  **为什么说是有一些计算机基础，而不是说从0开始呢？**

&emsp; 因为我想说的严谨一点，我没办法从0开始教会一个人用电脑，再带他认识电脑，再教会C语言，况且关注这个项目的人都是会使用电脑的，可能你是用电脑写文档，做表格，做PPT，或者拿它来炒股，打游戏。总之，你已经学会基本的电脑操作，我不需要教你单击双击，左键右键，大小写切换这些东西。。。

&emsp; 当然这个项目的目标不只是教会大家C语言，这太俗气了，毫不夸张的说，硬要一个根本没有接触过计算机或者说任何电子设备的人学C语言，他也可以在纸上写出正确的代码，所以说教会基本的C语言并不是这个项目的目标，我希望通过这个项目，以C为出发点，让大家能对计算机技术的探索感兴趣。

&emsp; 同时C是一个很好的入门语言（虽然我本人更倾向于`Python`或者`HTML`做入门语言），学会基本的C之后，可以在硬件上开发类似`arduino`的设备来进行一些发明创造(实际上arduino主要开发语言是`C++`，`C和C++的区别`本章会讨论)，软件上可以去学习C++以及其他的编程语言，或者去进行算法的研究，也或者去开发高性能的数据库，服务端，或者系统底层。（我就是说说，我只会调试或者配置上面说的这几个看起来高达上的东西。。）

&emsp;  当然学C的意义不仅在于此，虽然不同的语言之间有很大区别，但是基本的思想还是一样的，（比如说都会有`变量`，`函数`这些概念，你现在可能并不知道编程语言中的变量和函数是什么意思，忘了它吧，继续往下看！）所以学会C也可以轻松学习别的编程语言。

## 关于本章

&emsp; 关于这个章节，我主要想讲一讲计算机的基础知识，操作系统，C的编程思想，编辑器，基本的编译原理和编译器，还有IDE这些内容。

&emsp; 当然，还有很多同学好奇的C和C++的区别。

## 你可能想问的

### 机械键盘 **or Not** ？

&emsp; 之前说过不需要准备什么工具：智商上线的脑子和一台能正常运行的电脑就可以了，这里可能会有些朋友问我，要不要买一个机械键盘来敲代码，说是很多电影或者现实生活中的大牛都会有机械键盘巴拉巴拉......

&emsp; 这个问题：**因人而异**。

&emsp;  我家里的第一台电脑用的是机械键盘，我用了差不多有十年，它伴随我度过了幼儿园，小学，直到初中它才寿终正寝，后来家里也没买过太贵的键盘，都是普通的巧克力键盘，再到后来的笔记本的浮萍键盘，我觉得都差不多，用着用着，掌握了键间距，就习惯了，我现在最习惯用的是chromebook的浮萍键盘，类似macbook的那种，不过我热爱打游戏的室友觉得机械键盘用着很爽。

&emsp; 所以说，这个事情并没有确切的答案，找一个你用起来最顺手的键盘就好了。

&emsp; 不过话说回来，目前我们的编码水平（包括将来项目结束），不至于因为键盘制约编码效率，当然选用的键盘也不能太差，我们学校机房有一个屋子里面的键盘，那手感就像上面沾了X一样。
所以适中就好，比如（下面的品牌包含但不限于） 某技 或者 某飞燕的百元左右的键盘或者键鼠套装都是不错的选择。

### 我需要什么配置的电脑？

&emsp; 我无数次听到我的朋友跟我说，“**我电脑1T内存**”，或者懂一点的说“**我手机128G内存，比电脑都大**” 更有甚者说”**我电脑500G硬存**“！！！

&emsp; 每当我听到这样的话的时候我都会怀疑自己是不是没有跟上时代的潮流。虽然内存以后能够达到1T，（目前部分工作站和服务器的内存已经可以达到128G，所以我是不会像以前人写书的时候说”我们当时的硬盘容量达到10M，这已经很大了“这样的话的。）但是他们所说的内存并不是真正的“内存”，也就因为这样，我要在这一章里面介绍基础的计算机知识，等我介绍完这些，大家对计算机有一些基本的概念，就知道这个答案了。

&emsp; 所以不要急着去电脑城配台机子，况且电脑城鱼龙混杂。。。你懂得。。。

### 为什么图这么少 ？

&emsp; 这是经过本人深思熟虑的，首先因为我懒的给这个项目备案，所以无论是主站还是映像站都是在天朝境外的服务器，所以过多的图片会增加加载速度，况且本身加载图片就会花费很多时间，所以没有插图必要的章节，就不插图。

&emsp; 而且我还考虑了一个因素，因为这个项目本身不是一个纯粹的教学项目，你可以像看小说，看故事或者看段子一样的享受这个项目，而这些作品里面几乎都是没有图的，你们不也是看得津津有味嘛！！！（说白了就是懒。）

&emsp; 不过，在必要的地方，在表格或者代码块无法清楚表达我的意思的时候，我还是会加入图片的！！！

### 这个项目运营成本多大 ？

&emsp; 目前这个项目托管在[Github](https://github.com/)上，不过Github在米国，天朝访问比较慢，也不稳定，所以增加了岛国映像站，这两个站点是几乎同步更新的，所以费用主要出在服务器上，同时，如果可以，我希望能换一个好的域名。

&emsp; 还有需要说明的一点，**我不会在项目中投放任何广告**，如果有弹窗或者浮窗广告那是网络流量被你的ISP劫持了，所以我在考虑要不要使用HTTPS，这样就需要证书的费用了。目前这个还在考虑中。。。

&emsp; 这些能用金钱来衡量的开销并不是很多，主要还是我需要挤出时间来完成这个项目，这个学期几乎天天满课，我一般都在晚课结束到睡觉前去做这个项目，如果你觉得我的付出值得你奖励一下，就请在下面打赏哦～

##  最后说两句

&emsp; 从下节开始我就要给大家介绍计算机方面的知识了，不知道到现在大家看得怎么样，有没有感觉亚历山大？

&emsp; 拜托！大家都是成年人了，不这么扭扭捏捏的好不好？这电脑多好玩啊！（当然没有和对象出去好玩。。。）电脑并不是什么碰不得的稀罕玩意，计算机被发明出来就是为了方便人们的生活的（虽然最开始是为了解决复杂繁琐的数学问题的），所以说计算机已经发展的很人性化了，在这个科技高速发展的时代，不接触计算机技术，那还有啥意思？

&emsp; 所以说，不要一想到电脑和编程就头疼，随着这个项目的进行，你会发现其实计算机并不是那么复杂，只不过是你以前打开的方式不对罢了～

&emsp; 马上要开始探险了！让你的智商上线把！ 