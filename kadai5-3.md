## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* `https://zipcloud.ibsnet.co.jp/api/search`
* 郵便番号API（zipcloud）は、日本の郵便番号から住所情報を取得するためのWeb API。  
* リクエストとレスポンスのフォーマット
* JSON形式で住所情報を返す
* ```json
{
  "results": [
    {
      "zipcode": "1000001",
      "address1": "東京都",
      "address2": "千代田区",
      "address3":"千代田",
      ...
    }
  ],
  "status": 200,
  "message": null
}
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* OpenWeatherMap API
* https://openweathermap.org/api
* エンドポイントと機能
* 指定した都市の現在の天気情報を取得できるAPI。
例のエンドポイント：
https://api.openweathermap.org/data/2.5/weather
* リクエストとレスポンスのフォーマット
* HTTP GETリクエストで都市名やAPIキーなどをクエリパラメータとして送信する。
例：
https://api.openweathermap.org/data/2.5/weather?q=Tokyo&appid=YOUR_API_KEY&units=metric&lang=ja

レスポンスフォーマット
JSON形式で天気の概要、気温、湿度などの情報を取得できる。

### Q3-3. 感想
* 今回の課題で苦労したこと
* APIを理解するのに時間がかかったこと
* 演習を通して理解できたこと
* APIの仕様、リクエストやレスポンスの構造
* Web APIの利便性や課題など
* APIの利用制限やエラーハンドリング、セキュリティ面（APIキーの管理など）
