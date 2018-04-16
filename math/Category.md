
## 范畴

+ 范畴 = 类 + 态射

范畴是[代数结构][Algebraic_structure]
在其上增加了两个公理：[结合律][Associative_property]，[单位元][Identity_element]

它包含*对象*及*对象之间的箭头*
对象之间的箭头可以结合律的规则互相连接
每个对象有单位元箭头指向对象本身
> 例如，集合的范畴中，对象是集合，箭头是函数

#### 定义
一个范畴$C$包括
+ [对象][Object]构成的[类][Class] $\rm{ob}(C)$
+ [对象][Object]的[态射][Morphism]所构成的[类][Class] $\hom(C)$
    + 每个态射$f$都有唯一的源对象和目标对象,且都在$\rm{ob}(C)$内
        + 记作 $f \vcentcolon a \to b$
+ 态射[复合][Compose] $f \vcentcolon a \to b$和$g \vcentcolon b \to c$可以复合
    + 记作 $g \circ f$ 或 $gf$

## 小范畴

$\rm{ob}(C)$ 和 $\hom(C)$ 都不是[类][Class] 而是[集合][Set]


<!-- end of file -->

[Algebraic_structure]: TODO
[Associative_property]: TODO
[Identity_element]: TODO
[Object]: /math/Object.md
[Class]: /math/Class.md
[Morphism]: /math/Morphism.md
[Compose]: TODO
[Set]: TODO
