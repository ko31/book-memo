# book-memo

FileMakerで作った子ども向けの読書記録アプリです。

## 機能

* 一覧画面
* 登録画面
* 登録時にカメラでバーコード（ISBNコード）を読み取って本の情報を自動取得。

## 動作環境

下記の環境で使ってます。

* iPhone 6s
* FileMaker Go 14

## 注意

* 本の情報取得には[楽天ウェブサービスAPI](https://webservice.rakuten.co.jp/api/bookstotalsearch/) を利用しているのでインターネットに繋がっていないと使えません。
* スクリプト内の楽天ウェブサービスAPIのアプリケーションIDは自分のものに変更してください。

