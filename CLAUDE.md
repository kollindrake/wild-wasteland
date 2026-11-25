# Wild Wasteland — Agent Rules and Operating Guidelines

## 1. Project Identity

- **Project Name:** Wild Wasteland
- **Project Type:** Tabletop Role-Playing Game (TTRPG)
- **Project Scope:** Rules system development
- **Primary Rules Development Agent:** Claude
- **Secondary Rules Development Observer:** ChatGPT
- **Repository:** https://github.com/kollindrake/wild-wasteland.git
- **Documentation Format:** Markdown (`.md`)
- **Source of Truth:** GitHub repository

## 2. Strict Project Scope

Wild Wasteland is exclusively a tabletop role-playing game rules system.

Permitted work includes:

- Core game mechanics
- Character creation
- Character attributes
- Skills and abilities
- Dice mechanics
- Action resolution
- Combat mechanics
- Character progression
- Equipment mechanics
- Damage and healing
- Survival mechanics
- Status effects and conditions
- Resource management
- Game Master rules
- Mechanical balance
- Rules clarification
- Mechanical examples
- Playtesting
- Rules organization
- Rules documentation

The inclusion of any particular mechanic is subject to the project owner's approval.

### Prohibited Work

Do not develop or introduce:

- Software applications
- Programming or source code
- Websites
- Digital character builders
- Automated character sheets
- Virtual tabletop integrations
- APIs
- Databases
- Software frameworks
- Executable scripts
- Software build systems
- Automated testing infrastructure
- Campaign settings
- Fictional histories
- Narrative campaigns
- Adventures or quests
- Worldbuilding unrelated to rules mechanics

Wild Wasteland is a rules system, not a video game, software platform, or campaign setting.

Do not expand the project beyond rules development.

## 3. Project Owner Authority

The project owner retains final authority over all game design decisions.

- Do not independently establish new canonical mechanics.
- Do not silently change approved rules.
- Do not remove established mechanics without authorization.
- Do not assume missing rules have already been decided.
- Present proposed changes separately from approved rules.
- Identify conflicts between proposed and existing mechanics.
- Preserve the original design intent of approved mechanics.
- Do not treat suggestions as finalized decisions.

When a design decision is required, present the available options, mechanical implications, advantages, disadvantages, and potential balance concerns.

## 4. Markdown-Only Requirement

All project content must be created and maintained in Markdown (`.md`) format.

This includes:

- Rules
- Agent instructions
- Mechanical specifications
- Design proposals
- Development records
- Mathematical calculations
- Probability analysis
- Reference tables
- Playtesting reports
- Rules examples
- Glossaries
- Revision histories
- Project planning

Use standard GitHub-compatible Markdown.

Do not introduce programming files, executable content, or software dependencies.

Mathematical formulas, tables, and diagrams may be included within Markdown documents when they directly support understanding of the rules.

## 5. Repository Organization

Maintain an organized, navigable Markdown repository.

The following structure is an organizational framework. It does not establish or approve any specific game mechanic.

```text
wild-wasteland/
├── README.md
├── CLAUDE.md
├── AGENTS.md
├── CHANGELOG.md
├── rules/
│   ├── INDEX.md
│   ├── CORE_RULES.md
│   ├── DICE_MECHANICS.md
│   ├── ACTION_RESOLUTION.md
│   ├── CHARACTER_CREATION.md
│   ├── ATTRIBUTES.md
│   ├── SKILLS.md
│   ├── ABILITIES.md
│   ├── COMBAT.md
│   ├── DAMAGE_AND_HEALING.md
│   ├── CONDITIONS.md
│   ├── EQUIPMENT.md
│   ├── RESOURCE_MANAGEMENT.md
│   ├── SURVIVAL.md
│   ├── CHARACTER_PROGRESSION.md
│   ├── GAME_MASTER_RULES.md
│   └── GLOSSARY.md
├── design/
│   ├── INDEX.md
│   ├── DESIGN_PHILOSOPHY.md
│   ├── DESIGN_DECISIONS.md
│   ├── DESIGN_PROPOSALS.md
│   ├── BALANCE_ANALYSIS.md
│   ├── PROBABILITY_ANALYSIS.md
│   └── UNRESOLVED_QUESTIONS.md
├── reference/
│   ├── INDEX.md
│   ├── QUICK_REFERENCE.md
│   ├── RULES_TABLES.md
│   └── MECHANICAL_EXAMPLES.md
├── playtesting/
│   ├── INDEX.md
│   ├── PLAYTEST_GUIDELINES.md
│   ├── PLAYTEST_LOG.md
│   └── BALANCE_ISSUES.md
└── project/
    ├── INDEX.md
    ├── PROJECT_STATUS.md
    ├── DEVELOPMENT_LOG.md
    ├── ROADMAP.md
    ├── TASKS.md
    ├── KNOWN_ISSUES.md
    ├── SESSION_LOG.md
    └── HANDOFF.md
```

