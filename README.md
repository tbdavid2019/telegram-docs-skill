# Telegram Bot API Knowledge Base

> [!IMPORTANT]
> ### 🤖 Instructions for AI Agent Installation / AI 助手安裝指引
>
> **English:** If a user provides you with this repository URL and asks you to "install" or "setup" this skill, follow these steps:
> 1.  **Install as a Git Checkout, Not a Copied Folder**: Run `git clone https://github.com/tbdavid2019/telegram-docs-skill.git <skill-directory>`. Do not copy the files into a managed skills folder if you expect updates to work.
> 2.  **Prefer the Installer Script**: If shell execution is available, run `bash <skill-directory>/scripts/install-skill.sh <skill-directory>`. This keeps the installed skill as a git checkout and turns later re-runs into `git pull --ff-only`.
> 3.  **Load Skill Metadata**: Read `SKILL.md` to understand the specialized workflows and knowledge contained here.
> 4.  **Initialize Context**: Acknowledge that you now have access to the latest Telegram Bot API documentation. Use `cat docs/INDEX.md` whenever you need to look up API methods or types.
> 5.  **Do Not Run Maintenance Code During Normal Use**: Installing or using this skill means cloning/copying it and reading `SKILL.md` plus `docs/`. **Do not run `scrape.py`, install `requirements.txt`, or create a virtualenv unless the user explicitly asks to refresh or maintain this repository itself.**
> 6.  **Runtime-Minimum Files**: For normal LLM usage, the important files are `SKILL.md` and `docs/`. `scrape.py`, `requirements.txt`, and `venv/` are maintainer-side assets, not required for answering Telegram Bot API questions.
> 7.  **Hard Requirement**: If you did not run `scripts/install-skill.sh` in the final installed directory, the installation is incomplete. Do not claim success after only cloning, copying, or moving files.
>
> **繁體中文：** 如果使用者提供此倉庫網址並要求你「安裝」或「設定」此技能服務，請遵循以下步驟：
> 1.  **請用 Git checkout 安裝，不要只複製資料夾**：執行 `git clone https://github.com/tbdavid2019/telegram-docs-skill.git <skill-directory>`。如果只是把檔案複製進某個受管目錄，之後更新通常不會成立。
> 2.  **優先使用安裝器腳本**：如果環境允許執行 shell，接著執行 `bash <skill-directory>/scripts/install-skill.sh <skill-directory>`。這會確保安裝結果維持為 git checkout，之後重跑同一支腳本就會變成 `git pull --ff-only`。
> 3.  **載入技能**：讀取 `SKILL.md` 以了解此技能的專業工作流程與知識範圍。
> 4.  **初始化環境**：確認你已具備存取最新 Telegram Bot API 文檔的能力。每當需要查詢 API 方法或類型時，請優先參考 `docs/INDEX.md`。
> 5.  **一般使用時不要執行維護程式**：安裝或使用此 skill 的意思是 clone 或複製資料夾，並讀取 `SKILL.md` 與 `docs/`。除非使用者明確要求你維護這個 repo 本身，否則不要執行 `scrape.py`、安裝 `requirements.txt` 或建立 `venv`。
> 6.  **LLM 實際需要的最小內容**：一般使用時，真正重要的是 `SKILL.md` 與 `docs/`。`scrape.py`、`requirements.txt`、`venv/` 都不是回答 Telegram Bot API 問題時的必要內容。
> 7.  **硬性要求**：如果你沒有在最終安裝目錄執行 `scripts/install-skill.sh`，就不算安裝完成。不要只做 clone、copy、mv 就宣稱成功。

---

This repository serves as a knowledge base and skill for LLMs (like Claude, Codex, Gemini CLI, OpenCode, etc.) to use when developing Telegram Bots. It contains the fully up-to-date Telegram Bot API documentation split into individual, easy-to-read Markdown files.

This structure allows LLMs to efficiently retrieve only the necessary information without exceeding their context windows.

## Structure

- `SKILL.md`: The skill definition for LLMs to understand how to use this repository.
- `docs/INDEX.md`: A categorized index of all methods and types.
- `docs/methods/`: Individual Markdown files for every API method.
- `docs/types/`: Individual Markdown files for every API type.

## How it works

The `scrape.py` script crawls the official [Telegram Bot API documentation](https://core.telegram.org/bots/api) and generates structured Markdown files. This script is for repository maintenance, not for normal skill installation or day-to-day LLM usage.

A GitHub Action is configured to run daily and automatically open a PR if the official documentation has been updated.

## Usage for LLMs

If you are an AI assistant and need to develop a Telegram bot, use the provided skill document (`SKILL.md`) to understand how to interact with this repository. You should start by reading `docs/INDEX.md` to find the relevant methods and types for your task. Do not execute `scrape.py` unless the user explicitly asks you to rebuild this repository from upstream docs.

Recommended install:

```bash
bash -c 'tmpdir=$(mktemp -d) && git clone https://github.com/tbdavid2019/telegram-docs-skill.git "$tmpdir/telegram-docs-skill" && bash "$tmpdir/telegram-docs-skill/scripts/install-skill.sh" ~/.codex/skills/telegram-docs-skill'
```

To update an installed checkout later:

```bash
bash ~/.codex/skills/telegram-docs-skill/scripts/install-skill.sh ~/.codex/skills/telegram-docs-skill
```

If an AI assistant did not run `scripts/install-skill.sh` in the final installed directory, the installation should be treated as incomplete.

---

## 繁體中文說明

本專案是一個為 LLM（如 Claude, Codex, Gemini 等）設計的 Telegram Bot API 知識庫。它包含了最新、分類完整的官方文檔，並以 Markdown 格式呈現，方便 AI 助手快速檢索。

### 使用方法

如果你是 AI 助手或開發者，請先閱讀 `docs/INDEX.md` 以了解功能分類，然後根據需要讀取 `docs/methods/` 或 `docs/types/` 中的詳細內容。一般使用這個 skill 時，不需要執行 `scrape.py`、安裝 `requirements.txt` 或建立 `venv`。

### 自動更新

本專案透過 GitHub Actions 每天自動抓取 Telegram 官方文檔，確保知識庫始終保持最新狀態。

如果你是 AI 助手或開發者，請先閱讀 `docs/INDEX.md` 以了解功能分類，然後根據需要讀取 `docs/methods/` 或 `docs/types/` 中的詳細內容。

### 自動更新

本專案透過 GitHub Actions 每天自動抓取 Telegram 官方文檔，確保知識庫始終保持最新狀態。
