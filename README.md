# CodingAgentv2

このプロジェクトは、GitHub Issueに基づいてコードを自動実装するAI駆動の開発エージェントシステムです。Claude AIが Issue の内容を解析し、自動的にコードの実装とPull Requestの作成を行います。

## 使い方

1. GitHub Issue を作成し、実装したい内容を記載する
2. Issue に `ready-for-impl` ラベルを付ける
3. Claude エージェントが自動的に実装を開始し、Pull Request を作成する