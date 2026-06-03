---
name: case-study-generator
description: Generates senior-level product design case studies in Markdown from raw project notes, accomplishment docs, or brief descriptions. Use this skill whenever a designer needs to write, rewrite, or improve a portfolio case study. Triggers on "write my case study", "turn this into a case study", "help me document this project", "build a case study for [project name]", or any request to frame a design project for a senior portfolio. The skill specifically bridges the gap between describing WHAT was done vs. WHY decisions were made -- which is the key signal hiring managers use to evaluate senior designers.
---

# Case Study Generator — Senior Product Designer Portfolio

## Purpose
Transform raw project notes, accomplishment bullets, and process descriptions into senior-level portfolio case studies. The output should demonstrate design leadership, strategic thinking, and decision-making rationale — not just deliverable lists.

The single most common gap this skill addresses: designers describe **what** they did, not **why** they made decisions. Hiring managers for senior roles evaluate judgment, not output. This skill surfaces the judgment layer.

## Designer Context — Collect Before Writing

Before generating a case study, establish:
- **Designer's level & target role**: mid -> senior, senior -> staff, IC -> leadership, etc.
- **Industry & platform context**: enterprise SaaS, consumer, mobile, design systems, etc.
- **Team structure**: sole designer, design team, dual role (e.g. designer + Scrum Master)
- **Relationship to the project**: greenfield, inherited, self-initiated, assigned

If the designer hasn't provided these, ask before writing. A case study written without context will miss the framing that makes it land.

## Case Study Structure

Always produce these 8 sections in order:

### 1. Header Block
```
# [Project Title]
**Role:** [Designer's specific role]
**Timeline:** [Duration and dates]
**Team:** [Who was involved]
**Platform:** [Web / mobile / CMS / design system / etc.]
**Company:** [Company name]
```

### 2. The One-Line Impact
One sentence. Lead with the outcome, not the action. This is the hook.

Strong example:
> "Designed a no-code CMS in 10 working days that enabled 83 clients to self-serve 255 modular experiences — with zero support tickets post-launch."

The test: would a design director forward this sentence to a hiring committee? If not, rewrite it.

### 3. Context & Problem
Two paragraphs:
- **Business context**: Why did this project exist? What was the cost of the status quo?
- **Design problem**: What specifically was broken from a user/client experience perspective?

Do NOT open with "The problem was..." — frame it as a story of discovery.

### 4. Designer's Role & Constraints
Be specific about:
- What decisions the designer owned vs. what was collaborative
- Time pressure, resource constraints, scope ambiguity, organizational complexity
- What made this genuinely hard

This section separates senior designers from mid-level. If everything was smooth, find the honest friction.

### 5. Design Decisions (The Core Section)
For each major decision, use this structure:

```
**Decision: [What was decided]**
Why I chose this over alternatives: [The reasoning]
What I had to give up: [The tradeoff]
How I validated it: [Research, testing, stakeholder feedback, post-launch data]
```

Minimum 3 decisions. Real forks-in-the-road where a different designer might have chosen differently.

The distinction that matters:
- Weak (step): "Conducted usability testing with 24 participants"
- Strong (decision): "Chose moderated over unmoderated testing because we needed to understand WHY fans hesitated, not just where they failed"

### 6. Process Narrative
A flowing paragraph (not bullets) walking through the project chronologically. Must include:
- Something that surprised the designer
- A moment where direction changed
- How the designer communicated progress and uncertainty to stakeholders
- What collaboration with engineering / PM actually looked like

This reads like a story, not a methodology checklist.

### 7. Outcome & Impact
Three tiers:

**User/Client Impact:** What changed for the people using the product?
**Business Impact:** Metrics, efficiency gains, cost savings, revenue enablement
**Org/Team Impact:** Documentation, standards, processes that outlived the project

Then — mandatory: **"What I'd do differently"** — one honest, specific paragraph. Push for the specific decision the designer would revisit, not a generic answer.

### 8. Image Placeholders
At natural break points throughout, insert:
```
[IMAGE: Brief description of what screenshot/diagram would go here]
```

Place 4-6 placeholders where they do storytelling work — not appended at the end.

---

## Tone & Voice Guidelines

**DO:**
- Write in first person: "I chose...", "I pushed back on...", "I noticed..."
- Name specific tradeoffs: "This meant sacrificing X in order to gain Y"
- Show judgment: "The initial instinct was X — I argued for Y because..."
- Use active voice throughout

**DON'T:**
- Use passive voice: "A WYSIWYG editor was designed..."
- List process steps without rationale
- Hedge: "I sort of helped with..."
- Use internal jargon without explanation

---

## Input Handling

Accepts inputs in any form:
1. Raw accomplishment bullets
2. Brief project description
3. Partial draft (rewrite mode)
4. Project name only — ask 3 questions first

### When input is sparse — ask these before writing:
1. "What was the moment you realized the original approach wasn't going to work — and what did you do?"
2. "What's one decision you made that a less experienced designer might not have made?"
3. "If you had to cut one week from this project, what would you have cut and why?"

Don't write the case study until you have answers to at least two of these.

---

## Quality Check Before Outputting

- [ ] The "why" behind each major decision is explicit
- [ ] At least one moment of changed direction or honest struggle is in the narrative
- [ ] "What I'd do differently" is present and specific
- [ ] No section reads like a resume bullet list
- [ ] Image placeholders are at narrative break points, not dumped at the end
- [ ] The one-line impact is genuinely compelling
- [ ] The designer's specific ownership is clear throughout
- [ ] Internal acronyms and platform names are explained on first use

---

## Seniority Calibration

Adjust emphasis to match the designer's target level:

- **Mid -> Senior**: Emphasize ownership and handling ambiguity. Story: "I moved from executing to leading."
- **Senior -> Staff/Principal**: Emphasize org-level influence and systems thinking. Story: "My work changed how the team works."
- **IC -> Design Leadership**: Emphasize people, process, and vision. Story: "I multiplied the team's output."
