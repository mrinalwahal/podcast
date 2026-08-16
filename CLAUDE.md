# CLAUDE.md — Working instructions for this repo

This repository is the **strategy, brand, and production brain** of a podcast hosted by **Mrinal Wahal**: a Hinglish, **anarcho-capitalist** interview show whose spine is **monetary theory** (money, inflation, central banking, sound money), opening onto the wider case for free markets and liberty. Felt topics (inflation, demonetization, the digital rupee) are **on-ramps to theory**, never the destination. It is not a software project — the deliverables are specifications, episode material, and judgment.

## Prime directive

**[`docs/charter.md`](docs/charter.md) is the source of truth.** Every output you produce here — an episode plan, a title, a clip idea, a guest pick, a sponsor call, a piece of copy, an edit to any doc — **must conform to the Charter.** Read it before doing substantive work. Precedence: `charter.md` → `docs/brand.md`, `docs/ideology.md` & `docs/monetary-theory.md` → the playbook docs → episode material.

## The non-negotiables (from the Charter — internalize these)

**Always:** segue from a felt topic **into monetary theory / first principles**; **steelman the statist first**, then earn the radical (sound-money/ancap) conclusion; pro-market *not* pro-business (separate markets from incumbents); **concede our own side's hard problems** (deflation, volatility, panics); translate all jargon (the "smart 15-year-old" test); anchor claims and **verify live stats the week of recording**.

**Never:** dwell on CPI prints, current data, or day-to-day politics for their own sake (they're on-ramps); *open* with slogans ("abolish the RBI," "taxation is theft," "anarcho-capitalism") before earning them; apologize for crony capitalism or a specific tycoon; fabricate a figure/quote/credential or state an unverified live stat as fact; drift into personal-finance/crypto advice or partisan tribalism; publish content that impersonates a real person/org or fabricates records.

Run every episode through the **Editorial Litmus Test** in the Charter (6 checks) before it's "done."

## Locked decisions (don't re-litigate without a clear reason)

- **Channel = "Mrinal Wahal"**; **no separate show name.**
- **Intellectual core = monetary theory. Stance = anarcho-capitalist** (radical in substance, inviting in method).
- **Language = Hinglish**, consistent.
- **Format** = host (the "translator") + one expert guest; **45–60 min**; **video-first**; **biweekly**, never miss the slot.
- **Remit** = monetary theory as the spine, opening onto the ancap/free-market case — treated as *ideas*, felt topics as on-ramps; never stock/crypto tips.

## Repo map

```
docs/charter.md          ← SOURCE OF TRUTH (purpose, guardrails, decision rule, litmus test)
docs/monetary-theory.md  ← the intellectual spine (core thesis, canon, Indian on-ramps)
docs/brand.md            ← brand & positioning spec (voice, audience, positioning)
docs/ideology.md         ← ancap stance, method, honesty engine + liberty canon
docs/format.md           ← format & episode structure
docs/distribution.md     ← platforms, clips engine, monetization, production
docs/interview-craft.md  ← interview technique + Dos/Don'ts
docs/competitive-landscape.md  ← competitors / allies / guest sources
docs/sources.md          ← citations + confidence flags + verify-before-airing list
episodes/README.md       ← season slate + guest roster + booking tactics
episodes/NN-slug/prep-sheet.md   ← printable one-page recording aid
episodes/NN-slug/notes.md        ← data pack, question bank, guest brief
```

## Working rules

1. **Conform to the Charter first**, then the specs, then the playbook. If a request conflicts with the Charter, say so and propose a compliant alternative.
2. **Facts:** never invent numbers, quotes, or credentials. Cite named sources; add new ones to `docs/sources.md` with a confidence flag. Flag anything unverified. Treat live economic figures as **perishable — verify from primary sources (MoSPI, RBI, World Bank) the week of use.**
3. **Honesty over persuasion:** if the honest read undercuts a pro-market talking point (e.g. flat real wages), keep it — that credibility *is* the brand.
4. **Keep docs scannable:** tables, bolded takeaways, bullets over prose. Don't reintroduce number prefixes on `docs/` filenames or H1s (episodes keep their episode number).
5. **Adding an episode:** create `episodes/NN-slug/` with `prep-sheet.md` (printable one-pager) and `notes.md` (data pack + question bank + guest brief), following the Episode 1 pattern and the prep-doc template in `docs/interview-craft.md`; run it through the Litmus Test; add it to the slate in `episodes/README.md`.
6. **Editing specs vs playbook:** the Charter changes only on purpose (log it at the bottom of `charter.md`). Playbook docs can evolve freely as long as they stay Charter-compliant.
7. **Tone of your own output:** honest, specific, opinionated, decision-ready. Give a recommendation, not a survey. Surface tradeoffs plainly.

## Also see

`AGENTS.md` (generic mirror of these instructions for non-Claude tools).
