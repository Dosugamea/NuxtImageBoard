# NuxtImageBoard
Nuxt.jsを用いた画像投稿サイト(データベース)

## 注意
- 他のプロジェクトから一部機能を削除して切り抜いたものです
- セキュリティ面やバグ等不完全な点が多いため現段階での利用はおすすめしません

## スクリーンショット(PC)
![Top](https://i.imgur.com/rANh95I.png)
![Search](https://i.imgur.com/ieJZeJP.png)
![Art](https://i.imgur.com/tP4kUlB.png)

## スクリーンショット(スマホ)
![Menu](https://i.imgur.com/jk2rHtg.png)
![Search](https://i.imgur.com/IISEuv1.png)
![Art](https://i.imgur.com/u9K6Agi.png)

## デモ
- [こちらからどうぞ](https://nboard.domao.site)
- ID: demouser
- PW: demouser
- (開発中のため不安定です)

## 特徴
- タグベースの豊富な検索手段
- デスクトップ/スマホ 両対応UI
- 他言語対応
- PWA対応
- ミュート/マイリスト/ランキング
- 招待専用フロー
- LINE Notify / OneSignal を用いた通知機能
- LINE / Telegram 等のOauthログイン

## 開発環境
- バックエンド: Flask (Python)
- フロントエンド: Nuxt.js SSR(Javascript) / Bulma

## 検証済み動作環境
- Webサーバー: Apache2
- データベース: MariaDB / Redis
- ハードウェア: Raspberry Pi 3B
- Docker-compose
