# How accurate are AI IELTS Speaking scores? A small open check

An open dataset: 9 IELTS Speaking samples that have a band published by IELTS or by an examiner, each scored twice by the Kahoyo AI examiner (18 scores in all).

**Result:** 17 of 18 scores were within half a band of the published band. The average gap was 0.33 of a band and the worst was 1 band.

This is a small, self-run check, not an independent study. The bands are an AI estimate, not an official IELTS result. Method, limits and the full write-up: https://kahoyo.com/accuracy

## The samples

| # | Source | Part | Published band | Kahoyo, run 1 | Kahoyo, run 2 |
|---|---|---|---|---|---|
| 1 | IELTS official sample | Part 3 | 5 | 6 | 5 |
| 2 | IELTS official sample | Part 3 | 6 | 6 | 6 |
| 3 | IELTS official sample | Part 2 | 6.5 | 6.5 | 6 |
| 4 | IELTS official sample | Part 3 | 7 | 7 | 7.5 |
| 5 | examiner's published sample | Full test | 7.5 | 7 | 7 |
| 6 | IELTS official sample | Part 3 | 7.5 | 7 | 7 |
| 7 | IELTS official sample | Part 3 | 8 | 7.5 | 7.5 |
| 8 | examiner's published sample | Full test | 8 | 8 | 8 |
| 9 | IELTS official sample | Part 3 | 8.5 | 9 | 9 |

Sources of the published bands are in `samples.json` (`sourceUrl`), mainly the official IELTS scoring resources: https://ielts.org/organisations/ielts-for-organisations/understanding-ielts-scoring/resources-for-setting-your-ielts-scores

## Files

- `samples.json`: the data as published at https://kahoyo.com/accuracy/samples.json (last modified 2026-11-18)
- `samples.csv`: the same table as CSV

## Limits

- Nine samples is very few: one more sample could move every figure.
- We ran the check on our own tool. Nobody outside has repeated it yet; the data is here so that anyone can.
- The samples cover bands 5 to 8.5, not the whole scale.

## Licence and credit

Data: CC BY 4.0. Credit "Kahoyo (STARTAVO S.R.L.), kahoyo.com/accuracy".

Kahoyo is independent practice for the IELTS Speaking test with an AI examiner. IELTS is a registered trademark of the British Council, IDP: IELTS Australia and Cambridge University Press & Assessment, which do not sponsor or endorse Kahoyo.
