<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <strong>🇰🇷 한국어</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=FF7043&center=true&vCenter=true&width=620&lines=Rust+%EA%B8%B0%EB%B0%98+%EC%B4%88%EA%B3%A0%EC%86%8D+%EB%84%A4%EC%9D%B4%ED%8B%B0%EB%B8%8C+%EB%8F%84%EA%B5%AC+%EA%B0%9C%EB%B0%9C;%EC%A0%80%EC%88%98%EC%A4%80+%EC%8B%9C%EC%8A%A4%ED%85%9C%EA%B3%BC+%EB%B0%94%EC%9D%B4%EB%84%88%EB%A6%AC+%EB%B6%84%EC%84%9D;%EB%9F%B0%ED%83%80%EC%9E%84+%EC%84%B8%EA%B8%88+%EC%A0%9C%EB%A1%9C%2C+%EC%9E%91%EA%B3%A0+%EB%82%A0%EC%B9%B4%EB%A1%9C%EC%9A%B4+%EB%8F%84%EA%B5%AC;%EC%95%95%EB%8F%84%EC%A0%81%EC%9D%B8+%EC%86%8D%EB%8F%84%EC%99%80+%EC%B5%9C%EC%A0%81%ED%99%94." alt="typing"/>
</a>

</div>

---

### 👋 반가워요!

Rust로 **가볍고 번개처럼 빠른 네이티브 시스템 도구**를 개발하고, 컴파일된 바이너리와 저수준 아키텍처를 깊이 있게 파고드는 엔지니어입니다.

불필요하게 무거운 런타임이나 작은 바이너리 하나 열어보려고 15초씩 기다리는 비효율을 지양합니다. 1밀리초 안에 가볍게 끝낼 수 있다면 본질적인 속도와 성능에 집중하여 그렇게 빌드되어야 한다고 생각합니다.

---

### 🚀 주력 프로젝트: [`binvibe`](https://github.com/GHSFS/binvibe) *(Flagship)*

> **초고속 네이티브 바이너리 리버스 엔지니어링 MCP 서버 & 실전 실용주의 플러그인**  
> *100% Rust로 정밀하게 설계되어 나노초 단위 역어셈블리와 개발자 페어링을 지원합니다.*

[![CI](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml)
[![Mirror Sync](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml)
[![License: MIT OR Apache-2.0](https://img.shields.io/badge/License-MIT%20OR%20Apache--2.0-blue.svg)](https://github.com/GHSFS/binvibe/blob/main/LICENSE-MIT)

- **문제의식**: 기존의 무거운 리버스 엔지니어링 도구들(Ghidra, IDA Pro 등)은 콜드 스타트가 너무 길고, 메모리를 과도하게 점유하며, 코드 분석 흐름을 불필요하게 끊는 한계가 있었습니다.
- **해결 방식**: `binvibe`는 1ms 미만으로 즉각 기동하며, `iced-x86`을 통해 나노초 단위 기계어 디코딩을 수행하고, `goblin` 제로 카피 메모리 맵 기반 PE/ELF/Mach-O 파싱과 경량 Micro-IR 의사코드(Pseudo-C)를 복원합니다.
- **네이티브 멀티 플랫폼**: 무거운 VM이나 외부 런타임 종속성 없이 Windows, Linux, macOS에서 즉시 단일 독립 바이너리로 구동됩니다.
- **AI 페어 프로그래밍 연동 (MCP)**: Model Context Protocol (MCP) 표준 인터페이스를 구현하여 코딩 흐름 안에서 필요한 핵심 어셈블리 및 함수 제어 흐름 컨텍스트를 토큰 효율적으로 직통 제공합니다.

👉 **저장소**: [github.com/GHSFS/binvibe](https://github.com/GHSFS/binvibe)

---

### ⚙️ 엔지니어링 원칙

- **속도와 미니멀리즘**: 불필요한 런타임 오버헤드와 메모리 낭비를 철저히 배제하고 본질적인 속도에 집중합니다.
- **네이티브 우선**: 인터프리터나 가상 머신에 의존하지 않는 단일 독립 실행형 바이너리를 지향합니다.
- **실전 실용주의**: 탁상공론식 복잡함을 배제하고, 현업의 기술적 문제를 가장 직접적이고 정밀하게 해결합니다.
- **다중 플랫폼 미러링**: 핵심 프로젝트는 GitHub뿐만 아니라 GitLab, Hugging Face로 실시간 동기화됩니다.

---

### 📦 제작한 다른 프로젝트들

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
<summary><b>📦 Windows 데스크톱 워크플로 도구</b> (클릭하여 펼치기)</summary>
<br/>

> **클립보드 감지 → 트레이 상주 → 원격 다운로더 → 토스트 알림**으로 이어지는 직관적인 Windows 도구군.

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
요청된 URL의 컨텐츠를 목적지 클라우드로 안전하게 릴레이하는 경량 원격 다운로더.

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Windows 시스템 트레이 상주 유틸리티. 클립보드 URL을 실시간 감지하여 자동 큐 등록 및 네이티브 토스트 알림.

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Windows 탐색기 우클릭 컨텍스트 메뉴 확장. 파일이나 링크를 원클릭으로 즉각 큐에 전송.

</td>
</tr>
</table>
</details>

<details>
<summary><b>🤖 서버리스 & 엣지 봇</b> (클릭하여 펼치기)</summary>
<br/>

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Cloudflare Workers에서 구동되는 서버리스 텔레그램 봇. 사용자 질의 복잡도를 분석하여 경량 고속 모델과 심층 추론 모델 사이에서 동적으로 최적 라우팅을 수행합니다.

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
        "TypeScript & Cloudflare Workers Edge",
    ]
}
```

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1f1f1f?style=for-the-badge&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/Win32-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</div>

---

### 🌐 다중 플랫폼 미러

모든 주요 도구는 오픈 생태계 전반에 실시간 동기화됩니다:

- **GitHub**: [github.com/GHSFS](https://github.com/GHSFS) *(메인 소스)*
- **GitLab**: [gitlab.com/users/ghsfs_4c1f7f/projects](https://gitlab.com/users/ghsfs_4c1f7f/projects)
- **Hugging Face**: [huggingface.co/ghsfs-dev](https://huggingface.co/ghsfs-dev)

---

<div align="center">

<sub>⚡ <i>"작고 날카로운 바이너리, 그리고 런타임 세금 제로."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
