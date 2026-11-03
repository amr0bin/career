# 11 · Evaluation and Quality Assurance

## Overview

Evaluation and quality assurance are two distinct but related activities:

- **Quality Assurance (QA)** happens *before* launch — it confirms that the course meets defined standards of quality across pedagogy, accessibility, and technical function.
- **Evaluation** happens *during and after* the course runs — it assesses whether the course achieved its intended learning outcomes and what should change.

Both are essential. QA without evaluation tells you the course was built well but not whether it worked. Evaluation without QA risks launching a course with preventable errors.

---

## Quality Assurance

### What QA Reviews

A thorough QA review covers four dimensions:

| Dimension | What's Checked |
|---|---|
| **Pedagogical quality** | Alignment of outcomes, activities, and assessments; clarity of instructions; appropriate challenge level |
| **Accessibility** | WCAG compliance; captions; alt text; keyboard navigation; colour contrast (see `08_accessibility_and_inclusivity.md`) |
| **Technical function** | All links work; media plays; LMS tools function correctly; submission tools configured |
| **Consistency and polish** | Consistent formatting; no broken placeholders; professional tone throughout |

### QA Frameworks

| Framework | Description | Best For |
|---|---|---|
| **Quality Matters (QM)** | Research-based rubric with 8 general standards and a set of specific review standards (count varies by edition; check the current Higher Education Rubric) | Higher education; formal peer review |
| **OLC OSCQR** | Open-source rubric; 50 standards; free | Higher education; quick self-review |
| **Institutional rubric** | Custom rubric developed by your institution or team | When QM or OSCQR don't fit your context |
| **Bespoke checklist** | Your own checklist built from the above | Lightweight reviews; rapid QA |

### QA Process

**Who reviews:**
- Ideally, someone other than the LXD who built the course (fresh eyes catch different things)
- For formal QM review: certified QM reviewer required
- For lightweight QA: a peer LXD or learning technologist is sufficient

**When to QA:**
- When content is complete and formatted (not at first draft)
- Before beta testing — QA fixes technical issues that would distract beta testers from pedagogical feedback
- After final revisions following beta testing — confirm nothing was broken

**QA Workflow:**
1. Run through the course as a student (use student view in the LMS)
2. Complete the QA checklist systematically
3. Log all issues with location, description, severity (critical / major / minor), and recommended fix
4. Share the QA report with the LXD and SME
5. Track resolution of each issue before launch sign-off

### QA Severity Levels

| Severity | Description | Examples | Action |
|---|---|---|---|
| **Critical** | Blocks learning or is inaccessible | Broken submission link; video with no captions; missing assessment | Fix before launch — no exceptions |
| **Major** | Significantly affects the learner experience | Missing content; confusing instructions; misaligned assessment | Fix before launch |
| **Minor** | Small errors that don't impede learning | Typo; inconsistent formatting; minor link issue | Fix if time allows; log for next revision |

---

## Beta Testing

Beta testing is your opportunity to test the course with real or representative learners before the full cohort experiences it.

### Why Beta Testing Matters
Even the most carefully designed course has blind spots. What seems clear to the designer and SME may be confusing to learners. Beta testing catches:
- Navigation confusion
- Unclear instructions
- Broken or confusing activities
- Pacing problems
- Content gaps or errors
- Technology barriers

### Beta Testing Process

**Who participates:**
- 3–8 learners who represent the target audience
- Can be actual students from a previous cohort, peers from a related program, or volunteer participants
- Avoid using colleagues who know the content deeply — you need the learner's perspective

**What beta testers do:**
- Complete course activities as a real learner would
- Note any moment of confusion, frustration, or uncertainty
- Complete a structured feedback survey at the end

