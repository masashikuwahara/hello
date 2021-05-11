# To Doアプリ
![04f5bfcebee7172c56cb228ee1d75926](https://user-images.githubusercontent.com/80254228/117602834-93508e80-b18c-11eb-8d2f-1c97b133b4ce.png)

JavaScriptとajax学習のために開発したToDoアプリです。
やることを記入してチェックを入れることができます。

# アプリケーション概要
![dfcde7a1ab4e555a6d524777d22532ec](https://user-images.githubusercontent.com/80254228/117602870-a7948b80-b18c-11eb-9e09-c76ad2a2b91f.gif)

新規登録、編集、削除機能が付き、終わったタスクにはチェックボックスに
チェックを入れることができます。
ajax通信を行うことができるので、チェックボックスに入れたチェックは
更新しても付いたままにすることができます。

# URL
https://todo35089.herokuapp.com/

# 利用方法
- トップページの新規追加からやることを記入してタスクを追加
- タスクを編集したい時は編集ボタンから行う
- 削除したい時は削除ボタンから行う
- 終わったタスクは左のチェックボックスにチェックを入れる

# 大変だったところ
herokuにデプロイする際にsqlite3が対応しておらず、そのままではできなかったことです。
新たにPostgreSQLを導入し、herokuデプロイ時にはデータベースをPostgreSQLで
使用できるようにしました。