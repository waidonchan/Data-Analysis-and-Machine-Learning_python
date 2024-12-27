# Pythonによる機械学習

## 目次

1. [概要](#概要)
2. [使用したデータ](#使用したデータ)
3. [実装内容](#実装内容)
4. [結果](#結果)
5. [必要な環境](#必要な環境)
6. [実行方法](#実行方法)

---

## 概要

Kaggleで提供されているデータセットを使用して、機械学習モデルを構築・評価しました。Notebookでは、データの前処理、探索的データ分析 (EDA)、特徴量エンジニアリング、モデルの訓練と評価を行っています。主にPythonを使用して、以下のライブラリを活用しました

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

<p align="right">(<a href="#top">トップへ</a>)</p>

## 使用したデータ

- **データセット**: Kaggleで提供されているオープンデータセット
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/discussion/86957
- **内容**: データには数値型、カテゴリ型の特徴量が含まれています。
- **目的**: 回帰または分類問題の解決を目指して、予測モデルを構築。

<p align="right">(<a href="#top">トップへ</a>)</p>

## 実装内容

1. **データの読み込みと概要確認**
    - Pandasを使用してデータを読み込み、欠損値や異常値をチェック。
    - データ型や分布を分析。

2. **探索的データ分析 (EDA)**
    - SeabornとMatplotlibを使用して、データの可視化を実施。
    - 相関ヒートマップや特徴量分布のプロット。

3. **データ前処理**
    - 欠損値の補完、外れ値の処理。
    - 数値型とカテゴリ型の特徴量を適切にエンコード。

4. **特徴量エンジニアリング**
    - 新しい特徴量の生成。
    - 必要に応じて次元削減を適用。

5. **モデルの構築と評価**
    - Scikit-learnを使用して複数のモデルを構築（例: ランダムフォレスト、線形回帰、SVM）。
    - クロスバリデーションでモデルの汎化性能を評価。

6. **結果の分析**
    - 最適なモデルの選定。
    - モデル性能を可視化。

<p align="right">(<a href="#top">トップへ</a>)</p>

## 結果

Notebook内では、モデルの精度、再現率、F1スコアなどの評価指標を使用して、モデルの性能を比較しました。さらに、予測結果の解釈を行い、ビジネスや研究への応用可能性を議論しました。

<p align="right">(<a href="#top">トップへ</a>)</p>

## 必要な環境

- Python 3.8以上
- Kaggleアカウント（データセットへのアクセス用）
- 主要ライブラリ:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scikit-learn

<p align="right">(<a href="#top">トップへ</a>)</p>

## 実行方法

1. 必要なライブラリをインストールします：
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

2. Kaggleからデータセットをダウンロードし、Notebookファイルと同じディレクトリに配置します。

3. Notebookを開き、セルを順に実行してください。

<p align="right">(<a href="#top">トップへ</a>)</p>