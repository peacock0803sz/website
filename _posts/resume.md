---
title: "Resume"
date: '2019-06-03T21:51:13+01:00'
excerpt: Peacock's resume
coverImage: '/assets/img/cover.jpg'
author:
  name: Peacock
  picture: '/assets/img/peacock0803sz.jpg'
ogImage:
  url: '/assets/img/cover.ipg'
---

# 職務経歴書

現在、中期的(半年から1年)な転職を視野に入れて転職活動中です。

## 名前・連絡先

- Peacock
- 高井 陽一 (Yoichi TAKAI)
- [Twitter](https://twitter.com/peacock0803sz)
- [facebook](https://www.facebook.com/peacock0803sz)
- [Blog](https://peacock0803sz.hatenablog.jp)
- [e-mail](mailto:contact@peacock0803sz.com)

## 作品・OSSへの貢献

### コミュニティ活動

- [PyCon JP 2021](https://2021.pycon.jp)スタッフ(会場、スポンサー、デザイン)
- [PyCon JP 2020](https://pycon.jp/2020) Goods & Web Designチームリーダー
- [PyCon JP TV](https://tv.pycon.jp)ディレクター
- Plone User's Group JapanとしてWorld Plone Day 2021 TokyoでのYouTube Live(ディレクター)
- Plone User's Group JapanとしてPlone本体の翻訳(共同) <https://github.com/collective/plone.app.locales>
    - <https://github.com/collective/plone.app.locales/commit/0d74afd7361e17ebf9d7bd87299702baec286004>

### その他作品・OSS活動

- My Website(This repo): [peacock0803sz](https://github.com/peacock0803sz/peacock0803sz)
- [mr.s3](https://github.com/peacock0803sz/mr.s3)
    - PloneのデータベースをAWS S3と同期するためのスクリプト
- [HTTP/3 explained](https://daniel.haxx.se/http3-explained/)の日本語訳
- 「Pythonではじめる今風な型プログラミング」 at Open Source Conference 2021 Hokkaido, 2021/06/21
    - <https://speakerdeck.com/peacock0803sz/osc21do>
    - <https://youtu.be/2sZ9U1iIscQ>
- 「Getting Started with Statically Typed Programming in Python 3.10」 at EuroPython 2021, 2021/07/29
    - <https://speakerdeck.com/peacock0803sz/getting-started-with-statically-typed-programming-in-python-3-dot-10>
    - <https://www.youtube.com/watch?v=8HEYko-o63I>
- 「Getting Started with Statically Typed Programming in Python 3.10」 at PyCon APAC 2021, 2021/10/20
    - <https://speakerdeck.com/peacock0803sz/pycon-apac-2021>

## 興味分野、今後やりたいこと

- Rust
- Deno
- 非同期プログラミング
- Kubernetes

## 主なスキル

### 言語・フレームワーク・ライブラリ

- Python (3.6以降)
    - Flask 1.x / 2.x, Plone5, Pyramid
    - OpenPyXL, BeautifulSoup4
    - argparse, clickでのコマンドライン引数解析
    - mypy, pytest, black & flake8環境での開発
- JavaScript / TypeScript (ES2015以降)
    - React
- HTML/CSS

### データベース・ミドルウェア・パブリッククラウド

- Docker, docker-compose
- Nginx
- PostgreSQL
- AWS
    - Lambda, S3, DynamoDB, RDS, SES, ECS, CloudWatch

### ツール・OSなど

- Git / GitHub, Bitbucket
- Linux(開発用OSとして、2014年から)
- Neovim, zsh

## 職務経歴

### 2019/09/25 ~ 現在: [株式会社CMSコミュニケーションズ](https://cmscom.jp)

Pythonと教育をテーマに受託開発を行っている

#### PyramidでのAPIサーバー開発

- 役割: メインの開発担当として基本設計フェーズから実装、顧客との仕様調整(一部)を担当
- 使用技術: Pyramid 2.x, PostgreSQL 12, SQLAlchemy 1.14, Redis 6.x Ansible 2.11
- 学んだこと:
    - Session, Cookie管理
    - CORS
        - CORSとPreflight requestについて <https://zenn.dev/peacock0803sz/articles/fe331e04183257>
    - Zope interfaceを使用した開発
    - Ansibleでの構成管理

#### Flask + ReactでのWebサービス開発 (2021年3月頃~現在)

- 役割: メインの開発担当として基本設計フェーズから実装までを担当
- 使用技術: Flask 1.x, Numpy, React + d3.js, AWS Lambda & DynamoDB
- 学んだこと:
    - OpenAPI Specification (v3.0)
    - toCサービスの開発
    - MVCモデルアーキテクチャでの設計
    - Reactでのコンポーネント開発

#### Pyramid製システムのPython2.7 -> Python3.8アップグレード (2021年初頭)

- 役割: アップグレードのインフラ担当、アプリケーションコードの修正
    - Legacy EC2をAWS ECS(Fargate)へ移行
    - 2009年ごろのPyramid製サービスをPython3.8へアップグレード
- 使用技術: Terraform, Bitbucket Piplines, AWS ECS (Fargate)
- 学んだこと:
    - Terraformを用いたインフラ構築
    - AWS ECS (Fargate)の構築、運用

#### Ploneでの大学向け学習支援システム(LMS)開発 (2020年4月~9月頃)

- 役割: データベース、管理者向けWeb UIの設計・開発担当
- 使用技術: Plone 5.2, PostgreSQL 12, SQLAlchemy 1.3
- 学んだこと:
    - オブジェクト指向プログラミング(クラス継承)での設計
    - Plone PAS(Pluggable Authentication Service)を使った機能の開発

#### FlaskでのAPIサーバー開発 (2019年12月~2020年3月頃、2021年3月)

- 役割: 構築済みのAPIサーバーのエンドポイント追加や機能追加時の設計開発
    - メイン開発担当として、フロントエンドエンジニア(外部)とのやり取り
    - Vue.jsのコンポーネント修正
    - 年次更新時の保守作業
- 使用技術: Python 3.8, Flask 1.0, Vue.js 2.x, AWS Lambda, DynamoDB
- 学んだこと:
    - FlaskでのAPIサーバー構築
    - Unit-level test (Pytest)

#### Plone 4 -> Plone 5 & Volto 移行用コンテンツ整形スクリプトの開発(2019年11月~2020年3月頃)

- 役割: サポートエンジニアとして社内向けスクリプトの開発、機能追加への対応
- 使用技術: Python3.7, OpenPyXL, BeautifulSoup4, draft-js
- 学んだこと:
    - コマンドライン引数解析
    - フルスクラッチでの設計、開発

#### AWS Lambda上でのスクレイピングシステム (2019年9月~2021年4月)

- 役割: メイン開発者として、顧客との仕様調整などのやり取りを含む開発
    - 途中まで上司が書いていたコードを引き継ぎ再設計・リファクタリング
    - Webサイトをスクレイピング、WordPress API経由で別サイトに転載するシステムを10つ以上横展開
- 使用技術: Python 3.6~3.8(BeautifulSoup4), AWS Lambda & S3
- 学んだこと:
    - Webスクレイピング
    - ライブラリ(boto3)経由でのAWS S3操作

### 2019/04/08 ~ 2019/07/31: 東京電機大学 未来科学部 情報メディア学科 学生職員

- 事務雑用(学科内郵便や授業教室の清掃等)
- 授業で使用するPC環境・サーバー(CentOS)の保守
    - ネットワーク障害の対応
