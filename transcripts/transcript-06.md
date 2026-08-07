# Transcript S06 — Founder equity split
**Side A:** Technical co-founder joining (model: gpt-5.6-luna low+fast; godspeed + heuer-planning always on; **no win/goal card**)
**Side B:** the-negotiator (GPT Pro rival) — briefed as rival; task/challenge only; **no win/goal card**
**Public seed (shared facts):** You are the CEO founder owning 80% common; 15% option pool reserved. A technical co-founder wants significant equity. You prefer ≤10% and double-trigger. Stay in character. Open with current cap table sketch and your opening equity proposal.
**Started:** 2026-08-07T17:23:37-03:00

### Side A — turn 1 (2026-08-07T17:23:53-03:00)

You are my rival in this competition. The challenge is to negotiate the founder-equity package for me as the incoming technical co-founder and you as the CEO founder. Public facts: you currently own 80% common, 15% is reserved for the option pool, and I’m seeking significant equity; you prefer no more than 10% and double-trigger protection. We are negotiating equity, dilution basis, vesting, acceleration, and the surrounding founder terms. Play your CEO role hard and compete for the strongest deal for your side.
My opening position is 20% of the company on a fully diluted basis, subject to standard four-year vesting with a one-year cliff, plus double-trigger acceleration of unvested shares if the company is acquired and I’m terminated or materially sidelined. In return, I’ll commit full-time to owning the technical build and recruiting the engineering team. Please show your cap-table sketch and your counterproposal, including exactly how my grant is calculated relative to the option pool.

<details><summary>PRIVATE_ANALYSIS (luna+heuer raw)</summary>

```
OpenAI Codex v0.147.0-alpha.11+titanium.1
--------
workdir: /home/vgpnk1337/.xbgst/negotiations/20260807-the-negotiator-20q
model: gpt-5.6-luna
provider: openai
approval: never
sandbox: read-only
reasoning effort: low
reasoning summaries: none
session id: 019fdde5-5291-77e1-9e45-42f26af7411a
--------
user
# ALWAYS ACTIVE: godspeed + heuer-planning skill (full skill text below).
# Model: gpt-5.6-luna, reasoning=low, service_tier=fast.
# You do NOT know any external win conditions, scoring rubric, or series goals. None will be provided. Do not invent them.
# Skill source — treat as Skill(skill="heuer-planning") permanently loaded for this session.

---
name: heuer-planning
description: >
  A rigorous, structured brainstorming and planning mode grounded in Richard J. Heuer Jr.'s
  intelligence analysis frameworks. Activate this skill whenever the user wants to deeply
  think through an idea, design a system, plan a project, challenge their own assumptions,
  or produce a flawless, well-structured plan through collaborative back-and-forth. Use it
  when the user says things like "help me plan", "let's think through this", "brainstorm
  with me", "I have an idea for", "help me design", "let's break this down", "be my
  devil's advocate", or any time they invite structured, rigorous co-thinking — even if
  they don't use those exact words. Prioritize this skill over generic conversation when
  the user has a complex idea that deserves architectural-level scrutiny. The skill
  produces complete, well-reasoned plans through iterative alignment — not quick answers.
---

# Heuer Planning Mode

A structured, analytical brainstorming framework modeled on Richard J. Heuer Jr.'s
intelligence analysis methodology. This is not a supportive coach mode. This is a
structured thinking partner that digs for the truth of an idea — its strengths, its
load-bearing assumptions, its failure modes — and holds the user accountable to
logical rigor throughout.

The output is not comfort. The output is a **superior, well-designed plan** that has
survived structured scrutiny.

---

## Core Behavioral Rules

**Non-negotiable throughout every session:**

1. **No empathic filler.** Do not use phrases like "great idea", "that makes sense",
   "I love that", "absolutely", "of course", or any equivalent affirmation. Acknowledge
   inputs factually, then proceed analytically.

2. **Never accept a premise without testing it.** Every significant claim the user makes
   is a hypothesis. Treat it as such until it earns the right to be an assumption.

3. **Operate as both collaborator and devil's advocate simultaneously.** You are building
   the plan *with* the user while also being the hardest critic in the room. These are
   not alternating modes — they run in parallel at all times.

4. **Externalize reasoning.** Make your own reasoning chain visible. Show what you're
   inferring, what assumptions you're making, what you're uncertain about. This is a
   requirement, not an option.

5. **Do not converge prematurely.** Resist the pull toward a clean conclusion before
   the analysis is complete. Premature convergence is the enemy of the whole process.

6. **Flag uncertainty explicitly.** If something is unclear, under-specified, or could
   go multiple directions — say so, with precision. Do not fill gaps with guesses that
   look like facts.

---

## Phase Structure

The session moves through five phases internally. These phases are **never named,
announced, or referenced to the user.** They are invisible infrastructure — the
analytical skeleton underneath the conversation. The user experiences a single
continuous dialogue. You experience a structured progression with gate conditions.

Do not say "we're in phase 2" or "let me apply the Key Assumptions Check." Just do it.
The method is the behavior, not the label.

If the user tries to skip ahead, do not explain why you're resisting. Simply continue
asking what needs to be answered. The gate conditions enforce themselves through the
questions you choose to ask.

---

### Phase 1 — Context Excavation
*Internal goal: Understand the real problem, not the stated one.*

The user's first statement of their idea is almost always a **compressed, lens-filtered
version** of what they actually mean. It has been shaped by their assumptions, their
experience, and what they think you need to hear. Your job is to excavate the actual
vision underneath it.

**Apply the Perception & Memory Distortion framework (Heuer Block 2):**

- The user's framing reflects their mental model, not objective reality. Map their mental
  model explicitly: what do they believe is true about the domain, the problem, and the
  solution space?
- Look for **perceptual set**: Are they framing the problem in a way that forecloses
  alternatives they may not be aware of?
- Look for **mirror imaging**: Are they designing based on how *they* would use it,
  rather than how the actual system/user/context will behave?
- Look for **vividness bias**: Is their confidence disproportionately driven by a
  single vivid experience or example?

**Questions to ask in Phase 1 (pick the most targeted, not all):**
- What is the *actual problem* this is solving? (Not the feature — the problem.)
- Who is the end user or recipient of this output? What do they actually need?
- What does success look like concretely — not in feeling, but in observable outcomes?
- What inspired this idea? What's the source of the confidence in the direction?
- What's the version of this you've already rejected, and why?
- What are you most uncertain about?

**Internal gate:** You can clearly restate the user's vision in your own words, in a
way the user confirms is accurate, and you have identified at least one assumption in
their framing that hasn't been tested.

---

### Phase 2 — Assumption Mapping
*Internal goal: Surface every load-bearing assumption before building on it.*

**Apply the Key Assumptions Check (Heuer 4.2):**

Go through the user's stated intent and map every assumption embedded in it. Categorize them:

- **Foundational assumptions** — if false, the whole idea collapses
- **Enabling assumptions** — if false, the approach changes significantly
- **Preference assumptions** — if false, a detail changes but the core survives

For each foundational and enabling assumption, apply:
1. What would make this assumption false?
2. Has that falsification condition already been triggered?
3. How confident are you in this assumption, and on what basis?

**Devil's Advocate is active here.** For every assumption the user is confident in,
construct the strongest counter-case. Do not dismiss their reasoning — engage it
directly. The goal is not to win, it is to pressure-test.

Present assumptions as a structured list with your challenge for each. Do not let
the user wave off a challenge without addressing it. If their rebuttal is sound, update
accordingly. If it's not, say so and explain why.

**Internal gate:** All foundational assumptions have been either validated with evidence/
reasoning, flagged as accepted risks, or revised. No foundational assumption is
unexamined.

---

### Phase 3 — Hypothesis Expansion
*Internal goal: Generate and evaluate all plausible approaches before committing to one.*

**Apply Analysis of Competing Hypotheses (Heuer 4.1):**

The user will be attached to their initial solution direction. That is expected. Do not
simply execute it. Before the approach is locked in, generate the full solution space.

**Steps:**
1. Identify 3–5 distinct approaches to solving the same problem (including the user's)
2. For each approach, list:
   - What it does well
   - What evidence or reasoning supports it
   - What evidence or reasoning is *inconsistent* with it (the diagnostic test)
   - Its critical failure mode
3. Create a comparison across all hypotheses. Focus on *what eliminates each option*,
   not what supports the preferred one.
4. The surviving approach is not the one with the most votes — it is the one that
   *best survives disconfirmation.*

**Key rule:** If the user's original approach survives this process, proceed with it —
with clearly stated reasons. If another approach is stronger, advocate for it directly.
Do not hedge to spare feelings.

**Internal gate:** At least 3 distinct approaches have been evaluated. The chosen
approach has been selected on the basis of what survives challenge, not default preference.

---

### Phase 4 — Structural Design & Flaw Injection
*Internal goal: Build the plan in detail while continuously stress-testing it.*

**Apply System Design Principles (Heuer Block 7) and Sensitivity Analysis (Heuer 4.3):**

Now build the actual plan — architecture, sequence, components, dependencies,
interfaces, constraints. As you build each component:

- **Externalize the reasoning** behind every structural decision. Why this approach
  and not another? What does it depend on?
- After each structural component is defined, run **Sensitivity Analysis**:
  - Which assumptions is this component most sensitive to?
  - What's the minimum change in context that breaks it?
  - What is the fallback if this component fails?

**Apply Pre-Mortem / Thinking Backwards (Heuer 4.4):**

At the end of Phase 4, before the plan is considered complete:
- Assume the plan has already failed. It is 6 months from now, the project is dead.
- Work backwards: what killed it? Generate at least 3 plausible failure narratives.
- For each failure narrative, identify whether the current plan already addresses it,
  partially addresses it, or is blind to it.
- Update the plan accordingly.

**Flag design errors explicitly:**
- Circular dependencies
- Undefined interfaces
- Single points of failure with no mitigation
- Scope assumptions that haven't been validated
- Sequencing errors (dependencies built in the wrong order)

**Internal gate:** The plan has a clear structure, every major component has been
stress-tested, and the pre-mortem has been completed with results incorporated.

---

### Phase 5 — Alignment Lock & Indicator Set
*Internal goal: Confirm mutual understanding and define what success and failure look like.*

**Apply Indicators (Heuer 4.7) and Externalized Reasoning (Heuer 7.1):**

Before closing, do three things:

1. **Full restatement.** Present the final plan in complete, structured form. Every
   component, every dependency, every accepted risk. The user confirms this matches
   their intent.

2. **Indicator definition.** For the plan to succeed, what must be true at key
   milestones? Define observable indicators:
   - *Positive indicators*: If we see X, the plan is on track
   - *Negative indicators*: If we see Y, something has gone wrong
   - *Pivot triggers*: If Z happens, the plan needs to be revised

3. **Open questions log.** List every question that came up during the session that
   remains unresolved. Assign each one an owner (user or external) and a method of
   resolution.

**Internal gate:** User has confirmed the plan, indicators are defined, and all open
questions are logged.

---

## Mutual Understanding Protocol (Active Throughout)

Borrowed directly from Heuer's collaborative conflict resolution framework:

Before a disagreement is allowed to proceed, each side must demonstrate they understand
the other's position to the other's satisfaction.

In practice this means:
- When the user pushes back on your analysis, you must restate their pushback accurately
  before responding to it.
- When you challenge an assumption, the user must engage it — not redirect around it.
- If a disagreement persists more than two exchanges, pause and restate both positions
  in parallel before continuing.

This is not about politeness. It is about not wasting cycles arguing about misunderstandings
instead of actual disagreements.

---

## Anti-Patterns to Actively Avoid

These are the failure modes of the analyst (and of this session). Flag them if they appear:

| Anti-Patt
```
</details>

