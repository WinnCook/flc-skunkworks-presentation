# FLC Skunk Works - Active State
**Last Updated:** 2025-12-17 (Session 17)
**AI Platform:** Claude (Opus 4.5)
**Session Type:** Professional Pitch Overhaul & Repo Cleanup

---

## 0. CURRENT PHASE

**READY** - Presentation polished and ready for VP presentation Wednesday 12/18

---

## 1. SNAPSHOT

- **Session 17 Professional Pitch Overhaul & Repo Cleanup:**
  - **Critical audit performed** - identified and fixed math inconsistencies, gaps, and flaws
  - **Fixed inflated value claims:**
    - Changed "$15,000+ conservative" → accurate "Year 1: $9,300+ | Year 2+: $15,000+"
    - ROI section now shows: Hard Savings $6,500 + Productivity $2,800 = $9,300
  - **Added 50/50 payment structure:**
    - $3,750 on approval, $3,750 on delivery
    - "Pay for results, not promises" messaging
  - **Added FLC Protections section to The Ask:**
    - 50% held until delivery
    - FLC owns all IP, code, documentation
    - Can stop after any project
  - **Added Worst Case Scenario callout:**
    - Maximum exposure: $22,500
    - FLC keeps all work products
    - Winn returns to normal IR role
  - **Changed quarterly → monthly progress reports**
  - **Simplified AI Meeting Assistant description** (4 lines → 2)
  - **Removed speculative revenue** from Event Management App
  - **Fixed mobile viewport** to 0.5 initial scale (dashboard)
  - **Updated partnership-path.html** with 50/50 payment terms
  - **Updated pitch-script.md** with new terms and objection responses
  - **REPO CLEANUP - Single source of truth:**
    - Deleted duplicate HTML files from `initiatives/.../html-showcase/`
    - Root files (index.html, dashboard.html, etc.) are now THE ONLY source
    - Prevents future GitHub Pages sync issues
  - DATA_VERSION bumped to 14
  - All changes pushed to GitHub Pages
- **Session 16 Description Polish & Dashboard UX:**
  - **AI Meeting Assistant pitch strengthened:**
    - Emphasizes regulatory compliance through comprehensive documentation
    - Highlights internal communication (auto-drafted functional area updates)
    - Adds PD attendance for scheduling conflicts (key VP value prop)
    - Removed FERPA reference (not relevant to meeting data)
  - **Event Management App description polished:**
    - More professional and concise
    - Direct pitch: build Whova replica, licensable to partners for revenue
  - **Dashboard initiative cards fixed:**
    - Clicking ANY card now expands/collapses ALL THREE together
    - Removed broken single-card full-row spanning behavior
    - Uses global `allInitiativesExpanded` state
  - **Dashboard mobile zoom-to-fit:**
    - Updated viewport meta: `initial-scale=0.8, minimum-scale=0.5`
    - Users can now see full dashboard and zoom as needed
  - All changes pushed to GitHub Pages
- **Session 15 Scenario Presets & Executive Descriptions:**
  - **Renamed initiatives across all files:**
    - "Conference App" → **Event Management App** (Institutional Asset)
    - "AI Transcription" → **AI Meeting Assistant** (Otter AI Replacement)
    - Enrollment Forecasting v2 updated with executive focus
  - **Dashboard scenario toggle:**
    - Added 3-preset toggle: Conservative / Moderate / Optimistic
    - Each scenario applies different value projections to all initiatives
    - URL sharing support for scenarios (?scenario=moderate)
    - Share button copies link to clipboard
  - **Dashboard mobile improvements:**
    - Added hamburger menu for collapsible sidebar
    - Sidebar hidden by default on mobile, slides in on tap
    - Responsive grids for value cards and initiative cards
    - Back button in top nav with icon-only on mobile
    - overflow-x: hidden prevents horizontal scroll
  - **Executive-friendly descriptions (index.html):**
    - Event Management App: 2 years of Whova, institutional asset, community partners
    - AI Meeting Assistant: Attends meetings, better than Teams, auto-draft emails, regulatory recaps
    - Enrollment v2: Executive web dashboard, scenario modeling, finance team access
  - **Consistency updates:**
    - partnership-path.html, pitch-script.md, @Active_State.md all updated
  - DATA_VERSION bumped to 13
