# GitHub Actions 学習用リポジトリ

GitHub Actions の基本的な概念とワークフロー定義を学ぶためのリポジトリです。手動トリガーで実行できる最小限の例を通して、Actions の構成要素や挙動を確認できます。

## ワークフロー構成

- `.github/workflows/manual.yml`
  - `workflow_dispatch` イベントを使用した手動実行用のワークフロー
  - `greeting` という必須入力を受け取り、指定されたメッセージを `echo` で出力
  - GitHub が提供するホストランナー `ubuntu-latest` 上でステップを実行

## 使い方

1. GitHub 上でこのリポジトリを開く
2. `Actions` タブに移動し、`Manual` ワークフローを選択
3. `Run workflow` ボタンを押し、`greeting` 入力に任意の挨拶を入力して実行
4. 実行ログで入力値が出力されることを確認
