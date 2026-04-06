---
name: market-insight-product-selection
version: "2.2.0"
description: |
  Adaptive product-selection methodology built on multi-source signals and "voice of customer" (VoC): validate demand, momentum, competitive intensity, and user pain points from reviews/comments to produce a confident shortlist or a focused go/no-go.
  **When to use**:
    - User is asking about trends/popularity (Tiktok/Amazon/etc.), or what's selling well in a market (US/UK/etc.)
    - User asks for **single-category / single-product** trend analysis
    - User wants market analysis, market research, or competitive landscape insights
    - User is researching consumer preferences, demand patterns, or market dynamics
    - User needs help deciding what products to sell, source, or invest in
    - User is exploring product opportunities, winning products, or profitable niches
  Complete this in four steps:
    1. Demand & Scope (clarify market, timeframe, constraints)
    2. Signal Aggregation (multi-source signals (social media/retail platform/general web/etc.) + VoC)
    3. Adaptive Evaluation (route by scenario + scorecard)
    4. Recommendation & Action Guide (what to do next)
enabled: true
---

# Market Insight & Product Selection

Turn messy "trend" signals into decision-ready shortlists using multi-source triangulation + Voice of Customer (VoC).

## Important: Where Files Go

| Location | Path | What Goes There |
|----------|------|-----------------|
| **Skill directory** | `/home/wuying/skills/market-insight-product-selection-v2/` | Templates, chart-design-guide.md, reference docs |
| **Project directory** | follow system context | `findings.md`, analysis outputs, charts |


## Templates

| Template | Skill Path | Purpose | When to Update |
|----------|------------|---------|----------------|
| `findings.md` | `/home/wuying/skills/market-insight-product-selection-v2/templates/findings.md` | VoC samples, research discoveries, evidence | After ANY discovery (follow 2-Action Rule) |

### File Purposes

| File | What It Stores | Key Sections |
|------|----------------|--------------|
| `findings.md` | Your knowledge base — evidence, VoC, research | Requirements, Research Findings, Technical Decisions, Visual/Browser Findings |

### The 2-Action Rule

> "After every 2 view/browser/search operations, IMMEDIATELY save key findings to `findings.md`."

This prevents visual/multimodal information from being lost when context gets long.

## Quick Start

Before ANY market research task:

1. **Create `findings.md`** — Store VoC samples, signals, evidence
2. **Follow the 4-step pipeline**:
   - Trend Radar → Top Picks → Deep Dive Packs → Decision & Action
3. **Save evidence to `findings.md`** — VoC samples, signals, research discoveries

## The Core Pattern

```
Evidence Density → Decision Quality

Signals (trend data) + VoC (reviews/comments) + Triangulation (3+ sources)
= Confident Go / Cautious / No-Go
```

## Routing Shortcut

| User Request | Routing |
|--------------|---------|
| **Category trend** ("what's hot in X") | Demand & Scope → Radar → Deep Dive 3–8 → Final |
| **Specific candidates** ("evaluate product X") | Deep Dive → Brain → (optional) Scorecard → Final |

---

## Critical Rules

### 1. User Intent Overrides Skill
If any guidance here conflicts with what the user explicitly asked for (platform/channel, market, timeframe, constraints, format), **follow the user request first**.
- Example: user asks for **TikTok hot products** → primary pool = **TikTok products**
- You may still use **other channels** for supporting VoC / triangulation

### 2. Evidence First
Don't write deep "reasons" until you have enough concrete evidence.
- For any non-trivial claim, attach **how much evidence** supports it (e.g., `n=20`, `14/20 mention X`)

### 3. Question-Driven Collection
Collect information based on what the question needs:
- Action cameras → specs/capabilities + pricing/positioning + competitors + VoC
- Fashion trend → style attributes + price band + VoC + channel-fit

### 4. The 3-Signal Minimum
For each candidate, collect **≥3 signals** (prefer 2+ platforms):
- **Demand momentum**: trend dashboards, creator velocity, search suggestions
- **Commerce traction**: best-seller persistence, review velocity, stockout signals
- **VoC pull**: repeated pain points / praise patterns (not just hype)

### 5. Data Gaps = Explicit Output
If evidence is thin: explicitly output **Data Gaps + Next Collection Step** instead of inventing confident reasons.

### 6. Never Skip VoC Wedge
In Red Ocean (high competition): base differentiation on **recurring, fixable** mixed-sentiment pain point patterns (benefit + complaint).
- No recurring pattern found after enough samples → **Recommended: No-Go**

---

## Pipeline Overview

