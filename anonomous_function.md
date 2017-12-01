###自执行匿名函数
1. 常见格式
```
 (function(){
   /*code*/
   })();
```
2. 作用

> 外部就不能访问，除非你允许(变量前加上window，这样该函数或变量就成为全局).
> 执行函数的作用主要为 匿名 和 自动执行,代码在被解释时就已经在运行了。

3. 其它格式
```
(function () { /* code */ } ());  // 与(function(){ })();相等
!function () { /* code */ } ();
~function () { /* code */ } ();
-function () { /* code */ } ();
+function () { /* code */ } ();

```
