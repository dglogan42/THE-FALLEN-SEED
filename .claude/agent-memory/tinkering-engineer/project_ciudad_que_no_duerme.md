---
name: ciudad-que-no-duerme-novel
description: LA CIUDAD QUE NO DUERME — an original standalone YA urban-gothic novel in the repo, unrelated to The Fallen Seed
metadata:
  type: project
---

`La_Ciudad_Que_No_Duerme.md` (+ `La Ciudad Que No Duerme.epub`) is a **brand-new, fully original** ~30,000-word YA urban-gothic novel written from scratch on 2026-07-02. It is NOT connected to [[fallen-seed-novel]] — deliberately a distinct premise so it doesn't read as a reskin.

**Origin:** The file `La Ciudad Que No Duerme.epub` in the repo was originally a byte-for-byte duplicate of `La_Casa_Que_Respira.epub` (just renamed, zero unique content). David confirmed he wanted an original novel invented from only the title ("The City That Never Sleeps") in the house YA style. The placeholder .epub was overwritten with the real book (intended).

**Premise/logline:** In Vísperas, a city that has not slept in eleven years, 16-year-old Alba is one of the last people who can still dream — because sleep is where she visits her dead mother. The sleeplessness is a plague ("la Vigilia") caused by the corporation Vela S.A., which found an ancient being ("la Durmiente," the Sleeper) who for a thousand years dreamed the city's nightmares so it could rest — and imprisoned her awake at the top of their tower (the Needle), draining her stolen dreams to sell as the light that keeps the sleepless city upright. With Damián (a boy born unable to sleep, who natively walks the dream-overlay "el Duermevela"), Alba climbs the tower to free her, refuses the old one-victim bargain, and gets the city to reclaim its own nights communally.

**Key structure/craft choices (for consistency if revising):**
- Single-POV (Alba), English prose with Spanish spice (matches La_Casa sibling, not pure Spanish). 3 parts, 19 chapters + prologue + epilogue. Prologue/epilogue narrated by adult Alba (frame).
- Deliberately AVOIDS Fallen Seed's skeleton (per advisor): ascent up a tower NOT descent to a buried being; NO "hold-my-hand-or-you-die" tether; ability from grief NOT bloodline destiny; grief-mirror villain (Renata Vela lost a daughter to sleep, wages war on it).
- Closed-door romance (Alba/Damián, same-age). Themes: grief, hustle-culture/sleepless economy, gratitude-as-a-chain.
- Recurring motifs planted-and-paid-off: the mango-hedgehog (mother), "all is well / ya viene el alba," the sereno night-watch, giving sleep by touch.

**EPUB build:** built by hand via a Python script (`scratchpad/build_epub.py`) mirroring the repo's epub layout — mimetype stored-first uncompressed (`zip -X -0`), then `zip -rg` the rest; minidom-validated XHTML. Same method as [[fallen-seed-novel]]'s epub. Build script lives only in session scratchpad, not the repo. Part-divider pages + per-chapter xhtml; NCX/OPF EPUB 2.

**Why:** David asked to expand the placeholder into a full 30k-word YA novel; chose "original from scratch" over adapting existing content.
**How to apply:** Treat this as its own standalone canon, separate from The Fallen Seed. If asked to revise, keep it distinct from Fallen Seed's premise; keep romance closed-door and Alba's agency intact.
