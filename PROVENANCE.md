# Provenance

Community Finance / CoFi preserves explicit provenance for all imported donor code.

## Founder authorization

The founder has authorized CoFi to copy, modify, combine, adapt, and rebrand source code from the donor projects recorded in `UPSTREAM.md` for use in Community Finance / CoFi.

## Rules

1. Every donor snapshot is pinned to an exact upstream commit SHA.
2. Snapshot directories are treated as immutable import evidence.
3. CoFi-owned adaptations live outside pinned donor snapshot directories.
4. Genuine provider-owned identifiers, API contracts, protocol names, package names, compatibility identifiers, and third-party notices are not blindly renamed.
5. Third-party attribution and notice material present in imported sources is preserved.
6. Later donor updates require a new pinned snapshot or an explicitly reviewed integration commit; existing evidence is not rewritten.
7. CI, test, review, SHA, or qualification evidence must never be fabricated.

## Import location

Pinned source snapshots are stored under:

```text
upstream/<donor>/<commit-sha>/
```

The canonical pinned commits are listed in `UPSTREAM.md`.
