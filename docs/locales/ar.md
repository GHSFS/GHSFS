<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <strong>🇸🇦 العربية</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>

---

### 👋 نبذة عني

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
        "أدوات سطح مكتب Windows",
        "أتمتة سير العمل بـ GitHub Actions",
        "بوتات الحافة على Cloudflare Workers",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "ملفات ثنائية صغيرة، أداء فائق، دون أي عبء تشغيلي إضافي.",
};
```

---

### 🛠 الحزمة التقنية

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

### 📦 منظومة rdl

> ثلاث أدوات دقيقة تُشكّل تدفق عمل سلس — **الحافظة → علبة النظام → أداة التنزيل عن بُعد → الإشعارات.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
أداة تنزيل عن بُعد مدعومة بـ GitHub Actions.<br/>
أرسل رابطًا، وسيقوم المشغّل بجلبه وإعادة توجيهه مباشرة إلى التخزين السحابي.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
رفيق علبة النظام.<br/>
يراقب الروابط في الحافظة → يُطلق تنبيهات Toast ويسجلها فورًا في قائمة الانتظار.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
امتداد لقائمة السياق في مستكشف Windows.<br/>
انقر بزر الماوس الأيمن على أي ملف `.url` → "Send to remote-dl".

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![COM](https://img.shields.io/badge/-COM-512BD4?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-shell/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-shell/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-shell/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🔐 الأمان، التحليل الجنائي وإخفاء البيانات (Steganography)

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
خزينة مشفرة قائمة على مبدأ انعدام الثقة (`svault`) تجمع بين إخفاء البيانات بدون فقدان PNG/WAV/BMP/MP3 والربط المزدوج بالأجهزة (`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`).<br/>
تدعم أحجام الإكراه التمويهية، ومشاركة أسرار شامير (`GF(2^8)`)، والمعالجة الذاتية بتقنية ريد-سولومون، وتطبيق رموز TOTP وتدوير كلمات المرور الذري.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
محرك لفحص وتعديل البايتات والتحليل الجنائي للملفات الثنائية بدون أي اعتماديات خارجية (`bsentinel`).<br/>
يحلل ترويسات PE32/PE32+ وELF64 وMach-O/Universal، ويكتشف إنتروبيا أدوات الحزم والثوابت المشفرة، ويفكك استهلالات دالات x86_64، ويتحقق من تواقيع Authenticode، ويصنع وصفات تصحيح ثنائية معلنة.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
محرك للتحليل الجنائي لحزم الشبكة وبصمات حركة المرور المشفرة بدون اعتماديات (`nspecter`).<br/>
يفك ترميز PCAP/PCAPNG، ويعيد تجميع تدفقات TCP، ويستخرج بصمات TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H`، ويفك تشفير حزم QUIC Initial (RFC 9001)، ويكتشف أنفاق DNS ومخططات تقلب اتصالات C2 الطيفية، ويحتوي على محرك تصفية BPF.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
أداة استخراج البرامج الثابتة المدمجة وIoT واستخلاص التدفقات وتدقيق الثغرات البرمجية الثابتة (`fcarver`).<br/>
يحلل حاويات U-Boot/TRX/FDT، ويستخرج شجرة SquashFS v4، ويقسم الأقسام بناءً على خرائط الإنتروبيا، ويدقق في شفرات الحقن (Shellcode) متعددة المعماريات (MIPS/ARM/RISC-V) وحقن أوامر CGI والشهادات المضمنة.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

---

### 🤖 أدوات الحافة والحوسبة بدون خادم

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
بوت يعمل بدون خادم يوجه رسائل Telegram تلقائيًا إلى نقاط نهاية الاستدلال السريع أو التفكير العميق بناءً على تعقيد الطلب.<br/>
يعمل على الفئة المجانية من Cloudflare Workers ويحتفظ بسياق المحادثة وتكوينات النماذج في Workers KV.

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/-Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/llm-router-bot/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/llm-router-bot/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/llm-router-bot/actions/workflows/test.yml)

</td>
</tr>
</table>

---

### 🧭 الفلسفة البرمجية

```text
┌─────────────────────────────────────────────────────────┐
│  · نشر ملفات ثنائية صغيرة — كل ميغابايت يجب أن يثبت جدواه │
│  · غير متزامن افتراضيًا — لا تحظر أي عملية، استخدم await  │
│  · صفر عبء تشغيلي — ما يمكن جعله const يجب أن يكون const│
│  · Windows أولاً — بيئة سطح المكتب تستحق أدوات استثنائية │
└─────────────────────────────────────────────────────────┘
```

---

<div align="center">

<sub>⚡ <i>"أفضل كود برمجي هو الكود الذي لا تحتاج إلى صيانته — لذا اكتب كودًا أقل، واكتبه بـ Rust."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
