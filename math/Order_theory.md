## 序理论

研究捕获数学排序的直觉概念的各种二元关系
比如次序，每个元素都是可以比较于另一个元素，比如
> 自然数：一个元素，它或者大于、或者小于、或者等于另一个元素
> 集合：如果 $A \subseteq B$，则B被称为小于等于A。
>> 然而有些集合不能在这种方式来比较，因为其中每个都包含着其他集合中不存在的某些元素

当集合内的所有元素都是可以互相比较的时候，称为**全序**
当只有部分可以进行比较的时候，称为**偏序**

### 定义

假定 $P$ 是集合，且 $\leq$ 是在 $P$ 的关系，若 $\leq$ 是个偏序，需要满足
> [自反性][Reflexive_relation]： $a \leq a$
> [反对称性][Antisymmetirc_relation]：如果 $a \leq b$ ，并且 $b \leq a$ ，则 $a = b$
> [递移性][Transitive_relation]： 如果 $a \leq b$ ，并且 $b \leq c$ ，则 $a \leq c$

<!-- end of file -->

[Reflexive_relation]: TODO
[Antisymmetirc_relation]: TODO
[Transitive_relation]: TODO
