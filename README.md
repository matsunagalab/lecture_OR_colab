# オペレーションズリサーチ notebooks
埼玉大学工学部情報工学科で後期に開講している「オペレーションズリサーチ」の講義で用いる Google colab notebooks を置いています。下のバッジをクリックして開いてください。

## 第07回 ソルバ01：Pythonから線形計画を解く
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matsunagalab/lecture_OR_colab/blob/main/solver01.ipynb)

## 第08回 ソルバ02：輸送計画と簡易ドッキング
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matsunagalab/lecture_OR_colab/blob/main/solver02.ipynb)

第07回はColabの準備、Pythonの変数・リスト・for、PuLPのモデルと検算を扱います。小レポート・提出はありません。

第08回は `if`・`elif`・`else`、二重リスト、二重ループ、`for` と `if` の組合せへと段階的に進みます。輸送問題を解き、2次元の簡易ドッキングを体験します。回転は4候補、点の対応は固定し、各候補で平行移動によるL1誤差をLPで最小化します。結合エネルギーや衝突を扱う通常の分子ドッキングとは異なります。

第08回はオンデマンドです。小レポート・提出はありません。PDFとノートブックを並べ、練習は予想→実行→解答の順で進めます。末尾の条件変更も解答付きの任意練習です。09の最短経路、10の最大流へ、ネットワークの辺に付ける費用・長さ・容量の違いをつなぎます。

### 開き方と実行環境

- 「ファイル → ドライブにコピーを保存」で自分のコピーを作り、上から実行します。
- CPUで十分です。準備セルで `pulp==3.3.0` と `highspy==1.12.0` をインストールします。
- 本教材はHiGHSを明示して使います。ノートブック保存と実行環境は別なので、新しいランタイムでは準備から実行し直します。
- 各練習の後に解答があります。07・08はいずれも小レポート・提出なしです。

## ソルバ03：PuLPで整数計画問題を解く
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matsunagalab/lecture_OR_colab/blob/main/solver03.ipynb)

## 動的計画法の応用例
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matsunagalab/lecture_OR_colab/blob/main/advanced.ipynb)
