## 目的

- メインディスプレイのスクリーンショットを自動で撮影する
- 方向キーで操作するタイプのツールにおいて、事前に指定しておいた回数分のスクリーンショットを撮影する

## 使い方

### 環境再現

```bash
 # 仮想環境の作成（.venvが生成）
 uv sync
 # ipykernelのインストール
 pip install ipykernel
 # カーネルの登録
 python -m ipykernel install --user --name auto_screenshot --display-name "Auto Screenshot"
 # エディタで本カーネルを選択して完了
```

### 実行
1. `auto_screenshot.py`を実行する