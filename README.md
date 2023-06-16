# nodejs-webscraper
<blockquote class="trello-card"><a href="https:&#x2F;&#x2F;trello.com&#x2F;c&#x2F;YfSMTSJr&#x2F;4-%E3%83%87%E3%83%BC%E3%82%BF%E5%8F%8E%E9%9B%86%E3%82%B9%E3%82%AD%E3%83%AB%EF%BC%9Aweb%E3%82%B9%E3%82%AF%E3%83%AC%E3%82%A4%E3%83%91%E3%83%BC%EF%BC%88js%EF%BC%89%E4%BD%9C%E6%88%90">データ収集スキル：webスクレイパー（JS）作成</a></blockquote><script src="https://p.trellocdn.com/embed.min.js"></script>
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
