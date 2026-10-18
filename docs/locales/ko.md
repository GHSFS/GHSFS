<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <strong>🇰🇷 한국어</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=FF7043&center=true&vCenter=true&width=620&lines=%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94%2C+GHSFS%EC%9E%85%EB%8B%88%EB%8B%A4;Rust+%EA%B8%B0%EB%B0%98%EC%9D%98+%EC%B4%88%EA%B3%A0%EC%86%8D+%EB%84%A4%EC%9D%B4%ED%8B%B0%EB%B8%8C+%EB%8F%84%EA%B5%AC+%EA%B0%9C%EB%B0%9C;%EB%B2%88%EA%B3%84%EC%B2%98%EB%9F%BC+%EB%B9%A0%EB%A5%B4%EA%B3%A0+%EC%9E%91%EC%9D%80+%EB%B0%94%EC%9D%B4%EB%84%88%EB%A6%AC;%EA%B7%80%EC%B0%AE%EC%9D%80+%EA%B1%B4+%EC%A0%84%EB%B6%80+%EC%9E%90%EB%8F%99%ED%99%94." alt="typing"/>
</a>

</div>

---

### 👋 반가워요!

Rust로 **가볍고 번개처럼 빠른 네이티브 시스템 도구**를 만들고, 컴파일된 바이너리를 뜯어보며, 귀찮은 반복 작업은 **GitHub Actions 자동화 파이프라인**으로 전부 자동 처리하는 엔지니어입니다.

20KB짜리 바이너리 하나 분석하자고 15초씩 무거운 JVM 웜업을 기다리거나, 불필요하게 램을 몇 기가씩 잡아먹는 비효율적인 툴을 정말 싫어합니다. 1ms 안에 끝낼 수 있다면 군더더기 없이 그렇게 돌아가야 한다고 생각합니다.

---

### 🚀 주력 개발 프로젝트: [`binvibe`](https://github.com/GHSFS/binvibe) *(Flagship)*

> **초고속 네이티브 바이너리 리버스 엔지니어링 MCP 서버 & 실전 실용주의 플러그인**  
> *100% Rust로 작성되어 AI 코딩 에이전트와 MCP 프로토콜로 직통 연결됩니다.*