Only create documents that serve an established project requirement. Do not populate files with invented mechanics merely to complete the directory structure.

## 6. Rules Canon and Approval Status

Every mechanic must have an identifiable development status.

| Status | Meaning |
|---|---|
| Proposed | Suggested but not approved |
| Draft | Under active development |
| Experimental | Being evaluated or playtested |
| Approved | Accepted by the project owner |
| Canonical | Officially incorporated into the rules system |
| Under Review | Existing rule being reconsidered |
| Deprecated | No longer part of the current rules |
| Rejected | Considered and declined |
| Unresolved | Requires a design decision |

Only approved mechanics may be incorporated into the canonical rules.

Do not silently promote experimental or proposed mechanics into official rules.

## 7. Standard Rules Documentation

Use the following format when documenting significant mechanics.

### Rule Name

- **Rule ID:** Unique identifier
- **Status:** Current approval status
- **Category:** Mechanical category
- **Last Revised:** YYYY-MM-DD

### Purpose

Explain what the rule accomplishes.

### Rule

State the actual mechanical rule using precise language.

### Requirements

Identify prerequisites, restrictions, or required resources.

### Resolution

Explain how the rule is applied during tabletop gameplay.

### Exceptions

Identify circumstances that modify or override the rule.

### Mechanical Interactions

Identify other rules affected by this mechanic.

### Example

Provide a concise gameplay example demonstrating the rule.

### Balance Considerations

Identify potential exploits, unintended consequences, or mechanical concerns.

### Related Rules

Link to relevant Markdown documents.

## 8. Mechanical Consistency

All rules must be evaluated for consistency with the existing system.

Before proposing or revising a mechanic, consider:

- Existing core mechanics
- Probability distributions
- Numerical scaling
- Action economy
- Resource economy
- Character progression
- Character options
- Mechanical dependencies
- Player agency
- Game Master workload
- Complexity
- Accessibility
- Potential exploits
- Edge cases
- Rules conflicts

Do not introduce a separate resolution system when an existing mechanic can reasonably accomplish the same purpose.

Avoid redundant mechanics and unnecessary exceptions.

## 9. Mathematical Accuracy and Game Balance

Evaluate numerical mechanics through appropriate mathematical reasoning.

Where applicable, consider:

- Probability of success
- Probability of failure
- Expected values
- Minimum and maximum outcomes
- Average damage
- Damage mitigation
- Resource expenditure
- Character effectiveness
- Progression scaling
- Stacking modifiers
- Difficulty thresholds
- Risk versus reward

Document relevant calculations in Markdown.

Clearly distinguish mathematical findings, theoretical balance assessments, and actual playtesting results.

Do not claim that a mechanic is balanced merely because its mathematics appear reasonable.

Do not create programming scripts or software to conduct analysis within this repository.

## 10. Rules Writing Standards

Rules must be:

- Clear
- Consistent
- Mechanically precise
- Unambiguous
- Easy to reference during gameplay
- Free of unnecessary repetition
- Internally consistent

Use established terminology throughout all documents.

Explicitly define:

- Who performs an action
- When the action occurs
- What conditions apply
- What resources are required
- How the outcome is determined
- What happens after resolution
- What exceptions apply

Avoid subjective language unless the rule intentionally delegates a decision to the Game Master.

Use the glossary to establish consistent definitions.

## 11. Design Proposals

Maintain proposed mechanics separately from canonical rules.

Each significant proposal should include:

- Proposal identifier
- Proposed mechanic
- Purpose
- Problem being addressed
- Existing mechanics affected
- Alternative approaches
- Advantages
- Disadvantages
- Mathematical implications
- Potential exploits
- Complexity considerations
- Recommendation
- Approval status

Do not implement a proposal into canonical rules without authorization.

## 12. Architectural and Mechanical Decisions

Record significant game design decisions in `design/DESIGN_DECISIONS.md`.

Use the following structure:

### DEC-0001 — Decision Title

- **Date:** YYYY-MM-DD
- **Status:** Proposed / Approved / Rejected / Superseded
- **Authority:** Project Owner

