# ICCS372 Software Engineering — Course Grade Calculation

Your final course grade is calculated by converting each grading category into its assigned weight and then adding the weighted category scores together.

Do **not** directly average the percentages shown for individual Google Classroom assignments. Different assignments belong to different categories, and each category contributes a different amount to the final course grade.

---

## Why the Grading Structure Changed

The course was originally planned as:

| Original assessment area | Weight |
|---|---:|
| Team project work | 45% |
| Individual work | 25% |
| Final examination | 30% |
| **Total** | **100%** |

The final examination was not conducted.

Rather than introducing a new examination or an unrelated assessment after the course had already been delivered, the final grade uses work that students had already produced during the trimester.

The **45% shared team portion remains unchanged**. The original **25% individual portion and the removed 30% examination portion were reorganised together into 55% of individually differentiated evidence**.

| Final assessment basis | Weight |
|---|---:|
| Shared team assessment | 45% |
| Individually differentiated assessment | 55% |
| Final examination | 0% |
| **Total** | **100%** |

The removed examination weight was not transferred into additional shared team marks. This prevents a student's result from depending too heavily on teammates and allows the final grade to reflect each student's own assignments, documented work, technical contribution, repository participation, and calibrated peer-review result.

---

## Final Grade Overview

| Category | Weight | Raw maximum | Formula |
|---|---:|---:|---|
| A. Team Coursework Assignments | 10% | 220 | `(raw / 220) × 10` |
| B. Team Engineering Process and Repository Evidence | 10% | 15 | `(raw / 15) × 10` |
| C. Individual Coursework Assignments | 7.5% | 20 | `(raw / 20) × 7.5` |
| D. Individual Contribution Logs | 7.5% | 8 | `(raw / 8) × 7.5` |
| E. Verified Technical and Project Contribution | 20% | 9 | `(raw / 9) × 20` |
| F. GitHub Workflow and Project Participation | 5% | 4 | `(raw / 4) × 5` |
| G. Final Term-Project Output and Submission | 25% | 120 | `(raw / 120) × 25` |
| H. Final Calibrated Peer-Review Score | 15% | 25 | `(raw / 25) × 15` |
| **Final Grade** | **100%** | — | `A + B + C + D + E + F + G + H` |

---

## Shared Team Assessment — 45%

The following three categories are shared by all members of the same team:

| Shared category | Weight |
|---|---:|
| Team Coursework Assignments | 10% |
| Team Engineering Process and Repository Evidence | 10% |
| Final Term-Project Output and Submission | 25% |
| **Total shared assessment** | **45%** |

### A. Team Coursework Assignments — 10%

This uses the sum of the graded team assignments completed throughout the trimester, including planning, user stories, backlog work, Definition of Done, architecture, ADRs, sprint activities, project realignment, sprint notes, and client updates.

```text
Team Coursework =
(team coursework raw total / 220) × 10
```

### B. Team Engineering Process and Repository Evidence — 10%

This evaluates how the team worked during the project using repository and project-management evidence.

The raw score is out of 15:

| Process area | Raw points |
|---|---:|
| Backlog, board, and issue quality | 4 |
| Sprint coordination, ownership, and board maintenance | 3 |
| Traceability, branch use, and commit discipline | 2 |
| Pull-request review, verification, and Definition of Done | 3 |
| CI, testing, integration, documentation, and adaptation | 3 |
| **Total** | **15** |

```text
Engineering Process =
(process score / 15) × 10
```

### G. Final Term-Project Output and Submission — 25%

This uses the final-product rubric covering the working software, demonstration, architecture and engineering decisions, presentation, handover package, and repository cleanup.

```text
Final Project =
(final-project raw score / 120) × 25
```

---

## Individually Differentiated Assessment — 55%

The individual scores of the following categories vary for each student:

| Individual category | Weight |
|---|---:|
| Individual Coursework Assignments | 7.5% |
| Individual Contribution Logs | 7.5% |
| Verified Technical and Project Contribution | 20% |
| GitHub Workflow and Project Participation | 5% |
| Final Calibrated Peer-Review Score | 15% |
| **Total individual assessment** | **55%** |

### C. Individual Coursework Assignments — 7.5%

The counted individual assignments are:

| Individual item | Raw maximum |
|---|---:|
| Individual Activity #3.1 — In-class Sprint Work Demonstration | 5 |
| Individual Activity #4.1 — In-class Sprint Work Demonstration 2 | 5 |
| Individual Assignment #4.2 — What Now Is Software Engineering? | 10 |
| **Total** | **20** |

