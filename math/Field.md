
## 域

域是一种[集合][Set]，此集合上定义了加/减/乘/除操作

更精确一点是一种可进行加、减、乘和除运算的[代数结构][Algebraic_structure]。
域的概念是数域以及四则运算的推广。

#### 定义

非正式的定义，域是包含了加法(记作 $a + b$)，和乘法(记作 $a \cdot b$) 两个二元运算的集合
两个二元运算与我们熟知的有理数加法乘法类似
另外像在有理数上的运算一样，也有加法逆元 $-a$，和非零元素上的乘法逆元 $b^{-1}$

$$
\begin{aligned}
    a - b & = a + (-b) \\
    a / b & = a \cdot b^{-1}
\end{aligned}
$$

若有 $a, b, c$ 是集合 $F$ 中的元素，若 $F$ 是域，需要满足以下性质
> [结合律][Associative_property]：
> $$
> \begin{aligned}
>     a + (b + c) & = (a + b) + c \\
>     a \cdot (b \cdot c) & = (a \cdot b) \cdot c
> \end{aligned}
> $$
> [交换律][Commutative_property]：
> $$
> \begin{aligned}
>     a + b & = b + a \\
>     a \cdot b & = b \cdot a
> \end{aligned}
> $$
> [单位元][Identity_element]：
> $$
> \begin{aligned}
>     a + 0 & = a \\
>     a \cdot 1 & = a
> \end{aligned}
> $$
> [逆元][Inverse_element]：
> $$
> \begin{aligned}
>     a + (-a) & = 0 \\
>     a \cdot a^{-1} & = 1
> \end{aligned}
> $$
> [分配律][Distributive_property]：
> $$a \cdot (b + c) = (a \cdot b) + (a \cdot c)$$

#### 例子

+ 常见数域，比如复数，有理数等

<!-- end of file -->

[Set]: TODO
[Algebraic_structure]: /math/Algebraic_structure.md
[Associative_property]: TODO
[Commutative_property]: TODO
[Identity_element]: TODO
[Inverse_element]: TODO
[Distributive_property]: TODO
