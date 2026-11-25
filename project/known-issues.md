# Known Issues

### ISSUE-0001 — Check roll direction conflict

- **Status:** Open
- **Severity:** Critical
- **Affected Rules:** action-resolution.md (Difficulty Class), glossary.md (Success, Failure, Difficulty Class)
- **Discovered:** 2026-11-25

#### Description
The DC is built from the actor's own Attribute and Skill ratings, which implies rolling at or under it. The glossary says success "meets or exceeds" the DC, which implies rolling over it.

#### Mechanical Impact
Under the glossary reading, better-trained characters succeed less often. Checks cannot be resolved until this is settled.

#### Example
Attribute + Skill = DC 14. Roll-under: 79% success. Meet-or-exceed: 28% success.

#### Proposed Resolution
See [UQ-0001](../design/unresolved-questions.md#uq-0001--check-roll-direction).

#### Approval Status
Not approved.

#### Verification
None yet.

### ISSUE-0002 — "How to resolve a Check" is empty

- **Status:** Open
- **Severity:** High
- **Affected Rules:** action-resolution.md
- **Discovered:** 2026-11-25

#### Description
The section heading exists with no content. Blocked by ISSUE-0001.

#### Approval Status
Not approved.

### ISSUE-0003 — Parry sets the attacker's DC

- **Status:** Open
- **Severity:** Medium
- **Affected Rules:** glossary.md (Parry), action-resolution.md
- **Discovered:** 2026-11-25

#### Description
Parry is described as setting the DC an attacker must meet, but the DC formula uses the attacker's own ratings. See [UQ-0006](../design/unresolved-questions.md#uq-0006--parry-as-a-defensive-dc).

#### Approval Status
Not approved.

### ISSUE-0004 — Glossary definitions that need correcting

- **Status:** Open
- **Severity:** Medium
- **Affected Rules:** glossary.md
- **Discovered:** 2026-11-25

#### Description
- **Check** is defined only as an Attribute check, and the definition is circular. action-resolution.md combines Attribute and Skill.
- **Critical Success** says "A natural result of 20 is noted in the scanned draft", which reads as a transcription note, not a rule.
- **Duration** refers to "Condition" while the glossary defines "Status Effect". One term should be chosen.

#### Approval Status
Not approved.

### ISSUE-0005 — Skills table column called "Derived Attribute"

- **Status:** Open
- **Severity:** Low
- **Affected Rules:** skills.md
- **Discovered:** 2026-11-25

#### Description
The column names the governing Attribute. "Derived" is already used for Derived Statistics, which may confuse readers.

#### Approval Status
Not approved.

### ISSUE-0006 — Typos in imported text

- **Status:** Open
- **Severity:** Low
- **Affected Rules:** action-resolution.md, glossary.md, attributes.md
- **Discovered:** 2026-11-25

#### Description
- action-resolution.md: "uncertian"; "The outcome affect"; "determined by combines the ratings".
- glossary.md: "Player Characetr"; "during a its turn"; "a Actor".
- attributes.md: "Defnition".

#### Proposed Resolution
Correct spelling only, no change in meaning.

#### Approval Status
Not approved. Left unchanged pending owner authorization.