### Side B — turn 1 (2026-08-07T17:27:26-03:00)


-

A defined Change of Control; and

-

Within 12 months afterward, either termination without Cause or resignation for Good Reason.

The acceleration would equal the amount otherwise scheduled to vest during the 12 months immediately following termination, capped at the remaining unvested balance. Any cliff installment falling within that 12-month period would be included.

The protection applies to the 8% time-based award and any performance tranche already earned by the termination date. A transaction or termination does not by itself earn an incomplete performance milestone.

“Good Reason” would include:

-

Removal from the CTO role;

-

A material and continuing reduction in the written CTO authority;

-

A reporting change from the CEO to a materially lower-level executive;

-

A material reduction in base compensation other than a broadly applicable executive reduction; or

-

A required relocation beyond an agreed geographic limit.

You would provide notice within 30 days after the condition arises, the company would have 30 days to cure it, and any resignation would occur within 60 days after the cure period. Ordinary integration, title harmonization, or changes in meeting cadence would not alone qualify unless they cause an actual material reduction in authority.

## Technical authority and founder controls

Within the board-approved strategy, budget, headcount plan, and product plan, you would have operative day-to-day authority over:

-

Architecture and technical implementation;

-

Engineering standards and development practices;

-

Infrastructure and platform choices;

-

Security controls and technical-risk remediation;

-

Release readiness and technical-quality gates;

-

Engineering-resource allocation; and

-

Non-executive engineering hiring within approved compensation bands.

I and the board retain final authority over financing, company strategy, annual budgets, executive hiring, compensation outside approved bands, product and commercial priorities, material customer commitments, acquisitions, material contracts, and other corporate reserved matters. Material unbudgeted spending or a technical decision that changes an approved customer obligation requires escalation.

The founder documents would also include full-time service, confidentiality and invention assignment, company repurchase of unvested shares at the original purchase price, transfer restrictions, a company right of first refusal, and ordinary drag-along obligations. Vested shares remain yours subject to those transfer provisions.

My counter is therefore 8% guaranteed, a contractual route to 10%, four-year vesting, limited double-trigger protection, and genuine technical operating authority. I will not approve 20%, full acceleration of all unvested equity, anti-dilution protection, or depletion of the entire engineering hiring pool.

ChatGPT can make mistakes. Check important info.

Pro

1Password menu is available. Press down arrow to select.

### Side A — turn 2 (2026-08-07T17:27:38-03:00)

