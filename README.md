# micro-frontend
マイクロフロントエンドのお試し用

[こちら](https://intro-to-micro-frontends.netlify.app/contents/microfrontends/10_overview_of_micro_frontends)を参考に。

## 検証内容

- ヘッダー、フッター、コンテンツのようなベーシックな1ページの中で分割したマイクロフロントエンド構成
- 特定のページ以外はマイクロフロントエンドの構成
- 異なるフレームワークで構築されたマイクロフロントエンド構成

## メリデリ

一般的に語られているものはありつつ、やってみてどうだったか。
アプリケーションの保守性観点だけでなく、例えばSEOやデータ収集等にあたっての障害等も視野に入れつつの感想を述べる。

## 検討にあたって考慮すべき事項


## 

## メモ

- packageのnameの`@xxx`はスコープ。パッケージ名が被らないようにするための名前空間を設定している
- ルートのpackage.jsonに`private: true`を加えないと`yarn install`できない仕様
- workspaceのpackage.jsonに`version`が書かれていないとルートからworkspaceのコマンドを実行しようとしても実行できない
