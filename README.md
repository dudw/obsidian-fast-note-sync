[简体中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-CN.md) / [English](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/README.md) / [日本語](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ja.md) / [한국어](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ko.md) / [繁體中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-TW.md)


<h1 align="center">Fast Note Sync For Obsidian</h1>

<p align="center">
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/release/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/v/tag/haierkeys/obsidian-fast-note-sync?label=release-alpha&style=flat-square" alt="alpha-release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/LICENSE"><img src="https://img.shields.io/github/license/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="license"></a>
    <img src="https://img.shields.io/badge/Language-TypeScript-00ADD8?style=flat-square" alt="TypeScript">
</p>



<p align="center">
  <strong>Fast, stable, efficient, and deploy-anywhere Obsidian note synchronization & backup plugin</strong>
  <br>
  <em>Privately deployable, focused on providing Obsidian users with an unobtrusive, silky smooth, real-time multi-device synchronization and backup experience. Supports Mac, Windows, Android, iOS, and provides multi-language support.</em>
</p>

<p align="center">
  Requires a standalone server: <a href="https://github.com/haierkeys/fast-note-sync-service">Fast Note Sync Service</a>
</p>

<div align="center">
    <img src="https://github.com/user-attachments/assets/8e61d99e-6f76-49b1-a03e-c952ad9e21b0" alt="fast-note-sync-service-preview" width="800" />
</div>


## ✨ Features

- **Minimalist Configuration**: No tedious setup; just paste the remote service configuration and it's ready to use.
- **Real-time Note Sync**: Automatically monitors and synchronizes creation, update, and deletion of all notes within the Vault.
- **Full Attachment Support**: Synchronizes images, videos, audio, and other non-configuration files in real-time.
    > ⚠️ **Note**: Requires v1.0+, server v0.9+. Please keep attachment file sizes manageable, as large files may cause synchronization delays.
- **Config Sync**: Provides configuration synchronization, supporting config sync across multiple devices. Say goodbye to the pain of manually copying config files.
    > ⚠️ **Note**: Requires v1.4+, server v1.0+. Currently in beta, please use with caution.
- **Server Version Status**: Displays server version information to keep you informed of the server's status.
- **Multi-platform Sync**: Supports Mac, Windows, Android, and iOS.
- **Note History**: Provides note history functionality. You can view all historical versions of notes, check modification details, or copy content from historical versions via the plugin or the server WebGui.

## 🗺️ Roadmap

We are continuously improving. Here is the future development plan:

- [ ] **Offline Conflict Optimization**: Implement conflict resolution strategies for modifications on offline devices to avoid data loss caused by keeping only the latest update.
- [ ] **Cloud Backup Status**: View cloud storage backup status at any time to stay informed about the latest backups.
- [ ] **Note Sharing**: Generate sharing links for your cloud notes to easily share your work with others.
- [ ] **AI Notes**: Explore innovative AI+ note-related features. We look forward to your valuable suggestions.

> **If you have suggestions for improvement or new ideas, please share them with us by submitting an issue—we will carefully evaluate and adopt suitable suggestions.**

## 💰 Pricing

- If you find this plugin useful and want to support its continued development, you can support me here:

  | Ko-fi *Non-Mainland China*  |  | Alipay *Mainland China* |
  | --- | ---| --- |
  | [<img src="https://ik.imagekit.io/haierkeys/kofi.png" alt="BuyMeACoffee" height="150">](https://ko-fi.com/haierkeys) | or | <img src="https://ik.imagekit.io/haierkeys/wxds.png" height="150"> |

## 🚀 Quick Start

1. Install the plugin (choose one):
   - **Official Store**: <s>Search for **Fast Note Sync** in the Obsidian community plugin market</s>
        > ⚠️ Plugin is not yet on the official store; please install manually.
   - **Manual Installation**: Visit https://github.com/haierkeys/obsidian-fast-note-sync/releases to download the package, then extract it to the Obsidian plugin directory **.obsidian/plugins**
2. Open the plugin settings, click the **Paste Remote Configuration** button, and paste the remote service configuration into the input box.


## 📦 Server Deployment

For backend service settings, please refer to: [Fast Note Sync Service](https://github.com/haierkeys/fast-note-sync-service).