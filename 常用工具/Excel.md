# Excel使用

## VLOOKUP函数

该函数的语法规则如下：

```
VLOOKUP(lookup_value,table_array,col_index_num,range_lookup)
```
|参数|简单说明|输入数据类型|
|-----|------|------|
|lookup_value|要查找的值|数值、引用或文本字符串|
|table_array|要查找的区域|数据表区域|
|col_index_num|返回数据在查找区域的第几列数|正整数|
|range_lookup|模糊匹配/精确匹配|TRUE/FALSE（或不填）|

常见错误：https://jingyan.baidu.com/article/46650658c5cf60f549e5f809.html

## 如何将二维表变成一维表

### 逆透视法

如何将二维表a转换成一维表b

|部门、年度|2018|2019|
|----|-----|------|
|IT|1|2|
|QA|3|4|

二维表a

|部门|年度|经费|
|---|---|---|
|IT|2018|1|
|IT|2019|2|
|QA|2018|3|
|QA|2019|4|

 一维表b
 
 1、快捷键：ALT +D +P ，调用多表数据透视，选择“多重合并计算区域”，创建单页字段
 
 2、选定数据区域，添加到下方范围

 3、现在只需双击右下角的总计，见证奇迹的时刻到了
 
 参考：http://www.xuexila.com/excel/2010/363490.html
 
 
 ## power query法
 参考：http://www.360doc.com/content/16/0803/07/30583536_580403530.shtml
