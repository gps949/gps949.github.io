---
layout: post
title: 这里是真标题
categories: [分类1, 分类2]
description: 这是一篇测试用日志，没有实际意义
keywords: c++, 关键词2
---

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$


~~~ c
#include <stdio>
int main(){

}
~~~

# 这里是标题
> 我们还未知道那天所见的花的名字

```c
#include <stdio>
int main(){
	return 0;
}
```
- 这就是一篇测试，仅此而已




 $$
 \begin{align*}
  2^x + \alpha \cdot \vec{\beta} 
  \end{align*}
 $$ 




|---
| Default aligned | Left aligned | Center aligned | Right aligned
|-|:-|:-:|-:
| First body part | Second cell | Third cell | fourth cell
| Second line |foo | **strong** | baz
| Third line |quux | baz | bar
|---
| Second body
| 2 line
|===
| Footer row


----

*The End*