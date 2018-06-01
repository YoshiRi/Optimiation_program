# Convex Optimization
> Slides p70
> 
## 自分メモ
- Convex Optimization problem
最小化するfがconvex，制約がAffine.この制約は式変換可能。
AffineとはAx+bのアレ。
- Local optimal = Global optimal
- p82 epigraph form 領域の最小値とその外縁の最小値は同じ的な。
- p83 quasi convex 疑似凸関数。凸とは任意の端点間の線分が関数fより大きいことだが，疑似凸とはもう少しその条件がゆるい。
- Linear Problem 目的も制約もAffine。多くの問題をこれに変換可能。
- p89 Linera-Fractional，fが分母分子がAffine。bisectionでもLPでも解ける。
- Quadric Problem 目的が2次。制約はAffine。
- QCQP：目的も制約もQuad
- Robust linear programming:制約も目的もLinearだが不定
- 