<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <strong>🇮🇩 Bahasa Indonesia</strong>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>

---

### 👋 tentang saya

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
        "Perangkat desktop Windows",
        "Otomatisasi GitHub Actions",
        "Bot edge Cloudflare Workers",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "biner kecil, performa tajam, tanpa beban runtime.",
};
```

---

### 🛠 teknologi

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

### 📦 ekosistem rdl

> Tiga alat kecil yang menyusun satu alur kerja mulus — **Papan klip → Baki sistem → Pengunduh jarak jauh → Notifikasi.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
Pengunduh jarak jauh bertenaga GitHub Actions.<br/>
Kirimkan URL, runner akan mengambil dan meneruskannya langsung ke penyimpanan cloud.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Pendamping baki sistem.<br/>
Memantau URL di papan klip → memicu peringatan toast dan pendaftaran antrean instan.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Ekstensi menu konteks Windows Explorer.<br/>
Klik kanan file `.url` apa pun → "Send to remote-dl".

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-shell/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-shell/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🔐 keamanan, forensik & steganografi

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
Brankas terenkripsi zero-trust (`svault`) yang menggabungkan steganografi lossless PNG/WAV/BMP/MP3 dengan pengikatan perangkat keras ganda (`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`).<br/>
Mendukung volume umpan paksaan, pembagian rahasia Shamir (`GF(2^8)`), pemulihan mandiri Reed-Solomon, TOTP, dan rotasi frasa sandi atomik.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
Mesin forensik biner, inspeksi statis, dan penambalan byte tanpa dependensi (`bsentinel`).<br/>
Mem-parsing header PE32/PE32+, ELF64, Mach-O/Universal, mendeteksi entropi packer & konstanta kripto, membongkar prolog x86_64, memvalidasi tanda tangan Authenticode, dan membuat resep patch deklaratif.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
Mesin forensik paket jaringan dan sidik jari lalu lintas terenkripsi tanpa dependensi (`nspecter`).<br/>
Mendekode PCAP/PCAPNG, merakit ulang aliran TCP, mengekstrak sidik jari TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H`, mendekripsi QUIC Initial (RFC 9001), mendeteksi tunneling DNS dan spektrogram jitter C2, serta dilengkapi mesin filter BPF.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
Pembongkar firmware IoT & tertanam, pemahat aliran ajaib, dan auditor kerentanan statis (`fcarver`).<br/>
Menganalisis kontainer U-Boot/TRX/FDT, mengekstrak pohon SquashFS v4, memotong partisi melalui pemetaan entropi, dan mengaudit shellcode multi-arsitektur (MIPS/ARM/RISC-V), injeksi perintah CGI, serta sertifikat hardcode.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

---

### 🤖 alat serverless & edge

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Bot serverless yang merutekan pesan Telegram secara otomatis ke endpoint inferensi cepat atau penalaran mendalam berdasarkan kompleksitas prompt.<br/>
Berjalan di tingkat gratis Cloudflare Workers dan mempertahankan konteks percakapan serta konfigurasi model di Workers KV.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/llm-router-bot/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/llm-router-bot/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🧭 filosofi

```text
┌─────────────────────────────────────────────────────────┐
│  · rilis biner kecil — setiap MB harus membuktikan nilainya│
│  · asinkron secara bawaan — jangan blokir apa pun, await segalanya│
│  · tanpa beban runtime — jika bisa const, harus const    │
│  · Windows utama — desktop juga berhak mendapatkan alat hebat│
└─────────────────────────────────────────────────────────┘
```

---

<div align="center">

<sub>⚡ <i>"kode terbaik adalah kode yang tidak perlu Anda pelihara — jadi tulislah lebih sedikit kode, dan tulislah dalam Rust."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