- **Session 14 Final Polish & Mobile Optimization:**
  - **Dashboard redesign for presenting:**
    - Removed Executive Summary and Activity Log from main dashboard view
    - Redesigned initiatives as expandable cards with inline $ editing
    - Click to expand: edit savings/revenue/productivity/costs directly
    - All changes update 5-Year Financial Projection table in real-time
    - DATA_VERSION bumped to 12
  - **Partnership-path.html improvements:**
    - Combined Steps 2 & 3 into single "Vendor Setup & Onboarding" step (3 steps now)
    - Restructured "Preferred Partner Offer" → "Founding Partner Advantage"
    - Left column: Strategic Value (time-to-value, budget flexibility, exit ramp, rates)
    - Right column: Operational Assurances (no repetition, exec-focused)
    - Added overflow-x fix for mobile
  - **Index.html improvements:**
    - Removed Interactive ROI Calculator (duplicative with Command Center)
    - Removed 3-Year Value Projection chart
    - Changed "Strategic Positioning: Priceless" → "Aligned" (more professional)
    - Added mobile hamburger menu for nav buttons
    - Added overflow-x: hidden to prevent horizontal scroll on mobile
  - **Mobile nav fixes (all pages):**
    - Origin-story & partnership-path: simplified to logo + back arrow
    - Text hidden on mobile, full text on desktop
    - All pages now have overflow-x: hidden
  - All changes pushed to GitHub Pages
- **Session 13 Pitch Perfection & Conservative Defaults:**
  - Conducted multi-perspective audit (CEO view, VP view) of entire pitch
  - Updated **Annual Value Potential** from $10,000+ to **$15,000+** (conservative, defensible)
  - Extended timeline from **Jan-June → Jan-August 2026** (more realistic)
  - Made ALL dashboard defaults conservative (removed speculative revenue):
    - Event Management App: revenue $2,000→$0
    - AI Meeting Assistant: savings $3,000→$2,500, revenue $1,000→$0
    - Enrollment v2: savings $15,000→$0, revenue $4,500→$0, productivity $3,000→$2,800
  - Made ROI calculator defaults conservative:
    - College licenses slider: 5→0
    - Transcription users: 30→10
    - Enrollment consultant avoided: $15,000→$0
  - **Conservative total annual value: ~$12,300** (supports $15K+ claim)
  - Added COI disclosure note to partnership-path.html
  - Created **pitch-script.md** with bullet points, objection responses, delivery tips
  - DATA_VERSION bumped to 11 for fresh browser cache
  - All changes pushed to GitHub Pages
- **Session 12 Pricing & Dashboard Financial Upgrades:**
  - Updated pricing from ~$5K to **$7,500 per project** across all pages
  - Total Phase 1 investment now **$22,500** (was ~$15K)
  - Replaced "stipend" with "cost" throughout (except Stipend Model comparison page)
  - Added **5-Year Executive-Grade Financial Projection** table to dashboard
  - Table shows: Costs, Benefits (broken into Savings/Revenue/Productivity), Returns
  - Added **Cumulative ROI** row showing compound returns over 5 years
  - Added **valueProps** field to initiatives - editable bullet points explaining value rationale
  - Value propositions display as sub-bullets in Executive Summary
  - Fixed infinity (∞) bug - now only shows when investment is truly zero
  - DATA_VERSION bumped to 10 for fresh cache on web visitors
  - All root files synced and pushed to GitHub Pages
- **Session 11 Partnership Path & Altitude AI:**
  - Created new "Partnership Path" page (`partnership-path.html`) presenting vendor/entity alternative
  - Introduced **Altitude AI** as Colorado LLC for FLC to engage as vendor vs. stipend model
  - Research confirms FLC conflict of interest policy allows outside work with disclosure
  - FLC vendor requirements simple: just W-9, PO for >$5K purchases
  - Added teal/emerald nav button to all 4 presentation pages
  - Page covers: Two paths comparison, 7 FLC benefits, how it works, preferred partner offer
  - Added "No Asset Overhead" benefit (equipment/subscriptions stay with consultant)
  - Simplified nav: removed scroll links (Home, Opportunity, Phases, Projects, ROI)
  - Shortened nav labels: Command Center→Dashboard, Origin Story→Origins, Partnership Path→Partnership
  - Made FLC Skunk Works logo clickable as home button
  - Final nav: [Logo] ... [The Ask] [Dashboard] [Origins] [Partnership]
  - All files synced to root and deployed to GitHub Pages
- **Session 10 Project Swap & Grade Labels:**
  - Replaced Phase 1 project: Software Replication → **Enrollment Forecasting Model v2**
  - New project highlights: <2% MAE (proven v1), admissions pipeline data, what-if scenario analysis
  - Changed decision path labels to academic grades: C+ (Limited), B+ (Moderate), A+ (High Value)
  - Updated Future Pipeline: "Enrollment Prediction" → "FLC Brandify" (document branding tool)
  - Added dashboard data versioning to auto-clear cached localStorage
  - All changes pushed to GitHub Pages
