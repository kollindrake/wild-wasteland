# Development Log

### 2026-11-25 — Initial import and repository setup

#### Objective
Move the existing rules (then titled "Fallout 2d10", now the 2d10 Engine) from the Obsidian vault export (`Project.zip`) into GitHub and set up the documentation required by CLAUDE.md.

#### Rules Reviewed
`core/checks.md`, `core/glossary.md`, `characters/traits.md`, `characters/derived statistics.md` (empty), vault `README.md`.

#### Approved Rules Changes
None.

#### Proposed Mechanics
None.

#### Design Decisions
DEC-0001 (GitHub Markdown as source of truth), DEC-0002 (owner guidelines adopted).

#### Mathematical and Balance Findings
2d10 distribution and doubles probabilities recorded in `design/probability-analysis.md`. Mathematical only.

#### Rules Conflicts Identified
ISSUE-0001 to ISSUE-0006 in `project/known-issues.md`. The main one is the roll-direction conflict (ISSUE-0001).

#### Unresolved Questions
UQ-0001 to UQ-0006 in `design/unresolved-questions.md`.

#### Markdown Documents Modified
All files are new. Rules text imported unchanged; `traits.md` split into `attributes.md` and `skills.md`. Empty vault folders `gamemaster/player aid` and `gamemaster/rng` could not be stored in Git and are listed on the roadmap.

#### GitHub Synchronization Status
Initial push to branch `claude/project-thread-7r5nhu`, then published as `main` at the owner's request. `main` is the working branch.

#### Recommended Next Steps
Owner decides UQ-0001 and UQ-0002, then write "How to resolve a Check".

### 2026-11-25 — Naming convention adopted

#### Objective
Apply the project owner's naming convention: Wild Wasteland (project) and 2d10 Engine (rules system).

#### Rules Reviewed
None changed. Rules index header updated.

#### Approved Rules Changes
None.

#### Proposed Mechanics
None.

#### Design Decisions
DEC-0003 (project and rules system naming).

#### Mathematical and Balance Findings
None.

#### Rules Conflicts Identified
None new. The name "2d10 Engine" does not settle UQ-0001.

#### Unresolved Questions
UQ-0004 resolved.

#### Markdown Documents Modified
CLAUDE.md, AGENTS.md, README.md, CHANGELOG.md, rules/index.md, design/design-decisions.md, design/unresolved-questions.md, design/probability-analysis.md, project/handoff.md, project/tasks.md, project/project-status.md, project/legacy-tag-scheme.md, project/development-log.md.

#### GitHub Synchronization Status
Pushed to `main`.

#### Recommended Next Steps
Owner decides UQ-0001.

### 2026-11-25 — Lowercase file names

#### Objective
Apply the owner's request for lowercase file names.

#### Rules Reviewed
None changed.

#### Approved Rules Changes
None.

#### Proposed Mechanics
None.

#### Design Decisions
DEC-0004 (lowercase, hyphenated file names inside folders).

#### Mathematical and Balance Findings
None.

#### Rules Conflicts Identified
None.

#### Unresolved Questions
No change.

#### Markdown Documents Modified
All files in `rules/`, `design/`, and `project/` renamed; links updated across the repository, including CLAUDE.md §5 and AGENTS.md. Earlier log entries keep their original wording; file names in them now point to the renamed files.

#### GitHub Synchronization Status
Pushed to `main`.

#### Recommended Next Steps
Owner decides UQ-0001.
