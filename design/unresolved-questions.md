# Unresolved Questions

Each needs a decision from the project owner. Nothing here is approved.

### UQ-0001 — Check roll direction

- **Status:** Unresolved
- **Affected Rules:** [action-resolution.md](../rules/action-resolution.md), [glossary.md](../rules/glossary.md) (Success, Failure, Difficulty Class, Advantage, Disadvantage, Critical Success)
- **Related Issue:** [ISSUE-0001](../project/known-issues.md#issue-0001--check-roll-direction-conflict)

`action-resolution.md` sets `DC = Attribute Rating + Skill Rating + Modifiers`, built from the acting character's own ratings. The glossary defines Success as a final result that "meets or exceeds" the DC.

**Option A: Roll 2d10, succeed on a result at or below the DC (roll-under).**
- Higher ratings raise the success chance, which matches the DC formula.
- Glossary entries for Success, Failure, and DC would need rewording.
- Example (illustrative, rating scale not yet defined): DC 11 succeeds 55%, DC 14 succeeds 79%.

**Option B: Roll 2d10, succeed on a result that meets or exceeds the DC (roll-over).**
- Matches the glossary wording.
- With the current DC formula, higher ratings make success *less* likely (DC 11: 55%, DC 14: 28%), so the DC formula would need to change, for example to add ratings to the roll instead.

**Interactions to settle with either option:** what "keep the highest/lowest dice" means for Advantage and Disadvantage; whether a natural 20 is a Critical Success or Critical Failure; how Tagged Skill doubles interact. See [probability-analysis.md](probability-analysis.md).

### UQ-0002 — Approval status of imported rules

- **Status:** Unresolved

Every imported file is marked Draft. The owner should confirm which mechanics, if any, are Approved or Canonical (for example the six Attributes, the eighteen Skills, the modifier stacking rules).

### UQ-0003 — Legacy tag scheme vs. approval statuses

- **Status:** Unresolved

The original vault used `status/idea`, `draft`, `review`, `playtest`, `final`, `archive` ([legacy-tag-scheme.md](../project/legacy-tag-scheme.md)). CLAUDE.md §6 defines a different set. Should the legacy scheme be retired, mapped, or kept? Its `rules/` topic list is currently used as the roadmap of planned areas.

### UQ-0004 — System name

- **Status:** Resolved 2026-11-25 by [DEC-0003](design-decisions.md#dec-0003--project-and-rules-system-naming)

The project is Wild Wasteland; the imported rules called themselves "Fallout 2d10". Which name should rules text use? **Answer:** the rules system is the 2d10 Engine.

### UQ-0005 — Derived Statistics formulas

- **Status:** Unresolved

The glossary references Health Points, Pace, Parry, Damage Threshold, Radiation Points, and Action Points, but no formulas exist. Which statistics are derived, and from which Traits?

### UQ-0006 — Parry as a defensive DC

- **Status:** Unresolved
- **Related Issue:** [ISSUE-0003](../project/known-issues.md#issue-0003--parry-sets-the-attackers-dc)

The glossary says Parry sets the DC an attacker must meet, but the DC formula uses the attacker's own ratings. How do defended attacks work?

### UQ-0007 — Progression mechanics beyond Levels and Ranks

- **Status:** Unresolved
- **Affected Rules:** [character-progression.md](../rules/character-progression.md)

DEC-0005 approved Character Levels 1–20 and five Ranks only. The owner has reserved all of the following, each needing its own approval: Experience Points and advancement requirements, Rank-specific benefits, Rank-based restrictions, Attribute advancement, Skill advancement, Perk prerequisites, Rank-based equipment restrictions, and Rank-based mechanical modifiers.
