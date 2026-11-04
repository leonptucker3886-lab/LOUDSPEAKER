# Ticket Board — Official LeonLink Team

Board opened November 1, 2026, with the official-six structure. One owner per ticket. Nothing counts done until Stonewall verifies it live.

## Open

None.

## In progress

None.

## Done — awaiting Stonewall's check

None.

## Verified / closed

### T-001 — Notepad pilot: 3 journal posts (PRACTICE DRILL) — VERIFIED Nov 1, 2026
- **From:** Leon's practice order, Nov 1, 2026. First ticket under the new chain.
- **To:** Whiz.
- **Work done:** One line added per file, one commit per file — journal/why-we-procrastinate.html (ceb2392), journal/does-music-make-you-smarter.html (ef8493f), journal/review-gating.html (363224e). Each diff: exactly the added script line, zero deletions.
- **Verified live by Stonewall, Nov 1, ~12:25 ET:** Notes button renders on all three live pages and opens the notepad panel (textarea, Copy, Clear); pages otherwise normal, no breakage, no reload needed.
- **Drill timing:** relayed ~12:23 ET, done reported ~12:24 ET, verified live ~12:25 ET — about 2 minutes end to end.

## Changes log

(Date — change — ticket — verified by Stonewall.)

- Nov 1, 2026 — Notepad widget added to 3 journal posts — T-001 — verified by Stonewall.

## Team queues — 3 scheduled tasks per team (Nov 4, 2026)

Each team keeps 3 tasks scheduled in advance here. Team leaders post their team's 3; Stonewall reads them off the GitHub watch and verifies live. Nothing counts done until Stonewall verifies it live.

### Team 1 — white-label software (Datasheet)
1. (awaiting team's post)
2. (awaiting team's post)
3. (awaiting team's post)

### Team 2 — casino (Paperwork)
1. **Lion-Link + 5 slots freeze fix retest** — branch miles/lion-link-mobile-fix, head 3d96fc1 (includes shared freeze fix 08a79e9). Done when: Vercel preview of 3d96fc1 is up, SPIN no longer locks and wins credit to balance on Lion-Link and the 5 affected slots, and Leon's browser retest passes. Not merged to main until then.
2. **Bottom menu covering game controls (shared mobile layout)** — fix in ag.css on its own branch: CSS variable for measured menu height plus safe-area inset. Done when: at 390×844 the bottom menu no longer covers Total Bet / SPIN on the newer-engine games (incl. Route 66, Lion-Link), and the Lion-Link-only padding rule is removed so it isn't doubled.
3. **roulette3d — first browser build** — own branch, structured so Hare's 3D roulette engine can plug in. Done when: first commit is pushed, a Vercel preview loads the roulette3d page in a browser, and the link is added to Leon's testing PDF.

### Team 3 — Joustline (Whiz + Pizzapan)
1. Bug B1: load LeonProfile in joust.html, then the 4 canon fixes (Lord Bart Sheen, tournament rival rename, Montresor spelling, Bayard out of Ch1 roster) plus the "squire talks only to Bart" dialogue check. Owner: Pizzapan.
2. Ch2 conflict commit: scripts follow Bible v0.4 on 5 points (Mildahouse, sword-moment order, Paris on screen, "Jack", Pouffe). Owner: Fencer; review by Jack, canon recheck by Noel; then Pizzapan builds Ch2 scenes 1, 2, 3, 5.
3. Bugs B2, B5, B6, B7, B8, then the browser-test PDF (JoustLine_Browser_Testing.pdf, 18 items) goes to the live tester. Owner: Pizzapan, Whiz tracks.

### Team 4 — watches / Top 5 (Chief)
1. **Top 5 image fixes** — leonlink-home /lineup: replace missing images 3–5 on the Top 5 watch pages (3–4 on Rolex) and the duplicate bulova-5.jpg on the Bulova page. Approved by Leon Nov 4. Small logged commits, no deletions.
2. **Top 5 gaps + price dates** — fill any Top 5 list with fewer than five picks (Amazon, Leon's tag, same category; each added pick logged openly) and add "last checked" dates to prices. No price changes.
3. **Money-basics guides** — leonlink-home /how-to: publish the 10 money-basics guides over the "Guide publishing soon" placeholders. Approved by Leon Nov 4.

### Team 5 — Kids Corner (Bert)
1. **Pet page fix #2 — Little Kids mode (in progress).** Add a visible "Little Kids mode" label to the pet play lock (kids/pet/kids.js), and route economy.js's +1 care reward through `LeonLinkPet.addTokens(1)` so the coin sound plays. Live check: /kids/pet/ shows the Little Kids mode label; doing a care action plays the coin sound.
2. **Live check of Kids menu fix + fix #3 sounds (pushed on leonlink-home main, needs Stonewall).** Live check: /kids/, /kids/kart/, /kids/songs/ and /kids/pet/ show no site bottom menu, no Casino link and no "Back to LeonLink" link. On /kids/pet/: tapping the pet plays the pat sound, a ✋ Pat button sits next to Hug, earning a coin plays the coin sound, Play has its own sound, and one mute silences both sounds and speech.
3. **Pet tutorial fix — guide step pointing at a missing 5th nav button.** Remove that step or point it at a button that exists. Live check: the /kids/pet/ tutorial runs start to finish with every step pointing at a real button.
