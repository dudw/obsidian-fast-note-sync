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
  <em>プライベートデプロイ可能で、Obsidian ユーザーに邪魔にならない、シルクのように滑らかな多端末リアルタイム同期を提供することに特化したプラグインです。Mac、Windows、Android、iOS などのプラットフォームに対応し、多言語をサポートしています。</em>
</p>

<p align="center">
  独立したサーバーが必要です：<a href="https://github.com/haierkeys/fast-note-sync-service">Fast Note Sync Service</a>
</p>

<div align="center">
    <img src="https://github.com/user-attachments/assets/8e61d99e-6f76-49b1-a03e-c952ad9e21b0" alt="fast-note-sync-service-preview" width="800" />
</div>


## ✨ プラグイン機能

- **ミニマルな設定**: 複雑な設定は不要。リモートサービス設定を貼り付けるだけで、すぐにご利用いただけます。
- **ノートのリアルタイム同期**: Vault（リポジトリ）内のすべてのノートの作成、更新、削除を自動的に監視し、同期します。
- **添付ファイルのフルサポート**: 画像、動画、音声などの設定ファイル以外のファイルをリアルタイムで同期します。
    > ⚠️ **注意**: v1.0+、サーバー v0.9+ が必要。大きなファイルは同期遅延の原因となるため、ファイルサイズにご注意ください。
- **設定の同期**: 設定同期機能を提供し、複数のデバイス間での設定同期をサポート。手動で設定ファイルをコピーする手間を省けます。
    > ⚠️ **注意**: v1.4+、サーバー v1.0+ が必要。現在テスト段階のため、注意してご使用ください。
- **サーバーバージョンの表示**: サーバーのバージョン情報を表示し、サーバーの状態を簡単に確認できます。
- **マルチデバイス同期**: Mac、Windows、Android、iOS などに対応。
- **ノート履歴**: 履歴機能を提供。プラグインまたはサーバーの WebGui から、ノートのすべての履歴バージョン、修正の詳細、または履歴コンテンツのコピーが可能です。

## 🗺️ ロードマップ (Roadmap)

継続的に改善を行っています。以下は将来の開発計画です：

- [ ] **オフラインデバイスの競合最適化**: オフライン時の修正に対する競合解決戦略を追加し、最新の更新のみを残すことによるデータの損失を防止。
- [ ] **クラウドバックアップ状況**: クラウドストレージのバックアップ状態をいつでも確認可能に。
- [ ] **ノート共有機能**: クラウドノートの共有リンクを作成し、成果を簡単に共有。
- [ ] **AI ノート**: AI+ ノートに関連する革新的な機能を模索中。皆様からの貴重な提案をお待ちしております。

> **改善案や新しいアイデアがありましたら、issue を通じて教えてください。適切な提案を慎重に評価し、採用させていただきます。**

## 💰 価格

- プラグインが役に立ち、開発を支援したい場合は、こちらからサポートいただけます：
[<img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" alt="BuyMeACoffee" width="100">](https://ko-fi.com/haierkeys)


## 🚀 クイックスタート

1. プラグインのインストール（どちらか一つ）:
   - **公式ストア**: <s>Obsidian コミュニティプラグインマーケットで **Fast Note Sync** を検索してインストール</s>
        > ⚠️ まだ公式ストアに登録されていないため、手動でインストールしてください。
   - **手動インストール**: https://github.com/haierkeys/obsidian-fast-note-sync/releases からパッケージをダウンロードし、Obsidian プラグインディレクトリ **.obsidian/plugins** に展開してください。
2. プラグインの設定を開き、「**Paste Remote Configuration**」ボタンをクリックして、リモートサービス設定を入力欄に貼り付けます。


## 📦 サーバーのデプロイ

設定についてはこちらを参照してください：[Fast Note Sync Service](https://github.com/haierkeys/fast-note-sync-service)。
