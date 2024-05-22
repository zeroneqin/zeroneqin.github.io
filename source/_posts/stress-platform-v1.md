---
title: 性能测试服务（平台）一期
date: 2021-06-27 23:39:09
updated: 2022-05-29 19:33:04
top: 910
categories: 
- [测试服务/平台, 性能/压力测试服务]
- [DevOps, 流水线, 质量关卡/质量门, 性能/压力质量门]
tags:
typora-copy-images-to: stress-platform-v1
typora-root-url: stress-platform-v1
---

**性能测试服务（平台）一期，可以单独使用，也可以接入DevOps流水线作为性能质量门。**

性能测试服务（平台）一期实现如下功能（基于开源系统二次开发）。
1. Artillery兼容的压测(https://github.com/artilleryio/artillery)。
2. 性能测试。
3. 项目管理。
3. 用户和权限管理。

一期的问题有以下几个
1. 底层依赖的压测工具Artillery与Jmeter等工具相比功能还是比较简陋。
2. 压测用例和脚本管理相对简单，无法有效的组织用例和脚本。
3. 用户和权限管理相对简单。
所以我们又规划了性能测试平台（服务）二期。

{% asset_img stress-platform-v1.png "stress platform v1" %}