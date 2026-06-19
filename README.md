# boatstory-data

Public dataset for **Boat Story** (Team AM): marine maintenance task templates
with engine-hour and month intervals, seasonal anchors (winterize /
commission), and typical DIY-to-yard cost ranges.

- `data/boat-tasks.json` — the dataset (schema 1). 10 systems, applicability
  by boat type (outboard / sterndrive / inboard / sailboat / PWC / pontoon),
  safety items carry their real expiries (flares 42 months, EPIRB batteries
  ~60 months).
- `data/manifest.json` — version + sha256, rebuilt by CI on data changes,
  served via GitHub Pages for over-the-air app updates without a release.

## Honesty contract

Intervals are **standard marine-maintenance recommendations, not
engine-manufacturer service data**. The app presents them as such. Engine
manuals, surveyors, and local conditions (salt vs fresh, climate) take
precedence; corrections welcome via issues.

Sibling repos: [carstory-data](https://github.com/support-teamam/carstory-data) ·
[homestory-data](https://github.com/support-teamam/homestory-data)

## Disclaimer

This dataset is provided for **general informational purposes only**. The
intervals, schedules, and cost figures are **typical-case estimates** — many are
derived from generic, rule-based heuristics rather than manufacturer or expert
data, and some descriptions are produced with the help of automated (AI) tools.

It is **not** professional, medical, veterinary, or manufacturer advice. Always
verify against your owner's manual or a qualified professional before acting. The data is provided "as is", without
warranty of any kind, and you use it at your own risk. Team AM is not affiliated
with any manufacturer or brand referenced.

Full terms: https://teamam.org/terms
