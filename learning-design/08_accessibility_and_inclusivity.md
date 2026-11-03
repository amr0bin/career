# 08 · Accessibility and Inclusivity

## Why This Matters

Accessibility is not a compliance checkbox — it is a fundamental dimension of quality learning design. When a course is inaccessible to some learners, it doesn't matter how pedagogically brilliant the rest of the design is.

Inclusive design goes further: it recognises that learners come with diverse backgrounds, languages, abilities, learning preferences, and life circumstances — and that the best design works well for the widest possible range of people.

> Designing for accessibility benefits everyone. Captions help non-native speakers, learners in noisy environments, and those with hearing impairments. Clear structure helps learners with cognitive differences, learners under stress, and anyone skimming for a specific piece of information.

---

## Key Frameworks

### WCAG 2.2 (Web Content Accessibility Guidelines)
WCAG 2.2 (W3C Recommendation, October 2023) is the current version; it keeps everything in 2.1 except one removed criterion (4.1.1 Parsing) and adds nine success criteria, mostly on focus visibility, target size, dragging, consistent help, redundant entry and accessible authentication. Many institutional policies still cite 2.1 AA; designing to 2.2 AA meets both. The international standard for digital accessibility, organised around four principles. Content must be:

| Principle | Meaning | Examples |
|---|---|---|
| **Perceivable** | Information must be presentable in ways all users can perceive | Alt text for images, captions for video, sufficient colour contrast |
| **Operable** | UI components must be operable by all users | Keyboard navigation, no seizure-inducing content, enough time to complete tasks |
| **Understandable** | Content and operation must be understandable | Plain language, consistent navigation, error messages that explain how to fix the problem |
| **Robust** | Content must be interpretable by assistive technologies | Valid HTML, ARIA labels, compatibility with screen readers |

**Conformance Levels:**
- **Level A** — minimum requirements
- **Level AA** — standard target for most institutions (aim here)
- **Level AAA** — highest level; not always achievable for all content

### Universal Design for Learning (UDL)
UDL (CAST; Guidelines 3.0, 2024) is a framework for designing flexible learning experiences that address learner variability from the start — not as an accommodation added after the fact.

UDL is organised around three principles — provide multiple means of (Guidelines 3.0 list Engagement first and add an explicit focus on identity, belonging and bias):

| UDL Principle | What It Addresses | Design Implications |
|---|---|---|
| **Representation** | How learners perceive and comprehend information | Offer content in multiple formats (text, audio, video); use clear language; provide glossaries |
| **Action and Expression** | How learners demonstrate what they know | Offer choice in how learners respond (write, record, draw, present) |
| **Engagement** | How learners are motivated and sustained | Offer choice and autonomy; connect to real-world relevance; build community |

---

## Accessibility by Content Type

