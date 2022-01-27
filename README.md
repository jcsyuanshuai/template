# 开发手册

本手册尝试通过回答以下问题来做好相关的理论和实践总结。通过剖析合适的例子，来践行理论。

1. 如何编写代码？(核心概念)
2. 如何写好代码？(编程规范、注意事项、良好习惯、经典算法、设计模式)

重要的概念知识将会总结在下

## 编程语言

想要开始编写代码的唯一方式就是开始学习一门编程语言，掌握该其基本概念，学习其基本语法，了解其核心特性。

现代所有的高级语言都有一套基本通用的概念，如：

- 表达式和语句(expression & statement & keyword)
- 变量和常量(constants & variable)
- 函数(function)
- 数据类型(data type)
- 控制流(control flow)
- 常用集合(common collection)
- 代码管理(package、crate、module)
- 错误处理(error exception、panic)
- 单元测试(unit test)
- 面向函数
- 面向对象
- 并发模型

程序代码是有表达式和语句构成的，每种语言的对语句和表达式的划分都有所不同，但是其主要区别在于表达式可以被计算、求值的，是具有返回的，而语句只是表示一种过程。表达式总体上是语句的一部分。

程序中大部分都是由语句构成的，大部分语句中都含有关键字，其包含的关键字可以确定该语句的作用。

语句按照用途可以划分为，声明语句、赋值语句、控制语句(表达式)、引包语句；

引包语句

声明语句往往以特定含义的关键字开头，比如声明一个变量、函数、类型、包；

赋值语句往往包含"="，"="后往往是表达式；

控制语句由表示控制的关键字开头，比如 `if () {}else if () {} else{}` 表示判断，选择；比如`while` 和`for` 表示循环；

## 编程规范

## 注意事项

## 良好习惯

## 经典算法

## 设计模式

- 创建型
  - 单例：一个类只能创建一个对象或者实例
  - 工厂：用来创建对象实例
  - 构建：
  - 原型
- 结构型
  - 代理
  - 桥接
  - 装饰
  - 适配
  - 门面
  - 组合
  - 享元
- 行为型
  - 模板
  - 策略
  - 职责
  - 状态
  - 迭代
  - 访问
  - 备忘
  - 命令
  - 解释
  - 中介