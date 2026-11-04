# Northwind Platform — Release Coordination Hub

This repository is the system of record for cross-team release readiness.
Every release build gets one generated readiness block below.

## Operational Notes
- On-call rotation: platform-team@northwind.example
- Change approval window: Tue and Thu, 14:00-16:00 UTC
- Escalate blocked P0 items to #northwind-releases within 30 minutes.

## Release Readiness — 2026.11.3
**Status:** BLOCKED
**Completed:** 6
**Outstanding:** 4
**Deferred:** 2

### Completed in this build
| Ticket | Title | Component | Severity | Owner |
| --- | --- | --- | --- | --- |
| NW-112 | Dashboard latency regression on analytics tiles | Analytics | P2 | s.lee |
| NW-118 | Invoice rounding on multi-currency orders | Billing | P1 | d.kim |
| NW-125 | Bulk import CSV encoding fallback | Data Import | P3 | r.singh |
| NW-104 | Retry failed shipment webhook deliveries | Fulfillment | P1 | a.patel |
| NW-120 | Fleet route optimizer memory leak | Routing | P0 | t.volkov |
| NW-135 | Support ticket sentiment tagging | Support | P3 | y.mori |

### Outstanding
- **NW-108** — Warehouse slotting overflow on bulk SKUs (Warehouse, P0, blocked)
- **NW-115** — SSO session expiry edge case (Identity, P1, in_progress)
- **NW-121** — Carrier rate lookup timeout (Shipping, P2, blocked)
- **NW-128** — Inventory audit export column order (Inventory, P3, in_progress)

### Deferred
- **NW-126** — Mobile push notification dedupe (Notifications, P2)
- **NW-130** — Depot handoff signature capture (Warehouse, P2)

## Archive
- 2026.11.2 — AT RISK — 2 outstanding P1 items
- 2026.11.1 — READY
