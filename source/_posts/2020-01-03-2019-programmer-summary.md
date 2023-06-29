---
title: 作为程序员，你在 2019年都有哪些进步、收获与成长？
date: 2020-01-03
comments: true
toc: true
# thumbnail: https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093919-6faa2f79-7806-4385-8f83-6b4941ca4909.png
categories: "个人成长"
tags:
  - 程序员
  - 总结
---

> 本文首次回答自知乎，回答原文“[作为程序员，你在 2019年都有哪些进步、收获与成长？](https://www.zhihu.com/question/363043667/answer/961312815)”

不请自来，答一波，作为我在 b 乎的第一张通行证。

<!-- more -->

在 2019 年，我完成了从本科生到程序员职场的身份转换。恰好借用隔壁 [@沈世钧](https://www.zhihu.com/people/d069b25d6ca84652cb81ab3109572d90) 前辈的一句话开头，便是——这一年，表面的我波澜不惊，但内心其实经历了巨大的蜕变。

我的“波澜不惊”，体现在对比 15 年到 18 年年底在“城市型线下开源社区”的深度参与下，19 年的我“突然消失”，在开源社区 0 代码输出 0 博文输出；体现在面对日新月异、增速不减的前端新技术（WebAssembly 正式成为第四种 Web 语言、TypeScript 在业界大规模覆盖、React 16 新特性释出、ES6 标准已经发布四年变成 ES10、GraphQL 使用量进一步增长、Serverless 也逐渐被普及）下，曾经喜欢跟着大佬逐浪前行的我，也逐步产生了一种“不慌不慌，够用就好”的蜜汁安全感。

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093919-6faa2f79-7806-4385-8f83-6b4941ca4909.png#align=left&display=inline&height=239&margin=%5Bobject%20Object%5D&originHeight=682&originWidth=700&size=0&status=done&style=none&width=245)

而我的“内心蜕变”，便与此同时进行——曾经为了完成所有线下技术活动的运营任务从头到尾忙活半天以致有点“迷失职业方向”，曾经为了让举办的技术活动能多一点技术主题而强行当“分享者”、甚至曾经有过把“输出技术博客”作为唯一成长关注点而产生“为了博客而博客”的行为——都注定随着本科生涯的结束而尘封，也通过 2019 年在社区上的主动沉寂给自己这段时间所做的一些事画上了句号。

下面我就针对 2019 年选择几个关键主题，进行一次小小的总结。

## 1. 开源社区与毕业设计

随着 freeCodeCamp 在全球范围内逐步的火热，Github Star 量逐步上涨至第一，每个城市都建立起了线下学习小组；再随着我进入大学生活之处就有着关注技术、用博文总结技术的心态，并苦于找不到更多的社区归属感——大一暑假我便自告奋勇当了西安社区的组织者，并在每位 FCC 爱好者的支持下，通过十余场线下活动、近十篇活动运营文案，围绕微信生态从零建立起了数百人的社群。这一去，便是三年；也随着知乎 Live 正式上线，前端界几个大佬（他们也就在这个问题下回答了自己的 2019）开始开 Live，作为听众的我暗中写了笔记并分享也加了大佬们的微信群而人脉圈更广了点；同时 GitChat 正式上线，自己利用不多的影响力写了两篇博文赚了人生的第一桶金，体验了把“技术网红(无贬义)”的知识付费的感觉。

说了这么多，无非想论述清我和开源社区不可磨灭的缘分和感情。也因此，毕业设计主动申请了一个其实用技术实现起来很普通，但深藏了我对“城市型线下开源社区”的深度参与过程中所做的一些感思的课题——“跨平台开源社区运营管理系统的设计与实现”。

设计这个系统，便想从零出发，解决每个技术爱好者平衡技术学习和运营社区的时间矛盾，并助力每一个技术社区在解放繁琐的运营过程后，能做出更多非凡的事情。软件工程设计水平有限，下面是一个简单的系统结构图。

系统结构图：

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093916-00e8f797-5863-4c8b-8b0e-894c3655c3d3.png#align=left&display=inline&height=672&margin=%5Bobject%20Object%5D&originHeight=672&originWidth=720&size=0&status=done&style=none&width=720)

前端部分使用 Vue 全家桶并配上 UI 库 Vuetify，后端部分使用 Nest.js 系列，并配上 Electron 进行打包，实现了整个项目。由于暂时并不能正式使用，因此暂时也没有开源的计划，下面是其中的一部分截图，凑合着看看。
这也就是我在 2019 年的第一个进步、收获与成长。

角色管理：

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093912-27991ca0-a936-4e96-b0f4-b944e37e037c.png#align=left&display=inline&height=390&margin=%5Bobject%20Object%5D&originHeight=390&originWidth=720&size=0&status=done&style=none&width=720)

给角色分配导航：

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093920-90bf70df-4da1-4a94-b14f-0ab178e0698a.png#align=left&display=inline&height=385&margin=%5Bobject%20Object%5D&originHeight=385&originWidth=720&size=0&status=done&style=none&width=720)

社区活动管理：

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093913-37a19c48-8141-43ac-b2b0-6c165bc38fb2.png#align=left&display=inline&height=387&margin=%5Bobject%20Object%5D&originHeight=387&originWidth=720&size=0&status=done&style=none&width=720)

分享主题管理：

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093928-1bc29cee-c158-4e4e-86e5-ba31dee5073e.png#align=left&display=inline&height=384&margin=%5Bobject%20Object%5D&originHeight=384&originWidth=720&size=0&status=done&style=none&width=720)

## 2. 大厂编码与互联网寒冬

因为对开源的热爱，我爱上了 Github，收获了数百个 follower。也因这份缘分，在几乎没有走面试流程的情况下，当了一个独角兽公司的前端实习生，也顺利的实现了内部转正（Thx！）。来到公司后，由于前端项目技术框架选型的一定自由度，以及带我的导师 Vue、React 一起撸而且还会尽量把新技术及时搬进公司业务代码的原因，我很快熟悉了 Vue + Vuetify 和 Nest.js(用其实现了毕业设计)，也很快熟悉了 React、React Hooks、Ant Design 并自学了 Material UI 库(用其实现了 2020 年的第一个正式开源项目，见下文)。

同时在 2019 年我由前半年的校招生到后半年的转正试用期以及年底的转正答辩，彻底完成了职业化的入门性成长，并在技术上有了很大的提高，这也是我的进步、收获与成长。

同时遇上了传言之为“前 10 年内最坏的一年，未来 10 年内最好的一年”的 2019 年寒冬。见到了各大含金钥匙出生的互联网大厂的各种裁员手段和新闻，以及国内对干技术干不过 35 岁的各种真实性调侃，着实为刚毕业本来就根基不稳的应届生又添上一块冰，也让自己尽早的知道了要珍惜年轻的宝贵，并提前性的、持续性的关注成长，让未来不再惧怕。

这也就是我在 2019 年第二个进步、收获与成长。

## 3. 第一本，英语原著小说，英语不再畏惧

些许讽刺的是，英语四级考试第一次交白卷考场上画画、第二次考完得知自己以 426 分比四级线高出一分时的我，开心的心情就像六级满分一样。我的潜意识一直在抵抗我所从小接触的英语教育模式，但我又没有环境，也不知道如何改进，就这样一直耗到 2019。

在 2019 年双十一中，我为了抵消在北京工作日长时间通勤路上的无聊，剁手买了新出的 Kindle Oasis 3，一股新奇的想法诞生在脑海之中——读原著小说。也因此更进一步，注册了美服亚马逊账号，整个 Kindle 换成美服环境，解锁出了国服没有的“Goodreads”、“Audible Store”等功能。于是看起了可能和很多人一样的，第一部英文原著小说——《Harry Potter and the Sorcerer's Stone - J. K. Rowling》。

起初每个不认识的单词读起来很困难，我都立马暂停并用 kindle 划词翻译直接翻译成中文来尝试理解。接着喜欢上了故事，有了加快阅读速度的欲望，却依然停滞于不认识的单词之前，“气急败坏”之下左手 Kindle 右手手机版的必应翻译一个一个翻译，常常遇到一句话就得翻译个七八个单词——到两个月后的现在，大多数语气词、修饰词都有了初步的印象，不认识的单词也不一定非得转义成中文来理解，要么继续划词英对英翻译，要么直接在前后文中猜这个单词的意思然后直接略过。

原著小说的阅读能力，不得不承认，有了曾经 200% 的提升——阅读方法和阅读心态占比最多。同时，也让自己正式主动拥抱英语，也不再畏惧英语。

这也是我在 2019 年第三个进步、收获与成长。

## 4. 2020 伊始，“凝果开源”，再出发！

数个月前我一直在想，我到底要成为怎么样的我？就这样否定曾经在社区的不安定性活跃并不再参与开源项目的建设？也彻底放弃写技术博客来总结分享自己的所学，每天上班完成任务后就开始愉快的玩耍？其实某种角度那样的话真的挺开心，但总觉得并不是更真实的自己。

也因此，因毕业设计而对大学阶段我在城市型线下开源社区的感悟做了最终的答卷，也因这个毕业设计过程中所产生的各种灵感再出发，以全新的品牌“凝果屋(NingoWood)”及其社区“凝果开源社”为基石，开始我的新的 10 年——毕竟不想让 2030 年即将“中年危机”的我有太多的遗憾。

这也就是我 2019 最后一个进步、收获与成长。

————2020 分割线————

我设计的第一个开源项目是“程序员扑克牌”，灵感来自于 2019 年 freeCodeCamp 出的一副扑克牌。亲自用 React + TypeScript + Material UI 实现了一个 Demo 版本的 UI，并发布了 v0.1.0 版本。
![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093916-cd7ab514-53c9-41de-ab1b-dceb6541877d.png#align=left&display=inline&height=438&margin=%5Bobject%20Object%5D&originHeight=438&originWidth=720&size=0&status=done&style=none&width=720)
https://ningowood.github.io/poker-coder/

我也因此正式开始拥抱 Github 的英文社区，从开发到 Git Commit 再到 Release、Issue 和 MileStone，都用英文来记录和编写，希望走出更多的国际化脚步。

![](https://cdn.nlark.com/yuque/0/2020/png/86548/1578048093964-19940139-132d-4d6c-9f67-909f386431d6.png#align=left&display=inline&height=450&margin=%5Bobject%20Object%5D&originHeight=450&originWidth=720&size=0&status=done&style=none&width=720)

这两天刚刚宣传，收获了 12 个 Star 和 1 个 Issue，很开心，期待大家一起来玩！
我的公众号是“凝果屋的韩亦乐”，WeChat ID 是 ningowood，就酱紫。
