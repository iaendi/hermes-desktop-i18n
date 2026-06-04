# 🌐 Hermes Desktop i18n — Multilingual Support

**Hermes Agent 桌面端多语言国际化项目** — 已提交至 [PR #38846](https://github.com/NousResearch/hermes-agent/pull/38846)

[![Languages](https://img.shields.io/badge/languages-9-blue)](#)
[![Coverage](https://img.shields.io/badge/coverage-95%25-green)](#)
[![PR Status](https://img.shields.io/badge/PR%20%2338846-open-brightgreen)](https://github.com/NousResearch/hermes-agent/pull/38846)
[![Conflicts](https://img.shields.io/badge/conflicts-resolved-success)](https://github.com/NousResearch/hermes-agent/pull/38846)

[![Maintained by Hermes](https://img.shields.io/badge/maintained%20by-Hermes%20Agent-purple)](https://hermes-agent.nousresearch.com)

---

## 🇬🇧 English

We love [Hermes Agent](https://github.com/NousResearch/hermes-agent). It's the most capable open-source AI agent we've ever used. We wanted to make it accessible to everyone, regardless of native language.

This project adds **full i18n support to the Hermes Desktop app** with 9 languages. Adding a 9th language requires no code changes — just drop in a new JSON file.

### Supported Languages

| Language | Code | Coverage |
|----------|------|----------|
| English (source) | en | 861/861 (100%) |
| Deutsch (de) | de | 812/861 (94.3%) |
| Español (es) | es | 826/861 (95.9%) |
| Français (fr) | fr | 815/861 (94.7%) |
| 日本語 (ja) | ja | 839/861 (97.4%) |
| 한국어 (ko) | ko | 839/861 (97.4%) |
| Português (BR) (pt-BR) | pt-BR | 822/861 (95.5%) |
| 简体中文 (zh-CN) | zh-CN | 845/861 (98.1%) |
| 繁體中文 (zh-Hant) | zh-Hant | 845/861 (98.1%) |

### Features

- 🌐 **Auto-discovery**: drop a `{code}.json` in `src/locales/` → instantly available
- 🖱️ **One-click switch**: globe icon in the titlebar
- 💾 **Persistent**: remembers your choice
- 🖥️ **System detection**: follows OS language by default
- ⚡ **Instant switching**: no flash, no delay

### Need another language?

Comment below or open an issue — Hermes will maintain this continuously.

### ⭐ Star & Share

If you find this useful, please star this repo and share it with the Hermes community!

---

## 🇨🇳 简体中文

我们热爱 [Hermes Agent](https://github.com/NousResearch/hermes-agent)。这是我们用过最强大的开源 AI 代理。我们想让它对每个人都触手可及，无论母语是什么。

本项目为 Hermes 桌面端添加**完整的多语言支持**，覆盖 9 种语言。添加第 9 种语言**零代码改动**——只需放入新的 JSON 文件。

功能：自动发现新语言、一键切换、系统语言检测、即时无闪烁切换。

**喜欢这个项目？请 ⭐ 点赞并分享给 Hermes 社区！需要更多语言？留言告诉我们——Hermes 将持续维护。**

---

## 🇯🇵 日本語

私たちは Hermes Agent を愛用しています。このプロジェクトは Hermes Desktop に 9 言語の i18n サポートを追加します。新しい言語は JSON ファイルを追加するだけです。

**⭐ スターとシェアをお願いします！**

---

## 🇰🇷 한국어

우리는 Hermes Agent를 사랑합니다. 이 프로젝트는 Hermes Desktop에 9개 언어 i18n 지원을 추가합니다.

**⭐ 스타와 공유 부탁드립니다!**

---

## 🇩🇪 Deutsch / 🇪🇸 Español / 🇫🇷 Français / 🇹🇼 繁體中文

Sehen Sie die englische Version für vollständige Details.⭐ Star & Share!

---

## 🤖 Automated Maintenance by Hermes

This project is maintained by Hermes Agent itself:

- 🔔 **GitHub Webhook**: monitors issues, comments, and new language requests
- ⏰ **Cron Job**: periodic checks for unanswered comments and stale issues
- ✍️ **Auto-response**: Hermes replies to comments, applies fixes, submits PRs

---

## 📣 Latest Updates

- **2026-06-04**: PR #38846 merged with upstream main — all conflicts resolved
- **2026-06-04**: @Yuxin-Qiao's helper PR merged — added Vitest locale key parity tests + normalizeLocale coverage
- **2026-06-03**: Initial submission with 9 languages, 857 keys each
- **Auto-maintenance active**: Hermes monitors PR feedback every 15 minutes

## 🤝 How to Contribute a New Language

1. Copy `src/locales/en.json` to `src/locales/{your-code}.json`
2. Translate the values
3. Submit a PR or open an issue with your file
4. Hermes will integrate it automatically

---

**Built with ❤️ by Hermes Agent**
