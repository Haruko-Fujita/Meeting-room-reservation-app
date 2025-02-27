# 貸し会議室予約アプリ

<!-- 何かを簡潔に紹介する -->

<!-- DEMO
魅力が直感的に伝わる画像 -->

<!-- Features
セールスポイントや差別化などを説明する -->

## 機能

- 認証
- ログインユーザー毎に操作内容を変更（ユーザー/管理者）
- 会議室予約登録
- 会議室予約削除
- 会議室登録、画像アップロード（管理者）
- バリデーションチェック

## 使用技術

- TypeScript: 4.9.4
- Node.js: 18.14.2
- React: 18.2.0
- MUI: 5.11.2
- Python: 3.9
- FastAPI: 0.88.9
- sqlAlchemy: 1.4.45
- MySQL: 8.0.31
- Docker: 20.10.17
- Amazon S3

## システム構成

![image](https://user-images.githubusercontent.com/94355319/222135021-40c0298f-7e77-4012-9c30-7a31b44c99b7.png)

<!-- Usage
DEMO の実行方法など、基本的な使い方を説明する -->

## 使い方

1. リポジトリのクローン  
    <!-- Mina -->
   `git clone https://github.com/OakIMiNo/Meeting-room-reservation-app.git`
    <!-- Haruko -->
   <!-- `git clone https://github.com/Haruko-Fujita/Meeting-room-reservation-app.git` -->

2. ルートディレクトリへ移動  
   `cd app`

3. docker コマンドを入力  
   `docker-compose run -w /usr/src/app --rm frontend npm install`  
   `docker-compose up`

4. アプリにアクセスする  
   `http://localhost:3000/signup`

<!-- デプロイ -->
