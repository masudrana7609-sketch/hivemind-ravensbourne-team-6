# Decisions Log — Smart Onboarding

**Project:** HiveMind × Ravensbourne – UX Product Discovery Sprint
**Focus Area:** Smart Onboarding
**Team:** Team 6
**Last Updated:** 2026-04-11

---

## Week 1 Decisions

### D1 — Focus area confirmed: Smart Onboarding
**Decision:** Team 6 will design for the Smart Onboarding focus area.
**Reason:** Aligned to group strengths and the pain points most consistently raised across all 5 interviews — every participant described their first days as unstructured and overwhelming.
**Impact:** All research, hypotheses, IA, and wireframes are scoped to the new starter onboarding experience.

---

### D2 — Target persona: "Christoph" (new professional starter)
**Decision:** Design for a new employee joining a company in a professional role, with 0–2 weeks on the job.
**Reason:** This matches the HiveMind brief and the participant profiles from our Week 1 interviews (retail, marketing, hospitality, healthcare, architecture).
**Impact:** Onboarding content, tasks, and contacts are framed from a first-week perspective.

---

### D3 — Interview participants: working professionals only, no students
**Decision:** All 5 interview participants were working professionals with at least 1 year of work experience.
**Reason:** Required by the project brief. Student answers would not reflect real onboarding pain points.
**Impact:** All research evidence is grounded in real workplace experience.

---

## Week 2 Decisions

### D4 — IA scope: 5 top-level sections
**Decision:** The Smart Onboarding IA has 5 sections: Welcome & Setup, My Onboarding Journey, Guided Next Steps, Support & Contacts, and Resources.
**Reason:** Each section maps directly to a Week 1 hypothesis (H1, H2, H4, H5). We excluded an AI Assistant section from scope — this is a separate group's focus area.
**Alternatives considered:** A flat single-page layout was considered but rejected because it would not support progressive disclosure (unlocking tasks week by week).
**Impact:** Wireframes and prototype are structured around these 5 sections.

---

### D5 — Navigation model: persistent left sidebar
**Decision:** Primary navigation is a persistent left sidebar (240px), matching shadcn/ui's standard enterprise layout pattern.
**Reason:** All 5 interview participants described using tools with sidebar navigation (Teams, SharePoint, Google Drive) — this pattern reduces cognitive load for new starters.
**Impact:** All 6 wireframe screens use the same sidebar navigation.

---

### D6 — Three critical user tasks selected
**Decision:** The 3 tasks chosen for design and testing are:
1. Complete the Day 1 checklist and know what to do next (H1)
2. Check onboarding progress and identify the next milestone (H4)
3. Find who to contact when stuck on a question (H5)

**Reason:** These directly target the 3 most common pain points from interviews: no structure on Day 1, no visible progress, and not knowing who to ask.
**Alternatives considered:** A 4th task ("Access role-specific learning modules") was considered but deprioritised — the 3 selected tasks cover the most critical onboarding moments.
**Impact:** Wireframes W1–W6 are designed around these 3 flows.

---

### D7 — Low-fidelity wireframes: grey-box only, no colour or typography
**Decision:** All Week 2 wireframes are grey-box only, following shadcn/ui layout patterns.
**Reason:** Week 2 brief explicitly requires low-fidelity. High-fidelity design (colour, typography, branding) is deferred to Week 3.
**Impact:** Wireframes focus on structure, logic, and user task flow — not visual design.

---

### D8 — Wireframe tool: Figma, Wireframes page
**Decision:** All wireframes are built on the "Wireframes" page of the Team 6 Figma file.
**Reason:** Agreed team convention from project setup. Keeps all design assets in one place.
**Impact:** Exports from Figma go into `design/wireframes/` in GitHub.

---

## Upcoming Decisions (Week 3)

- Colour palette and typography (to be defined using HiveMind brand and shadcn/ui tokens)
- Which wireframe screens to promote to high-fidelity
- Whether to include an AI-assisted "next step" recommendation feature in scope
