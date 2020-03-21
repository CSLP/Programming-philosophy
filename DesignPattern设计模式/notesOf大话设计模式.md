[TOC]

# 大纲

[导学](#导学)



# 导学

### 1. 好程序

* 特点
  * 可维护性（可读，好理解，修改方便）
  * 可扩展性（容易在其基础上扩展新功能）
  * 可复用性
  * 灵活性好
* 可复用!=可复制
  * 业务逻辑与界面逻辑分开，模块化，降低耦合度。才是可复用
* **编程是一门技术，更加是一门艺术** ，**不能只满足于写完代码运行结果正确就完事，时常考虑如何让代码更加简练，更加容易维护，容易扩展和复用，只有这样才可以真正得到提高**。写出优雅的代码真的是一种很爽的事情

### 2. UML图示

##### 1. 类

* 图示
  * ![类.PNG](https://upload-images.jianshu.io/upload_images/8438096-d5826fe0429d1427.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 特征
  * 矩形框
  * 三层
    * 一层类名，抽象类用斜体表示
    * 二层类特性，常为字段和属性
    * 三层方法，行为。
  * \+ public  -  private #  protected

##### 2. 接口图

* 图示
  * ![接口图.PNG](https://upload-images.jianshu.io/upload_images/8438096-036cc754575a115f.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 特征
  * 如图

##### 3. 类之间，类与接口之间的关系

* 继承
  * <img src="https://upload-images.jianshu.io/upload_images/8438096-c72a4188a2389b22.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="继承.PNG" style="zoom:50%;" />
* 实现接口
  * ![实现接口.PNG](https://upload-images.jianshu.io/upload_images/8438096-0676d3567d793b11.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 关联
  * ![关联关系.PNG](https://upload-images.jianshu.io/upload_images/8438096-889a8f7fe81acf4a.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
  * 一个类知道另一个类
* 聚合关系
  * <img src="https://upload-images.jianshu.io/upload_images/8438096-0effb587315340f7.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="聚合关系.PNG" style="zoom:50%;" />
  * 大雁是群居动物，每只大雁都是属于一个雁群，一 个雁群可以有多只大雁。所以它们之间就满足聚合（Aggregation）关系。**聚合表示一种弱的‘拥 有’关系，体现的是A对象可以包含B对象，但B对象不是A对象的一部分** 
* 合成（组合）关系
  * ![合成关系.PNG](https://upload-images.jianshu.io/upload_images/8438096-7f5ce88b484e1e67.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
  * **“合成（Composition，也有翻译成‘组合’的）是一种强的‘拥有’关系，体现了严格的部分和整体的关系，部分和整体的生命周期一样** 
  * 在这里鸟和其翅膀就是合成（组合）关系， 因为它们是部分和整体的关系，并且翅膀和鸟的生命周期是相同的。合成关系用实心的菱形+实线 箭头来表示。另外，**你会注意到合成关系的连线两端还有一个数字‘1’和数字‘2’，这被称为基数。** 表明这一端的类可以有几个实例，很显然，一个鸟应该有两只翅膀。如果一个类可能有无数个实 例，则就用‘n’来表示。关联关系、聚合关系也可以有基数的。”
* 依赖关系
  * ![依赖关系.PNG](https://upload-images.jianshu.io/upload_images/8438096-e6dd68aa8912687d.PNG?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 

​	
