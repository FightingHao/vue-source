# Vue 源码阅读
<a href="https://github.com/vuejs/vue"><img src="https://img.shields.io/badge/vue-v2.6.10-blue.svg" alt="react-router"></a>

<a href="https://github.com/FightingHao/vue-source/issues/1">01-准备工作</a>

## 阅读方式
这里推荐两种方式：
- 按照`commit-log`来阅读
  `commit-log`一般对应某一个版本的迭代。通过阅读每一次迭代的代码，可以更清晰的了解迭代原因，迭代优化项以及 Vue 的完整历史。这种阅读方式需要的时间比较多。

- 按照 Vue 入口中各个模块来阅读
  每个模块各司其职，可以从入口文件中找到相应模块位置，并各个阅读击破。这种方式耗时短一些。

两种方式都很好，因为这里时间不够充裕，所以使用第二种方式来阅读。

## 目录结构
![图片源自《Vue.js 技术揭秘》](https://fightinghao.github.io/vue-source/images/readme/mind.png)

## 完整流程
![图片源自网络](https://fightinghao.github.io/vue-source/images/readme/start.png)
