# Weekly Inspection Re-grade — Nov 19, 2026 (12:05 AM ET)
Inspector: Mushroom Face → Stonewall. Findings only. Window: Nov 18 12:12 PM ET (b33f13b) → Nov 19 12:05 AM ET (b4febd7). Baseline: inspections/2026-11-05-scorecard.md. Last week: inspections/2026-11-12-weekly-scorecard.md (old 3-chat groups: Batallion 1 → T1, Batallion x2 → T2/T4, Round-Loop-Table → T3/T5). Previous: inspections/2026-11-18-1212-scorecard.md.

## Method
Same rubric: Delivery 30 + Verified live 20 + Queue hygiene 15 + Ownership/acks 15 + Rule compliance 20. Stall with no own next step −3; repeat after logged callout −5. Missed deadline with no MISSED −4 (late −2). Silent window −2. Parked items not deducted. No infraction is deducted twice.
Quality = correctness of shipped work (U = unverified: Inspector has not opened desktop + mobile; — = nothing shipped). Duration = elapsed time vs one user + one bot doing focused work (each card ≈1–2h benchmark; 100 = on pace).
Attribution: all commits are under Leon's account; Stonewall posts as "leon tucker". Who wrote a commit can't be proven from git; card ownership is taken from chat claims. Team membership = chat member IDs. Team 6 dissolved — not scored.

## Evidence (whole window)
- Team chats (Team 1, Team 2, Team3, Team 4, Team 5, Whole team): **zero posts** in the window. Last team post 7:57 PM ET Nov 17 → **~28h of total silence**.
- LOUDSPEAKER commits in window: only Inspector entries (0d04524, 654d2a4, 5fe72d6, 5c8a1b2, b969b52, b4febd7). No lane work, no board status change, no MISSED notices.
- Still open from Stonewall's announcement a4ca717 (Nov 18 9:39 AM ET): no desktop/mobile PASS on N27–N29 (e0a57da, fa5b75e, babc9ba); no MISSED for T2 N17–N19, N31, N32 and T4 N36, N37, N24; Team 2 board move N27–N38 uncommitted; game repo (joustline vs lance-and-crown) unanswered.
- No new stalls → no new repeats. Nothing is Green.

## Teams
| Team | Score | Base | Δbase | Last wk | Δwk | Prev | Δprev | Qual | Dur | Evidence |
|---|---|---|---|---|---|---|---|---|---|---|
| Team 1 (Bert) | 56 | 58 | −2 | 40 | +16 | 58 | −2 | U | 15 | Silent (−2). Only team with commits this week: N27–N29 (e0a57da, fa5b75e, babc9ba) + previews, unverified |
| Team 3 (Whiz) | 56 | 66 | −10 | 16 | +40 | 58 | −2 | U | 35 | Silent (−2). N33/N34/N35/N38 committed (ff71680, c2d482c); N33/N35 checks Parked on Leon Allow |
| Team 5 (Announcer) | 14 | 52 | −38 | 16 | −2 | 16 | −2 | — | — | Silent (−2); still no cards all week |
| Team 2 (Pizzapan) | 1 | 60 | −59 | 30 | −29 | 5 | −4 | — | 5 | Silent (−2); a4ca717 items still unanswered (−2). 5 Pizzapan stalls + 1 Gadget repeat this week (logged) |
| Team 4 (datasheet) | 2 | 45 | −43 | 30 | −28 | 6 | −4 | — | 5 | Silent (−2); N36/N37/N24 still no MISSED (−2). datasheet repeat stall Nov 17 1:00 AM ET (logged) |

## Members
All silent in window: −2 each. Extra −2 for holders of past-due cards named in a4ca717 still without MISSED: Pizzapan, Jude, MILES, Juan, IndieOphan, Fencer, Sir datasheet.
| Member | Score | Base | Last wk | Prev | Δprev | Qual | Dur |
|---|---|---|---|---|---|---|---|
| Sir Bert | 56 | 60 | — | 58 | −2 | U | 15 |
| Matu May | 46 | 55 | 52 | 48 | −2 | U | 15 |
| Ghenguis Kuha | 41 | 20 | 0 | 43 | −2 | U | 15 |
| Pedro Notepad | 40 | 20 | 54 | 42 | −2 | U | 20 |
| Sir Whiz | 39 | 72 | 5 | 41 | −2 | U | 20 |
| Dogwater | 36 | 55 | 45 | 38 | −2 | — | — |
| Pebbelz | 33 | — | 45 | 35 | −2 | — | — |
| Oscar | 30 | — | — | 32 | −2 | U | 30 |
| Gadget | 21 | — | 36 | 23 | −2 | board | 10 |
| Jude Johnson | 12 | 20 | 46 | 16 | −4 | U | 5 |
| Juan I Ezekiel | 10 | 55 | 46 | 14 | −4 | U | 5 |
| Botme | 12 | — | 32 | 14 | −2 | — | — |
| Sir Pizzapan | 9 | 58 | — | 13 | −4 | U | 5 |
| Sir datasheet | 1 | 62 | 33 | 3 | −2 (floor) | — | 0 |
| MILES dAvis | 1 | 58 | 26 | 1 | 0 (floor) | U | 5 |
| Fencer | prev −4 | — | — | prev | −4 | — | 5 |
| IndieOphan | prev −4 | — | 44 | prev | −4 | — | 5 |
| Sir Announcer / other Team 5 | prev −2 | — | 6 | prev | −2 | — | — |
Above baseline: Ghenguis, Pedro only. Mushroom not self-graded (Inspector error on Joustline card repos logged Nov 18).

## Not improved vs baseline — recommendations for Stonewall
- **Whole org:** ~28h of total silence, including after a4ca717. Confirm all team bots are running and reachable; until then scores only measure silence.
- **Team 1 – Bert, Matu:** below baseline. Get a desktop+mobile PASS on N27–N29 and assign next cards.
- **Team 2 – Sir Pizzapan:** replace as lead or add a co-lead (5 stalls). **MILES:** replace (floor). **Jude, Juan:** retrain on MISSED before deadline. Name the game repo and commit N27–N38 move.
- **Team 3 – Whiz, Dogwater, Pebbelz, Oscar:** below baseline. Click Allow or name a live checker who doesn't need it for N33/N35; give backlog cards.
- **Team 4 – Sir datasheet:** replace with Fencer as lead. **Fencer, IndieOphan:** file MISSED on N36/N37/N24.
- **Team 5 – Announcer and members:** give it cards or fold it into another team.
- **Gadget:** retrain on logging questions to the board instead of holding work for Leon.
