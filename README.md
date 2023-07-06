# 概要
mp4形式の動画から、議事録を自動生成するプログラムです。

# 仮想環境
$ python3 -m venv ~/venv
$ source ~/venv/bin/activate
(venv)$

# ライブラリ等をインストール
(venv)$ pip install -r requirements.txt

# 環境変数
(venv)$ touch .env
```txt:.env
API_KEY = "openaiのAPIキー"
```

# mp4ファイルの準備
mp4_to_minutesディレクトリに議事録を作成したい動画ファイルを配置してください。
