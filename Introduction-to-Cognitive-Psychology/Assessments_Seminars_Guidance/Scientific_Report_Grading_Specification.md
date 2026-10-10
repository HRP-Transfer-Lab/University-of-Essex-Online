# Introduction to Cognitive Psychology Scientific Report Grading Specification

Version 1.0 · 10 October 2026

**Assessment:** Unit 9 Scientific Report based on the Misinformation Effect or Emotional Stroop experiment.

**Status:** Assessment-specific configuration of `GRADING_FEEDBACK_ENGINE_SPEC.md`. The official University of Essex Online Level 4 Assignment rubric and assessment brief remain authoritative.

---

## 1. Source hierarchy

1. Official Assignment grading rubric: `ICP 2024 L4 Assignment Grading Criteria.pdf`.
2. Assessment brief: `Introduction-to-Cognitive-Psychology/syllabus_materials/syllabus and assessments.md`.
3. Official rubric summary: `Introduction-to-Cognitive-Psychology/syllabus_materials/official grading criteria summary.md`.
4. Diagnostic rubric: `Introduction-to-Cognitive-Psychology/Assessments_Seminars_Guidance/Scientific_Report_Criteria_and_Subcriteria.md`.
5. Supplied experiment results, reading list, formative task and seminar materials.
6. Repository-level grading engine.

The official rubric and brief take precedence in any conflict.

---

## 2. Official criteria and weights

| Criterion | Weight |
|---|---:|
| Knowledge and Understanding of the Subject Area / Conceptual Issues | **20%** |
| Application of Theory to Practice and/or Real-world Example | **20%** |
| Evaluation and Analytical Skills | **20%** |
| Reading and Referencing | **20%** |
| Presentation Style and Structure | **20%** |

Each criterion has exactly four diagnostic subcriteria, equally weighted within the criterion for diagnostic aggregation only.

---

## 3. Agreed diagnostic subcriteria

### C1. Knowledge and Understanding — 20%
- **C1.1** Understanding of the experiment's purpose and cognitive phenomenon
- **C1.2** Understanding of relevant cognitive theories
- **C1.3** Understanding of design, variables and procedure
- **C1.4** Understanding of broader context, ethics and implications

### C2. Application of Theory — 20%
- **C2.1** Theory is applied to the rationale and hypothesis
- **C2.2** Theory is applied to interpretation of the class results
- **C2.3** Research evidence is applied to the specific experiment
- **C2.4** Real-world application is justified and proportionate

### C3. Evaluation and Analytical Skills — 20%
- **C3.1** Testable hypothesis and alignment with the research question
- **C3.2** Accurate and evidence-based interpretation of results
- **C3.3** Critical evaluation of study design and evidence
- **C3.4** Integration, judgement and alternative interpretation

### C4. Reading and Referencing — 20%
- **C4.1** Structured literature searching and source selection
- **C4.2** Breadth, quality and relevance of research literature
- **C4.3** Meaningful use of sources in design, hypothesis and discussion
- **C4.4** Evidence-to-claim alignment and referencing accuracy

### C5. Presentation Style and Structure — 20%
- **C5.1** Complete and appropriate scientific-report structure
- **C5.2** Scientific-writing conventions and section discipline
- **C5.3** Clarity, coherence and precision
- **C5.4** APA-style presentation and technical completeness

---

## Competence coding

Score every subcriterion independently before cohort moderation.

| Code | Meaning |
|---:|---|
| **0** | Not demonstrated, fundamentally incorrect, irrelevant, or absent where required |
| **0.5** | Partly demonstrated but materially incomplete, inaccurate, weakly justified or uneven |
| **1** | Adequately and substantively demonstrated at Level 4; minor weaknesses may remain |

Each code must have a concise evidence note and location.

The competence codes are diagnostic and are **not** converted mechanically into percentage marks.

## Independent subcriterion quality marks