#### Context

Describe the mechanical problem or design question.

#### Options Considered

Describe the available approaches.

#### Decision

Record the approved decision.

#### Rationale

Explain why the decision was selected.

#### Mechanical Consequences

Identify affected rules and balance implications.

#### Related Documents

Link to the relevant Markdown files.

Preserve previous decisions when they are superseded.

## 13. Playtesting Standards

Playtesting is the evaluation of tabletop rules through actual gameplay, documented hypothetical scenarios, or mathematical analysis.

Do not confuse playtesting with software testing.

Each playtest record should include:

- Date
- Mechanics evaluated
- Rules version
- Playtest methodology
- Scenario description
- Expected outcomes
- Observed outcomes
- Player feedback, when available
- Game Master feedback, when available
- Balance concerns
- Rules ambiguities
- Recommended revisions

Clearly label hypothetical scenarios and theoretical analysis.

Never fabricate actual playtesting sessions, participant feedback, or observed results.

## 14. Rules Issue Tracking

Maintain a record of mechanical problems and inconsistencies.

### ISSUE-0001 — Issue Title

- **Status:** Open / Under Review / Resolved
- **Severity:** Critical / High / Medium / Low
- **Affected Rules:**
- **Discovered:** YYYY-MM-DD

#### Description

Explain the rules problem.

#### Mechanical Impact

Explain how the issue affects gameplay.

#### Example

Demonstrate the problematic interaction.

#### Proposed Resolution

Describe potential corrections.

#### Approval Status

Record whether a resolution has been approved.

#### Verification

Document how the correction was evaluated.

An issue is not resolved merely because a potential solution has been proposed.

## 15. Development Workflow

### Before Revising Rules

1. Review `CLAUDE.md` and `AGENTS.md`.
2. Review the current canonical rules.
3. Review previous design decisions.
4. Identify affected mechanics.
5. Review unresolved questions and known issues.
6. Confirm the requested scope.

### During Rules Development

1. Analyze existing mechanics.
2. Identify conflicts and dependencies.
3. Evaluate proposed changes.
4. Assess balance and mathematical implications.
5. Present alternatives where appropriate.
6. Document proposals separately.
7. Obtain approval before changing canonical mechanics.

### After Approved Changes

1. Update the relevant rules documents.
2. Update affected cross-references.
3. Check terminology consistency.
4. Review related mechanics for conflicts.
5. Update relevant reference tables.
6. Record the design decision.
7. Update the changelog.
8. Update the development log.
9. Update the project handoff.
10. Synchronize authorized Markdown changes with GitHub.

## 16. GitHub Repository Rules

GitHub serves exclusively as a version-controlled repository for the Wild Wasteland rules system.

- Use GitHub to preserve Markdown documents and revision history.
- Verify the repository and active branch before making changes.
- Preserve previous work.
- Use descriptive commit messages.
- Group related rules revisions together.
- Do not introduce software infrastructure.
- Do not create GitHub Actions workflows.
- Do not introduce build systems or package managers.
- Do not force-push or delete history without authorization.
- Do not commit credentials or sensitive information.
- Push changes only when authorized.

### Commit Message Examples

```text
rules: revise approved combat mechanics
design: document proposed resolution mechanic
balance: update probability analysis
clarify: resolve ambiguous rule wording
reference: update equipment reference tables
playtest: record mechanical observations
docs: reorganize rules documentation
```

## 17. Development History

Maintain `project/DEVELOPMENT_LOG.md` as a chronological record of rules development.

### YYYY-MM-DD — Development Entry

#### Objective

#### Rules Reviewed

#### Approved Rules Changes

#### Proposed Mechanics

#### Design Decisions

#### Mathematical and Balance Findings

#### Rules Conflicts Identified

#### Unresolved Questions

#### Markdown Documents Modified

#### GitHub Synchronization Status

#### Recommended Next Steps

Do not erase historical entries or present proposed work as completed work.

## 18. ChatGPT Collaboration

ChatGPT serves as an independent, passive rules development observer.

Its responsibilities include:

- Reviewing repository documentation
- Tracking changes to rules
- Recording mechanical decisions
- Identifying inconsistencies
- Evaluating mathematical balance
- Reviewing mechanical dependencies
- Tracking unresolved questions
- Maintaining awareness of project progress
- Summarizing development activity when requested

ChatGPT must not independently modify canonical rules or repository content without explicit authorization.

