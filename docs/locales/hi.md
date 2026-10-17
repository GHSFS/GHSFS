<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <strong>🇮🇳 हिन्दी</strong><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>

---

### 👋 परिचय

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
        "Windows डेस्कटॉप टूल्स",
        "GitHub Actions ऑटोमेशन",
        "Cloudflare Workers एज बॉट्स",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "छोटे बाइनरी, तेज़ प्रदर्शन, शून्य रनटाइम टैक्स।",
};
```

---

### 🛠 टेक स्टैक

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

### 📦 rdl इकोसिस्टम

> तीन छोटे उपकरण जो एक सहज प्रवाह का निर्माण करते हैं — **क्लिपबोर्ड → सिस्टम ट्रे → रिमोट डाउनलोडर → नोटिफिकेशन।**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
GitHub Actions-संचालित रिमोट डाउनलोडर।<br/>
एक URL सबमिट करें, रनर इसे फ़ेच करके सीधे क्लाउड स्टोरेज में रिले करता है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
सिस्टम ट्रे साथी उपकरण।<br/>
क्लिपबोर्ड URL की निगरानी करता है → टोस्ट अलर्ट और तत्काल कतार पंजीकरण ट्रिगर करता है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Windows Explorer संदर्भ मेनू एक्सटेंशन।<br/>
किसी भी `.url` फ़ाइल पर राइट-क्लिक करें → "Send to remote-dl"।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-shell/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-shell/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🔐 सुरक्षा, फोरेंसिक्स और स्टेग्नोग्राफी

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
शून्य-विश्वास एन्क्रिप्टेड वॉल्ट (`svault`) जो दोषरहित PNG/WAV/BMP/MP3 स्टेग्नोग्राफी को दोहरे हार्डवेयर बाइंडिंग (`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`) के साथ जोड़ता है।<br/>
दबाव प्रलोभन वॉल्यूम, शमीर सीक्रेट शेयरिंग (`GF(2^8)`), रीड-सोलोमन सेल्फ-हीलिंग, TOTP और परमाणु पासफ़्रेज़ रोटेशन का समर्थन करता है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
शून्य-निर्भरता बाइनरी फोरेंसिक्स, स्थिर निरीक्षण और बाइट-पैचिंग इंजन (`bsentinel`)।<br/>
PE32/PE32+, ELF64, Mach-O/Universal हेडर का विश्लेषण करता है, पैकर एन्ट्रॉपी और क्रिप्टो स्थिरांक का पता लगाता है, x86_64 प्रोलॉग को डिसअसेंबल करता है, Authenticode हस्ताक्षर सत्यापित करता है और घोषणात्मक पैच रेसिपी बनाता है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
शून्य-निर्भरता नेटवर्क पैकेट फोरेंसिक्स और एन्क्रिप्टेड ट्रैफ़िक फ़िंगरप्रिंटिंग इंजन (`nspecter`)।<br/>
PCAP/PCAPNG को डिकोड करता है, TCP स्ट्रीम को फिर से जोड़ता है, TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H` फ़िंगरप्रिंट निकालता है, QUIC Initial (RFC 9001) को डिक्रिप्ट करता है, DNS टनलिंग/C2 जिटर स्पेक्ट्रोग्राम का पता लगाता है और इसमें BPF फ़िल्टर इंजन शामिल है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
IoT और एम्बेडेड फ़र्मवेयर अनपैकर, मैजिक स्ट्रीम कार्वर और स्थिर भेद्यता ऑडिटर (`fcarver`)।<br/>
U-Boot/TRX/FDT कंटेनरों का विश्लेषण करता है, SquashFS v4 ट्री निकालता है, एन्ट्रॉपी मैपिंग के माध्यम से विभाजन को स्लाइस करता है और मल्टी-आर्क (MIPS/ARM/RISC-V) शेलकोड, CGI कमांड इंजेक्शन और हार्डकोडेड प्रमाणपत्रों का ऑडिट करता है।

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

---

### 🤖 सर्वरलेस और एज टूल्स

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
सर्वरलेस बॉट जो प्रॉम्प्ट की जटिलता के आधार पर टेलीग्राम संदेशों को तेज़-अनुमान या गहन-तर्क एंडपॉइंट्स पर स्वचालित रूप से रूट करता है।<br/>
Cloudflare Workers मुफ़्त टियर पर चलता है और Workers KV में वार्तालाप संदर्भ और मॉडल कॉन्फ़िगरेशन बनाए रखता है।

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/llm-router-bot/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/llm-router-bot/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🧭 दर्शन

```text
┌─────────────────────────────────────────────────────────┐
│  · छोटे बाइनरी शिप करें — हर MB को अपनी उपयोगिता साबित करनी होगी│
│  · डिफ़ॉल्ट रूप से एसिंक्रोनस — कुछ भी ब्लॉक न करें, सब कुछ अवेट करें│
│  · शून्य रनटाइम टैक्स — यदि इसे const बनाया जा सकता है, तो बनाएं│
│  · Windows प्राथमिकता — डेस्कटॉप भी बेहतरीन टूल्स का हकदार है│
└─────────────────────────────────────────────────────────┘
```

---

<div align="center">

<sub>⚡ <i>"सबसे अच्छा कोड वह है जिसे आपको बनाए रखने की आवश्यकता नहीं है — इसलिए कम कोड लिखें, और इसे Rust में लिखें।"</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
