# Module Setup and Assessment Workflow

Use this checklist whenever a new University of Essex Online module is added to the repository.

The purpose is to create a reproducible sequence from **raw module materials → organised syllabus/readings → seminar-linked scholarship → assessment subcriteria → grading specifications → marking-ready module**.

Seminar redesign is intentionally treated as a **later phase**. At this stage, seminars are reviewed only enough to identify where core readings can be anchored and how those readings should feed into assessment criteria.

---

# Phase 1 — Create the module structure

- [ ] Create a top-level folder for the module.
- [ ] Create a `syllabus_materials/` folder.
- [ ] Create an `Assessments_Seminars_Guidance/` folder.
- [ ] Add a short `README.md` to each folder explaining its purpose.
- [ ] Confirm the repository branch and intended working location.

Suggested structure:

```text
Module-Name/
├── syllabus_materials/
│   ├── README.md
│   ├── syllabus and assessments.md
│   ├── reading list.md
│   ├── official grading rubrics.pdf
│   └── seminar/workshop source files.pdf
│
└── Assessments_Seminars_Guidance/
    ├── README.md
    ├── Seminar_Led_Reading_Integration.md
    ├── [Assessment]_Criteria_and_Subcriteria.md
    └── [Assessment]_Grading_Specification.md
```

---

# Phase 2 — Upload and organise official module content

- [ ] Upload the official module homepage / syllabus material.
- [ ] Upload all assessment briefs and submission instructions.
- [ ] Upload all official assessment grading rubrics.
- [ ] Upload all seminar/workshop outlines or slides.
- [ ] Upload any formative assessment instructions.
- [ ] Upload any official reading-list source material.
- [ ] Keep original PDFs/slides unchanged as source documents.

Create or update:

- [ ] `syllabus and assessments.md`

This file should contain, where available:

- [ ] module overview;
- [ ] module aims;
- [ ] learning outcomes;
- [ ] weekly/unit topics;
- [ ] formative assessments;
- [ ] summative assessment briefs;
- [ ] submission rules;
- [ ] word limits;
- [ ] penalties;
- [ ] academic integrity requirements.

Do not silently change official requirements.

---

# Phase 3 — Build the reading list

Create:

- [ ] `reading list.md`

For each unit:

- [ ] add required textbook chapters;
- [ ] add required journal articles;
- [ ] add additional readings;
- [ ] add recommended activities/resources;
- [ ] add stable links where possible;
- [ ] prefer DOI, publisher, PubMed/PMC, institutional repository, NICE, WHO, BPS or equivalent authoritative links;
- [ ] note bibliographic discrepancies rather than silently correcting them;
- [ ] distinguish full-text links from catalogue/publisher records.

For the module as a whole:

- [ ] identify the core textbook(s);
- [ ] verify editions and publication details;
- [ ] identify seminal theory papers;
- [ ] identify current/recent empirical papers;
- [ ] identify applied/professional guidance where relevant.

---

# Phase 4 — Review seminars and assign anchor readings

Do **not** redesign the seminars yet.

At this stage:

- [ ] review each seminar/workshop outline;
- [ ] identify its main conceptual focus;
- [ ] identify the assessment(s) it prepares students for;
- [ ] assign **one core reading** to each seminar;
- [ ] optionally assign **one supplementary reading** where it adds a genuinely different perspective;
- [ ] prefer readings already on the official module reading list where possible;
- [ ] add an external reading only where it materially improves alignment and is appropriate for the module level;
- [ ] summarise what each reading contributes intellectually;
- [ ] note one possible seminar activity that could use the reading later.

Create:

- [ ] `Assessments_Seminars_Guidance/Seminar_Led_Reading_Integration.md`

For each seminar record:

- [ ] seminar title/topic;
- [ ] core reading;
- [ ] supplementary reading if useful;
- [ ] key concepts/findings;
- [ ] methodological or theoretical limitations worth discussing;
- [ ] potential application task;
- [ ] assessment subcriteria supported.

Use the design principle:

> **read → use in seminar → apply/evaluate in assessment**

---

# Phase 5 — Extract the official grading criteria

For each summative assessment:

- [ ] read the official assessment-specific rubric;
- [ ] record the exact official criterion titles;
- [ ] record the exact official criterion weights;
- [ ] record the academic level;
- [ ] record the pass threshold;
- [ ] record assessment-specific format requirements;
- [ ] record word-count rules;
- [ ] record required components;
- [ ] identify any mandatory collaborative or practical elements.

Do not replace the official rubric with a custom rubric.

The custom work must sit **underneath** the official criteria.

---

# Phase 6 — Generate four diagnostic subcriteria per official criterion

Create:

- [ ] `[Assessment]_Criteria_and_Subcriteria.md`

For every official main criterion:

- [ ] create exactly **four diagnostic subcriteria** unless the assessment clearly requires otherwise;
- [ ] make each subcriterion assess a distinct competence;
- [ ] avoid overlap between criteria;
- [ ] avoid rewarding the same weakness/strength twice;
- [ ] keep the official weighting unchanged.

Use diagnostic scores:

