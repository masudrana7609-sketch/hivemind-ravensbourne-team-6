# Information Architecture — Smart Onboarding

**Project:** HiveMind × Ravensbourne – UX Product Discovery Sprint
**Focus Area:** Smart Onboarding
**Author:** Team 6
**Last Updated:** 2026-04-11

---

## Overview

This IA defines the structure of the Smart Onboarding solution — what exists, where it lives, and how a new starter navigates through it. It is grounded in the five pain points and five hypotheses produced in Week 1.

---

## Sitemap

```
Smart Onboarding
│
├── 1. Welcome & Setup  (one-time, Day 0)
│   ├── 1.1  Personalised Welcome Screen
│   │         • New starter's name + role displayed
│   │         • Team / department shown
│   │         • Start date & "Day X" indicator
│   ├── 1.2  Profile Setup
│   │         • Select role
│   │         • Select team / department
│   │         • Set preferences
│   └── 1.3  Onboarding Overview
│             • What to expect (visual timeline)
│             • Duration of the journey
│             • What you will achieve by the end
│
├── 2. My Onboarding Journey  (main hub)
│   ├── 2.1  Progress Overview
│   │         • Overall progress bar ("Week 1 of 4")
│   │         • Tasks completed vs. remaining
│   │         • Upcoming milestones
│   ├── 2.2  Day 1 Checklist
│   │         • Essential setup tasks (tools, accounts)
│   │         • Key people to meet
│   │         • First-day orientation items
│   ├── 2.3  Weekly Tasks
│   │         • Week 1 (current, expanded)
│   │         • Week 2 (upcoming, locked)
│   │         • Week 3–4 (future, locked)
│   └── 2.4  Learning Modules
│             • Role-specific training
│             • Company culture & values
│             • Tools & systems guides
│
├── 3. Guided Next Steps
│   ├── 3.1  Today's Focus  ("what to do right now")
│   ├── 3.2  This Week's Goals
│   └── 3.3  Milestone Tracker
│             • Completed milestones ✓
│             • Current milestone (active)
│             • Next milestone (preview)
│
├── 4. Support & Contacts
│   ├── 4.1  Who to Ask
│   │         • My Manager
│   │         • Buddy / Mentor
│   │         • HR contact
│   │         • IT support
│   ├── 4.2  Team Directory
│   │         • My immediate team
│   │         • Key stakeholders
│   └── 4.3  Help Centre
│             • FAQs for new starters
│             • Request support
│
└── 5. Resources  (quick access)
    ├── 5.1  Role-specific documents
    ├── 5.2  Company policies
    ├── 5.3  Tool guides & how-tos
    └── 5.4  Saved / bookmarked items
```

---

## Design Rationale — Linked to Week 1 Research

| IA Section | Hypothesis | Interview Evidence |
|---|---|---|
| 1. Welcome & Setup | H1 — role-specific onboarding | P2, P3 said onboarding felt generic and like "box-ticking" |
| 2. Onboarding Journey | H1 — structured daily plan | All 5 participants described chaotic, unplanned first days |
| 3. Guided Next Steps | H1, H4 — clear "what to do next" | P3: "I didn't know what to do next each day" |
| 4. Support & Contacts | H5 — clear ownership / who to ask | P1, P2, P3: "I didn't know who was responsible for what" |
| 5. Resources | H2 — single source of truth | All 5 participants checked multiple places and still couldn't find things |

---

## Navigation Model

- **Primary nav:** Left sidebar (persistent across all sections)
- **Entry point:** Welcome & Setup (first-time only, then skipped)
- **Default home:** My Onboarding Journey (section 2)
- **Quick access:** Support & Contacts always reachable from nav

---

## Notes

- Figma IA diagram exported to `design/IA/` (see Figma file)
- This document is the text reference; the visual sitemap lives in Figma
