<div align="center">

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>

---

### 👋 about

```rust
struct Dev {
    handle: &'static str,
    focus:  [&'static str; 4],
    stack:  &'static str,
    motto:  &'static str,
}

const ME: Dev = Dev {
    handle: "GHSFS",
    focus:  [
        "Rust",
        "Windows desktop tooling",
        "GitHub Actions automation",
        "Cloudflare Workers edge bots",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "small binaries, sharp edges, no runtime tax.",
};
```

---

### 🛠 stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1f1f1f?style=for-the-badge&logo=rust&logoColor=ff7043)
![WinAPI](https://img.shields.io/badge/Win32-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

</div>

---

### 📦 the rdl ecosystem

> 세 개의 작은 도구가 하나의 흐름을 만듭니다 — **클립보드 → 트레이 → 원격 다운로더 → 알림.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
GitHub Actions 기반 원격 다운로더.<br/>
URL 하나 던지면 러너가 받아 클라우드로 직송·보관.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
시스템 트레이 컴패니언.<br/>
클립보드 URL을 감시 → 토스트 알림 및 즉시 큐 등록.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
탐색기 컨텍스트 메뉴 확장.<br/>
`.url` 파일 우클릭 → "Send to remote-dl".

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-shell/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-shell/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🔐 security, forensics & steganography

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
무손실 PNG/WAV/BMP 스테가노그래피와 이중 하드웨어 바인딩(`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`)을 결합한 제로 트러스트 암호화 금고(`svault`).<br/>
듀레스 디코이 볼륨, Shamir 비밀 분산(`GF(2^8)`), Reed-Solomon 자가 치유, TOTP 및 원자적 패스프레이즈 로테이션 지원.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
제로 디펜던시 바이너리 포렌식 및 정적 분석·패치 엔진(`bsentinel`).<br/>
PE32/PE32+, ELF64, Mach-O/Universal 헤더 파싱, 패커 엔트로피/S-Box 탐지, x86_64 프롤로그 디스어셈블리, Authenticode 서명 검증 및 선언적 바이너리 디프/패치 레시피 지원.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
제로 디펜던시 네트워크 패킷 포렌식 및 암호화 트래픽 지문 분석기(`nspecter`).<br/>
PCAP/PCAPNG 디코딩, TCP 스트림 재조립, TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H` 지문 추출, QUIC Initial(RFC 9001) 복호화, DNS 터널링·C2 비콘 지터 스펙트로그램 탐지 및 BPF 필터 엔진 탑재.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
IoT 및 임베디드 펌웨어 언패커·매직 스트림 카버 및 정적 취약점 감사 엔진(`fcarver`).<br/>
U-Boot/TRX/FDT 컨테이너 분석, SquashFS v4 트리 추출, 엔트로피 기반 파티션 슬라이싱, 다중 아키텍처(MIPS/ARM/RISC-V) 셸코드·CGI 명령 주입·하드코딩 인증서 감사 지원.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

---

### 🤖 serverless & edge tooling

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
텔레그램 메시지를 길이에 따라 고속 추론 및 심층 추론 엔드포인트로 자동 라우팅하는 서버리스 봇.<br/>
Cloudflare Workers Free 티어에서 동작하며 Workers KV에 대화 컨텍스트와 모델 설정을 유지합니다.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/llm-router-bot/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/llm-router-bot/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🧭 philosophy

```text
┌─────────────────────────────────────────────────────────┐
│  · ship small binaries — every MB has to earn its keep  │
│  · async by default — block nothing, await everything   │
│  · no runtime tax — if it can be const, it should be    │
│  · Windows-first — the desktop deserves nice tools too  │
└─────────────────────────────────────────────────────────┘
```

---

<div align="center">

<sub>⚡ <i>"the best code is the code you don't have to maintain — so write less of it, and write it in Rust."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