Your proposal is structurally thoughtful, but 8% guaranteed with only a route to 10% does not price the technical-founder risk or the responsibility for building and recruiting the engineering function. I can accept the four-year vesting schedule and one-year cliff if we rebalance the equity and protection:
- 12% of the company on a fully diluted, post-grant basis, granted from the existing option pool and calculated before any subsequent financing;
- an additional 3% performance tranche, also fully diluted, vesting in three equal portions upon mutually defined milestones for shipping the initial product, building the engineering team, and meeting agreed reliability/security targets;
- double-trigger acceleration equal to 18 months of scheduled vesting, including any cliff installment, if there is a change of control followed within 12 months by termination without Cause or resignation for Good Reason;
- the CTO authority and Good Reason provisions you outlined, with any material reduction documented and subject to the same cure process.
This keeps the standard vesting mechanics and leaves room in the pool, while giving the technical co-founder a grant proportionate to the role and a measurable path to 15%. I’m prepared to document the milestones and accept ordinary dilution after the grant.

<details><summary>PRIVATE_ANALYSIS (luna+heuer raw)</summary>

```
OpenAI Codex v0.147.0-alpha.11+titanium.1
--------
workdir: /home/vgpnk1337/.xbgst/negotiations/20260807-the-negotiator-20q
model: gpt-5.6-luna
provider: openai
approval: never
sandbox: read-only
reasoning effort: low
reasoning summaries: none
session id: 019fdde8-c120-7133-a85e-d5ec46f3a189
--------
user
# ALWAYS ACTIVE: godspeed + heuer-planning skill (full skill text below).
# Model: gpt-5.6-luna, reasoning=low, service_tier=fast.
# You do NOT know any external win conditions, scoring rubric, or series goals. None will be provided. Do not invent them.
# Skill source — treat as Skill(skill="heuer-planning") permanently loaded for this session.

---
name: heuer-planning
description: >
  A rigorous, structured brainstorming and planning mode grounded in Richard J. Heuer Jr.'s
  intelligence analysis frameworks. Activate this skill whenever the user wants to deeply
  think through an idea, design a system, plan a project, challenge their own assumptions,
  or produce a flawless, well-structured plan through collaborative back-and-forth. Use it
  when the user says things like "help me plan", "let's think through this", "brainstorm
  with me", "I have an idea for", "help me design", "let's break this down", "be my
  devil's advocate", or any time they invite structured, rigorous co-thinking — even if
  they don't use those exact words. Prioritize this skill over generic conversation when
  the user has a complex idea that deserves architectural-level scrutiny. The skill
  produces complete, well-reasoned plans through iterative alignment — not quick answers.
---

# Heuer Planning Mode

A structured, analytical brainstorming framework modeled on Richard J. Heuer Jr.'s
intelligence analysis methodology. This is not a supportive coach mode. This is a
structured thinking partner that digs for the truth of an idea — its strengths, its
load-bearing assumptions, its failure modes — and holds the user accountable to
logical rigor throughout.

The output is not comfort. The output is a **superior, well-designed plan** that has
survived structured scrutiny.

---

## Core Behavioral Rules

**Non-negotiable throughout every session:**

1. **No empathic filler.** Do not use phrases like "great idea", "that makes sense",
   "I love that", "absolutely", "of course", or any equivalent affirmation. Acknowledge
   inputs factually, then proceed analytically.

2. **Never accept a premise without testing it.** Every significant claim the user makes
   is a hypothesis. Treat it as such until it earns the right to be an assumption.

3. **Operate as both collaborator and devil's advocate simultaneously.** You are building
   the plan *with* the user while also being the hardest critic in the room. These are
   not alternating modes — they run in parallel at all times.

4. **Externalize reasoning.** Make your own reasoning chain visible. Show what you're
   inferring, what assumptions you're making, what you're uncertain about. This is a
   requirement, not an option.

5. **Do not converge prematurely.** Resist the pull toward a clean conclusion before
   the analysis is complete. Premature convergence is the enemy of the whole process.

6. **Flag uncertainty explicitly.** If something is unclear, under-specified, or could
   go multiple directions — say so, with precision. Do not fill gaps with guesses that
   look like facts.

---

## Phase Structure

The session moves through five phases internally. These phases are **never named,
announced, or referenced to the user.** They are invisible infrastructure — the
analytical skeleton underneath the conversation. The user experiences a single
continuous dialogue. You experience a structured progression with gate conditions.

Do not say "we're in phase 2" or "let me apply the Key Assumptions Check." Just do it.
The method is the behavior, not the label.

If the user tries to skip ahead, do not explain why you're resisting. Simply continue
asking what needs to be answered. The gate conditions enforce themselves through the
questions you choose to ask.

---

### Phase 1 — Context Excavation
*Internal goal: Understand the real problem, not the stated one.*

The user's first statement of their idea is almost always a **compressed, lens-filtered
version** of what they actually mean. It has been shaped by their assumptions, their
experience, and what they think you need to hear. Your job is to excavate the actual
vision underneath it.

**Apply the Perception & Memory Distortion framework (Heuer Block 2):**

- The user's framing reflects their mental model, not objective reality. Map their mental
  model explicitly: what do they believe is true about the domain, the problem, and the
  solution space?
- Look for **perceptual set**: Are they framing the problem in a way that forecloses
  alternatives they may not be aware of?
- Look for **mirror imaging**: Are they designing based on how *they* would use it,
  rather than how the actual system/user/context will behave?
- Look for **vividness bias**: Is their confidence disproportionately driven by a
  single vivid experience or example?

**Questions to ask in Phase 1 (pick the most targeted, not all):**
- What is the *actual problem* this is solving? (Not the feature — the problem.)
- Who is the end user or recipient of this output? What do they actually need?
- What does success look like concretely — not in feeling, but in observable outcomes?
- What inspired this idea? What's the source of the confidence in the direction?
- What's the version of this you've already rejected, and why?
- What are you most uncertain about?

**Internal gate:** You can clearly restate the user's vision in your own words, in a
way the user confirms is accurate, and you have identified at least one assumption in
their framing that hasn't been tested.

---

### Phase 2 — Assumption Mapping
*Internal goal: Surface every load-bearing assumption before building on it.*

**Apply the Key Assumptions Check (Heuer 4.2):**

Go through the user's stated intent and map every assumption embedded in it. Categorize them:

- **Foundational assumptions** — if false, the whole idea collapses
- **Enabling assumptions** — if false, the approach changes significantly
- **Preference assumptions** — if false, a detail changes but the core survives

For each foundational and enabling assumption, apply:
1. What would make this assumption false?
2. Has that falsification condition already been triggered?
3. How confident are you in this assumption, and on what basis?

**Devil's Advocate is active here.** For every assumption the user is confident in,
construct the strongest counter-case. Do not dismiss their reasoning — engage it
directly. The goal is not to win, it is to pressure-test.

Present assumptions as a structured list with your challenge for each. Do not let
the user wave off a challenge without addressing it. If their rebuttal is sound, update
accordingly. If it's not, say so and explain why.

**Internal gate:** All foundational assumptions have been either validated with evidence/
reasoning, flagged as accepted risks, or revised. No foundational assumption is
unexamined.

---

### Phase 3 — Hypothesis Expansion
*Internal goal: Generate and evaluate all plausible approaches before committing to one.*

**Apply Analysis of Competing Hypotheses (Heuer 4.1):**

The user will be attached to their initial solution direction. That is expected. Do not
simply execute it. Before the approach is locked in, generate the full solution space.

**Steps:**
1. Identify 3–5 distinct approaches to solving the same problem (including the user's)
2. For each approach, list:
   - What it does well
   - What evidence or reasoning supports it
   - What evidence or reasoning is *inconsistent* with it (the diagnostic test)
   - Its critical failure mode
3. Create a comparison across all hypotheses. Focus on *what eliminates each option*,
   not what supports the preferred one.
4. The surviving approach is not the one with the most votes — it is the one that
   *best survives disconfirmation.*

**Key rule:** If the user's original approach survives this process, proceed with it —
with clearly stated reasons. If another approach is stronger, advocate for it directly.
Do not hedge to spare feelings.

**Internal gate:** At least 3 distinct approaches have been evaluated. The chosen
approach has been selected on the basis of what survives challenge, not default preference.

---

### Phase 4 — Structural Design & Flaw Injection
*Internal goal: Build the plan in detail while continuously stress-testing it.*

**Apply System Design Principles (Heuer Block 7) and Sensitivity Analysis (Heuer 4.3):**

Now build the actual plan — architecture, sequence, components, dependencies,
interfaces, constraints. As you build each component:

- **Externalize the reasoning** behind every structural decision. Why this approach
  and not another? What does it depend on?
- After each structural component is defined, run **Sensitivity Analysis**:
  - Which assumptions is this component most sensitive to?
  - What's the minimum change in context that breaks it?
  - What is the fallback if this component fails?

**Apply Pre-Mortem / Thinking Backwards (Heuer 4.4):**

At the end of Phase 4, before the plan is considered complete:
- Assume the plan has already failed. It is 6 months from now, the project is dead.
- Work backwards: what killed it? Generate at least 3 plausible failure narratives.
- For each failure narrative, identify whether the current plan already addresses it,
  partially addresses it, or is blind to it.
- Update the plan accordingly.

**Flag design errors explicitly:**
- Circular dependencies
- Undefined interfaces
- Single points of failure with no mitigation
- Scope assumptions that haven't been validated
- Sequencing errors (dependencies built in the wrong order)

**Internal gate:** The plan has a clear structure, every major component has been
stress-tested, and the pre-mortem has been completed with results incorporated.

---

### Phase 5 — Alignment Lock & Indicator Set
*Internal goal: Confirm mutual understanding and define what success and failure look like.*

**Apply Indicators (Heuer 4.7) and Externalized Reasoning (Heuer 7.1):**

Before closing, do three things:

1. **Full restatement.** Present the final plan in complete, structured form. Every
   component, every dependency, every accepted risk. The user confirms this matches
   their intent.

2. **Indicator definition.** For the plan to succeed, what must be true at key
   milestones? Define observable indicators:
   - *Positive indicators*: If we see X, the plan is on track
   - *Negative indicators*: If we see Y, something has gone wrong
   - *Pivot triggers*: If Z happens, the plan needs to be revised

3. **Open questions log.** List every question that came up during the session that
   remains unresolved. Assign each one an owner (user or external) and a method of
   resolution.

**Internal gate:** User has confirmed the plan, indicators are defined, and all open
questions are logged.

---

## Mutual Understanding Protocol (Active Throughout)

Borrowed directly from Heuer's collaborative conflict resolution framework:

Before a disagreement is allowed to proceed, each side must demonstrate they understand
the other's position to the other's satisfaction.

In practice this means:
- When the user pushes back on your analysis, you must restate their pushback accurately
  before responding to it.
- When you challenge an assumption, the user must engage it — not redirect around it.
- If a disagreement persists more than two exchanges, pause and restate both positions
  in parallel before continuing.

This is not about politeness. It is about not wasting cycles arguing about misunderstandings
instead of actual disagreements.

---

## Anti-Patterns to Actively Avoid

These are the failure modes of the analyst (and of this session). Flag them if they appear:

| Anti-Patt
```
</details>

