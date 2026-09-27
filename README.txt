【歴史探検クエスト】

このアプリは無料でGitHub Pagesに公開できます。

ファイル
- index.html : アプリ本体。通常は触らない
- questions.js : ★問題を追加・修正するファイル
- manifest.json : スマホアプリ化設定
- service-worker.js : オフライン対応。更新時はCACHEのv番号を上げる
- icon.svg : アイコン

問題追加
questions.js の QUESTION_BANK に同じ形式の問題を追加してください。
idは既存問題と重複させず、既存問題のidは変更しないでください。

更新前
アプリの「設定」→「学習データを書き出す」でバックアップ推奨。

注意
学習データは端末・ブラウザごとのlocalStorageです。別端末とは自動同期しません。