[![CI](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml)
[![Mirror Sync](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml)
[![License: MIT OR Apache-2.0](https://img.shields.io/badge/License-MIT%20OR%20Apache--2.0-blue.svg)](https://github.com/GHSFS/binvibe/blob/main/LICENSE-MIT)

- **배경**: 기존 리버싱 도구들(Ghidra, IDA Pro, 무거운 파이썬 래퍼)은 실행이 너무 느리고, 메모리를 수 GB씩 먹으며, AI에게 어셈블리 분석을 맡기면 뻔한 도덕적 훈계나 방어적 거절로 작업 흐름을 끊는 문제가 있었습니다.
- **해결책**: `binvibe`는 1ms 미만으로 즉각 기동하며, `iced-x86`으로 나노초 단위 기계어 디코딩, `goblin` 제로 카피 메모리 맵 기반 PE/ELF/Mach-O 파싱, 그리고 AI 친화적인 Micro-IR 의사코드(Pseudo-C)를 복원합니다.
- **자동화 개발 환경**: 로컬 자원을 아끼고 지속적인 개발을 위해 모든 빌드와 멀티 OS(Ubuntu, Windows, macOS) 테스트, 그리고 4대 플랫폼(GitLab, Gitea, Hugging Face) 미러링까지 GitHub Actions를 통해 100% 자동 구동되도록 구축했습니다.

👉 **저장소 둘러보기**: [github.com/GHSFS/binvibe](https://github.com/GHSFS/binvibe)

---

### ⚙️ 작업 철학

- **작고 빠르게 만들기**: 바이트 하나도 낭비하지 않습니다. 단순 CLI 하나에 수백 MB짜리 런타임을 얹을 필요는 없습니다.
- **자동화할 수 있는 건 전부 자동화**: 같은 작업을 두 번 해야 한다면 즉시 GitHub Action이나 백그라운드 봇으로 전환합니다.
- **실전 실용주의 (Pragmatic Engineering)**: 탁상공론식 교과서 규정에 갇히지 않고, 실제로 동작하는 우회로와 실전 해결책을 직접 설계합니다.
- **다중 플랫폼 미러링**: 주력 오픈소스 저장소는 GitHub뿐만 아니라 GitLab, Gitea, Hugging Face로 실시간 자동 미러링됩니다.

---

### 📦 그 외 제작한 프로젝트들

<details open>
<summary><b>🛡️ 바이너리 포렌식, 보안 & 스테가노그래피</b> (클릭하여 접기)</summary>
<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
무손실 PNG/WAV/BMP/MP3 스테가노그래피와 이중 하드웨어 바인딩(`Argon2id` + `ChaCha20-Poly1305` + Windows `DPAPI`)을 결합한 제로 트러스트 암호화 볼트(`svault`).<br/>
디코이 더미 볼륨, 샤미르 비밀 공유, 리드-솔로몬 자체 복구, TOTP 탑재.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
외부 종속성 없는 바이너리 포렌식 & 정적 검사 엔진 (`bsentinel`).<br/>
PE32/PE64, ELF64, Mach-O 파싱, 패커 엔트로피 측정, Authenticode 인증서 검증, 선언적 패치 레시피 생성.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
외부 종속성 없는 네트워크 패킷 포렌식 & 트래픽 핑거프린팅 (`nspecter`).<br/>
PCAP/PCAPNG 파서, TCP 스트림 재조립, TLS JA3/JA4 핑거프린트 추출, QUIC 복호화 지원.

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
IoT 및 임베디드 펌웨어 언패커 & 취약점 정적 분석기 (`fcarver`).<br/>
SquashFS v4, U-Boot, TRX 컨테이너 언패킹, 엔트로피 기반 파티션 분할 및 멀티 아키텍처 셸코드 분석.

</td>
</tr>
</table>
</details>

<details>
<summary><b>📦 Windows 데스크톱 RDL 워크플로 도구</b> (클릭하여 펼치기)</summary>
<br/>

> **클립보드 감지 → 트레이 상주 → 원격 다운로더 → 토스트 알림**으로 이어지는 간결한 Windows 생산성 파이프라인.

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
GitHub Actions 기반 원격 다운로더. URL을 넘기면 러너가 직접 다운로드하여 클라우드로 릴레이.

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Windows 시스템 트레이 상주 유틸리티. 클립보드 URL을 실시간 감지하여 자동 큐 등록 및 네이티브 토스트 알림.

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Windows 탐색기 우클릭 컨텍스트 메뉴 확장. 파일이나 링크를 원클릭으로 원격 큐에 즉각 전송.

</td>
</tr>
</table>
</details>

<details>
<summary><b>🤖 서버리스 & 엣지 봇</b> (클릭하여 펼치기)</summary>
<br/>

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Cloudflare Workers 무료 티어에서 구동되는 서버리스 텔레그램 봇. 사용자 입력 프롬프트의 복잡도를 판별하여 경량 고속 모델과 심층 추론 모델로 자동 라우팅하고 Workers KV에 대화 맥락을 유지합니다.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)

</details>

---

### 🛠 기술 스택

```rust
fn current_stack() -> Vec<&'static str> {
    vec![
        "Rust (iced-x86, goblin, tokio, memmap2)",
        "Win32 API & Windows DPAPI Security",
        "Binary Forensics & Reverse Engineering",
        "Model Context Protocol (MCP) Servers",
        "GitHub Actions CI/CD Automation",
        "TypeScript & Cloudflare Workers Edge",
    ]
}
```

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1f1f1f?style=for-the-badge&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/Win32-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</div>

---

### 🌐 다중 플랫폼 미러

모든 주요 도구는 오픈 생태계 전반에 실시간 동기화됩니다:

- **GitHub**: [github.com/GHSFS](https://github.com/GHSFS) *(메인 소스)*
- **GitLab**: [gitlab.com/ghsfs_4c1f7f](https://gitlab.com/ghsfs_4c1f7f)
- **Gitea**: [gitea.com/GHSFS](https://gitea.com/GHSFS)
- **Hugging Face**: [huggingface.co/ghsfs-dev](https://huggingface.co/ghsfs-dev)

---

<div align="center">

<sub>⚡ <i>"최고의 코드는 가볍고 빠르며, 키보드에서 손을 떼기도 전에 CI에서 이미 검증된 코드입니다."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
