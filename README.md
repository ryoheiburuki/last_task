# README
# Apartment Hunting

## 概要

ユーザー課金型の不動産検索サイト

## コンセプト

数年に1度のライフイベントである物件探しに失敗したくないユーザー向けに、物件の情報だけでなく物件を仲介する業者の情報・口コミを閲覧できるポータルサイトです。従来の仲介業者のみが利用料を払うポータルサイトには提供できない仲介業者の情報を、ユーザー課金を取り入れたビジネスモデルにすることで提供できるようにします。

## バージョン

Ruby 2.5.0 Rails 5.1.6

## 機能一覧
* 不動産業者関連の機能
    * ログイン
    * 物件情報の登録
        * 住所、家賃、広さ、間取り、画像（複数）など
    * 物件情報の削除
    * 物件情報の編集
    * お気に入り登録したユーザーを見る機能
    * ユーザーにメールを送る機能
* ユーザー関連の機能
    * ログイン
    * お気に入り登録
    * 求める条件を登録
        * 地域、家賃などの複数条件に合致するものをレコメンドするメール機能
* 仲介業者の評価機能
    * ユーザーによる口コミ投稿機能
    * ユーザーの口コミにより、仲介業者を5段階で評価する機能
* 不動産検索機能
    * 地域、家賃、広さ、間取りなどで複合条件の検索

## テーブル定義

https://docs.google.com/spreadsheets/d/1Nhm2oxgpuMVY8EUHctFwQ2xptzVVQIw9P6_WZrJWCpM/edit?usp=sharing

## 画面遷移図

https://app.milanote.com/1GtjNw1hL9OK1U

## 画像ワイヤーフレーム

https://cacoo.com/diagrams/K5kv11IsghW2tr2m/34224

## 使用Gem

* carrierwave
* mini_magick
* devise
* pry-rails
* better_errors
* binding_of_caller
* letter_opener_web
