# Introduction to Cognitive Psychology CLQ Grading Specification

Version 1.0 · 10 October 2026

**Assessment:** Units 3–4 Collaborative Learning Question — Change Blindness.

**Status:** Assessment-specific configuration of `GRADING_FEEDBACK_ENGINE_SPEC.md`. The official University of Essex Online Level 4 CLQ rubric and assessment brief remain authoritative.

---

## 1. Source hierarchy

1. Official CLQ / Discussion Forum grading rubric: `ICP 2024 L4 CLQ and Discussion Forum Grading Criteria.pdf`.
2. Assessment brief: `Introduction-to-Cognitive-Psychology/syllabus_materials/syllabus and assessments.md`.
3. Official rubric summary: `Introduction-to-Cognitive-Psychology/syllabus_materials/official grading criteria summary.md`.
4. Diagnostic rubric: `Introduction-to-Cognitive-Psychology/Assessments_Seminars_Guidance/CLQ_Change_Blindness_Criteria_and_Subcriteria.md`.
5. Change-blindness results, reading list and seminar materials.
6. Repository-level grading engine.

If any operational rule conflicts with an official source, the official source wins and the conflict must be flagged.

---

## 2. Official criteria and weights

| Criterion | Weight |
|---|---:|
| Knowledge and Understanding of the Subject Area / Conceptual Issues | **25%** |
| Evaluation and Analytical Skills | **25%** |
| Communication | **25%** |
| Reading & Referencing | **25%** |

Each criterion has exactly four diagnostic subcriteria, equally weighted within the criterion for diagnostic aggregation only.

---

## 3. Agreed diagnostic subcriteria

### C1. Knowledge and Understanding — 25%
- **C1.1** Accurate understanding of the Change Blindness task and phenomenon
- **C1.2** Accurate explanation using attention and awareness
- **C1.3** Integration of Unit 1–4 module knowledge
- **C1.4** Understanding of real-world implications

### C2. Evaluation and Analytical Skills — 25%
- **C2.1** Evidence-based evaluation of explanations
- **C2.2** Comparative use of cognitive approaches
- **C2.3** Consideration of alternatives, limits and inferential strength
- **C2.4** Critical engagement with peers' specific arguments

### C3. Communication — 25%
- **C3.1** Clear and coherent Initial Response
- **C3.2** Peer responses are connected and reflective
- **C3.3** Constructive academic dialogue and leadership
- **C3.4** Precision, structure and audience-appropriate expression

### C4. Reading & Referencing — 25%
- **C4.1** Substantive engagement with core module evidence
- **C4.2** Appropriate breadth and quality of scholarly evidence
- **C4.3** Evidence-to-claim alignment
- **C4.4** Accurate and consistent referencing

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


## Module-reading engagement rule

Strong CLQ work should normally combine:

1. reflective engagement with the student's own Change Blindness task experience;
2. direct change-blindness evidence, especially Rensink et al. (1997);
3. at least one relevant attention/approach source such as Posner (2012), Katsuki & Constantinidis (2014), or Milner & Goodale;
4. appropriate wider evidence where needed.

**Band guidance:**

- **60+** normally requires identifiable use of relevant module scholarship.
- **70+** normally requires integrated use of module theory, empirical evidence and at least two cognitive approaches across the peer responses.
- **80–85** requires unusually strong synthesis, precision and independent judgement for a Level 4 discussion task.

Token citations do not count as substantive reading engagement.

---

## 6. Required components and eligibility

Required assessed responses:

1. Initial Response — **500 words**;
2. Peer Response 1 — **300 words**;
3. Peer Response 2 — **300 words**.

All three are required to pass according to the assessment brief.

Therefore:

- missing Initial Response → hold and flag;
- missing either Peer Response → hold and flag;
- missing both Peer Responses → substantive non-completion;
- inaccessible posts are unresolved until checked.

Informal posts may show animation/leadership, but their content is not itself assessed and cannot replace the three required responses.

