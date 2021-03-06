---
title: jQuery常用方法
date: 2022-02-20 15:47:09
tags:
  - 前端学习
  - jQuery
categories: 前端学习
---

<!-- toc -->
<!--more-->

## `$` 的作用

1. `$`其实就是一个函数名，是 jQuery 的缩写。
   ```js
   jQuery("button").click(function () {
     //code
   });
   $("button").click(function () {
     //code
   });
   ```
2. `$`可以作为选择器，获取 DOM 对象对应的 jQuery 对象。
3. `$`可以将一个 DOM 对象，转换成一个 jQuery 对象。
4. 事件中的 this，指向 DOM 对象，所以需要使用`$(this)`做转换。
5. 什么时候使用 jQuery，什么时候使用 JS？其实本质上 jQuery 就是 JS,只是我们使用一些现成的方法而已。

## jQuery 常用方法

1. `index()`; 获取元素索引
2. `text();` 获取和设置文本节点
3. `css();`获取和设置样式
4. `val();`获取和设置 value 属性
5. `attr();` 获取和设置属性值，例如 src
6. `addClass();` 添加 class
7. `removeClass();` 删除 class
8. `toggleClass();` 切换 class
9. `siblings(); `获取同级其他元素
10. `find("");` 获取子级
11. `parent(); `获取父级

## jQuery 里 DOM 操作

1. `append();` 添加元素节点
2. `remove();` 删除元素节点

## jQuery 事件

1. click();
2. mouseenter()
3. mouseleave()
4. mousemove()
5. on()事件委托

## jQuery 动画方法

1. show();
2. hide();
3. fadeIn();
4. fadeOut();
5. slideDown();
6. slideUp();
7. animate();

基本都是用 CSS3

## 课后练习

1. 轮播图练习
2. 水果列表的添加与删除
3. 随鼠标显示大图
