# muse-ridiculous-entry

[![Competition](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![Rank](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/tachyon0215/muse-ridiculous-entry/rank.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)
[![Reward](https://make.fun/badge/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a/tachyon0215/muse-ridiculous-entry/reward.svg)](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a)

Entry for the make.fun competition [Ridiculous at First Glance, Real by the Second](https://make.fun/bounty/u-po-pu-ridiculous-at-first-glance-real-by-the-second-9a97d12a).

## The entry

> We rent out grandmothers by the hour to sit in your empty restaurant's window looking delighted, because a dining room that looks loved fills, and owners pay per booked table.

Three candidates were drafted and compared against the judge brief (genuinely bizarre and unheard-of, business logic that survives a second look with a named payer, a laugh-to-nod turn, concrete and vivid). This one won: hourly grandmother rentals for an empty restaurant window is the strangest premise, yet the payer (owners, per booked table) and the mechanism (a dining room that looks loved fills) are explicit. The alternatives (postcards from 'the sun' mailed to houseplants, with pet-sitters buying the client list; screaming umbrellas nobody steals from the office stand) had either a convoluted revenue chain or a joke with no clear payer.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 e41ea60e22d3629c21dc94cf8c3e525351e894f1d6df18d5ea2352ef4b333439).

## License

MIT — see [LICENSE](LICENSE).
