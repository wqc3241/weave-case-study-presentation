# Weave PLG PM — Case Study Presentation Prep

## Session Summary
**Date:** April 1, 2026
**Purpose:** Prepare a 5-slide case study presentation for Weave's 3rd round interview (PM, PLG role)
**Format:** 60-minute remote session — 20-25 min presentation + Q&A with product, design, and engineering stakeholders

---

## 1. The Email from Weave

**From:** Crystal Strobehn (Senior Talent Acquisition Recruiter) — crystal.strobehn@getweave.com
**Date:** March 30, 2026
**Subject:** Tom, Weave next steps!
**Attachment:** PLG, PM Presentation Prompt.pdf

Crystal asked Tom to prepare a slide presentation for a small group of Weave's product, design, and engineering stakeholders. 60-minute remote session, ~20-25 min presentation followed by Q&A.

**Scheduling link:** https://you.ashbyhq.com/meeting/7a68195b-7c1c-4ecc-8409-c35f93590a0d/
**Interview hours:** Monday–Friday, 9:00am–3:00pm MST

---

## 2. The Prompt Requirements

### Role Context
As a PM for the PLG team at Weave, the objective is to build self-serve, AI-driven pathways that help Practices achieve value faster. Expand the high-touch service model into a versatile, multi-channel growth engine.

### Case Study Requirements
Present a product initiative that delivered quantifiable business results, ideally involving:
- Helping existing users discover and adopt addons or high-value features
- Streamlining complex onboarding or setup workflows into self-serve/automated experience
- Utilizing AI to automate manual tasks and reduce Time-to-Value
- Identifying at-risk segments and building in-app loops for long-term user health

### Evaluation Criteria
1. Identify the core problem/opportunity and define success
2. Approach customer discovery and gather insights
3. Collaborate with team and stakeholders to set strategy
4. Utilize data and insights to inform approach
5. Work tactically to deliver on roadmap, including GTM collaboration
6. Analyze results and derive key learnings

### Guidelines
- Format: Slide presentation
- Timing: 20-25 minutes (do not exceed)
- Visual aids encouraged (process flows, roadmaps, mockups)

---

## 3. Weave Company Research

### Company Overview
- **Weave** (NYSE: WEAV) — AI-powered patient communications and engagement platform for SMB healthcare practices
- ~40,000 customer locations
- Named 2026 Best Software Awards winner (G2), ADA-endorsed Patient Engagement solution (160K ADA members)
- Revenue: $61.3M in Q3 2025 (17.1% YoY growth)

### TrueLark Acquisition (Announced May 2025)
- Acquired for $35M ($25M cash + $10M equity)
- AI-powered receptionist and front-desk automation platform
- Conversational AI for missed calls, texts, web chats, appointment scheduling
- Agentic AI model: reactive → proactive patient engagement
- Estimated TAM expanded to $10B domestic / $22B international

### 2026 Product Roadmap
- **Q4 2025 launch:** Unified Inbox consolidating TrueLark AI + Weave staff conversations
- **H1 2026:** Omnichannel AI Receptionist across all verticals (24/7 AI handling calls/texts with intelligent handoffs)
- Weave Call Intelligence for follow-up task generation

### Key Metrics & Challenges
- Net revenue retention: 93% (102% for multi-location on logo basis, 93% for single-location)
- Gross revenue retention: 89% (targeting 91-93% historical range)
- Two-thirds of base = single-location practices
- Historically "landed heavy" — limits near-term upsell
- Weave Payments growing 2x+ total revenue rate
- <15% penetration of U.S. dental, ~1% specialty medical

### Pricing Model
- Licensed per location, consumption-based (not per-seat)

---

## 4. Case Study Selection

### Chosen Project: Lucid Motors Digital Customer Purchasing Journey

