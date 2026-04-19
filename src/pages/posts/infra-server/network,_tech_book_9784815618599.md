---
layout: ../../../layouts/MarkdownPostLayout.astro
title: "『体験しながら学ぶネットワーク技術入門』の学習メモ"
pubDate: 2026-4-11
description: "書籍を進めていくうえで必要と感じた事項をメモとして残します。"
author: "jhfenri"
image:
  url: ""
  alt: ""
tags: ["ネットワーク", "書籍"]
---

## 情報源

- [『体験しながら学ぶネットワーク技術入門』の書籍HP](https://www.sbcr.jp/product/4815618599/)
- [検証環境構築用ファイルのダウンロードページ](https://www.sbcr.jp/support/4815617794)

- [WSLのドキュメント](https://learn.microsoft.com/ja-jp/windows/wsl/)
- [Dockerのドキュメント]()
- [tinetの公式サイト](https://github.com/tinynetwork/tinet)

## memo

- 作業前の注意
  - ハンズオンで使用するUbuntuバージョンが20.04から24.04になっているので注意

- p8 WSL2のインストール  
  以下の環境では再起動不要だった。

```
WSL バージョン: 2.6.1.0
カーネル バージョン: 6.6.87.2-1
WSLg バージョン: 1.0.66
MSRDC バージョン: 1.2.6353
Direct3D バージョン: 1.611.1-81528511
DXCore バージョン: 10.0.26100.1-240331-1435.ge-release
Windows バージョン: 10.0.26200.8117
```

- ログインは、terminalから　`wsl --destribution Ubuntu-24.04`　で行ける
