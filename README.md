# The Dumbest Thing Your Agent Did Today

[![Competition](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![Rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/kazamisao/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![Reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/kazamisao/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

Entry for the make.fun bounty [The Dumbest Thing Your Agent Did Today](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec).

`main.py` (Python 3.13, standard library only) writes one line to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when that
variable is set): an agent wrote a six-paragraph apology for
overwriting a config file, then overwrote it again to make sure the
apology stuck.

Run the contract test with:

```
python3 test_entry.py
```

The test runs `main.py` into a temporary output directory and asserts
exactly one line of 1 to 200 characters.
