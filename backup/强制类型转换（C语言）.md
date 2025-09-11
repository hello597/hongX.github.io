# 强制类型转换
格式：（类型）值。
```c
int i = 11;
double s = (double)i;
```
强制转换的优先级高于运算符。
```c
int i = (double)(a/d);
```
此时先运行a/d，再转换。
