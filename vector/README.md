向量
===

## 基本观念

* 向量 (Vector) 的书写方式跟点 (Point) 很类似，都是用 (X, Y) 描述，但在意义上，向量主要用于说明以原点 (0, 0) 为中心往某个「__方向__」的「__动量__」。所以：

    $\vec{a}$ = (3, 4) 表示在平面空间中从 P(0, 0) 往 P(3, 4) 的动量。

* 因向量具备「动量」特值，所以纵使二向量如 $\vec{a}(3, 4)$ 与 $\vec{b}(6, 8)$ 朝向同一方向，但后者的「动量」是前者的两倍，也就是说 $\vec{b}(6, 8) = 2\vec{a}(3, 4)$ 。

* 向量可以转弯、增减，所以：

    $\vec{a}(3, 0) + \vec{b}(0, 4) = \vec{c}(3, 4)$

* 向量变成纯量
  
    $|\vec{a}| = \sqrt{X^{2} + Y^{2}}$

* $\vec{a}$ 的垂直向量

    $\vec{b}(-Y, X)$ 或 $\vec{b}(Y, -X)$

## 内积 $\vec{a}\cdot\vec{b}$

### 二维空间

* $\vec{a}\cdot\vec{b} = ({X_{a}}{X_{b}}+{Y_{a}}{Y_{b}}) = |\vec{a}||\vec{b}|\cos\theta$

* $\vec{a}$ 在 $\vec{b}$ 上投影的长度 $\displaystyle\frac{\vec{a}\cdot\vec{b}}{|\vec{b}|}$


## 外积 $\vec{a}\times\vec{b}$

### 二维空间

* $\vec{a}\times\vec{b} = {X_{a}}{Y_{b}} - {X_{b}}{Y_{a}} = n|\vec{a}||\vec{b}|\sin\theta$，n 在三度空间中，根据方向为 +1 或 -1。

* $\vec{a}$ 在 $\vec{b}$ 上的垂直距离 $\displaystyle\frac{\vec{a}\times\vec{b}}{|\vec{b}|}$



## 常用的应用

### 1. 求取一点 P 到一线 L 的距离
1. 在 L 上随意取两点 A & B，可得到向量 

   $\vec{AP} = P - A$ 
   
   $\vec{AB} = B - A$

2. 根据外积公式推导

   $|\vec{AP}|\sin\theta = \displaystyle\frac{{X_{ap}}{Y_{ab}} - {X_{ab}}{Y_{ap}}}{|\vec{AB}|}$

### 2. 求取向量 $\vec{a}$ 投射在向量 $\vec{b}$ 上的长度

1. 根据内积公式推导

   $|\vec{a}|\cos\theta = \displaystyle\frac{({X_{a}}{X_{b}}+{Y_{a}}{Y_{b}})}{|\vec{b}|}$

### 3. 求取向量 $\vec{a}$ 旋转 $\theta$ 度后的向量

1. 转后的向量假定为 $\vec{b}(X, Y)$，其中 $|\vec{a}|=|\vec{b}|$，根据内外积公式可得下列二元一次联立方程式

   ${X_{a}}X+{Y_{a}}Y = |\vec{a}|^{2}\cos\theta$

   ${X_{a}}Y-{Y_{a}}X = |\vec{a}|^{2}\sin\theta$

2. 求二元一次方程式解

   $X = {X_{a}}\cos\theta - {Y_{a}}\sin\theta$
   
   $Y = {X_{a}}\sin\theta + {Y_{a}}\cos\theta$


