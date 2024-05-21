---
title: 基于开源软件的DevOps流水线质量保障体系（Based on Jenkins）
date: 2022-10-27 15:49:09
updated: 2023-12-06 11:00:23
top: 1000
categories: 
- [DevOps, 流水线, 质量关卡/质量门, 架构]
- [质量保障体系, 流水线质量保障体系]
tags:

typora-copy-images-to: jenkins-quality-gate
typora-root-url: jenkins-quality-gate
sticky: 100
---

本人为公司DevOps流水线设计和实现的一整套质量保障体系，整套系统由Jenkins流水线结合各种测试服务组成，覆盖单元测试，接口测试，压力测试，UI测试，功能自动化测试，静态扫描，安全扫描，代码规格扫描，依赖扫描，Mock服务等多种自动化手段以及相应的质量门，全部由开源软件或基于开源软件二次开发的平台和服务组成，目前已经在笔者的公司成功落地并运行。

Jenkins流水线+单元测试服务+代码质量扫描服务+代码安全扫描服务+代码依赖扫描服务+代码规格扫描服务+接口测试服务+压力测试服务+UI测试服务+功能测试服务+其他辅助类的测试时服务（如Mock服务，测试数据服务等）。
{% asset_img jenkins-quality-gate.png "jenkins quality gate" %}