# teamA-api（プロジェクト名が決まり次第変えます）

## 環境構築方法

- 下記コマンドを実行する

```
make init
```

- 以下 URL が api のパス <br>
  [localhost:9010](http://localhost:9010/)

## make コマンド一覧

| コマンド     | 説明                                   |
| ------------ | -------------------------------------- |
| make init    | 環境構築時に最初に行うコンテナ立ち上げ |
| make down    | コンテナを落とします                   |
| make api     | コンテナの中に入ります                 |
| make analyse | 静的解析とフォーマッターを動かします   |

### discord と連携しています
commit、プルリクなどのイベントが起きれば、ディスコードの当該チャンネルに通知がいきます。

## 推奨ツール
- [Sequel Ace](https://apps.apple.com/jp/app/sequel-ace/id1518036000?mt=12)
- [postman](https://www.postman.com/)
