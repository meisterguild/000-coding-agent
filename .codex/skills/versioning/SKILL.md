---
name: versioning
description: development-processの各ステップ毎でファイルのバージョン管理を行う。レビューがOKならgit commitする。コミットメッセージは対応中のタスクがあれば、そのタスクのタイトルにする。そうでない場合は日本語のコミットメッセージを付ける。
---

# Versioning

## Overview
ファイルの変更に関するルール。変更や追加をそのまま通すのではなく、どんな変更であってもレビュー依頼を出し、それがOKだった場合にgit commitすることでファイル変更履歴を残すルール。

## Prerequisites
.gitディレクトリがプロジェクトルートになければ、git initを実行する。