# PythonTipsHub
このリポジトリはPythonのTipsを集めて共有するためのものです。人工知能研究会で使います。

## How to install and run python environment.
### windows
1. Anacondaをインストールする。\
https://www.anaconda.com/products/individual

2. Installerを起動してインストールする。\
すべてデフォルトのままインストールする。

3. Anaconda Promptを検索して開く。
4. 仮想開発環境を作成するために、次のコマンドを実行する。\
conda create -n 環境の名前(日本語ダメ) python=3.9
5. 仮想環境をActivateする。\
conda activate さっきの名前
6. Numpyをインストールしてみよう。\
pip install numpy
7. Pythonを実行してみよう。\
Python\
">>> print("Hello wolrd")"\
">>> import numpy as np"
">>> quit()"

8. 環境をdeactivate する。\
conda deactivate