---

## 7. Change Blindness evidence check

The supplied class results should be treated accurately:

- N = 70;
- control condition mean RT = 3.65 seconds;
- experimental/full-scene mean RT = 15.68 seconds;
- difference reported as p < .001.

Do not require students to know the mixed-effects model used to generate significance; the source explicitly says they do not need to know it.

Reward students who distinguish:

- observed task result;
- theoretical explanation;
- real-world inference.

---

## 8. Independent criterion and overall marks

```text
X_ic = mean(x_icj)
Q_ic = mean(q_icj)
B_i  = sum_c(w_c * Q_ic)
```

Official weights:

```text
w_C1 = 0.25
w_C2 = 0.25
w_C3 = 0.25
w_C4 = 0.25
```

---

## 9. Cohort calibration

Use the same cohort norming target as the other modules:

```text
target_mean = 65
target_population_sd = 8
```

The desired ordinary range is approximately **45–85**, as a soft descriptive target.

Policy:

- do not force a Gaussian distribution;
- do not manufacture failures or exceptional grades;
- preserve meaningful ties and evidence-based rank order;
- use the common constrained-affine moderation process from the repository engine;
- criterion movement from independent quality is normally limited to ±5 points.

The target mean applies **after academic eligibility checks and before administrative penalties**.

---

## 10. Borderline-fail policy

Pass threshold: 40.

```text
if processed_overall in [38, 39]
and all three assessed responses are present
and no essential criterion is wholly absent
and no unresolved evidence remains:
    academic_overall = 40
    borderline_uplift = true
else:
    retain evidence-based result or hold for review
```

Any processed overall below 38 is held for tutor review and is not finalised automatically.

---

## 11. Exceptional grades

- routine upper bound: **79**
- exceptional range: **80–85**
- operational maximum: **85**

Any 80–85 result requires a written evidence-based rationale.

There is no quota for exceptional marks.

---

## 12. Moderation procedure

1. Score all **16 subcriteria** using 0/0.5/1 without reference to cohort targets.
2. Assign 16 independent subcriterion quality marks.
3. Aggregate to four criterion marks and a weighted overall.
4. Compare the same subcriteria across the cohort.
5. Review all sub-40 evidence, fail candidates, 80+ candidates, missing responses and unresolved evidence.
6. Freeze the evidence matrix.
7. Apply constrained cohort moderation towards mean 65 and population SD 8.
8. Apply eligible 38–39 → 40 rule.
9. Hold remaining fail cases for tutor review.
10. Jointly round displayed criterion marks so they reproduce the final academic overall as closely as feasible.
11. Report achieved mean, SD, minimum, maximum and all activated flags.

---

## 13. Word-count policy

The brief specifies:

- Initial Response: 500 words;
- Peer Response 1: 300 words;
- Peer Response 2: 300 words.

A penalty applies if the authorised word-count limit/range is exceeded by **more than 10%**, reducing the grade by **10 percentage points**.

Potential per-response thresholds are:

- Initial Response: >550 words;
- each Peer Response: >330 words.

However, the supplied brief does not specify whether the penalty is assessed separately by post or collectively across assessed posts.

Therefore:

- verify the authorised institutional counting method before applying a penalty;
- flag ambiguous cases near the threshold;
- do not invent a counting rule;
- apply any confirmed penalty **after academic moderation**;
- do not renormalise afterwards.

No automatic penalty applies for under-length work.

---

## 14. Student-facing feedback format

For each student produce:

- exactly **3 concise strengths**;
- exactly **3 priority areas for improvement**;
- one paragraph for each of the **4 official criteria**;
- the official criterion percentage beside each criterion;
- the overall academic grade;
- the final grade if a word-count penalty changes it;
- a **two-sentence personalised closing observation**.

Do **not** expose:

- 0/0.5/1 diagnostic codes;
- subcriterion quality marks;
- cohort-normalisation calculations;
- internal tutor-review flags.

Use **British English** and address the student directly.

