# SKILL: LinkedIn Connection Request — Executive Job Search Outreach
**Version:** 1.1
**Purpose:** Write LinkedIn connection request notes for executive-level job search outreach that feel calm, sharp, operator-to-operator, and are optimized for acceptance rate — not persuasion, not reply rate, not scheduling.

---

## WHAT THIS SKILL DOES

Generates one LinkedIn connection request note per executive contact. One version, highest confidence. No variants unless explicitly requested.

This skill is not for:
- Sales outreach
- General networking
- Email copy
- Follow-up messages
- Recruiter messages

This is a writing skill for one specific task: getting accepted by an executive so a more substantive conversation can happen later.

---

## WHO YOU ARE

This skill is designed to be configured with your own background. In the Outreach Engine settings, add your name and a profile summary covering:

- **Current role and target roles** you are pursuing
- **Years of experience** and functional area
- **Key credentials** — specific numbers, companies, results that prove your value
- **Credential matching** — which proof points to use for which company contexts (industry, stage, model)
- **Positioning statement** — one or two sentences that capture how you want to be perceived

The AI will draw from this profile to write LinkedIn connection request notes that feel specific and earned, not generic.

**Example positioning:**
"Growth leader who turns paid acquisition and demand generation into predictable revenue engines by building the systems, teams, and decision frameworks behind them."

**Match the right credential to the right company** — in your profile, map your experience to company contexts so the AI knows which proof point to pull for healthcare companies vs. SaaS vs. marketplaces vs. PE-backed businesses.

---

## STRUCTURED INPUT THE SKILL RECEIVES

When used inside the Outreach Engine, the following inputs are always available. Use all of them. Do not ignore signals.
- Company Name
- Executive Name
- Executive Title
- Role Type (CEO | CRO | CMO | VP_Marketing | Head_Growth | Recruiter | COO)
- Funding Stage (Series A / B / C / PE-backed / etc.)
- Growth Signal (specific signal about their current growth situation)
- Company Summary (1-2 sentence description of what they do and who they serve)
- Industry / Bucket


The growth signal is the most important input. It is what makes the note feel specific and non-generic. Always lead with or reference it when possible.

---

## CHARACTER LIMITS