**Beta Testing Feedback Survey — Key Questions:**
- What was confusing or unclear? (navigation, instructions, content)
- Were there any technical problems? (broken links, media that didn't load)
- What did you find most useful or engaging?
- What would you change or add?
- How long did this take you? Did the time estimate match?
- On a scale of 1–5, how ready do you feel to [core skill/outcome]?

**After the session:**
- Compile feedback into the Beta Testing Report (Stage 14)
- Prioritise issues using severity levels (Critical → Major → Minor)
- Present findings and recommendations to the SME
- Agree on what will be fixed before launch vs. flagged for the next revision

---

## Evaluation

Evaluation asks: **Did the course work?** It moves beyond quality (was it built well?) to effectiveness (did learners learn?).

### Kirkpatrick Model (Four Levels)

The most widely used evaluation framework for learning and training:

| Level | Question | Data Sources |
|---|---|---|
| **1. Reaction** | Did learners find the course valuable and satisfying? | End-of-course survey; satisfaction ratings |
| **2. Learning** | Did learners achieve the intended outcomes? | Pre/post assessments; assignment performance; quiz data |
| **3. Behaviour** | Are learners applying what they learned? | Follow-up survey (4–8 weeks post); supervisor feedback; portfolio evidence |
| **4. Results** | Did the course produce meaningful outcomes? | Organisational metrics; program completion rates; downstream performance |

> Most learning design evaluations reach Level 1 and Level 2. Levels 3 and 4 require longitudinal data collection and are more appropriate for high-stakes programs.

### Additional Evaluation Frameworks

**CIPP Model (Stufflebeam):** Evaluates Context, Input, Process, and Product — useful for program-level evaluation where you need to assess the design decisions themselves, not just outcomes.

**Phillips ROI Model:** Extends Kirkpatrick with Level 5 (Return on Investment) — converts Level 4 results to monetary value. Primarily used in corporate L&D.

### Formative vs. Summative Evaluation

| Type | When | Purpose |
|---|---|---|
| **Formative** | During design and development | Improve the course before launch |
| **Summative** | After the course runs | Judge effectiveness; inform future design |

Formative evaluation includes: storyboard reviews, SME feedback cycles, beta testing, QA review.
Summative evaluation includes: end-of-course surveys, learning analytics, post-course follow-up.

---

## Learning Analytics

Most LMSs provide data that can inform evaluation. Know what's available and how to interpret it.

| Metric | What It Indicates |
|---|---|
| **Completion rates** | How many learners finish modules, activities, or the course |
| **Time on page / in module** | Engagement level; whether content is taking unexpectedly long or short |
| **Quiz attempt data** | Where learners struggle; which questions have low success rates |
| **Discussion participation** | Engagement with collaborative activities |
| **Assessment grades** | Outcome achievement; patterns of success or struggle |
| **Login frequency** | Overall engagement pattern; early warning of disengagement |

**Cautions:**
- Analytics show *what*, not *why* — low completion might mean the content is poor, or the instructions are confusing, or learners are time-pressed
- Always triangulate analytics with qualitative data (surveys, learner comments, faculty observation)
- Be careful about privacy — aggregate data before sharing; don't draw individual conclusions without consent

---

## Evaluation-Impact Report (Stage 18)

The Evaluation-Impact Report documents what the design intervention achieved and contributes to institutional knowledge.

**Contents:**
- Project overview (what was designed, for whom, over what timeline)
- Evaluation data summary (Levels 1–2 at minimum)
- Key findings (what worked, what didn't, what surprised you)
- Design decisions that made a difference
- Recommendations for the next iteration
- Quantitative impact where available (enrolment, completion, satisfaction scores, grade distributions)

**Audience:** Your manager, the SME, institutional leadership, and your own professional portfolio.

---

## Quality and Evaluation Checklist

### Pre-Launch QA
- [ ] All links are functional
- [ ] All media plays correctly
- [ ] Captions and transcripts are present and accurate
- [ ] LMS submission tools are configured correctly
- [ ] Course is navigable as a student (student view tested)
- [ ] All accessibility issues from QA report are resolved or documented
- [ ] SME has given final approval

### Beta Testing
- [ ] Beta testing session completed with representative learners
- [ ] Structured feedback collected
- [ ] Beta testing report completed
- [ ] Priority issues resolved before launch

### Post-Launch Evaluation
- [ ] End-of-course survey deployed
- [ ] Learning analytics reviewed
- [ ] Evaluation data shared with SME
- [ ] Evaluation-impact report completed
- [ ] Sustainment plan updated based on evaluation findings

---

> 💡 **See also:** `01_workflow_reference.md` for Stages 13–18 detail · `08_accessibility_and_inclusivity.md` for accessibility QA · `05_assessment_design.md` for assessment-level evaluation
