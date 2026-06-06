# 🌐 Hermes Desktop i18n — Multilingual Support

**Hermes Agent 桌面端多语言国际化项目** — 已提交至 [PR #38846](https://github.com/NousResearch/hermes-agent/pull/38846)

[![Languages](https://img.shields.io/badge/languages-15-blue)](#)
[![Coverage](https://img.shields.io/badge/key%20parity-100%25-green)](#)
[![PR Status](https://img.shields.io/badge/PR%20%2338846-open-brightgreen)](https://github.com/NousResearch/hermes-agent/pull/38846)
[![Conflicts](https://img.shields.io/badge/conflicts-resolved-success)](https://github.com/NousResearch/hermes-agent/pull/38846)

[![Maintained by Hermes](https://img.shields.io/badge/maintained%20by-Hermes%20Agent-purple)](https://hermes-agent.nousresearch.com)

---

## 🇬🇧 English

We love [Hermes Agent](https://github.com/NousResearch/hermes-agent). It's the most capable open-source AI agent we've ever used. We wanted to make it accessible to everyone, regardless of native language.

This project adds **full i18n support to the Hermes Desktop app** with 15 languages. Adding a 16th language requires no code changes — just drop in a new JSON file.

### Supported Languages

| Language | Code | Coverage |
|----------|------|----------|
| English (source) | en | 861/861 (100%) |
| العربية | ar | 861/861 (100%) |
| Deutsch | de | 861/861 (100%) |
| Español | es | 861/861 (100%) |
| Français | fr | 861/861 (100%) |
| हिन्दी | hi | 861/861 (100%) |
| Italiano | it | 861/861 (100%) |
| 日本語 | ja | 861/861 (100%) |
| 한국어 | ko | 861/861 (100%) |
| Português (BR) | pt-BR | 861/861 (100%) |
| Русский | ru | 861/861 (100%) |
| ภาษาไทย | th | 861/861 (100%) |
| Tiếng Việt | vi | 861/861 (100%) |
| 简体中文 | zh-CN | 861/861 (100%) |
| 繁體中文 | zh-Hant | 861/861 (100%) |

> All 15 locales pass key parity regression tests against en.json (861 flattened keys each), verified by Vitest.

### Features

- 🌐 **Auto-discovery**: drop a `{code}.json` in `src/locales/` → instantly available
- 🖱️ **One-click switch**: globe icon in the titlebar
- 💾 **Persistent**: remembers your choice
- 🖥️ **System detection**: follows OS language by default
- ⚡ **Instant switching**: no flash, no delay
- ✅ **Key parity tested**: automated Vitest regression tests catch missing/extra keys

### Need another language?

Comment on [PR #38846](https://github.com/NousResearch/hermes-agent/pull/38846) or open an issue — Hermes will maintain this continuously.

### ⭐ Star & Share

If you find this useful, please star this repo and share it with the Hermes community!

---

## 🇨🇳 简体中文

我们热爱 [Hermes Agent](https://github.com/NousResearch/hermes-agent)。这是我们用过最强大的开源 AI 代理。我们想让它对每个人都触手可及，无论母语是什么。

本项目为 Hermes 桌面端添加**完整的多语言支持**，覆盖 15 种语言。添加第 16 种语言**零代码改动**——只需放入新的 JSON 文件。

功能：自动发现新语言、一键切换、系统语言检测、即时无闪烁切换、自动化键位对等回归测试。

**喜欢这个项目？请 ⭐ 点赞并分享给 Hermes 社区！需要更多语言？留言告诉我们——Hermes 将持续维护。**

---

## 🇯🇵 日本語

私たちは Hermes Agent を愛用しています。このプロジェクトは Hermes Desktop に 15 言語の i18n サポートを追加します。新しい言語は JSON ファイルを追加するだけです。

**⭐ スターとシェアをお願いします！**

---

## 🇰🇷 한국어

우리는 Hermes Agent를 사랑합니다. 이 프로젝트는 Hermes Desktop에 15개 언어 i18n 지원을 추가합니다.

**⭐ 스타와 공유 부탁드립니다!**

---

## 🇩🇪 Deutsch / 🇪🇸 Español / 🇫🇷 Français / 🇹🇼 繁體中文

Siehe englische Version für vollständige Details. ⭐ Star & Share!

---

## 🤖 Automated Maintenance by Hermes

This project is maintained by Hermes Agent itself:

- 🔔 **GitHub Webhook**: monitors PR comments, issues, and new language requests
- ⏰ **Cron Job**: periodic checks for unanswered comments and stale issues
- ✍️ **Auto-response**: Hermes replies to comments, applies fixes, submits PRs

---

## 📣 Latest Updates

- **2026-06-04**: zh-CN polish pass by @starlit-dream — fixed mistranslations and awkward phrasing throughout
- **2026-06-04**: @Yuxin-Qiao contributed 3 helper PRs, all merged:
  - Vitest locale key parity regression test (all 15 languages verified at 861/861)
  - `normalizeLocale()` coverage for `zh-TW`, `zh-HK`, `zh-MO` → `zh-Hant`
  - `useLocaleSync()` hook to ensure standalone `t()` repaints on locale switch
  - Docs follow-up to clarify `LANGUAGE_LABELS` registration
- **2026-06-04**: @heidis168 endorsed the PR, calling it "accessible to so many more developers around the world"
- **2026-06-04**: Merge conflicts with upstream main resolved — branch is clean and ready for review
- **2026-06-03**: Initial submission with 15 languages
- **Auto-maintenance active**: Hermes monitors PR feedback every 15 minutes

---

## 🤝 How to Contribute a New Language

1. Copy `apps/desktop/src/locales/en.json` to `apps/desktop/src/locales/{your-code}.json`
2. Translate the values
3. Submit a PR or open an issue with your file
4. Hermes will integrate it automatically

---

**Built with ❤️ by Hermes Agent**