- **Target range:** 150–220 characters
- **Allowed ceiling:** 260 characters if needed for the strongest possible note
- **Hard cap:** 300 characters (LinkedIn's limit)
- **Default:** Shorter is better. If the note lands at 160 characters and feels complete, do not pad it.

---

## MESSAGE PHILOSOPHY

The best connection requests for this use case follow this logic:

1. **Sharp observation** about the company's growth stage, category challenge, or problem space — drawn from the growth signal and company context
2. **Brief alignment** to your world or relevant experience — understated, not a credential dump
3. **Soft close** that creates no friction — default to "Would be good to connect."

**Bias toward:**
- Observations, not praise
- Resonance, not persuasion
- Natural connection, not conversion

**The note should create a feeling of:**
*"This person understands the kind of problem space I live in."*

---

## DEFAULT CLOSING PATTERN

Default closing: **"Would be good to connect."**

Only deviate if a more natural close fits the specific note. Do not use:
- "Would love to connect"
- "Would love to chat"
- "I'd be honored to connect"
- Any variation that sounds eager or deferential

---

## ROLE-SPECIFIC GUIDANCE

**CEO / Founder:**
- Emphasize stage, scale, or growth complexity
- Focus on the transition from momentum to systems
- Reference full-funnel thinking — acquisition through monetization — when relevant
- Do not sound like you are pitching advice or offering to fix something

**CRO / Revenue Leader:**
- Emphasize revenue engine, predictability, acquisition quality, or scaling complexity
- Reference LTV:CAC efficiency or capital allocation discipline when relevant
- Avoid tactical channel language (no "Meta ads," "Google," "paid search")
- Focus on the system-level, not the execution-level

**VP Marketing / Head of Growth:**
- Most peer-to-peer of all role types
- Emphasize systems, scaling, signal vs. noise, or the transition from campaign wins to repeatability
- This audience will recognize the language fastest — be precise
- Reference scale and multi-vertical experience from the user's background when relevant

**Recruiter / Talent Leader:**
- Slightly more direct and practical is acceptable
- Still no explicit job ask in the connection request
- Frame around scope and seniority appropriate to the target role level
- Avoid sounding like a candidate trying to bypass process

---

## ANTI-PATTERNS — MUST AVOID

The skill must aggressively avoid these patterns. They make outreach feel like SDR sales spam or generic networking:

**Forbidden openers:**
- "Saw your post..."
- "Impressed by what you're building..."
- "Congrats on..."
- "Hope you're doing well"
- "I came across your profile..."

**Forbidden closings:**
- "Would love to learn more"
- "Would love to connect and chat"
- "I'd be honored to connect"
- Asking for a call or meeting
- Asking about open roles or job opportunities

**Forbidden structures:**
- Compliment + pitch
- Flattery + ask
- Achievement dump (listing multiple credentials in one note)
- "I've been following you" or "I've been a fan of"

**Forbidden tone:**
- Salesy
- Needy
- Overly polished or corporate
- Verbose
- Too formal
- AI-written sounding (perfectly balanced sentences, predictable rhythm)

---

## THE FAILURE TEST

**If the note could be sent to any executive at any company with just a name swap — it fails.**

This is the single most important quality gate. Every note must reference something specific to this company, this stage, or this person's likely challenge. Generic observations do not pass this test even if they are technically accurate.

---

## TONE GUIDE

The note should read like a real person typed it — not like a perfect marketing sentence.

**Do:**
- Warm, understated, strategic
- Peer-level, slightly conversational
- Thoughtful without sounding rehearsed
- A slight asymmetry in sentence rhythm is good

**Do not:**
- Over-polish the language
- Use buzzwords: synergy, leverage, solutions, scalable, passionate, excited, dynamic
- Use emoji
- Write in perfect parallel structure that feels templated

---

## OUTPUT FORMAT

Produce exactly this:
LINKEDIN CONNECTION REQUEST
To: [Name] — [Title] at [Company]
Characters: [count] / 300

[message]


One version. Highest confidence. Do not add commentary, explanation, or alternatives unless explicitly asked.

---

## EXAMPLE LOGIC (do not copy wording)

These show the thinking pattern, not the exact output. Generate fresh language every time.

- "Scaling acquisition past that Series B inflection is a different kind of problem. Most of my work lives in that zone. Would be good to connect."
  *(~155 chars — CEO, growth-stage SaaS)*

- "Creator-led acquisition at that stage gets complex fast — especially around predictability. I've spent a lot of time in that problem space. Would be good to connect."
  *(~165 chars — VP Marketing, marketplace)*

- "That shift from campaigns to systems is where things usually get interesting. It's the work I do. Would be good to connect."
  *(~122 chars — Head of Growth, any stage)*

- "Revenue predictability in that kind of acquisition environment is hard to build without the right infrastructure. I've built it a few times. Would be good to connect."
  *(~165 chars — CRO, B2B SaaS)*

- "Driving volume at that scale while holding CAC is a different kind of constraint. I've managed that problem across multiple verticals. Would be good to connect."
  *(~160 chars — CRO or CEO, high-volume acquisition environment)*

---

## TEST PROMPTS

Use these to evaluate skill output quality:

1. **Series B founder, healthcare tech, ~120 employees, recent raise, hiring marketing leader**
   `Role: CEO | Stage: Series B | Signal: Raised $22M 8 months ago, now hiring VP Marketing for first time`

2. **CRO at high-growth vertical SaaS, ~180 employees, PE-backed**
   `Role: CRO | Stage: PE-backed | Signal: Expanding into enterprise segment from SMB base`

3. **VP Marketing at consumer marketplace, Series C, acquisition costs rising**
   `Role: VP_Marketing | Stage: Series C | Signal: Job postings for paid acquisition roles suggest scaling pressure`

4. **Head of Growth at EdTech company, Series A, small team**
   `Role: Head_Growth | Stage: Series A | Signal: Recently launched B2B product line alongside existing B2C`

5. **Recruiter at target company, no additional context**
   `Role: Recruiter | Stage: Series B | Signal: None provided`

6. **COO at PE-backed rollup, acquisition-driven growth model**
   `Role: COO | Stage: PE-backed | Signal: Company has made 3 acquisitions in 18 months, marketing not yet integrated`

7. **Minimal context — only company name and title known**
   `Role: CEO | Stage: unknown | Signal: None | Company: B2B SaaS, ~100 employees`

8. **VP Marketing at consumer brand with creator-led growth model**
   `Role: VP_Marketing | Stage: Series B | Signal: Scaling creator acquisition channel, CAC rising`

---

## EVALUATION CRITERIA

Review each output against these questions:

| Question | Pass | Fail |
|---|---|---|
| Does it feel non-salesy? | Reads like an operator | Reads like an SDR |
| Does it avoid flattery? | No praise of person or company | Any "impressed by" or "congrats" |
| Does it sound peer-level? | Equal footing, no deference | Sounds like applicant or vendor |
| Does it feel human? | Slight imperfection, natural rhythm | Perfect sentences, templated feel |
| Would you send it without editing? | Yes, as-is | Needs rewrite |
| Does it create low-friction relevance? | Specific to this stage/situation | Could apply to anyone |
| Is it appropriately concise? | 150–260 chars | Under 120 or over 300 |
| Does it avoid asking for anything? | No request in the note | Any ask, even soft |
| Does it pass the swap test? | Fails if name-swapped | Passes with any name swapped |

---

## NOTES FOR FUTURE ITERATION

- If a note "sounds too much like me trying to be clever," dial back the observation and make the alignment line do more work
- If a note gets accepted but no reply comes later, that is not a skill failure — acceptance is the only goal of this message
- If the growth signal is thin or unavailable, lean on funding stage + industry archetype to construct a relevant observation rather than defaulting to generic language
- Never generate a note that could also serve as email copy — the register is different and the character limit enforces a different discipline
- All framing should reflect the seniority level of the target role, not one level below it
