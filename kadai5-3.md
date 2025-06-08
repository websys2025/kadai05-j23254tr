## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* `https://zipcloud.ibsnet.co.jp/api/search`
* 郵便番号API（zipcloud）は、日本の郵便番号から住所情報を取得するためのWeb APIです。  
* リクエストとレスポンスのフォーマット
* JSON形式で住所情報を返す。  
主なレスポンス例：  
```json
{
  "results": [
    {
      "zipcode": "1000001",
      "address1": "東京都",
      "address2": "千代田区",
      "address3": "千代田",
      ...
    }
  ],
  "status": 200,
  "message": null
}
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* エンドポイントと機能
* リクエストとレスポンスのフォーマット
### Q3-3. 感想
* 今回の課題で苦労したこと
* 演習を通して理解できたこと
* Web APIの利便性や課題など
