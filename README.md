fluentdを検証する為のリポジトリです。

# インストール
```
gem install fluentd
gem install fluent-plugin-s3
```

# 内容
|ディレクトリ|内容|
|---|---|
|intro|とりあえずの動作確認用。flune_catにパイプでjsonを入力 > 標準出力|
|test1|./test.logに書き込まれたログを./logs/app.logへ|
|test2|test1の発展型。./test.logに書き込まれたログをS3へ|
|test3|./test.logにcsvで書き込まれたログを./logs/app.logへcsvで出力|
|test4|test3を発展型。出力先をS3へ|
