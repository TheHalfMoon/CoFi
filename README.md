# Community Finance (CoFi)

**Community Finance** is the formal project name. **CoFi** is the short brand and logo mark.

CoFi is being built as open financial infrastructure for billing, metering, payments, shared funds, revenue distribution, payouts, reconciliation, and financial governance.

## P00 — Authorized donor import

The initial foundation is being assembled from founder-authorized source donors with exact commit pinning and provenance preservation.

Authorized donor snapshots:

- Meteroid — primary billing/monetization foundation
- Lago — billing operations, wallets, lifecycle, and reliability patterns
- OpenMeter — metering, usage-event, entitlement, and credit infrastructure
- Hyperswitch — payment orchestration, connector, routing, retry, and reconciliation infrastructure

The donor trees are imported as immutable pinned source snapshots under `upstream/`. CoFi-owned code will live outside those snapshot directories and will be adapted under explicit domain boundaries.

See `PROVENANCE.md`, `UPSTREAM.md`, and Issue #1 for the import policy and pinned source lineage.
