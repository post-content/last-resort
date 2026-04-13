# Last Resort
### Omens · Numbers · Intercessions · Divinations · Fate

A single-file fortune-telling web app drawing on multicultural divination traditions from around the world — built as a fun entry point into comparative religion and the history of how humans have always tried to read meaning into things.

**[→ Live demo]([your repo URL here])** &nbsp;·&nbsp; Built with [Claude](https://claude.ai) by Anthropic

---

## What it does

- **Deity of the Day** — 28 deities rotating by day of month, spanning Hindu, Egyptian, Aztec, Yoruba, Norse, Shinto, Greek, Celtic, Chinese, Andean, and folk traditions. Each with a dry biography, daily omen, and Wikipedia source link.
- **Consult the Oracle** — 8 divination traditions (I Ching, Tarot, Norse Runes, Yoruba Ifá, Astrology, Tasseography, Santería, Numerology). Type a specific question for a Claude-powered tradition-specific reading, or leave blank for a general reading.
- **Lucky Numbers** — Powerball, Mega Millions, Pick 3, Keno, Lucky Dip. Generated using advanced techniques including: thinking about it.
- **Daily Horoscope** — All 12 signs with rotating readings, star ratings, and lucky details.
- **Omen of the Hour** — Working analog clock with 24 hour-specific omens drawn from cross-cultural temporal traditions. Refreshes at the top of each hour.
- **Wheel of Fate** — Spinning canvas wheel with 12 outcomes and full readings.
- **Dream Interpreter** — Claude-powered, drawing on Jungian, Islamic ta'bir, Egyptian, Greek, Iroquois, and Chinese dream traditions.
- **Curse or Bless Someone** — Self-explanatory. The curses are proportionate (shoelace, battery, puddle).
- **Supplementary tools** — Coin toss, sacred dice, Magic 8-Ball, lucky color, biorhythm, animal guide. Each with historical grounding and source links.
- **Traditions of the World** — Full reference accordion covering the history, cultural context, appropriation notes, and Wikipedia links for every tradition featured.

## How to use

It's a single HTML file. Download `last-resort.html`, open it in a browser. That's it. No build step, no dependencies, no server required.

The Oracle chat, dream interpreter, and tradition-specific fortune readings require an internet connection (they call the Anthropic API).

## Attribution

Built by [Claude](https://claude.ai) (Anthropic), prompted and directed by [@yourusername]([your repo URL here]).

This project uses the [Anthropic Messages API](https://docs.anthropic.com/en/api/messages) for AI-powered features.

Fonts via [Google Fonts](https://fonts.google.com): UnifrakturMaguntia, Special Elite, Courier Prime.

Historical and cultural information sourced from [Wikipedia](https://wikipedia.org) and linked inline throughout the app. Traditions are presented for educational and entertainment purposes. They belong to real communities with living practices — the app tries to say so clearly.

---

## Patch Notes

### v0.5 — Deity of the Day
- Renamed "Saint of the Day" → **Deity of the Day** (it was only going to be Christian otherwise)
- Expanded roster from 10 entries to 28 deities across Hindu, Egyptian, Aztec/Mexica, Yoruba, Norse, Shinto, Buddhist, Greek/Roman, Celtic, Chinese, Andean, and folk traditions
- Each deity now shows tradition and region of origin in the subheading
- Added explicit note on Coyote entry that this is not one unified Indigenous tradition

### v0.4 — Attribution & Cultural Grounding
- **Animal Guide** (renamed from "Spirit Animal"): full replacement of all 10 animals with attributed entries covering cross-cultural symbolism, a "Across Traditions" section, a cultural context note, and Wikipedia links
- Added honest framing note about the term "spirit animal" borrowing from Indigenous traditions
- Added grounding notes to all supplementary tools: coin toss, dice, Magic 8-Ball, lucky color, biorhythm — each now has a brief history and Wikipedia link
- All modal tool headers updated with historical context

### v0.3 — Educational Layer
- Added **"About This Tradition"** collapsible info panel to the Consult the Oracle section — covers history, facts grid, cultural context note, and Wikipedia links for all 8 traditions
- Added **saint/deity context footnotes** below the daily omen — historical grounding with Wikipedia source
- Added **Traditions of the World** full reference section at bottom of app: 10 accordion entries (I Ching, Tarot, Elder Futhark Runes, Yoruba Ifá, Astrology, Tasseography, Santería/Lucumí, Numerology, Oneiromancy, Folk Saints) with substantive histories and appropriation context
- Norse rune entry explicitly addresses Nazi misappropriation of runic symbols
- Santería entry includes the 1993 Supreme Court case (Church of Lukumi v. City of Hialeah)

### v0.2 — New Sections & Steampunk Pass
- Added **Daily Horoscope** — all 12 signs, rotating readings, star ratings for luck/love/money
- Added **Omen of the Hour** — working SVG analog clock with 24 hourly omens
- Added **Wheel of Fate** — canvas-rendered spinning wheel with 12 outcomes
- Added **Dream Interpreter** — Claude-powered, multi-tradition oneiromancy
- Added **Curse or Bless Someone** — name entry, two modes, typed delivery
- Visual overhaul: distressed paper texture (layered burn-corner gradients, fiber lines, grain overlay), brass/copper color system, steampunk accents (rotating SVG gears, rivets, pipe dividers, chamfered buttons, brass scrollbar)

### v0.1 — Initial Build
- **Saint of the Day** with biography, omen, and footnote
- **Consult the Oracle** — 8 traditions, static fortune library
- **Lucky Numbers** — 5 lottery types with animated ball reveal
- **Supplementary tools** — coin, dice, Magic 8-Ball, lucky color, biorhythm, spirit animal
- **Ask the Oracle** — Claude-powered chat maintaining character as ancient dry skeptic
- Single-file HTML, no dependencies, steampunk newspaper aesthetic (UnifrakturMaguntia masthead, aged paper, brass ornaments, rotating gear backgrounds)

---

*"May your fortunes be at least slightly better than they would have been anyway."*
