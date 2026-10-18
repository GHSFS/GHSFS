<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <strong>🇨🇳 中文</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>


---


### 👋 关于

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
        "Windows 桌面工具",
        "GitHub Actions 自动化",
        "Cloudflare Workers 边缘机器人",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "微型二进制，极致锐利，零运行时税。",
};
```


---

<details>
<summary><h3>🛠 技术栈</h3></summary>
<br/>

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

</details>

---

<details open>
<summary><h3>📦 rdl 生态系统</h3></summary>
<br/>

> 三个精巧的工具构成一个无缝工作流 — **剪贴板 → 系统托盘 → 远程下载器 → 消息通知。**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
基于 GitHub Actions 的远程下载器。<br/>
只需提交一个 URL，Runner 自动拉取并直接转存至云端存储。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
系统托盘伴侣工具。<br/>
实时监听剪贴板 URL → 触发 Toast 提示通知并即时加入下载队列。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Windows 资源管理器右键上下文菜单扩展。<br/>
右键点击任意 `.url` 文件 → “Send to remote-dl”。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-shell/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-shell/actions/workflows/test.yml)

</td>
</tr>
</table>

</details>

---

<details open>
<summary><h3>🔐 安全、取证与隐写术</h3></summary>
<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
结合无损 PNG/WAV/BMP/MP3 隐写术与双重硬件绑定的零信任加密金库（`svault`）（`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`）。<br/>
支持胁迫诱饵卷、Shamir 门限秘密共享（`GF(2^8)`）、Reed-Solomon 自愈纠错、TOTP 以及原子化口令轮换。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
零依赖二进制取证、静态分析与字节补丁引擎（`bsentinel`）。<br/>
解析 PE32/PE32+、ELF64、Mach-O/Universal 头部，检测加壳熵值与加密常量，反汇编 x86_64 函数序言，验证 Authenticode 签名，并生成声明式二进制补丁配方。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
零依赖网络数据包取证与加密流量指纹分析引擎（`nspecter`）。<br/>
解码 PCAP/PCAPNG，重组 TCP 流，提取 TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H` 指纹，解密 QUIC Initial (RFC 9001)，检测 DNS 隧道与 C2 抖动频谱图，内置 BPF 过滤引擎。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
IoT 与嵌入式固件解包、魔数流提取与静态漏洞审计工具（`fcarver`）。<br/>
分析 U-Boot/TRX/FDT 容器，提取 SquashFS v4 目录树，基于熵值映射分割分区，审计多架构（MIPS/ARM/RISC-V）Shellcode、CGI 命令注入与硬编码证书。

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

</details>

---

<details>
<summary><h3>🤖 无服务器与边缘工具</h3></summary>
<br/>

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
基于 Cloudflare Workers 的无服务器机器人，根据提示词复杂度将 Telegram 消息自动路由至快速推理或深度推理端点。<br/>
运行于 Cloudflare Workers 免费层，并在 Workers KV 中持久化保存对话上下文与模型配置。

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/llm-router-bot/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/llm-router-bot/actions/workflows/test.yml)

</td>
</tr>
</table>

</details>

---

<details>
<summary><h3>🧭 核心哲学</h3></summary>
<br/>

```text
┌─────────────────────────────────────────────────────────┐
│  · 发布微型二进制 — 每个 MB 都必须证明其存在的价值     │
│  · 默认纯异步 — 不阻塞任何线程，全面 await             │
│  · 零运行时税 — 凡是能做成 const 的，坚决 const 化      │
│  · Windows 优先 — 桌面端同样配得上优雅好用的工具       │
└─────────────────────────────────────────────────────────┘
```

</details>

---


<div align="center">

<sub>⚡ <i>"最好的代码是根本无需维护的代码 — 少写代码，多用 Rust。"</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
