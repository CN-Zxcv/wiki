## 态射

+ 态射 = 数学结构 + 关系

两个数学结构之间保持结构的一种过程抽象。
在某种意义上保持结构的函数或映射。
> 集合论中，态射就是函数；
> 群论中，它们是群同态；
> 在拓扑学中，它们是连续函数；
> 泛代数（universal algebra）的范围，态射通常就是同态。

#### 定义

有两个操作定义在每个态射上，定义域和对应域。

态射经常用从域到他们的陪域的箭头来表示
> 例如，若一个态射 $f$ 域为 $X$ 而陪域为 $Y$ ，它记为 $f \vcentcolon X \to Y$。
> 所有从 $X$ 到 $Y$ 的态射的集合记为 $homC(X,Y)$ 或者 $hom(X, Y)$ 。
>> 有些作者采用 $MorC(X,Y)$ 或 $Mor(X, Y)$。

对于任意三个对象$X$，$Y$，$Z$，存在一个二元运算 $hom(X, Y) \times hom(Y, Z) \to hom(X, Z)$ 称为复合。
$f \vcentcolon X \to Y$ 和 $g \vcentcolon Y \to Z$ 的复合记为 $g \circ f$ 或 $gf$（有些作者采用 $fg$ ）。

态射必须满足两条公理：

[单位元][Identity_element]存在恒等态射：对于每个对象 $X$ ，存在一个态射 ${\rm {id}}_X \vcentcolon X \to X$ 称为 $X$ 上的恒等态射，使得对于每个态射 $f \vcentcolon A \to B$ 我们有  ${\rm {id}}_{B}\circ f=f=f\circ {\rm {id}}_{A}$。
[结合律][Associative_property]： $h\circ (g\circ f)=(h\circ g)\circ f$ 在任何操作有定义的时候。

<!-- end of file -->

[Identity_element]: TODO
[Associative_property]: TODO