**Why this project over BlueSnap:**
- $62M revenue impact and 30% → 60% conversion are 10x more impressive metrics
- The narrative is cleaner: "1 week → 5 min" is instantly understood
- B2C "weakness" is actually a PLG strength — consumer-grade simplicity is what PLG brings to B2B
- BlueSnap can be used as a supplementary proof point in Q&A
- Tom also has SMB operator experience (NLP Performance, used car dealership) that bridges B2C↔B2B

### B2C → B2B Reframe Strategy
- PLG IS consumer thinking applied to B2B — Weave's office managers expect consumer-grade UX
- Lucid work was actually B2B2C (lender integrations, multi-market compliance, sales enablement)
- NLP Performance = operating an SMB with 200K SKUs (Weave's target persona)
- Used car dealership = literally been the SMB owner these tools serve

---

## 5. Deep-Dive Interview: Project Details

### 5.1 Problem & Opportunity

**Company goal:** Deliver more vehicles to customers

**Tom's scope:** Digital financing journey, but always thinking holistically about the full E2E purchasing experience (discovery → research → deposit → credit application → document upload → contract signing → delivery)

**Key problems identified:**
- Fragmented purchasing flow — separate systems for deposits, financing, credit decisions, delivery scheduling
- Credit approval took 1 week — FinOps manually emailed applications to lenders, lender emailed back, manual Salesforce workflow
- No self-serve path — every step required a sales advisor
- Mobile = 65% of traffic but converted 20% lower than desktop
- Deposit-to-delivery conversion: ~30%

**Success metrics defined:**
- Primary: Customer conversion rate (deposit → delivery)
- Guardrails: Drop-off rate, approval-to-delivery %, product usage %

---

### 5.2 Customer Discovery & Insights

**End-to-end dropout funnel dashboard built across three phases:**

**Discovery metrics:**
- Site visits → Vehicle page views → Deposit button clicks

**Acquisition to Purchase metrics:**
- Document uploads → Finance applications → Completed finance → Signed contracts → Delivery completion

**Entry points tracked:** Online vs. in-studio, landing page sources (finance page, offer page, home page, vehicle details page)

**Discovery methods:**
1. **Funnel analytics** — Built dropout dashboard; identified credit decision step as #1 drop-off
2. **Customer surveys** — Complaints about clunky mobile experience confirmed by data
3. **Studio visits** — Led designers and engineers to observe real customers and sales advisors in-studio
4. **Pre-launch A/B testing:**
   - Control group (old desktop-driven design) vs. experiment group (new mobile-driven design)
   - Saw more mobile users starting and completing credit applications in experiment group
   - Added placeholder product buttons (co-buyer, trade-in/lease, payment calculator) to measure click-through interest before building
5. **Competitive benchmark** — Affirm, Klarna set the bar for instant decisioning. Sales team confirmed: "Customers can't wait 5 days."

**Key customer moment (studio visit):** A customer said, "I can't complete the application on my mobile phone" — crystallized the need for mobile-driven experience.

**Hypotheses formed:**
- Fix the largest drop-off point (credit decisioning)
- Improve mobile-driven experience
- Add more product options to the journey
- Close technical gaps

**Enhancements categorized into:** UX challenges vs. product/options challenges

---

### 5.3 Strategy & Stakeholder Alignment

**North Star:** Customer conversion rate (deposit → delivery)

**Three strategic bets, phased over 9 months:**

#### MVP (3 months)
- Instant credit decision via DealerTrack API integration (1 week → <5 min)
- Mobile-first UI redesign for purchasing app
- Phased rollout: California first, then expand
- **Result:** 20% mobile conversion lift, ~100 new vehicles/week

#### Phase 2 (3 months)
- Co-borrower product launch
- Trade-in / lease product
- AI pricing engine for non-engineers to configure regional programs (2x launch speed)
- **Result:** Additional 5-10% conversion growth

#### Phase 3 (3 months)
- Canada expansion (lease product, local formatting)
- Middle East expansion (annual payment program)
- AI chatbot for purchasing questions and financing procedures
- **Result:** 80% Canada sales growth, 60% ME lead growth

**Team:** 2 designers, 5 full-time engineers, ~10 contract engineers (15 total)

---

### 5.4 Stakeholder Navigation — Sales Ops Pushback Story

**Context:** While pitching the idea to rebuild the digital journey for mobile, got hard pushback from Sales Ops team lead.

**Her three concerns:**
1. No proven results yet — just analysis, no shipped product to show
2. Tight bandwidth — no resources to spare for this initiative
3. Fear that the new digital journey would disrupt their existing operational flow

**Tom's three responses (mapped 1:1):**
1. Presented A/B testing results, walked her through how the data shows conversion improvement potential
2. Committed to using own team's resources — zero ask from her team
3. Promised to involve her team in testing before each launch phase so they understand changes and confirm it doesn't break their flow

**Final alignment move:** Reframed around shared company goal — "We're both trying to deliver more vehicles. I'm improving the digital funnel, you keep doing what you're doing."

**Secret weapon:** Used AI to build an end-to-end digital experience prototype — let her actually *see* the product and how it works from the customer's perspective. This tipped the buy-in.

**After getting Sales Ops buy-in first, other stakeholders followed more easily.**

**MVP trade-off decision:** Scoped down to UI redesign + instant decision only. Pushed co-borrower and other features to Phase 2 — driven by engineering and design capacity within the 3-month window. Prioritized the most critical problems: (1) UI redesign, (2) instant decision — addressing sales team's and compliance team's asks first.

---

### 5.5 Instant Credit Decision — Technical Story

**Before:** FinOps manually emailed credit applications to lenders. Lender emailed back. Manual Salesforce workflow. ~1 week turnaround. Sales team reported: "Many customers can't wait 5 days — they just go away."

**Investigation:** Tom talked to FinOps team, observed their manual process, identified it as a key automation opportunity.

**Build vs. buy decision:**
- Route 1: Third-party vendor integration
- Route 2: Build in-house
- Decision: Third-party (time-sensitive, needed immediate impact)

**Vendor selection process:**
1. Talked to both vendors — evaluated long-term potential
2. Assessed customer support capabilities
3. Conducted market share research
4. Chose **DealerTrack** — more complete support functionality, supports later add-on products
5. Consulted engineering team (API feasibility) and compliance team (regulatory check)

**Result:** Delivered within 3 months alongside UI redesign. Credit decision: 1 week → under 5 minutes. 40%+ conversion improvement on that step. ~3,000 vehicle deliveries per month.

---

### 5.6 Data & Insights Approach

**Pre-launch A/B testing (not just post-launch):**
- UI: Control group (desktop-driven) vs. experiment group (mobile-driven) — more mobile users starting and completing credit applications
- Product discovery: Added placeholder product buttons to measure click interest before building anything
- Used click data to prioritize which products to build next

**Phased rollout strategy:** California first (most important market) → measure results → expand to broader markets based on customer reaction and data

---

### 5.7 GTM Collaboration

**MVP launch:**
- Created sales communication instructions so the sales team understood the new app experience
- Could guide customers through the process if needed

**Marketing collaboration:**
- Secured spotlight position on website for financing offers with each new product launch
- Surfaced the right APR rate based on credit selection so customers could quickly estimate costs

**Canada & Middle East expansion:**
- Reused majority of technical components
- Customized product offering for local markets:
  - Middle East: Annual payment program
  - Canada: Different financing calculation formats and display requirements
- Published best offering for each local market's website

---

### 5.8 AI Products Shipped

**AI Chatbot for Purchasing & Financing:**
- Embedded directly in the customer journey
- Users can get answers to financing questions without human interaction
- **Impact:** 30% reduction in FinOps operations time
- Reduced average application completion time: 10 min → 6 min per session
- Enabled fully zero-human-interaction purchasing

**AI Prototype for Stakeholder Buy-in:**
- Used AI to build end-to-end digital experience prototype
- Showed Sales Ops lead the product from customer's perspective
- This is what actually tipped the stakeholder buy-in

---

## 6. Final Results Summary

| Metric | Before | After |
|---|---|---|
| Deposit-to-delivery conversion | 30% | 60% |
| Incremental revenue (one quarter) | — | $62M |
| Credit decision time | 1 week | < 5 minutes |
| Vehicle deliveries per month | — | ~3,000 |
| Application completion time | 10 min | 6 min |
| FinOps workload (AI chatbot) | — | -30% reduction |
| Mobile conversion (MVP) | — | +20% lift |
| Canada sales (Phase 3) | — | +80% growth |
| Middle East inbound leads (Phase 3) | — | +60% growth |
| Phase 2-3 additional conversion | — | +5-10% |

---

## 7. Bridge to Weave — How to Apply

### The Parallel
Weave faces the same transformation: high-touch service model → self-serve, AI-driven growth engine. ~40K locations, <15% dental penetration, 93% NRR with room to grow.

### Three Focus Areas

**1. Collapse Onboarding TTV**
- AI-guided setup that auto-imports contacts, configures workflows, delivers value in the first session
- *Lucid parallel:* 1 week → 5 min credit decision was the single biggest conversion unlock

**2. Self-Serve Feature Discovery**
- In-app ROI calculators for Payments, AI Receptionist — help practices see value before they commit
- *Lucid parallel:* Payment calculator drove 60% more inbound leads without adding sales headcount

**3. Activation-Based Retention**
- Instrument the funnel, identify at-risk practices not using key features, trigger AI-powered nudges
- *Lucid parallel:* Pre-launch A/B testing + phased rollout ensured we shipped what customers needed

### First 90 Days
1. Map the self-serve activation funnel end-to-end — find the biggest drop-off
2. Talk to 20+ practices to learn what "value" means in their first week
3. Ship one high-impact TTV reduction experiment

---

## 8. Q&A Prep — Anticipated Questions

**Q: "How did you handle pushback from sales who feared self-serve would cannibalize their role?"**
→ Full story above (Section 5.4). Key: self-serve made sales more effective. Payment calculator generated 60% more inbound leads. Aligned around shared company goal.

**Q: "How would you measure success for PLG at Weave?"**
→ Primary: Time-to-first-value (how fast a new practice gets their first patient interaction through Weave). Secondary: Self-serve activation rate, feature adoption breadth, net revenue retention improvement.

**Q: "How do you think about the tension between single-location practices (low NRR) and multi-location groups?"**
→ Reference Weave's own data (93% vs 102% NRR). Single-location needs PLG because they can't afford high-touch. Multi-location needs PLG for scale. Different playbooks, same engine.

**Q: "Your experience is B2C — how does that apply to B2B SaaS?"**
→ PLG IS consumer thinking applied to B2B. Lucid work was B2B2C underneath. NLP Performance = operating an SMB. Used car dealership = literally been the SMB owner these tools serve. B2C instinct for frictionless UX is the exact muscle most B2B PMs lack.

**Q: "What's your experience with AI in product?"**
→ AI chatbot in production at Lucid (30% FinOps reduction). AI prototype for stakeholder buy-in. BreakLingo (AI language learning app). AI customer support agent for NLP Performance. AI phone agent architecture. Builder, not just PM who "talks about AI."

**Q: "Why DealerTrack over building in-house?"**
→ Time-sensitive decision. Needed immediate impact. Evaluated both vendors on: long-term potential, customer support, market share. DealerTrack had more complete support + supported add-on products for future phases. Consulted engineering (API feasibility) and compliance (regulatory check).

---

## 9. Presentation Deck

**File:** weave_case_study_v2.pptx (5 slides)
**Design:** Navy + teal on white, minimal color palette
**Structure:**
1. Problem & Opportunity (with 3 key stat callouts)
2. Discovery & Insights (funnel visualization + 5 discovery methods)
3. Strategy & Execution (3-phase cards + stakeholder alignment)
4. Results & Learnings (dark slide with 6 metrics + 4 learnings)
5. Bridge to Weave (3 focus areas + first 90 days)

---

*Session exported: April 1, 2026*
