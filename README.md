# Stock Management

![サイト写真](/app/assets/images/stock-management_readme.png)

# サイト概要

## 「いつでもどこでも便利に収支管理ができること」がテーマです。

ペーパーレスで環境にも優しく、私生活で扱うアイテム等を一括管理でき
計算を自動でおこなってくれる収支管理サイトです。

# テーマを選んだ理由

最近では働き方改革の一環として国が副業を推進したこともあり、多くの会社で副業が解禁されました。
それに伴い副業としてネット上でECショップをオープンしたり、ヤフオクやメルカリなどを使って商品の売買をする人も増えてきました。
ただこのような副業をする時には、売れた商品などを管理する必要が出てきます。
そこで大切になるのが収支管理です。最近はタブレットやスマホの普及なども進んでいるので、紙やエクセルよりも馴染みやすいと思います。
いつでもどこでも便利に収支管理ができるようにするためこのテーマを選びました。

# ターゲットユーザ

- 電子機器で在庫管理がしたい人
- 収支管理を楽にしたい人


# 主な利用シーン

- 物の収支管理をしたい時
- 家族や仲間と共有しながら収支管理をしたい時

# 機能一覧

- ユーザー登録機能

  - メールアドレス
  - パスワード

- ログイン機能

  - devise でログイン機能を実装
  - ゲストログイン機能を実装

- 管理者ページ

  - ユーザー登録・編集・強制退会・復帰

- 投稿ページ

  - 商品名・ジャンル・販売ステータス、備考登録する機能
  - 編集機能
  - 削除機能
  - ジャンル分け機能
  - 検索機能
  - 販売ステータス機能
  - ジャンルと販売ステータスを絞り込み自動計算機能

# 設計書


# 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9