```text
Individual Coursework =
(individual coursework raw total / 20) × 7.5
```

> Individual Assignment #4.4 — Peer Review is not included in this category.

### D. Individual Contribution Logs — 7.5%

Contribution logs are graded out of 8 based on their continuity, timing, specificity, reflection, traceability, and consistency with available project evidence.

```text
Contribution Logs =
(log score / 8) × 7.5
```

A log submitted within **four calendar days after the stated sprint period** is treated as within cadence. Historical Git versions, earlier filenames, renames, folder moves, copies, and merge artifacts were checked before determining whether an entry was late.

### E. Verified Technical and Project Contribution — 20%

This category measures each student's independently verified contribution to the delivered project.

| Contribution area | Raw points |
|---|---:|
| Coding and implementation contribution | 5 |
| Ownership, completion, and delivered impact | 2.5 |
| Engineering support, integration, testing, design, or documentation | 1.5 |
| **Total** | **9** |

```text
Technical Contribution =
(technical contribution score / 9) × 20
```

Commit counts and changed-line totals were used only as supporting evidence. The score also considers the scope, complexity, completion, delivered effect, integration, testing, documentation, and whether the work remained in the final system.

### F. GitHub Workflow and Project Participation — 5%

This evaluates each student's participation in the shared engineering workflow.

| Workflow area | Raw points |
|---|---:|
| Pull-request use | 1.5 |
| Issues and project-board participation | 1.25 |
| Review, merge, verification, and coordination | 1.25 |
| **Total** | **4** |

```text
GitHub Workflow =
(workflow score / 4) × 5
```

### H. Final Calibrated Peer-Review Score — 15%

This score reflects teammate evaluation of reliability, responsibility, communication, cooperation, temperament, and usefulness to the group.

```text
Peer Review =
(calibrated peer-review score / 25) × 15
```

The peer-review score was checked and calibrated rather than used as an unexamined average.

This is different from Individual Assignment #4.4:

| Item | Meaning | Included? |
|---|---|---:|
| Individual Assignment #4.4 | Completing the reviewer task | No |
| Final Calibrated Peer-Review Score | How teammates evaluated the student | Yes, 15% |

---

## Final Grade Formula

```text
Final Grade =
(Team Coursework raw / 220 × 10)
+ (Engineering Process raw / 15 × 10)
+ (Individual Coursework raw / 20 × 7.5)
+ (Contribution Logs raw / 8 × 7.5)
+ (Technical Contribution raw / 9 × 20)
+ (GitHub Workflow raw / 4 × 5)
+ (Final Project raw / 120 × 25)
+ (Calibrated Peer Review raw / 25 × 15)
```

The maximum possible final grade is **100**.

---

## Example Calculation

Suppose a student has:

| Category | Raw score |
|---|---:|
| Team Coursework | 190/220 |
| Engineering Process | 12/15 |
| Individual Coursework | 18/20 |
| Contribution Logs | 7/8 |
| Technical Contribution | 8/9 |
| GitHub Workflow | 3.5/4 |
| Final Project | 105/120 |
| Peer Review | 22/25 |

The weighted category scores are:

```text
Team Coursework:       (190 / 220) × 10  = 8.6364
Engineering Process:   (12 / 15) × 10    = 8.0000
Individual Coursework: (18 / 20) × 7.5   = 6.7500
Contribution Logs:     (7 / 8) × 7.5     = 6.5625
Technical Contribution:(8 / 9) × 20      = 17.7778
GitHub Workflow:       (3.5 / 4) × 5     = 4.3750
Final Project:         (105 / 120) × 25  = 21.8750
Peer Review:           (22 / 25) × 15    = 13.2000
```

```text
Final Grade =
8.6364 + 8.0000 + 6.7500 + 6.5625
+ 17.7778 + 4.3750 + 21.8750 + 13.2000
= 87.1767
```

Displayed to two decimal places:

```text
87.18 / 100
```

---

## How to Confirm Your Grade

1. Locate your raw score for each category.
2. Apply the formula shown in the Grade Overview table.
3. Keep the full decimal value from each calculation.
4. Add all eight weighted category scores.
5. Round only the final displayed result to two decimal places.

Small differences may appear if each category is rounded before adding. The authoritative total uses the full available decimal precision.
