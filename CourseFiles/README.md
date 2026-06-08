# CourseFiles — Course Design Documents

One `.md` file per course, produced by the [Course Design Workflow](../Course_Design_Workflow.md) and verified against the [Course Design Checklist](../Course_Design_Checklist.md).

---

## Folder map

```
CourseFiles/
├── Foundation/       ← courses in ALL 6 programs (Sem I–II; mostly FC)
├── AI-Programs/      ← courses shared by AIDS + AIML (± CSE) (Sem I–III)
├── CS-Programs/      ← courses shared by CSE + CSIT + ISE + IoT (Sem I–II)
├── AIDS/             ← AIDS-exclusive courses
├── AIML/             ← AIML-exclusive courses
├── CSE/              ← CSE-exclusive courses
├── CSIT/             ← CSIT-exclusive courses
├── ISE/              ← ISE-exclusive courses
└── IoT/              ← IoT-exclusive courses
```

**Rule:** place the course file in the *most-shared* folder that correctly describes its scope. Never duplicate a file — one course, one file.

| Where it goes | Condition |
|---|---|
| `Foundation/` | Course code appears in all 6 program scheme docs (`Docs/*-v1.md`) |
| `AI-Programs/` | Course appears in AIDS + AIML (and optionally CSE), but not in CSIT / ISE / IoT |
| `CS-Programs/` | Course appears in CSE + CSIT + ISE + IoT (and optionally AIML), but not in AIDS |
| `<PROGRAM>/` | Course appears in exactly one program |

When a course straddles a boundary that doesn't fit the above (e.g. AIDS + CSE only), put it in the more specific program folder and add a note in the front-matter `shared_with:` field.

---

## File naming

```
CF_<CourseCode>_<ShortTitle>.md
```

Examples:
- `CF_B24AH0103_CommunicativeEnglish.md`
- `CF_B25CS0301_DataStructuresAlgorithms.md`
- `CF_B25EA0302_PrinciplesOfAI.md`

If the course code has not yet been assigned (common in Sem IV–VIII while the 2026 scheme is being finalised), use:

```
CF_Sem<Roman>_<ShortTitle>.md
```

Example: `CF_SemV_NaturalLanguageProcessing.md`

Update the name once the official code is assigned.

---

## Program → course file index

Use this to find all course files relevant to a given program.

### AI & Data Science (AIDS)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `AI-Programs/` | AIDS+AIML shared courses (Sem I–III) |
| `AIDS/` | AIDS-exclusive courses (Sem III–VIII) |

### AI & Machine Learning (AIML)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `AI-Programs/` | AIDS+AIML shared courses (Sem I–III) |
| `AIML/` | AIML-exclusive courses (Sem III–VIII) |

### Computer Science & Engineering (CSE)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `CS-Programs/` | CSE+CSIT+ISE+IoT shared courses (Sem I–II) |
| `AI-Programs/` | CSE also shares some Sem III courses with AIDS+AIML (see codes B25AS0301, B25CS0301, B25CS0302, B25CS0304, B25CS0305, B25ME0301) |
| `CSE/` | CSE-exclusive courses (Sem III–VIII) |

### Computer Science & Information Technology / Cyber Security (CSIT)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `CS-Programs/` | CSE+CSIT+ISE+IoT shared courses (Sem I–II) |
| `CSIT/` | CSIT-exclusive courses (Sem III–VIII) |

### Information Science & Engineering (ISE)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `CS-Programs/` | CSE+CSIT+ISE+IoT shared courses (Sem I–II) |
| `ISE/` | ISE-exclusive courses (Sem III–VIII) |

### Internet of Things & Cyber Security (IoT)
| Folder | What to find there |
|---|---|
| `Foundation/` | All 17 Sem I–II foundation courses |
| `CS-Programs/` | CSE+CSIT+ISE+IoT shared courses (Sem I–II) |
| `IoT/` | IoT-exclusive courses (Sem III–VIII) |

---

## Course file front-matter (YAML header)

Every course file should begin with this block so automated tools can query it without parsing the prose:

```yaml
---
course_code: "B25CS0301"
title: "Data Structures and Algorithms"
programs: [AIDS, AIML, CSE]        # all programs this file serves
semester: III
category: HC                        # HC / FC / SC / OE / MC / ETC / AEC / W
ltpc: "2-0-1-3"
cie: 50
see: 50
level: "A+Adv"                      # A / Adv / A+Adv / — (from Curriculum_Visual_Map.md)
faculty: ""
ay: ""
---
```

---

## Course counts (from 2026 scheme docs, Sem I–III)

| Folder | Coded courses now | Expected final |
|---|---|---|
| `Foundation/` | 17 | ~17 (Sem I–II complete) |
| `AI-Programs/` | 13 | ~25–35 (Sem I–VI) |
| `CS-Programs/` | 3 | ~15–25 (Sem I–VI) |
| `AIDS/` | 0 | ~15–20 |
| `AIML/` | 0 | ~15–20 |
| `CSE/` | 8 | ~15–20 |
| `CSIT/` | 0 | ~15–20 |
| `ISE/` | 0 | ~15–20 |
| `IoT/` | 0 | ~15–20 |

> **Note:** Semesters IV–VIII of the 2026 scheme are partially coded. Course files for those semesters should be created as courses are designed, using `CF_Sem<Roman>_<ShortTitle>.md` until official codes are assigned.

---

## How to create a new course file

1. Identify the program(s) this course serves → choose the right folder (table above).
2. Use the **`reva-course-designer`** skill in Claude Code, or follow the [Course Design Workflow](../Course_Design_Workflow.md).
3. Name the file `CF_<CourseCode>_<ShortTitle>.md` and add the YAML front-matter.
4. After the faculty review, run the **`reva-course-reviewer`** skill to verify against the checklist.
5. Commit and open a PR.
