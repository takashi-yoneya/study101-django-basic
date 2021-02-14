# Djangoの基本課題
Djangoの基本技術の習得確認のための課題です

DBの中身を参照するため、DBクライアントをインストールしてください。
※下記は参考のため、お好きなDBクライアントで構いません
参考：https://forest.watch.impress.co.jp/library/software/heidisql/

## １
好きな名前のアプリケーションを作成し、「hello world」と
固定で表示するWebページを作成してください。

## ２
templateを使い、同じサイドメニューのページを２つ作成してください
サイドメニューの構成は、以下の通りとしてください。
鬼滅の刃
　|_ キャラクター登録
　|_ キャラクター一覧

## ３
サイドメニューの「キャラクター登録」からリンクさせたページに
入力フォームを作成してください
入力項目は以下の通りです。

名前（テキスト）
性別（選択式）
特徴（テキスト）

## ４
modelを使い、鬼滅のキャラクター情報を格納するmodelを作成してください。
migrateしてDBにテーブルができることを確認してください。

## ５
課題３で作ったフォームとmodelを連携させて、フォームで登録した内容がDBに記録されるようにしてください。

## ６
DBに登録された鬼滅のキャラクターを「キャラクター一覧」からリスト表示できようにしてください

## ７
AWSにサイトをデプロイして外部から参照できるようにしてください。
参考書籍：https://af.moshimo.com/af/c/click?a_id=2003347&p_id=170&pc_id=185&pl_id=27060&url=https%3A%2F%2Fwww.amazon.co.jp%2Fdp%2FB07YY5RDPC