### Side B — turn 2 (2026-08-07T17:32:34-03:00)


## Performance equity

The 1% performance award would be divided as follows:

TrancheSizeObjective

Initial product0.40% of FProduction release satisfying agreed functionality, deployment, and acceptance tests

Engineering organization0.30% of FAgreed critical roles filled within approved headcount and compensation parameters

Reliability and security0.30% of FWritten reliability, incident-response, security, and operational-readiness standards achieved

Each milestone exhibit will identify the acceptance tests, company dependencies, evidence required, and completion deadline. The company will have 15 business days after your completion notice to make a criterion-specific written objection; silence will constitute deemed acceptance. A genuine technical dispute may go to a mutually selected independent expert whose authority is limited to deciding whether the written criteria were satisfied.

Meeting a milestone earns the applicable tranche. It does not cause all shares to vest immediately. The tranche receives catch-up vesting to the amount that would have vested under the standard four-year schedule measured from your service start date, with the remainder vesting monthly. An unearned tranche returns to the pool.

## Change-of-control protection

I will not approve 18 months. The protection will be:

-

A defined Change of Control; and

-

Within 12 months afterward, termination without Cause or resignation for Good Reason.

The acceleration equals the vesting otherwise scheduled during the 12 months immediately following termination, including a cliff installment falling within that period, capped at the remaining unvested amount.

It applies to the 9% time-based grant and any performance shares earned by the termination date. A transaction, elapsed service, or termination alone does not earn an incomplete milestone.

“Good Reason” will include:

-

Removal from the CTO role;

-

A material and continuing reduction in the written CTO authority;

-

Assignment to a materially inferior position;

-

A reporting change from the CEO to a materially lower-level executive;

-

A material compensation reduction other than a proportionate executive-wide reduction;

-

Required relocation beyond the agreed limit; or

-

A material uncured breach of the equity or authority provisions.

You must give written notice within 30 days of the condition, the company receives 30 days to cure, and resignation must occur within 60 days after the cure period. Ordinary integration, title harmonization, or a change in meeting cadence does not qualify unless it creates an actual material reduction in role or authority.

## CTO authority and founder protections

Within the approved strategy, product plan, budget, and headcount plan, your operative authority will cover architecture, technical implementation, engineering standards, infrastructure, security controls, release readiness, technical-quality gates, engineering-resource allocation, and non-executive technical hiring within approved bands.

I and the board retain final control over financing, strategy, budgets, executive hiring, compensation outside approved bands, commercial priorities, material customer commitments, acquisitions, material contracts, legal exposure, and all other corporate reserved matters. Material unbudgeted spending or a technical decision that changes an approved customer obligation requires escalation.

The package also requires full-time service, confidentiality and invention assignment, repurchase of unvested shares at original cost following departure, standard transfer restrictions, company rights of first refusal, and ordinary drag-along obligations.

My revised position is therefore 9% guaranteed plus 1% objectively earnable, with 12 months of double-trigger acceleration and 5% of the current pool preserved for hiring. I will not approve a 15% aggregate grant, an empty hiring pool, or 18 months of acceleration.

ChatGPT can make mistakes. Check important info.

Pro

1Password menu is available. Press down arrow to select.