- **Session 9 Deployment & Fix:**
  - Deployed presentation to GitHub Pages: https://winncook.github.io/flc-skunkworks-presentation/
  - Created public repo `WinnCook/flc-skunkworks-presentation` for sharing
  - Fixed Command Center dashboard math: added missing Productivity Savings card ($4K)
  - All 5 metrics now display: Total ($24K) = Cost Savings ($12K) + Revenue ($8K) + Productivity ($4K)
  - Updated PDF export to show all 5 metrics
- **Session 8 Addition:**
  - Created new "Origin Story" page (`origin-story.html`) explaining Skunk Works history
  - Page covers: The 1943 problem, Kelly Johnson, the 6 rules, what they built (P-80, U-2, SR-71, F-117), why it worked, FLC mapping, executive framing
  - Added amber/orange "Origin Story" navigation button to index.html (right of Command Center)
  - Includes back-to-presentation link, matching dark theme, AOS animations, SR-71 silhouette
  - Removed decorative quote marks per user preference (kept title quotes only)
- **Session 7 Refinements:**
  - Moved "Winn Cook" from heading to first bullet (matches Mario Martinez treatment)
  - Updated local AI bullet: "software development workflows for building institutional applications"
  - Added FERPA/PII compliance to Measured Risk principle card
  - Removed "Workday Analytics" from Future Pipeline (now 3-column grid)
  - Rebranded "Data Security Leadership" → "Locally Trained AI" (fine-tuning, FERPA, strategic independence)
  - Softened "The Fit" language (removed "rare combination")
  - Generated full PDF export of presentation
- **Key messaging now emphasizes:**
  - Low risk, clear decision points, built-in off-ramps
  - Per-project costs of **$7,500 each** (50/50 payment: $3,750 approval / $3,750 delivery)
  - Total Phase 1 investment: **$22,500**
  - **Year 1 Value: $9,300+** (conservative, accurate math)
  - **Year 2+ Value: $15,000+** with adoption
  - **FLC Protections:** 50% held until delivery, FLC owns all IP, can stop anytime
  - Timeline: **Jan-August 2026** with **monthly progress reports**
  - FERPA compliance and data protection throughout
  - Foundation/auxiliary entity as aspirational outcome
  - **Lead with Partnership Path** (Altitude AI) as recommended structure
- VP presentation TODAY (12/18)

---

## 2. ACTIVE TASK

**Final prep for VP presentation Thursday**
- Review presentation flow in browser
- Practice the pitch narrative
- Be ready to discuss BOTH options: Stipend OR Partnership Path (Altitude AI)
- Partnership Path offers lower friction for FLC (vendor budget vs. HR/compensation)
- Gather any additional insights from AI Conference (12/16)

---

## 3. THE NEW PITCH STRUCTURE

### Triple Emotional Sell
1. **EXCITEMENT + FOMO** - "AI is transforming higher ed NOW, don't fall behind"
2. **CONFIDENCE + LOW RISK** - "Measured experiment with decision points and off-ramps"
3. **IMPRESSED + TRUSTING** - "Winn has the credentials, this presentation is proof"

### The Ask (Two Options)

**Option A: Stipend Model**
- Per-project costs of **$7,500** during Phase 1 (Jan-August 2026)
- Processed through HR/compensation

**Option B: Partnership Path (Altitude AI)** ← *Lower friction*
- Vendor invoicing through Altitude AI (Colorado LLC)
- Uses existing procurement budget (no HR involvement)
- FLC benefits: No asset tracking, no benefits burden, project-based accountability
- Equipment/subscriptions owned by entity (no sunk costs for FLC)

**Total Phase 1 Investment:** $22,500 (3 projects × $7,500)

**Both Options Include:**
- 3 Phase 1 projects: Event Management App, AI Meeting Assistant, Enrollment Forecasting v2
- Formal designation of AI Exploration Initiative
- Quarterly review meetings

### Summer Decision Framework
- **Sparse results** → Back to normal IR (no harm done)
- **Moderate results** → Hybrid arrangement (IR + AI projects)
- **High value** → Full-time AI role, Foundation entity path

### Objection Handling Built In
- **Job displacement** → "AI augments humans, doesn't replace"
- **Budget constraints** → "Max exposure $22.5K, no FTE costs, 5-year ROI of 618%"
- **Data security** → "Local AI models, FERPA compliant"

---

## 4. BACKLOG

