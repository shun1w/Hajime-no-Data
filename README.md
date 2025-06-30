# Hajime-no-Data
Python超入門

# はじめてのデータ分析

このリポジトリは、プログラミング初心者や医学生がデータ分析と機械学習の基礎を学ぶためのJupyter Notebookを提供します。

## ファイル概要

### 1. `Python.ipynb`
- **対象者**: Pythonプログラミングが初めての方
- **学習内容**:
  - Pythonの基本的な構文（`print`, 変数, リスト, ループ, 関数など）
  - データ分析ライブラリ`pandas`の基礎
  - データ可視化ライブラリ`matplotlib`を使ったグラフ作成
- **目標**: Pythonを使った基本的なデータ操作と可視化ができるようになる

### 2. `Statistics_basics.ipynb`
- **対象者**: 医学生・医療従事者で統計分析の基礎を学びたい方
- **学習時間**: 約30分
- **学習内容**:
  - **実データ（Pima Indians Diabetes Dataset）**を用いた統計分析
  - **記述統計**: データの要約と可視化
  - **相関分析**: 
    - Pearson相関係数（線形関係）
    - Spearman順位相関係数（単調関係）
  - **カイ二乗検定**: カテゴリカル変数の独立性検定
  - **効果量**: 統計的有意性と臨床的意義の違い
  - **実践的な解釈**: 医療データ分析での注意点
- **目標**: 医学論文を読むための統計リテラシーを身につけ、基本的な統計検定を実施できるようになる

### 3. `Machine_learning.ipynb`
- **対象者**: データ分析の基礎を学びたい医学生・医療従事者
- **学習内容**:
  - **実データ（Pima Indians Diabetes Dataset）**を用いた実践的なデータ分析
  - **データクリーニング**: 欠損値（生理学的にありえない0）の特定と処理
  - **欠損値補完**: 様々な補完方法（平均値、中央値、条件付き中央値）の比較と実装
  - **機械学習モデルの構築**:
    - ロジスティック回帰 (Logistic Regression)
    - 決定木 (Decision Tree)
  - **モデルの評価**: 混同行列, ROC曲線, AUC
  - **臨床応用**: 感度・特異度の観点からのモデル解釈と臨床での注意点
- **目標**: 実際の医療データが持つ課題を理解し、データ前処理からモデル構築、評価までの一連の流れを習得する

## 学習の推奨順序

1. **Python入門** (`Python.ipynb`) - プログラミングが初めての方はここから
2. **統計分析入門** (`Statistics_basics.ipynb`) - 統計の基礎を30分で学習
3. **機械学習入門** (`Machine_learning.ipynb`) - より高度な予測モデルの構築

## Google Colabでの使用方法

これらのNotebookは、Googleのアカウントさえあれば、環境構築不要でブラウザ上で直接実行できます。

1.  以下のリンクをクリックして、各NotebookをGoogle Colaboratoryで開きます。
2.  コードセルを上から順番に実行（`Shift + Enter`）していくことで、学習を進めることができます。

### Notebookへのリンク

- **Python入門**:
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shun1w/Hajime-no-Data/blob/main/Python.ipynb)

- **統計分析入門（30分コース）**:
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shun1w/Hajime-no-Data/blob/main/Statistics_basics.ipynb)

- **機械学習入門（医学生向け）**:
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shun1w/Hajime-no-Data/blob/main/Machine_learning.ipynb)

