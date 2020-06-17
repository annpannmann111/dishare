# DiShare

『美味しい』を共有するをモットーに、様々なジャンルや、近場のレストランを探し出し、
そのレストランの情報を友人と共有することができるwebアプリケーションです！。

### [リンク]: https://dishare.work

![UNADJUSTEDNONRAW_thumb_1](https://user-images.githubusercontent.com/49737864/84769305-94c31680-b010-11ea-8e82-f0d925e6e9f9.jpg)

:hamburger:  観賞用にテストユーザーでのログインもご用意しております！お気軽にお越し下さい！:hamburger:

# 特に見ていただきたい点
- ### インフラ面
  - Dockerを使い、ECS(FARGATE)/ECRで本番環境をサーバーレスで運用している点。
  - Terraformを使い、本番環境インフラをコードで管理している点。
  - CircleCIを使い、CD/CDパイプラインを構築している点。
  - AWSを使い、ALBを通すことで常時SSL通信を行っている点。
- ### バックエンド面
  - データベースの正規化を意識したテーブル設計を行なっている点。
  - 外部API（ぐるなびAPI,GoogleMapAPI）を利用し機能を追加している点。
  - JWTを使用したログイン認証を実装してる点。
- ### フロントエンド面
  - Nuxt.jsを採用し、SSR（サーバーサイドレンダリング）で配信している点。
  - トランジションやカード、モーダルなどこだわりを持ってUIをデザインしている点。
- ### その他
  - チーム開発を意識し、Github flowに従った開発手法を取り入れている点。

# クラウドアーキテクチャー
![cloud-map](https://user-images.githubusercontent.com/49737864/84779262-23d72b00-b01f-11ea-8e2c-9347f31a07a7.png)