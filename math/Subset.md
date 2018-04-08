## 子集

若$A$和$B$为集合，当$A$的所有元素都是$B$的元素，则称$A$是$B$的子集，$B$是$A$的超集。

### 符号

子集记作

$$ A \subseteq B $$

超集记作

$$ B \supseteq A $$

> $ \subseteq $ 表示任何子集
> $ \subsetneq $ 表示真子集
> $ \subset $ 有人用它表示真子集，也有人用它表示子集，所以*最好不用*

### 性质

- 任意集合是自身的子集，但不是真子集
    - 空集 $\emptyset$ 是任意集合的子集。
    - 空集是除了自身意外的其他集合的真子集。
- 若$A$，$B$，$C$是集合，则
    - 自反性:
        - $ A \subseteq A $
    - 反对称性
        - $ A \subseteq B $ 且 $ B \subseteq A $ 当且仅当 $ A = B $
    - 传递性
        - 若 $ A \subseteq B $ 且 $ B \subseteq C $ 则 $ A \subseteq C $
- 若 $A$，$B$，$C$ 是 $S$ 的子集，则
    - 存在一个最小元和一个最大元
        - $ \emptyset \subseteq A \subseteq S $
    - 存在并运算
        - $ A \subseteq A \cup B $
        - 若 $ A \subseteq C $ 且 $ B \subseteq C $ 则 $ A \cup B \subseteq C $
    - 存在交运算
        - $ A \cap B \subseteq A $
        - 若 $ C \subseteq A $ 且 $ C \subseteq B $ 则 $ C \subseteq A \cap B $
- 对任意集合 $A$ 和 $B$，下列表述等价
    - $ A \subseteq B $
    - $ A \cap B = A $
    - $ A \cup B = B $
    - $ A - B = \emptyset $
    - $ B' \subseteq A' $
