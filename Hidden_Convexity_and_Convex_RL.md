# 隠れ凸性と強化学習

このページでは、隠れ凸性の説明と性質を説明します。

## 目次
* 隠れ凸性の定義
* 隠れ凸性の性質
* 隠れ凸性と強化学習

## 準備

**最適化対象の目的関数**は、
$$
F: \mathcal{X} \rightarrow \mathbb{R} \cup\{+\infty\}
$$
です。ここで、$\mathcal{X}$は$\mathbb{R}^{d}$の閉じていて凸な部分集合です。方策パラメータの場合だとパラメータ空間って閉じて凸なんですかね？

---
隠れ凸性の重要なパーツとなる**写像**を定義します。



$$
c: \mathcal{X} \rightarrow \mathcal{U}
$$
$c$は$\mathcal{X}$を、$\mathbb{R}^{d}$の閉じていて凸な部分集合の$\mathcal{U}$に写す写像です。

---

**写像と逆写像**について定義します。
$\forall x \in \mathcal{X}$、$ \forall u \in \mathcal{U}$について、
$$
\begin{align*}
 &c^{-1}(c(x))= x\\
&c^{-1}(c(u)) = u 
\end{align*}
$$
が成り立つとき、$c$は可逆な写像であると言います。$\mathcal{X}$,
$\mathcal{U}$のどこから出発しても逆写像をすれば元の出発点に戻るイメージです。

---
**集合が凸であること**を定義します。
$\forall u, v \in \mathcal{U}$ と$ \forall \lambda \in[0,1]$ に対して、
$$
(1-\lambda) u+\lambda v \in \mathcal{U}
$$ 
である場合、$\mathcal{U}$ は凸集合であるといいます。

---
**関数が入力の集合に対して強凸・凸であること**を定義します。
関数$H: \mathcal{U} \rightarrow \mathbb{R} \cup\{+\infty\}$が $\mathcal{U}$ に対して$\mu_{H}$強凸であるとは、$\forall u, v \in \mathcal{U}$ と$ \forall \lambda \in[0,1]$ に対して、
$$
H((1-\lambda) u+\lambda v) \leq(1-\lambda) H(u)+\lambda H(v)-\frac{(1-\lambda) \lambda \mu_{H}}{2}\|u-v\|^{2}
$$
が成り立ち、ある$\mu_{H} > 0$が存在することです。

$\mu_{H} = 0$の場合は不等式は以下のようになります。
$$
H((1-\lambda) u+\lambda v) \leq(1-\lambda) H(u)+\lambda H(v)
$$
ある$\mu_{H} = 0$が存在し、上の不等式を満たす場合$H$が $\mathcal{U}$ に対して凸であるといいます。

## 隠れ凸性の定義