---
title: jQuery 概述
date: 2022-02-20 15:47:31
tags:
  - 前端学习
  - jQuery
categories: 前端学习
---

<!-- toc -->
<!--more-->

# jQuery 概述

## 库(Library)与框架(Framework)

共同点：都是第三方写好的现成的程序，使用库与框架可以提升开发效率。
不同点：

1. 库更像是一个工具，拿过来直接使用，相对随意(jQuery)。
2. 框架会对开发者的开发方式设置一定的限制，使用框架需要按照框架的规则来开发项目（Vue、react）。

## 下载 jQuery

- `jquery.js`
- `jquery.min.js`

## 初步了解 jQuery

jQuery 是一个基于 JavaScript 的库，主要用于操作 DOM。

1. 获取节点 $("选择器")

```js
$("button");
```

2.  操作节点 $().method();

```js
$("button").click(function () {
  console.log("hello world!");
});
```

3. 设置元素样式 $().css();

```js

```

案例：多个按钮绑定点击事件。

## jQuery 行情分析

jQuery 是一个过时的库，大量的应用场景已经被取代。

1. 解决兼容内容：随着各大浏览器趋于标准化，浏览器兼容问题已经越来越不是问题。
2. 简化 DOM 操作：随着 MVVM(Vue、React)框架的普及，项目不再大量直接操作 DOM。
3. 动画方法：被 CSS3 取代。

## jQuery 的应用场景

1. 简单的网站，主要用来展示效果（宣传公司或宣传产品）。
2. 单独的某个广告宣传界面。
3. 编写一些简单的小 demo，模拟测试。

jQuery 的学习成本很低（最多一到两天），因此即使过时了，也一定要掌握，这是前端工程师必备技能。

## 课后练习

1. 下载 jQuery。
2. 给多个按钮绑定点击事件。
