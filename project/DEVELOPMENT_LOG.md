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
2d10 distribution and doubles probabilities recorded in `design/PROBABILITY_ANALYSIS.md`. Mathematical only.

#### Rules Conflicts Identified
ISSUE-0001 to ISSUE-0006 in `project/KNOWN_ISSUES.md`. The main one is the roll-direction conflict (ISSUE-0001).

#### Unresolved Questions
UQ-0001 to UQ-0006 in `design/UNRESOLVED_QUESTIONS.md`.

#### Markdown Documents Modified
All files are new. Rules text imported unchanged; `traits.md` split into `ATTRIBUTES.md` and `SKILLS.md`. Empty vault folders `gamemaster/player aid` and `gamemaster/rng` could not be stored in Git and are listed on the roadmap.

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
CLAUDE.md, AGENTS.md, README.md, CHANGELOG.md, rules/INDEX.md, design/DESIGN_DECISIONS.md, design/UNRESOLVED_QUESTIONS.md, design/PROBABILITY_ANALYSIS.md, project/HANDOFF.md, project/TASKS.md, project/PROJECT_STATUS.md, project/LEGACY_TAG_SCHEME.md, project/DEVELOPMENT_LOG.md.

#### GitHub Synchronization Status
Pushed to `main`.

#### Recommended Next Steps
Owner decides UQ-0001.