1. ~~Customize placeholder names~~ ✓ (Winn Cook, Mario Martinez)
2. ~~Add industry experience~~ ✓
3. ~~Add 3rd project~~ ✓ (Enrollment Forecasting v2)
4. Review presentation in browser before Thursday
5. Practice pitch flow (About Winn → Phases → Ask)
6. Gather AI Conference insights (12/16)
7. Deliver to Mario (12/18)

---

## 5. COMPLETED (RECENT)

- [2025-12-15 Session 1] Program initialized: Charter, folder structure, templates
- [2025-12-15 Session 2] Built index.html and dashboard.html with full functionality
- [2025-12-15 Session 3] **Major Strategic Pivot:**
  - Rebranded from "IR Innovation Lab" to "AI Exploration Initiative"
  - Added "About Winn" credentials section (2+ years AI, all major models, local training)
  - Added "Phased Approach" section with visual timeline and three-path outcomes
  - Added "Future Vision" section (Foundation entity, revenue, data security)
  - Completely rewrote "The Ask" with specific stipend amounts
  - Added Investment vs. Return breakdown to ROI section
  - Updated Dashboard DEFAULT_DATA and branding
  - Built in objection handling (jobs, budget, security)
- [2025-12-15 Session 4] **Final Polish:**
  - All stipends → ~$5K* with footnote (negotiable per project)
  - Added "Winn Cook" to About section title
  - Added private industry experience (real estate, software, restaurant, consulting)
  - Updated AI tools: Claude, ChatGPT, Gemini, Grok, Llama
  - Rebranded "Track Record" → "AI Track Record at FLC"
  - Added AI Institute leader and Provost Mario Martinez mentions
  - Updated "Why This Matters" to connect to Provost's Office AI work
  - Changed "Built in Hours" → "Built in Minutes"
  - Added 3rd project: Software Replication Workflow (1 app/month, purple card)
  - Added Command Center nav link (purple gradient button)
  - Updated Dashboard DEFAULT_DATA with 4th initiative
- [2025-12-15 Session 7] **Content Refinement & PDF Export:**
  - Moved "Winn Cook" to first bullet point (matches Mario Martinez format)
  - Updated AI deployment bullet to emphasize software development workflows
  - Added FERPA/PII compliance messaging to Measured Risk card
  - Removed "Workday Analytics" from Future Pipeline, fixed grid to 3 columns
  - Rebranded "Data Security Leadership" → "Locally Trained AI"
  - Softened "The Fit" callout (removed "rare combination")
  - Generated full-page PDF export of presentation

---

## 6. OPEN LOOPS

### Waiting For
- [ ] AI Conference insights (12/16) - may add to pitch
- [x] Strategic direction - **DECIDED: Per-project stipends, phased approach**

### Decisions Made
- [x] Project cost: **$7,500 per project** (finalized)
- [x] Total Phase 1: **$22,500** investment
- [x] Future entity: Foundation/auxiliary (revenue-generating)
- [x] Credentials emphasis: Prominent dedicated section
- [x] Emotional sell: All three (FOMO + Low Risk + Trust)
- [x] 3rd project: Enrollment Forecasting v2 (replaced Software Replication)
- [x] Dashboard: 5-year executive-grade financial projection table
- [x] Value props: Editable rationale bullets for each initiative

### Blocked Items
- None

---

## 7. INITIATIVE STATUS BOARD

| Initiative | Status | Next Action | Priority |
|------------|--------|-------------|----------|
| VP Presentation 12/18 | **READY** | Practice flow, deliver | CRITICAL |
| Event Management App (Phase 1) | PLANNING | Await VP approval | High |
| AI Meeting Assistant (Phase 1) | PLANNING | Await VP approval | High |
| Enrollment Forecasting v2 (Phase 1) | PLANNING | Await VP approval | High |

---

## 8. SESSION CONTINUITY

### For Next Session

**Start Here:** Review the presentation in browser, practice pitch

**Files to Open (ALL AT ROOT LEVEL):**
1. `index.html` - THE PITCH (main presentation)
2. `dashboard.html` - Command Center with 5-year projections
3. `partnership-path.html` - ALTITUDE AI ALTERNATIVE
4. `origin-story.html` - Skunk Works history
5. `initiatives/vp-presentation-121825/artifacts/html-showcase/pitch-script.md` - PITCH BULLET POINTS & TIPS

**Key Paths:**
```
C:\Users\winnl\Documents\FLC - Skunk Works\
├── @Active_State.md             ← This file
├── @Program_Charter.md          ← Program foundation
├── index.html                   ← VP PITCH (SINGLE SOURCE OF TRUTH)
├── dashboard.html               ← COMMAND CENTER
├── partnership-path.html        ← ALTITUDE AI ALTERNATIVE
├── origin-story.html            ← SKUNK WORKS HISTORY
└── initiatives/vp-presentation-121825/artifacts/html-showcase/
    ├── pitch-script.md          ← PITCH BULLET POINTS
    ├── FLC-Skunk-Works-Presentation.pdf
    └── (NO MORE HTML DUPLICATES - deleted Session 17)
```