- [ ] **0** = absent, seriously incorrect, irrelevant or not demonstrated;
- [ ] **0.5** = partially/unevenly demonstrated;
- [ ] **1** = adequately and substantively demonstrated.

Important:

- [ ] diagnostic scores are **not** direct percentage marks;
- [ ] use them as structured evidence for the official criterion judgement.

---

# Phase 7 — Tie seminar-led readings into the assessment subcriteria

For each assessment:

- [ ] identify which seminar-led readings are directly relevant;
- [ ] integrate them into the wording of relevant subcriteria;
- [ ] link theory-specific readings to theory criteria;
- [ ] link empirical seminar readings to evidence/critical-analysis criteria;
- [ ] link applied readings to intervention/application criteria.

Do **not** require a mechanical citation count.

Instead, define **substantive engagement**.

Substantive engagement includes:

- [ ] accurately explaining a source's theory or finding;
- [ ] applying it to the assessment topic;
- [ ] comparing it with another source;
- [ ] evaluating its methodology or limitations;
- [ ] using it to justify an intervention/message;
- [ ] using it to challenge an intervention/message;
- [ ] transferring a seminar example to a new problem.

The following should **not** count as substantive engagement:

- [ ] source appears only in the reference list;
- [ ] token parenthetical citation;
- [ ] generic paraphrase with no application;
- [ ] citation does not support the claim;
- [ ] theory is named without engaging with its constructs;
- [ ] abstract/slide wording is reproduced without analysis.

Recommended band expectation:

- [ ] **60+** normally requires identifiable engagement with relevant seminar/module scholarship;
- [ ] **70+** normally requires integration of seminar/module readings with wider independent scholarship;
- [ ] **80–85** requires unusually strong synthesis, evaluation and independent judgement.

---

# Phase 8 — Add assessment-specific formal requirements

For each assessment:

- [ ] identify all required components;
- [ ] identify formatting rules;
- [ ] identify submission rules;
- [ ] identify presentation requirements;
- [ ] identify anonymity/blind-marking requirements;
- [ ] identify whether visuals/posters/slides need legibility checks;
- [ ] distinguish official rules from internal marking guidance.

Where an official source does not specify a technical detail:

- [ ] label any internal benchmark clearly as **recommended guidance**, not University policy.

Examples:

- [ ] font size guidance;
- [ ] poster text density;
- [ ] visual hierarchy;
- [ ] section-balance expectations;
- [ ] accessibility/legibility checks.

---

# Phase 9 — Create the assessment-specific grading specification

Create:

- [ ] `[Assessment]_Grading_Specification.md`

Base it on:

- [ ] `GRADING_FEEDBACK_ENGINE_SPEC.md`
- [ ] the official rubric;
- [ ] the assessment brief;
- [ ] the agreed subcriteria;
- [ ] the seminar-led reading integration;
- [ ] tutor-set cohort calibration rules.

Include:

- [ ] official criteria and weights;
- [ ] all four subcriteria per criterion;
- [ ] 0 / 0.5 / 1 diagnostic rules;
- [ ] independent subcriterion quality marks;
- [ ] normal subcriterion quality range;
- [ ] exceptional-grade policy;
- [ ] fail-review policy;
- [ ] missing-component policy;
- [ ] cohort target mean;
- [ ] cohort spread target;
- [ ] moderation bounds;
- [ ] word-count penalty rules;
- [ ] rounding rules;
- [ ] feedback format;
- [ ] release gates.

---

# Phase 10 — Set cohort calibration parameters

For each assessment, explicitly set:

- [ ] target cohort mean;
- [ ] target population SD or mean-only mode;
- [ ] typical expected overall range;
- [ ] typical expected subcriterion range;
- [ ] ordinary maximum;
- [ ] exceptional maximum;
- [ ] borderline-fail convention;
- [ ] extreme-fail review rule.

Example tutor configuration:

```text
target mean: 65
soft population SD: 8
typical subcriterion range: 45–85
ordinary maximum: 79
exceptional maximum: 85
38–39 borderline cases: may be lifted to 40 if substantively eligible
below 38: hold and flag for tutor review
```

Important:

- [ ] do not manufacture the requested distribution;
- [ ] do not create failures to satisfy a histogram;
- [ ] do not create 80+ grades without exceptional evidence;
- [ ] preserve meaningful ties;
- [ ] keep academic judgement separate from moderation.

---

# Phase 11 — Define quality anchors

For each subcriterion:

- [ ] assign 0 / 0.5 / 1 competence independently;
- [ ] assign a separate quality mark;
- [ ] normally keep quality marks within the agreed operating range;
- [ ] permit lower values for genuinely poor or missing work;
- [ ] flag extreme values for tutor review.

Typical interpretation:

- [ ] **80–85** = rare exceptional performance;
- [ ] **70–79** = strong first-class performance;
- [ ] **60–69** = good 2:1 performance;
- [ ] **50–59** = adequate 2:2 performance;
- [ ] **45–49** = weak but meaningful performance;
- [ ] **40–44** = borderline performance;
- [ ] **below 40** = dramatic weakness / mandatory review.

---

