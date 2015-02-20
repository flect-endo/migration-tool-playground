# migration-tool-playground

## 準備

### 移行ツールをダウンロード・セットアップ

1. Java, Antをインストール
2. Force.com から、[設定] - [ビルド] - [開発] - [ツール] - [Force.com移行ツール]
3. 解凍して出てきた `ant-salesforce.jar` をこのリポジトリの直下に配置する

### 環境変数のセット

|環境変数名|説明|設定例|
|----|----|----|
|SALESFORCE_USERNAME|Force.comログイン名（メールアドレス）|aaa@test.net|
|SALESFORCE_PASSWORD|Force.comログインパスワード + セキュリティトークン||

## 使い方

Antそのままなので、各タスクの説明

- pkg1
  - カスタムオブジェクトを一つ登録する
  - パッケージ名はPkg1
