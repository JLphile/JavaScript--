## 07. 函数式编程



- 纯函数
  - 数组的两个函数对比
  - 纯函数练习
  
- 函数柯里化
  - 柯里化的过程和结构
  - 单一职责的原则
  - 逻辑的复用
  - 柯里化函数的实现
  
- 组合函数

  - 组合函数的理解

  - 通用组合函数的实现
  
    

## 08. JS-面向对象

- with语句（一般了解）
  - with语句的作用域
  - 不推荐使用
- eval函数（一般了解）
  - eval 全局函数
  - 不推荐使用
- 严格模式 “use strict”；
  - ECMAScript 5标准
  - 常见的限制
- 面向对象
  - 创建对象的两种方式
  - 对对象属性的操作
    - 获取
    - 赋值
    - 删除
  - 添加属性操作限制
    - 数据属性描述符
    - 存取属性描述符

## 09. 对象的隐式原型与函数的显式原型

- 对象定义多个属性描述符
- 对象方法补充
  - 获取某个特定属性描述符
  - 获取所有属性描述符
  - Object的方法禁止给对象添加属性
  - Object的方法禁止对对象进行配置或删除
  - Object的方法禁止对对象进行修改
- 字面量创建
- 工厂模式
- 认识构造函数 constructor
- 对象的原型（隐式原型）
- 函数的原型 （显式原型）
  - constructor属性
  - 自定义属性

## 10~11.原型链和继承

- 可枚举属性的补充
  
- enumerable ：false  设置为false时，浏览器显示为灰色，方便调试
  
- JavaScript中的类和对象

- 面向对象的特性
  - 封装 
  - 继承
  - 多态

- JavaScript的原型链

- Object顶层原型

- Object是所有类的父类

- 继承
  - 父类：公共属性和方法

  - 子类：特有属性和方法

  - 原型链的继承方案

  - 借用构造函数继承
    - 子类 借用 父类的构造函数为自己添加属性并赋值

    - ```js
      function Child(params) {
        Parent.call(this,params)
      }
      Child.prototype=new Parent
      ```

  - 父类原型赋值给子类

    ```JS
    Child.prototype=Parent.prototype
    ```

  - 原型式继承3种方式

  - 寄生式继承（了解）

    - 原型式继承和工厂函数结合

  - 寄生组合式继承（最终方案）

- 判断方法的补充

  - hasOwnProperty
  - in
  - for in
  - instanceof
  - isPrototypeOf

- 对象及函数的原型之间的关系

## 12.  认识class定义类及babel转码解读

- class定义类的方式
- class的构造方法
- class中的方法定义
  -  类的访问器方法
  - 类的静态方法（类方法）
- class中实现继承
  - super  
  - static
- ES 6转ES 5代码
  - babel
- ES 6转ES 5代码的继承
- 阅读Babel源码

## 13. ES 6 存储数据

- Set的基本使用
  -  数据不允许重复
- WeakSet 使用（一般了解）
- Map的基本使用
-  WeakMap的使用













