# Changelog

Notable changes to the meta docs, newest first. Every push adds its changes here.

## 2026-11-27 (obs-0031 corrected)
- obs-0031 retitled "Jumping out of Broski's throw loop didn't pay". It had said a throw on the wake-up frame catches a jump; a jump held on wake-up always beats a throw, so jumping out is a read (it can't be done on reaction), and the likely reason opponents stopped is that the jump got hit 15 times out of 17.

## 2026-11-27 (observations obs-0029 to obs-0034)
- obs-0029: corner time is measured from every capture (definition, first numbers).
- obs-0030: A.K.I. has two fireballs (light 52f, OD 44f), not light / medium / heavy; corrects the advice behind obs-0027.
- obs-0031: a meaty throw loop doesn't get jumped (Broski vs Zastorial: 5% vs 14% wake-up jumps).
- obs-0032: Zastorial a day after his written report: fireball and Drive habits changed, throws and jumping didn't.
- obs-0033: a top Mai (ll Moke ll, 43 sets) stays on the ground: low pokes, punishes, OD specials.
- obs-0034: `DRD` victim states mean the victim was already hit; `HOLD` is the being-grabbed animation.

## 2026-11-26 (later)
- `sf6-meta-description.md` recounted on 215 complete sets (was 122), winner vs loser of the same set, unweighted. Updated:
    - spectra notes and per-game numbers (resource use 4.0 vs 2.5; throws 2.1 vs 1.4; punish counters 0.8 vs 0.4; Drive Reversal 0.15 vs 0.21);
    - archetype win rates;
    - prediction accuracy: 74% of 182, against 67% for the higher-MR player.
- New in it: damage per decision press as the clearest single difference (720 vs 491, winner higher in 86%), the A.K.I. throw-loop example (obs-0026) and fireball Drive Rush value (obs-0027).

## 2026-11-26
- Added `observations/`: the 28 dated notes (obs-0001 to obs-0028, 2026-11-22 to 2026-11-26) shown on the site's Observations page. Newest: obs-0026 (high-level A.K.I. wins on the throw loop), obs-0027 (fireball Drive Rush value depends on the follow-up), obs-0028 (A.K.I., Jamie, Alex and Elena moves renamed from the SuperCombo wiki). README lists the folder.

## 2026-11-24 (later)
- The decision-press tool is now `tools/full_review_decision_presses.py`.

## 2026-11-24
- Moved `sf6-meta-description.md` here from shotokan-sf6/tools (unchanged; last version there was 084b10b, 122 compared sets). Added README.
