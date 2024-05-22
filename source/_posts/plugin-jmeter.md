---
title: Jmeter插件-Json Schema校验插件
date: 2020-07-10 22:20:01
updated: 2020-08-20 21:10:05
top: 700
categories: 
- [测试技术, Jmeter插件]
tags:
  - Jmeter
typora-copy-images-to: plugin-jmeter
typora-root-url: plugin-jmeter
---

**Json结构是一个非常常见的数据交互格式，尤其是在使用HTTP协议交互的场景，一个常见的测试需求是校验整个JSON的格式是否符合要求，一般的解决办法是使用JSON Schema（类似于XML Schema)，Jmeter作为压测工具在请求和响应中经常会见到Json格式的数据，但是Jmeter缺乏JSON schema校验的插件，所以本人实现了一个JSON schema校验插件 **
https://github.com/zeroneqin/tsplugin_jmeter

{% asset_img plugin-jmeter.png "plugin jmeter" %}