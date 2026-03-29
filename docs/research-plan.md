# Research Plan – Christoph Dashboard
**Project:** HiveMind × Ravensbourne – UX Product Discovery Sprint  
**Focus Area:** "Christoph" Dashboard  
**Last Updated:** 2026-03-29

---

## 1. Research Goal

To understand how workplace professionals currently experience information overload, scattered tooling, and difficult navigation — and to validate whether our proposed Dashboard design addresses Christoph's core pain points: cognitive load, no unified view, and difficult navigation.

---

## 2. Research Questions

The following questions guided all interviews:

1. What is your current job role and what does a typical workday look like?
2. How many different tools or platforms do you use daily to do your job?
3. How do you keep track of tasks, updates, and team information?
4. Is there a single place you go to get an overview — or is information spread across multiple places?
5. Can you describe a recent moment where finding information felt overwhelming or frustrating?
6. What slows you down the most when navigating your work tools?
7. If you had one home screen showing the most important things, what would you want it to display?
8. What information should be super quick to access — within a few clicks?
9. Have you used AI tools at work (e.g. ChatGPT, Copilot)? What was good or bad about it?
10. What would make you trust or not trust an AI tool at work?

---

## 3. Method

**Method used:** Semi-structured interviews  
**Format:** 1-to-1 conversations (in person or remote/recorded)  
**Duration:** ~30–40 minutes per session  
**When conducted:** Week 1 of the sprint (March 2026)

---

## 4. Participants

| # | Interviewer | Participant | Role | Industry | Company Size |
|---|---|---|---|---|---|
| P1 | Arnob | Anonymous | Sales Assistant | Retail (Tesco) | Large enterprise |
| P2 | Toriqul | Anonymous | Marketing Executive | Digital Marketing | ~200 employees |
| P3 | Rajan | Anonymous | Marketing Executive | Digital Marketing | ~200 employees |
| P4 | MdMasud Rana | Yena | Event Manager | Hospitality (Bantof, Soho) | Small/growing |
| P5 | Shirish | D (Anonymous) | Senior Carer | Private Nursing Home | 11–50 staff |
| P6 | Nojus | Anonymous | Project Coordinator | Architecture & Construction | Mid-size firm |

> All participants are professionals with real workplace experience. No students were interviewed, in line with the project brief.

---

## 5. Interview Questions Used

Questions were consistent in theme across all six interviews, covering:

