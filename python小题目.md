1、表达式(1 == 2 != 3)的输出结果是？

A、True                B、False

2、定义一个函数

```
def foo(*args):
     return len(args) and max(args) - min(args)           
```

`foo()`和`foo(1, 2, 3, 4, 5)`分别输出什么？

A、False/True		 B、4/0

3、`i = i+1` 和`i += 1`有区别吗？

A、有				B、没有

4、给定一个数字型字符串，找出字符串中重复的连续的3个数字？

For example: if the string was: `123412345123456` 程序输出:

```
123 - 3 times
234 - 3 times
345 - 2 times
```



解答：

1、A

https://docs.python.org/2.3/ref/comparisons.html

2、B

https://docs.python.org/3/reference/expressions.html#and

3、A

https://docs.python.org/3/reference/datamodel.html#emulating-numeric-types