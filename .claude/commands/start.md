# /start

開発サーバを起動する。

## 手順
1. 仮想環境を有効化する
   source .venv/bin/activate
2. 開発サーバを起動する
   python -m uvicorn src.main:app --reload