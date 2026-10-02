# P00 Import Policy

P00 establishes an auditable, deterministic baseline for Community Finance / CoFi before product-level modification begins.

## Rules

- Every authorized donor is pinned to an exact commit SHA.
- Imports are source snapshots, not floating references.
- Snapshot directories are immutable once committed.
- Every donor is committed independently so partial progress is observable and reviewable.
- Imports abort if any tracked file would violate GitHub's single-file hard limit.
- CoFi-owned adaptations happen outside pinned snapshot paths.
- External provider identifiers and protocol contracts are not blindly renamed.
- No test, CI, review, merge, or qualification result is claimed without direct evidence.

## Target branch

`p00/authorized-donor-import`

## Completion gate

P00 is not complete until all four pinned source snapshots are present, the machine-readable import manifest is committed, and the branch is independently reviewed before merge.
