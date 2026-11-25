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

### DEC-0005 — Character Levels and Ranks

- **Date:** 2026-11-25
- **Status:** Approved (Canonical)
- **Authority:** Project Owner

#### Context

The 2d10 Engine had no progression rules. The glossary defined "Level" and "Rank" only loosely, and the Rank entry implied benefits ("unlocks features and improves certain statistics") that were never written. The owner's request referred to a previous 25-level progression system; no document in the repository or its history describes one, so the only prior record of progression is those two glossary entries.

#### Options Considered

Not recorded. The owner issued the rule directly.

#### Decision

- Character Level runs from 1 (minimum) to 20 (maximum).
- Progression is divided into five Ranks of four consecutive Character Levels each: Rank 1 Drifter (1–4), Rank 2 Survivor (5–8), Rank 3 Veteran (9–12), Rank 4 Renowned (13–16), Rank 5 Legend (17–20).
- A character's Rank is determined by their current Character Level. A character automatically advances to a Rank on reaching its minimum Character Level (1, 5, 9, 13, 17). There is no separate Rank advancement system.
- Explicitly **not** decided, and left unresolved (UQ-0007): Experience Points and advancement requirements, Rank-specific benefits, Rank-based restrictions, Attribute advancement, Skill advancement, Perk prerequisites, Rank-based equipment restrictions, Rank-based mechanical modifiers.

#### Rationale

Owner decision. Establishes the progression scale that later progression mechanics will build on.

#### Mechanical Consequences

- New canonical rule PROG-001 in `rules/character-progression.md`.
- Glossary "Level" replaced by "Character Level", and "Rank" rewritten to match. Previous imported wording, kept for the record:
  - Level: "A numerical representation of a character’s overall advancement, determining progression and access to additional abilities."
  - Rank: "A mark of advancement that unlocks features and improves certain statistics for Player Characters."
- Levels and Ranks have no mechanical effect yet, so there is nothing to balance until benefits or modifiers are approved.

#### Related Documents

[character-progression.md](../rules/character-progression.md), [glossary.md](../rules/glossary.md), [unresolved-questions.md](unresolved-questions.md#uq-0007--progression-mechanics-beyond-levels-and-ranks)
