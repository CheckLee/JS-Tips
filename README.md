# 技术栈
> 技术栈超级大总结

(施工中👷)

<!-- TOC -->

- [技术栈](#技术栈)
  - [📋 - Table of Stacks](#📋---table-of-stacks)
  - [⚙ - 规则](#⚙---规则)
  - [👶 - 基础篇](#👶---基础篇)
    - [🛠 - 工具篇](#🛠---工具篇)
    - [💻 - 计算机基础](#💻---计算机基础)
    - [⚔ - 三剑客JS/HTML/CSS](#⚔---三剑客jshtmlcss)
    - [🖥 - 服务器](#🖥---服务器)
  - [👦 - 进阶篇](#👦---进阶篇)
    - [⛸ - 编程CSS](#⛸---编程css)
    - [🗡 - 模块化](#🗡---模块化)
    - [⛸ - 优化工作流](#⛸---优化工作流)
    - [🗡&⛸ - 前端框架学习](#🗡⛸---前端框架学习)
    - [🛡 - 测试框架](#🛡---测试框架)
    - [⛸ - 第三方JS库](#⛸---第三方js库)
  - [👼 - 大师篇](#👼---大师篇)
  - [💯 - Web面试篇](#💯---web面试篇)
  - [📕 - 保持学习](#📕---保持学习)

<!-- /TOC -->

## 📋 - Table of Stacks

> 工具&轮子汇总

* 工具
    * 👶 编写工具 - `VSCode`
    * 👶 浏览器工具 - `Chrome`
* JavaScript
    * 👶 格式化 - `ESlint-standard & Airbnb JavaScript 编码规范`
    * 👶 `ES-next` - 永远拥抱新特性

## ⚙ - 规则

* 📕 - 书籍
* 👶 - 基础
* ⛸ - 敏捷加点
* 🗡 - 攻击加点

## 👶 - 基础篇

学习就像是练功，此时入门阶段你处于在门派求学阶段。

修炼内功，第1步需要什么？当然是 **筑基啦！**

### 🛠 - 工具篇

> 工欲善其事必先利其器。这就是洞天福地啊！

* [VScode]() / 配置好了就是无敌的
* Chrome-dev / F12开始调试，运行JS最快的方式

### 💻 - 计算机基础

> 虽然要求没有其他工程师那么高，但是理解数据结构和算法会加快的你的效率。

* [x] [📕 JavaScript数据结构与算法](https://github.com/JiangWeixian/JS-Books/tree/master/JS%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95) / 这本书引申开来，你需要知道以下几点
    * [x] - 简单几种求解算法的思路
    * [x] - 递归 / 不仅仅是调用自身那么容易，其实是含有一些数学知识的
    * [ ] - 了解算法复杂度之类的 - 网易的算法公开课会帮到你(既然是公开课，也没有那么难)
* [ ] 前端开发更像是软件开发，所以一些设计模式你是需要了解的。
* [ ] 浏览器相关知识
* [ ] 网络相关知识

### ⚔ - 三剑客JS/HTML/CSS

> 不建议一开始就学习前端框架，原生是基础，很重要。**道友，能否筑基成功？**

<img src="https://raw.githubusercontent.com/JiangWeixian/JS-Tips/master/img/javascript.png" height="44px" alt="js">

> MDN真的不错

> 浏览器`JavaScript`环境和`NodeJS`环境是不同的。所以最好复制到浏览器`debug`工具里面。

> `JavaScript`是技术栈最为重要的部分。学习是枯燥的，实践是有趣的。

* [x] [MDN - Web开发入门]()
* [x] `JavaScript`语言特性 - `JavaScript`十分看重是 **语言特性的语言**。以下几本书籍都是值得看的
    * [x] [📕 JS高级程序设计]() / 的确不适合初入门，但是两本真的都很经典。语言特性体现的很多(如果看到不会，留空，以后时常翻阅)，至少和语言相关那部分是一定要知道的。
    * [x] [📕 Youdontkonwjs]()
    * [x] 这是我的阅读笔记 - [JS-Books]()
    * [ ] [JS-踩坑实录]()
* [ ] [ES6]() - 拥抱新特性
* [ ] [Babel]() - 转译你的`ES6`代码，现在浏览器支持大部分的`ES6`代码。如果你需要更多支持(或者多平台适配)，可能需要`Babel`进行适配。

💯**检验：** 找一些公司面经或者笔试题目，能够正确解答就差不多。

**在真正开始写代码之前，你需要养成一个良好的习惯。**

* [ ] 好的编程习惯 - **千万不要听信"那句又不是不能用"！(以下上手其实很快的)**
    * [x] [ESLint-standard]() - VScode上配置`ESLint`
    * [x] [Airbnb JavaScript 编码规范]() - 上面那个是格式化要求，这个是真正的编程习惯。
* [ ] 练习`JavaScript`(脱离浏览器，纯`JavaScript`) - 建议`ES5/ES6`两个版本都要实践一遍
    * [x] [MDN-JS-API]() / **即使无聊，也要背下它**，内置函数API，输入输出以及Polyfill(有助于你学习`JavaScript`语言特性)
    * [x] [牛客网-JavaScript能力测试]() / 基础版本
    * [x] [📕 JavaScript数据结构与算法]() / 升级版本
    * [ ] [📕 剑指Offer]() / 升级版本，`JavaScript`实现一遍
    * [ ] [leetcode]() / 学有余力，网站上面JS相关题目学习算法基础巩固JS基础

💯**检验：** 前端对算法或许会少一些。但是如果你想找一份工作的话，这是少不了的一部分知识储备。**因为这是检验你本科学习是否认真努力**

<img src="https://raw.githubusercontent.com/JiangWeixian/JS-Tips/master/img/html.png" height="43px" alt="html"></img>

> 建议和CSS入门之后，找慕课网的一些实践项目，一边实践一边巩固。这部分你真的需要实践。

* [x] - [MDN-HTML入门]()
* [ ] - [MDN-HTMLAPI]() / 没错你还是要背下它，也至少知道它有哪些`API`。不至于用到的时候束手无策。
* [ ] - 好的编程习惯
    * [ ] 不要全部`DIV`，语义化你的`HTML`。**或许很难，但这是尝试的第一步。**
    * [ ] 除了手写`HTML`页面结构，还要知道如何通过`JS`操作`DOM`
    
<img src="https://raw.githubusercontent.com/JiangWeixian/JS-Tips/master/img/css.png" height="43px" alt="css"></img>

> `JavaScript`就像是功法，`CSS`会让你拥有属性。从外观上展示你的能力。**一些建议，CSS/HTML不一定需要全部看完再去实践，可以选择实践之后，再回过头来看看一看。优化你之前的实践内容**

> CSS多且杂。不亚于一门语言，所以你需要系统了解它。**或许你不要知道复杂的CSS动画如何实现，但是一定要明白布局！**

* [x] [MDN-CSS入门]()
* [x] [📕 CSS权威指南]() / 我相信这回解决你的困惑
* [ ] [CSS-踩坑实录]()
* [x] [CSS-BFM]() - 好的命名习惯

💯**检验：** 找一份设计稿，然后实现它。**要求能够响应式布局**

### 🖥 - 服务器

> 个人认为，对于新手来说。服务器入门和`JS/HTML/CSS`不同，应该以框架入门

* [ ] [Koa]()

## 👦 - 进阶篇

> (还在摸索)筑基成功之后，你需要加点技能点：加点速度⛸(优化你的工作流)；加点攻击🗡(适配，最佳实践)；加点防御(安全，优化，测试)

> 同时前端轮子造起来比较容易，选一把 **趁手的武器，然后活用它**很重要，因为要避免成为配置工程师。

### ⛸ - 编程CSS

* [x] [Stylus]() - 编程你的`CSS`。

### 🗡 - 模块化

> 在NodeJS环境下，模块化是主流的开发选择。但是你可能需要学习在浏览器环境下如何使用模块化的开发。

* [require.js]()

### ⛸ - 优化工作流

> 对应任务有对应插件可选(或许是一对多的关系，选好了就不要换了，学习成本大)

> 避免成为配置工程师

* [ ] [Gulp]() - 在`JS`文件中处理`JS`, 在`CSS`文件中处理`CSS`..。你需要做到
    * [ ] 页面自动刷新
    * [ ] 处理`JS/CSS` - 压缩优化，预处理等
    * [ ] 处理多页面/单个页面情况
* [ ] 结合`nodejs`实现一个类似`vue-cli`工具
* [ ] [Webpack]() - 与`gulp`相比各有所长，适合`vue/react`此类需要打包的，且在`JS`中处理各种文件类型的形式(基于它任何都是包文件的设计思想)

### 🗡&⛸ - 前端框架学习

> 框架之下有许多插件，还是那个规则选个合适的，并保持

> 框架学习不应该停留在会用，还要知道其中原理。例如涉及到了怎样的设计模式，如何实现等。

> 虽然很想和你说只要学`vue`。但是，如果你只会`vue`，要学`react`。如果你会`react`，或许你学习`vue`就只是个备选项。


* [ ] [Vue]()
* [ ] [React]()

框架需要知道然以及所以然，从框架引申开来，你需要知道其中蕴含的设计思想：

* 发布订阅
* 状态机

### 🛡 - 测试框架

> 测试框架使用可能个人不会在意，就像是我一样，不太注意这方面；但是会发现很多大工程都是包含测试部分，建议你还是了解他。

* [JTest.js]()

### ⛸ - 第三方JS库

> 前端轮子多。可能设置动画就有好多种动画库，轮播器也有好多种。因此 **还是选择最合适，并保持**

* [ ] - 🖼动画
* [ ] - 一些设计模式库

## 👼 - 大师篇

## 💯 - Web面试篇

## 📕 - 保持学习

> 关注博客；订阅邮件；关注大牛；**无论在哪个阶段都是需要你保持饥渴的学习态度的！**

* [x] - 这个[网站](https://uptodate.frontendrescue.org/zh/)会帮到你！