### Required feedback-report order

1. **Overall Grade**
2. **Strengths** — exactly three
3. **Priority Areas for Improvement** — exactly three
4. **Knowledge and Understanding — XX%**
5. **Evaluation and Analytical Skills — XX%**
6. **Communication — XX%**
7. **Reading & Referencing — XX%**
8. **Closing observation** — two sentences

---

## 15. Internal cohort output

Maintain per student:

- 16 competence codes;
- 16 subcriterion quality marks;
- evidence location and rationale for each subcriterion;
- four independent criterion marks;
- independent weighted overall;
- processed criterion marks;
- academic overall;
- borderline-uplift flag;
- missing-component / unresolved flags;
- extreme-fail review flag;
- exceptional-grade rationale;
- verified word-count status/penalty;
- final released grade.

Cohort report:

- N;
- target and achieved mean;
- population SD;
- minimum and maximum;
- band counts;
- borderline uplifts;
- fail cases held for review;
- 80–85 cases and rationale status;
- subcriterion diagnostic distributions;
- subcriterion quality distributions;
- any moderation target made infeasible by evidence constraints.

---

## 16. Configuration

```yaml
engine_spec_version: "1.0"
module_id: "Introduction to Cognitive Psychology"
assessment_id: "CLQ_Change_Blindness"
academic_level: 4
pass_threshold: 40

criteria:
  - id: C1
    title: "Knowledge and Understanding of the Subject Area / Conceptual Issues"
    weight: 0.25
    subcriteria: [C1.1, C1.2, C1.3, C1.4]
  - id: C2
    title: "Evaluation and Analytical Skills"
    weight: 0.25
    subcriteria: [C2.1, C2.2, C2.3, C2.4]
  - id: C3
    title: "Communication"
    weight: 0.25
    subcriteria: [C3.1, C3.2, C3.3, C3.4]
  - id: C4
    title: "Reading & Referencing"
    weight: 0.25
    subcriteria: [C4.1, C4.2, C4.3, C4.4]

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
  requires_complete_submission: true
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

- all three assessed posts are accounted for;
- all 16 subcriteria are scored or unresolved;
- all fail and sub-40 cases are reviewed;
- every 80–85 result has a rationale;
- word-count status is verified;
- criterion marks reproduce the released overall;
- cohort statistics are reported honestly;
- feedback matches the final grade-sheet run.

### Feedback voice and seminar-linking

Student-facing feedback should sound like feedback from the tutor who has taught the module, not a detached rubric summary.

Where it is genuinely relevant to the student's work, make **specific links back to the taught seminars**, for example:

- “As we covered in Seminar 1, …”
- “This connects well with the point we discussed in Seminar 2 about …”
- “For the next assignment, return to the approach we practised in Seminar 3 …”

Rules:

- use the **actual seminar number and topic** supported by the module's seminar materials / `Seminar_Led_Reading_Integration.md`;
- make the seminar reference analytically useful — it should remind the student of a concept, method, reading or activity that helps explain the feedback;
- do not force a seminar reference into every criterion paragraph;
- normally include **at least one useful seminar connection in the overall feedback when an appropriate connection exists**;
- never claim something was taught in a seminar if the source materials do not support that claim.

Use brief, natural encouragement where warranted. Appropriate phrases include:

- “Great job here.”
- “Excellent work.”
- “Nicely done.”
- “This is a real strength.”
- “Good work on this.”
- “You handled this well.”
- “This is developing well.”

Praise must be **evidence-calibrated**:

- reserve “Excellent work” and similarly strong praise for genuinely excellent / First-class evidence;
- use warmer but more measured phrases such as “Nicely done” or “Good work on this” for solid achievement;
- avoid generic praise that is not tied to something the student actually did;
- do not make every paragraph begin or end with praise.

The overall tone should be **warm, encouraging, specific and academically direct**. Areas for improvement should be framed constructively and, where possible, tell the student what to do next rather than merely naming a weakness.
