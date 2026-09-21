# Statistics-and-dimensionality-reduction
統計學及降維分析整理
## PCA
PCA(Principal Component Analysis, 主成分分析)
是一種常見的降維方法

透過找出原始資料中的變異結構，將原始資料樣本投影至其變異結構上，並計算每個變異結構所包含的資訊量，根據資訊量進行捨棄維度，以達到降低變數數量及包含原始資訊的平衡
## PCA流程
![PCA流程圖](PCA_Flowchart.png)
# 核心公式
## 1、特徵分解
$$
Cv = \lambda v
$$

其中 $C$ 為共變異矩陣， $\lambda$ 為特徵值， $v$ 為特徵向量

特徵值 $\lambda$ ：資料沿著 $v$ 方向的變異量
特徵向量 $v$ ：在資料中的一個變異向量
## 2、投影
## 3、解釋變異度
