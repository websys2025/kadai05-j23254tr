## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* `https://zipcloud.ibsnet.co.jp/api/search`
* 郵便番号API（zipcloud）は、日本の郵便番号から住所情報を取得するためのWeb API。  
* リクエストとレスポンスのフォーマット

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
* 演習を通して理解できたこと
* Web APIの利便性や課題など