# Phase 12 — Define assessment completeness and fail rules

For each assessment:

- [ ] identify components required to pass;
- [ ] identify components that can be weak without causing automatic failure;
- [ ] distinguish missing evidence from inaccessible evidence;
- [ ] treat unreadable/inaccessible evidence as unresolved, not automatically zero;
- [ ] specify when a borderline uplift is allowed;
- [ ] specify when a result must be held for tutor review.

For collaborative assessments:

- [ ] check all required posts/responses are present.

For essays/reports:

- [ ] check all required substantive parts of the question are materially represented.

---

# Phase 13 — Define word-count handling

For each assessment:

- [ ] record the official word limit/range;
- [ ] record the exact >10% rule if applicable;
- [ ] calculate the numerical threshold;
- [ ] apply a 10 percentage-point deduction only when authorised;
- [ ] do not renormalise after penalties;
- [ ] do not invent under-length deductions;
- [ ] verify institutional inclusion/exclusion rules before applying a penalty.

---

# Phase 14 — Define feedback output

For each assessment:

- [ ] exactly three strengths;
- [ ] exactly three priority areas for improvement;
- [ ] one paragraph per official main criterion;
- [ ] criterion percentages visible;
- [ ] subcriterion diagnostics hidden from students;
- [ ] overall grade shown clearly;
- [ ] penalties shown separately where applicable;
- [ ] two-sentence personalised closing observation;
- [ ] British English;
- [ ] direct second-person feedback;
- [ ] no invented seminar references;
- [ ] no claims of originality without evidence.

---

# Phase 15 — Marking workflow

When submissions arrive:

- [ ] pin the source repository commit;
- [ ] inventory all submissions;
- [ ] verify the correct version for each student;
- [ ] identify missing/unreadable files;
- [ ] exclude rubric/instruction/feedback files from the student count;
- [ ] inspect all assessment components;
- [ ] score all subcriteria independently;
- [ ] record evidence locations;
- [ ] assign quality marks independently of the target distribution;
- [ ] complete a cross-cohort calibration pass;
- [ ] review all low/extreme/high cases;
- [ ] freeze evidence-based marks before numerical moderation;
- [ ] apply constrained cohort moderation;
- [ ] apply authorised borderline rules;
- [ ] apply authorised administrative penalties;
- [ ] verify final arithmetic;
- [ ] generate feedback;
- [ ] hold flagged cases for tutor review.

---

# Phase 16 — Release checks

Before releasing any grades:

- [ ] every student accounted for;
- [ ] every required component accounted for;
- [ ] all subcriteria scored or explicitly unresolved;
- [ ] all sub-40 subcriteria reviewed;
- [ ] all fail candidates reviewed;
- [ ] all extreme fails approved by tutor;
- [ ] all 80–85 grades have written rationale;
- [ ] word-count penalties independently verified;
- [ ] criterion marks reproduce the overall;
- [ ] cohort mean and SD reported honestly;
- [ ] minimum/maximum reported;
- [ ] all feedback files match the final grade sheet;
- [ ] identifiable student data stored only in an appropriate restricted location.

---

# Phase 17 — Seminar redesign (later phase)

Only after the module-reading and grading architecture is complete:

- [ ] redesign seminar activities around the assigned anchor readings;
- [ ] create worked examples;
- [ ] add structured reading questions;
- [ ] add small-group application tasks;
- [ ] add critical-evaluation prompts;
- [ ] model strong versus weak use of evidence;
- [ ] explicitly practise assessment subcriteria;
- [ ] add seminar-to-assessment signposting;
- [ ] revise slides where needed;
- [ ] preserve official module learning outcomes;
- [ ] avoid teaching hidden assessment requirements.

The seminar redesign should operationalise what is already specified in:

- [ ] `Seminar_Led_Reading_Integration.md`
- [ ] assessment subcriteria files;
- [ ] assessment grading specifications.

---

# Phase 18 — Version and freeze

Before marking begins:

- [ ] confirm the official source versions;
- [ ] confirm the final seminar-reading map;
- [ ] confirm the final subcriteria;
- [ ] confirm the target mean/spread;
- [ ] confirm fail/borderline rules;
- [ ] confirm word-count rules;
- [ ] confirm feedback format;
- [ ] commit all grading specifications;
- [ ] record the repository commit used for marking;
- [ ] do not change the rubric mid-cohort without a documented new grading run.

---

# Minimum deliverables for a marking-ready module

A module is ready for marking when it has:

- [ ] official source materials uploaded;
- [ ] `syllabus and assessments.md`;
- [ ] `reading list.md`;
- [ ] seminar/workshop source files;
- [ ] `Seminar_Led_Reading_Integration.md`;
- [ ] one `Criteria_and_Subcriteria.md` file per assessment;
- [ ] one `Grading_Specification.md` file per assessment;
- [ ] agreed cohort calibration settings;
- [ ] explicit module-reading engagement rules;
- [ ] defined fail/borderline/exceptional rules;
- [ ] defined word-count and feedback rules;
- [ ] source hierarchy and release checks documented.

Once these are complete, seminar redesign and then cohort marking can proceed.
