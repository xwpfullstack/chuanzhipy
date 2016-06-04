# python高级语法

Python高级--专题
===============

## 数据类型进阶
### 数字类型扩展
+ 小数数字
+ 分数类型
+ 布尔类型
+ 数字扩展
    + NumPy

### 字符串扩展
+ string

### 列表扩展
+ collections

### 字典扩展
+ collections

### 集合

### 为什么有了列表还需要元祖

###  引用VS拷贝

### Python中真和假的含义

### 动态类型

#### 缺少类型声明语句的情况
+ 变量、对象和引用
+ 类型属于对象，而不是变量
+ 对象的垃圾收集

#### 共享引用
+ 共享引用和在原处修改
+ 共享引用和相等


## 字符串编解码进阶
### 字符串基础知识
+ 字符编码方法
+ Python字符串类型
+ 文本和二进制文件

### py3的字符串应用
+ 常量和基本属性
+ 转换

### py3编码Unicode字符串
+ 编码ASCII文本
+ 编码非ASCII文本
+ 编码和解码非ASCII文本
+ 转换编码

### py2中编码Unicode字符串

### 使用py3的bytes对象

### 使用py3和py2的bytearray对象

### 总结py2和py3的区别


## 程序结构进阶
### 循环技巧
+ 循环计数器: while/range
+ 非完备遍历: range和分片
+ 修改列表: range
+ 并行遍历: zip/map
+ 产生偏移和元素: enumerate


## 函数进阶
### lambda表达式
+ lambda表达式简介
+ lambda表达式举例

### map
+ 作用
+ 举例

### filter
+ 作用
+ 举例

### reduce
+ 作用
+ 举例

### 迭代器和解析
+ iter/next
+ range/map/zip/filter
+ 多个迭代器VS单个迭代器
+ 生成器
    + yield vs return
    + 生成器函数 vs 生成器表达式

### 装饰器
#### 装饰器简介

#### 二层装饰器
+ 语法
+ 举例

#### 三层装饰器
+ 语法
+ 举例

#### 类装饰器
+ 语法
+ 举例


## 类进阶
### 运算符重载
+ 索引和分片
    + \_\_getitem\_\_ 和 \_\_setitem\_\_
+ 迭代器对象
    + \_\_iter\_\_  和 \_\_next\_\_
+ 成员关系
    + \_\_contains\_\_ 、 \_\_iter\_\_ 、 \_\_getitem\_\_
+ 属性引用
    + \_\_getattr\_\_ 和  \_\_setattr\_\_
+ 字符串
    + \_\_str\_\_ 和 \_\_repr\_\_
+ 右侧加法和原处加法
    + \_\_radd\_\_ 和 \_\_iadd\_\_
+ call表达式
    + \_\_call\_\_
+ 比较
    + \_\_lt\_\_  \_\_gt\_\_
+ 布尔
    + \_\_bool\_\_ 和 \_\_len\_\_
+ 析构函数
    + \_\_del\_\_


## 异常进阶
### 异常简介
### 异常类
### 捕获异常-try/except/finally/else
### 抛出异常
+ raise
+ raise/from
### assert
### with/as环境管理器


## 模块进阶
### 模块搜索路径

### 循环导入
+ 为什么会出现循环导入
+ 怎样避免循环导入

### importlib


## 常用标准库和扩展库进阶
### 常用标准库
+ buildins
+ os
+ sys
+ functools
+ json
+ logging
+ multiprocessing
+ threading
+ copy
+ datetime
+ calendar
+ hashlib
+ random
+ re
+ socket

### 常用扩展库
+ requests
+ urllib
+ scrapy
+ beautifulsoup4
+ celery
+ redis
+ Pillow
+ xlsxwriter
+ xlrd
+ haystack
+ elasticsearch
+ pymysql
+ mongoengine/pymongo