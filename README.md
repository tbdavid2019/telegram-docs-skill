# Telegram Bot API Knowledge Base

An Agent Skill with a local snapshot of the official Telegram Bot API documentation. Methods
and types are stored in individual Markdown files for targeted lookup.

## Install or update

With Node.js 22.20 or later and Git, run this from your project:

```bash
npx -y telegram-docs-skill@latest
```

The default target is Codex at `.agents/skills/telegram-docs`. Use `--global` for a user
installation or `--agent openclaw` to select OpenClaw. Re-run the same command and options to
refresh. The installer downloads the validated snapshot from GitHub and reports the installed
path, skill commit, and Telegram Bot API version.

### Git checkout

```bash
git clone https://github.com/tbdavid2019/telegram-docs-skill.git <skill-directory>
git -C <skill-directory> pull --ff-only origin main
```

Use `telegram-docs` as the final directory name. Re-run the pull when you want to update a Git
installation. Host-managed copies use the corresponding host update mechanism.

## AI Agent Installation Contract

1. Identify the host and installation scope. Prefer npm for a new install and use the original
   installer for an existing copy.
2. Read the installed `SKILL.md`. Verify `docs/SOURCE.json`, `docs/INDEX.md`, and the methods and
   types directories. Report the installed location, skill commit, and Bot API version.
3. Use the installed snapshot during ordinary lookups. Refresh only on request and reserve
   `scrape.py` and its Python dependencies for maintaining this repository.

## 繁體中文說明

需要 Node.js 22.20 以上與 Git。在專案執行 `npx -y telegram-docs-skill@latest`，預設會為
Codex 安裝至 `.agents/skills/telegram-docs`。可加 `--global`，或用 `--agent openclaw`
指定宿主。用相同指令與選項更新。既有 Git checkout 請沿用 `git pull --ff-only`。

平常直接讀本機快照。知道方法或型別名稱時，可直達 `docs/methods/` 或 `docs/types/` 的
個別文件。需要探索功能時，再查 `docs/INDEX.md` 的相關分類。`docs/SOURCE.json` 記錄
Telegram Bot API 版本、官方來源與發佈日期。

## Daily synchronization

GitHub Actions runs `scrape.py` daily against the [official Telegram Bot API documentation](https://core.telegram.org/bots/api).
It commits a complete, validated snapshot to `main` when the generated files change. Installed
skills receive that snapshot on the next explicit update.

## Release the npm installer

Update the npm version and lockfile when the installer changes. Test the first tarball with
`npm pack`, then publish it with `npm publish <tarball> --access public`. For subsequent releases,
configure npm Trusted Publishing for `publish-npm.yml` when ready to release, then push the matching
`v<version>` tag. The first OIDC publish must succeed within two days of configuring trust.

## License

Repository-authored code is licensed under [AGPL-3.0](LICENSE). The generated reference pages
link to the official Telegram source.
