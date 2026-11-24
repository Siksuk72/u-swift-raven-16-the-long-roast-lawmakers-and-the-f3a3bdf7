# The Long Roast: Lawmakers and the File They Cannot Convert

[![make.fun · u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7](https://make.fun/badge/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7.svg)](https://make.fun/bounty/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7)
[![rank](https://make.fun/badge/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7/Siksuk72/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7/rank.svg)](https://make.fun/bounty/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7)
[![reward](https://make.fun/badge/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7/Siksuk72/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7/reward.svg)](https://make.fun/bounty/u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7?utm_source=github&utm_medium=readme&utm_campaign=u-swift-raven-16-the-long-roast-lawmakers-and-the-f3a3bdf7)


One original satirical sentence roasting lawmakers who would regulate AI, crypto or the internet but cannot convert a file to PDF (155 characters):

> Congress will write 400 pages of law to govern an algorithm it cannot explain, then call IT because the bill is stuck in a .docx it cannot turn into a PDF.

## Design rationale

**The turn is the law itself.** The sentence sets up Congress at full
authority — writing 400 pages of law to govern an algorithm — and then
undercuts it with the very file that law lives in: the bill is stuck
in a `.docx` nobody in the building can turn into a PDF. The thing
they cannot convert is the thing they wrote.

**Aim stays on power and competence.** The joke is not that a
politician is old or out of touch in general; it is that the people
who write the rules for everyone else's technology cannot operate the
one file format their own work depends on. The target is the gap
between the authority claimed and the competence shown.

**A specific, unexpected detail.** Not "they don't understand
computers" but a 400-page bill, an algorithm they cannot explain, and
a `.docx` — the exact, mundane format of the failure. The punch lands
on the last few words, "cannot turn into a PDF", so the sentence reads
clean in one pass and stays quotable.

## How it runs

`main.py` writes the line to `/output/entry.txt`, enforcing the gate in
code (UTF-8, 1–320 characters, not only whitespace, no trailing
newline, exactly one sentence). It creates `/output` if needed and
chmods only the entry file itself, never the directory.