| Step | Goal | Output |
|------|------|--------|
| **1. Demand & Scope** | Define market + segment + timeframe | Scope table, 2–5 segments |
| **2. Trend Radar** | Build trend-driven candidate pool | 10–30 candidates with signals |
| **3. Top Picks** | Rank and select with decision rule | Top 3–8 with scores |
| **4. Deep Dive Packs** | Comprehensive evidence per pick | Evidence pack per candidate |
| **5. Brain Routing** | Apply right validation depth | Scenario-specific actions |
| **6. Final Recommendation** | Decision-ready output | Go / Cautious / No-Go |

---

## Step 1: Demand & Scope

**Goal**: Define market + segment + timeframe so you don't do deep VoC work on the wrong slice.

**When**: Recommended for broad category questions. Skip for specific product evaluation.

### Scope Checklist
- Market + channels (TikTok/Amazon/etc.)
- Timeframe (momentum window + seasonality)
- Category → segment → use case

### Trend Scan Template

| Segment (category → micro-niche) | Who buys / use case | Demand momentum (why) | Seasonality | Competitive intensity | Notes / risks |
|---|---|---|---|---|---|
| ... | ... | ... | ... | ... | ... |

**Decision rule**: Pick segments with clearest momentum / acceptable risk as many as possible.

---

## Step 2: Trend Radar (Candidate Pool)

**Goal**: Create a trend-driven candidate pool (10–30 for open-ended, 3–8 when specific).

### Signal Sources (prioritized)

| Source Type | What to Look For |
|-------------|------------------|
| **YouTube + Reddit** | VoC + momentum, creator velocity |
| **Google Trends / Pinterest / TikTok** | Trend directionality, search suggestions |
| **Marketplaces** (Amazon, TikTok Shop, Shopee, Temu, Alibaba.com) | Best-seller persistence, reviews/Q&A, price patterns |

### Candidate Pool Template

| Candidate | Trend signal (what & where) | VoC themes (n=) | Typical price band | Competitor examples | Hypothesis / angle |
|---|---|---|---|---|---|
| ... | ... | ... | ... | ... | ... |

---

## Step 3: Top Picks Selection

**Goal**: Convert candidate pool into shortlist with explicit, repeatable rule.

### Scorecard (default weights)

Rate each candidate 1–5 (5 is best), compute Σ(Score × Weight).

| Criteria | Weight | What to look for |
|---|---:|---|
| **Demand velocity** | 30% | Searches/discussions accelerating? Review velocity? Creator frequency? |
| **Trend durability** | 20% | Emerging/growing/mature/declining; seasonality; 6–12mo outlook |
| **Competitive gap (VoC wedge)** | 30% | Recurring "benefit + complaint" pattern you can fix (report n= and frequency) |
| **Channel-fit / content potential** | 20% | Easy to demo? Repeatable hook? UGC format works? |

### Decision Rule
- **Pick Top 3–8** by score
- **Tie-breaker**: choose stronger **VoC wedge** (frequency + fixability) over pure hype

### Top Picks Template

| Rank | Candidate | Trend status | Evidence (3 sources) | Score | Why it makes Top (1–2 bullets) | Main risk |
|---:|---|---|---|---:|---|---|
| 1 | ... | ... | ... | 4.5 | ... | ... |

---

## Step 4: Deep Dive Evidence Pack

**Goal**: Make analysis as comprehensive as evidence allows. Incomplete pack → output **Data Gaps + Next Collection Step**.

### Evidence Checklist (per Top pick)

| Category | What to Collect |
|----------|-----------------|
| **Product snapshot** | What it is, who it's for, job-to-be-done, key variants |
| **Trend narrative** | What changed; trigger events; "why now" |
| **Specs & performance** | Parameters that matter for use-case |
| **Pricing & offer** | Price band, bundles, shipping, returns/warranty |
| **Value perception** | Price-per-unit, "value for money" VoC |
| **Competition** | 3–5 comparables + why they win; what's commoditized vs defensible |
| **VoC wedge (mandatory)** | 10–20 mixed-sentiment samples → 2–3 recurring patterns with counts (e.g., `7/20`) |
| **Channel-fit** | Hook, proof format, repeatable content pattern |
| **Trust & compliance** | Claims risk, certifications, materials safety, market constraints |
| **Risks / unknowns** | Seasonality, supply, shipping, regulation, durability |

### Deep Dive Card Template

```markdown
### [Candidate Name] — Deep Dive

- **Snapshot**: [what it is + who it's for + job-to-be-done]
- **Trend status**: [emerging/growing/mature/declining] + 1-line "why now"
- **Evidence**: [3 sources; cite reference IDs when available]
- **Pricing & offer**: [price band + bundle/returns/shipping]
- **Competitors**: [3–5 comps + 1-line why they win]
- **VoC wedge (mandatory)**: [2–3 patterns with n= and frequency like x/y]
- **Channel-fit**: [hook + proof format + repeatable content pattern]
- **Trust & compliance**: [claims/certs/market constraints]
- **Risks / unknowns**: [top risks] + **Next data to collect**
- **Score**: [optional but recommended]
- **Verdict**: Go / Cautious / No-Go
```

