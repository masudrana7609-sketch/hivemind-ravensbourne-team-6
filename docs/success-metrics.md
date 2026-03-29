# Success Metrics – Christoph Dashboard
**Project:** HiveMind × Ravensbourne – UX Product Discovery Sprint  
**Focus Area:** "Christoph" Dashboard  
**Last Updated:** 2026-03-29

---

## 1. Overview

These metrics define how we will measure whether our Dashboard design successfully addresses Christoph's pain points — cognitive load, scattered information, no unified view, and difficult navigation — as validated by our six interviews with workplace professionals across digital marketing, retail, hospitality, healthcare, and architecture & construction.

Metrics are collected during Week 4 usability testing sessions with 3–5 professional participants.

---

## 2. Primary Success Metrics

### 2.1 Task Completion Rate
**What it measures:** Whether users can successfully complete each critical task without assistance.

| Task | Target |
|---|---|
| Find a specific piece of information on the dashboard | ≥ 80% completion |
| Navigate to a different section without getting lost | ≥ 80% completion |
| Identify what action to take next from the dashboard | ≥ 75% completion |
| Identify the latest/correct version of a document | ≥ 75% completion |

**Why it matters:** All six interviewees described spending excessive time finding information or asking colleagues for help. P6 (Project Coordinator) made a costly real-world error — ordering wrong materials — because they could not identify which document was the most current version. If users cannot complete these tasks independently and confidently, the dashboard fails its core purpose.

**How to capture:** Observe each session and record pass/fail per task. A task is "complete" if the user reaches the correct destination without facilitator assistance.

---

### 2.2 Time on Task
**What it measures:** How quickly users can complete key tasks — a direct proxy for navigation efficiency and cognitive load reduction.

| Task | Target |
|---|---|
| Find a specific piece of information | ≤ 60 seconds |
| Navigate to a new section | ≤ 30 seconds |
| Identify the correct/latest document version | ≤ 45 seconds |

**Why it matters:** P1 and P5 (Marketing Executives) both described spending more time searching for things than doing actual work. P2 (Tesco) said slow information retrieval made busy periods stressful. P6 described spending so long "hunting for info" that it caused downstream delays and mistakes. Speed of access is a consistent need across all six participants.

**How to capture:** Start a timer when the task is given, stop when the user confirms completion or gives up.

---

### 2.3 Ease of Use Rating (Per Task)
**What it measures:** The user's perceived effort for each task, on a 1–5 scale.

- **Scale:** 1 = Very difficult → 5 = Very easy
- **Target:** Average score of ≥ 4.0 across all tasks
- **Question asked after each task:** *"On a scale of 1 to 5, how easy was that to do?"*

**Why it matters:** Participants across all six interviews described current tools as requiring too many steps, too many platforms, or being impossible to navigate without asking someone. Ease of use is the baseline expectation for a dashboard that replaces scattered workflows.

---

### 2.4 Cognitive Load / Overwhelm Rating
**What it measures:** Whether the dashboard feels clear and manageable — directly addressing the overload described by all six interviewees.

- **Scale:** 1 = Very overwhelming → 5 = Not overwhelming at all
- **Target:** Average score of ≥ 4.0
- **Question asked post-test:** *"On a scale of 1 to 5, how overwhelming did the dashboard feel overall?"*

**Why it matters:** P1, P2, P3, P4, P5, and P6 all described stress and cognitive overload as a direct consequence of their current tools. P3 and P6 used identical language — "vicious circle" — to describe how overload compounds into more mistakes. A dashboard that still feels overwhelming has not solved the core problem.

---

### 2.5 Navigation Confidence Rating
**What it measures:** Whether users feel confident they know where to find things — addressing the "I had to ask three people to find one file" problem raised by P1 and P5.

- **Scale:** 1 = Not confident at all → 5 = Very confident
- **Target:** Average score of ≥ 4.0
- **Question asked post-test:** *"On a scale of 1 to 5, how confident are you that you could find what you need on this dashboard?"*

---

### 2.6 "Would You Use This?" Rating
**What it measures:** Overall desirability — whether the dashboard feels like something participants would genuinely adopt in their real working life.

- **Scale:** 1 = Definitely not → 5 = Definitely yes
- **Target:** Average score of ≥ 4.0
- **Question asked post-test:** *"On a scale of 1 to 5, how likely would you be to use this dashboard in your daily work?"*

**Why it matters:** All six interviewees independently described wanting exactly this kind of product. P6 called it a "Single Source of Truth." P5 said "a single platform with everything in one place." This metric validates whether our design delivers on that promise in practice.

---

## 3. Secondary / Qualitative Indicators

These are not scored but tracked as supporting evidence during sessions:

| Indicator | What to look for |
|---|---|
| Unprompted positive comments | Users noting something works well without being asked |
| Navigation errors | Wrong taps, backtracking, or visible confusion |
| "I would use this" statements | Any direct expression of desire to adopt the product |
| Comparison to current tools | Users favourably comparing to Google Drive, sticky notes, Teams, email threads, etc. |
| Document version confusion | Any moment a user is unsure which item is most current (critical finding from P6) |
| Privacy or trust concerns raised | Particularly relevant for any AI-assisted elements on the dashboard |

---

## 4. Interview-Grounded Validation Checkpoints

Based on what all six participants told us they need, we will specifically check:

| Interview Insight | Who Said It | Design Feature to Test | How to Measure |
|---|---|---|---|
| "I spent more time searching than working" | P1, P5 | Unified search / quick access panel | Time on task |
| "I had to ask 2–3 people to find one file" | P1, P5 | Document visibility & organisation | Task completion rate |
| "I keep things in notes but it gets messy" | P1, P3, P4, P5 | Centralised information view | Ease of use + overwhelm rating |
| "I want tasks, deadlines, and key links on one screen" | P2, P4, P5 | Task + priority panel on dashboard | Navigation confidence + qualitative feedback |
| "I ordered wrong materials because of a versioning issue" | P6 | Clear document status / version labelling | Task: identify correct document version |
| "No clear plan — sink or swim onboarding" | P1, P2, P5, P6 | Onboarding progress + what's next | Task: identify next step |
| "AI must cite its sources or I lose trust immediately" | P6 | AI source transparency indicator | Post-test interview question |
| "I trust AI for basics, not for critical things" | P1, P2, P3, P4, P5, P6 | Human escalation / AI fallback behaviour | Post-test interview question |

---

## 5. Minimum Viable Success Threshold

We consider the design **validated** if all of the following are met:

- Task completion rate ≥ 75% across all tasks
- Ease of use average ≥ 3.5
- Cognitive load rating average ≥ 3.5
- No more than 1 participant unable to complete more than 2 tasks

If these thresholds are not met, findings feed directly into recommendations in `/delivery/validation-report.md`.

---

## 6. Where Results Are Stored

- Raw session notes → `/testing/`
- Per-task scores → `/testing/tasks.md`
- Findings, analysis, and recommendations → `/delivery/validation-report.md`
