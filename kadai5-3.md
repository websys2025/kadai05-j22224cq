## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
エンドポイント：https://zipcloud.ibsnet.co.jp/api/search
機能：郵便番号から都道府県・市区町村・町名を調べて返す。
リクエスト例：?zipcode=1000001
レスポンス形式：JSON（例：address1: 東京都, address2: 千代田区 など）

### Q3-2. 各自で調査したAPIについて説明せよ。
API名とURL：Dog API（https://dog.ceo/dog-api/）
エンドポイント：https://dog.ceo/api/breeds/image/random
機能：ランダムな犬の画像を取得できる。
リクエスト例：そのままアクセスするだけでOK
レスポンス形式：以下のようなJSON形式で画像URLが返される

### Q3-3. 感想
苦労したこと：fetchの使い方や非同期処理（async/await）に慣れるのが大変だった。
学べたこと：APIの呼び出し方やJSONの扱い方が理解できた。
APIの印象：Webページにリアルタイムな情報を簡単に追加できて便利だが、エラー処理なども必要。
　
