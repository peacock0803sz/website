---
title: "Resume"
date: 2019-06-03T21:51:13+01:00
draft: false
hideLastModified: true
keepImageRatio: true
tags: ["resume"]
summary: "This is my resume"
showInMenu: true
---

# 職務経歴書

最終更新: 2022/06

現在、中期的(半年から1年)な転職を視野に入れて転職活動中です。

## 名前・連絡先

- Peacock
- 高井 陽一 (Yoichi TAKAI)
- [Twitter](https://twitter.com/peacock0803sz)
- [facebook](https://www.facebook.com/peacock0803sz)
- [Blog](https://peacock0803sz.hatenablog.jp)
- [e-mail](mailto:contact@peacock0803sz.com)

業務以外の活動については[こちら](../activities)を参照

## 主なスキル

### できる(実務で使った)

- Python (3.6以降)
    - Flask 1.x / 2.x, Plone5, Pyramid
    - OpenPyXL, BeautifulSoup4
    - argparse, clickでのコマンドライン引数解析
    - mypy, pytest, black & flake8環境での開発
- Docker, docker-compose
- Nginx
- PostgreSQL
- AWS
    - Lambda, S3, DynamoDB, RDS, SES, ECS, CloudWatch
- Terraform

### 少しできる(実務で触ったことがある・個人で使っている)

- JavaScript / TypeScript (ES2015以降)
    - React, Vue
- GCP
    - Cloud Run

### 興味がある(チュートリアル触った程度)

- Deno
- Rust
    - Haskellを少し触ったことがあり、関数型的指向に興味がある
- Go
    - Batteries IncludedなPythonばかりなので、素の実装力をつけるために身につけたい
- Kubernetes
    - 大規模サービスを運用したことがないので、経験してみたい

### 使用しているツール・OSなど

- Git / GitHub, Bitbucket
- Linux(開発用OSとして、2014年から)
- Neovim, zsh

## 職務経歴

### 2019/09/25 ~ 現在: [株式会社CMSコミュニケーションズ](https://cmscom.jp)

Pythonと教育をテーマに受託開発を行っている。社員6名

- 雇用形態
    - 2019/09よりアルバイトとして、2020/06より社員として勤務中。
    - 2021/05より規定6.4時間の時短勤務で正社員。

#### 問い合わせ機能付きランディングページサイト開発(2022年4月~2022年6月)

- 役割: メイン開発者としてバックエンド、インフラ
- 使用技術: Flask 2.x, Terraform 1.x, AWS Lambda, API Gateway, S3, CloudFront
- 学んだこと:
    - Terraformを用いてのサービス量産
    - Pythonの `importlib` を工夫しての設定読み込み
- 苦労したこと・できなかったこと
    - AWSのリージョンを跨いだTerraformでの構成管理

#### Open edX導入支援 (2022年2月頃~2022年3月)

- 役割: インフラ担当としてDockerでのOpen edXシステム導入
- 使用技術: Open edX (version Maple), AWS RDS(MySQL), Docker, click
- 学んだこと:
    - Django Admin画面での操作
    - Docker(on AWS EC2)ベースでのシステム導入

#### PyramidでのAPIサーバー開発 (2021年8月頃~2022年1月頃)

- 役割: メインの開発担当として基本設計フェーズから実装、顧客との仕様調整(一部)を担当
- 使用技術: Pyramid 2.x, PostgreSQL 12, SQLAlchemy 1.14, Redis 6.x, Ansible 2.11
- 学んだこと:
    - Session, Cookie管理
    - CORS
        - CORSとPreflight requestについて <https://zenn.dev/peacock0803sz/articles/fe331e04183257>
    - Zope interfaceを使用した開発
    - Ansibleでの構成管理

#### Flask + ReactでのWebサービス開発 (2021年3月頃~7月頃)

- 役割: メインの開発担当として基本設計フェーズから実装までを担当
- 使用技術: Flask 1.x, Numpy, React + d3.js, AWS Lambda & DynamoDB
- 学んだこと:
    - OpenAPI Specification (v3.0)
    - toCサービスの開発
    - MVCモデルアーキテクチャでの設計
    - Reactでのコンポーネント開発
    - AWSにてServerless Serviceの立ち上げ

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
