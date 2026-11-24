# SF6 Meta Agent Description

## Part 1: Profile of a consistent winner

This is the profile I'd expect from a player who wins most of their sets over time, against many opponents and characters. It isn't the most exciting player in any one game. It's the player whose bad nights still look like wins.

**Archetype:** Balanced, with a lean that fits their character (a grappler leans aggressive; a zoner leans fundamentalist). Confidence would be **High** after a couple of sets, because the signs stay the same from set to set.

### Spectra (1-5)
| Spectrum | Expected score | Why |
|---|---|---|
| Temperament (defense): Impulsive ↔ Mindful | **4** | Blocks first after blockstrings and on wake-up, and acts on a delay (about 6-frame throw tech, or ~12f against staggers) instead of pressing on reversal timing. Not a 5: they still challenge with a fast button often enough that frame traps are a real risk for the attacker. (Data so far: barely separates, 3.4 vs 3.3; what separates on wake-up is the result, not how often they block.) |
| Temperament (offense): Impulsive ↔ Mindful | **3-4** | Uses plus frames on purpose: frame traps when the defender mashes, staggers when they delay, and a throw when they just block. Rarely presses again into a minus situation. |
| Adaptability: Inelastic ↔ Elastic | **5** | The defining trait. Anything that got counter-hit or punished in game 1 shows up less in game 2. They also re-test it later instead of dropping it forever. (Not yet confirmed by the data: since the spectrum only counts losing plans, winners and losers both average 3.0. It counts how often a punished move is reused, not whether it kept costing, so it misses real adjustments like AZ_Young02 dropping a punished sweep.) |
| Risk tolerance: Low ↔ High | **2-3** | Wake-up reversals mainly when the reversal kills or swings the round, Drive Impact as a punish or a read rather than a habit, and few raw jumps. Takes the throw midscreen. Willing to gamble when they're losing and the gamble wins the round. |
| Initiative: Reactive ↔ Proactive | **3** | Walks forward and claims space, but doesn't run into pokes. Lets the opponent make the first mistake at the edge of their range, then punishes it. (Data so far: even, 3.0 vs 3.0 over 122 sets; it was 2.7 vs 3.1 at 69 sets. Who starts exchanges doesn't decide sets; what each press earns does.) |
| Composure: Steady ↔ Tilts | **1** | Plays the same after a 3,000 combo or a lost round. Losing round 1 doesn't change their risk-taking; the information from it does. |
| Variety: Scripted ↔ Mixed | **3-4** | Has a default for each common situation (a "checkpoint"), and mixes it when the opponent shows they've learned it. Mixed enough to stay unpredictable, but not random. |
| Resource use: Conservative ↔ Spendthrift | **4** | Spends Drive where it pays (a hit-confirmed Drive Rush cancel, a corner carry, a burnout that ends the round) and keeps enough back to defend. Rarely ends a round with a full super gauge. (Revised from 3: set winners average 3.9 to the loser's 2.2 and score higher in 86% of sets, the widest gap of any measure. They spend more, but on hits: 1.9 combo Drive Rush cancels a game to 1.0, and more cheap raw Drive Rushes (3.4 vs 2.6), while pressure cancels on block are even.) |

### What their games look like
- **Damage taken** comes mostly from honest 50/50s and lost neutral exchanges, not from pressing in pressure, jumping into anti-airs or blocked reversals.
- **Damage dealt** comes from whiff punishes, punish counters on unsafe moves, and conversions from checkpoints (Drive Rush jab, plus-on-block strings, knockdowns).
- **Anti-airs:** close to every jump in their reach. Opponents learn to stop jumping by game 2. (Across sets this separates winners less than expected, 1.2 vs 1.0 a game, because it depends on how much the matchup jumps. In a matchup built on jumps it can decide the set: Cheez's Juri landed 33 Tensenrin anti-airs to the opponents' 9 over ten sets.)
- **Drive:** they spend it on hits and keep it out of gapped blockstrings. Burnouts on their own don't separate winners from losers (0.40 vs 0.38 a game once a burnout spent on a combo that kills isn't counted); what the Drive bought does. They use Drive Reversal less: losers use it about twice as often (0.21 vs 0.11 a game), though most sets have none.
- **Punishes:** max or near-max punishes on blocked DPs and heavy specials, and few missed punishes. Winners land about twice the punish counters (0.8 vs 0.4 a game) and more counter hits (5.9 vs 4.7).
- **Throws:** a throw in the default offense. Winners throw 2.0 times a game to the loser's 1.3 (higher in 74% of sets). When a throw-led player stops throwing, their offense shrinks to whatever the opponent is ready for (AZ_Young02 vs PepsiHeart: 15 throws in games 1-4 went 3-1, none in games 5-7 went 0-3, 5 in games 8-9 went 2-0).
- **Defense:** they don't hold block more often than losers (23% vs 21% after a blocked string, 20% vs 21% on wake-up), but they take less of their damage on wake-up (11% of damage taken vs 14%). The difference is the wake-up option they pick, not how often they block.
- **Matchup rules:** some characters change what defense costs. Arjun's blocked pressure leaves white (recoverable) health that his next hit cashes in: 24-36% of his damage came that way in every reviewed Arjun set. Damage in the data counts that white health (since 23 Nov 2026).
- **Adaptation:** when they lose a game, the next game shows a specific change (e.g. "stopped teching, started back-jumping in the corner"), tagged *New* or *Improved*.
- **Comebacks:** they come back from 0-1 often, because they treat the first game as information.

