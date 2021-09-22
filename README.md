# Instagram-basic-api
Instagram基本表示APIの使い方。

1. [https://www.e-pokke.com/blog/instagram-basic-display-api.html](https://www.e-pokke.com/blog/instagram-basic-display-api.html) アクセスしてトークンを取得する。
1. [https://github.com/hiroghap1/instagram-basic-api](https://github.com/hiroghap1/instagram-basic-api) にアクセスして「get-feed-sample.php」と「js/get-json.js」をダウンロードする。
1. 「get-feed-sample.php」に1で取得したトークンを入力し、「get-feed.php」にファイル名を変更する。

## 仕組み
get-json.js から get-feed.php にアクセスすると、get-feed.php が Instagram基本表示APIからデータを取得し、get-json.js に返します。
そのデータを整形し、index.html 内の #instagram-feed に表示しています。