Assign a separate quality mark to each subcriterion after the competence judgement.

### Normal operating range

Subcriterion quality marks should normally fall between **45 and 85**.

| Quality mark | Interpretation |
|---:|---|
| **80–85** | Rare exceptional Level 4 performance; unusually strong accuracy, integration, judgement or communication |
| **70–79** | Strong First-class performance; developed, analytical and well supported |
| **60–69** | Good 2:1 performance; competent and developed with identifiable limitations |
| **50–59** | Adequate 2:2 performance; relevant but limited, uneven or too descriptive |
| **45–49** | Weak but meaningful evidence; substantial limitations |
| **40–44** | Borderline / marginal evidence; substantive weaknesses requiring review |
| **Below 40** | Dramatically weak, absent or seriously flawed performance; mandatory tutor-review flag |

Relationship to diagnostic code:

- **1:** normally supports approximately 55–85;
- **0.5:** normally supports approximately 45–59; 60+ requires a clear rationale;
- **0:** normally supports 0–44 depending on residual evidence; wholly absent work should normally receive 0.

Do not manufacture a 45 minimum where the evidence is genuinely weaker.

### Mandatory tutor-review flags

Flag where:

- any subcriterion mark is below 40;
- any official criterion mark is below 40;
- the independent or processed overall is below 40;
- multiple zeros occur within one official criterion;
- required assessment components are missing;
- evidence is inaccessible or unresolved;
- an overall of 80–85 is proposed.


## 6. Experiment-specific evidence rules

### Misinformation Effect

The supplied class dataset reports no significant condition effects on the listed outcomes.

Marking must therefore reward accurate handling of a **null class result**.

Do not reward claims that:

- the expected wording effect was demonstrated when it was not;
- a non-significant result proves that wording never affects memory.

Strong discussion should compare the null class result with prior misinformation research and consider plausible methodological/theoretical explanations.

### Emotional Stroop

The supplied class dataset reports:

- Neutral mean = 485 ms;
- Positive mean = 450 ms;
- Negative mean = 472 ms;
- significant overall condition effect, p = .002;
- significant Neutral–Positive comparison;
- significant Negative–Positive comparison;
- no significant Neutral–Negative comparison.

Do not reward a generic “negative emotion slowed responses” account unless the student reconciles it with the actual pattern.

---

## 7. Literature-review integration rule

The Unit 7 formative review is optional, so non-completion must **not** itself be penalised.

However, the final report is required to demonstrate the skills the formative activity practises:

- locating relevant academic evidence;
- constructing a focused rationale;
- integrating seminal and recent work;
- using literature to support the hypothesis and Discussion.

Where the student completed the formative work, it may be incorporated into the final report.

---

## 8. Report-section expectations

### Abstract
Concise and accurate summary of rationale, method, key findings and conclusion.

### Literature Review
Should progress from background and prior evidence to theory, rationale and a testable hypothesis.

### Method
Should report Participants, Design, Materials, Procedure and Ethics with sufficient clarity to understand/replicate the study.

### Results
Should accurately present the class data supplied by the tutor without introducing unsupported analyses.

### Discussion
Should:

- summarise the result;
- compare it with prior research;
- interpret theoretically;
- evaluate the study;
- discuss justified applications/implications;
- identify future directions;
- conclude coherently.

---

## 9. Cohort calibration

Use the same class-average norming target as the other modules:

```text
target_mean = 65
target_population_sd = 8
```

Soft ordinary range: approximately **45–85**.

Do not:

- force a Gaussian distribution;
- manufacture failures;
- manufacture exceptional marks;
- hide genuine weak evidence through moderation.

Use the repository-level constrained common-affine process. Criterion shifts from independent quality are normally limited to ±5 points.

---

## 10. Borderline-fail policy

Pass threshold: 40.

```text
if processed_overall in [38, 39]
and the report is substantively complete
and no essential criterion is wholly absent
and no unresolved evidence remains:
    academic_overall = 40
    borderline_uplift = true
else:
    retain result or hold for review
```

