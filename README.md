<div align="center">

# 🧰 DBHQ Tools - Claude Code marketplace

**Free, open-source Claude Code and Codex tools by [DBHQ](https://dbhq.uk)**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Marketplace-blueviolet)](https://code.claude.com/docs/en/plugin-marketplaces)

</div>

---

This is the DBHQ plugin marketplace for [Claude Code](https://code.claude.com/docs/en/plugins). Add it once, then install any of our tools with a single command.

## Add the marketplace

```
/plugin marketplace add dbhq-uk/marketplace
```

## Install a plugin

```
/plugin install outlook-graph@dbhq
/plugin install trello@dbhq
/plugin install legwork@dbhq
/plugin install dovetail@dbhq
/plugin install verve@dbhq
/plugin install vela@dbhq
```

## What's here

| Plugin | Description |
|--------|-------------|
| 📬 **[outlook-graph](https://github.com/dbhq-uk/outlook-graph-skill)** | A pack of Outlook skills - Microsoft 365 email and calendar via the Graph API (inbox, reply-all-safe replies, attachments up to 150 MB, calendar and availability), plus PST and live-mail extraction into integrity-verified markdown archives that stay current |
| 📋 **[trello](https://github.com/dbhq-uk/trello-skill)** | A pack of Trello skills - board/list/card management, shopping-list aisle sort, board status digest, and cross-board due radar |
| 🔎 **[legwork](https://github.com/dbhq-uk/legwork-skill)** | Decision research where every claim states how well it is supported - a source judged by the claim it backs rather than by its domain, corroboration counted only across genuinely independent sources, and a plain answer when the evidence cannot settle the question |
| 🪵 **[dovetail](https://github.com/dbhq-uk/dovetail-skill)** | Checks whether a repository agrees with itself - broken links, dangling anchors, orphaned files, duplicate content and stale translations. Deterministic and fast enough to gate every pull request; never modifies the repo it scans |
| ✒️ **[verve](https://github.com/dbhq-uk/verve-skill)** | Strips AI tells from prose and puts a human voice back, in British English - a catalogue of tells with before/after for each, four tone presets, three strength levels, and a scored exit gate where fidelity is a veto rather than an average |
| ⛵ **[vela](https://github.com/dbhq-uk/vela-skill)** | Compiler-exact code search for .NET - where a symbol is defined, every reference, who calls it, and what a change breaks. Roslyn-backed, so Razor views and Blazor components are indexed rather than skipped; nothing stays resident and it never modifies your repo |

More tools land here as we build them. Each plugin lives in its own repository under [github.com/dbhq-uk](https://github.com/dbhq-uk) and is free to use under the MIT licence.

## About DBHQ

DBHQ builds and ships AI and cloud engineering - and gives away the small tools we build along the way. [dbhq.uk](https://dbhq.uk)

## License

Marketplace metadata: [MIT](LICENSE) © 2026 DBHQ Consulting Ltd. Each plugin is licensed in its own repository.
