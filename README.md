# StoryLand Driving School — Folder README

**This is your map.** If you get lost in this folder, start here.

Last updated: 2026-04-22
Owner: Jeff Story (jeffstory007@gmail.com), Lewisville, TX

---

## What lives here

| File | What it is | How often you read it |
|------|------------|------------------------|
| **StoryLand_AI_Staffed_Blueprint.docx** | The 20-section strategic blueprint. The "why" and "what" of StoryLand. | Reference only. Re-read sections 17–20 quarterly. |
| **StoryLand_Admin_Guide.docx** | How you operate the AI-staffed back office, day to day. | Read start to finish once. Reference after. |
| **StoryLand_User_Guide.docx** | Customer-facing doc for students and parents. Share as PDF with new enrollments. | Review annually, update as policy changes. |
| **StoryLand_Quick_Start.docx** | One-page wall reference. Print and pin it by your desk. | Every day. |
| **OPERATIONS_RUNBOOK.md** | Every recurring task — daily, weekly, monthly, quarterly, annual, triggered. | When a new cadence starts. Compliance audit references it. |
| **INCIDENT_PLAYBOOK.md** | What to do when something goes wrong. Print a copy for each vehicle. | In an emergency. Before. During. After. |
| **STORYLAND_STATUS.md** | Live status file. Launch checklist, deadlines, student counts, risks. | Weekly at minimum. Whenever anything changes. |
| **BRIEFING_FLAGS.md** | Auto-generated when the Monday audit finds a RED item. | Whenever it appears. |

---

## First-time reading order

If you just opened this folder for the first time, read in this order:

1. **Blueprint §§1–3** — the vision, market thesis, and differentiator.
2. **Blueprint §§17–20** — safety, Lewisville reality, Day Zero playbook, and the Claude Routines operating model. This is the dense stuff.
3. **Admin Guide §§1–5** — how to operate the AI stack, the status file, and the Monday audit.
4. **Quick Start** — print it.
5. **Operations Runbook** — scan the cadences. You don't need to memorize.
6. **Incident Playbook** — read it now, before you ever need it.
7. **User Guide** — read once so you know what you're promising students.

That's ~2 hours of reading. Do it in one sitting if you can.

---

## Where the AI routines live

Scheduled tasks live in your Cowork "Scheduled" sidebar. StoryLand-specific routines are prefixed `storyland-`. Current roster:

- `storyland-compliance-audit` — Monday 7:32 AM. Regulatory and launch-progress audit against STORYLAND_STATUS.md.

The 10-routine roadmap (§20 of Blueprint) drives what gets built next. Build order: #4 ✅ → #1 → #2 → #9 → #7 → #3 → #6 → #5 → #8 → #10.

Skill definitions live under `/sessions/.claude/skills/`. You normally don't need to touch these.

---

## The two rules

1. **AI drafts, audits, reminds, schedules. Humans file, sign, pay, submit.** No exceptions.
2. **STORYLAND_STATUS.md is the source of truth.** If it's wrong, the audit is wrong. Keep it current.

Everything else flows from those two rules.

---

## When something doesn't make sense

- **Lost in a doc** — read this README.
- **Lost in the system** — read the Admin Guide §2 (the AI stack).
- **An audit finding looks wrong** — Admin Guide §10.4. It's usually a stale status file.
- **Something actually broke** — Admin Guide §10. If a routine won't run, pause it and ask Claude to rebuild from Blueprint §20.
- **Something actually went wrong in the world** — INCIDENT_PLAYBOOK.md.
- **You want to change how things work** — update the Runbook, update the status file, or rewrite the relevant routine. Log the change in the Admin Guide changelog.

---

## Version history

- **v1.0 — 2026-04-22** — Initial release. Phase 0 pre-formation. Blueprint, three guides, two runbooks, status file, one compliance audit routine.
