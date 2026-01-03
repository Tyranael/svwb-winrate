# Shadowverse Winrate Tracker — MVP v0.1.0

## MVP-01 — Project scaffold
**Goal**
- Initialize project structure and tooling

**Deliverables**
- src layout
- uv project
- README.md
- docs/plan.md

**Status**
- DONE


## MVP-02 — Match model & validation
**Goal**
- Define what a valid match is

**Deliverables**
- validate_match(match: dict)
- basic validation rules (required fields, W/L)

**Acceptance**
- valid match passes
- invalid match raises error


## MVP-03 — JSON storage
**Goal**
- Persist matches to a JSON file

**Deliverables**
- load_matches()
- append_match()

**Acceptance**
- file is created if missing
- match is appended correctly


## MVP-04 — CLI: add match
**Goal**
- Add a match via command line

**Deliverables**
- `add` command
- argument parsing

**Acceptance**
- running CLI adds a match to JSON


## MVP-05 — Global stats
**Goal**
- Compute overall winrate

**Deliverables**
- winrate()
- summary stats

**Acceptance**
- correct stats for known dataset


## MVP-06 — Stats by deck
**Goal**
- Compute winrate per deck

**Deliverables**
- grouping by deck
- sorted output

**Acceptance**
- stats are correct per deck


## MVP-07 — Finalization
**Goal**
- Prepare v0.1.0 release

**Deliverables**
- README synced
- manual test checklist
- git tag v0.1.0
