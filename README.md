# test-android-app
Android練習用アプリ

# はじめの一歩

## まずは

当面の目標  
数字Nを入力すると0からNまでの合計をテキストに表示する。  

ゴールはSlack連携した何か  


## はじめてみた警告文

> Changes were not applied.
> Adding or renaming a resource requires an
> application restart.
> Resource 'test' (string) was added.
> Reinstall and restart app

要約  
リソースファイルに値を追加したら  
アプリケーションをリスタートしなきゃダメよ。  

## リソースファイル
リソースファイルってのはRのこと。  
レイアウトや値、フォント数の管理をしている。  
形式はXML  

## 基本のキ

Androidアプリケーション上にあるUIのことを
コード上ではViewと呼ぶ

Viewにアクションをつける場合はイベントリスナーを登録する。  
UI要素の値を参照する場合はリソースIDを使う。  

それぞれの状態遷移をアクティビティと呼び  
状態遷移の移り変わりをアクティビティサイクルという。  

## リソースID

Viewそれぞれが持つIDのこと  
今はそれだけわかる。

## TextView

Android版テキストラベル  

## Button
シンプルなボタン

## CharactorSequence

Stringに実装されたインターフェイス  
今はその理解  

## SnackBar
一瞬だけ表示されて消えるアイツ  
なんか、昔は違う名前だったような気がしてならない。  

## MainActivity.kt

起動時の画面を構成するメインファイル

## FirstFragment.kt

起動時の画面に埋め込まれるファイル

## SecondFragment.kt
FirstFragmentから呼び出すファイル

