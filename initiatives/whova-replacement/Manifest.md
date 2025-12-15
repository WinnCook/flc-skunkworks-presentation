# Initiative Manifest: Whova App Replacement
**Slug:** whova-replacement
**Created:** 2025-12-15
**Owner:** [Your Name], Institutional Researcher
**Sponsor/Requestor:** Internal initiative (IR Skunk Works)

---

## 1. INITIATIVE SUMMARY

**One-Liner:** Build an in-house conference management app to replace Whova, saving $4k/year and creating potential licensing revenue.

**Problem Statement:**
Fort Lewis College currently pays approximately $4,000/year for Whova to manage the AI Conference and potentially other events. The platform works but has limitations we can't customize, and the cost adds up. Other small colleges face the same challenge with limited budgets for conference technology.

**Proposed Solution:**
Build a custom conference management progressive web app (PWA) that handles:
- Event scheduling and agenda
- Attendee registration and networking
- Session check-ins and feedback
- Announcements and push notifications
- Speaker and sponsor management

Once proven at FLC, license to other small colleges as a revenue stream.

---

## 2. VALUE PROPOSITION

### 2.1 Expected Benefits
| Benefit Type | Description | Estimated Value |
|--------------|-------------|-----------------|
| Cost Savings | Eliminate Whova subscription | $4,000/year |
| Revenue Potential | License to 5-10 small colleges @ $500-1000/year | $2,500-10,000/year |
| Customization | Build exactly what we need | Qualitative |
| Control | Own the data and platform | Qualitative |
| Demonstration | Show AI/tech capabilities | Strategic |

### 2.2 Stakeholder Impact
| Stakeholder | Impact | Visibility |
|-------------|--------|------------|
| VP | Cost savings, revenue potential, innovation showcase | High |
| AI Conference Attendees | Better customized experience | Medium |
| Other Colleges | Affordable conference tool option | Future |

### 2.3 Initiative Score
| Criterion | Score (1-5) | Notes |
|-----------|-------------|-------|
| Impact | 4 | $4k savings + revenue potential |
| Visibility | 5 | Direct cost elimination, VP will see |
| Feasibility | 4 | PWA tech is mature, scope is known |
| Timeliness | 3 | Not urgent, but AI Conference is annual |
| Strategic Fit | 5 | Perfect Skunk Works project |
| WOW Factor | 4 | Building our own app is impressive |
| **TOTAL** | **25/30** | Strong candidate |

---

## 3. SCOPE

### 3.1 In Scope (MVP)
- Event agenda/schedule display
- Session details and speaker info
- Attendee directory (opt-in)
- Push notifications for announcements
- Session feedback/ratings
- Offline capability (PWA)
- Admin dashboard for event management

### 3.2 Out of Scope (Initial)
- Payment processing for registration
- Live streaming integration
- Complex networking matching algorithms
- Native iOS/Android apps (PWA only initially)
- Multi-language support

### 3.3 Dependencies
- Web hosting (can use FLC infrastructure or free tier services)
- Push notification service (Firebase free tier)
- Domain/SSL (FLC can provide)

---

## 4. APPROACH

### 4.1 Phases
| Phase | Activities | Deliverable |
|-------|------------|-------------|
| 1. Research | Analyze Whova features, survey users, define MVP | Requirements doc |
| 2. Design | UI/UX design, architecture, data model | Figma mockups, tech spec |
| 3. Build MVP | Core features development | Working app |
| 4. Test | Internal testing at small event | Tested app |
| 5. Deploy | Use for 2026 AI Conference | Production app |
| 6. Commercialize | Package for other colleges | Licensing model |

### 4.2 Tech Stack (Proposed)
| Component | Technology | Rationale |
|-----------|------------|-----------|
| Frontend | React/Next.js or Vue | Modern, PWA-capable |
| Backend | Node.js or Python/FastAPI | Quick development |
| Database | PostgreSQL or Firebase | Reliable, scalable |
| Hosting | Vercel/Netlify or FLC servers | Free tier available |
| Notifications | Firebase Cloud Messaging | Free, reliable |

### 4.3 Resources Needed
| Resource | Description | Status |
|----------|-------------|--------|
| Developer time | IR + AI assistance | Have |
| Hosting | Free tier or FLC | Have |
| Domain | flc.edu subdomain | Need to request |
| Test users | AI Conference committee | Have |

---

## 5. RISKS & MITIGATIONS

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| Scope creep | Medium | High | Strict MVP definition, defer nice-to-haves |
| Technical complexity | Low | Medium | Use proven tech stack, AI assistance |
| User adoption | Low | Medium | Involve users in design, beta testing |
| Maintenance burden | Medium | Medium | Build for simplicity, document well |

---

## 6. SUCCESS CRITERIA

### 6.1 Definition of Done
- [ ] App handles all core Whova functions we use
- [ ] Successfully used for one FLC event
- [ ] At least 80% positive user feedback
- [ ] Whova subscription cancelled
- [ ] Documentation complete for handoff

### 6.2 Success Metrics
| Metric | Target | Measurement |
|--------|--------|-------------|
| Feature parity | 100% of MVP features | Checklist |
| User satisfaction | 80%+ positive | Survey |
| Reliability | 99%+ uptime during events | Monitoring |
| Cost savings | $4,000/year | Budget comparison |

---

## 7. FILE INDEX

| File | Purpose | Status |
|------|---------|--------|
| Active_State.md | Current working state | Active |
| /artifacts/ | Design docs, code, etc. | Empty |

---

## CHANGELOG

| Date | Change | Rationale |
|------|--------|-----------|
| 2025-12-15 | Created | Initiative kickoff |
