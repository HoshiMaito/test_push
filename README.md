# 計算機のプログラム

皆さんが応用プログラミングの授業後半で開発を行った計算機のプログラムの
作成見本です。

PySimpleGUIをインストールする必要があります。

# 動作準備

最初にコマンドプロンプトを立ち上げ、コマンドプロンプトでpythonが動作可能かを確認します。
下記のように、pythonのバージョンが表示されていればpythonが動作可能です。

```
$ python -V
Python 3.11.9
```

仮想環境を作成します。

```
 $ python -m venv venv 
```

作成した仮想環境をアクティブにします。

```
 $ ./venv/Script/activate
```

仮想環境にPySimpleGUIをインストールします。

```
 $ pip install pysimplegui==4.60.5
```

pythonコマンドの後にスクリプトファイルを指定することでプログラムを実行します。

```
 $ python python_calc.py
```

# レポジトリーのクローン

矢野先生のgithubレポジトリを自分のPCにコピーするためには、クローンを使います。

```
 git clone https://github.com/ShouheiYano2020/python_calc.git
```