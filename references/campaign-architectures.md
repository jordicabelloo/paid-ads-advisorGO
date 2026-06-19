# Campaign Architectures

## Meta/Facebook Ads Architectures

### Architecture 1: Ecommerce Full Funnel (Ruger Viladrosa)

```
ECOMMERCE FUNNEL
│
├── BRANDFORMANCE (10% budget)
│   └── Traffic → IG Profile Visits
│       └── Purpose: warm up cold audiences, 8-10% CTR
│
├── PROSPECTING (70% budget)
│   ├── PRO - Interests (ABO)
│   │   ├── Ad Set: Interest A
│   │   ├── Ad Set: Interest B
│   │   └── Ad Set: Interest C
│   │
│   ├── PRO - Lookalikes (ABO)
│   │   ├── Ad Set: Purchasers 5%
│   │   ├── Ad Set: ATC 5%
│   │   └── Ad Set: View Content 5%
│   │
│   └── PRO - Broad/Open (CBO)
│       └── Ad Set: Demographics only (5M+ audience)
│
├── RETARGETING WARM (10% budget)
│   ├── Warm Product: engage + visitors → product-focused ads
│   └── Warm Brand: same audience → brand storytelling
│
└── RETARGETING HOT (10% budget)
    ├── Ad Set: 30d ATC + 30d View Content
    ├── Ad Set: 60d ATC excl. 30d (recovery)
    ├── Ad Set: 180d ATC excl. 60d (deep recovery)
    └── DPA (Dynamic Product Ads) from catalog
```

**Naming convention**: `[TYPE] - [GEO] - [AUDIENCE] - [EVENT]`
Example: `PRO - US - Lookalike Purchasers 5% - Q3`

### Architecture 2: Services/Coaching Funnel (Brandon Willington)

```
SERVICES FUNNEL (The Three Cs)
│
├── TESTING CAMPAIGN (ABO - $30-50/day)
│   ├── Ad Set 1: Broad targeting, Ad variation A
│   ├── Ad Set 2: Broad targeting, Ad variation B
│   ├── Ad Set 3: Interest 1, Ad variations A+B
│   └── Ad Set 4: Interest 2, Ad variations A+B
│   └── Goal: Find winning ad creative
│
├── SCALING CAMPAIGN (CBO)
│   ├── Ad Set: Winning audiences consolidated
│   └── Ads: All proven winners + variations
│   └── Goal: Maximize volume at target CPA
│
└── RETARGETING CAMPAIGN
    ├── Ad Set: Website visitors (7-30 days)
    ├── Ad Set: Video viewers (50%+ watched)
    ├── Ad Set: IG/FB engagers (30 days)
    └── Ads: Testimonials, objection handling, urgency
```

### Architecture 3: Infoproducts Lead Gen (Ruger Viladrosa)

```
INFOPRODUCTS FUNNEL
│
├── LEAD GEN - INSTANT FORMS
│   ├── Campaign: Leads objective
│   ├── Optimization: Leads
│   └── Forms: 3-5 questions, auto-populate fields
│
├── LEAD GEN - LANDING PAGE
│   ├── Campaign: Conversions objective
│   ├── Optimization: Lead event
│   └── Landing: Long-form with webinar/VSL embed
│
└── RETARGETING - SALES
    ├── Audience: Leads who haven't purchased
    └── Ads: Urgency, scarcity, testimonials, objection busting
```

## Google Ads Architectures

### Architecture 4: Search Campaign (Lead Velocity)

```
GOOGLE SEARCH
│
├── Campaign: [Service Category A]
│   ├── Ad Group: [Exact theme 1]
│   │   ├── Keywords: [phrase match], [exact match]
│   │   ├── Negatives: preemptive list + ongoing
│   │   └── RSA: 15 headlines, 4 descriptions
│   │       ├── Headlines: 3 pinned (positions 1,2,3)
│   │       ├── Include: DKI, location insertion
│   │       └── Use ChatGPT to generate variations
│   │
│   └── Ad Group: [Exact theme 2]
│       └── ...
│
├── Campaign: [Service Category B]
│   └── ...
│
├── Campaign: Brand Protection
│   └── Ad Group: Brand terms
│       └── Low CPC, high CTR, defensive
│
└── Campaign: Remarketing (Display)
    └── Audience: website visitors
    └── Ads: responsive display ads
```

### Pre-Build Spreadsheet Workflow
Before touching the Google Ads interface:
1. List all keyword themes
2. Group into ad groups (tight themes)
3. Write all headlines and descriptions
4. List all negative keywords (preemptive)
5. Map to landing pages
6. Calculate target CPC and budget

### Bidding Strategy Progression
1. **Start**: Manual CPC or Maximize Clicks (with bid cap)
2. **After 30 conversions**: Test Maximize Conversions
3. **After 50+ conversions**: Target CPA or Target ROAS
4. **Key**: Never start with Smart Bidding without conversion data

### Ad Rank Formula
```
Ad Rank = Bid × Quality Score × Expected Impact of Extensions
```

Quality Score (1-10) based on:
- Expected CTR
- Ad relevance to search query
- Landing page experience

## Naming Conventions (All Platforms)

```
[PLATFORM]_[OBJECTIVE]_[AUDIENCE]_[OFFER]_[DATE]

Examples:
META_Conv_Lookalike-Purchasers_MainProduct_2026Q3
META_Traffic_Broad_Brandformance_Ongoing
GOOG_Search_KW-WeightLoss_FreeTrial_2026Jul
GOOG_Shopping_AllProducts_Feed_Ongoing
```

## Budget Allocation Templates

### Low Budget ($1,000-3,000/month)
- 100% one platform
- 70% prospecting, 30% testing
- No retargeting (not enough traffic)

### Medium Budget ($3,000-10,000/month)
- 80% primary platform, 20% retargeting
- Testing budget: $500/month for new angles

### High Budget ($10,000+/month)
- 60% primary platform prospecting
- 15% retargeting
- 15% secondary platform
- 10% testing new angles/platforms
