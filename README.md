# Ubuntu 開発環境構築（VirtualBox）

## ■ 目的
ローカル環境で開発・動作確認を行い、その後AWSへ展開するための基盤を作成する。

---

## ■ 環境
- ホストOS：Windows
- 仮想環境：VirtualBox
- ゲストOS：Ubuntu

---

## ■ 構築手順

### ① VirtualBox インストール

### ② Ubuntu ダウンロード

### ③ 仮想マシン作成

### ④ Ubuntu インストール

---

## ■ 初期設定

```bash
sudo apt update
sudo apt upgrade -y

## ■ ネットワーク確認結果

- インターフェース：enp0s3
- IPアドレス：10.0.2.15
- 状態：UP（正常）

- デフォルトゲートウェイ：10.0.2.2
→ インターネット接続OK

## ■ 外部接続確認

```bash
ping -c 3 google.com

結果：
- 応答あり
- パケットロス：0%

→ インターネット接続正常
