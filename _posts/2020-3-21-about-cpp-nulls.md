---
layout: post
title: c++ | 关于c++的null问题
---

### 1.问题的产生
以前是学Java的，现在玩的是cpp。就觉得Java的null如果可以搬到cpp里多好。然后最近一直在学cpp11新特性,



一不小心看到了nullptr，爽得很哪。不禁起了疑问:NULL,0,nullptr什么区别？
### 2.写个代码实验下
<pre>
<code>
void func(int x)
{std::abort();}
void func(int*x)
{}
</code>
</pre>
func(NULL);执行结果是abort!
