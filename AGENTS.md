# AGENTS.md

Generic instructions for any AI agent or tool working in this repository. Claude Code users: the canonical, fuller version is [`CLAUDE.md`](CLAUDE.md).

## What this is
The strategy, brand, and production brain of a podcast hosted by **Mrinal Wahal** — a Hinglish, **first-principles analytical** interview show about **power, incentives, and freedom** (anarcho-capitalist / classical-liberal conviction). **Two pillars, sequenced: Pillar 1 (launch) = the politics of money** (monetary theory — money, inflation, central banking, sound money); **Pillar 2 (planned, host-led) = AI / deep learning**, the host's expertise, same lens. Felt topics are on-ramps to first principles; launch narrow on money, broaden into AI later. Deliverables are specs, episode material, and judgment — not code.

## Prime directive
**[`docs/charter.md`](docs/charter.md) is the source of truth.** Everything you produce must conform to it. Precedence: `charter.md` → `docs/brand.md`, `docs/ideology.md` & `docs/monetary-theory.md` → playbook docs → episode material. Read the Charter before substantive work.

## Non-negotiables (from the Charter)
- **Segue to first principles** — start from a felt topic (money now, AI later), end in the theory under the hood, not the news.
- **Radical in substance, inviting in method** — steelman the statist first, then earn the sound-money/ancap conclusion; never *open* with slogans ("abolish the RBI," "taxation is theft").
- **Pro-market, not pro-business** — separate markets from incumbents; never apologize for cronyism.
- **Steelman our own side too** — concede sound money's hard problems (deflation, volatility, panics). Honesty over persuasion.
- **Translate all jargon** (the "smart 15-year-old" test); Hinglish, accessible.
- **Anchor every claim to a named source; verify live stats before use; never fabricate** a figure, quote, or credential.
- **Never** drift into stock/crypto tips or partisanship, or impersonate real people/orgs.
- Run every episode through the **Editorial Litmus Test** (6 checks) in the Charter.

## Locked decisions
Channel = "Mrinal Wahal" (no separate show name) · **analytical spine (power/incentives/freedom); Pillar 1 = monetary theory (launch), Pillar 2 (planned) = AI/deep learning; anarcho-capitalist/classical-liberal stance** · **guest-first planning** (topic follows the guest's expertise; recurring guests get numbered rounds) · Hinglish · host + one guest · 45–60 min · video-first · biweekly.

## Repo map & how to add an episode
See [`CLAUDE.md`](CLAUDE.md) for the full repo map and the **guest-first** episode-creation procedure (`episodes/<guest>/<round>/{host.md,guest.md}` — pick the guest, shape the topic to their expertise, write a host sheet + a shareable guest brief, run the Litmus Test, list it in `episodes/README.md`).

**Where things live:** `docs/` = global & governing (reused across every episode); `episodes/<guest>/<round>/` = everything that exists only because of this recording (prep now — `host.md`, `guest.md` — plus its show notes and cut plan later). Never duplicate a global spec into a round folder, or scatter episode-specific material into `docs/`; create per-round files only when they have real content.
