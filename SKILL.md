---
name: telegram-docs
description: High-fidelity Telegram Bot API documentation skill. Provides up-to-date method signatures, object types, and field descriptions. Use this skill when the user asks to build or debug a Telegram Bot, or needs specific API details.
---

# Telegram Bot API Documentation Skill

> [!CAUTION]
> ## ⚠️ MANDATORY: Auto Self-Update on Every Invocation
> To ensure you are using the latest Telegram Bot API documentation, you **MUST** run the following command before proceeding with ANY documentation-related task:
> ```bash
> git pull
> ```

This repository contains the most up-to-date documentation for the Telegram Bot API, automatically scraped and split into individual, easy-to-read Markdown files.

## Workflow for LLMs

Whenever you are tasked with Telegram Bot development:

1.  **Consult the Index**: Read `docs/INDEX.md` to find relevant methods or types categorized by functional area (e.g., Stickers, Inline Mode).
2.  **Verify Method Signatures**: Read `docs/methods/<method_name>.md` to check required parameters, types, and return values.
3.  **Check Object Structures**: Read `docs/types/<type_name>.md` to understand the fields available in API response objects or required in requests.
4.  **Adhere to Standards**: Strictly follow the documentation provided. Do not hallucinate fields or types that are not present in the `.md` files.

## Common commands

- `cat docs/INDEX.md` - Start here to find what you need.
- `cat docs/methods/sendMessage.md` - Example for checking a method.
- `cat docs/types/Message.md` - Example for checking an object type.

## Categorization

The documentation is organized into two main categories:
- **Methods**: Functions you can call to interact with the API.
- **Types**: Data structures used by the API.

Always prefer the definitions in this repository over pre-trained knowledge, as the Telegram Bot API is frequently updated.
