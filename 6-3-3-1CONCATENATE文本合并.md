# CONCATENATE
*****
函数原型：CONCATENATE(text1, [text2], ...)
*****
函数说明：将多个文本字符串合并成一个文本字符串。
*****
函数例子：
CONCATENATE(A,B,C)，即返回值为ABC
字段或者函数之间，用逗号隔开。
如果是字符串，需要用引号包裹起来。

~~~
CONCATENATE(TEXT(DATE(日期时间), "yyyyMMdd"), "-", 姓名, "-BBY-", 学号)
~~~
实际效果如下：
![](http://docfiles.baibaoyun.com/FlF0gZoDz3uqPUc-67GPSLKBEkr0)