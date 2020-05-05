# chat-profile
チャットUIを使った自己紹介サイト作成Kit

このようなサイトが作れます
https://yoshikai.net/interview.html

![Takuto Yoshikai's Profile](https://github.com/TakutoYoshikai/chat-profile/blob/master/cover.png)


### 使い方
#### 自動生成
1. index.jsを編集して、myIconに自分側のアイコンのパス、yourIconに相手側のアイコンのパスを設定する。

2. chat.csvを編集して、以下の記法に従って表示させるメッセージを追加する
* メッセージは一行で記述し、改行してから次のメッセージを登録する
* 自分側のメッセージとして登録する時には最初にmをつける
* 相手側のメッセージとして登録する時には最初にyをつける
* メッセージのタイトルをつける時は最初にtをつける
* 自分のメッセージとして画像を表示させる時は最初にiをつける
* 相手のメッセージとして画像を表示させる時は最初にjをつける
#### htmlタグ書き出し
1. export.jsを編集して、myIconに自分側のアイコンのパス、yourIconに相手側のアイコンのパスを設定する。

2. chat.csvを編集して、以下の記法に従って表示させるメッセージを追加する

3. node.jsでexport.jsを実行
```
node export.js
```
4. コピーしてindex.htmlに貼り付け

5. index.jsの読み込みタグを削除