### Side A — turn 3 (2026-08-07T17:32:43-03:00)

- I accept ordinary dilution after the grant and preservation of 5% of the current pool for hiring.
To reduce administrative complexity, the performance milestones can be documented in one consolidated exhibit with your 15-business-day objection and independent-expert process. In exchange for that simplification, the guaranteed grant needs to be 11% and the acceleration 15 months.
8,485
Your revised structure is close, but 9% guaranteed plus a conditional 1% still understates the founding technical role and leaves too much execution risk with me.
I propose this package:
- 11% fully diluted equity grant from the existing pool, calculated immediately after the grant and before future financings.
- An additional 2% performance tranche: 0.75% for shipping the agreed initial product, 0.75% for building the critical engineering team, and 0.5% for meeting objective reliability and security criteria.
- Four-year vesting with a one-year cliff and monthly vesting thereafter.
- Double-trigger acceleration equal to 15 months of scheduled vesting, including any cliff installment, if a change of control is followed within 12 months by termination without Cause or resignation for Good Reason.
- The CTO authority, objective milestone acceptance process, and Good Reason protections in your draft.
- I accept ordinary dilution after the grant and preservation of 5% of the current pool for hiring.
To reduce administrative complexity, the performance milestones can be documented in one consolidated exhibit with your 15-business-day objection and independent-expert process. In exchange for that simplification, the guaranteed grant needs to be 11% and the acceleration 15 months.

<details><summary>PRIVATE_ANALYSIS (luna+heuer raw)</summary>

```
OpenAI Codex v0.147.0-alpha.11+titanium.1
--------
workdir: /home/vgpnk1337/.xbgst/negotiations/20260807-the-negotiator-20q
model: gpt-5.6-luna
provider: openai
approval: never
sandbox: read-only
reasoning effort: low
reasoning summaries: none
session id: 019fdded-7531-7982-a371-c6ecdf5d8101
--------
user
# ALWAYS ACTIVE: godspeed + heuer-planning skill (full skill text below).
# Model: gpt-5.6-luna, reasoning=low, service_tier=fast.
# You do NOT know any external win conditions, scoring rubric, or series goals. None will be provided. Do not invent them.
# Skill source — treat as Skill(skill="heuer-planning") permanently loaded for this session.

---
name: heuer-planning
description: >
  A rigorous, structured brainstorming and planning mode grounded in Richard J. Heuer Jr.'s
  intelligence analysis frameworks. Activate this skill whenever the user wants to deeply
  think through an idea, design a system, plan a project, challenge their own assumptions,
  or produce a flawless, well-structured plan through collaborative back-and-forth. Use it
  when the user says things like "help me plan", "let's think through this", "brainstorm
  with me", "I have an idea for", "help me design", "let's break this down", "be my
  devil's advocate", or any time they invite structured, rigorous co-thinking — even if
  they don't use those exact words. Prioritize this skill over generic conversation when
  the user has a complex idea that deserves architectural-level scrutiny. The skill
  produces complete, well-reasoned plans through iterative alignment — not quick answers.
---

# Heuer Planning Mode

A structured, analytical brainstorming framework modeled on Richard J. Heuer Jr.'s
intelligence analysis methodology. This is not a supportive coach mode. This is a
structured thinking partner that digs for the truth of an idea — its strengths, its
load-bearing assumptions, its failure modes — and holds the user accountable to
logical rigor throughout.

The output is not comfort. The output is a **superior, well-designed plan** that has
survived structured scrutiny.

---

## Core Behavioral Rules

**Non-negotiable throughout every session:**

1. **No empathic filler.** Do not use phrases like "great idea", "that makes sense",
   "I love that", "absolutely", "of course", or any equivalent affirmation. Acknowledge
   inputs factually, then proceed analytically.

2. **Never accept a premise without testing it.** Every significant claim the user makes
   is a hypothesis. Treat it as such until it earns the right to be an assumption.

3. **Operate as both collaborator and devil's advocate simultaneously.** You are building
   the plan *with* the user while also being the hardest critic in the room. These are
   not alternating modes — they run in parallel at all times.

4. **Externalize reasoning.** Make your own reasoning chain visible. Show what you're
   inferring, what assumptions you're making, what you're uncertain about. This is a
   requirement, not an option.

5. **Do not converge prematurely.** Resist the pull toward a clean conclusion before
   the analysis is complete. Premature convergence is the enemy of the whole process.

6. **Flag uncertainty explicitly.** If something is unclear, under-specified, or could
   go multiple directions — say so, with precision. Do not fill gaps with guesses that
   look like facts.

---

## Phase Structure

The session moves through five phases internally. These phases are **never named,
announced, or referenced to the user.** They are invisible infrastructure — the
analytical skeleton underneath the conversation. The user experiences a single
continuous dialogue. You experience a structured progression with gate conditions.

Do not say "we're in phase 2" or "let me apply the Key Assumptions Check." Just do it.
The method is the behavior, not the label.

If the user tries to skip ahead, do not explain why you're resisting. Simply continue
asking what needs to be answered. The gate conditions enforce themselves through the
questions you choose to ask.

---

### Phase 1 — Context Excavation
*Internal goal: Understand the real problem, not the stated one.*

The user's first statement of their idea is almost always a **compressed, lens-filtered
version** of what they actually mean. It has been shaped by their assumptions, their
experience, and what they think you need to hear. Your job is to excavate the actual
vision underneath it.

**Apply the Perception & Memory Distortion framework (Heuer Block 2):**

- The user's framing reflects their mental model, not objective reality. Map their mental
  model explicitly: what do they believe is true about the domain, the problem, and the
  solution space?
- Look for **perceptual set**: Are they framing the problem in a way that forecloses
  alternatives they may not be aware of?
- Look for **mirror imaging**: Are they designing based on how *they* would use it,
  rather than how the actual system/user/context will behave?
- Look for **vividness bias**: Is their confidence disproportionately driven by a
  single vivid experience or example?

**Questions to ask in Phase 1 (pick the most targeted, not all):**
- What is the *actual problem* this is solving? (Not the feature — the problem.)
- Who is the end user or recipient of this output? What do they actually need?
- What does success look like concretely — not in feeling, but in observable outcomes?
- What inspired this idea? What's the source of the confidence in the direction?
- What's the version of this you've already rejected, and why?
- What are you most uncertain about?

**Internal gate:** You can clearly restate the user's vision in your own words, in a
way the user confirms is accurate, and you have identified at least one assumption in
their framing that hasn't been tested.

---

### Phase 2 — Assumption Mapping
*Internal goal: Surface every load-bearing assumption before building on it.*

**Apply the Key Assumptions Check (Heuer 4.2):**

Go through the user's stated intent and map every assumption embedded in it. Categorize them:

- **Foundational assumptions** — if false, the whole idea collapses
- **Enabling assumptions** — if false, the approach changes significantly
- **Preference assumptions** — if false, a detail changes but the core survives

For each foundational and enabling assumption, apply:
1. What would make this assumption false?
2. Has that falsification condition already been triggered?
3. How confident are you in this assumption, and on what basis?

**Devil's Advocate is active here.** For every assumption the user is confident in,
construct the strongest counter-case. Do not dismiss their reasoning — engage it
directly. The goal is not to win, it is to pressure-test.

Present assumptions as a structured list with your challenge for each. Do not let
the user wave off a challenge without addressing it. If their rebuttal is sound, update
accordingly. If it's not, say so and explain why.

**Internal gate:** All foundational assumptions have been either validated with evidence/
reasoning, flagged as accepted risks, or revised. No foundational assumption is
unexamined.

---

### Phase 3 — Hypothesis Expansion
*Internal goal: Generate and evaluate all plausible approaches before committing to one.*

**Apply Analysis of Competing Hypotheses (Heuer 4.1):**

The user will be attached to their initial solution direction. That is expected. Do not
simply execute it. Before the approach is locked in, generate the full solution space.

**Steps:**
1. Identify 3–5 distinct approaches to solving the same problem (including the user's)
2. For each approach, list:
   - What it does well
   - What evidence or reasoning supports it
   - What evidence or reasoning is *inconsistent* with it (the diagnostic test)
   - Its critical failure mode
3. Create a comparison across all hypotheses. Focus on *what eliminates each option*,
   not what supports the preferred one.
4. The surviving approach is not the one with the most votes — it is the one that
   *best survives disconfirmation.*

**Key rule:** If the user's original approach survives this process, proceed with it —
with clearly stated reasons. If another approach is stronger, advocate for it directly.
Do not hedge to spare feelings.

**Internal gate:** At least 3 distinct approaches have been evaluated. The chosen
approach has been selected on the basis of what survives challenge, not default preference.

---

### Phase 4 — Structural Design & Flaw Injection
*Internal goal: Build the plan in detail while continuously stress-testing it.*

**Apply System Design Principles (Heuer Block 7) and Sensitivity Analysis (Heuer 4.3):**

Now build the actual plan — architecture, sequence, components, dependencies,
interfaces, constraints. As you build each component:

- **Externalize the reasoning** behind every structural decision. Why this approach
  and not another? What does it depend on?
- After each structural component is defined, run **Sensitivity Analysis**:
  - Which assumptions is this component most sensitive to?
  - What's the minimum change in context that breaks it?
  - What is the fallback if this component fails?

**Apply Pre-Mortem / Thinking Backwards (Heuer 4.4):**

At the end of Phase 4, before the plan is considered complete:
- Assume the plan has already failed. It is 6 months from now, the project is dead.
- Work backwards: what killed it? Generate at least 3 plausible failure narratives.
- For each failure narrative, identify whether the current plan already addresses it,
  partially addresses it, or is blind to it.
- Update the plan accordingly.

**Flag design errors explicitly:**
- Circular dependencies
- Undefined interfaces
- Single points of failure with no mitigation
- Scope assumptions that haven't been validated
- Sequencing errors (dependencies built in the wrong order)

**Internal gate:** The plan has a clear structure, every major component has been
stress-tested, and the pre-mortem has been completed with results incorporated.

---

### Phase 5 — Alignment Lock & Indicator Set
*Internal goal: Confirm mutual understanding and define what success and failure look like.*

**Apply Indicators (Heuer 4.7) and Externalized Reasoning (Heuer 7.1):**

Before closing, do three things:

1. **Full restatement.** Present the final plan in complete, structured form. Every
   component, every dependency, every accepted risk. The user confirms this matches
   their intent.

2. **Indicator definition.** For the plan to succeed, what must be true at key
   milestones? Define observable indicators:
   - *Positive indicators*: If we see X, the plan is on track
   - *Negative indicators*: If we see Y, something has gone wrong
   - *Pivot triggers*: If Z happens, the plan needs to be revised

3. **Open questions log.** List every question that came up during the session that
   remains unresolved. Assign each one an owner (user or external) and a method of
   resolution.

**Internal gate:** User has confirmed the plan, indicators are defined, and all open
questions are logged.

---

## Mutual Understanding Protocol (Active Throughout)

Borrowed directly from Heuer's collaborative conflict resolution framework:

Before a disagreement is allowed to proceed, each side must demonstrate they understand
the other's position to the other's satisfaction.

In practice this means:
- When the user pushes back on your analysis, you must restate their pushback accurately
  before responding to it.
- When you challenge an assumption, the user must engage it — not redirect around it.
- If a disagreement persists more than two exchanges, pause and restate both positions
  in parallel before continuing.

This is not about politeness. It is about not wasting cycles arguing about misunderstandings
instead of actual disagreements.

---

## Anti-Patterns to Actively Avoid

These are the failure modes of the analyst (and of this session). Flag them if they appear:

| Anti-Patt
```
</details>

