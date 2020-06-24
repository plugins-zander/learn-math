# Introduction



[mubu](https://share.mubu.com/doc/sxxO6Q3Be0)

<iframe width="100%" height="1000" src="https://mubu.com/doc5vFUpm-F6u_" allowfullscreen="allowfullscreen" frameborder="0"></iframe>
+ 演算长公式用行内公式
  + 为了让其左对其，katex不支持环境
+ 极限用`^_`不规范
  + 为了让其显示为标准行间公式排版，katex行间公式极限格式和行内的一样

+ 部分三角反三角不规范
  + 部分三角反三角没有加`\`,加后katex没法解释，`arccot{x}`
  + 需要添加括号`\arcsin{x}`



+ 引用行内不要

> 若$\left\{ 
> \begin{array}{ll} 
> 0<(\exist) N<n \\
> 0<|a_n-A|< (\forall)\varepsilon 
> \end{array} \right.$称   $^{\lim}_{n \rightarrow \infty}a_n=A$

> 若$\left\{ 
 \begin{array}{ll} 
 0<(\exist) N<n \\
 0<|a_n-A|< (\forall)\varepsilon 
 \end{array} \right.$称   $^{\lim}_{n \rightarrow \infty}a_n=A$

$\left | 
\begin{array}{ll} 
0 & 0  \\
0 & 0 \end{array} \right|$

$$
\left\{ 
\begin{array}{ll} 
a \\
b 
\end{array} \right.
$$


+ draw.io中
  + `$$ a^2 $$`包裹行间公式
  + `\( a^2 \)`包裹行内公式
  + https://desk.draw.io/support/solutions/articles/16000032875





+ 三角
  + `\sin{x}`
  + `\ln{}`



+ 数组

```
\left\{ %%% 开始左边大括号，还可以 （ |
\begin{array}{ll}  %%% 开始数组，{ll}表示，两列，左对齐 还可以 {ll|l}三列，第三列和第而列中间有竖线
f(0)=0 & \\   %%% & 表示对齐 \\表示换行
f'(x)>0 & (x>0)
\end{array}\right.  %%% \right. 省略左边大括号
```

