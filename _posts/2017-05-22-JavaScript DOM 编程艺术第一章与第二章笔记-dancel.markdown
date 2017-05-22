---
layout: post
title:  "搭建个人博客"
date:   2017-05-07 18:16:23 
categories: blog
---

# JavaScript 简史
## 浏览器内核
- chrome，safari 浏览器内核：`webkit`
- IE 浏览器内核：`trident`
- firefox 浏览器内核： `gecko`
## JavaScript 发展历程
- 网景公司与微软大战之后出现 W3C 组织
- 由 W3C 组织制定喝推荐各项标准


# JavaScript 语法
## 语法
>  注释： // /* */ <--! -->

```
// 这是一个注释
    var a = '姚烈坤大傻逼'
/* 这是一个注释
    这是一个注释*/
    
```

>  变量：var 

```
// 定义变量
    var mood = 'happy', age = 24;
    var mood = 'happy',
            age  = 24;
    var mood = 'happy';
    var age  = 24;
```
>  数据类型-字符串

```
// 定义字符串
     var mood = 'don\'t ask' 
```
>  数据类型-数值

```
// 定义数值
    var age = 18;
    var float = 2.1234;
    var tem = -20;
```
>  数据类型-布尔值

```
// 定义布尔值
    var sleeping = true;
    var sleeping = false;
```
>  数组

```
// 创建数组
    var arr = new Array();
    var arr = [];
// 下标从0开始，取值arr[index] = element
    
```
>  对象

```
// 创建对象
    var obj = new Object();
    var obj = {};
    //内建对象 自身包含的方法
    //宿主对象 浏览器提供的方法
// 取对象数值obj.name = value
```
###  算术操作符
- 加 `+` ，数字加减，字符串拼接
- 减 `-` ，减法
- `++i` ,`--i` 先运算再赋值，自加与自减
- `i++` ,`i--` 先赋值在运算，自加与自减
- 乘 `*`,乘法
- 除 `/`,除法
###  条件语句

```
if(true){
    ...
    //do it something 
    }else{
    ...
    //do it something   
    }
```
### 逻辑操作符
- `&&` 逻辑与 当一个值符合两个条件时为true
- `||` 逻辑或 当一个值满足一个条件时为true
- `!`  逻辑非 值取反
### 循环语句

```
// 判断循环
    while (true){
        ....
        //do it something
    }
// 循环判断
    do{
        ....
        //do it something
    }while (true);
// for 循环
    for (var i; i<10; i++){
        ....
        // do it something
    }
```
###  函数

```
//创建函数
    var a = new Function();
    var a = function(){
        ....
    }
    function a(){
        
    }
```
