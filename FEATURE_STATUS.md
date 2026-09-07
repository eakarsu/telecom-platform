# Feature status — Telecom networks & customer operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 181 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Carrier contract and tariff library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Circuit and number inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location and cost-center allocation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier invoice ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract-rate recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disconnected-service billing detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate service detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mobile zero-use analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roaming and international fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage allowance reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tax and surcharge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service-level credit calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order-to-bill reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Refund and credit ledger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Renewal and consolidation analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Porting Order | records | 1 | 0 | Native records/view |
| Porting Number | records | 1 | 0 | Native records/view |
| Authorization Letter | records | 1 | 0 | Native records/view |
| Customer Service Record | records | 1 | 0 | Native records/view |
| Carrier Submission | records | 1 | 0 | Native records/view |
| Carrier Rejection | records | 1 | 0 | Native records/view |
| Firm Order Commitment | records | 1 | 0 | Native records/view |
| Port Activation | records | 1 | 0 | Native records/view |
| Porting Exception | records | 1 | 0 | Native records/view |
| Operational Task | records | 1 | 0 | Native records/view |
| Rule Version | records | 1 | 0 | Native records/view |
| Document Requirement | records | 1 | 0 | Native records/view |
| Authorization extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CSR and order comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier rejection classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Resubmission preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activation checklist draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer status update draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Interconnect agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carrier route registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| CDR ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Prefix destination mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billable duration calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rate deck versioning | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Least-cost route validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Traffic imbalance analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality SLA credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fraud traffic exclusion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Counterparty invoice audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Net settlement reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Route carrier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Slices | records | 1 | 0 | Native records/view |
| QoS Profiles | records | 1 | 0 | Native records/view |
| Edge Locations | records | 1 | 0 | Native records/view |
| Connected Devices | records | 1 | 0 | Native records/view |
| SIM Cards | records | 1 | 0 | Native records/view |
| Traffic Policies | records | 1 | 0 | Native records/view |
| SLA Monitors | records | 1 | 0 | Native records/view |
| Bandwidth | records | 2 | 0 | Native records/view |
| Latency Profiles | records | 1 | 0 | Native records/view |
| Developer Apps | records | 1 | 0 | Native records/view |
| API Keys | records | 1 | 0 | Native records/view |
| CAMARA APIs | records | 1 | 0 | Native records/view |
| Network Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Traffic Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly Detector | records | 1 | 0 | Native records/view |
| Capacity Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Security Threat | records | 1 | 0 | Native records/view |
| Cost Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Slice Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Report | records | 1 | 0 | Native records/view |
| Auto Provisioning | records | 1 | 0 | Native records/view |
| Federation | records | 1 | 0 | Native records/view |
| Anomaly Rules | records | 1 | 0 | Native records/view |
| Usage Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Events | records | 1 | 0 | Native records/view |
| Call Quality | records | 1 | 0 | Native records/view |
| Dropped Calls | records | 1 | 0 | Native records/view |
| Plan Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proactive Issues | records | 1 | 0 | Native records/view |
| NPS Prediction | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Churn Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Outages | records | 1 | 0 | Native records/view |
| Customer Sentiment | records | 1 | 0 | Native records/view |
| Billing Disputes | records | 1 | 0 | Native records/view |
| SLA Compliance | records | 1 | 0 | Native records/view |
| Tower Performance | records | 1 | 0 | Native records/view |
| Customer 360 View | records | 1 | 0 | Native records/view |
| Proactive Care | records | 1 | 0 | Native records/view |
| NPS Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Churn Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Call Quality RCA | records | 1 | 0 | Native records/view |
| Sentiment Routing | records | 1 | 0 | Native records/view |
| Health Score | records | 1 | 0 | Native records/view |
| Plan Recommender (AI) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contact Threads | records | 1 | 0 | Native records/view |
| Billing Integrations | integration | 1 | 0 | Provider request records only |
| Customer Profiles | records | 2 | 0 | Native records/view |
| Support Tickets | records | 2 | 0 | Native records/view |
| Payment History | records | 2 | 0 | Native records/view |
| Appointments | records | 2 | 0 | Native records/view |
| Usage Tracking | records | 2 | 0 | Native records/view |
| Call Quality Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dropped Call Root Cause Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Personalized Plan Recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Proactive Issue Resolution | records | 1 | 0 | Native records/view |
| Customer Churn Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Outage Monitoring | records | 1 | 0 | Native records/view |
| Customer Sentiment Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billing Dispute Resolution | records | 1 | 0 | Native records/view |
| SLA Compliance Tracking | records | 1 | 0 | Native records/view |
| Tower Performance Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outreach campaigns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dispatch plan | records | 1 | 0 | Native records/view |
| churn early warning system with real time scoring and retention | records | 1 | 0 | Native records/view |
| sentiment driven routing escalating negative calls to specialists | records | 1 | 0 | Native records/view |
| call quality root cause analysis correlating with network customer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| dynamic plan recommendations from usage patterns account risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| composite customer health score payment satisfaction churn nps | records | 1 | 0 | Native records/view |
| automated outage notification system with sms email blast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| critical no ai endpoints for churn prediction sentiment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| conversational customer service copilot | records | 1 | 0 | Native records/view |
| retention offer optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| multi channel contact history phone sms email chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| limited billing system integrations only stub layer no | integration | 1 | 0 | Provider request records only |
| customer self service portal | records | 1 | 0 | Native records/view |
| correlation engine between network performance and satisfaction | records | 1 | 0 | Native records/view |
| webhooks for outage events | integration | 1 | 0 | Provider request records only |
| limited notifications one reference only not a full | records | 1 | 0 | Native records/view |
| Cell Tower Management | records | 1 | 0 | Native records/view |
| 5G Rollout Planning | records | 1 | 0 | Native records/view |
| Coverage Gap Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Network Load Balancing | records | 1 | 0 | Native records/view |
| Spectrum Management | records | 1 | 0 | Native records/view |
| QoS Monitoring | records | 1 | 0 | Native records/view |
| Infrastructure Cost Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Signal Interference Detection | records | 1 | 0 | Native records/view |
| Network Alarms & Alerts | records | 1 | 0 | Native records/view |
| Subscriber Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fiber Optic Routes | records | 1 | 0 | Native records/view |
| Maintenance Scheduling | records | 1 | 0 | Native records/view |
| Energy & Sustainability | records | 1 | 0 | Native records/view |
| Coverage map | records | 1 | 0 | Native records/view |
| Capacity simulator | records | 1 | 0 | Native records/view |
| Alarm correlation | records | 1 | 0 | Native records/view |
| Energy optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 5g deployment plan | records | 1 | 0 | Native records/view |
| Predictive maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Backlog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| 5g deployment planner prioritizing rollout by demand roi | records | 1 | 0 | Native records/view |
| dynamic spectrum sharing optimization across 4g 5g | records | 1 | 0 | Native records/view |
| predictive maintenance flagging equipment likely to fail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| energy efficiency scoring by pue | records | 1 | 0 | Native records/view |
| network slicing optimizer for urllc embb mmtc service | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| operator bench marking dashboard comparing peer carriers | records | 1 | 0 | Native records/view |
| all major planning functions are ai driven minimal gaps | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| conversational network planning copilot | records | 1 | 0 | Native records/view |
| ai suggested sla recovery playbooks | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| integration with network management systems ericsson nokia | integration | 1 | 0 | Provider request records only |
| real time network telemetry ingestion | records | 1 | 0 | Native records/view |
| what if scenario ui export to excel powerpoint | records | 1 | 0 | Native records/view |
| capacity roadmap planning budgeting module | records | 1 | 0 | Native records/view |
| webhooks for alarm correlation events | integration | 1 | 0 | Provider request records only |
| notification system | records | 1 | 0 | Native records/view |
| multi tenant network operator separation | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 181 feature pages were visited in the browser; 179 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 78 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

78 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
