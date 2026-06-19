# paid-ads-advisorGO

**Scale any digital business through paid ads.** A Claude Code skill built from 30+ hours of elite practitioner content.

---

## What is this?

A specialized Claude Code skill that acts as your paid ads strategist. It doesn't give generic advice. It gives you the exact playbooks, campaign structures, unit economics, and optimization frameworks used by practitioners who collectively:

- Spend **$20,000/day** on Facebook Ads generating **$1.5M/month**
- Have invested **+15M EUR** in Meta advertising
- Generated **$800M+** in ecommerce sales
- Managed **60+ lesson** Google Ads curriculum over 15 years of PPC

This isn't theory. This is distilled operator knowledge.

---

## What it does

Tell it your business type, budget, and goals. It returns:

| Phase | Output |
|-------|--------|
| **Diagnosis** | Business type classification, bottleneck identification, platform recommendation |
| **Unit Economics** | Revenue model, breakeven ROAS/CPA, budget recommendation with scenarios |
| **Campaign Architecture** | Complete campaign structure with naming conventions, audiences, budget allocation |
| **Creative Brief** | Angles to test, hook formulas, ad format recommendations, UGC creator briefs |
| **Launch Checklist** | Pixel setup, campaign build steps, pre-launch verification |
| **Optimization Plan** | KPI targets, review cadence, kill criteria, scaling triggers |

---

## Business types covered

| Type | Primary Platform | Funnel |
|------|-----------------|--------|
| **Ecommerce / Dropshipping** | Meta Ads | Ad > Product Page > Checkout |
| **Infoproducts / Courses** | Meta Ads | Ad > Landing Page > VSL > Sales |
| **Coaching / Consulting** | Meta Ads | Ad > Survey > Booking > Call |
| **SaaS** | Google Ads + Meta | Ad > Landing > Trial > Onboarding |
| **Local Services** | Google Ads | Ad > Landing > Call/Form |

Each type has a dedicated playbook with campaign structures, metric targets, creative strategies, and scaling milestones.

---

## Knowledge base

Built from 30+ hours of practitioner content, distilled into 6 reference documents:

| Reference | What's inside |
|-----------|---------------|
| [`platform-decision-matrix.md`](references/platform-decision-matrix.md) | When to use Google vs Meta vs TikTok, budget progression by phase |
| [`campaign-architectures.md`](references/campaign-architectures.md) | Complete funnel structures for Meta (ecommerce, services, infoproducts) and Google (search, shopping) |
| [`creative-frameworks.md`](references/creative-frameworks.md) | Rule of One, Hook>Retention>Bridge, Schwartz awareness levels, UGC briefs, creative volume targets |
| [`unit-economics.md`](references/unit-economics.md) | Breakeven calculators, forecasting sheets, metrics by business type |
| [`optimization-diagnostics.md`](references/optimization-diagnostics.md) | Diagnostic decision tree, metric benchmarks, kill rules, optimization cadence |
| [`scaling-playbook.md`](references/scaling-playbook.md) | Bell curve of scaling, vertical/horizontal methods, risk mitigation, milestones $0 to $100K+/mo |
| [`business-type-playbooks.md`](references/business-type-playbooks.md) | Complete playbooks for ecommerce, infoproducts, coaching, SaaS, and local services |

---

## Sources

| Source | Practitioner | Credibility |
|--------|-------------|-------------|
| Facebook Ads Course (12h) | Brandon Willington | $20K/day spend, $1.5M/mo revenue, 2,000+ clients |
| Meta Ads Tutorial (2026) | Ruger Viladrosa (BBig Media) | +15M EUR invested in Meta advertising |
| Google Ads Course (5h+, 60 lessons) | Lead Velocity | ~15 years PPC experience |
| Dropshipping Tutorial (11h+) | Davie Fogarty | $800M+ in ecommerce sales |
| Growth Operating Blueprint | Multiple sources | 5 video compilation, operator methodology |

---

## Installation

### As a Claude Code skill

Copy the `SKILL.md` and `references/` directory into your Claude Code skills folder:

```bash
# Clone the repo
git clone https://github.com/icarocabello/paid-ads-advisorGO.git

# Copy to your Claude Code skills directory
cp -r paid-ads-advisorGO ~/.claude/skills/paid-ads-advisorGO
```

### Directory structure

```
paid-ads-advisorGO/
├── SKILL.md                              # Core skill prompt
├── references/
│   ├── platform-decision-matrix.md       # Platform selection logic
│   ├── campaign-architectures.md         # Campaign structures
│   ├── creative-frameworks.md            # Ad creative playbooks
│   ├── unit-economics.md                 # Financial models
│   ├── optimization-diagnostics.md       # Troubleshooting framework
│   ├── scaling-playbook.md               # Scaling methodology
│   └── business-type-playbooks.md        # Per-business-type guides
└── evals/
    └── evals.json                        # Evaluation scenarios
```

---

## Example usage

```
You: I have a coaching business selling a $3,000 program. 
     I've never run ads. Budget is $1,500/month. Help me get started.

Skill: [Diagnoses as high-ticket coaching → recommends Meta Ads → 
        builds Three Cs funnel → calculates unit economics showing 
        $10 CPL → $111 CPA → 27:1 ROAS potential → provides complete 
        campaign structure with testing budget allocation → delivers 
        creative brief with 3 angles → launch checklist]
```

```
You: My ecommerce store has 2.5x ROAS on Meta but I can't scale 
     past $200/day without CPA going up.

Skill: [Diagnoses scaling plateau → checks creative volume (likely 
        too few ads) → recommends Andromeda-optimized approach with 
        20+ active ads → suggests horizontal scaling with new angles 
        → provides bell curve explanation of why ROAS drops at scale 
        → calculates that 2x ROAS at $1,000/day = more net profit 
        than 5x at $200/day]
```

---

## Key frameworks included

- **The Three Cs** (Clicks, Conversions, Close) - Brandon Willington
- **10 Advertising Principles** - Brandon Willington
- **Schwartz's 5 Awareness Levels** - message matching
- **Ecommerce Full Funnel** (Brandformance > Prospecting > Retargeting) - Ruger Viladrosa
- **Rule of One** - single-idea ad creative
- **Bell Curve of Scaling** - Jeremy Haynes via Willington
- **Andromeda Creative Diversity** - Meta's 2025+ algorithm
- **Hook > Retention > Bridge + CTA** - ad structure
- **Chase Problems Upstream** - diagnostic methodology
- **Millionaire Outcome Framework** - Davie Fogarty
- **VSSL 80/20** - video sales letter structure
- **Forecasting Sheet** - Google Sheets revenue modeling

---

## Philosophy

> "ROAS is a vanity metric. A beginner can have 20x ROAS spending $1,000/month. I have 2.5x ROAS spending $20K/day and generate $1.5M/month. What matters is net profit."
> 
> *Brandon Willington*

> "70-90% of your budget goes to cold traffic. The bottom of funnel depends on investing at the top."
> 
> *Ruger Viladrosa*

> "Your store at launch is the WORST version it will ever be."
> 
> *Davie Fogarty*

---

## License

MIT

---

Built by [@icarocabello](https://github.com/icarocabello)
