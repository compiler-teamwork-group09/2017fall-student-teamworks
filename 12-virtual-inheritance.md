# Virtual Inheritance

## 小组成员：

| 姓名   | Github账户  |
| ---- | --------- |
| 陈泳舟  | elvinlife |
| 刑宇   | xyyimian  |
| 庄涛   | Ubpa      |

## 项目简介：

- 单重继承，多重继承的c++实现机制，包括如何消除歧义，实现虚函数
- c++如何处理多重继承中继承格带来的问题及虚继承原理
- c++如何实现多重继承中类的构造，类的析构，及类的控制权限
- 尝试实现一个我们的从C++到C的编译器

### 项目分工：

* 陈泳舟：组内分工；c++虚继承的实现机制，对比与普通多重继承的异同，提供示例。
* 刑宇：c++单重继承，多重继承的实现机制，内存模型详解，并提供示例。
* 庄涛：调研cfront-3编译器的细节。

### 小组交流：

* qq
* 线下图书馆讨论

## 12.23 commit

### 当前进展：

* 小组所有成员看完了Bjarne Stroustrup的《Multiple Inheritance for C++》，基本上了解了C++多重继承与虚继承的机制。
* c++单重继承，多重继承的实现机制的详解，并提供示例。
* 尝试编译cfront-3，但由于版本与年代问题，目前编译还是失败，正在更改源码。

### 下一步计划：

* c++虚继承实现机制的详解，对比其与普通多重继承的异同。
* 调查c++虚继承的应用及其缺陷。
* 编译cfront-3，尝试初步实现我们的编译器。

## 1.3 commit

### 当前进展：

* c++虚继承实现机制的详解，对比了虚继承和普通继承异同。
* 调研了虚继承的优点与缺点。
* 经过努力，但是发现实现cfont-3有些困难，决定放弃

### 下一步计划：

* 详解虚继承中的控制权限，构造函数与析构函数的原理
* 阅读论文《Space and time-efficient memory layout for multiple inheritance》，看一下具体的多继承内存空间优化
* 准备答辩

### 仓库链接：

https://github.com/elvinlife/virtual-inheritance

### 资料链接：

https://en.wikipedia.org/wiki/Virtual_inheritance

http://condor.depaul.edu/dmumaugh/readings/handouts/CSC548/MultipleInheritance.pdf

https://dl.acm.org/citation.cfm?id=320408