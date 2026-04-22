# StoryLand Incident Playbook

**Purpose:** What to do when something goes wrong, in the order to do it.
**Owners:** Whichever instructor is present at the time of the incident. Jeff if not in the vehicle.
**Last updated:** 2026-04-22

Print this. Put a copy in each vehicle. The middle of an incident is the worst time to look up a procedure.

---

## Universal first move — the 90-second rule

For ANY incident, the first 90 seconds are the same:

1. **Safe the scene.** Hazards on. Park out of traffic if possible. Instructor brake if needed.
2. **Check for injuries.** Student first. Then yourself. Then anyone else involved.
3. **If anyone is injured or the vehicle is blocking traffic → 911.** Don't debate. Call.
4. **Do not admit fault.** Not to the student, not to other parties, not to police on-scene statements beyond facts. Facts only.
5. **Photograph everything** before anything moves if it's safe to do so — plates, positions, damage, road conditions.

Everything else flows from those first 90 seconds.

---

## 1. Vehicle collision (any severity)

### Immediate (minutes 0–30)
- Universal first move.
- If under 18, call parent/guardian now. Brief, factual: "There was a collision. Everyone is safe. I'm on scene. I'll call you with more in 20 minutes."
- Exchange insurance info with any other party. Don't discuss fault.
- File police report if there's damage >$1,000 or any injury. Texas law requires it.
- Have the student wait with you until the parent/guardian arrives — don't release them alone.

### Same day
- Call your insurance carrier's claims line. Start the claim.
- Call your attorney if the collision involved injury, another vehicle with injury, or a pedestrian/cyclist.
- Notify Jeff (if not present) immediately.
- Stop all other lessons that day. Reschedule as free rebooks.

### Next 72 hours
- Written incident report — date, time, location, conditions, vehicle state, people involved, sequence of events. Facts only, no opinions.
- Provide report to: insurance carrier, attorney, parent/guardian (if student is minor), vehicle owner's records, StoryLand records folder.
- Update STORYLAND_STATUS.md: increment incidents count, flag in notes.
- Pause the vehicle from the schedule until damage is assessed and insurance clears.

### Regulatory
- TDLR notification — required if the collision affected instruction or caused a student injury. Check 16 TAC Ch. 84 for reporting thresholds. When in doubt, notify within 30 days and document.
- If driver is a minor, their parents' insurance and yours may both be involved. Attorney coordinates.

### Do NOT
- Do not post about it publicly. Not on social, not on Google reviews.
- Do not offer refunds, settlements, or statements of fault without attorney review.
- Do not allow the student back behind the wheel the same day — even if they want to.

---

## 2. Near-miss (no contact, but scare)

- Pull over safely and pause the lesson for 5 minutes.
- Talk the student through what happened. Normalize that it happened. Name the specific skill or decision that would have prevented it.
- Decide whether to continue the lesson. If the student is shaken, end early. Free reschedule — don't bill.
- Log the near-miss in the CRM with a brief note: what happened, what you did, what to practice next.
- Update STORYLAND_STATUS.md — near-miss count and date.
- If the near-miss involved a third party who became upset (horn, gestures, following you), note vehicle info and move on. Do not engage.

Near-misses are free information. Log them. Patterns matter.

---

## 3. Medical emergency (student or third party)

- Safe the vehicle. Hazards on.
- Call 911.
- Do what you can — keep the person talking, keep them still, apply pressure to bleeding. Do not give medication.
- Call the student's emergency contact (listed in CRM).
- Wait for EMS. Provide facts. Do not speculate on cause.
- After: incident report as above. Insurance notification. Attorney if any question of contributing cause.

---

## 4. Student behavior issue during lesson

Examples: refusing to follow instruction, visibly impaired, aggressive, having a panic attack.

- Pull over safely. End the lesson.
- For panic / anxiety — calm, no judgment. Offer to drive the student home or call the parent/guardian for pickup. Reschedule as free rebook.
- For suspected impairment (alcohol, drugs, medication) — do NOT drive with them. Call the parent/guardian. If they're alone and adult, offer a rideshare and refuse to continue lessons until there's a conversation. Document in the CRM. Consider terminating enrollment if it recurs.
- For hostile or threatening behavior — pull over, end the lesson, remove yourself. Call Jeff. Call parent/guardian. Terminate enrollment and refund per §84.501. Attorney if the threat involved harm to you or the vehicle.
- Never argue. Never raise your voice. The vehicle is not a therapy space but it also isn't a battleground.

---

## 5. Mechanical failure mid-lesson

- Hazards. Pull over. Student exits on the curb side, not the traffic side.
- If on a highway — call 911, stand well away from traffic, wait for help.
- Call roadside assistance (keep number taped inside the glove box).
- Call the student's emergency contact, arrange pickup or rideshare.
- Reschedule the lesson free.
- Pause the vehicle from the schedule until repaired.
- Document the failure, the mechanic's diagnosis, and the repair cost. If the failure was a maintenance miss on our end, that's a process problem — investigate.

---

## 6. Weather / environmental cancellation

