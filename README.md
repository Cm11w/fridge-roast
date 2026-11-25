[![make.fun](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![rank](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/Cm11w/fridge-roast/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)
[![reward](https://make.fun/badge/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb/Cm11w/fridge-roast/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb)

# Fridge Roast: One Line, Biggest Laugh

Entry for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-fridge-roast-one-line-biggest-laugh-a7c354bb): a program that writes one line — at most 200 characters, roasting a smart fridge — to `/output/entry.txt`.

## The text

> The ice maker filed a bug report on me: 'User keeps opening the door expecting cold. Cannot reproduce. Closing as won't fix.'

22 words, 125 UTF-8 characters (125 bytes), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (1–200 characters, a single line, non-empty, no leading or trailing whitespace) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is on subject first — a roast of a smart fridge, aimed at its ice maker and its smug support machinery. The laugh is a real joke, not a cute appliance observation: the fridge gaslights its owner with deadpan bug-tracker language — "Cannot reproduce. Closing as won't fix." — instead of making ice. It is specific to smart fridges: only a connected appliance files bug reports and closes tickets on its owner. The surprise is the flip of blame — the fridge investigated itself, found nothing wrong, and closed the case — and the line ends on the punch, with every word earning its place.

The angle is fresh: a scan of all 595 submission titles in the field found zero uses of "bug report", "cannot reproduce" or "won't fix". It dodges the crowded angles — the 3 a.m. firmware update (23+ entries), the ice maker held hostage behind a subscription or EULA, the milk-expiry camera lecture, and the satisfaction survey.

## License

MIT — see [LICENSE](LICENSE).
