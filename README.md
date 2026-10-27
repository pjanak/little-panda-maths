# Little Panda Maths

A colourful, mobile-first maths site for 5-year-olds that teaches the methods used in Chinese Year 1 and 2 classrooms, in English. Bao the panda guides children through eight games covering adding, take away, times and sharing, with every question read aloud.

## Games

- **Split & Join (分与合 fēn yǔ hé)**: number bonds. Every number is made of two parts.
- **Ten Friends (凑十 còu shí)**: the pairs that make 10, on a ten-frame.
- **Make Ten to Add (凑十法 còu shí fǎ)**: add past 10 by filling up the ten first (8 + 5 = 10 + 3).
- **Bead Abacus (算盘 suàn pán)**: show numbers with a top bead worth 5 and bottom beads worth 1.
- **Take Away (减法 jiǎn fǎ)**: cross out dots and count what's left; on Hard, "think adding to take away" (想加算减).
- **Break Ten (破十法 pò shí fǎ)**: for 13 − 5, take the 5 from the ten (10 − 5 = 5), then add the 3 ones back.
- **Equal Groups (几个几 jǐ gè jǐ)**: multiplying as equal groups, with the matching line of the 九九 times-table rhyme (三五十五).
- **Share Fairly (平均分 píng jūn fēn)**: dividing as sharing peaches out one at a time between pandas.

## Difficulty levels

Pick **Easy**, **Medium** or **Hard** on the home screen or inside any game. The choice is remembered on the device.

| Game | Easy | Medium | Hard |
|---|---|---|---|
| Split & Join | Numbers 2–5 with dots | Numbers 3–10, sometimes the whole is missing | Numbers 8–20, no dots, teen numbers split as 10 and the rest |
| Ten Friends | Pairs that make 5 | Pairs that make 10 | `7 + ? = 10` with the dots hidden until "Show me" |
| Make Ten to Add | Start from 8 or 9, totals 11–13 | Start from 6–9, tap dots to fill the ten | No tapping: work out how many make 10, how the second number splits, then the total |
| Bead Abacus | 1–9 on the ones rod only | 1–20 | 10–99, and the abacus no longer shows its number |
| Take Away | Up to 5, tap dots to cross out | Up to 10, tap dots to cross out | No dots: a number bond shows the adding fact |
| Break Ten | 11 or 12, taking away up to 5 | 11–18, tap dots in the full ten | No tapping: the ones, ten take away, then the total |
| Equal Groups | 2 on every plate, up to 5 plates | 2, 5 or 10 on every plate | Any groups up to 5 × 5, plates hidden until "Show me" |
| Share Fairly | Up to 10 between 2 pandas | Up to 15 between 2 or 3 pandas | Up to 25 between up to 5 pandas, worked out in your head |

Right answers earn stars and confetti, and every 5 stars brings up a celebration. Stars are saved in the browser's local storage.

## Running it

Live at **https://little-panda-maths.pages.dev** (Cloudflare Pages, redeploys on every push to `main`).

It's a single static file with no build step. Open `index.html` in a browser, or host the folder on any static host (GitHub Pages, Cloudflare Pages, Netlify).
