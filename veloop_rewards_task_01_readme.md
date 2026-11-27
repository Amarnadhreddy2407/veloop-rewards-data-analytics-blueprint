# VELOOP Rewards — Data Analyst Internship (Task 01)

**Product Analytics, Data Readiness & Data Management Blueprint**

## Overview
This repository contains the project files and interactive blueprint companion for **VELOOP Rewards — Data Analyst Internship Task 01** (22–25 day project). VELOOP Rewards is an online rewards and engagement platform under development (covering user accounts, tasks/missions, daily rewards, streaks, spins, referrals, wallet transactions, and withdrawals).

Because VELOOP is still evolving and the working dataset is simulated, this project focuses on establishing reliable event boundaries, lifecycle schemas, a data dictionary, a logical data model, and analytics readiness checks rather than presenting simulated data as live company performance.

## Data Authenticity & Integrity Notice
* **Simulated / Fictional Data:** Any simulated or sample datasets referenced in this task are synthetic test datasets and **do not** represent live VELOOP users, actual earnings, withdrawals, revenue, retention, conversion rates, or real company statistics.
* **Status Classification:** Product details, events, schemas, and specifications in this blueprint are marked **Proposed** or **To Be Verified** where live production behavior has not been confirmed. Assumptions are not stated as verified facts.
* **Privacy & Security:** No passwords, API keys, payment/authentication credentials, or unnecessary personal data are included or requested.

## Blueprint Progress
* **Completed in Spreadsheet (Work Packages A–H):**
  * **WP A (`A1`, `A2_A3`, `A4`):** Product area mapping, user vs. system vs. business event distinctions, data coverage matrix, and 11 readiness gaps (`GAP-01` to `GAP-11`).
  * **WP B (`WP_B_User_Analytics`):** Core identifiers (`user_id`, `event_id`, `session_id`, `transaction_id`) and user/account lifecycle fields.
  * **WP C (`WP_C_Earning_Rewards`):** Five-stage earning lifecycle (*Discovery → Start → Completion → Validation → Reward*), task fields, proposed failure categories, reward states (`pending`, `credited`, `reversed`, `corrected`), and third-party dependencies.
  * **WP D (`WP_D_Wallet_Withdrawals`):** Wallet transaction ledger model, withdrawal lifecycle (`requested`, `processing`, `completed`, `rejected`, `reversed`), and core withdrawal KPIs.
  * **WP E (`WP_E_Referral_Engagement`):** Four-stage referral funnel (*Referral Created → User Registered → User Activated → Referral Converted*) and engagement metrics.
  * **WP F (`WP_F_Event_Tracking_Plan`):** Standardized event naming, UTC timestamp and deduplication rules, and a 30-event production tracking plan.
  * **WP G (`WP_G_Data_Dictionary`):** 78 governed fields across `Users`, `Tasks`, `Task_Activity`, `Rewards`, `Wallet_Transactions`, `Withdrawals`, `Referrals`, and `Feature_Events`.
  * **WP H (`WP_H_Logical_Data_Model`):** Primary/foreign keys, business grain, entity relationships, and logical ER blueprint.
* **Next Phases (Work Packages I–S & Final Deliverables):** KPI catalogue, simulated dataset profiling, data quality audit, quality control framework, 7-view dashboard blueprint, developer handoff, data pipeline, governance & change management, readiness scorecard, assumption register, prioritized backlog, and final consolidated report.

## Repository Files
* `index.html` — Interactive web blueprint view for static hosting (Vercel / Netlify).
* `README.md` — Project overview, authenticity notice, progress summary, and roadmap.
* `assumptions_and_gaps.md` — Key readiness gaps and items marked `Proposed` or `To Be Verified`.