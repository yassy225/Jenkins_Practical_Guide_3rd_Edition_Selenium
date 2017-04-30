# 『［改訂第3版］Jenkins実践入門 ――ビルド・テスト・デプロイを自動化する技術』サンプルコードのダウンロード

## 書籍について
- 川口耕介，佐藤聖規　監修，佐藤聖規，和田貴久，新井雄介，米沢弘樹，山岸啓，岩成祐樹　著
- 『［改訂第3版］Jenkins実践入門――ビルド・テスト・デプロイを自動化する技術』（WEB+DB PRESS plus シリーズ）
- A5判／416ページ
- 技術評論社、2017年

### サポートページ
https://gihyo.jp/magazine/wdpress/plus/978-4-7741-7423-5

### WEB+DB PRESS plusシリーズ
http://gihyo.jp/magazine/wdpress/plus

## 注意
本サンプルコード、本書の内容に基づく運用結果について、監修者、著者、ソフトウェアの開発元および提供元、株式会社技術評論社は一切の責任を負いかねますので、あらかじめご了承ください。

### サンプルコードのライセンス
サンプルコードはMITライセンスで配布しています。

http://opensource.org/licenses/mit-license.php

## Gitを利用せずにダウンロード
本ページ上部にある「Download ZIP」ボタンを押すと、最新のソースコードがダウンロードできます。Gitを利用していない方はこちらをご利用ください。

## 本書についてのご質問
本書についてのお問い合わせは、以下のページからお願いします。
https://gihyo.jp/site/inquiry/book?978-4-7741-7423-5

## ソースコードについて
本書の4章〜8章での修正済のsampleprojectに対するSeleniumテストコードです。
未修整状態のsampleprojectを利用した場合、いくつかのテストが失敗します。
下記の環境にて動作を確認済です。(確認日: 2017年4月24日)
* Apache Maven 3.5.0
* Java SE Development Kit 8u121 (JDK 8 Update 121)
* Firefox 53

Firefoxの最新版を利用した場合、Seleniumのテストコードが正常に実行できない場合があります。その場合、pom.xmlの下記の部分のバージョンを最新版のSeleniumのバージョンに変更してください。

### 修正例

* 修正前
```
<selenium-java.version>3.4.0</selenium-java.version>
```

* 修正後
```
<selenium-java.version>2.5.0</selenium-java.version>
```
