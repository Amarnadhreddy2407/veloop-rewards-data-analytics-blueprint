# VELOOP Rewards Task 01 — Assumptions & Readiness Gaps (`Proposed` / `To Be Verified`)

> **Notice:** All specifications and observations below are **Proposed** or **To Be Verified** for analytical design purposes and do not represent live VELOOP production figures or verified company metrics.

## Key Readiness Gaps (`GAP-01` to `GAP-11`)
1. **GAP-01 (Critical):** Unverified event instrumentation across frontend and backend surfaces.
2. **GAP-02 (Critical):** Task completion vs. reward credit conflation (must separate validation, pending holds, credits, and reversals).
3. **GAP-03 (High):** Standardized failure categories (`abandoned`, `validation_failed`, `tracking_failed`, `system_error`) are proposed and require verification.
4. **GAP-04 (High):** Third-party ad, survey, offer, and partner postback delays/drops require explicit pending and reversal tracking.
5. **GAP-05 (Critical):** Wallet reversals and adjustments require unique transaction IDs and parent/reference links to avoid double-counting.
6. **GAP-06 (High):** Withdrawal stage timestamps and standardized reason categories are needed for turnaround and rejection analysis.
7. **GAP-07 (High):** Referral funnel stages (*Created → Registered → Activated → Converted*) must be tracked separately.
8. **GAP-08 (Medium):** Session and user ID consistency across tables must be verified to prevent broken joins.
9. **GAP-09 (High):** UTC timestamp normalization and consistent formatting across sources.
10. **GAP-10 (High):** Early detection of duplicate IDs, orphan records, invalid transitions, and formatting inconsistencies.
11. **GAP-11 (Medium):** Strict PII minimization and exclusion of passwords, tokens, API keys, and payment credentials.