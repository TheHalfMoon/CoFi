# Upstream Source Lock

P00 pins the authorized donor source trees below.

| Donor | Repository | Pinned commit | Role |
|---|---|---|---|
| Meteroid | `meteroid-oss/meteroid` | `c72f3f05715a122c70e14b51e42fecd111b57e87` | Primary billing and monetization foundation |
| Lago | `getlago/lago` | `a0de065beab237f357f033c6aa92058ebd417d5c` | Billing operations, wallets, lifecycle, worker/reliability patterns |
| OpenMeter | `openmeterio/openmeter` | `cebcd9f8b9f6a1b5cf473d3bb7065450549b4240` | Metering, event ingestion, entitlement and credit architecture |
| Hyperswitch | `juspay/hyperswitch` | `d03f8547d6367fab56690e4f5043590be4935dcd` | Payment orchestration, connector abstraction, routing, retries and reconciliation |

## Import policy

The P00 import workflow archives the exact tracked source tree at each pinned SHA into an isolated path under `upstream/`. `.git` metadata, build outputs, and untracked local files are not imported. The tracked source snapshot itself is copied in full unless GitHub repository hard limits make that impossible; any such exception must fail the import and be documented before proceeding.
