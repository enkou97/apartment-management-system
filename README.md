# apartment-management-system

## 概要
Spring Boot を用いた賃貸管理システムのバックエンド学習プロジェクトです。  
動画教材をもとに、PC向け管理画面機能を中心としたバックエンド開発を学習し、CRUD、ページング、認証認可、画像アップロード、キャッシュ処理、単体テストまで一通りの流れを確認しました。

## 使用技術
- Java
- Spring Boot
- MyBatis-Plus
- MySQL
- Redis
- MinIO
- Docker
- JUnit
- Mockito
- JWT
- Knife4j

## 主な学習内容
- CRUD API 実装
- ページング機能
- JWT 認証およびロール権限管理
- MinIO を用いた画像アップロード
- Redis を用いたキャッシュ処理
- JUnit / Mockito による単体テスト
- Docker による開発環境構築
- Knife4j による API 確認

## プロジェクト構成
- `common`  
  共通処理、共通設定、ユーティリティなど
- `model`  
  Entity、DTO、VO などのデータ定義
- `web`  
  Controller、Service、Mapper、設定クラスなど

## 実行環境
- JDK 17
- Maven
- MySQL
- Redis
- MinIO
- Docker

## 実行方法
1. MySQL、Redis、MinIO を起動
2. 必要に応じてデータベースを作成し、初期SQLを実行
3. `application.yml` の接続情報を環境に合わせて設定
4. Spring Boot アプリケーションを起動
5. Knife4j から API の動作確認を実施

## 学習を通じて理解したこと
- Spring Boot における Controller / Service / Repository の層構造
- DB設計の基本的な流れ
- 認証認可を含むバックエンドAPI開発の基本
- 外部ストレージやキャッシュを含めた構成の考え方
- 単体テストの基本的な書き方

## 補足
本プロジェクトは動画教材をもとに学習した内容を、自分なりに整理したものです。  
教材に沿って実装・確認を進めながら、バックエンド開発の流れや使用技術への理解を深めました。
