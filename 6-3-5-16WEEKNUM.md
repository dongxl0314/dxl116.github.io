# WEEKNUM
*****
函数原型：WEEKNUM(date, return_type)
*****
函数说明：返回特定日期的周数。
*****
函数例子：
例如，包含1月1里的周为该年的第1周，其编号为第1周。

* data: 必需。指定日期。代表一周中的日期。应使用DATE函数输入日期，或者将日期作为其他公式或函数的结果输入

* return_type: 可选。一数字，确定星期从哪一天开始。默认值为1。

|return_type|一周的第一天为|
|---|---|
|1或省略|星期日|
|2|星期一|
|3|星期二|
|4|星期三|
|5|星期四|
|6|星期五|
|7|星期六|


![](http://docfiles.baibaoyun.com/FiBrrXngWIkeiuz1_JYbN4Bz_-Nk)

如下图：2018-01-14 是周日，如果按照周日来计算周数，那么是第三周，如果是按照周1计算，那么是第周二。
![](http://docfiles.baibaoyun.com/FqFHZOBCpJ_tm2FtMalMsldm-AEA)
