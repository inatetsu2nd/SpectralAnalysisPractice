# SpectralAnalysisPractice
書籍：名古屋大学大学院生命農学研究科稲垣哲也による書籍「スペクトル解析実践ガイド」に関するプログラムとデータです

## 概要
本書は、スペクトル解析の基礎から応用までを網羅した実践的なガイドです。
Pythonを用いたデータ分析、ケモメトリクス、機械学習、イメージングデータへの適用など、スペクトル解析に関連する多岐にわたるトピックを扱います。

## フォルダ構成
リポジトリには以下のフォルダが含まれています：

- `SpeAnamodule`: SpeAnaシリーズのモジュールファイル
- `dataChapter10-11`: 第10章～第11章で使用するデータ
- `dataChapter12`: 第12章で使用するデータ
- `dataChapter3`: 第3章で使用するデータ
- `dataChapter4`: 第4章で使用するデータ
- `dataChapter8`: 第8章で使用するデータ

## ファイル構成
各ファイルは `SpeAna(章番号)_(節番号)_内容` の形式で命名されています。以下はそれぞれのファイルの概要です。

- `SpeAna02_3-4_basic.ipynb`: 第2章3～4節、pythonの基礎
- `SpeAna03_1-10_statistcs.ipynb`: 第3章1～10節、統計学の基礎とpythonでの実装
- `SpeAna04_1-3_linearalgebraANDdataframe.ipynb`: 第4章1～3節、線形代数とデータフレーム
- `SpeAna06_1_CLSandILS.ipynb`: 第6章1節、CLSとILS
- `SpeAna07_1_PCA.ipynb`: 第7章1節、主成分分析（PCA）
- `SpeAna07_2_PLS.ipynb`: 第7章2節、部分最小二乗回帰（PLS）
- `SpeAna08_1-4_pretreatment.ipynb`: 第8章1～4節、前処理
- `SpeAna08_5_modules.ipynb`: 第8章5節、モジュールの使用
- `SpeAna09_1-6_machinelearning.ipynb`: 第9章1～6節、機械学習の応用
- `SpeAna10_1-9_practicaluse.ipynb`: 第10章1～9節、実践的な応用
- `SpeAna11_1-6_practicaluse.ipynb`: 第11章1～6節、実践的な応用（続き）
- `SpeAna12_1_Imaging.ipynb`: 第12章1節、イメージングの応用


### ライブラリインポート用ファイル
- `requirements.txt`
このファイルをダウンロード後、Anacondaプロンプトで`requirements.txt`ファイルがあるディレクトリに移動してください。
例として、`requirements.txt`ファイルが`C:\Users\ユーザー名\Documents\PythonProjects\MyProject`フォルダ内にあると仮定します。
以下の手順でライブラリをインストールできます。

1. Anacondaプロンプトを開き、`cd`コマンドを使用して`requirements.txt`ファイルがあるディレクトリに移動します。
`cd C:\Users\ユーザー名\Documents\PythonProjects\MyProject`


2. 以下のコマンドを実行して、ファイルにリストされているすべてのライブラリをインストールします。
`pip install -r requirements.txt`



## 使用方法
本リポジトリのコードを使用するには、Python 3.x および必要なライブラリがインストールされていることを確認してください。SpeAnaから始まるファイルはJupyter Notebook形式です。これをJupyter Notebookで開くことでコードを実行できます。

## ファイルがダウンロードできない場合
Githubから各種ファイルがダウンロードできない場合には、お手数ですがinatetsu@agr.nagoya-u.ac.jpまでご連絡ください。
メールタイトルは【スペクトル解析【稲垣講義用】ファイルダウンロード】としてください。


## 著者
- [稲垣哲也] ([Researchmap](https://researchmap.jp/inatetsu25/))
