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


