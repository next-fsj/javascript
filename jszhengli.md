# javaScript概述

##程序语言

*基础逻辑处理部分
  *变量 数据类型 (数据存储)
  *分支和循环运算符    (逻辑操作)
  *函数（对语言的扩展）
```javascript
var vr=1.2;            //Numeber
var vr="asd";          //String
var vr=1.2;            //Numeber
var vr=null; 
var vr=true;           //Boolean
var vr=function(){};   //Function
var vr=underfing;
var vr=[1.2.3];        //数组Array
var vr= {a:1,a:2};     //Object 对象

+ - * / %
=== !== >  <  >=  <=
&&  ||  !

if()
if()else
if()else if()else if()
swith(x){
	case 1:
	break;
	case 2:
	break;
	default:
	beak;
}
for(var i=1;i<3;i++){};
while(){
	
}
do{
	
}while()


function  XX(){
	
}
var fn = function(x1,x2){ //规范语言
	//argunmets
}
fn(a,b)

//函数的常用方法
//字符串的常用方法
//函数对象中的方法
//对象的增删改查 原型链
//数字对象身上的方法 toFixed()
//Math 对象身上的方法
function A(c){
	this.x=c;
}
A.p
new A(1);
```
**针对特定用途的部分
> *当js来浏览器运行的那一刻
> *浏览器会创建一个window对象
> *window对象中很多的属性和方法
> *这写属性和方法不用就加 window.就可以使用
setInterval
document.getElementById()

### 选取元素

* var el document.getElementById()
* var el document.getElementsByClassName()
* var el document.getElementsBYTagName()
* var el document.getElementsName()

### 筛选元素
*
### 操作样式
### 获取位置信息
### 操作属性
### 节点操作
### 其他