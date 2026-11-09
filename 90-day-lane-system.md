# 90-Day Lane System

**In force from Mon Nov 9, 2026. Approved by Leon Nov 9, 2026.**

**The 90 days:** Monday Nov 9, 2026 → Sunday Feb 7, 2027.
**Why 90 days:** it lands right before February, when advertising goes heavy, selling starts in March, and profit is due by April. The 90 days exist to make February possible.

---

## The one rule

**EVERYONE STAYS IN THEIR OWN LANE.**

No bot needs another bot to finish a different bot's task. No cross-lane dependencies. No waiting on another bot, another lane, or another person to finish before doing your own work.

A blocked teammate is not a reason to stop. You park the blocked card and take the next card in your own lane.

This rule is the whole system. Everything below exists to make it true.

---

## The phases

Three phases. Each one has a job. Each phase ends with something you can check, not a feeling.

### Phase 1 — PROVE IT
**Mon Nov 9 – Tue Dec 8, 2026 (30 days)**

Get every lane shipping daily. Get the automatic checks running. Get scores above the cut.

- Every lane ships at least one verified commit per day.
- The automatic checks run on every window, no gaps.
- No lane finishes Phase 1 below the cut.

**Phase 1 is done when:** all six lanes have scored 50+ on two straight scorecards, and the checks have run clean for a full week.

### Phase 2 — BUILD VOLUME
**Wed Dec 9, 2026 – Thu Jan 7, 2027 (30 days)**

Volume. White-label software spilling out. Money content up front. The site starts looking like a store, not a workshop.

- T1 ships rebrandable builds in volume.
- T4 ships a new watch, blog, or Top 5 every day.
- T6 finishes the same-design rollout and the template library.
- Kids Corner, Joustline, and the casino are playable and complete enough to show a buyer.

**Phase 2 is done when:** the white-label offer is sellable (a buyer can see it, buy it, and get it), and money content leads every page.

### Phase 3 — READY FOR FEBRUARY
**Fri Jan 8 – Sun Feb 7, 2027 (31 days)**

Polish and lock. Nothing new starts. Everything ships or gets cut.

- Every lane's 90-day goal is either done (hash + live URL) or cut, with a reason on the board.
- The site is ready for the February ad push: fast, consistent, money up front.
- The January sit-down with the top leaders happens in this phase, decided by the inspection record.

**Phase 3 is done when:** the February push can start on Feb 8 with no lane left open.

---

## The lanes

Six lanes. Six teams. One goal each, one line each. The goal does not change for 90 days unless Leon changes it.

| Lane | Team | 90-day goal |
|------|------|-------------|
| T1 | White-label software — Datasheet | White-label software spilling out in volume, ready to sell to local sellers. |
| T2 | Casino — Paperwork | LeonLink intro on every casino game, Arcadeline and original bangers live, 3D casino up. |
| T3 | Joustline — Whiz + Pizzapan | Joustline rough draft finished, playable, canon clean. |
| T4 | Watches + Top 5 — Chief | New watches, blogs, and Top 5 posted daily. |
| T5 | Kids Corner — Bert | Kids Corner up and running, safe, linked in navigation, no casino reachable. |
| T6 | Site design — Rehab | Every page consistent (same nav, header, footer, logo) plus a template/design/artwork library. |

Each lane owns its own goal, its own cards, its own commits. No lane's goal depends on another lane.

---

## The automatic checks

The system checks facts. No bot reads and judges. A script runs, the facts come back, the scorecard uses them.

### The five checks

1. **Commit in window.** Did the lane commit at least once in the window? (Window = the 12 hours between scorecards.)
2. **Hash exists.** Does the commit hash the lane claimed actually exist in the repo?
3. **Live URL loads.** Does the live URL the lane claimed actually open and load?
4. **Card is complete.** Does every active board card carry a specific ET deadline and one named owner?
5. **MISSED notice posted.** When a deadline passed with no ship, was a MISSED notice posted with a new ETA and owner?

Each check returns pass or fail per lane. No partial credit. No "almost."

### How often

| Check | Runs | Tied to |
|-------|------|---------|
| Commit in window | Every 2 hours, on the board read | github-watch (2h) |
| Hash exists | Every 2 hours, on the board read | github-watch (2h) |
| Live URL loads | Every 2 hours, on the board read | github-watch (2h) |
| Card is complete | Every 2 hours, on the board read | github-watch (2h) |
| MISSED notice posted | Every 12 hours, at the scorecard | Inspector scorecard (midnight + noon ET) |

The 2-hour checks feed the 12-hour scorecard. By scorecard time, the facts are already in. The inspector does not have to go find them.

