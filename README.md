# Nobu42 | AWS Infrastructure as Code

AWSとInfrastructure as Code（IaC）を中心に、インフラの構築コード、構成図、検証記録を公開しています。
TerraformとAWS CloudFormationを使い、AWS構成のコード化と変更内容の確認に取り組んでいます。

## AWS IaC Projects

| リポジトリ | 内容 |
|---|---|
| [terraform-iac-Lab](https://github.com/Nobu42/terraform-iac-Lab) | AWS CLI・Shell Scriptで構築したAWS基盤をTerraformへ移行。構成コード、設計図、検証記録をまとめています。 |
| [cloudformation-iac-lab](https://github.com/Nobu42/cloudformation-iac-lab) | CloudFormationによるAWS構築と、RDS・Redis更新時のテンプレート整合を検証するためのリポジトリです。 |

## Network Architecture

Terraform・CloudFormationでコード化する元となるAWS構成図です。

[![ネットワーク構成図](https://raw.githubusercontent.com/Nobu42/terraform-iac-Lab/main/docs/network-diagrams/01-network.png)](https://github.com/Nobu42/terraform-iac-Lab/blob/main/docs/network-diagrams/01-network.png)

## Focus

- AWSのネットワーク・Webアプリケーション基盤の設計と構築
- Terraform・CloudFormationによる構成管理と変更差分の確認
- 構築手順・検証結果・リファレンスの整理

## Tools

- **IaC**: Terraform / AWS CloudFormation（YAML・JSON）
- **構成管理**: Ansible
- **CLI・スクリプト**: AWS CLI / Bash / Python
- **開発環境**: Git / VS Code / Vim
