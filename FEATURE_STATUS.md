# Feature status — Documents, knowledge & meetings

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 198 pages |
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
| Clients & customers | records | 1 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 1 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 5 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 4 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| Inbox Views | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Inbox | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Drafts | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Labels | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rules | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Categories | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Priority Scorer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Meeting Extractor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Follow-up Reminder | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Template Suggester | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Spam Intelligence | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Email Prioritizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Subject Optimizer | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Inbox Digest | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sales Sequence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sla reply breach monitor | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | Native records/view |
| Source Corpora | records | 1 | 0 | Native records/view |
| Grounding Reports | records | 1 | 0 | Native records/view |
| Signatures | records | 1 | 0 | Native records/view |
| Redaction Logs | records | 1 | 0 | Native records/view |
| AI · Extract Atomic Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Ground Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Build Grounding Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Contradiction Detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Paraphrase Linker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Source Deduplicator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Entailment Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pdf viewer | records | 1 | 0 | Native records/view |
| Merkle viewer | records | 1 | 0 | Native records/view |
| Citation coverage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hallucination flag | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Source credibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Citation generate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quote verify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Numeric consistency | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim novelty | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence retrieve | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rag answer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sources | records | 1 | 0 | Native records/view |
| Document spans | records | 1 | 0 | Native records/view |
| Evidence links | records | 1 | 0 | Native records/view |
| Fact check publisher | records | 1 | 0 | Native records/view |
| Provenance graph | records | 1 | 0 | Native records/view |
| Bulk ingest | records | 1 | 0 | Native records/view |
| Source staleness monitor | records | 1 | 0 | Native records/view |
| Articles | records | 1 | 0 | Native records/view |
| Tags | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Teams | records | 1 | 0 | Native records/view |
| Bookmarks | records | 1 | 0 | Native records/view |
| AI Features | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Knowledge Graph | records | 1 | 0 | Native records/view |
| Smart Suggestions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Users | records | 2 | 0 | Native records/view |
| AI Article Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI API Documentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Search Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Outdated Content Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Translation Engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI FAQ Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Content Generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Summarizer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Writing Improver | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translator | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Q&A Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Knowledge Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Password Reset | records | 1 | 0 | Native records/view |
| Change Password | records | 1 | 0 | Native records/view |
| Sort Controls | records | 1 | 0 | Native records/view |
| CSV Export | records | 1 | 0 | Native records/view |
| PDF Export | records | 1 | 0 | Native records/view |
| Bulk Select | records | 1 | 0 | Native records/view |
| Bulk Delete | records | 1 | 0 | Native records/view |
| Bulk Update | records | 1 | 0 | Native records/view |
| Toast Notifications | records | 1 | 0 | Native records/view |
| Confirmation Dialogs | records | 1 | 0 | Native records/view |
| Error Boundaries | records | 1 | 0 | Native records/view |
| Skeleton Screens | records | 1 | 0 | Native records/view |
| Role-Based Access | records | 1 | 0 | Native records/view |
| Rate Limiting | records | 1 | 0 | Native records/view |
| Helmet Security Headers | records | 1 | 0 | Native records/view |
| Email Verification | records | 1 | 0 | Native records/view |
| Article suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Api documentation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Search optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Outdated content | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translation engine | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Faq generator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Article ownership drift | records | 1 | 0 | Native records/view |
| Translators | records | 1 | 0 | Native records/view |
| Languages | records | 1 | 0 | Native records/view |
| Glossary | records | 1 | 0 | Native records/view |
| Orders | records | 1 | 0 | Native records/view |
| Localize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Grammar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Terminology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tm | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cultural | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Seo | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Back translation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Lang detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Readability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Style transfer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Brand voice | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Subtitles | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Doc compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Client insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Translator matcher | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Glossary gen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Order optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bias check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Generate quote | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Streaming asr | records | 1 | 0 | Native records/view |
| Streaming mt | records | 1 | 0 | Native records/view |
| Streaming tts | records | 1 | 0 | Native records/view |
| Medical glossary pack | records | 1 | 0 | Native records/view |
| Legal glossary pack | records | 1 | 0 | Native records/view |
| Dialect adaptation | records | 1 | 0 | Native records/view |
| Speaker diarization | records | 1 | 0 | Native records/view |
| Terminology drift qa | records | 1 | 0 | Native records/view |
| Join Meeting | records | 1 | 0 | Native records/view |
| Recordings | records | 1 | 0 | Native records/view |
| Meetings | records | 1 | 0 | Native records/view |
| Action Items | records | 1 | 0 | Native records/view |
| Transcripts | records | 1 | 0 | Native records/view |
| Decisions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Follow-ups | records | 1 | 0 | Native records/view |
| AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Assistant | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quality Tools | records | 1 | 0 | Native records/view |
| Meeting Coach | records | 1 | 0 | Native records/view |
| Recurring Series | records | 1 | 0 | Native records/view |
| Meeting Views | records | 1 | 0 | Native records/view |
| Actions | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Topics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Follow-up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agenda | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Planner | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transcribe | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Meeting Quality Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Participant Engagement Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Decision Consensus Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Next Meeting Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Decision reversal risk | records | 1 | 0 | Native records/view |
| Plagiarism aicontent detector work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repository | records | 1 | 0 | Native records/view |
| Workflow Builder | records | 1 | 0 | Native records/view |
| Sites | records | 1 | 0 | Native records/view |
| Records | records | 1 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Finance | records | 1 | 0 | Native records/view |
| Company home | records | 1 | 0 | Native records/view |
| Folders | records | 1 | 0 | Native records/view |
| Preview | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workflow bottlenecks | records | 1 | 0 | Native records/view |
| Bulk ocr | records | 1 | 0 | Native records/view |
| Retention flag | records | 1 | 0 | Native records/view |
| Send | integration | 1 | 0 | Provider request records only |
| Security | records | 1 | 0 | Native records/view |
| Roadmap | records | 1 | 0 | Native records/view |
| Changelog | records | 1 | 0 | Native records/view |
| R force | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Army | records | 1 | 0 | Native records/view |
| Navy | records | 1 | 0 | Native records/view |
| Space force | records | 1 | 0 | Native records/view |
| Joint ops | records | 1 | 0 | Native records/view |
| Documentation | records | 1 | 0 | Native records/view |
| Api reference | records | 1 | 0 | Native records/view |
| Blog | records | 1 | 0 | Native records/view |
| Webinars | records | 1 | 0 | Native records/view |
| Case studies | records | 1 | 0 | Native records/view |
| Demo | records | 1 | 0 | Native records/view |
| Compliance | records | 1 | 0 | Native records/view |
| Accessibility | records | 1 | 0 | Native records/view |
| Cookies | records | 1 | 0 | Native records/view |
| Makepdf work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pdf reader work | records | 1 | 0 | AI question-and-answer workspace; records available as context |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 198 feature pages were visited in the browser; 196 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 99 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

99 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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
