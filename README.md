# README

## 環境構築
```
$ bundle install
$ bin/rails db:setup
$ yarn install
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
選択した事業側の課題

サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

提案内容

もくもく会の参加条件に女性限定での募集を付け加える
ー＞女性側はいきなり初対面の男性と会うのは少し気がひけるだろうし、実際に参加してみたらほとんどが男性だったというような状況になると次のもくもく会に足を運ばないであろうから、女性だけのもくもく会を開けるようにするべきであると考える。

実装方針

・プロフィールに性別を追加する
・もくもく会を作る際に男性限定または女性限定のチェックボックスをつくる
・ヘッダーの検索部分を性別で絞って検索をかけれるように変更する