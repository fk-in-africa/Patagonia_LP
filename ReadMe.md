# 基本情報
sonaeLP管理ようのリポジトリ  
MCとして各LCのLPをどう管理していくかはAIの戦略と調整中のため  
一時的なものになるかもしれません。

## 作成者
[1718KBOGXDの大杉さん](https://github.com/hiroki0816)  
[もとのリポジトリ](https://github.com/hiroki0816/sonaeLP)  
[1819KBMarCoD山本くん](https://github.com/YukiYamamoto0222)  

## Author
[1819MCISkomatsu](https://github.com/Yuki-k-lion)


---
# 運用改善について
[基本ここと同じです](https://github.com/Yuki-k-lion/agrino)  
ここには今後ページを更新する際のルールを書いていきます。  
基本的なところは、 *Github Flow* に従うので、  
下部も読んで置いてください。  

## 01 何か追加および編集をする時
なにか追加および編集をする場合は新しいブランチを切ってください。  
その場合の命名規則は`yourname_functionname`のように `名前_作業名`で書いてください。

## 02 コミットについて
コミット文はなるべく細かく、何をどう変更したかわかりやすいようにしてください。
コミット文はどんなに長くても構いません。

## 03 マージ
編集が終わり次第プルリクエストを出してください。  
マージするのは MCIS が行います。  

## 04 デプロイ
サーバーへのアップロードはmasterブランチにマージしたあとすぐに行います。

*to MCISs*  
いきなりKBのサーバーにはアップロードできないので  
まずは踏み台サーバーへgit cloneし、  
そこからrsyncつかってKBのサーバーにアップする。  

 _メモ_
>自動デプロイのシステムを構築したい。
現状はセキュリテイの都合上簡単には行かない。

***

## Github Flowのメモ
参照：https://qiita.com/tbpgr/items/4ff76ef35c4ff0ec8314

### 基本原則
- masterブランチは 常時デプロイ可能 である
- 機能追加、バグフィックスなどは 説明的な名前のブランチ をmasterから作成する
  - 機能追加の例： add_user_notice (ユーザーの通知機能追加)
  - バグフィックスの例： fix_user_login_validation_error (ユーザーのログイン認証のVlidation修正)
- 作成したブランチでローカル開発。小さい単位でこまめにコミットし、リモートにもこまめにPush
- フィードバックや助言が欲しい時、ブランチをマージしてもよいと思ったときは、 Pull Request を作成する
  - フィードバックや助言が欲しい時に作成する Pull Request を WIP Pull Request という
  - WIP = Work In Progress
  - WIP Pull Request を行う場合は、Pull Request 名の頭に [WIP] をつけるのが慣習
- レビューOKになったら、masterへマージ
- masterへpushしたら、即デプロイをする

## Github markDownの書き方
https://qiita.com/tbpgr/items/989c6badefff69377da7
https://qiita.com/Qiita/items/c686397e4a0f4f11683d



---
# そなえLP引き継ぎドキュメント
[LookThisDocks](https://github.com/Yuki-k-lion/sonaeLP/blob/master/info_docks.md#%E3%81%9D%E3%81%AA%E3%81%88lp%E5%BC%95%E3%81%8D%E7%B6%99%E3%81%8E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88)
