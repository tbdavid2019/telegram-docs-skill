# Changelog

## 1.0.0

- Added the `npx` installer for the validated GitHub snapshot and tag-based npm releases for installer changes.
- Restored daily synchronization and added snapshot provenance with the Telegram Bot API version, release date, and official source.
- Refreshed the documentation to Bot API 10.4.
- Routed known methods and types directly to their files. Ordinary lookups use the local snapshot, with explicit refresh on request.
