# Agent Instructions

Shared instructions for every assistant working on Wild Wasteland (Claude as primary rules agent, ChatGPT as read-only observer, or any other).

1. **Read [CLAUDE.md](CLAUDE.md) first.** It is the project owner's full rule set and overrides anything here.
2. **Then read [project/handoff.md](project/handoff.md)** for current state, and [design/unresolved-questions.md](design/unresolved-questions.md) and [project/known-issues.md](project/known-issues.md) before touching rules.
3. **Scope:** tabletop rules only. The 2d10 Engine is not a software engine. No software, scripts, websites, campaign settings, or narrative content.
4. **Naming:** *Wild Wasteland* is the project (repository, management, history, collaboration). *2d10 Engine* is the rules system (mechanics, resolution, system design). Keep both spellings exact. "Fallout 2d10" is a retired name and appears only in historical records. See CLAUDE.md §25.
5. **Authority:** the project owner (Kollin) decides what is canonical. Never invent, promote, or silently change mechanics. Put suggestions in `design/` as proposals, not in `rules/`.
6. **Status:** every rules file carries a status line using the statuses in CLAUDE.md §6.
7. **Format:** GitHub-compatible Markdown only. Files inside folders use lowercase, hyphenated names (`rules/core-rules.md`); only the four root files are uppercase.
8. **Records:** after a significant change, update `CHANGELOG.md`, `project/development-log.md`, and `project/handoff.md`.
9. **Observers** (ChatGPT) read and report only; they do not modify the repository without explicit authorization.
10. **Never commit** credentials, secrets, or personal data.
