## 函子

函子是范畴间的一类映射
[小范畴][Small_category]范围内的态射

#### 定义

设$C$和$D$为[范畴][Category]，从$C$至$D$的函子为映射$F$
+ 将每个对象$X \in C$映射至对象$F(X) \in D$上
+ 将每个态射$f : X \to Y \in C$映射至态射$F(f) : F(X) \to F(Y) \in D$上，使满足以下条件
    + 对任何对象$X \in C$，恒有$F(id_X) = \rm{id}_{F(X)}$
    + 对任何态射$f : X \to Y$，$g : Y \to Z$，恒有$F(g \circ f) = F(g) \circ F(f)$

### 双函子与多函子

### 遗忘函子
遗忘函子 $U:{\mathcal {C}}\to \mathbf {Set}$ ，此函子将一个对象映至其下的集合；换言之，此函子“遗忘”所有代数操作

### 自由函子
遗忘函子 $U:{\mathcal {C}}\to \mathbf {Set}$
若$U$有左伴随函子 $F:\mathbf {Set} \to {\mathcal {C}}$，则称之为 $\mathcal{C}$的自由函子

<!-- end of file -->

[Small_category]: /math/Category.md
[Category]: /math/Category.md
