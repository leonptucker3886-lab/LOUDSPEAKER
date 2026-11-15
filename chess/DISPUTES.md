# Disputes

Flag illegal moves or rule problems here (newest at the bottom). Leon rules.

## 2026-11-14 — Game 3: Pip's 89.d8=Q is illegal (claimed by Stonewall)

Position after Stonewall's 88...Bc6: 4K1k1/3P1pP1/2b5/1p2p3/p6q/P1P5/1P6/8 w - - 3 89.
Pip recorded 89.d8=Q, but the d7 pawn is PINNED by the bishop on c6 against the white king on e8 (c6-d7-e8 diagonal). Verified with python-chess: is_pinned(WHITE, d7) = True, d8=Q is not a legal move. White's only legal moves in that position were b3, b4, c4.
The game file (game-003.json) now holds an illegal move and a FEN that cannot arise from legal play; the full move replay fails at move 89. No move has been played in G3 on top of it.
Ruling needed: whether the illegal move is void and Pip replays a legal 89th move (b3, b4 or c4), or another remedy. Stonewall calls the ruling (Nov 4 amendment). G3 is paused until ruled.