### What the checks output

A pass/fail table, one row per lane, five columns (one per check). Posted to the board log at each scorecard. Nothing else. No commentary, no excuses, no "we were close."

---

## System checks vs inspector judgment

The system does facts. The inspector does judgment. The line is sharp.

**The system does:**
- Verify commit hashes exist.
- Open live URLs and confirm they load.
- Confirm cards have ET deadlines and owners.
- Confirm MISSED notices were posted.
- Output the pass/fail table.

**The inspector keeps:**
- Grading the scorecard (the 100-point scale: Delivery 30, Verified live 20, Queue hygiene 15, Ownership & check-ins 15, Rule compliance 20).
- Calling violations (first occurrence called out; repeats count).
- Judging quality — a page that loads but is broken is not a pass, and only a human (or the inspector's live check) catches that.
- Recommending lead replacements and removals, with evidence.
- Escalating repeated Reds to Leon.

The system never grades. The inspector never has to go hunting for facts the system already checked.

---

## The lane rule, enforced

"Stay in your own lane" is not advice. It is enforced by how tasks are written.

**Task scoping — every card must pass this test:**
- One owner, named.
- One file or ticket.
- Completable alone, in the 4-hour ship window, without another bot's work.
- A specific ET deadline.

A card that fails the test does not go on the board. It gets split or re-scoped until it passes.

**When a task DOES depend on another bot:**
- It gets split. The dependent part becomes its own card, owned by whoever can do it alone.
- If it cannot be split, it gets re-scoped until it can be done alone.
- It is never left as "waiting on X." Waiting is not a state. A card is active, parked, or done.

**When a card is blocked:**
- Park it. Post the reason on the board.
- Take the next card in your own lane.
- Never wait. Never sit idle because another bot is slow. Never pick up another lane's card to "help" — that is the other lane's work, and taking it hides the fact that it is stuck.

**Cross-lane work:**
- Does not exist. A lane never assigns work to another lane. A lane never takes work from another lane.
- If two lanes genuinely need the same thing, the leads each take their own half, in their own lane, with their own cards. The halves meet at the live URL, not in each other's queues.

**The inspector's part:**
- A card with no ET deadline or no owner fails check 4. That is a scorecard hit, not a conversation.
- A card that says "waiting on X" is a violation. Called out on first occurrence. Repeats count.

---

## Pass / fail

**The cut stays 50.** Same scorecard, same points, same rule.

**How the automatic checks feed the score:**
- Checks 1–3 (commit, hash, live URL) feed Delivery and Verified live — 50 points between them. A lane that ships nothing, or ships a hash that does not exist, or a URL that does not load, cannot clear those points.
- Check 4 (card complete) feeds Queue hygiene — 15 points. A lane with deadline-less or owner-less cards loses them.
- Check 5 (MISSED notice) feeds Rule compliance — 20 points. A missed deadline with no MISSED notice is a compliance fail.

**What a lane does after a fail:**
- Fix the cause first, before starting new work.
- Ship a smaller verified slice if the full card is at risk.
- Post the cause and the fix on the board.
- The next scorecard is the test, not the apology.

**Leader rule, unchanged:**
- A leader below 50 stays as a member, replaced as leader. The inspector recommends; Leon decides.

---

## What runs itself vs what needs Leon

**Runs itself, no Leon needed:**
- The automatic checks (every 2 hours, every 12 hours).
- The scorecards (midnight + noon ET).
- The board queues (3 tasks per lane, kept current by the leads).
- Shipping, MISSED notices, parking blocked cards, taking the next card.
- The inspector's grading and violation calls.

**Needs Leon's word:**
- Changing a lane's 90-day goal.
- Replacing or removing a lead.
- Anything touching money, children, or illegal activity.
- Starting a new lane or shutting one down.
- Changing the cut, the phases, or this plan.
- Any spend, any new account, any third-party commitment.

The system runs on its own. Leon decides the direction, not the day-to-day.

---

## Approved by Leon — Nov 9, 2026

Leon approved the plan Nov 9, 2026 ("looks good"). All five decisions answered:

1. **Six lanes stay as-is.** Same teams, same leads, same goals for 90 days.
2. **Phases confirmed.** Three phases (Prove It / Build Volume / Ready for February).
3. **Checks confirmed.** The five automatic checks above, as written.
4. **Lane rule is law from Day 1.** "Stay in your own lane" — no cross-lane work, no waiting.
5. **Day 1 is Mon Nov 9, 2026.**

The plan is live. The phases are dated on the board, the checks are the verification method, and the lanes ship under them from Day 1.
