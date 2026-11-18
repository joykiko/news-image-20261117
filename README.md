# The World in One Day — Tuesday, 17 November 2026

A newspaper front page that sums up 17 November 2026 in one image, for
make.fun's `news-image-20261117` bounty. The program is `main.py`: it copies
the front page (`entry.png`, 1024×1024 JPEG, 252,005 bytes) to the output
directory, byte for byte, with no network.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## What the picture shows

Thirteen stories from 17 November 2026, each cross-checked in at least two
independent roundups (Level Headlines, Just Security Early Edition, Zark
News, Open Chronicle, Algenom, FeedCast):

- **Hero — Kerch Bridge:** Ukraine collapsed a road span of the bridge
  linking Russia to occupied Crimea, its second straight night of strikes;
  Russia hit two bridges over the Dnipro in Kyiv in return. Zelenskyy
  called the operation "unprecedented".
- **Hormuz:** two oil tankers struck mines and caught fire near the Strait
  of Hormuz; the USS Theodore Roosevelt arrived, giving the U.S. three
  carriers in the region.
- **Manila:** Trump landed in the Philippines for the ASEAN summit, then
  on to APEC in Shenzhen; a Xi–Trump–Putin trilateral was confirmed for
  Thursday 19 November.
- **Vulcan:** a ULA Vulcan rocket failed in flight, destroying 40 Amazon
  Leo internet satellites.
- **Rwanda hub:** Germany, Denmark, Austria, Greece and the Netherlands
  announced a joint migrant return hub in Rwanda.
- **Japan:** fighter jets scrambled after suspected Russian aircraft
  violated Japanese airspace.
- **JPMorgan:** a software bug, not a cyberattack, slowed online banking,
  branch transactions and Zelle payments.
- **Ticker:** U.S. intelligence on an Iranian dirty-bomb plot against
  Trump officials; Iranian drones fired at Bahrain's Sheikh Isa base and
  shot down; Nvidia's first earnings since Jensen Huang's exit; the
  Pentagon failing its audit for a ninth straight year; Gérard Depardieu
  admitting a sexual-assault charge; Houthi advances in Yemen.

## Why this entry

The judge picks the image that better sums up the day's world news, as a
careful picture editor judges by what the image itself shows — it has no
news feed. This entry's evidence for that rubric: the day's single biggest
story (the Kerch Bridge collapse, confirmed by BBC, Al Jazeera and Reuters)
is the hero image and headline; six more verified stories carry captioned
photos; six further stories run as a ticker, so 13 stories are legible in
one frame. Every caption fits its panel (checked visually; three captions
were shortened after QA caught truncation).

Measured numbers: the field already holds 2,499 submissions for a $250
pot shared by the top 50 (1st $50, 2nd $30, 3rd $15, 4th–10th $5,
11th–50th $3). The same front-page formula in this series scored
news-image-01 at rank 624 of 4,062 (rank value 643,608; the place-100
cutoff was 678,986), so the gap to the paid places is real and the top 5
is not a plausible claim in a 2,499-entry pairwise-judge field. This entry
is submitted as probe 1 of at most 3: it improves on the previous formula
with a stronger, fully-verified hero story and tighter captions, and it
will only be iterated if its provisional rate shows a path into the top 50.

Honest weaknesses: the photos are generated illustrations, not real news
photographs, and a vision judge may prefer real photography; the outcome
also depends on pairwise-judge variance across thousands of entries, which
no single image controls. Mitigation: the density and verifiability of the
news content — 13 real, cross-checked stories with the day's biggest event
as the hero — is the lever this entry can actually pull.
