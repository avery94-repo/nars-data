### Roster Details
Team Name: insane players
Roster: (unknown)
NARS Rank: 453 of 506

Final Rating: 889.5
Seeded Start: 1105.5
H2H Adjustment: -216.0

Final Rating (889.5) = Seeded Start (1105.5) + H2H Adjustment (-216.0)

#### Seeded Start
Starting rating = 1100 + seed_factor x 1400
                = 1100 + 0.004 x 1400 = 1105.5

seed_factor 0.004 = 0.25 x Tier Exposure (0.014) + 0.50 x Quality Wins (0.001) + 0.25 x Opponent Network (0.001)

- Tier Exposure (Bounty Offered): best-10 age-weighted event weights, normalized by 5th-best team
- Quality Wins (Bounty Collected): beaten opponent exposure x age x event weight (LAN wins get tier-scaled bonus)
- Opponent Network: distinct opponents beaten, age x event weighted

#### Growth
Where this team's points come from and where they can grow. Projections are estimates: the decay outlook assumes no new matches are played, event weights stay as they are, and the whole field ages with the same decay. Upside gains assume current ratings.

| Horizon | Seed factor | Seeded start | Change |
| :- | -: | -: | -: |
| Now | 0.004 | 1105.5 | - |
| +30 days | 0.000 | 1100.0 | -5.5 |
| +60 days | 0.000 | 1100.0 | -5.5 |
| +90 days | 0.000 | 1100.0 | -5.5 |

Weakest lever vs the 5 teams ranked above: Opponent Network (0.001 vs 0.266 average, gap -0.265). Matching that average is worth about 92.8 seed points.

- Tier Exposure drivers: VRS-tracked 2026-04 (2026-04-28) 0.11; VRS-tracked 2026-04 (2026-04-27) 0.10; VRS-tracked 2026-04 (2026-04-26) 0.09
- Quality Wins drivers: beat Club 333 at VRS-tracked 2026-04 (2026-04-19) 0.01
- Opponent Network drivers: beat Club 333 at VRS-tracked 2026-04 (2026-04-19) 0.01

Next rung: the teams ranked directly above (projected H2H gain for one win, estimate at current ratings):

| Opponent | Rank | Rating | Gap | Projected gain |
| :- | -: | -: | -: | -: |
| GoopT | 452 | 894.4 | +4.9 | +173.2 |
| on disability | 451 | 894.8 | +5.3 | +164.0 |
| Friendly Fire | 450 | 895.4 | +5.9 | +164.2 |
| Baja Blasters | 449 | 903.6 | +14.1 | +166.7 |
| Team Deathgrip | 448 | 904.1 | +14.6 | +169.7 |

Realistic stretch targets (higher rated opponents within 350 points, ranked by expected value of playing them; win probability from the engine at current ratings):

| Opponent | Rank | Gap | Win gain | Expected value |
| :- | -: | -: | -: | -: |
| fiveB | 318 | +349.0 | +325.2 | +32.5 |
| Team TahMeow | 321 | +346.2 | +324.6 | +32.3 |
| innerFire | 325 | +334.7 | +306.8 | +31.6 |
| Transcended | 326 | +333.8 | +308.1 | +31.4 |
| Double Dink | 329 | +331.1 | +290.1 | +31.1 |
| NetanYAHOO | 323 | +337.8 | +357.6 | +30.4 |
| PogSquad | 327 | +333.0 | +344.0 | +30.4 |
| Relativity | 316 | +349.3 | +288.6 | +29.7 |
| Brobies | 330 | +325.9 | +354.2 | +29.3 |
| MONARCH | 337 | +311.3 | +324.2 | +28.1 |

Ceiling reference only: beating the current number 1 team, Liquid, projects to +641.2 points at current ratings.

Seed inputs expiring within 90 days:
- VRS-tracked 2026-04 vs Club 333 (2026-04-19): expires in 1 days [Tier Exposure 0.01, Quality Wins 0.01, Opponent Network 0.01]
- VRS-tracked 2026-04 (2026-04-26): expires in 8 days [Tier Exposure 0.09]
- VRS-tracked 2026-04 (2026-04-26): expires in 8 days [Tier Exposure 0.09]
- VRS-tracked 2026-04 (2026-04-27): expires in 9 days [Tier Exposure 0.10]
- VRS-tracked 2026-04 (2026-04-28): expires in 10 days [Tier Exposure 0.11]

#### Matches (5 qualifying)
Per-match values are raw inputs before best-10 filtering and normalization. H2H +/- is the Glicko-2 rating change from that match (age-weighted only).

| Date | Opponent | W/L | Score | Competition | Tier | Src | AgeW | EvtW | LANx | Exp | QW | Net | H2H +/- | Roster |
| :- | :- | :- | :- | :- | :- | :- | -: | -: | -: | -: | -: | -: | -: | :- |
| 2026-04-28 | girl kissers | L |  | VRS-tracked 2026-04 | A | vrs | 0.07 | 1.59 | 1.00 | 0.11 | 0.00 | 0.00 | -322.9 | core 3/5 |
| 2026-04-27 | Marsborne | L |  | VRS-tracked 2026-04 | A | vrs | 0.06 | 1.59 | 1.00 | 0.10 | 0.00 | 0.00 | -8.1 | core 3/5 |
| 2026-04-26 | FarmVille | L |  | VRS-tracked 2026-04 | A | vrs | 0.05 | 1.59 | 1.00 | 0.09 | 0.00 | 0.00 | -0.2 | core 3/5 |
| 2026-04-26 | Incognito | L |  | VRS-tracked 2026-04 | A | vrs | 0.05 | 1.59 | 1.00 | 0.09 | 0.00 | 0.00 | -353.1 | core 3/5 |
| 2026-04-19 | Club 333 | W |  | VRS-tracked 2026-04 | A | vrs | 0.01 | 1.59 | 1.00 | 0.01 | 0.01 | 0.01 | +468.3 | core 3/5 |

_Snapshot 2026-10-14 | NARS v2 | CC BY-SA 4.0_
