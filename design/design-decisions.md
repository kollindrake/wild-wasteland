# Design Decisions

Only decisions the project owner has actually made are recorded here. Mechanics in the imported rules are not recorded as decisions until the owner confirms them (see [UQ-0002](unresolved-questions.md#uq-0002--approval-status-of-imported-rules)).

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

### DEC-0003 — Project and rules system naming

- **Date:** 2026-11-25
- **Status:** Approved
- **Authority:** Project Owner

#### Context

The imported rules were titled "Fallout 2d10", and early documentation described Wild Wasteland as the rules system itself (UQ-0004).

#### Options Considered

Not recorded.

#### Decision

- **Wild Wasteland** is the overall project: project management, repository organization, development history, agent collaboration.
- **2d10 Engine** is the tabletop rules system: mechanics, resolution systems, system design.
- Exact spelling and capitalization of both names are preserved. The repository is not renamed.
- "Fallout 2d10" is retired. Historical records keep it, with a clarifying note.

#### Rationale

Separates the project from the rules system it produces. Full text in CLAUDE.md §25.

#### Mechanical Consequences

None. The name "2d10 Engine" does not approve any specific dice resolution mechanic; UQ-0001 remains open.

#### Related Documents

[CLAUDE.md §25](../CLAUDE.md#25-project-identity-and-naming-convention), [AGENTS.md](../AGENTS.md), [unresolved-questions.md](unresolved-questions.md)

### DEC-0004 — Lowercase file names

- **Date:** 2026-11-25
- **Status:** Approved
- **Authority:** Project Owner

#### Context

The structure in CLAUDE.md §5 used all-caps file names (`rules/CORE_RULES.md`).

#### Options Considered

Keep all caps; use lowercase.

#### Decision

Files inside folders use lowercase names with hyphens (`rules/core-rules.md`, `project/known-issues.md`). The root files `README.md`, `CLAUDE.md`, `AGENTS.md`, and `CHANGELOG.md` keep their conventional names because tools look for them by those exact names.

#### Rationale

Project owner preference.

#### Mechanical Consequences

None. Organizational only.

#### Related Documents

[CLAUDE.md §5](../CLAUDE.md#5-repository-organization)