- **Role & context** — job title, industry, company size
- **Onboarding experience** — first days, what felt unclear, what structure was (or wasn't) in place
- **Information retrieval** — where people look first, how often they check multiple places, specific examples of failing to find something
- **Tools & organisation** — current systems used, personal workarounds (notes, bookmarks, memory)
- **AI trust** — current AI usage, what builds or breaks trust, privacy concerns, when AI should defer to humans
- **Ideal solution** — what one thing would most improve their experience

---

## 6. Raw Notes & Recordings

All raw interview transcripts are stored in the `/research/transcripts/` folder:

- `Group6_P01_2026-03-25_Interview.md` — P1, Tesco Sales Assistant (Arnob)
- `Group6_P02_2026-03-25_Interview.md` — P2, Marketing Executive (Toriqul)
- `Group6_P03_2026-03-25_Interview.md` — P3, Marketing Executive (Rajan)
- `Group6_P04_2026-03-25_Interview.md` — P4, Event Manager (MdMasud Rana)
- `Group6_P05_2026-03-25_Interview.md` — P5, Senior Carer (Shirish)
- `Group6_P06_2026-03-25_Interview.md` — P6, Project Coordinator (Nojus)

---

## 7. Key Findings by Theme

### 7.1 Information is Scattered Across Multiple Places
All six participants confirmed they regularly check more than one place to find what they need. P2 and P3 (both Marketing Executives at the same firm) described spending more time searching for files than doing actual work — each had to ask two to three colleagues just to locate a single misfiled client document. P1 (Tesco) frequently had to ask colleagues or managers to locate stock information during busy periods. P4 (Event Manager) kept personal notes but still had to "search everywhere" for specific details. P5 (Carer) maintained notes and spreadsheets but acknowledged the high manual effort to keep them updated. P6 (Project Coordinator) described finding a "REVISED_FINAL" document in a random email thread after already actioning a wrong version from the Shared Drive — a mistake that caused a two-day site delay and a costly material order error.

**Implication for dashboard:** A unified, single-screen view of tasks, key documents, and contacts is strongly validated across all six participants. Version control and clear document status (e.g. "latest") is a specific need raised by P6.

### 7.2 Onboarding Felt Unstructured or Generic
Five out of six participants described their onboarding as confusing, overwhelming, or poorly structured. P2 and P3 both described it as "box-ticking" with no role-specific guidance. P1 mostly shadowed colleagues with no formal structure in place. P4 felt confused and highly stressed during their first solo event. P6 described a "sink or swim" situation — handed a laptop and told to "look through the server," with no map, no contacts list, and no tailored guidance. P5 had a more positive experience due to a supportive team, but noted that a written quick-reference guide would still have helped.

**Implication for dashboard:** A visible onboarding progress indicator, a "who to contact" section, and a clear "what's next" prompt on the dashboard would directly address this pain point across the majority of participants.

### 7.3 Cognitive Load and Stress Are Real and Frequent
All six participants mentioned stress, delays, or mistakes as a direct result of information overload or unclear navigation. P2 and P3 felt overwhelmed by scattered files and unclear daily priorities. P1 found busy periods especially stressful when information was hard to locate quickly. P4 described a "vicious circle" of time delays causing more stress and more mistakes. P5 noted stress that lingered even during sleep. P6 described the same vicious circle explicitly: "The more time I spend hunting for info, the further behind I get, which makes me more stressed, which leads to more mistakes."

**Implication for dashboard:** Reducing visible complexity and surfacing only the most relevant information at any given moment is critical. A calm, prioritised dashboard view is not a nice-to-have — it is the core value proposition.

### 7.4 AI Is Used but Trust Is Conditional
All six participants had used AI tools, primarily ChatGPT. Usage was mostly limited to language polishing, summarising meeting notes, or drafting emails quickly. Key trust barriers included: AI responses sounding generic or inaccurate for work-critical queries (P2, P3), privacy concerns around sharing company or client data (P4, P5), and — most specifically — P6 stating they would need AI to cite the source document for any factual claim before they would trust it. All six participants agreed AI should defer to humans for sensitive, high-stakes, or emotionally complex decisions.

**Implication for dashboard:** Any AI features must show exactly where answers come from (with links to source documents), allow easy verification or override, and must never handle sensitive data without explicit user consent. "Hallucinations" were mentioned as an immediate trust-killer (P6).

### 7.5 The Ideal Solution: One Unified Place
When asked what single change would most improve their experience, all six participants independently described some version of a unified system:

- P1: "All information in one easy-to-access system."
- P2: "A single platform where tasks, links, and documents are organised in one place."
- P3: "A single platform with everything in one place."
- P4: "A good format" — clear structure for everything in one place.
- P5: "A note or guidance that saves time — or even a life."
- P6: "A Single Source of Truth — one centralised dashboard where I can see my tasks, the latest document versions, and the key contacts. No more jumping between five different apps."

**Implication for dashboard:** This is the strongest signal from the research. Six out of six participants independently converged on this answer. The HiveMind Dashboard concept is directly validated.

---

## 8. Synthesis Approach

After collecting all six transcripts, the team:

1. Reviewed all raw notes and transcripts together
2. Clustered recurring themes using affinity mapping on the Figma Research page
3. Identified the five top pain point themes documented in Section 7 above
4. Used these themes to write hypotheses stored in `/docs/hypotheses.md`

---

## 9. Ethical Considerations

- All participants gave verbal consent to be recorded or interviewed for academic research purposes
- Participant identities are anonymised in all documentation (referred to by role or code name)
- No personally identifiable client or company data is stored in the repository
- Participation was voluntary
