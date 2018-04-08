## 反函数 / 逆函数

设$f$为一函数，定义域为$X$，值域为$Y$，
如果存在函数$g$,其定义域为$Y$，值域为$X$，
并对每一$x \in X$有：

$$g(f(x))=x$$

则称$g$为$f$的反函数，记为$f^{-1}$

> 例如，若给定一函数
>
> $$ f : x \mapsto 3x + 2 $$
>
> 则其反函数为
>
> $$ f^{-1} : x \mapsto \frac{x - 2}{3}$$

若一函数有反函数，此函数便称为**可逆的**

### 存在性

如果一函数$f$有反函数，$f$必须是一[双射][Bijection]函数，即：

+ [单射][Injective_function]: [对应域][Codomain]上的每一元素都只被$f$映射至多一次
+ [满射][Surjective_function]: [对应域][Codomain]上的每一元素都必须被$f$映射到

不然将没有办法对某些元素定义f的反函数

<!-- end of file -->

[Bijection]: TODO
[Injective_function]: TODO
[Surjective_function]: TODO
[Codomain]: /math/Codomain.md
