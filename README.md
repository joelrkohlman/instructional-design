# instructional-design

A Claude skill for instructional designers and L&D practitioners.

## What this is

This skill gives Claude working knowledge of the full ID process — from deciding whether training is the right solution to publishing a SCORM package to your LMS. It covers real practice, not just theory: the kind of work a solo ID is expected to own end-to-end.

Articulate Storyline 360 and Rise 360 guidance is integrated throughout, not isolated in a separate tools section.

## Skill structure

```
instructional-design/
├── SKILL.md       # The skill — add this to Claude
├── README.md
└── LICENSE
```

## Quick start

**Custom instructions or system prompt:**

1. Open `SKILL.md` and copy the contents
2. Paste into your LLM's custom instructions or system prompt field
3. Claude will apply it automatically when you ask ID-related questions

Works with Claude (web, desktop, API), and any LLM that accepts system prompts.

## What it covers

Ten sections, each grounded in how ID work actually runs:

1. **Problem framing** — Is training the right solution? Do this before writing a single objective.
2. **Course design methodology** — ADDIE, SAM, Learning Experience Design (LXD)
3. **Learning objectives** — Bloom's Taxonomy with verb table, ABCD format, alignment rules
4. **Learner engagement** — Branching scenarios, hotspots, lightboxes, design for low-motivation audiences
5. **Assessment design** — Formative vs. summative, distractors, scenario-based questions
6. **Content sequencing** — Cognitive load, chunking, scenario-first structuring, storyboarding
7. **SME and stakeholder workflow** — Interview guides, feedback management, sign-off checkpoints
8. **LMS and SCORM/xAPI publishing** — SCORM 1.2 vs. 2004 vs. xAPI vs. cmi5, Articulate publishing, SCORM Cloud testing
9. **Measurement and evaluation** — Kirkpatrick four levels, evaluation plan structure
10. **Rapid development realities** — Fidelity tradeoffs, scope decisions under pressure, minimum viable course checklist

## Example

**Prompt:**
> I need to build a compliance training course on data privacy for new employees. About 200 new hires a year, spread across departments, and most of them are going to treat this as a checkbox. Our LMS is Docebo. Where do I start?

**Response (with skill):**

Before opening any authoring tool, you need to answer three questions:

- What specifically do employees need to be able to *do*? Not "understand data privacy" — think in terms of decisions they will actually face on the job.
- What does getting it wrong look like? Ask your compliance team what mistakes actually happen. Those are your scenarios.
- What is the risk if someone gets it wrong? This determines how much fidelity the course needs.

Here is a starter needs analysis based on what you described:

```
Project: Data Privacy Compliance — New Employee Onboarding

Performance gap: New employees are not consistently applying data privacy
practices from day one.

Root cause: Knowledge gap. Employees do not yet know what the policy requires
or how it applies to their role.

Training recommended: Yes — but training alone will not prevent all incidents.
Clear policies, accessible job aids, and manager reinforcement matter too.

Motivation level: Low. Engagement must be designed in.

Success looks like: Employees can identify personal data, make correct handling
decisions, and know how to report a suspected breach. At 90 days, fewer
privacy-related incidents from new hires than baseline.

LMS: Docebo — supports SCORM 1.2, SCORM 2004, and xAPI with a built-in LRS.
```

From here, the skill walks through scope decisions, learning objectives at the Apply and Analyze levels of Bloom's, design strategies for checkbox audiences (open with a scenario, not objectives), authoring tool selection for Docebo, SCORM vs. xAPI tradeoffs, and a pre-launch SCORM Cloud testing step.

## License

MIT. Use freely, share widely.

## Author

[Joel Kohlman](https://joelrkohlman.com) — instructional designer and e-learning developer.