### Text Content
- Use proper heading hierarchy (H1 → H2 → H3 — don't skip levels)
- Write in plain language (aim for Grade 10–12 reading level for most adult learners)
- Use meaningful link text ("Read the accessibility guide" not "Click here")
- Avoid conveying information through colour alone (e.g., "the items in red are incorrect")
- Ensure sufficient colour contrast (minimum 4.5:1 ratio for body text — WCAG AA)
- Use bullet lists and tables purposefully; tables need headers

### Images and Graphics
- Every image needs **alt text** that conveys the same meaning as the image
  - Decorative images: use empty alt attribute (`alt=""`)
  - Informational images: describe what the image communicates, not just what it shows
  - Complex images (charts, diagrams): provide a full text description in the surrounding content
- Avoid text embedded in images (screen readers can't read it)
- Ensure infographics have accessible equivalents (e.g., a data table)

### Video
- **Captions:** All video content needs accurate captions (not just auto-generated — human-reviewed)
- **Transcript:** Provide a full text transcript alongside every video
- **Audio description:** If visual information not conveyed in the audio is essential, provide an audio description track
- **No autoplay:** Do not autoplay video or audio
- **Pause/play control:** Learners must be able to control playback

### Audio / Podcasts
- Provide a full text transcript
- Ensure audio is clear and of good quality (poor audio is inaccessible to many, not just those with hearing impairments)

### Interactive Activities and eLearning
- All interactions must be keyboard navigable
- Use sufficient time limits — or allow learners to extend time
- Provide non-interactive alternatives for activities that cannot be made accessible
- Test with assistive technologies (screen readers, keyboard-only navigation)

### PDFs
- PDFs must be tagged (not just scanned images)
- Ensure reading order is logical
- All images need alt text
- Forms must be accessible
- Prefer HTML over PDF where possible — HTML is inherently more accessible and responsive

---

## Inclusive Course Design Beyond Accessibility

### Language and Representation
- Use **inclusive language** throughout (gender-neutral where possible, avoid assumptions about family structure, cultural background, physical ability)
- **Represent diverse voices** in examples, case studies, and readings — not just dominant cultural perspectives
- Use **person-first or identity-first language** as appropriate to context and community
- Avoid idioms or culturally specific references that may not translate for international or ESL learners

### Learner Flexibility and Choice
- Offer **multiple means of accessing content** where possible (read the article, or watch the summary video, or listen to the podcast version)
- Allow **flexible deadlines** where institutional policy permits
- Provide **self-assessment and low-stakes practice** so learners can gauge their own progress without penalty
- Design assessments that don't assume access to specific technology or environments (not everyone has a webcam or quiet space at home)

### Prior Knowledge and Context
- Be explicit about assumed prior knowledge — don't just assume learners have it
- Provide **bridging resources** (glossaries, prerequisite review modules, introductory readings) for learners who may need them
- Use examples from **multiple professional and cultural contexts**, not just the dominant one in the discipline

### Trauma-Informed Design
- Provide **content warnings** for material covering trauma, violence, discrimination, or distressing topics
- Offer **learner choice** over whether to engage with certain content (where possible)
- Design a **welcoming and psychologically safe course environment** in the tone of instructions, feedback, and discussion prompts

---

## Accessibility Review Checklist

Use this during Stage 15 (QA Report) or as an ongoing design check.

### Text and Structure
- [ ] Heading hierarchy is logical and consistent
- [ ] Plain language used throughout
- [ ] Link text is meaningful (no "click here")
- [ ] Colour is not the only way information is conveyed
- [ ] Colour contrast meets WCAG AA standards

### Media
- [ ] All images have appropriate alt text
- [ ] Complex images have text descriptions
- [ ] All videos have accurate human-reviewed captions
- [ ] All videos and audio have transcripts
- [ ] No content autoplays

### Navigation and Interaction
- [ ] All interactive elements are keyboard navigable
- [ ] LMS course structure is logical and consistent
- [ ] PDFs are tagged and readable by screen readers

### Inclusive Design
- [ ] Language is inclusive and bias-free
- [ ] Examples and case studies represent diverse contexts
- [ ] Content warnings are provided where needed
- [ ] Bridging resources are available for assumed prior knowledge
- [ ] Assessment design offers flexibility where appropriate

---

## Tools for Accessibility Checking

| Tool | Purpose |
|---|---|
| **WAVE (WebAIM)** | Web accessibility evaluation — browser extension |
| **Colour Contrast Analyser** | Check foreground/background contrast ratios |
| **axe DevTools** | Automated accessibility testing for web content |
| **Adobe Acrobat Pro** | PDF accessibility checker and remediation |
| **NVDA / VoiceOver / JAWS** | Screen readers for manual accessibility testing |
| **Microsoft Accessibility Checker** | Built into Word, PowerPoint — catches common issues |
| **Canvas Ally / Anthology Ally** | LMS-integrated accessibility checker |

---

### The social model, in practice
Treat every barrier found in review as a property of the design, not of the learner. Where a course still relies on individual accommodation, ask whether the assessment is measuring the *construct* or one *method* of showing it; if it is the method, design the flexibility in. This is the same distinction the corpus study codes (`../knowledge/research-designs.md`, code 1).

> 💡 **See also:** `07_content_and_media_development.md` for media production guidelines · `05_assessment_design.md` for accessible assessment design · `09_tools_and_technology.md` for accessibility tools
