---
layout: post
title: 虚函数的实现
categories: cplusplus
keywords: virtual_table,virtual_table_ptr
---

#1. 虚函数的引入
虚函数在cpp的中，主要的作用就是实现了多态。所谓多态，其表现形式就是父类的指针指向子类的对象。实现就是父类来定义一个虚函数，子类可以重写这个虚函数，那么如何去实现