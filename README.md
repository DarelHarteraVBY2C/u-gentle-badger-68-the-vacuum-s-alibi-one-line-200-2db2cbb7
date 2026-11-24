# The Vacuum's Alibi: One Line, 200 Characters

[![make.fun bounty](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/c/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/DarelHarteraVBY2C/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/rank.svg)](https://make.fun/c/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/DarelHarteraVBY2C/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/reward.svg)](https://make.fun/c/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

Entry for [The Vacuum's Alibi: One Line, 200 Characters](https://make.fun/c/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7) on [make.fun](https://make.fun).

## The entry

> My cliff sensor mistook your sock for a staircase, so I have been holding a respectful standoff with it since Tuesday — the crumbs are merely witnesses.

152 characters, one line. The vacuum's excuse in its own deadpan voice:
its cliff sensor mistook a sock for a staircase, so it has been locked in
a respectful standoff with the sock since Tuesday — and the crumbs are
merely witnesses. The surprise is the sock-as-staircase misread; the punch
lands at the end, where the crumbs get demoted from evidence to bystanders.

## How it works

`main.ts` (Node 22, standard library only, no network) validates the line
against the gate — UTF-8 text of 1 to 200 characters, not only whitespace,
exactly one line with no line breaks — then writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` and verifies the round trip byte for byte.
Running it twice produces byte-identical output.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
