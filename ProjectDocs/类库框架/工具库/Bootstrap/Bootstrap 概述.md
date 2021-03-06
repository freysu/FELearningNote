---
title: Bootstrap 概述
date: 2022-02-20 15:47:23
tags:
  - 前端学习
  - Bootstrap
categories: 前端学习
---

<!-- toc -->
<!--more-->

## Bootstrap 概述

Bootstrap 是一个 UI 框架。

1. 美化页面效果。
2. 简化布局
3. 使用现成的组件和插件。

## 下载 Bootstrap

1. 在官网下载 Bootstrap 文件
2. 在 html 文件中引入 Bootstrap

## Bootstrap 常用样式

1. 按钮
2. 表单
3. 表格

## Bootstrap 组件

1. 图标
2. 菜单
3. 分页

有些交互效果需要通过引入 Bootstrap.js 实现
**注意：要先引入 jQuery 才再引入 Bootstrap**

```html
<!-- 要先引入jQuery才再引入Bootstrap -->
<script src="../script/jquery.min.js"></script>
<script src="./js/bootstrap.min.js"></script>
```

## Bootstrap Javascript 插件

1. 模态框
   以后尽量用自己写的 div 弹出框或者第三方组件的模态框。因为 alert 弹出框在移动设备上可能会屏蔽。