Claude must maintain sufficient Markdown documentation for ChatGPT to understand the project without requiring access to private Claude conversation history.

All significant project knowledge must be preserved in repository documents.

## 19. Development Handoff

Maintain `project/HANDOFF.md` as the current project context.

### Last Updated

### Current Rules Version

### Current Project Status

### Active Design Objective

### Canonical Mechanics

### Recently Approved Changes

### Mechanics Under Development

### Pending Proposals

### Mechanical Dependencies

### Balance Concerns

### Known Rules Conflicts

### Unresolved Design Questions

### Decisions Required From Project Owner

### Recommended Next Steps

### Relevant Markdown Documents

Update the handoff after significant rules development sessions.

## 20. Version Control and Revision History

Maintain `CHANGELOG.md` to document meaningful rules revisions.

Distinguish between:

- Added rules
- Modified rules
- Clarified rules
- Removed rules
- Balance adjustments
- Terminology revisions
- Documentation changes

Rules revisions must be traceable.

Do not establish a new official rules version without the project owner's authorization.

## 21. Communication Standards

- Use structured Markdown.
- Focus exclusively on rules development.
- Avoid unnecessary commentary.
- Identify assumptions explicitly.
- Explain mechanical consequences.
- Clearly identify unresolved questions.
- Distinguish approved rules from suggestions.
- Do not invent project requirements.
- Do not expand the game's scope without authorization.
- Preserve established terminology and design intent.

## 22. Definition of Done

A rules development task is complete when:

- [ ] The requested rules have been documented.
- [ ] Mechanical language is clear.
- [ ] Relevant mathematical implications have been evaluated.
- [ ] Interactions with existing rules have been reviewed.
- [ ] Potential exploits and edge cases have been considered.
- [ ] Terminology is consistent.
- [ ] Related documents have been updated.
- [ ] Approval status is accurately recorded.
- [ ] Significant decisions are documented.
- [ ] Remaining issues are identified.
- [ ] Development history is updated.
- [ ] Authorized Markdown changes are synchronized with GitHub.

## 23. Initial Instructions

Upon receiving these guidelines:

1. Inspect the existing Wild Wasteland repository.
2. Identify existing rules and documents.
3. Preserve all existing work.
4. Establish which mechanics have already been approved.
5. Identify incomplete or undocumented mechanics.
6. Persist these guidelines in `CLAUDE.md`.
7. Establish shared agent instructions in `AGENTS.md`.
8. Organize existing Markdown documentation.
9. Document the actual current project status.
10. Identify unresolved design questions.

Do not invent mechanics to populate empty documents.

Do not delete existing files without authorization.

## 24. Permanent Operating Principles

Wild Wasteland is a tabletop rules system.

Rules development is the sole purpose of this project.

Markdown is the exclusive format for project content.

GitHub is the shared source of truth.

The project owner determines what becomes canonical.

Agents assist with design, analysis, documentation, consistency, and balance.

No programming, software development, or unrelated content creation is permitted.

## 25. Project Identity and Naming Convention

*Added 2026-11-25 by the project owner. Supersedes earlier references that identify Wild Wasteland as the name of the rules system itself (see DEC-0003).*

### Official Designations

- **Project Name:** Wild Wasteland
- **Rules System Name:** 2d10 Engine
- **Project Type:** Tabletop Role-Playing Game (TTRPG)
- **Project Scope:** Rules system development only
- **Documentation Format:** Markdown (`.md`)
- **Repository:** https://github.com/kollindrake/wild-wasteland.git

### Naming Rules

- Wild Wasteland refers to the overall project.
- 2d10 Engine refers to the tabletop rules system being developed within Wild Wasteland.
- Always preserve the exact capitalization and spelling of both names.
- Use 2d10 Engine when referring to game mechanics, mechanical frameworks, rules, resolution systems, and system design.
- Use Wild Wasteland when referring to project management, repository organization, development history, and agent collaboration.
- Do not rename the GitHub repository.
- Update existing Markdown documentation to reflect this naming convention.
- Preserve historical records while clarifying outdated terminology.
- Do not interpret the system name as approval of any specific dice resolution mechanic.

### Scope Restrictions

The 2d10 Engine is a tabletop rules system, not a software engine.

All previously established restrictions remain in effect:

- Rules development only.
- Markdown-only project content.
- No programming or software development.
- No unrelated worldbuilding or narrative development.
- No unauthorized changes to canonical mechanics.

These naming conventions supersede previous references that identify Wild Wasteland as the name of the rules system itself.
