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
 
dom对象  dom集合


### 选取元素

* var el document.getElementById()
* var el document.getElementsByClassName()
* var el document.getElementsBYTagName()
* var el document.getElementsName()

### 筛选元素
* el.parnetNote
* el.childNotes
* el.firstChild
* el.lastChild
* el.nextSibling
* el.previousSibling
### 操作样式
* el.styel.属性
* el.currentStyle.属性
* getComputedStle(el,null).属性

### 获取位置信息
* offsetTop   offsetLeft  //获取相对于父元素的坐标
* scrollTop   scrollLeft  //获取具有滚动条元素的位置属性
### 操作属性
* el.属性
* el.属性=值

### 节点操作
* document.createElement("div")  //创建元素节点
* arrt=document.createAttribute();
  arrt.nodeValue=""
  obj.setAttributeNode(arrt)
* el.innerHTML="";               //创建属性节点
* document.createTexTNode()
* 父对象.appendChild(el)     //插入到最后
* 父对象.insertBefore(el，之前的对象)  //插入到某个对象之前
* 父对象.removeChild(删除的对象)     //删除对象只删除表面的，内存还保留
* 父对象.replaceChild(新节点，被修改的节点)；
* var newobj=obj.cloneNode(false/true)
  父对象.appendChild(newobj)
### 其他