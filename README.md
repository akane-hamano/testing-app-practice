# testing-app-practice

## 概要
COACHTECH 教材 Tutorial 10-5「テスト ハンズオン演習」で作成した成果物です。Laravelのテスト機能を使って、ユーザー作成機能のテストコードを作成しました。

## 使用技術
- PHP 8.x
- Laravel 10.x
- PHPUnit（テスト）
- Eloquent / Factory

## 学んだこと
- 正常系テストと異常系テスト
- テスト間の干渉を防ぐRefreshDatabaseトレイト
- ファクトリー（Factory）を使った、テストデータの効率的な作成方法

## 動作確認
ターミナルで sail artisan test --filter UserTest を実行し、緑色のチェックマークが表示されればテスト成功です。

