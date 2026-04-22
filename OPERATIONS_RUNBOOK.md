# StoryLand Operations Runbook

**Purpose:** Every recurring task that keeps StoryLand compliant and running, organized by cadence.
**Owners:** Jeff (primary), Candace (secondary).
**Last updated:** 2026-04-22

This is a *living document*. Update the owner and frequency as the business evolves. When you finish a recurring task, do NOT append a log — that's what STORYLAND_STATUS.md and the audit trail are for. Just check it against the cadence and move on.

---

## How to use this runbook

- The **AI routines** handle most of the reminders. If you see a task here that doesn't have a routine attached, it's on your calendar as a recurring event or it should be.
- The **compliance audit** (Monday 7:32 AM) will flag anything in this runbook that's falling behind.
- **When in doubt**, the Admin Guide Section 5 tells you how to respond to audit findings.

---

## Daily — Monday through Friday

| Time | Task | Owner | Routine |
|------|------|-------|---------|
| 6:50 AM | Read the morning briefing | Jeff | morning-briefing |
| 6:55 AM | Check BRIEFING_FLAGS.md for any RED items from Monday audit | Jeff | — |
| Before first lesson | Confirm vehicle safe — brakes, tires, fuel, signage, first-aid kit | Instructor on deck | — |
| After each lesson | Send student a lesson summary (template in Admin Guide) | Instructor | Future #6 |
| After each lesson | Log hours and skills covered in CRM | Instructor | — |
| End of day | Update STORYLAND_STATUS.md if student count / incidents / deadlines changed | Jeff | — |
| 3:45 PM | Read weekday-wrap; note anything carrying over | Jeff | weekday-wrap |
| 9:00 PM | Light evening reset | Jeff | evening-reset |

**On non-teaching days,** skip the vehicle and lesson items. Everything else still runs.

---

## Daily — Weekend

| Day | Task | Owner |
|-----|------|-------|
| Saturday morning | Respond to any enrollment inquiries from Friday night | Jeff or Candace |
| Saturday | Teaching (if booked) | Whichever instructor is on |
| Sunday 6:00 PM | Read sunday-weekly-preview — shape the coming week | Jeff |
| Sunday | Review Cal.com for availability conflicts in upcoming week | Jeff |

---

## Weekly

| Day | Task | Owner |
|-----|------|-------|
| Monday 7:32 AM | Read compliance audit, act on top 3 items, update status file | Jeff |
| Monday | Review the vehicle — interior clean, no client data left behind | Instructor |
| Tuesday | Reconcile Cal.com ↔ Stripe ↔ CRM — every paid lesson has a booking, every booking has a student | Jeff |
| Wednesday | Review Twilio / Retell call logs — listen to 1–2 random calls for quality | Jeff |
| Thursday | Review the lead pipeline — any warm lead not contacted in 7+ days gets a nudge draft | Jeff |
| Friday | Light bookkeeping pass — check Stripe deposits landed in Mercury | Jeff |
| Friday evening | Plan next week's lesson blocks, block personal time on Cal.com | Jeff + Candace |
| Weekend | One 60-minute block for strategic/admin work (not urgent) | Jeff |

---

## Monthly

*Run on the 1st, or the first business day after.*

