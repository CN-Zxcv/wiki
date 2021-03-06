
## 向量空间

#### Vector space / Linear space

#### 公理化定义

给定[域][Field] $F$, $F$ 上的向量空间 $V$ 是一个[集合][Set]，其上定义了两种运算：
+ 向量加法 $+$ ：$V \times V \to V$ 把 $V$ 中的两个元素 $u$ 和 $v$ 映射到 $V$ 中另一个元素，记作 $u + v$
+ 标量乘法 $\cdot$ ：$F \times V to V$ 把 $F$ 中的一个元素 $a$ 和 $V$ 中的一个元素 $u$ 变为 $V$ 中的另一个元素，记作 $a \cdot u$

$V$ 中的元素称为向量，相对地，$F$ 中的元素称为标量
<!-- end of file -->

#### 例子

给定了直角坐标系的平面：平面上的每一点 $P$ 都有一个坐标 $P(x,y)$，并对应着一个向量 $(x, y)$。
所有普通意义上的平面向量组成了一个空间，记作 $\mathbb{R}^{2}$ ，因为每个向量都可以表示为两个实数构成的有序数组 $(x, y)$。
可以验证，对于普通意义上的向量加法和标量乘法，$\mathbb{R}^{2}$ 满足向量空间的所有公理。
实际上，向量空间是 $\mathbb{R}^{2}$ 的推广。

[Set]: TODO
[Field]: /math/Field.md