Processed overall below 38 is held for tutor review.

A materially absent required section should block automatic borderline uplift.

---

## 11. Exceptional grades

- routine upper bound: **79**
- exceptional range: **80–85**
- operational maximum: **85**

80–85 requires a written rationale demonstrating unusually strong Level 4 performance across knowledge, application, analysis, scholarship and scientific communication.

---

## 12. Moderation procedure

1. Score all **20 subcriteria** using 0/0.5/1.
2. Assign 20 independent quality marks.
3. Aggregate to five criterion marks and an independent weighted overall.
4. Conduct cross-cohort comparisons on the same subcriteria.
5. Review sub-40 evidence, fail candidates, 80+ candidates, missing sections and unresolved evidence.
6. Freeze evidence-based marks.
7. Apply constrained moderation towards mean 65 and population SD 8.
8. Apply eligible 38–39 → 40 rule.
9. Hold remaining fail cases for tutor review.
10. Jointly round criterion marks so displayed weighted criteria reproduce the academic overall as closely as feasible.
11. Report achieved mean, SD, minimum, maximum and activated flags.

---

## 13. Word-count policy

Official overall word count: **2,500 words**.

The brief states that exceeding the applicable word-count limit/range by **more than 10%** causes a **10 percentage-point deduction**.

A nominal 10%-over threshold would therefore be:

```text
2750 words
```

However, the supplied report structure gives suggested counts for Abstract, Literature Review, Method and Discussion while the Results section is supplied separately and no explicit counting rule is given here for every element.

Therefore:

- use the authorised institutional word-count rules;
- verify what is included/excluded before applying a penalty;
- if the verified assessed count is subject to a 2,500-word limit, the trigger is strictly **greater than 2,750**;
- flag ambiguous cases rather than inventing an inclusion rule;
- apply the penalty after academic moderation;
- do not renormalise afterwards;
- a penalty-induced fail is not automatically uplifted to 40.

No automatic deduction applies for under-length work.

---

## 14. Student-facing feedback format

For each student produce:

- exactly **3 concise strengths**;
- exactly **3 priority areas for improvement**;
- one paragraph for each of the **5 official criteria**;
- the official criterion percentage beside each criterion;
- the overall academic grade;
- final grade if a penalty changes it;
- a **two-sentence personalised closing observation**.

### Feedback voice and seminar-linking

Student-facing feedback should sound like feedback from the tutor who has taught the module, not a detached rubric summary.

Where it is genuinely relevant to the student's work, make specific links back to taught seminars, for example:

- “As we covered in Seminar 1, …”
- “This connects well with the point we discussed in Seminar 2 about …”
- “For the next assignment, return to the approach we practised in Seminar 3 …”

Use the actual seminar number and topic supported by the module's seminar materials and `Seminar_Led_Reading_Integration.md`. Do not force a seminar reference into every criterion paragraph, but normally include at least one useful seminar connection in the overall feedback when an appropriate connection exists.

Use brief, natural encouragement where warranted, such as “Great job here”, “Nicely done”, “Good work on this”, “This is a real strength”, “You handled this well”, or “Excellent work”. Strong praise such as “Excellent work” should be reserved for genuinely excellent evidence. Praise should be specific rather than generic.

The overall tone should be warm, encouraging, specific and academically direct. Areas for improvement should tell the student what to do next where possible.

### Required wording conventions in student feedback

These are hard style rules for all student-facing feedback:

- **Never use “scholarly”.** Use **“academic”**, **“high-quality academic”**, **“research literature”**, or **“high-quality sources”** as appropriate.
- Use natural contractions in feedback: **“don't”, “won't”, “can't”, “isn't”, “doesn't”, “you've”, “you're”** rather than unnecessarily formal **“do not”, “will not”, “cannot”, “is not”, “does not”, “you have”, “you are”**. Keep the tone professional, but conversational.
- **Never use “designated textbook”.** Refer to it as the **“module textbook”**.
- These wording rules apply to headings, criterion paragraphs, strengths, improvement points and the closing observation.


