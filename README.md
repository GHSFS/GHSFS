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
    focus:  [&'static str; 3],
    stack:  &'static str,
    motto:  &'static str,
}

const ME: Dev = Dev {
    handle: "GHSFS",
    focus:  ["Rust", "Windows desktop tooling", "GitHub Actions automation"],
    stack:  "Rust + Tokio + WinAPI + a sprinkle of YAML",
    motto:  "small binaries, sharp edges, no runtime tax.",
};
```

---

### 🛠 stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1f1f1f?style=for-the-badge&logo=rust&logoColor=ff7043)
![WinAPI](https://img.shields.io/badge/Win32-0078D6?style=for-the-badge&logo=windows&logoColor=white)
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
URL 하나 던지면 러너가 받아 보관·전달.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
시스템 트레이 컴패니언.<br/>
클립보드 URL을 감시 → 토스트 알림.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
탐색기 컨텍스트 메뉴 확장.<br/>
.url 파일 우클릭 → "Send to remote-dl".

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)

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

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff7043,100:1f1f1f&height=120&section=footer" width="100%" alt="footer"/>

</div>
