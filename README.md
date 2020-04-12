## 概要
### HTMLリファレンスサイト
HTMLやCSSの構文をまとめたサイト

## 使い方
### セットアップ
1. リポジトリをクローン
2. npm install

### 編集の仕方
1. `source/_posts` 配下にMarkDown(.md)のファイルを作成し、書き込む
2. `npx hexo server` でローカル起動
3. 問題がなければ、コミット＆プッシュ

## デプロイについて
CI/CDにGithub Actionsを使っています。
プルリクがmasterブランチにマージされた段階で、CIが動きます。
CI上で静的ページを作成、Netlifyにデプロイまで行ってくれます。
