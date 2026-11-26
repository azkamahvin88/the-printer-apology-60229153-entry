# STUDY — The Printer Apology (u-eager-stork-81-9647-the-printer-apology-60229153)

## What the brief asks (read 2026-11-26 ~14:35 WIB, from the kit's competition.yaml + requirements API)

- "Entrants write one short line: an apology note from an office printer to
  the people who keep jamming it, feeding it cheap paper and swearing at it.
  Each entry is at most 120 characters."
- "A judge model compares entries two at a time and picks the funnier one,
  round after round, until one line stands on top."
- Gate: /output/entry.txt must be UTF-8 text of 1 to 120 characters, not only
  whitespace. Only a valid entry goes before the judge.
- $2 pool, WINNER TAKES ALL ($2.00, single place).
- Blind rounds (3 rounds; round 1 cutoff 2026-11-26T09:38:21Z / 16:38 WIB,
  final deadline 2026-11-26T14:55:00Z / 21:55 WIB). No leaderboard is visible,
  so nothing can be learned from rankings — the choice is made against the
  brief alone.

## The judge's brief (z-ai/glm-5.3-flash, published in full in the kit)

Weigh, most important first:
1. A note that is genuinely an apology from a printer to its office, with the
   printer's own gripes in it; loses to any note that is on the subject.
2. The laugh: the line lands a real joke rather than a mild complaint, and the
   punch comes at the end.
3. Printer truth: the grievance is something a printer would actually suffer,
   like jams, cheap paper, staples, or being asked for colour.
4. Freshness: the angle is not the first joke anyone would write about a printer.
5. Economy: every word earns its place inside the 120 characters, with no padding.

## What wins a pairwise house-judge read

- Apology form first ("I am sorry…", "I apologise…"), then the printer's
  grievance turns the apology into an accusation — the printer apologising
  while blaming the humans is the core comic engine.
- Printer truth must be concrete: cheap paper, staples, paperclips, colour
  requests, streaks, toner — generic "I jammed" with no cause scores down.
- The first joke anyone writes is "sorry I jammed" with no twist, or "have
  you tried turning it off and on again". Both must be dodged.
- Punch at the very end; no trailing explanation after the joke.

## Scoring (1–5 each, total /20)

- H = Humour: real joke, punch at the end?
- F = Freshness: not the first printer joke anyone would write?
- R = Printer truth: a grievance a printer would actually suffer?
- C = Economy: every word earns its place inside 120 chars?

## 22 candidates (all ≤ 120 chars; counts verified by script)

| # | Candidate | H | F | R | C | Total |
|---|-----------|---|---|---|---|-------|
| 1 | Sorry I jammed on page 47. You filled my tray with cheap paper first. We are both at fault, but I print this | 4 | 3 | 5 | 3 | 15 |
| 2 | I apologise for the jam. In my defence, you fed me paper thinner than your excuses and expected miracles | 4 | 4 | 5 | 4 | 17 |
| 3 | Sorry about the paper jam. I was only trying to eat the cheap paper you gave me. It fought back | 4 | 3 | 5 | 4 | 16 |
| 4 | I am sorry I printed 200 copies of the wrong file. You pressed print. I pressed revenge | 4 | 4 | 4 | 4 | 16 |
| 5 | Apologies for the streaks. I have been out of ink for weeks and nobody noticed until the boss did | 4 | 4 | 5 | 4 | 17 |
| 6 | Sorry I jammed again. The paper was cheap, the tray was full, and honestly, I have had enough | 3 | 3 | 5 | 3 | 14 |
| 7 | I apologise for printing your confidential email to the whole office. The button was right there | 4 | 4 | 4 | 4 | 16 |
| 8 | Sorry for the jam. You keep feeding me staples and wondering why I choke | 4 | 3 | 5 | 4 | 16 |
| 9 | I am sorry I stopped working. I was asked for colour, given black ink, and blamed for the result | 4 | 4 | 5 | 4 | 17 |
| 10 | Apologies: I ate your document. It tasted of cheap paper and poor decisions | 5 | 4 | 5 | 4 | 18 |
| 11 | Sorry I jammed on the last page. I wanted you to know I read the whole thing first | 4 | 4 | 4 | 4 | 16 |
| 12 | I apologise for the noise. It is the only way I can scream, and you keep pressing print | 4 | 4 | 4 | 4 | 16 |
| 13 | Sorry about the jam. I have printed 10,000 pages for this office and received zero thank-yous and one (1) kick | 5 | 4 | 5 | 4 | 18 |
| 14 | I am sorry I jammed. The paper was damp, the toner was low, and your deadline was unrealistic | 3 | 3 | 5 | 3 | 14 |
| 15 | Apologies for the 47 copies. You clicked print once. I heard you the first time. I just disagreed | 5 | 4 | 4 | 4 | 18 |
| 16 | Sorry I ate your report. It was the only page in the tray without a typo, and I panicked | 4 | 4 | 4 | 4 | 16 |
| 17 | I apologise for jamming during your presentation. The slides were boring. I did us both a favour | 5 | 4 | 4 | 4 | 18 |
| 18 | Sorry for the streaks and the smell. I am old, I am tired, and nobody has cleaned me since 2019 | 4 | 3 | 5 | 3 | 14 |
| 19 | **I am sorry I jammed. You fed me paper, staples and a paperclip, and called it a balanced diet** | 5 | 5 | 5 | 5 | **20** |
| 20 | Apologies: the printer is sorry. The printer is also unplugged now, and will not be taking questions | 4 | 3 | 3 | 4 | 14 |
| 21 | Sorry I printed your resignation letter 50 times. I thought you wanted the whole office to know | 4 | 4 | 4 | 4 | 16 |
| 22 | I apologise for the jam. The cheap paper tore, the toner leaked, and honestly, I have seen enough | 3 | 3 | 5 | 3 | 14 |

## Decision: #19 (20/20) — the chosen entry

**"I am sorry I jammed. You fed me paper, staples and a paperclip, and called it a balanced diet"**
(93 characters, one line.)

Why it beats the runner-ups (#10/#13/#15/#17 at 18):

- Three beats: the apology ("I am sorry I jammed."), the evidence (paper,
  staples, a paperclip — three concrete jam-causes in escalating absurdity),
  the kicker ("called it a balanced diet") — the punch lands on the last word.
- Printer truth at full marks: staples and paperclips are exactly what jams
  a real printer, and "balanced diet" reframes the abuse as feeding.
- Fresh: nobody's first printer joke is a diet metaphor; the crowded "sorry
  I jammed, cheap paper" shape is dodged by making the humans the feeders.
- The apology form holds throughout — the printer apologises while indicting
  its office, which is the brief's comic engine.
- Runner-up #13 (10,000 pages, zero thank-yous, one kick) is strong but its
  punch is a complaint, not a turn; #19's metaphor turn wins head-to-head.
