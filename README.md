# SIGNATE_Practice_Image_Labeling20
Machine Learning practice using SIGNATE competition data

[Reference](https://signate.jp/competitions/108)

# 目次
1. [概要](#anchor1)
2. [評価方法](#anchor2)
3. [ルール](#anchor3)
4. [スケジュール](#anchor4)
5. [情報公開ポリシー](#anchor5)
6. [データ](#anchor6)


<a id="anchor1"></a>
# 概要
画像データに対して、20種類のラベルの1つを割り当てるモデルを作成する
**データ概要**
課題種別：分類
データ種別：画像
サンプル数：50,000
画像サイズ：32×32

**データソース**
[Link](https://www.cs.toronto.edu/~kriz/cifar.html)

<a id="anchor2"></a>
# 評価方法
評価関数：Log Loss
$$
LogLoss = -\frac{1}{n}\sum_{i=1}^n\sum_{j=1}^{m}y_{ij}\log(\hat{y}_{ij})
$$