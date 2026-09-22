# experimental-methods — Repo Plan

## What this is

A GitHub repo for working through **GU6008: Experimental Methods for Social Research**
(James Y. Chu, Columbia, Spring 2024 syllabus: https://jchu1225.github.io/courses/gu6008/),
adapted into a self-study, ARENA-style course repo.

Repo: https://github.com/EmilioBarkett/experimental-methods

**Dual purpose:**
1. A working space for Emilio to go through the course material himself.
2. Structured so other people can fork it and work through experimental methods
   on their own, independent of the original class.

## Source material

- Course covers: randomization, control, causal effects; experimental design theory;
  validity (internal/external/construct/statistical conclusion); building toward a
  final experiment proposal (TESS or OSF format).
- Original syllabus is split into two parts:
  - **Part I: Understanding Experiments** — weeks 1–5
  - **Part II: Designing Experiments** — weeks 6–14 (week 8 is spring break; weeks
    12–13 are student presentations)
- Assessment in the original course: short writing assignments (30%), analysis paper
  (10%), experiment proposal (40%), participation (20%).

## Repo structure (decided)

Organized by the syllabus's two parts, with weeks nested inside — not a flat
`week-01`...`week-14` list at the top level.

```
experimental-methods/
├── README.md                          # course overview, how to use/fork this repo
├── part-1-understanding-experiments/
│   ├── week-01/
│   │   ├── notes.md                   # concepts + reading list for the week
│   │   ├── exercises/                 # hands-on exercises (R and/or Python)
│   │   └── solutions/                 # created, likely empty for now — see below
│   ├── week-02/
│   ├── week-03/
│   ├── week-04/
│   └── week-05/
├── part-2-designing-experiments/
│   ├── week-06/
│   ├── week-07/
│   ├── (week-08 skipped — spring break)
│   ├── week-09/
│   ├── week-10/
│   ├── week-11/
│   ├── week-12/                       # presentations
│   ├── week-13/                       # presentations
│   └── week-14/
└── assignments/
    ├── short-writing/                 # blank fillable templates
    ├── analysis-paper/
    └── experiment-proposal/
```

## Content per week (decided)

Each week folder gets:
- **`notes.md`** — key concepts for the week, plus the reading list (citations +
  links where available, matching the syllabus).
- **`exercises/`** — hands-on exercises to work through (e.g. power analysis,
  randomization checks, designing a mock RCT). Not every week necessarily needs
  code — some weeks may be discussion/design-only.
- **`solutions/`** — folder created for consistency, but we're not populating it
  yet. Decide later whether solutions live here, in a separate branch, or behind
  a collapsible block in the exercise file itself.

## Exercise language (decided)

**Both R and Python** — pick whichever fits a given exercise best. Power analysis
and randomization inference work naturally in either; some causal inference
tooling leans R, some ML-adjacent tooling leans Python. No single required
language across the whole repo.

## Assignment templates (decided)

Yes — include the real course deliverables as **blank, fillable templates** so
forkers can use them too:
- Short writing assignments (experiment summary, abstract, outline,
  mediator/moderator section, threat analysis, ethics memo)
- Analysis paper
- Experiment proposal (TESS/OSF format)

## Open questions (not yet decided)

1. **Solutions pattern** — separate folder (created, currently placeholder) vs.
   git branch vs. inline collapsible markdown. Revisit once exercises exist.
2. **README contents** — needs a clear "how to use this if you forked it" section,
   distinct from Emilio's own personal-use notes.
3. **Licensing** — if this is meant to be forked and reused publicly, worth
   picking a license (e.g. MIT for code/exercises, CC-BY for notes/text).
4. **Copyright on readings** — the original syllabus links to paywalled/CW
   (Coursework-only) readings. The repo should link out to sources rather than
   redistribute copyrighted PDFs directly.
5. **Naming conventions** — confirm `week-01` vs `week1` vs `01-week-one` style
   before scaffolding folders, for consistency across the whole repo.

## Workflow

Emilio is cloning the repo into VS Code and working there directly. Claude is
not writing into the repo — this file is a planning summary to paste in and
work from.
