# GoogleMap Serverless

Google Mapのマーカーをサーバーレスな形で保存するアプリケーション、SAMテンプレート

## 変更箇所

index.html: API_KEY_HERE→Google Map API KEY
deploy.sh: BUCKET_NAME_HERE→ S3 Bucket
xxxxx.execute-api.ap-northeast-1.amazonaws.com: 作成されたAPI GatewayのEndpoint

## 使い方

* 変更箇所を変更する

* ./deploy.sh

* client/index.html をブラウザで開く
