# Library-management-system

Database principle experiment

## 第1章 概述

### 1.1 背景

数据库技术和Internet的飞速发展，使他们已经成为现在信息技术的重要组成部分，是现在计算机信息系统和应用的基础和核心。如今图书馆图书种类和数量不断扩大，检索速度慢，统计工作量大，难以满足图书馆现代化管理的需求。因此，建立图书管理系统，科学进行数据管理，方便图书的检索和读者的借阅工作。

在我们系统学习数据库原理后，按照关系型数据库的基本原理，综合运用所学知识，设计开发一个小型的数据库管理系统。

### 1.2 系统开发目的与意义

理解数据库设计的各个阶段的主要任务，了解拟开发系统在信息化背景下的发展目标、组织构成、业务流程和管理流程，初步了解管理信息系统分析、设计、实施的思路与方法，提高系统开发文档撰写能力。

## 第2章 系统需求分析

### 2.1 组织管理调查

#### 2.1.1 组织结构

![pic](/asset/组织结构.png)

#### 2.1.2 主要职能

* 管理员:
  * 对图书信息进行管理
  * 对订单进行管理

* 顾客:
  * 挑选图书
  * 加入购物车
  * 提交订单

### 2.2 系统功能结构图

![pic](/asset/系统功能结构图.png)

### 2.3 系统需求说明

#### 2.3.1 数据需求

* 顾客账户
* 书籍信息
* 管理员账户
* 购买记录

#### 2.3.2 功能需求

![pic](/asset/功能需求.png)

* 顾客基本信息查询,修改
* 图书的信息管理,包括添加,修改,删除
* 购买记录,包括订单号,顾客账号,书籍编号,书籍价格,买书时间
* 书籍信息的查询,包括书籍编号,书籍价格,库存

### 2.4 系统数据流图

### 2.5 系统数据字典

## 第3章 系统概念结构设计(E-R图)

### 3.1 局部E-R图

![pic](/asset/书ER.png)

![pic](/asset/购买记录ER.png)

![pic](/asset/客户账号ER.png)

![pic](/asset/管理员账号.png)

### 3.2 全局E-R图

## 第4章 系统逻辑结构设计

### 4.1 逻辑结构（关系数据模型）

### 4.2 规范化设计

## 第5章 结论

## 致谢

## 参考文献

## 附件