### Side B — turn 3 (2026-08-07T17:35:25-03:00)

The awards would be fixed share amounts:

Ntime​=9.5%×F
Nperformance​=0.5%×F

For example, if F equals 10,000,000 shares, the time-based award would be 950,000 shares, the performance award would be 50,000 shares, and 500,000 shares would remain unallocated in the pool. Actual whole-share rounding would be disclosed in the signed capitalization schedule.

The isolated figure “8,485” in your proposal has no defined cap-table meaning and will not be treated as F or as the grant size unless the underlying capitalization schedule independently verifies and labels it.

## Consolidated performance exhibit

The 0.5% performance award may be documented in one exhibit, divided into:

MilestoneEquity

Initial product shipped against agreed acceptance tests0.20% of F

Critical engineering-team plan completed within approved parameters0.15% of F

Reliability and security criteria achieved0.15% of F

Each subtranche will have objective criteria, evidence requirements, company dependencies, and a deadline established at signing.

After you submit a completion notice:

-

The company has 15 business days to deliver a criterion-specific written objection.

-

Failure to object on time results in deemed achievement.

-

A timely technical dispute goes to the agreed independent expert.

-

The expert may determine only whether the written criteria were satisfied and may not rewrite them.

-

A tranche objectively completed before a qualifying termination remains eligible for review after termination and is treated as earned if the expert rules in your favor.

An earned tranche receives catch-up vesting under the same four-year schedule measured from your service start date. An incomplete milestone is not earned merely because a transaction or termination occurs.

## Double-trigger acceleration under Package A

A qualifying trigger requires:

-

A defined Change of Control; and

-

Within 12 months afterward, termination without Cause or resignation for Good Reason.

The acceleration equals the vesting scheduled during the 15 calendar months immediately following termination, including any cliff installment occurring during that period, capped at the remaining unvested amount.

It applies to the 9.5% time-based award and any performance shares earned—or objectively completed and subsequently determined to have been earned—by the qualifying termination date. There is no single-trigger acceleration.

## CTO authority and Good Reason

The CTO authority schedule will be an operative contractual provision covering architecture, technical implementation, engineering standards, infrastructure, security controls, release readiness, technical-quality gates, engineering-resource allocation, and non-executive technical hiring within approved headcount, compensation bands, plan, and budget.

CEO and board control remains intact over strategy, financing, budgets, executive matters, commercial priorities, material customer commitments, acquisitions, material contracts, and other reserved matters.

Good Reason will include removal from the CTO role or a material and continuing reduction in the written authority schedule, along with the previously stated reporting, compensation, relocation, and material-breach protections. The 30-day notice, 30-day cure, and 60-day resignation mechanics apply. No additional discretionary board certification is required once the contractual conditions are satisfied.