Do not show:

- diagnostic codes;
- subcriterion marks;
- cohort-moderation calculations;
- internal tutor-review flags.

Use British English and address the student directly.

### Required feedback-report order

1. **Overall Grade**
2. **Strengths** — exactly three
3. **Priority Areas for Improvement** — exactly three
4. **Knowledge and Understanding — XX%**
5. **Application of Theory to Practice / Real-world Example — XX%**
6. **Evaluation and Analytical Skills — XX%**
7. **Reading and Referencing — XX%**
8. **Presentation Style and Structure — XX%**
9. **Closing observation** — two sentences

---

## 15. Internal cohort output

Maintain:

- 20 competence codes per student;
- 20 quality marks per student;
- evidence location and rationale for every subcriterion;
- five independent criterion marks;
- independent weighted overall;
- processed criterion marks;
- academic overall;
- borderline flag;
- missing-section / unresolved flags;
- experiment option;
- result-accuracy flag;
- exceptional-grade rationale;
- word-count status and penalty;
- final released grade.

Cohort report:

- N;
- target and achieved mean;
- population SD;
- minimum and maximum;
- grade-band counts;
- borderline uplifts;
- tutor-review fail cases;
- 80–85 cases and rationale status;
- diagnostic distributions;
- quality-mark distributions;
- moderation constraints;
- counts by experiment option for audit only, not separate norming unless explicitly requested.

---

## 16. Configuration

```yaml
engine_spec_version: "1.0"
module_id: "Introduction to Cognitive Psychology"
assessment_id: "Scientific_Report"
academic_level: 4
pass_threshold: 40
official_word_limit: 2500

criteria:
  - id: C1
    title: "Knowledge and Understanding of the Subject Area / Conceptual Issues"
    weight: 0.20
    subcriteria: [C1.1, C1.2, C1.3, C1.4]
  - id: C2
    title: "Application of Theory to Practice and/or Real-world Example"
    weight: 0.20
    subcriteria: [C2.1, C2.2, C2.3, C2.4]
  - id: C3
    title: "Evaluation and Analytical Skills"
    weight: 0.20
    subcriteria: [C3.1, C3.2, C3.3, C3.4]
  - id: C4
    title: "Reading and Referencing"
    weight: 0.20
    subcriteria: [C4.1, C4.2, C4.3, C4.4]
  - id: C5
    title: "Presentation Style and Structure"
    weight: 0.20
    subcriteria: [C5.1, C5.2, C5.3, C5.4]

competence_codes: [0, 0.5, 1]
within_criterion_weights: equal

moderation:
  target_mean: 65
  target_population_sd: 8
  mode: constrained_common_affine
  max_criterion_shift_points: 5
  force_gaussian_shape: false

quality:
  normal_subcriterion_range: [45, 85]
  ordinary_maximum: 79
  exceptional_maximum: 85
  exceptional_rationale_required_from: 80

borderline:
  uplift_scores: [38, 39]
  uplift_to: 40
  requires_substantively_complete_report: true
  unresolved_blocks_uplift: true

feedback:
  strengths: 3
  areas_for_improvement: 3
  paragraphs_per_main_criterion: 1
  visible_criteria: main_only
  personal_closing_sentences: 2
  language: en-GB
```

---

## 17. Release gates

No grade is released until:

- the full report is accounted for and readable;
- all 20 subcriteria are scored or unresolved;
- supplied class results have been represented accurately;
- every sub-40 case has been checked;
- every fail case has been reviewed;
- every 80–85 result has a rationale;
- word-count status is verified;
- displayed criterion marks reproduce the released overall;
- cohort statistics are reported honestly;
- feedback matches the final grade-sheet run.
