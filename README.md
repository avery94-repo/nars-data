# NARS Data

Public data feed for the **North American Regional Standings (NARS)** — a
community ranking of North American Counter-Strike teams, updated automatically
after every recompute.

## Files

| File | Contents |
|---|---|
| `rankings.json` | Top 100 teams: rank, rating, RD, matches, wins, seed factor |
| `ratings.json` | All ranked teams (full detail) |
| `matches.json` | Recent matches (rolling 180 days) |
| `teams.json` | Team ID to name/match-count map |
| `meta.json` | Snapshot time, engine version, per-source freshness |

## Schema

`meta.json` carries `schema_version` (currently 1). Fields are additive —
new fields may appear, existing ones will not change meaning.

## Sources & license

- Match data from Liquipedia (CC BY-SA 3.0), FACEIT, HLTV (via parse.bot), and Valve's public VRS repo.
- This dataset is published under CC BY-SA 4.0.
- Liquipedia content: "Data from Liquipedia (https://liquipedia.net) (CC BY-SA 3.0)"

## Freshness

Check `meta.json` → `exported_at` for the last update and `sources` for
per-feed freshness.
