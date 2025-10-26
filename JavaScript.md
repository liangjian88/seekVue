### 什么是JavaScript 
*  ECMAScript ： ECMA国际描述的JavaScript语言语法 

*  文档对象模式 （DOM）： 描述处理网页内容的方法和接口 

* 浏览器对象模式（bom） ： 描述处理浏览器窗口和交互的方法和接口 


### JavaScript 语言基础

* 有哪些数据类型 ： number string boolean null undefined object function  Symbol

* 

###  基本引用类型
* Object  Array  Date Function 



### 集合引用类型 

*  array  :判断是否是数组  [value instanceof Array]
*  判断数据类型  1.  typeof 42 == "number"   2. [] instanceof Array 3. 精确类型检测： Object.prototype.toString.call(42);   4.  专用类型检测 ： Array.isarray  

* array : 基础操作方法 ：  push   pop unshift  shift  splice（删除 / 添加 / 替换元素）   


###  对象 类与面向对象编程 

*  Object.defineProperty() ： 精确控制属性的行为  

*  Object.assign()  ：  合并多个对象的属性到一个目标对象中 

* 对象的核心  拥有属性 和方法 

* 原型  ： 每个对象都有一个原型对象，它包含了该对象的共享属性和方法。通过原型链，对象可以访问其原型的属性和方法。

*  __proto__：所有对象（包括普通对象和函数对象）都拥有的隐式属性

*  prototype：仅函数对象拥有的属性，指向该函数的 “原型对象”。


### 代理与反射 

*  代理  ： Proxy 对象用于创建一个对象的代理，从而实现基本操作的拦截和自定义（如属性查找、赋值、枚举、函数调用等）。


### 函数 闭包 
* this 引用的是把函数当成方法调用的上下文对象
* 箭头函数   ，this引用的是定义箭头函数的上下文
* 函数还有两个方法  apply call  
* apply()和 call()。这两个方法都会以指定的 this 值来调用函数，即会设
置调用函数时函数体内 this 对象的值并且立即执行 
* call 立即执行 拙个参数传递
* apply 立即执行  数组形式传递
* bind 返回绑定函数  稍后调用  可逐个传递


### 期约与异步函数
* promise  resolve reject  状态  只能从 pending 到 fulfilled 或 rejected ，且只能发生一次。

