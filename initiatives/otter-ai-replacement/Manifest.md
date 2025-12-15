# Initiative Manifest: Otter AI Replacement
**Slug:** otter-ai-replacement
**Created:** 2025-12-15
**Owner:** [Your Name], Institutional Researcher
**Sponsor/Requestor:** Internal initiative (IR Skunk Works)

---

## 1. INITIATIVE SUMMARY

**One-Liner:** Deploy an open-source AI transcription solution for campus-wide meeting transcription, eliminating per-seat licensing costs.

**Problem Statement:**
Meeting transcription and note-taking is a productivity multiplier, but commercial solutions like Otter AI charge per-seat ($100-500/user/year). This limits who can access the tool. Additionally, commercial solutions send meeting audio to third-party servers, raising privacy concerns for sensitive discussions.

**Proposed Solution:**
Deploy an open-source speech-to-text solution (like OpenAI Whisper) that can:
- Transcribe meeting recordings automatically
- Generate meeting summaries and action items
- Run on FLC infrastructure (data stays local) or controlled cloud
- Be available to all staff without per-seat licensing

---

## 2. VALUE PROPOSITION

### 2.1 Expected Benefits
| Benefit Type | Description | Estimated Value |
|--------------|-------------|-----------------|
| Cost Avoidance | No per-seat licensing for transcription | $1,200-6,000/year* |
| Productivity | All staff can transcribe meetings | Hours saved campus-wide |
| Privacy | Data stays on FLC-controlled systems | Risk reduction |
| Accessibility | Better access for hearing-impaired | Compliance/inclusion |

*Estimate: 12-60 users @ $100/user/year

### 2.2 Stakeholder Impact
| Stakeholder | Impact | Visibility |
|-------------|--------|------------|
| VP | Cost avoidance, productivity, innovation | High |
| All Staff | Meeting transcription capability | High |
| Faculty | Lecture transcription possibility | Medium |
| IT | New system to consider | Medium |

### 2.3 Initiative Score
| Criterion | Score (1-5) | Notes |
|-----------|-------------|-------|
| Impact | 4 | Campus-wide productivity gain |
| Visibility | 5 | Everyone can use it |
| Feasibility | 3 | Some technical complexity |
| Timeliness | 3 | Nice to have, not urgent |
| Strategic Fit | 5 | Perfect Skunk Works - AI showcase |
| WOW Factor | 5 | "We built our own AI tool" |
| **TOTAL** | **25/30** | Strong candidate |

---

## 3. SCOPE

### 3.1 In Scope (MVP)
- Audio file upload interface
- Automatic transcription (speech-to-text)
- Basic meeting summary generation
- Downloadable transcript (text, Word, PDF)
- Simple web interface for access
- User authentication (FLC SSO ideally)

### 3.2 Out of Scope (Initial)
- Real-time live transcription
- Zoom/Teams direct integration
- Speaker identification/diarization (complex)
- Advanced analytics on meeting content
- Mobile app

### 3.3 Dependencies
- Compute resources for Whisper model
- FLC IT approval for deployment
- User training/adoption

---

## 4. APPROACH

### 4.1 Phases
| Phase | Activities | Deliverable |
|-------|------------|-------------|
| 1. Proof of Concept | Test Whisper locally, evaluate accuracy | POC demo |
| 2. Architecture | Design scalable deployment | Tech spec |
| 3. Build | Develop web interface and backend | Working system |
| 4. Pilot | Test with small group | Feedback |
| 5. Deploy | Roll out campus-wide | Production system |

### 4.2 Tech Stack (Proposed)
| Component | Technology | Rationale |
|-----------|------------|-----------|
| Transcription | OpenAI Whisper | Best open-source accuracy |
| Summarization | Local LLM or API | Extract key points |
| Frontend | Simple web app | Easy access |
| Backend | Python/FastAPI | Whisper integration |
| Hosting | FLC servers or cloud | Control over data |

### 4.3 Resources Needed
| Resource | Description | Status |
|----------|-------------|--------|
| GPU compute | For faster transcription | Need to evaluate |
| Hosting | Server/container | Need IT coordination |
| Development time | Build interface | Have (IR + AI) |

---

## 5. RISKS & MITIGATIONS

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| IT resistance | Medium | High | Early IT involvement, show value |
| Compute costs | Medium | Medium | Start small, CPU-only option exists |
| Accuracy issues | Low | Medium | Whisper is very accurate; test first |
| Low adoption | Medium | Medium | Marketing, training, easy access |

---

## 6. SUCCESS CRITERIA

### 6.1 Definition of Done
- [ ] System transcribes audio with 95%+ accuracy
- [ ] Web interface accessible to all staff
- [ ] 20+ active users in first month
- [ ] Documentation and training materials complete

### 6.2 Success Metrics
| Metric | Target | Measurement |
|--------|--------|-------------|
| Transcription accuracy | 95%+ | Sample testing |
| User adoption | 20+ monthly active users | Usage logs |
| User satisfaction | 80%+ positive | Survey |
| Processing time | < 2x audio length | Benchmarks |

---

## 7. FILE INDEX

| File | Purpose | Status |
|------|---------|--------|
| Active_State.md | Current working state | Active |
| /artifacts/ | POC code, specs, etc. | Empty |

---

## CHANGELOG

| Date | Change | Rationale |
|------|--------|-----------|
| 2025-12-15 | Created | Initiative kickoff |