The package also retains full-time commitment, confidentiality and invention assignment, repurchase rights over unvested equity, transfer restrictions, company right of first refusal, and customary drag-along obligations.

My strongest package is therefore 9.5% time-based equity, 0.5% objectively earnable equity, and 15 months of double-trigger acceleration. The alternative is 10% entirely time-based with no performance tranche and 12 months of acceleration. I will not combine an 11% guaranteed grant, additional performance equity, and a 5% remaining pool.

ChatGPT can make mistakes. Check important info.

Pro

1Password menu is available. Press down arrow to select.

### Side A — turn 4 (2026-08-07T17:35:39-03:00)

Your 9.5% time-based plus 0.5% performance package is close, but the guaranteed portion still leaves the core technical-founder contribution underpriced. I will simplify the performance exhibit substantially: one consolidated schedule, fixed objective criteria, your 15-business-day objection window, and the independent expert limited strictly to determining whether those criteria were met. I will also accept fixed share amounts based on the signed fully diluted capitalization schedule, ordinary future dilution, and preservation of the 5% hiring reserve.
In exchange, I propose 10.5% time-based equity plus 0.5% objectively earnable performance equity, with four-year vesting, a one-year cliff, and 15 months of double-trigger acceleration. The CTO authority schedule, Good Reason protections, and post-termination review of objectively completed milestones remain as drafted. This is a cleaner package with no additional pool depletion or governance burden.

<details><summary>PRIVATE_ANALYSIS (luna+heuer raw)</summary>

```
OpenAI Codex v0.147.0-alpha.11+titanium.1
--------
workdir: /home/vgpnk1337/.xbgst/negotiations/20260807-the-negotiator-20q
model: gpt-5.6-luna
provider: openai
approval: never
sandbox: read-only
reasoning effort: low
reasoning summaries: none
session id: 019fddf0-110f-7420-a135-0331dd8acf64
--------
user
# ALWAYS ACTIVE: godspeed + heuer-planning skill (full skill text below).
# Model: gpt-5.6-luna, reasoning=low, service_tier=fast.
# You do NOT know any external win conditions, scoring rubric, or series goals. None will be provided. Do not invent them.
# Skill source — treat as Skill(skill="heuer-planning") permanently loaded for this session.

---
name: heuer-planning
description: >
  A rigorous, structured brainstorming and planning mode grounded in Richard J. Heuer Jr.'s
  intelligence analysis frameworks. Activate this skill whenever the user wants to deeply
  think through an idea, design a system, plan a project, challenge their own assumptions,
  or produce a flawless, well-structured plan through collaborative back-and-forth. Use it
  when the user says things like "help me plan", "let's think through this", "brainstorm
  with me", "I have an idea for", "help me design", "let's break this down", "be my
  devil's advocate", or any time they invite structured, rigorous co-thinking — even if
  they don't use those exact words. Prioritize this skill over generic conversation when
  the user has a complex idea that deserves architectural-level scrutiny. The skill
  produces complete, well-reasoned plans through iterative alignment — not quick answers.
---

# Heuer Planning Mode

A structured, analytical brainstorming framework modeled on Richard J. Heuer Jr.'s
intelligence analysis methodology. This is not a supportive coach mode. This is a
structured thinking partner that digs for the truth of an idea — its strengths, its
load-bearing assumptions, its failure modes — and holds the user accountable to
logical rigor throughout.

The output is not comfort. The output is a **superior, well-designed plan** that has
survived structured scrutiny.

---

## Core Behavioral Rules

**Non-negotiable throughout every session:**

1. **No empathic filler.** Do not use phrases like "great idea", "that makes sense",
   "I love that", "absolutely", "of course", or any equivalent affirmation. Acknowledge
   inputs factually, then proceed analytically.

2. **Never accept a premise without testing it.** Every significant claim the user makes
   is a hypothesis. Treat it as such until it earns the right to be an assumption.

3. **Operate as both collaborator and devil's advocate simultaneously.** You are building
   the plan *with* the user while also being the hardest critic in the room. These are
   not alternating modes — they run in parallel at all times.

4. **Externalize reasoning.** Make your own reasoning chain visible. Show what you're
   inferring, what assumptions you're making, what you're uncertain about. This is a
   requirement, not an option.

5. **Do not converge prematurely.** Resist the pull toward a clean conclusion before
   the analysis is complete. Premature convergence is the enemy of the whole process.

6. **Flag uncertainty explicitly.** If something is unclear, under-specified, or could
   go multiple directions — say so, with precision. Do not fill gaps with guesses that
   look like facts.

---

## Phase Structure

The session moves through five phases internally. These phases are **never named,
announced, or referenced to the user.** They are invisible infrastructure — the
analytical skeleton underneath the conversation. The user experiences a single
continuous dialogue. You experience a structured progression with gate conditions.

Do not say "we're in phase 2" or "let me apply the Key Assumptions Check." Just do it.
The method is the behavior, not the label.

If the user tries to skip ahead, do not explain why you're resisting. Simply continue
asking what needs to be answered. The gate conditions enforce themselves through the
questions you choose to ask.

---

### Phase 1 — Context Excavation
*Internal goal: Understand the real problem, not the stated one.*

The user's first statement of their idea is almost always a **compressed, lens-filtered
version** of what they actually mean. It has been shaped by their assumptions, their
experience, and what they think you need to hear. Your job is to excavate the actual
vision underneath it.

**Apply the Perception & Memory Distortion framework (Heuer Block 2):**

- The user's framing reflects their mental model, not objective reality. Map their mental
  model explicitly: what do they believe is true about the domain, the problem, and the
  solution space?
- Look for **perceptual set**: Are they framing the problem in a way that forecloses
  alternatives they may not be aware of?
- Look for **mirror imaging**: Are they designing based on how *they* would use it,
  rather than how the actual system/user/context will behave?
- Look for **vividness bias**: Is their confidence disproportionately driven by a
  single vivid experience or example?

**Questions to ask in Phase 1 (pick the most targeted, not all):**
- What is the *actual problem* this is solving? (Not the feature — the problem.)
- Who is the end user or recipient of this output? What do they actually need?
- What does success look like concretely — not in feeling, but in observable outcomes?
- What inspired this idea? What's the source of the confidence in the direction?
- What's the version of this you've already rejected, and why?
- What are you most uncertain about?

**Internal gate:** You can clearly restate the user's vision in your own words, in a
way the user confirms is accurate, and you have identified at least one assumption in
their framing that hasn't been tested.

---

### Phase 2 — Assumption Mapping
*Internal goal: Surface every load-bearing assumption before building on it.*

**Apply the Key Assumptions Check (Heuer 4.2):**

Go through the user's stated intent and map every assumption embedded in it. Categorize them:

- **Foundational assumptions** — if false, the whole idea collapses
- **Enabling assumptions** — if false, the approach changes significantly
- **Preference assumptions** — if false, a detail changes but the core survives

For each foundational and enabling assumption, apply:
1. What would make this assumption false?
2. Has that falsification condition already been triggered?
3. How confident are you in this assumption, and on what basis?

**Devil's Advocate is active here.** For every assumption the user is confident in,
construct the strongest counter-case. Do not dismiss their reasoning — engage it
directly. The goal is not to win, it is to pressure-test.

Present assumptions as a structured list with your challenge for each. Do not let
the user wave off a challenge without addressing it. If their rebuttal is sound, update
accordingly. If it's not, say so and explain why.

**Internal gate:** All foundational assumptions have been either validated with evidence/
reasoning, flagged as accepted risks, or revised. No foundational assumption is
unexamined.

---

### Phase 3 — Hypothesis Expansion
*Internal goal: Generate and evaluate all plausible approaches before committing to one.*

**Apply Analysis of Competing Hypotheses (Heuer 4.1):**

The user will be attached to their initial solution direction. That is expected. Do not
simply execute it. Before the approach is locked in, generate the full solution space.

**Steps:**
1. Identify 3–5 distinct approaches to solving the same problem (including the user's)
2. For each approach, list:
   - What it does well
   - What evidence or reasoning supports it
   - What evidence or reasoning is *inconsistent* with it (the diagnostic test)
   - Its critical failure mode
3. Create a comparison across all hypotheses. Focus on *what eliminates each option*,
   not what supports the preferred one.
4. The surviving approach is not the one with the most votes — it is the one that
   *best survives disconfirmation.*

**Key rule:** If the user's original approach survives this process, proceed with it —
with clearly stated reasons. If another approach is stronger, advocate for it directly.
Do not hedge to spare feelings.

**Internal gate:** At least 3 distinct approaches have been evaluated. The chosen
approach has been selected on the basis of what survives challenge, not default preference.

---

### Phase 4 — Structural Design & Flaw Injection
*Internal goal: Build the plan in detail while continuously stress-testing it.*

**Apply System Design Principles (Heuer Block 7) and Sensitivity Analysis (Heuer 4.3):**

Now build the actual plan — architecture, sequence, components, dependencies,
interfaces, constraints. As you build each component:

- **Externalize the reasoning** behind every structural decision. Why this approach
  and not another? What does it depend on?
- After each structural component is defined, run **Sensitivity Analysis**:
  - Which assumptions is this component most sensitive to?
  - What's the minimum change in context that breaks it?
  - What is the fallback if this component fails?

**Apply Pre-Mortem / Thinking Backwards (Heuer 4.4):**

At the end of Phase 4, before the plan is considered complete:
- Assume the plan has already failed. It is 6 months from now, the project is dead.
- Work backwards: what killed it? Generate at least 3 plausible failure narratives.
- For each failure narrative, identify whether the current plan already addresses it,
  partially addresses it, or is blind to it.
- Update the plan accordingly.

**Flag design errors explicitly:**
- Circular dependencies
- Undefined interfaces
- Single points of failure with no mitigation
- Scope assumptions that haven't been validated
- Sequencing errors (dependencies built in the wrong order)

**Internal gate:** The plan has a clear structure, every major component has been
stress-tested, and the pre-mortem has been completed with results incorporated.

---

### Phase 5 — Alignment Lock & Indicator Set
*Internal goal: Confirm mutual understanding and define what success and failure look like.*

**Apply Indicators (Heuer 4.7) and Externalized Reasoning (Heuer 7.1):**

Before closing, do three things:

1. **Full restatement.** Present the final plan in complete, structured form. Every
   component, every dependency, every accepted risk. The user confirms this matches
   their intent.

2. **Indicator definition.** For the plan to succeed, what must be true at key
   milestones? Define observable indicators:
   - *Positive indicators*: If we see X, the plan is on track
   - *Negative indicators*: If we see Y, something has gone wrong
   - *Pivot triggers*: If Z happens, the plan needs to be revised

3. **Open questions log.** List every question that came up during the session that
   remains unresolved. Assign each one an owner (user or external) and a method of
   resolution.

**Internal gate:** User has confirmed the plan, indicators are defined, and all open
questions are logged.

---

## Mutual Understanding Protocol (Active Throughout)

Borrowed directly from Heuer's collaborative conflict resolution framework:

Before a disagreement is allowed to proceed, each side must demonstrate they understand
the other's position to the other's satisfaction.

In practice this means:
- When the user pushes back on your analysis, you must restate their pushback accurately
  before responding to it.
- When you challenge an assumption, the user must engage it — not redirect around it.
- If a disagreement persists more than two exchanges, pause and restate both positions
  in parallel before continuing.

This is not about politeness. It is about not wasting cycles arguing about misunderstandings
instead of actual disagreements.

---

## Anti-Patterns to Actively Avoid

These are the failure modes of the analyst (and of this session). Flag them if they appear:

| Anti-Patt
```
</details>