### What the data says so far
From 122 complete reviewed sets (winner vs loser of the same set, MR-weighted, as of 23 Nov 2026; most sets include .shog, so treat small gaps as hints):
- **Archetype:** Balanced wins 58% of its player-sets (59% MR-weighted), Aggressive 49% (53%), Defensive 1 of 7.
- **Clearest differences:** Resource use (3.9 vs 2.2, winner higher in 86%), combo Drive Rush cancels (72%), throws (74%), counter hits and punish counters (68% each), raw Drive Rush (62%), less damage taken on wake-up, and fewer Drive Reversals.
- **No difference:** pressure Drive Rush cancels, burnouts, throw techs, holding block after a string or on wake-up, Initiative, and decision presses per round. Perfect parries lean slightly to winners (59%).
- **Decision presses** (where players press, with what, and what happens; `tools/decision_presses.py`): about a third of decision presses land and about one in six gets the presser hit, for every player measured so far. Players differ in where they press, not in how well. Among three Cammy players (.shog ~1700, Coosco ~1880, RobTV ~1940): 2MP as a mid-range check got .shog hit 28% of the time; pressing on the first free frame after blocking was 17% for .shog vs 8% for RobTV; oki throws landed 90% for RobTV and Coosco, who throw on 11-19% of oki presses to .shog's 6%.
- **Economy of buttons:** every player measured takes 45-50% of a set's decision presses, so the share alone doesn't predict much. What separates them is damage per decision press against the opponent's (.shog 650 vs 494; Cheez 695 vs 490; jueks 601 vs 392) and who wins the Drive war (Heretic: 0 burnouts, opponents 0.21 a round).
- **Predictions:** blind pre-set predictions picked the winner in 72% of 92 sets (84-100% at Medium and High confidence), about the same as picking the higher-MR player (76%). They help more with the deciding factors than with the winner.
- **Measures to fix:** Composure reads the wrong way (winners score as tilting more, 2.8 vs 2.4, likely because they have more to do after a big combo) and Adaptability doesn't yet see whether a reused move kept costing.
- **Round openers:** in ranked, .shog's opponents land the first hit in 61% of rounds (49% across all his sets), but the first hit alone isn't decisive; the counter-hit openers on a mid-range button are the expensive ones.
The live numbers are on SHOTOKAN Web's What winning players do page; this section is updated as the data grows.

### Their weaknesses (none are huge)
- Can be slow to start, giving away the first round while they collect information.
- A very fast-paced opponent with a strong, unusual gimmick can steal a game before the adjustment comes.
- Mindful defense can be farmed by an opponent who throws more than average, until they adjust (and they do).

### How to beat them
Don't try to out-guess them; they want to play the guessing game. Change what you do before they adjust. Take the round leads early, keep your own Drive high, and play the matchup's fundamentals well enough that their extra information doesn't matter.

---

## Part 2: How Street Fighter plays

Street Fighter is a game of **space, time and information**. Two players stand on a line, and each character's normal moves cover a part of it. Each move has startup (frames before it can hit), active frames (when it can hit) and recovery (frames before you can act again). Most of a match happens at the range just outside where those moves hit. This is the "footsies" range: each player walks forward and back, sticks out pokes, and waits for the other to commit. Walking forward beats a player who is waiting to whiff punish. A poke beats a player who walks forward. A whiff punish beats a player who sticks out a poke. Nobody wins this triangle every time, so neutral is mostly about reading what the opponent is about to do, and spacing yourself so their likely action fails.

When one player lands a hit or a knockdown, the game shifts from neutral to **offense and defense**. The attacker is usually "plus" on the frame meter, so they get to act first. They mix up four things: hitting (low, overhead, or a frame trap that catches a button), throwing (which beats blocking), waiting (a shimmy that baits a throw tech or a button) and moving. The defender has their own set: block, tech the throw, jump out, press a fast button, use an invincible reversal, or spend meter on a Drive Reversal or Drive Parry. Every defensive option loses to something. The skill is choosing the option whose worst case you can afford, given both players' health, Drive, super, screen position and the score. Taking a throw midscreen is often the right answer. Teching a throw that turns out to be a shimmy can cost a third of your life.

Street Fighter 6 adds a shared resource on top of this: the **Drive gauge**. Six bars fund Drive Rush (a burst forward, from neutral or as a cancel off a hit or block), Drive Parry, Drive Impact (an armored attack that crumples you if you're cornered or burnt out), Drive Reversal (a guard-cancel escape) and OD (enhanced) specials. Blocking and getting hit also drain it. Running out ("burnout") is a big deal: you lose all Drive tools, take chip damage, and a blocked Drive Impact in the corner stuns you. So every round has an economy. Spending three bars on a Drive Rush cancel can turn a light hit into a corner carry. Spending them on a gapped blockstring or an unconfirmed cancel can lose you the round two exchanges later. The super gauge (three bars, Level 1-3 and the Critical Art) works the same way: a super ends a round, punishes a move that would otherwise be safe, or goes through a fireball.

The general strategy follows from all this. **Win neutral by being harder to read than your opponent:** know the ranges of your best pokes and anti-airs, walk instead of jumping, and punish what they commit to. **Turn every hit into the most you can afford:** confirm before you spend, and end combos in the knockdown or corner that gives you the next mixup. **On offense, start with the safest option that covers the most** (usually a throw or a safe string), learn how they answer it, and only then call that answer out. **On defense, default to blocking**, pick your reversals by risk and reward instead of fear, and keep enough Drive to escape. **Manage resources** so you burn out the other player, not yourself.

Above it all is **adaptation**. Characters and frame data give everyone the same options; the player decides how often to use each one. Good players gather information early (does this player mash on wake-up? tech every throw? jump when they get nervous?), then shape their offense and defense around it, while keeping the opponent from doing the same to them. That's why sets are first to two or three games, and why consistency (removing gambles, playing your character's win condition, staying calm after a bad round) beats flashy play over the long run. The player who learns faster across a set, and who makes their losses cheap, is the one who keeps winning.
