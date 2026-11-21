# GitHub discoverability — editorial inventory

> **Status:** recommendations only. These About descriptions, topics and homepages are **not** automatically applied to GitHub repository settings by this document. Audit date: 2026-11-21. Keep the descriptions aligned with actual released functionality.

GitHub search and discovery benefit from concise repository descriptions, relevant topics and an accurate homepage. README content helps humans and search engines understand the project; it is not a guarantee of search ranking.

## Suggested GitHub About fields

| Public repository | Suggested concise description (English) | Suggested topics | Homepage |
| --- | --- | --- | --- |
| [SystemMonitor](https://github.com/neosoda/SystemMonitor) | Windows PC monitoring dashboard with PyQt5: CPU, RAM, disk, network and optional hardware sensors. | `windows`, `system-monitor`, `hardware-monitoring`, `python`, `pyqt5`, `performance-monitoring` | — |
| [DriversUpdate](https://github.com/neosoda/DriversUpdate) | PowerShell tools for controlled Windows driver updates through Windows Update or WSUS, with GPO support. | `windows`, `drivers`, `powershell`, `wsus`, `windows-update`, `gpo`, `sysadmin` | — |
| [ia-portable](https://github.com/neosoda/ia-portable) | Local-first Linux CLI assistant that turns natural language into Bash commands via Ollama or OpenRouter. | `linux`, `bash`, `ollama`, `llm`, `terminal`, `local-ai`, `cli` | — |
| [news](https://github.com/neosoda/news) | Self-hosted tech news aggregator with RSS collection, deduplication and AI-assisted summaries. | `rss`, `news-aggregator`, `tech-news`, `ai`, `cybersecurity`, `self-hosted`, `docker` | https://news.techsentinel.fr |
| [Tools](https://github.com/neosoda/Tools) | Self-hosted browser toolbox for images, PDF, text, dates and structured data. | `web-tools`, `self-hosted`, `privacy`, `pdf-tools`, `image-tools`, `react`, `docker` | https://tools.techsentinel.fr |
| [networking-toolbox](https://github.com/neosoda/networking-toolbox) | Hosted derivative of Alicia Sykes' Networking Toolbox: subnetting, CIDR, DNS and network diagnostics. | `networking`, `network-tools`, `subnet-calculator`, `cidr`, `dns`, `sveltekit` | https://nettools.techsentinel.fr |
| [NetTools](https://github.com/neosoda/NetTools) | Windows network operations app: SNMP discovery, multi-site inventory, SSH backups and configuration audits. | `network-administration`, `snmp`, `ssh`, `network-inventory`, `network-audit`, `wails`, `go` | — |
| [NeoGet](https://github.com/neosoda/NeoGet) | Windows desktop app for WinGet software management, updates and maintenance, built with Tauri and Rust. | `winget`, `windows`, `package-manager`, `software-updater`, `tauri`, `rust` | — |
| [DistroSentinel](https://github.com/neosoda/DistroSentinel) | Explore and compare Linux and BSD distributions with an interactive searchable catalogue. | `linux`, `linux-distributions`, `bsd`, `distro`, `typescript`, `vite` | https://distro.techsentinel.fr/ |
| [ShadowRDP](https://github.com/neosoda/ShadowRDP) | Windows remote support toolkit for RDP Shadow, session discovery, diagnostics and GPO deployment. | `rdp`, `rdp-shadow`, `remote-support`, `windows`, `powershell`, `gpo` | — |
| [reclip](https://github.com/neosoda/reclip) | Lightweight self-hosted media downloader UI for accessible MP4/MP3 content using yt-dlp and FFmpeg. | `yt-dlp`, `ffmpeg`, `video-downloader`, `audio-downloader`, `flask`, `self-hosted` | — |
| [GenSentinel](https://github.com/neosoda/GenSentinel) | Browser-only password, token and secret generator using the Web Crypto API. | `password-generator`, `token-generator`, `web-crypto`, `security`, `privacy`, `nextjs` | https://gen.techsentinel.fr/ |
| [NeoTech-Toolkit](https://github.com/neosoda/NeoTech-Toolkit) | Portable PowerShell/WPF toolkit for Windows diagnostics, hardware auditing and security reports. | `powershell`, `windows`, `sysadmin`, `diagnostics`, `hardware-audit`, `wpf` | — |
| [agent-commons](https://github.com/neosoda/agent-commons) | Local-first synchronization of AI agent skills and MCP configurations across coding assistants. | `ai-agents`, `mcp`, `skills`, `claude-code`, `codex`, `gemini-cli`, `local-first` | — |
| [Protocol](https://github.com/neosoda/Protocol) | Interactive bilingual network protocol lessons with packet animation and byte-level inspection. | Existing topics are relevant; maintain `networking`, `packet-analysis`, `tcp-ip`, `dns`, `tls`, `interactive-learning` | https://protocol.techsentinel.fr |
| [MiniScreenCompanion](https://github.com/neosoda/MiniScreenCompanion) | Windows PC telemetry and AI coding quota monitor for Turing Smart Screen 3.5-inch USB displays. | `turing-smart-screen`, `windows`, `usb-display`, `hardware-monitoring`, `claude-code`, `openai-codex`, `python` | — |
| [ChocolateyPackager](https://github.com/neosoda/ChocolateyPackager) | Windows GUI to build offline Chocolatey packages from MSI/EXE installers with validation and SHA-256 checks. | `chocolatey`, `windows`, `package-builder`, `winforms`, `dotnet`, `msi`, `sysadmin` | — |
| [neosoda](https://github.com/neosoda/neosoda) | GitHub profile README, not a product repository. Keep curated links to published projects. | Profile, no product topics required | https://techsentinel.fr |

## Deployment checklist

1. For each relevant repository, open the GitHub **About** settings and paste the description, homepage (if public and functioning), and topics. Avoid adding irrelevant topics or describing unshipped features.
2. Add a **Social preview** image in repository **Settings → General → Social preview** (GitHub recommends 1280 × 640). An SVG banner in a README does **not** automatically configure social preview.
3. Keep one prominent product call to action: **Try live**, **Download release**, or **Install locally**, depending on what actually exists. Do not link to a nonexistent release.
4. Use real screenshots or videos where available; label illustrations and mockups.
5. Ensure bilingual README translations remain aligned and avoid broken anchors, local file paths, and unsupported claims.
6. Link relevant project pages from [TechSentinel](https://techsentinel.fr/) and product pages with meaningful, non-duplicated summaries.

### Priority issues identified

- Most public repositories had **no GitHub topics** at the time of inspection.
- `MiniScreenCompanion` had an About description mentioning unrelated **GeekMagic/ESP32** hardware, while the README documents the **Turing 3.5-inch** display.
- `NeoTech-Toolkit` documented a release download before any GitHub release was found; avoid this claim until a real artifact exists.
- `networking-toolbox` is a derivative of **Alicia Sykes'** original work. Preserve explicit credit and do not market it as an original product.
