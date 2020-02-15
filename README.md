# backbone.js - サンプル

## ローカル環境
dockerでnginxを起動してwebサーバを構築します。
```
$ docker-compose build
$ docker-compose up -d
```

## 動作確認
ブラウザで閲覧してみる。
```
$ open http://localhost:8080
```

## サンプルコード
作ったコードを一覧にして記載します。

- TOP Page - http://localhost:8080/
※ とりあえず、動く環境を整える

- Model - http://localhost:8080/model1.html
※ ModelでAjax通信してみる

- Model - http://localhost:8080/model2-validate.html
※ Modelで入力検証をしてみる

## 参考サイト
- [dockerでnginx導入と複数サービスの展開](https://qiita.com/asylum/items/05d8dc4cc4671d7a5d4f)

以上
