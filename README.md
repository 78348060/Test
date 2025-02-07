# 入院患者の病棟内移動方法に関する要因の探索 (Exploring Factors Affecting Inpatient Mobility in the Ward)
　本リポジトリは、「回復期リハビリテーション病棟入院患者の病棟内移動方法に関する要因」の探索を行う Jupyter Notebook を含んでいます。  
## 概要 (Overview)
- 本リポジトリには、解析の再現性を確保するためのコードのみが含まれています。実際に使用したデータは個人情報保護およびプライバシーの観点から公開されていません。
- 研究の目的は、回復期リハビリテーション病棟入院患者の病棟内移動方法に関する要因を明らかにすることです。
- 論文中の方法セクションで示した解析手法を再現できます。

## ファイル構成 (Structure)
project-root

　　├── analysis.ipynb   # 主な解析を実行する Jupyter Notebook

　　└── README.md        # このリポジトリの概要や説明

## Requirements / Environment

　本プロジェクトは Jupyter Notebook の IPython カーネル Python 3.12.4 上で実行および検証されています。
　このプロジェクトは Python 3.8 以降で動作することを前提としており、以下の主要な Python ライブラリおよびシステム依存ツールを使用しています。

### Python

- **Python 3.8+**

### Python パッケージ

- **pandas**  
  データ操作・解析ライブラリ  
  *例: version 1.3.0 以降*

- **numpy**  
  数値計算ライブラリ  
  *例: version 1.21.0 以降*

- **matplotlib**  
  データ可視化ライブラリ  
  *例: version 3.4.2 以降*

- **seaborn**  
  統計的データ可視化ライブラリ  
  *例: version 0.11.1 以降*

- **scikit-learn**  
  機械学習アルゴリズムおよび評価指標を提供  
  *例: version 0.24.2 以降*

- **lightgbm**  
  高速な勾配ブースティングフレームワーク  
  *例: version 3.2.1 以降*

- **optuna**  
  ハイパーパラメータ最適化ライブラリ  
  *例: version 2.8.0 以降*

- **dtreeviz**  
  決定木の詳細な可視化ライブラリ  
  *例: version 1.4.0 以降*

- **graphviz (Python パッケージ)**  
  決定木の可視化に使用します。  
  *例: version 0.17 以降*  
  ※**注意**: このパッケージを利用するには、システム側に [Graphviz ソフトウェア](https://graphviz.org/download/) のインストールが必要です。

### システム依存ツール

- **Graphviz ソフトウェア**  
  - Windows, macOS, Linux 各環境に合わせたインストールが必要です。  
  - 例:
    - **Ubuntu**:  
      ```bash
      sudo apt-get install graphviz
      ```
    - **macOS** (Homebrew 利用の場合):  
      ```bash
      brew install graphviz
      ```
    - **Windows**:  
      [Graphviz の公式サイト](https://graphviz.org/download/) からインストーラーをダウンロードしてください。  
