向button标签中设置onclick后讲js函数名称放入，可以实现点击
button的时候的js代码的调用
//声明变量
var x= 5; 
var y=6;
var z= 9;
//声明字符串
var person= "laowang";

document.getElementById(访问的对象id).innerHTML= 要插入的内容

定义变量
var x1= 34.00;
var x2 = 34 ;

//科学计数法
var y = 123e5;
var z= 123e-5

定义数组
var cars = new Array() ;
cars[0] = "car1";
cars[1] = "saab" ;
cars[2] = "bmw" ;

或者
var cars = new Array("Saab", "volvo", "bmw") ;
或者
var cars = ["aa", "bb", "cc"] ;

定义键值对形式的字典
var person = {
firstname : "aa" ,
lastname : "dd",
id:6
}
//访问元素
name = person.firstname ;

name=person[firstname] ;
通过null来清空变量

cars = null ;
person = null;

//new来实现声明变量类型的作用
var x = new String ;
var y = new Number ;
var z = new Array ;
var person  = new Object ;

//js对象
不含方法的定义形式和字典差不多
var person = {
name:"ck",
age:12 ,
eyecolor:"black"
sleep:function() {
    alert("hello world!") ;
}
}
调用对象方法
person.sleep() ;

//定义函数

function myFunction() {
    //内容
}
//带参数的函数
function myfucntion(arg1, arg2) {
    //内容
}

//带有返回值的函数
function myfunction(a, b) {
    return a*b ;
}

js的作用域为可访问变量的集合
// 此处不能调用 carName 变量
function myFunction() {
    var carName = "Volvo";
    // 函数内可调用 carName 变量
}

全局变量
var carName = " Volvo";
// 此处可调用 carName 变量
function myFunction() {
    // 函数内可调用 carName 变量
}

javascript事件
html事件时发生在html元素上的事情
当html页面中使用js，javascript可以出发这些事件

html事件可以使浏览器行为，也可以是用户行为

以下是事件的实例：
html页面完成加载，html　input字段改变的时候。
html按钮被点击

html可以添加事件属性，使用js代码来添加html元素
<some-HTML-element some-event='JavaScript 代码'> //单引号和双引号都可以

实例：
<button onclick= "getElementById('demo').innerHTML= Date()">现在的时间?</button>
<p id="demo"></p>

常见的事件:
onchange  html元素改变
onclick    用户点击html元素
onmouseover    用户在一个html元素上移动
onmouseout    用户在一个html元素上移开鼠标
onkeydown    用户按下键盘按键
onload      浏览器已完成页面数据的加载
onfocus  元素获得焦点
onmousemove    鼠标被移动
ondblclick    鼠标双击某个对象
onblur     用户失去焦点
onsubmit      提交按钮被点击
onunload      用户退出页面
onselect  文本被选定
事件可以做什么？

页面加载时触发事件
页面关闭的时候触发事件
用户点击按钮执行动作
验证用户输入内容的合法性
...

html事件属性可以直接执行js代码
html事件可以调用javascript函数
可以为html元素指定自己的事件处理程序
阻止事件的发生

获取时间
var date =new Date() ;

