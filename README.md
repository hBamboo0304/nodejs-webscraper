# nodejs-webscraper
メモ
* npm： `Node Package Manager`
* axios：

  * ブラウザからXMLHttpRequest を作成する
  * Node.jsからhttpリクエストを行う
  * Promise APIをサポート
  * リクエストとレスポンスをインターセプトする
  * リクエストとレスポンスのデータを変換する
  * リクエストのキャンセル
  * JSONデータの自動変換
  * 🆕データオブジェクトの自動シリアル化`multipart/form-data`と`x-www-form-urlencoded`本体エンコーディング
  * XSRFから保護するためのクライアント側のサポート
* **cheerio：**
HTMLをパースしたい場合使うと楽。Cheerio のセレクター実装は jQuery のものとほぼ同じだから「$」で取り出せる

```.js
$('.apple', '#fruits').text();
//=> Apple

$('ul .pear').attr('class');
//=> pear

$('li[class=orange]').html();
//=> Orange
```
