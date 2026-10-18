<div align="center">

<p align="center">
  <a href="https://github.com/GHSFS/GHSFS/blob/main/README.md">🇺🇸 English</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ko.md">🇰🇷 한국어</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/zh-CN.md">🇨🇳 中文</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/es.md">🇪🇸 Español</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/hi.md">🇮🇳 हिन्दी</a><br />
  <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ar.md">🇸🇦 العربية</a> · <strong>🇧🇷 Português</strong> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/ru.md">🇷🇺 Русский</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/fr.md">🇫🇷 Français</a> · <a href="https://github.com/GHSFS/GHSFS/blob/main/docs/locales/id.md">🇮🇩 Bahasa Indonesia</a>
</p>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/banner.svg" width="100%" alt="GHSFS — building small, sharp tools in Rust"/>

<br/>

<a href="https://github.com/GHSFS">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=FF7043&center=true&vCenter=true&width=620&lines=cargo+build+--release;async%2C+zero-cost%2C+memory-safe;Windows+desktop+%E2%9D%A4+Rust;ship+small%2C+ship+often." alt="typing"/>
</a>

</div>


---


### 👋 sobre mim

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
        "Ferramentas de desktop para Windows",
        "Automação com GitHub Actions",
        "Bots de borda no Cloudflare Workers",
    ],
    stack:  "Rust + Tokio + WinAPI + TypeScript + Cloudflare Workers",
    motto:  "binários pequenos, bordas afiadas, custo de execução zero.",
};
```


---

<details>
<summary><h3>🛠 tecnologias</h3></summary>
<br/>

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-1f1f1f?style=for-the-badge&logo=rust&logoColor=ff7043)
![WinAPI](https://img.shields.io/badgeWin32-0078D6?style=for-the-badge&logo=windows&logoColor=white)
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
<summary><h3>📦 o ecossistema rdl</h3></summary>
<br/>

> Três pequenas ferramentas compondo um fluxo contínuo — **Área de transferência → Bandeja do sistema → Baixador remoto → Notificação.**

<table>
<tr>
<td width="33%" valign="top">

#### 🧊 [`remote-dl`](https://github.com/GHSFS/remote-dl)
Baixador remoto impulsionado por GitHub Actions.<br/>
Envie uma URL, o executor baixa e transfere diretamente para o armazenamento em nuvem.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Actions](https://img.shields.io/badge/-Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/remote-dl/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/remote-dl/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/remote-dl/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 📋 [`rdl-tray`](https://github.com/GHSFS/rdl-tray)
Companheiro da bandeja do sistema.<br/>
Monitora URLs da área de transferência → dispara notificações toast e registro imediato na fila.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32](https://img.shields.io/badge/-Win32-0078D6?style=flat-square&logo=windows&logoColor=white)
[![Build](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/build.yml?branch=main&style=flat-square&label=build)](https://github.com/GHSFS/rdl-tray/actions/workflows/build.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/GHSFS/rdl-tray/test.yml?branch=main&style=flat-square&label=tests)](https://github.com/GHSFS/rdl-tray/actions/workflows/test.yml)

</td>
<td width="33%" valign="top">

#### 🐚 [`rdl-shell`](https://github.com/GHSFS/rdl-shell)
Extensão de menu de contexto do Windows Explorer.<br/>
Clique com o botão direito em qualquer arquivo `.url` → "Send to remote-dl".

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
<summary><h3>🔐 segurança, perícia forense e esteganografia</h3></summary>
<br/>

<table>
<tr>
<td width="50%" valign="top">

#### 🕵️ [`shadow-vault`](https://github.com/GHSFS/shadow-vault)
Cofre criptografado de confiança zero (`svault`) combinando esteganografia sem perdas em PNG/WAV/BMP/MP3 com vinculação dupla de hardware (`Argon2id` + `ChaCha20-Poly1305 AEAD` + Windows `DPAPI`).<br/>
Suporta volumes de coerção isca, compartilhamento secreto de Shamir (`GF(2^8)`), autocura Reed-Solomon, TOTP e rotação atômica de senha.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Win32 DPAPI](https://img.shields.io/badge/-DPAPI-0078D6?style=flat-square&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🧬 [`bin-sentinel`](https://github.com/GHSFS/bin-sentinel)
Motor de perícia binária, inspeção estática e patch de bytes sem dependências (`bsentinel`).<br/>
Analisa cabeçalhos PE32/PE32+, ELF64, Mach-O/Universal, detecta entropia de empacotadores e constantes criptográficas, descompila prólogos x86_64, valida assinaturas Authenticode e gera receitas declarativas de patch binário.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Forensics](https://img.shields.io/badge/-Binary%20Forensics-4B5563?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [`net-specter`](https://github.com/GHSFS/net-specter)
Motor de análise forense de pacotes de rede e identificação de tráfego criptografado sem dependências (`nspecter`).<br/>
Decodifica PCAP/PCAPNG, remonta fluxos TCP, extrai impressões digitais TLS `JA3`/`JA3S`/`JA4`/`JA4S`/`JA4H`, descriptografa QUIC Initial (RFC 9001), detecta tunelamento DNS e espectrogramas de jitter C2, e inclui um motor de filtro BPF.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Network](https://img.shields.io/badge/-Packet%20Forensics-0284C7?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
<td width="50%" valign="top">

#### 🔬 [`firm-carver`](https://github.com/GHSFS/firm-carver)
Descompactador de firmware embarcado/IoT, extrator de fluxos mágicos e auditor estático de vulnerabilidades (`fcarver`).<br/>
Analisa contêineres U-Boot/TRX/FDT, extrai árvores SquashFS v4, fatia partições via mapeamento de entropia e audita shellcodes multiarquitetura (MIPS/ARM/RISC-V), injeção de comandos CGI e certificados codificados.

![Rust](https://img.shields.io/badge/-Rust-000?style=flat-square&logo=rust&logoColor=ff7043)
![Firmware](https://img.shields.io/badge/-IoT%20Security-7C3AED?style=flat-square)
![License](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

</td>
</tr>
</table>

</details>

---

<details>
<summary><h3>🤖 ferramentas serverless e de borda</h3></summary>
<br/>

<table>
<tr>
<td width="100%" valign="top">

#### 🔀 [`llm-router-bot`](https://github.com/GHSFS/llm-router-bot)
Bot serverless que roteia automaticamente mensagens do Telegram para endpoints de inferência rápida ou raciocínio profundo com base na complexidade do prompt.<br/>
Executa no nível gratuito do Cloudflare Workers e mantém o contexto de conversas e configurações de modelos no Workers KV.

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
<summary><h3>🧭 filosofia</h3></summary>
<br/>

```text
┌─────────────────────────────────────────────────────────┐
│  · forneça binários pequenos — cada MB deve provar seu valor│
│  · assíncrono por padrão — não bloqueie nada, espere tudo│
│  · sem taxa de runtime — se pode ser const, deve ser    │
│  · Windows primeiro — o desktop merece ótimas ferramentas│
└─────────────────────────────────────────────────────────┘
```

</details>

---


<div align="center">

<sub>⚡ <i>"o melhor código é aquele que você não precisa manter — portanto, escreva menos código, e escreva em Rust."</i></sub>

<br/><br/>

<img src="https://raw.githubusercontent.com/GHSFS/GHSFS/main/.github/footer.svg" width="100%" alt="footer"/>

</div>
