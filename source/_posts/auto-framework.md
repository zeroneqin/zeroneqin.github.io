---
title: 测试框架
date: 2020-01-15 10:20:01
updated: 
categories: 
- [自动化测试,  测试框架]
tags:

typora-copy-images-to: test-framework
typora-root-url: test-framework
---

**测试框架封装底层的测试逻辑，提供自动化测试的各种功能，使测试人员可以更快，更方便的构建自动化测试用例，本人基于工作中不同的测试需求，实现了一系列测试框架，较好的满足了业务的自动化测试需求。测试框架封装底层的测试逻辑，提供自动化测试的各种功能，使测试人员可以更快，更方便的构建自动化测试用例，本人基于不同的测试需求，实现了一系列测试框架，在实际工作场景中帮助团队提高自动化测试能力**

1. PSV测试框架。
   将测试用例中的逻辑再抽象，抽象为构建测试数据，执行测试，进行验证，分别对应P(POJO),S(Servide),V(Verification)，将自动化用例书写标准化，提高编写效率。
   https://github.com/zeroneqin/tstest_psv
   https://github.com/zeroneqin/tstest_psv_python
2. Template测试框架。
   类似于设计模式中的模板方法，将测试步骤在基础类中进行抽象，由具体测试用例进行实现。
   https://github.com/zeroneqin/tstest_template
3. DataDriving测试框架。
   数据驱动模式，适用于有大量数据，并且只是数据不同，测试逻辑相同的自动化测试。
   https://github.com/zeroneqin/tstest_datadriving
   https://github.com/zeroneqin/tstest_datadriving_python
4. POP测试框架
   对UI Page进行封装来进行UI自动化测试。
   https://github.com/zeroneqin/tstest_pop_selenium
   


{% asset_img test-framework.png "test framework" %}