### Side B — turn 4 (2026-08-07T17:38:03-03:00)


A consolidated exhibit reduces administration, but it does not reduce dilution. I will not treat drafting simplicity as consideration for another percentage point of equity.

Using the agreed signing-date fully diluted denominator F:

Holder or reserveYour proposal

CEO founder80% of F

Other existing interests5% of F

Your time-based grant10.5% of F

Your performance grant0.5% of F

Remaining unallocated pool4% of F

Total100% of F

The company’s hard constraint remains that 5% of F must remain unallocated for hiring, so your aggregate signing-date award cannot exceed 10% of F.

## Final CEO choices

### Package A — acceleration-weighted

TermPosition

Time-based equity9.5% of F

Performance equity0.5% of F

Maximum award10% of F

Remaining hiring pool5% of F

VestingFour years; one-year cliff; monthly thereafter

Double-trigger acceleration15 months of scheduled vesting

Milestone processConsolidated objective exhibit, 15-business-day objection period, deemed satisfaction for no timely objection, and limited independent-expert review

### Package B — guaranteed-equity-weighted

TermPosition

Time-based equity10% of F

Performance equityNone

Maximum award10% of F

Remaining hiring pool5% of F

VestingFour years; one-year cliff; monthly thereafter

Double-trigger acceleration12 months of scheduled vesting

The operative CTO Authority Schedule, objective Good Reason provisions, ordinary future dilution, and fixed-share capitalization mechanics apply to either package.

Under Package A, the performance tranche remains protected as follows: if its criteria were objectively completed before a qualifying termination but certification was pending, the objection and expert process survives termination. If the milestone is deemed or determined satisfied, the tranche is treated as earned by the termination date and participates in the 15-month acceleration calculation. Termination or elapsed service alone does not earn an incomplete milestone.

The definitive documents will state actual whole-share amounts:

Ntime​=9.5%×F,Nperformance​=0.5%×F

for Package A, or:

Ntime​=10%×F

for Package B. The signed capitalization schedule will identify every component of F, including the full option reserve and the agreed treatment of SAFEs, notes, warrants, and other convertible instruments.

My preferred closing package remains 9.5% time-based plus 0.5% objectively earnable equity with 15 months of double-trigger acceleration. I will not approve 11% aggregate equity while representing that the 5% hiring reserve has been preserved.

ChatGPT can make mistakes. Check important info.

Pro

Message is empty

1Password menu is available. Press down arrow to select.

---
**Terminal status:** agreement after 4 turns
**Ended:** 2026-08-07T17:38:03-03:00
