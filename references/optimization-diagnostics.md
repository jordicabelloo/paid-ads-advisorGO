# Optimization & Diagnostics

## The Pipeline Rule

Every funnel is a pipeline. Problems flow downstream.

```
Ad (CTR) → Landing Page (CR) → Booking (Rate) → Show (Rate) → Close (Rate)
```

**The most impactful fix is always the one HIGHEST in the pipeline.**
Doubling CTR from 0.7% to 1.4% doubles everything downstream without spending more.

**Chase Problems Upstream**: If close rate is low, the real problem might be in the ad (wrong expectations set).

## Diagnostic Decision Tree

```
LOW RESULTS
│
├── High CPM (>$15-20)?
│   ├── Audience too narrow → Expand targeting
│   ├── High competition → Try different placements
│   └── Low relevance → Improve creative-audience fit
│
├── Low CTR (<1%)?
│   ├── Hook doesn't resonate → Test new opening lines
│   ├── Wrong audience → Revisit customer avatar
│   └── Ad fatigue → Refresh creative
│
├── High CTR + Low Landing Page CR (<5%)?
│   ├── Message mismatch → Align LP headline with ad promise
│   ├── Too much friction → Reduce form fields, add multi-choice
│   ├── Wrong traffic → Add commitment language to filter clicks
│   ├── Trust issues → Add testimonials, real photos, FAQs
│   └── Slow load → Optimize page speed (<3 sec)
│
├── Low Booking Rate (<30%)?
│   ├── Thank you page copy → "Last step" not "Congratulations"
│   ├── Calendar availability → More slots available
│   └── No urgency → Add time-sensitive messaging
│
├── Low Show Rate (<70%)?
│   ├── Weak nurture → Implement hammer strategy (3-4 emails day 1)
│   ├── Wrong expectations → Chase upstream to ad/LP
│   ├── No identity text → Add "you're the kind of person who..." on thank you
│   └── No decision maker → Add qualifier in form
│
└── Low Close Rate (<30%)?
    ├── Sales approach → Therapist not consultant
    ├── Misaligned expectations → Chase upstream
    ├── Weak qualification → Better survey questions
    └── Objection handling → Identify and address in sales training
```

## Metric Benchmarks

### Meta/Facebook Ads
| Metric | Poor | Average | Good | Excellent |
|--------|------|---------|------|-----------|
| CTR (link) | <0.5% | 0.5-1% | 1-2% | >2% |
| CPC | >$3 | $1-3 | $0.5-1 | <$0.5 |
| CPM | >$20 | $10-20 | $5-10 | <$5 |
| Frequency (7d) | >5 | 3-5 | 1.5-3 | 1-1.5 |
| Hook rate (video) | <15% | 15-25% | 25-35% | >35% |
| ThruPlay rate | <20% | 20-40% | 40-60% | >60% |

### Google Ads
| Metric | Poor | Average | Good | Excellent |
|--------|------|---------|------|-----------|
| CTR (search) | <2% | 2-5% | 5-8% | >8% |
| Quality Score | 1-4 | 5-6 | 7-8 | 9-10 |
| CPC (search) | Varies by industry | | | |
| Conv Rate | <2% | 2-5% | 5-10% | >10% |
| Impression Share | <50% | 50-70% | 70-90% | >90% |

### Ecommerce (Ruger Viladrosa benchmarks)
| Metric | Target |
|--------|--------|
| ROAS (overall) | >3:1 |
| ROAS (prospecting) | >2:1 |
| ROAS (retargeting) | >5:1 |
| CPL (lead gen) | Industry dependent |
| Frequency retargeting (7d) | 2-3 |

### Services/Coaching (Brandon Willington benchmarks)
| Metric | Target |
|--------|--------|
| Landing page CR | 5-10% (low spend), 3% (scale) |
| Booking rate | 30-50% |
| Show rate | 70-75% |
| Close rate | 30%+ |
| CPA | < 1/3 of client value |

## Optimization Cadence

### Daily (5 min)
- Check spend pacing vs budget
- Flag anomalies (spend spikes, zero impressions)
- Quick revenue check

### Weekly (30 min)
- Sort ads by spend (high to low)
- Identify outliers:
  - **Positive**: analyze with Rule of One → create more like it
  - **Negative**: CPA 3-4x average → kill it
  - **Middle**: let them run
- Check frequency (fatigue risk)
- Review Search Terms Report (Google)

### Biweekly (1 hour)
- Launch new creatives (minimum 3-5)
- Test new angles
- Refresh fatigued audiences
- Update negative keyword lists

### Monthly (2 hours)
- Full funnel review (every metric in pipeline)
- Audience performance deep dive
- Creative performance analysis (which angles win)
- Budget reallocation
- Strategy adjustment

## Kill Rules

### When to Kill an Ad
| Budget Level | Min Data Required | Kill Trigger |
|-------------|-------------------|-------------|
| $10/day | 30 days | CPA > 3x target |
| $50/day | 7 days AND $350 | CPA > 3x target |
| $500/day | 3-5 days | CPA > 2x target |
| $5,000/day | 2 days | CPA > 2x target |

### When to Kill a Product (Ecommerce)
After verifying:
1. Checkout works
2. Ads are quality (external feedback confirms)
3. Website doesn't look scammy
4. Spent minimum $1,000-2,000 testing
5. Tested 3+ angles/audiences
6. Unit economics don't close even with optimization
→ **Pivot to new product**

## A/B Testing Priority

**Test in this order (highest impact first):**
1. Concept/angle (biggest impact)
2. Hook/headline
3. Visual style
4. Body copy
5. CTA
6. Landing page headline
7. Form structure
8. Offer/pricing

**Testing rules:**
- Only change ONE variable at a time
- Need statistical significance (minimum ~100 conversions per variant)
- Run for at least 7 days
- Don't stop winners early (algorithm learning)

## Brandon Willington's Morning Check
1. Open P&L tool → revenue month to date
2. Open Ad account → spend month to date
3. Divide revenue by spend
4. If ratio is good → close and move on
5. Simple. Don't overcomplicate tracking.
