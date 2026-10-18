<div align="center">

<p align="center">
  <strong>🇺🇸 English</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=FF7043&center=true&vCenter=true&width=620&lines=hey%2C+I'm+GHSFS;crafting+fast+native+tools+in+Rust;automating+the+boring+stuff;zero+runtime+tax%2C+small+binaries." alt="typing"/>
</a>

</div>

---

### 👋 Hey there!

I'm a systems developer and tooling tinkerer focused on writing **blazingly fast native software in Rust**, dissecting compiled binaries, and building **hands-off CI/CD automation pipelines**.

I don't like slow tools, bloated runtimes, or waiting 15 seconds for a heavy JVM just to inspect a 20KB executable. If something can run in 1 millisecond with zero memory overhead, that's how it should be built.

---

### 🚀 Currently Building: [`binvibe`](https://github.com/GHSFS/binvibe) *(Flagship)*

> **Ultra-fast native binary reverse engineering MCP server & pragmatic intent plugin.**  
> *Built 100% in Rust, wired directly to AI coding agents via MCP.*

[![CI](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/ci.yml)
[![Mirror Sync](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml/badge.svg)](https://github.com/GHSFS/binvibe/actions/workflows/mirror.yml)
[![License: MIT OR Apache-2.0](https://img.shields.io/badge/License-MIT%20OR%20Apache--2.0-blue.svg)](https://github.com/GHSFS/binvibe/blob/main/LICENSE-MIT)

- **The Problem**: Existing RE tools (Ghidra, IDA Pro, heavy wrappers) are slow to launch, consume gigabytes of RAM, or hit defensive AI refusals when you just want to analyze assembly logic.
- **The Solution**: `binvibe` boots in under 1ms, decodes instructions at nanosecond speed using `iced-x86`, parses PE/ELF/Mach-O via zero-copy memory maps (`goblin`), and reconstructs high-level pseudo-C logic.
- **Automated Development Pipeline**: Developed with continuous automation — all builds, tests on Linux/macOS/Windows, and cross-platform mirror syncs (GitLab, Gitea, Hugging Face) run seamlessly in GitHub Actions without manual friction.

👉 **Check it out**: [github.com/GHSFS/binvibe](https://github.com/GHSFS/binvibe)

---

### ⚙️ How I Build Things

- **Ship small & fast**: Every byte counts. Unstripped 500MB binaries for simple CLI tools make no sense.
- **Automate everything**: If I have to do something twice, it becomes a GitHub Action or a background bot.
- **Pragmatic engineering**: Real engineering is about finding working solutions, not getting trapped in dogmatic rules or defensive roadblocks.
- **Multi-platform redundancy**: My core repos are mirrored automatically across GitHub, GitLab, Gitea, and Hugging Face.

---

### 📦 Other Projects I've Built

<details open>
<summary><b>🛡️ Binary Forensics, Security & Steganography</b> (Click to collapse)</summary>
<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
Zero-trust encrypted vault (`svault`) combining lossless PNG/WAV/BMP/MP3 steganography with dual hardware binding (`Argon2id` + `ChaCha20-Poly1305` + Windows `DPAPI`).<br/>
Features duress decoy volumes, Shamir secret sharing, Reed-Solomon self-healing, and TOTP.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
Zero-dependency binary forensics & static inspection engine (`bsentinel`).<br/>
Parses PE32/PE64, ELF64, Mach-O, analyzes packer entropy, checks Authenticode certificates, and generates declarative patch rules.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
Zero-dependency network packet forensics and traffic fingerprinting (`nspecter`).<br/>
PCAP/PCAPNG parser, TCP stream reassembler, TLS JA3/JA4 fingerprint extractor, and QUIC decryptor.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
IoT & embedded firmware unpacker and vulnerability auditor (`fcarver`).<br/>
Carves SquashFS v4, U-Boot, and TRX containers, slices partitions via entropy mapping, and analyzes multi-arch shellcode.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)

</td>
</tr>
</table>
</details>

<details>
<summary><b>📦 The RDL Workflow Tools (Windows Desktop)</b> (Click to expand)</summary>
<br/>

> Three modular desktop tools composing a streamlined flow: **Clipboard → System Tray → Remote Downloader → Toast Alert.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
GitHub Actions-powered remote downloader. Send a URL, and the runner fetches and relays it directly to your target cloud storage.

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Lightweight Windows system tray companion. Monitors clipboard for target URLs and triggers automatic queueing with native toast notifications.

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Windows Explorer context menu shell extension. Right-click any link or file to dispatch instantly.

</td>
</tr>
</table>
</details>

<details>
<summary><b>🤖 Serverless & Edge Bots</b> (Click to expand)</summary>
<br/>

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Serverless Telegram bot running on Cloudflare Workers Free tier that routes incoming prompts between lightweight fast-inference and deep-reasoning AI models based on prompt complexity, maintaining conversation memory in Workers KV.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)

</details>

---

### 🛠 Tech Toolbox

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

### 🌐 Multi-Platform Mirrors

All my major tools are replicated across open ecosystems:

- **GitHub**: [github.com/GHSFS](https://github.com/GHSFS) *(Primary source)*
- **GitLab**: [gitlab.com/ghsfs_4c1f7f](https://gitlab.com/ghsfs_4c1f7f)
- **Gitea**: [gitea.com/GHSFS](https://gitea.com/GHSFS)
- **Hugging Face**: [huggingface.co/ghsfs-dev](https://huggingface.co/ghsfs-dev)

---

<div align="center">

<sub>⚡ <i>"The best code is small, fast, and tested in CI before you even step away from the keyboard."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
