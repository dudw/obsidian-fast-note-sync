[简体中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-CN.md) / [English](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/README.md) / [日本語](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ja.md) / [한국어](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ko.md) / [繁體中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-TW.md)


<h1 align="center">Fast Note Sync For Obsidian</h1>

<p align="center">
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/release/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/v/tag/haierkeys/obsidian-fast-note-sync?label=release-alpha&style=flat-square" alt="alpha-release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/LICENSE"><img src="https://img.shields.io/github/license/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="license"></a>
    <img src="https://img.shields.io/badge/Language-TypeScript-00ADD8?style=flat-square" alt="TypeScript">
</p>



<p align="center">
  <strong>高速、安定、効率的、どこにでもデプロイ可能な Obsidian ノート同期＆バックアッププラグイン</strong>
  <br>
  <em>プライベートデプロイが可能で、Obsidian ユーザーに邪魔にならない、スムーズな、マルチデバイスのリアルタイム同期＆バックアップ体験の提供に特化しています。Mac、Windows、Android、iOS などのプラットフォームに対応し、多言語をサポートしています。</em>
</p>

<p align="center">
  独立したサーバーが必要です：<a href="https://github.com/haierkeys/fast-note-sync-service">Fast Note Sync Service</a>
</p>

<div align="center">
    <img src="https://github.com/user-attachments/assets/8e61d99e-6f76-49b1-a03e-c952ad9e21b0" alt="fast-note-sync-service-preview" width="800" />
</div>


## ✨ 機能

- **最小限の設定**：煩わしい設定は不要。リモートサービス設定を貼り付けるだけで、すぐにご利用いただけます。
- **ノートのリアルタイム同期**：Vault（リポジトリ）内のすべてのノートの作成、更新、削除を自動的に監視し、同期します。
- **添付ファイルの完全サポート**：画像、動画、音声などの非設定ファイルをリアルタイムで同期します。
    > ⚠️ **注意**：バージョン v1.0+、サーバー v0.9+ が必要です。同期の遅延を防ぐため、添付ファイルのサイズは控えてください。
- **設定の同期**：設定同期機能を提供し、複数デバイス間での設定同期をサポートします。手動で各デバイスに設定ファイルをコピーする手間を省きます。
    > ⚠️ **注意**：バージョン v1.4+、サーバー v1.0+ が必要です。現在テスト段階ですので、ご注意ください。
- **サーバーバージョンの表示**：サーバーの版本情報を表示し、ステータスを簡単に把握できます。
- **マルチデバイス同期**：Mac、Windows、Android、iOS などのプラットフォームをサポート。
- **ノート履歴**：ノート履歴機能を提供します。プラグイン側またはサーバーの WebGui から、ノートのすべての変更履歴を確認したり、詳細を確認したり、過去のバージョンの内容をコピーしたりできます。

## 🗺️ ロードマップ

継続的な改善に取り組んでいます。今後の開発計画は以下の通りです：

- [ ] **オフラインデバイスのノート競合の最適化**：オフラインでの変更に対し、競合解決戦略を追加し、最新の更新のみが保持されることによるデータ損失を防止します。
- [ ] **クラウドバックアップステータス**：いつでもクラウドストレージのバックアップ状態を確認できる機能。最新のバックアップ状況を簡単に把握できます。
- [ ] **ノート共有機能**：クラウド上のノートの共有リンクを生成し、成果を簡単に他者と共有できます。
- [ ] **AI ノート**：AI+ ノートに関連する革新的な機能を探索中。皆様からの貴重な提案をお待ちしております。

> **改善の提案や新しいアイデアがございましたら、issue を通じて共有してください。適切な提案を慎重に検討し、採用させていただきます。**

## 💰 価格

- このプラグインが役立ち、開発の継続をサポートしたい場合は、以下の方法でご支援をお願いします：

  | Ko-fi *中国以外*  |  | 支付宝 (Alipay) *中国* |
  | --- | ---| --- |
  | [<img src="https://ik.imagekit.io/haierkeys/kofi.png" alt="BuyMeACoffee" height="150">](https://ko-fi.com/haierkeys) | または | <img src="https://ik.imagekit.io/haierkeys/wxds.png" height="150"> |

## 🚀 クイックスタート

1. プラグインのインストール（いずれかを選択）：
   - **公式ストア**: <s>Obsidian コミュニティプラグイン市場で **Fast Note Sync** を検索してインストール</s>
        > ⚠️ 現在、公式ストアには掲載されていないため、手動でインストールしてください。
   - **手動インストール**: https://github.com/haierkeys/obsidian-fast-note-sync/releases にアクセスしてインストールパッケージをダウンロードし、Obsidain のプラグインディレクトリ **.obsidian/plugins** に解凍します。
2. プラグインの設定を開き、「**リモート設定を貼り付け**」ボタンをクリックして、入力ボックスにサーバーの設定を貼り付けます。


## 📦 サーバーのデプロイ

バックエンドサーバーの設定については、[Fast Note Sync Service](https://github.com/haierkeys/fast-note-sync-service) を参照してください。
