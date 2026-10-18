<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/pt-BR.md">🇧🇷 Português</a> · <strong>🇷🇺 Русский</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>


---


### 👋 обо мне

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
        "Инструменты для рабочего стола Windows",
        "Автоматизация GitHub Actions",
        "Edge-боты на Cloudflare Workers",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "компактные бинарники, максимальная острота, нулевой оверхед рантайма.",
};
```


---

<details>
<summary><h3>🛠 стек технологий</h3></summary>
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
<summary><h3>📦 экосистема rdl</h3></summary>
<br/>

> Три небольших инструмента, создающих единый рабочий процесс — **Буфер обмена → Системный трей → Удаленный загрузчик → Уведомление.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
Удаленный загрузчик на базе GitHub Actions.<br/>
Передайте URL, и раннер скачает и перенаправит файл напрямую в облачное хранилище.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Компаньон для системного трея.<br/>
Отслеживает URL-адреса в буфере обмена → вызывает всплывающие уведомления и мгновенно ставит в очередь.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Расширение контекстного меню Проводника Windows.<br/>
Кликните правой кнопкой мыши по любому файлу `.url` → "Send to remote-dl".

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
<summary><h3>🔐 безопасность, форензика и стеганография</h3></summary>
<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
Зашифрованное хранилище с нулевым доверием (`svault`), объединяющее стеганографию без потерь в PNG/WAV/BMP/MP3 с двойной аппаратной привязкой (`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`).<br/>
Поддерживает тома-приманки под принуждением, разделение секрета Шамира (`GF(2^8)`), самовосстановление Рида-Соломона, TOTP и атомарную ротацию парольных фраз.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
Движок бинарной форензики, статического анализа и байт-патчинга без зависимостей (`bsentinel`).<br/>
Разбирает заголовки PE32/PE32+, ELF64, Mach-O/Universal, определяет энтропию упаковщиков и криптоконстанты, дизассемблирует прологи x86_64, проверяет подписи Authenticode и создает декларативные патч-рецепты.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
Движок форензики сетевых пакетов и анализа фингерпринтов зашифрованного трафика без зависимостей (`nspecter`).<br/>
Декодирует PCAP/PCAPNG, выполняет реассемблинг TCP-потоков, извлекает TLS-отпечатки `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H`, расшифровывает QUIC Initial (RFC 9001), обнаруживает DNS-туннелирование и спектрограммы джиттера C2, оснащен фильтром BPF.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
Инструмент распаковки прошивок IoT/встроенных систем, карвинга потоков и статического аудита уязвимостей (`fcarver`).<br/>
Анализирует контейнеры U-Boot/TRX/FDT, извлекает деревья SquashFS v4, разбивает разделы по карте энтропии и проверяет мультиархитектурный (MIPS/ARM/RISC-V) шеллкод, CGI-инъекции команд и хардкод-сертификаты.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

</details>

---

<details>
<summary><h3>🤖 бессерверные и edge-инструменты</h3></summary>
<br/>

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Бессерверный бот, автоматически маршрутизирующий сообщения Telegram на эндпоинты быстрого инференса или глубокого рассуждения в зависимости от сложности запроса.<br/>
Работает на бесплатном тарифе Cloudflare Workers и сохраняет контекст диалога и конфигурации моделей в Workers KV.

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
<summary><h3>🧭 философия</h3></summary>
<br/>

```text
┌─────────────────────────────────────────────────────────┐
│  · компактные бинарники — каждый МБ должен оправдывать себя │
│  · асинхронность по умолчанию — ничего не блокировать, всё await │
│  · нулевой оверхед — если можно сделать const, делайте const │
│  · Windows в приоритете — десктоп заслуживает отличных инструментов │
└─────────────────────────────────────────────────────────┘
```

</details>

---


<div align="center">

<sub>⚡ <i>"лучший код — тот, который не нужно поддерживать; пишите меньше кода и пишите его на Rust."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
