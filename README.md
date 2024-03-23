# Atte

勤怠の打刻、勤務情報の確認ができるアプリ　　
  ![image](https://github.com/shobuhinako/attendance-system/assets/142642424/93125782-859e-4f17-a5b0-836115d66972)


## 目的

  人事評価のため


## URL

  git@github.com:shobuhinako/attendance-system.git
  
  会員登録画面にて会員登録を行なった後、ログイン画面からログインして使用



## 機能一覧
  1. 会員登録機能
  2. ログイン機能
  3. ログアウト機能
  4. 勤務開始時間登録機能
  5. 勤務終了時間登録機能
  6. 休憩開始時間登録機能
  7. 休憩終了時間登録機能
  8. 日付別勤怠情報取得機能



## 使用技術（実行環境）

  laravel 8.83.8



## テーブル設計
![image](https://github.com/shobuhinako/attendance-system/assets/142642424/fc5217d3-0ced-4830-b39e-d5d3638ccbe3)



## 環境構築
1. docker-compose exec php bash
2. composer install
3. .env.exampleファイルから.envを作成し、環境変数を変更
4. php artisan key:generate
5. php artisan migrate
6. php artisan db:seed
