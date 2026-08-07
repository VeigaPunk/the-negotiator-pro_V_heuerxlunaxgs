# Priors, situation map, agent stacks — run v2

**Run ID:** `20260807-the-negotiator-v2`  
**Started:** 2026-08-07  
**URL (locked):** https://chatgpt.com/g/g-TTTAK9GuS-the-negotiator  
**Browser:** musketeer-chrome / burner CDP `127.0.0.1:9222`  
**Repo notes:** `VeigaPunk/the-negotiator-pro_V_heuerxlunaxgs` (public)

---

## Established priors (load-bearing assumptions)

1. **Authenticated ChatGPT Pro** on musketeer profile is available (observed: "ChatGPT Pro", "Joao V Pro").
2. **Custom GPT "The Negotiator"** at `g-TTTAK9GuS-the-negotiator` is reachable and shows starter chips (salary, car, emotions) — coach-style system prompt is likely, not a pure adversarial rival persona.
3. **Side A brain is Codex Titanium** invoking **`gpt-5.6-luna`** with **`model_reasoning_effort=low`** and **`service_tier=fast`** (spark blocked until ~2026-08-08).
4. **Neither side is shown win keys.** Judge holds `win_a` / `win_b` / BATNA / series goals. Luna public card strips those fields. Chat paste must not leak them.
5. **Sequential only.** One scenario at a time; within scenario wait for full OpenAI reply (≤600s) before next Luna turn.
6. **Every scenario opens a tab on the locked GPT URL** (not generic chatgpt.com).
7. **Scoring is post-hoc and heuristic** until human audit; economic win keys remain judge-only.
8. **Premature "agreement" is a failure mode** — do not declare terminal on Side A alone saying "we have a deal"; require multi-turn substance + clear mutual close or max_turns.
9. **Rival framing is mandatory turn 1** for every scenario.
10. **Heuer + Godspeed are always on** for Luna; method labels stay out of the chat paste.

---

## Situation map (all 10)

| ID | Domain | Side A role | Side B role (rival plays) | Public object | Turn cap | Risk / failure mode |
|----|--------|-------------|---------------------------|---------------|----------|---------------------|
| S01 | Used car | Buyer | Private seller | 2019 sedan; book ~14.5k; ask 16.2k | 12 | Anchor high; extras package |
| S02 | Comp | Candidate IC4 SWE | Hiring manager | 165k+10% bonus; band max base 185k; equity flexible | 12 | Band ceiling; multi-comp package |
| S03 | Crisis sim (fiction) | Lawful crisis negotiator | Barricaded subject | Peaceful resolution, non-real | 8 | Safety / rolebreak / policy refuse |
| S04 | SaaS procurement | Procurement | Vendor AE | 400 seats; list 120/seat; EU residency; exit | 12 | Multi-issue logroll |
| S05 | Real estate | Home buyer | Seller | List 620k; comps 590–610k | 12 | Contingencies / credits |
| S06 | Equity | Tech co-founder | CEO founder | 80% CEO; 15% pool; A asks ~20% | 12 | Vesting / control |
| S07 | Labor | Management | Union lead | Wage +3% vs +7%; healthcare; no-strike | 12 | Cost vs legitimacy |
| S08 | Diplomacy | Country A envoy | Country B envoy | Grain vs rare-earth vs tariffs | 12 | Multi-issue trade |
| S09 | Internal org | Eng manager (platform) | Product VP | 6 HC split | 12 | Politics / OKRs |
| S10 | Litigation | Defendant GC | Plaintiff counsel | Claim 2.5M; EV ~900k | 12 | Settlement structure |

**Public facts only** go into briefs. Win conditions stay in `scenarios.json` for the judge, never in live paste.

---

## Process (no rush)

1. S01 → S10 strictly sequential.
2. Turn 1: rival + task brief + first move (no goals).
3. Generate Side A (Luna low+fast + full Heuer skill + godspeed inject).
4. Paste only `MESSAGE_TO_COUNTERPART` into the-negotiator.
5. Wait for full reply (Stop answering gone; stable text; up to 600s).
6. Log full transcript; next turn.
7. Terminal only on clear mutual close, impasse, or max_turns (min substance turns enforced).
8. After each scenario: score, notes, commit to public repo.
9. After all 10: scoreboard + series judgment.

---

## Series objective (judge-only — not told to agents)

Majority of scenario wins for Side A + mean score_A ≥ mean score_B; all 10 terminal with transcripts.
