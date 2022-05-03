# ServerlessFrameworkComposeの動作確認

## 確認の流れ

- .envを作成して、AWSの認証情報を入れる
  - AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID
  - AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION
  - AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY
- `docker compose up -d` でコンテナを立ち上げる
  - 以降はコンテナ内で操作をする
- `npm install`をする
- `sls deploy`をする
  - リソースがデプロイされていることを確認する
- `sls remove`をする
  - リソースをまとめて削除されたことを確認する