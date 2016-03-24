# javaScript概述

##程序语言

  * 基础逻辑处理部分
  * 变量 数据类型 (数据存储)
  * 分支和循环运算符    (逻辑操作)
  * 函数（对语言的扩展）
 ### 数据类型
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
```
###运算符
```javascript
+ - * / %
=== !== >  <  >=  <=
&&  ||  !
```
###分支
```javascript
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
```
###循环
```javascript
for(var i=1;i<3;i++){};
while(){
	
}
do{
	
}while()
```
###函数
```javascript
function  XX(){
	
}
var fn = function(x1,x2){ //规范语言
	//argunmets
}
fn(a,b)

function vr(){
	 this.a="a";
	 this.b=function(){

	}
}
vr.prototype.console=function(){
	console.log(this.a);
}
var vr=new vr();
vr.console();
```
//函数的常用方法
//字符串的常用方法
//函数对象中的方法
//对象的增删改查 原型链
//数字对象身上的方法 toFixed()
//Math 对象身上的方法



###针对特定用途的部分
> * 当js来浏览器运行的那一刻
> * 浏览器会创建一个window对象
> * window对象中很多的属性和方法
> * 这写属性和方法不用就加 window.就可以使用
 
###dom对象  dom集合

> 按照我们的正常编程思路

> 第一步找出元素

> 我们从document对象开始 利用它身上的方法

> 找出我们的元素（dom元素或dom集合）

### 选取元素
//dom对象
* var el=document.createElement()  //创建元素节点
* var el document.getElementById()
* var el document.querySelector()       // 不兼容IE6    只获取第一个dir对象

//dom集合
* var el document.getElementsByClassName()
* var el document.getElementsByTagName()
* var el document.getElementsByName()
* var el document.querySelectorAll()   //ie8     值是获取的所有元素的组成的数组

>dom对象

>js会用一个很大的对象来代表页面中我们看到的那个元素


>dom集合

>在一个类数组对象中存储很多的dom对象构成一个集合


### 筛选元素

> 从一个dom对象开始根据逻辑关系再去寻找dom对象

> 父元素

* el.parnetNote
* el.parnetElement


> 子元素
* el.childNotes
* el.nodeChilds

* el.firstChild
* el.firstElementChild


* el.lastChild
* el.lastElementChild

> 兄弟元素

* el.nextSibling
* el.previousSibling
* el.nextElementSibling

### 获取位置信息
* offsetTop   offsetLeft  //获取相对于父元素的坐标
* scrollTop   scrollLeft  //获取具有滚动条元素的位置属性

### 操作属性

* el.setAttribute()    //  设置
* el.getAttribute()    // 获取
* el.removeAttribute()
* el.hasAttribute()
* el.className
* el.id
* el.classList

### 节点操作(NODE)

* el.appendChild()     //插入到最后
* el.removeChild()       
* el.insertBefore()  //插入到某个对象之前
* el.removeChild(删除的对象)     //删除对象只删除表面的，内存还保留
* el.replaceChild(新节点，被修改的节点)；
* el.cloneNode(false/true)


### 获取元素信息（HTMlELEMENT）

* el.offsetWidth;           //获取相对于父元素的坐标
* el.offsetHeight;       
* el.offsetleft;                 
* el.offsettop;
* el.offsetParent;  //具有定位属性的父元素
* el.getBoundingClietRect();  //计算元素距离窗口位置的
* el.innerHTML;
* getCoputedStyle(el,null).width //带单位

### 操作样式

* el.styel(读取行内样式的值，设置行内样式的值)



### 其他

### get和set在对象中的使用
 var obj ={
	a:1,
	b:2,
	set c (X) {console.log(111)};
	get c () {return 5;}
}
