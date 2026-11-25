# Design Decisions

Only decisions the project owner has actually made are recorded here. Mechanics in the imported rules are not recorded as decisions until the owner confirms them (see [UQ-0002](UNRESOLVED_QUESTIONS.md#uq-0002--approval-status-of-imported-rules)).

### DEC-0001 — GitHub Markdown repository as source of truth

- **Date:** 2026-11-25
- **Status:** Approved
- **Authority:** Project Owner

#### Context

Rules were previously kept in an Obsidian vault. Two assistants (Claude and ChatGPT) need a shared, reviewable record.

#### Options Considered

Keep the Obsidian vault; move to a GitHub repository of plain Markdown.

#### Decision

Use `kollindrake/wild-wasteland` on GitHub, Markdown only, as the single source of truth. Obsidian is no longer used and its configuration is not kept.

#### Rationale

Version history, and a record any assistant can read without access to private conversations.

#### Mechanical Consequences

None. Organizational only.

#### Related Documents

[CLAUDE.md](../CLAUDE.md), [AGENTS.md](../AGENTS.md)

### DEC-0002 — Agent rules and operating guidelines adopted

- **Date:** 2026-11-25
- **Status:** Approved
- **Authority:** Project Owner

#### Context

The project needs fixed rules for scope, authority, documentation, and collaboration between agents.

#### Options Considered

Not recorded.

#### Decision

The owner's guidelines are stored verbatim in `CLAUDE.md` and govern all work. The repository layout follows CLAUDE.md §5, creating files only when real content exists.

#### Rationale

Keeps the project to rules development and makes the owner the sole authority on canon.

#### Mechanical Consequences

None directly. All imported rules are treated as Draft until confirmed.

#### Related Documents

[CLAUDE.md](../CLAUDE.md)
