[简体中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-CN.md) / [English](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/README.md) / [日本語](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ja.md) / [한국어](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.ko.md) / [繁體中文](https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/docs/README.zh-TW.md)


<h1 align="center">Fast Note Sync For Obsidian</h1>

<p align="center">
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/release/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/releases"><img src="https://img.shields.io/github/v/tag/haierkeys/obsidian-fast-note-sync?label=release-alpha&style=flat-square" alt="alpha-release"></a>
    <a href="https://github.com/haierkeys/obsidian-fast-note-sync/blob/master/LICENSE"><img src="https://img.shields.io/github/license/haierkeys/obsidian-fast-note-sync?style=flat-square" alt="license"></a>
    <img src="https://img.shields.io/badge/Language-TypeScript-00ADD8?style=flat-square" alt="TypeScript">
</p>



<p align="center">
  <strong>빠르고 안정적이며 효율적인, 어디에나 배포 가능한 Obsidian 노트 동기화 및 백업 플러그인</strong>
  <br>
  <em>개인 배포를 지원하며, Obsidian 사용자에게 방해받지 않는 실크처럼 부드러운 다중 기기 실시간 동기화 및 백업 경험을 제공하는 전용 플러그인입니다. Mac, Windows, Android, iOS 등 다양한 플랫폼을 지원하며 다국어를 지원합니다.</em>
</p>

<p align="center">
  독립적인 서버가 필요합니다: <a href="https://github.com/haierkeys/fast-note-sync-service">Fast Note Sync Service</a>
</p>

<div align="center">
    <img src="https://github.com/user-attachments/assets/8e61d99e-6f76-49b1-a03e-c952ad9e21b0" alt="fast-note-sync-service-preview" width="800" />
</div>


## ✨ 플러그인 기능

- **미니멀한 설정**: 번거로운 설정 없이 원격 서비스 구성을 붙여넣기만 하면 즉시 사용 가능합니다.
- **노트 실시간 동기화**: Vault(저장소) 내 모든 노트의 생성, 업데이트, 삭제 작업을 자동으로 감지하고 동기화합니다.
- **첨부 파일 완벽 지원**: 이미지, 비디오, 오디오 등 설정 파일이 아닌 모든 파일을 실시간으로 동기화합니다.
    > ⚠️ **주의**: v1.0 이상, 서버 v0.9 이상이 필요합니다. 대용량 파일은 동기화 지연을 유발할 수 있으므로 파일 크기를 조절해 주세요.
- **설정 동기화**: 여러 기기 간의 설정 동기화 기능을 제공하여 수동으로 설정 파일을 복사하는 번거로움을 덜어줍니다.
    > ⚠️ **주의**: v1.4 이상, 서버 v1.0 이상이 필요합니다. 현재 테스트 단계이므로 주의해서 사용해 주세요.
- **서버 버전 확인**: 서버의 버전 정보를 표시하여 서버 상태를 쉽게 파악할 수 있습니다.
- **다중 기기 동기화**: Mac, Windows, Android, iOS 등을 지원합니다.
- **노트 히스토리**: 노트 기록 기능을 제공합니다. 플러그인 또는 서버 WebGui에서 노트의 모든 과거 버전과 수정 내역을 확인하거나 내용을 복사할 수 있습니다.

## 🗺️ 로드맵 (Roadmap)

지속적으로 개선 중입니다. 다음은 향후 개발 계획입니다:

- [ ] **오프라인 기기 노트 충돌 최적화**: 오프라인 기기에서 발생한 충돌을 해결하기 위한 전략을 추가하여 최신 업데이트만 유지되는 데이터 손실을 방지합니다.
- [ ] **클라우드 백업 상태**: 클라우드 저장소 백업 상태를 언제든지 확인할 수 있는 기능을 제공합니다.
- [ ] **노트 공유 기능**: 클라우드 노트의 공유 링크를 생성하여 자신의 성과를 타인과 쉽게 공유할 수 있도록 합니다.
- [ ] **AI 노트**: AI와 결합된 혁신적인 노트 기능을 탐색 중입니다. 여러분의 소중한 제안을 기다립니다.

> **개선 제안이나 새로운 아이디어가 있다면 issue를 통해 공유해 주세요. 적절한 제안을 신중하게 검토하고 반영하겠습니다.**

## 💰 가격

- 이 플러그인이 유용하고 지속적인 개발을 응원하고 싶다면 여기서 후원해 주세요:
[<img src="https://cdn.ko-fi.com/cdn/kofi3.png?v=3" alt="BuyMeACoffee" width="100">](https://ko-fi.com/haierkeys)


## 🚀 빠른 시작

1. 플러그인 설치 (택 1):
   - **공식 스토어**: <s>Obsidian 커뮤니티 플러그인 마켓에서 **Fast Note Sync** 검색 후 설치</s>
        > ⚠️ 아직 공식 스토어에 등록되지 않았으므로 수동으로 설치해 주세요.
   - **수동 설치**: https://github.com/haierkeys/obsidian-fast-note-sync/releases 에서 설치 패키지를 다운로드한 후, Obsidian 플러그인 디렉터리 **.obsidian/plugins** 에 압축을 해제하세요.
2. 플러그인 설정을 열고 **Paste Remote Configuration** 버튼을 클릭하여 원격 서비스 구성을 입력창에 붙여넣습니다.


## 📦 서버 배포

서버 설정은 다음을 참조하세요: [Fast Note Sync Service](https://github.com/haierkeys/fast-note-sync-service).
