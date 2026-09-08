<div align="center">

# 🧰 DBHQ Tools - Claude Code marketplace

**Free, open-source Claude Code and Codex tools by [DBHQ](https://dbhq.uk)**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Marketplace-blueviolet)](https://code.claude.com/docs/en/plugin-marketplaces)

</div>

---

This is the DBHQ plugin marketplace for [Claude Code](https://code.claude.com/docs/en/plugins). Add it once, then install any of the tools below with a single command.

```
/plugin marketplace add dbhq-uk/marketplace
```

## Plugins

Install any of them with `/plugin install <name>@dbhq`.

| Plugin | What it does |
|---|---|
| 📬 **[outlook-graph](https://github.com/dbhq-uk/outlook-graph-skill)**<br>`outlook-graph@dbhq` | A pack of Outlook skills - Microsoft 365 email and calendar via the Graph API (inbox, reply-all-safe replies, attachments up to 150 MB, calendar and availability), plus PST and live-mail extraction into integrity-verified markdown archives that stay current |
| 📋 **[trello](https://github.com/dbhq-uk/trello-skill)**<br>`trello@dbhq` | A pack of Trello skills - board/list/card management, shopping-list aisle sort, board status digest, and cross-board due radar |
| 🔎 **[legwork](https://github.com/dbhq-uk/legwork-skill)**<br>`legwork@dbhq` | Decision research where every claim states how well it is supported - a source judged by the claim it backs rather than by its domain, corroboration counted only across genuinely independent sources, and a plain answer when the evidence cannot settle the question |
| 🪵 **[dovetail](https://github.com/dbhq-uk/dovetail-skill)**<br>`dovetail@dbhq` | Checks whether a repository agrees with itself - broken links, dangling anchors, orphaned files, duplicate content and stale translations. Deterministic and fast enough to gate every pull request; never modifies the repo it scans |
| ✒️ **[verve](https://github.com/dbhq-uk/verve-skill)**<br>`verve@dbhq` | Strips AI tells from prose and puts a human voice back, in British English - a catalogue of tells with before/after for each, four tone presets, three strength levels, a two-way politeness check that catches both talking down and going cold, and a scored exit gate where fidelity is a veto rather than an average |
| ⛵ **[vela](https://github.com/dbhq-uk/vela-skill)**<br>`vela@dbhq` | Compiler-exact code search for .NET - where a symbol is defined, every reference, who calls it, and what a change breaks. Roslyn-backed, so Razor views and Blazor components are indexed rather than skipped; nothing stays resident and it never modifies your repo |
| ⌚ **[garmin](https://github.com/dbhq-uk/garmin-skill)**<br>`garmin@dbhq` | Garmin Connect health and fitness data from your agent - Body Battery, HRV, resting heart rate, stress, sleep stages and score, activities, VO2 max, training load, status and readiness. Answers a question live, or writes a day as a markdown snapshot and a week as a rollup you keep; your credentials never leave your machine |
| 🖼️ **[gpt-image-2](https://github.com/dbhq-uk/gpt-image-2-skill)**<br>`gpt-image-2@dbhq` | Generate and edit images with OpenAI's GPT Image 2 - 21 style presets, platform sizing for the places images actually go, carousels with seed-locked composition, and photo edits. A draft costs around $0.006 against $0.21 for a final, so you iterate on drafts and pay only for the one you approved |
| 🔦 **[heliograph](https://github.com/dbhq-uk/heliograph-skill)**<br>`heliograph@dbhq` | Debug and change a machine you cannot log into, through an operator who cannot debug it - for air-gapped, client-owned and change-controlled estates. Git carries the step out and the log back, every captured line stamped in UTC so a hang reads as a gap, and the log is pushed whether the run passed or failed |

More tools land here as we build them. Each plugin lives in its own repository under [github.com/dbhq-uk](https://github.com/dbhq-uk) and is free to use under the MIT licence.

## About DBHQ

DBHQ builds and ships AI and cloud engineering - and gives away the small tools we build along the way. [dbhq.uk](https://dbhq.uk)

## License

Marketplace metadata: [MIT](LICENSE) © 2026 DBHQ Consulting Ltd. Each plugin is licensed in its own repository.