- Ice, severe storm, tornado warning, flash flood, extreme heat advisory affecting air-conditioning failure → cancel.
- SMS all same-day students by 6 AM (if morning) or 3 PM the day before (if evening).
- Use a template in the CRM so the message is consistent.
- Offer a free reschedule at the student's first available slot.
- Never penalize for weather. You paused; they rebook.
- Do not use Cal.com to "auto-cancel" — each message should be reviewed by a human before it goes out.

---

## 7. Payment dispute / chargeback

- Read the chargeback reason carefully. Note the response window (Stripe is usually 7–10 days).
- Gather evidence: booking record, signed enrollment agreement, session logs, correspondence.
- Submit through Stripe dashboard. Keep tone factual, not accusatory.
- If the student is still enrolled, pause future lessons until resolved — politely, in writing.
- If the chargeback is legitimate (you made an error or the student never took the lesson), accept and issue the refund yourself. Don't let Stripe fight it for you.
- Attorney if chargebacks pattern-repeat or exceed $500.

---

## 8. Refund request

- Student/parent emails a withdrawal or refund request.
- Acknowledge receipt within one business day. Human reply — not the AI intake.
- Calculate §84.501 pro-rata refund:
  - **Refund = amount paid − (lessons used × per-lesson rate) − enrollment fee (state-allowed max)**
- Draft a written calculation. Send to the family for review.
- Process within 30 days of the written withdrawal.
- Log in CRM. Update STORYLAND_STATUS.md refund-pending and refund-processed counters.

Do not let the AI release the refund. You release it in Stripe.

---

## 9. TDLR audit notice or complaint

- Read it fully. Note any response deadline.
- Call the attorney within 24 hours. Not email — call.
- Do not respond immediately, even if the notice implies urgency. "We are reviewing and will respond within the stated window" is the only appropriate first response, if you must say anything.
- Gather all records TDLR has asked for. Do not create new records to fit the request — provide what already exists.
- Attorney drafts the response. Jeff signs and sends.
- If the complaint is from a student or parent — do not contact them directly about it until the attorney says so.
- Document the entire process in a dated folder under /Drive/StoryLand/Legal/.

---

## 10. Data or privacy incident

Examples: laptop stolen with student records; email address list accidentally CC'd; CRM login leaked.

- Contain first — change passwords immediately for any affected account.
- Assess scope — what data, how many students, is it plaintext?
- Call attorney within 24 hours. Texas Business and Commerce Code §521 imposes breach-notification duties for PII breaches affecting 250+ Texas residents (AG notice) and requires notice to affected individuals.
- Document: what was exposed, how, when it was detected, what was done to contain.
- Notify affected students/parents in writing per attorney guidance.
- Update privacy policy and security practices to prevent recurrence.
- Do not publicize until attorney approves the messaging.

---

## 11. System outage (CRM, Cal.com, Stripe, Twilio, Retell)

- Confirm it's the vendor, not you. Check status pages.
- Update Google Business profile to note "scheduling by phone only" if the website is down.
- Post a one-line note on social if outage is long — factual, not apologetic.
- Do not refund students for delays that are neither safety-critical nor lesson-affecting. Offer a makeup if the delay made a student wait >30 min.
- Document outage duration for insurance records — recurring vendor problems may warrant switching vendors.

---

## 12. Stolen or damaged vehicle (not during a lesson)

- Police report.
- Insurance claim.
- Pause all lessons until vehicle is replaced or repaired.
- Notify all affected students — offer free rescheduling at no penalty.
- If replacement vehicle is needed, confirm it has instructor-side brake installed and signage before ANY lesson happens in it. Texas §84.42 applies the moment you teach.

---

## After any incident — the 7-day checklist

- [ ] Incident report filed and filed in /Drive/StoryLand/Incidents/YYYY-MM-DD/
- [ ] Insurance notified (if applicable)
- [ ] Attorney notified (if applicable)
- [ ] Parent/guardian / student notified (if applicable)
- [ ] TDLR notified (if reportable)
- [ ] STORYLAND_STATUS.md updated (incident count, notes)
- [ ] Next Monday compliance audit will see this
- [ ] Insurance renewal premium impact assessed at next renewal
- [ ] Root-cause review (alone or with Candace) — was this preventable?
- [ ] Any process change documented in the Admin Guide changelog?

---

## What the AI is NEVER allowed to do during an incident

- The AI does not call 911.
- The AI does not speak to law enforcement on your behalf.
- The AI does not contact parents or guardians about incidents without your approval of exact wording.
- The AI does not post or comment publicly about any incident.
- The AI does not file insurance claims, regulatory reports, or legal responses.

The AI can: draft the written incident report once you give it the facts, summarize the events, draft the parent notification for your review, and prepare attorney-ready documentation. That's it.

---

## Emergency contacts — fill in and keep current

- 911 (all emergencies)
- Jeff cell: ________________
- Candace cell: ________________
- Attorney: ________________ (keep a retained driving-education attorney on file)
- Insurance carrier claims: ________________
- Vehicle roadside assistance: ________________
- TDLR: (512) 463-6599 (general) — use only after attorney guidance
- Nearest hospital ER: ________________
- Poison Control: 1-800-222-1222

Print this page. Laminate. One copy in each vehicle glove box. One copy on your desk.