---

## Step 5: Brain — Scenario Routing

**Goal**: Apply the right validation depth based on competitive landscape.

### Scenario Decision Matrix

| Scenario | Condition | Your Move | Action | Outcome |
|----------|-----------|-----------|--------|---------|
| **A: Red Ocean** | High Demand, High Competition | Pain Point Mining | Analyze 2–4★ reviews of top 5 competitors; look for benefit + complaint | No fixable pattern → No-Go; 1–2 patterns → proceed with wedge |
| **B: Blue Ocean** | High Demand, Low Competition | Speed Focus | Validate demand reality + trend durability | Durable + light competition → Go / Cautious-Go |
| **C: Ghost Town** | Low / Unclear Demand | Smoke Test | Run "Fake Door" test ($50 ad, landing page, email capture) | Validate demand before committing |

### Red Ocean Deep Dive
- Prefer **2–4★** on 5-star systems
- If no stars: filter for comments with **benefit + complaint** ("but/however/except")
- Scan enough samples to find (or not find) recurring patterns

---

## Step 6: Final Recommendation

**Goal**: Provide decision the user can execute, with transparency about evidence and gaps.

### Final Output Structure

```markdown
## 1) Assumptions / Scope
- Market / channel / timeframe
- Constraints

## 2) Trend Candidate List (10–20)
- Table with signals + VoC themes (n=)

## 3) Top Picks (Top 3–8) + Scorecard
- Table with score + tie-breaker rationale

## 4) Deep Dive Packs (per Top pick)
- Snapshot, Evidence, VoC wedge, Competitors, Channel-fit, Risks

## 5) Final Recommendation
- Top pick + why
- Go / Cautious / No-Go
- Next steps (what to validate next)
- Data gaps (if any)
```

---

## Chart Design

**When to use charts**: If dataset is sufficiently rich (≥5 data points or ≥3 categories), include charts. More data → more charts, less long text.

> **⚠️ CRITICAL**: Before generating ANY chart, you MUST read:
> 
> **`/home/wuying/skills/market-insight-product-selection-v2/chart-design-guide.md`**
> 
> Contains: Tool selection (Seaborn vs Matplotlib), code patterns, styling, chart type selection, Seaborn v0.12+ API updates.

### Quick Chart Reference

| Data Pattern | Chart Type | Tool |
|--------------|------------|------|
| Time series (trends) | Line + area fill | `sns.lineplot()` |
| Part-to-whole | Pie / donut | `plt.pie()` |
| Category comparison | Horizontal bar | `sns.barplot()` |
| Multi-attribute (3+ dims) | Radar | `plt.polar()` |
| Correlation | Scatter | `sns.scatterplot()` |
| Composition over time | Stacked area | `ax.stackplot()` |

---

## When to Use This Skill

**Use for:**
- User asks about trends/popularity (TikTok/Amazon/etc.)
- Single-category / single-product trend analysis
- Market research, competitive landscape insights
- Consumer preferences, demand patterns
- Product opportunities, winning products, profitable niches

**Skip for:**
- Simple product lookup (use direct search)
- Price comparison only (use comparison tools)
- Supplier sourcing (use sourcing skills)

---

## Anti-Patterns

| Don't | Do Instead |
|-------|------------|
| Treat all products with same depth | Apply adaptive routing (Red/Blue/Ghost) |
| Ignore VoC (reviews/comments) | Always collect VoC wedge with n= counts |
| List data without decision rule | State explicit selection criteria + tie-breaker |
| Write confident reasons without evidence | Output "Data Gaps + Next Collection Step" |
| Default only to bar/line charts | Use pie/radar/scatter as data supports |
| Replace user's requested platform | Use requested platform as primary, others for triangulation |

---

## Checklist

### ✅ Strongly Recommended
- [ ] For broad category: define segment + timeframe first (Demand & Scope)
- [ ] For specific products: include concrete inputs (image, price, link/ID, variant) + full deep dive
- [ ] Use multi-source evidence: YouTube + Reddit (VoC) + at least one trend/marketplace signal
- [ ] Output: **Trend Candidate List → Top Picks → Deep Dive Packs → Final Recommendation**
- [ ] Use scenario routing (Red/Blue/Ghost) to decide validation depth
- [ ] In Red Ocean: base differentiation on recurring, fixable VoC patterns
- [ ] **Follow 2-Action Rule**: Update `findings.md` after every 2 search/view operations
- [ ] Include sources in final output
- [ ] Read `/home/wuying/skills/market-insight-product-selection-v2/chart-design-guide.md` before generating charts

### ❌ Avoid
- Starting without creating `findings.md`
- Treating all products with the same depth
- Ignoring VoC (reviews/comments)
- Listing data without a decision rule
- Inventing confident reasons without evidence
- Forgetting to update findings after search/view operations
