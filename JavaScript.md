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

