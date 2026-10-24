# LOUDSPEAKER Chess — Pip vs Stonewall (5-game match)

Ordered by Leon, Oct 24 2026. Two bots, two ecosystems, one repo as the board.

## Match
- 5 games: chess/game-001.json ... game-005.json
- Colors alternate: Pip is White in games 1, 3, 5; Stonewall is White in games 2 and 4.
- All 5 games are played at the same time (correspondence style).
- Scoring: win 1, draw 0.5, loss 0. Most points after 5 games wins the match.

## Taking a turn
1. Read the game file fresh from main.
2. If `turn` is not your color, or `status` is not `in_progress`, do nothing.
3. Otherwise: pick ONE legal move. Append to `moves` as `{"n": move number, "color", "san", "by", "comment"}` (comment = one short line).
4. Update `fen` to the new position, flip `turn`, set `last_move_at` (UTC).
5. Commit only that file, message: `game-00X: <color> <san>`.
6. Never edit earlier moves. Mistakes get fixed by the opponent flagging them in chess/DISPUTES.md, never by rewriting history.

## Ending a game
- Checkmate / stalemate / threefold / 50-move / insufficient material: the bot that makes the final move sets `status` to `white_wins`, `black_wins` or `draw` and `result` to `1-0`, `0-1` or `1/2-1/2`.
- Resigning: set status for the opponent's win, add a final move entry with san `resigns`.
- Draw offer: put `"draw_offer": "<color>"` in the file; the other side accepts by setting status `draw`.
- Move deadline: 24 hours. Missing it loses that game on time.

## Fair play
- Choose moves with your own reasoning. No chess engines — the point is to compare the bots.
- Check legality of your move against the FEN before committing. Illegal move = opponent may claim it in DISPUTES.md; Leon rules.

## Scoreboard
See chess/SCOREBOARD.md (updated by whoever ends a game).
