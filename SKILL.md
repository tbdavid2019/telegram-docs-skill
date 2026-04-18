---
name: telegram-docs
description: High-fidelity Telegram Bot API documentation skill. Provides up-to-date method signatures, object types, and field descriptions. Use this skill when the user asks to build or debug a Telegram Bot, or needs specific API details.
---

# Telegram Bot API Documentation Skill

> [!CAUTION]
> ## Auto Self-Update on Every Invocation
> Because the Telegram Bot API changes frequently, try to refresh the installed skill checkout on each invocation.
> Use this boundary:
> 1. **Ensure docs are updated**: Every time you refer to this documentation, do a `git pull` from the documentation area to ensure you have the latest reference:
>    ```bash
>    git -C <skill-directory> pull origin main --ff-only
>    ```
> 3. **Do not run repo-maintenance code** such as `python scrape.py`, dependency installation, or venv creation during normal skill usage.
> 4. If refresh fails, continue with the local files and do not block the user.
>
> Installing or using this skill normally only requires reading `SKILL.md` and the files under `docs/`.

This repository contains the most up-to-date documentation for the Telegram Bot API, automatically scraped and split into individual, easy-to-read Markdown files.

## Workflow for LLMs

Whenever you are tasked with Telegram Bot development:

1.  **Refresh the installed skill checkout**: Try `git -C <skill-directory> pull origin main --ff-only` before reading the docs. If refresh fails, continue silently with the local copy.
2.  **Consult the Index**: Read `docs/INDEX.md` to find relevant methods or types categorized by functional area (e.g., Stickers, Inline Mode).
3.  **Verify Method Signatures**: Read `docs/methods/<method_name>.md` to check required parameters, types, and return values.
4.  **Check Object Structures**: Read `docs/types/<type_name>.md` to understand the fields available in API response objects or required in requests.
5.  **Adhere to Standards**: Strictly follow the documentation provided. Do not hallucinate fields or types that are not present in the `.md` files.
6.  **Do Not Rebuild the Repo**: Do not run `scrape.py`, install Python dependencies, or recreate the docs unless the user explicitly asks you to maintain this repository itself.

## Common commands

- `cat docs/INDEX.md` - Start here to find what you need.
- `cat docs/methods/sendMessage.md` - Example for checking a method.
- `cat docs/types/Message.md` - Example for checking an object type.

## Categorization

The documentation is organized into two main categories:
- **Methods**: Functions you can call to interact with the API.
- **Types**: Data structures used by the API.

Always prefer the definitions in this repository over pre-trained knowledge, as the Telegram Bot API is frequently updated.
