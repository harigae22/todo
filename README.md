# ToDo App

Laravel を使用した Web アプリケーション  
フォルダごとにタスク管理することができる入門ToDo アプリ

参考URL:https://www.hypertextcandy.com/laravel-tutorial-introduction


## 環境  
MacOS Docker-Laradock Laravel10 PHP8.1 DB:PostgreSQL

## アプリ説明

主な機能 -  

    ・認証機能 (画面Top)  
        アカウント作成時、ログインした各ユーザーのフォルダおよびタスクだけを閲覧または編集可能。  
        パスワードを忘れた場合には再登録することが可能。  
        ログイン後、画面にてフォルダ、各フォルダ内タスク一覧表示。
        
    ・フォルダ管理  
        フォルダごとにタスク管理。  
        フォルダの作成  
        
    ・タスク管理  
        タスク（ToDo）の作成。  
        タイトル、期限日、状態を設定。  
        状態 -「未着手」「着手中」「完了」の3種類。  
        (タイトル、期限日、状態)の編集。  
        
## サーバーデプロイ

Herokuにてデプロイ、動作確認済み