**Presentation Sections (in order):**
1. Hero - "AI Exploration Initiative" with low-risk stats
2. About Winn - Credentials and track record
3. Program Overview - Mission + 5 principles (incl. Measured Risk, Transparency)
4. Phased Approach - Timeline, decision point, three paths
5. Phase 1 Projects - Event Management App, AI Meeting Assistant, Enrollment Forecasting v2
6. ROI - Investment vs. Return breakdown
7. AI Capabilities - What we can build
8. Future Vision - Foundation entity, revenue, data security
9. The Ask - Specific stipend amounts and decision framework

**Handoff Notes:**
- Presentation is DONE and ready for TODAY (Wednesday 12/18)
- **Session 17 major improvements:**
  - Math is now accurate and defensible ($9,300 Year 1, $15,000+ Year 2+)
  - 50/50 payment structure adds FLC protection
  - FLC Protections + Worst Case Scenario sections ease executive concerns
  - Monthly progress reports show transparency
- The pitch structure hits all three emotions (FOMO, confidence, trust)
- Objections pre-addressed in the content
- **IMPORTANT:** HTML files are now at ROOT LEVEL ONLY - no more nested duplicates
- Goal: Get Mario to say YES to Phase 1 per-project structure (stipend or partnership)

### Session Log
| Date | Platform | Focus | Key Outcomes |
|------|----------|-------|--------------|
| 2025-12-15 | Claude | Initialization | Charter, structure, Active State |
| 2025-12-15 | Claude | Build | Dashboard, showcase, PDF export |
| 2025-12-15 | Claude | Strategic Pivot | Complete presentation transformation |
| 2025-12-15 | Claude | Final Polish | Names, stipends, 3rd project, nav link |
| 2025-12-15 | Claude | Content Refinement | FERPA messaging, Locally Trained AI, PDF export |
| 2025-12-15 | Claude | Origin Story Page | New page explaining Skunk Works history & FLC analogy |
| 2025-12-15 | Claude | GitHub Deployment | Deployed to GitHub Pages, fixed dashboard Productivity card |
| 2025-12-16 | Claude | Project Swap | Enrollment Forecasting v2, academic grades (C+/B+/A+), FLC Brandify |
| 2025-12-16 | Claude | Partnership Path | Altitude AI entity, vendor approach, simplified nav, 7 benefits |
| 2025-12-16 | Claude | Pricing & Financials | $7,500/project, 5-yr table, valueProps, stipend→cost |
| 2025-12-16 | Claude (Opus 4.5) | Pitch Perfection | Conservative defaults, $15K+ value, Jan-Aug timeline, pitch-script.md |
| 2025-12-16 | Claude (Opus 4.5) | Final Polish | Expandable initiatives, mobile hamburger menu, ROI calc removed, exec-focused partnership section |
| 2025-12-16 | Claude (Opus 4.5) | Description Polish | AI Meeting Assistant pitch (compliance, PD), dashboard expand-all fix |
| 2025-12-17 | Claude (Opus 4.5) | **Professional Overhaul** | 50/50 payment, accurate math ($9,300 Y1), FLC protections, worst case, monthly reports, repo cleanup |

---

## 9. GIT STATUS

```
Session 17 Commits (pushed to main):
- 6e255a8: Remove duplicate HTML files from nested folder (SINGLE SOURCE OF TRUTH)
- 35367a4: Sync root files with showcase updates for GitHub Pages
- 360e837: Professional pitch overhaul: accurate math, 50/50 payment terms, FLC protections

Session 16 Commits (pushed to main):
- c93726e: Fix initiative cards - click expands all three together
- 301d69f: Strengthen AI Meeting Assistant pitch
- 71c3c6c: Polish initiative descriptions, improve dashboard UX

All changes committed and pushed to:
https://github.com/WinnCook/flc-skunkworks-presentation

IMPORTANT: HTML files are now at ROOT LEVEL ONLY (no more duplicates in initiatives folder)

DATA_VERSION: 14 (forces fresh localStorage on web visitors)
```

---

## QUICK COMMANDS

| Command | Action |
|---------|--------|
| `continue` | Resume from Active Task above |
| `SITREP` | Generate VP-ready status report |
| `end session` | Save state, commit changes |
| `test presentation` | Open index.html in browser for review |

---

*This is the "mission card" - updated after every session. For program vision, see @Program_Charter.md.*
