# MLFW #1
---

# 機械学習フレームワークとは

- 機械学習にありがちな処理をモジュール化して、扱いやすくして提供するライブラリのこと

---

# フレームワーク一覧

- TensorFlow (28,779 stars, Python)
- scikit-learn (12,535 stars, Python)
- Caffe (11,481 stars, C++)
- Keras (7,200 stars, Python)
- CNTK (5878 stars, BrainScript)
- MXnet (4,520 stars, various languages)

---

- ConvnetJS (5,163 stars, JavaScript)
- Theano (4,190 stars, Python)
- Chainer (1,533 stars, Python)
- nupic
- torch + nn
- neon
- shogun
- Mahout
- Jubatus
- ...

---

# 比較

---

# [TensorFlow](https://github.com/tensorflow/tensorflow)

- Google
- 28,779 stars (最多)
- Python

---

## Pros

- 分散処理に強い (Distributed TensorFlow)

## Cons

- 記述量が多くなりがち

---

# scikit-learn

- ​David Cournapeau (Google Summer of Code)
- 12,535 stars
- Python

---

## Pros

- 入門に最適

## Cons

- DNNには強くなさそう

---

# [Caffe](https://github.com/BVLC/caffe)

- Berkeley Vision and Learning Center (BVLC)
- protobuf + Python
- 機械学習ライブラリの草分け的存在

---

## Pros

- 高速

## Cons

- 導入が面倒臭い
- protobufがやや面倒臭い

---

# Keras

---

## Pros

- 柔軟に書けそう

## Cons

- 日本語の情報が少ない (公式ドキュメントは一部日本語化された)

---

# Theano

- MILA lab at University of Montreal

---

## Pros

- 自動微分

## Cons

- 導入が微妙に面倒臭い

---

# Chainer

- Preferred Networks
- Python

---

## Pros

- 日本語情報が多い
- 計算グラフの構築の手法が独特

## Cons

- ドキュメント/サンプルが少ない

---

# 学習環境

---

## nVIDIA GPUを搭載したLinuxマシンで学習を行い、モデルを作る

> MacやWindowsで出来なくも無いが、TensorFlowなど、GPU対応していないライブラリが多い
