# Cherry

![Cherry](http://47.108.189.192/Pymili/logo.ico)
樱桃是红色的

解释性语言

使用Python编写 Python编写的解释器 --> 解释代码 --> 转换为Python语言

版本：0.3vBeta

作者:PYmili

![PYmili](http://47.108.189.192/Pymili/image/PYmili.jpg)

Email：2097632843@qq.com

## 文件后缀名

任何后缀名文件都可以识别运行!只要写了一样的代码！

### 配置Cherry变量环境后windows终端输入:Cherry -r 此处填写要编译的文件

# 现已完成功能

## 1.基本变量定义

var_int=<此处填写数字>; 	 简介：这是一句赋值数字的语句

var_str="此处填写字符串"; 	 简介：这是一句赋值字符串语句

var_var=var_str;  	简介：这是赋值变量名给变量的语句

var_float=F<此处填写数字>;	简介：这是一句赋值浮点数的语句

## 2.Print输出

var_str="Hello Cherry !  Hello PYmil !";

Print Var var_str;	简介：这是输出上方变量的值

Print_Str "此处填写字符串";	简介：这是输出字符串语句

Print_Int <此处填写数字>;	简介：这是输出数字的语句

## 3.加减乘除

### 加法 plus

num_a=<1>;

num_b=<2>；

plus=a<plus>b;	简介：这就是一句两数相加的函数plus，必须是被定义变量才能相加

Print Var plus;

### 减法 reduce

num_a=<1>;
  
num_b=<2>；
  
er=a<reduce>b;	简介：这就是一句减法的函数reduce，必须是被定义变量才能运行
  
Print Var er;

### 乘法 ride

num_a=<1>;
  
num_b=<2>；
  
e=a<ride>b;	简介：这就是一句两数乘的函数plus，必须是被定义变量才能运行
  
Print Var e;

### 除法 exc

num_a=<1>;
  
num_b=<2>；
  
exc=a<exc>b;	简介：与前面相同使用方法，只是变成除法
  
Print Var exc;

# 输入 Input

mess=Input "这里随意填写";	简介：这就是Input函数使用方法
  
Print Var mess;	Print即可输出出来

# 列表 List

### 创建列表

msg=List_Str【我,是,PYmili】;	创建一个字符串列表，注意！【】这个符号是中文符号！

msg_num=List_Num【1,10,50,1.131415962】;	创建一个数字列表

### 访问列表值

msg=List_St【1,2,3】;

mess=List【msg<1>】	访问；列表msg中的位于1的值也就是"2"可访问位置看列表有多少从0开始计算

Print Var mess;	即可访问值

### 删除列表指定值 remove

msg=List_Str【a,b,c】;

msg remove【a】;	删除值‘a’

### 添加值 addto

msg=List_Str【a,b,c】;

msg addto<此处填写要添加至的位置如：1或2>【要添加的内容】		添加值