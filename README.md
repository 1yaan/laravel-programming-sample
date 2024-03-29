# Laravelプログラマー養成＆マナー講座用サンプルプロジェクト

[株式会社RedoIT](https://redoit.tech)が開催する「Laravelプログラマー養成＆マナー講座」では、本リポジトリを利用して開発を行っていく過程を学習していきます。

## 一番最初の状態

このシステムは、簡単なECサイトになっています。  
構築済み機能の一覧は[こちら](./doc/PRECONSTRUCTED_FUNCTIONS.md)  

## 作業の進め方

- このリポジトリを[Fork](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)して、自分のところにコピーします。  
- [issue一覧](./doc/ISSUES.md) に記載されている内容を１つずつ issue として登録していきましょう。画像もしっかり登録します。  
- issueに記載された内容を、コーディングしていきます。issueには解説はありません。作業指示のみが記載されています。現実に合わせるため、内容はわかりやすかったりわかりにくかったりするでしょう。解説は、[Laravelプログラマー＆マナー講座](https://redoit.tech/laravel-programmer)にて解説しています。  

## 開発環境の作成方法

[Docker環境構築方法](./doc/DOCKER_USAGE.md) にまとめました。  

### 開発環境 URL

- [http://localhost:8000/](http://localhost:8000/) Web
  - [利用者ログイン](http://localhost:8000/login)  
    email: user_test@redoit.tech  
    password: password  
  - [管理者ログイン](http://localhost:8000/login/admin)  
    email: admin_test@redoit.tech  
    password: password  
- [http://localhost:8880/](http://localhost:8880/) phpMyAdmin
- [http://localhost:8025/](http://localhost:8025/) MailHog

## 非機能要件

[非機能要件](./doc/NON_FUNCTIONAL_REQUIREMENT.md) にまとめました。  
開発者も非機能要件を把握し、処理速度やサービス持続性について意識しましょう。  

## ログ出力

ログをどのように出力するのか、[ログ出力基準](./doc/LOG_DESIGN.md) にまとめました。

## リリース

- mainブランチにマージでUAT環境
- mainブランチにタグをつけてマージで本番環境

## 技術力アップのために！「ステップアップ」

1. 毎日[寿司打](https://sushida.net/)をやろう！  
   お手軽→お勧め→高級を1回ずつやろう！  
2. SQLの練習をしよう！  
   練習問題を用意しました！→[こちら](./doc/stepup/SQL.md)  
