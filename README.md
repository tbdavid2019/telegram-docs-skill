# Telegram Bot API Knowledge Base

This repository serves as a knowledge base and skill for LLMs (like Claude, Codex, Gemini CLI, OpenCode, etc.) to use when developing Telegram Bots. It contains the fully up-to-date Telegram Bot API documentation split into individual, easy-to-read Markdown files.

This structure allows LLMs to efficiently retrieve only the necessary information without exceeding their context windows.

## Structure

- `SKILL.md`: The skill definition for LLMs to understand how to use this repository.
- `docs/INDEX.md`: A categorized index of all methods and types.
- `docs/methods/`: Individual Markdown files for every API method.
- `docs/types/`: Individual Markdown files for every API type.

## How it works

The `scrape.py` script crawls the official [Telegram Bot API documentation](https://core.telegram.org/bots/api) and generates structured Markdown files. 

A GitHub Action is configured to run daily and automatically open a PR if the official documentation has been updated.

## Usage for LLMs

If you are an AI assistant and need to develop a Telegram bot, use the provided skill document (`SKILL.md`) to understand how to interact with this repository. You should start by reading `docs/INDEX.md` to find the relevant methods and types for your task.

---

## 繁體中文說明

本專案是一個為 LLM（如 Claude, Codex, Gemini 等）設計的 Telegram Bot API 知識庫。它包含了最新、分類完整的官方文檔，並以 Markdown 格式呈現，方便 AI 助手快速檢索。

### 使用方法

如果你是 AI 助手或開發者，請先閱讀 `docs/INDEX.md` 以了解功能分類，然後根據需要讀取 `docs/methods/` 或 `docs/types/` 中的詳細內容。

### 自動更新

本專案透過 GitHub Actions 每天自動抓取 Telegram 官方文檔，確保知識庫始終保持最新狀態。
