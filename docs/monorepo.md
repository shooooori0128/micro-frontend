# モノレポ関連のメモ

## yarn を利用した場合の詰まりどころポイント

- package の name の`@xxx`はスコープ。パッケージ名が被らないようにするための名前空間を設定している
- ルートの package.json に`private: true`を加えないと`yarn install`できない仕様
- workspace の package.json に`version`が書かれていないとルートから workspace のコマンドを実行しようとしても実行できない