| Task | Owner | Notes |
|------|-------|-------|
| Bookkeeping close — reconcile Stripe, Mercury, Cal.com, expenses in QuickBooks | Jeff | Before the 5th |
| Vehicle visual inspection — dual-brake, signage, tires, fluids, interior | Instructor | Log in maintenance folder |
| Review incident log for the previous month; confirm all reportable items were reported | Jeff | §84.81 retention |
| Refresh MVR on Jeff and Candace if TDLR requires it (most years it's annual, check state notice) | Jeff | IdentoGO if fingerprints also up for refresh |
| Review all student records — any approaching §84.81 5-year end? | Jeff | Retention compliance |
| Review the 10 scheduled routines — is any failing, stale, or no longer relevant? | Jeff | Scheduled sidebar |
| Review Stripe disputes & chargebacks | Jeff | Respond within window |
| Review Google Workspace users — are ex-contractors still active? | Jeff | Revoke unused access |
| Review cloud costs: Retell, Cal.com, Twilio, Mercury fees, Google, QuickBooks, Anthropic | Jeff | Target: <$400/mo at Phase 0–1 |
| Review curriculum — any TDLR guidance update this month? | Jeff | Blueprint §18 |
| Backup: Export Gmail "StoryLand" and "TDLR" labels, save to Drive /backups/YYYY-MM | Jeff | Google Takeout |
| Review Anthropic usage — routines within daily limits? | Jeff | Scheduled sidebar |
| Pay credit cards and recurring vendors | Jeff | Never let any vendor auto-cancel |

---

## Quarterly

*Run on the 1st of January, April, July, October (or first business day after).*

| Task | Owner | Notes |
|------|-------|-------|
| Quarterly financial close — hand off to CPA | Jeff | Tax-quarter estimates |
| Review all vendor contracts — any up for renewal? | Jeff | Negotiate; don't auto-renew |
| Review instructor performance — hours taught, student feedback, pass rates | Jeff (self + Candace) | |
| Review refund log — any pattern? | Jeff | Adjust intake or policy if needed |
| Review data retention — purge any voice recordings past retention window | Jeff | §84.81 floor; privacy policy ceiling |
| Audit sharing permissions in Google Drive — anything shared publicly that shouldn't be? | Jeff | |
| Password rotation on high-risk accounts: bank, Stripe, domain registrar, Google Workspace admin | Jeff | Password manager |
| Review insurance policy — coverage still appropriate? | Jeff | Call broker |
| Review pricing vs. DFW comps — Jordan, Varsity Driving Academy, A+, Coastline | Jeff | Blueprint §18 |
| Review the Admin Guide and Runbook — anything stale? Update it | Jeff | Changelog entry |
| Prepare for TDLR renewal cycle if within 90 days | Jeff | Calendar reminder |

---

## Annually

*Run in the months shown.*

| Month | Task | Owner | Source |
|-------|------|-------|--------|
| January | Review W-9s, 1099s for any contractor paid >$600 | Jeff + CPA | IRS |
| January | Issue 1099s by Jan 31 | Jeff + CPA | IRS |
| March | Full annual backup of entire StoryLand Drive folder to cold storage | Jeff | Backblaze or similar |
| April | Franchise tax report prep | Jeff + CPA | Texas Comptroller |
| May 15 | File Texas Franchise Tax report + PIR (Form 05-102) | Jeff | Comptroller deadline |
| Month of TDLR provider license anniversary | Renew TDLR provider license | Jeff | TDLR portal |
| Month of TDLR instructor license anniversary | Renew Jeff & Candace instructor licenses | Each instructor | TDLR portal |
| Month of bond anniversary | Renew $10,000 TDLR surety bond | Jeff | Bond broker |
| Month of commercial auto policy renewal | Renew auto insurance with driving-school endorsement | Jeff | Carrier |
| June / December | Policy review: refund, safety, privacy, data retention | Jeff | Attorney optional |
| December | Board / owner sync (just Jeff and Candace) — state of the business, next year goals | Jeff + Candace | — |
| Month 12 after provider license | TPST eligibility review — apply if volume justifies | Jeff | Tex. Transp. Code §521.1655 |
| October | Curriculum review vs. TDLR rule updates | Jeff | 16 TAC Ch. 84 |
| September | Website refresh: photos, policies, pricing | Jeff | Public-facing |

---

## Event-triggered (not on a clock — happen when triggered)

| Trigger | Response | Owner |
|---------|----------|-------|
| New student enrolls | Intake routine runs → Jeff reviews → confirmation sent | Jeff |
| Student withdraws | §84.501 refund calculation → Jeff releases refund in Stripe → status file updated | Jeff |
| Vehicle collision or near-miss | See INCIDENT_PLAYBOOK.md | Whichever instructor is present |
| TDLR correspondence received | Read within 24 hours. Attorney if audit/violation. Draft response for Jeff to send | Jeff |
| Stripe dispute / chargeback | Respond within carrier window (usually 10 days). CRM records as evidence | Jeff |
| Instructor vehicle unavailable | Notify all same-day students by SMS, offer free reschedule | On-duty instructor |
| Weather cancellation (ice, severe storm) | Notify by SMS by 6 AM. Free reschedule. Updated status in CRM | Jeff |
| Payment failure | Retry 48 hrs, then SMS, then email. Never run a lesson on unpaid block | Jeff |
| Website / booking system down | Update Google Business profile with phone number as alternate | Jeff |
| TPST application window opens | Review demand; decide to apply or defer | Jeff |
| New instructor hired (future) | Licensing paperwork → orientation → shadow lessons → solo after sign-off | Jeff |

---

## Claude routine cadence — current

| Routine | Schedule | Next build priority |
|---------|----------|---------------------|
| storyland-compliance-audit | Monday 7:32 AM | — (DONE) |
| morning-briefing (general) | Mon–Fri 6:50 AM | Augment with StoryLand block (#1) |
| Future: new-student intake | Triggered | #2 |
| Future: schedule reconciliation | Daily evening | #3 |
| Future: lead follow-up | Weekly | #5 |
| Future: after-lesson coaching notes | Triggered | #6 |
| Future: weekly TDLR digest | Friday | #7 |
| Future: incident triage | Triggered | #8 |
| Future: payment reconciliation | Weekly | #9 |
| Future: end-of-month rollup | 1st of month | #10 |

Build order per Blueprint §20.15: #4 (done) → #1 → #2 → #9 → #7 → #3 → #6 → #5 → #8 → #10.

---

## Responding to a missed recurring task

The compliance audit will flag anything slipping. When it does:

1. **Don't panic.** Recurring tasks missed by a day rarely matter. Missed by a week sometimes does. Missed by a month almost always does.
2. **Do the task.** Don't negotiate with past-you.
3. **Update STORYLAND_STATUS.md.**
4. **Ask why it slipped.** If the cadence isn't realistic, change it here. Don't let the runbook become fiction.

---

## Changelog

- **2026-04-22** — v1.0 initial. Phase 0 (pre-formation). One routine active (compliance audit).
