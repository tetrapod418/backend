# Express server for React App x kintone REST API

React の初期アプリケーションをもとに、kintone のREST APIでデータを読み込んで表示する機能の確認用アプリの実行用Expressサーバーです

## 実行の仕方
```
node server.js
```
フロントエンドアプリは、以下を参照してください。<br>
https://github.com/tetrapod418/get_qrcodetest

## 謝辞
ReactでREST APIを利用する手順は、きんとーん・らぼの、[React_and_REST_API_第3.1版](https://kintone-labo.booth.pm/items/4067757)　を参考にしました。

また、[cybozu developer network](https://cybozu.dev/ja/) の以下を参考にしました。
- 複数のレコードを取得する
https://cybozu.dev/ja/kintone/docs/rest-api/records/get-records/
- kintone JavaScript Client
https://cybozu.dev/ja/kintone/sdk/rest-api-client/kintone-javascript-client/
- kintone Webhook
https://cybozu.dev/ja/kintone/docs/overview/webhook/
- 外部からセキュアに kintone のデータを操作する
https://cybozu.dev/ja/kintone/tips/best-practices/securely-operating-kintone-data/#precautions-for-data-registration
