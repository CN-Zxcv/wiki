## 函数

在数学中表示为两个[集合][Set]之间的对应关系；输入值集合中的每项元素都能对应**唯一**的输出值集合中的元素

某个输入值称作函数的[参数][Argument]，某个输出值称作函数的[值][Value]

所有输入值的集合被称为[定义域][Domain]
所有输出值的集合被称为[值域][Range]或者[像][Image]
包含了值域的更大的集合被称为[对应域][Codomain]

所有的输入输出对的关系，被称为[函数图形][Graph_of_function]

在大部分数学领域，[对应](TODO),[映射](TODO),[变换](TODO)通常是函数的近义词

> 对于函数$f(x) = x^2$，我们说
>> 定义域和对应域是实数
>> 函数的像是非负实数
>> 函数图形指所有的序对$(x, x^2)$

具有相同的定义域和定义域的函数的集合称为[函数空间][Function_space]
> 相关学科有[实变函数论][Real_analysis]，[复分析][Complex_analysis]，[泛函分析][Functional_Analysis]

### 定义

从输入值集合$X$到可能的输出值集合$Y$的函数$f$是$X$与$Y$的关系,满足
>  1. $f$是**完全**的：对每一个输入值， $y$中都有与之对应的输出值
>  2. $f$是**多对一**的：多个输入可以映射到一个输出，但一个输入不能映射到多个输出

若只满足条件1，被称为[多值函数][Multivalued_function]
若只满足条件2，被称为[偏函数](TODO)

### 函数的符号

通常函数被记作
    $$x \xrightarrow{f} y$$
或
    $$f:X \to Y$$
或
    $$y=f(x)$$

有时候我们更希望讨论函数和值之间的[二元性][Duality]的时候，将函数和值区别开来就很重要了。这种情况下我们将函数和参数在同一层次上进行表示会更好。其中一种表达方式是使用*方括号*$[x,f]$和$\mapsto$来代替$f(x)$

这时函数可以表示成
$$f \mapsto [x_0, f] = f(x)$$

我们简单的定义一个函数的时候使用$ \mapsto $是很方便的,例如
    $$ x \mapsto 4 - x $$

但是要完整的描述一个函数，我们需要使用如下的形式

$$\begin{aligned}
f: \mathbb{N} & \to \mathbb{Z} \\
    x & \mapsto 4 - x
\end{aligned}$$

> 第一行定义函数的名字，定义域，对应域
> 第二行定义函数本身

使用简单形式的时候，如果在不同的环境中使用(定义域或者定义域不同)，两者其实是完全不同的函数，虽然函数本身形式是一致的

$$\begin{aligned}
f: \mathbb{Z} & \to \mathbb{Z} \\
    x & \mapsto 4 - x
\end{aligned}$$



<!-- end of file -->
[Set]: /math/Set.md
[Domain]: /math/Domain.md
[Codomain]: /math/Codomain.md
[Image]: /math/Image.md
[Graph_of_function]: /mah/Graph_of_function.md
[Function_space]: /math/Function_space.md
[Real_analysis]: TODO
[Complex_analysis]: TODO
[Functional_Analysis]: TODO
[Multivalued_function]: /math/Multivalued_function.md
[Range]: /math/Range.md
[Argument]: TODO
[Value]: TODO
[Duality]: /math/Duality.md
