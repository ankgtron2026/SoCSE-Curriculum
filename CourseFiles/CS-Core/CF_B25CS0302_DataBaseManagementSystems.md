---
course_code: "B25CS0302"
title: "Data Base Management Systems"
programs: [AIDS, AIML, CSE]
semester: III
category: HC
ltpc: "1-1-1-3"
contact_hours_per_week: 5
cie: 50
see: 50
total_marks: 100
aicte_category: PCC
level: "A+Adv"
status: draft
---

# Course File — Data Base Management Systems

> **Status: DRAFT** — This file applies the dual-level 1-1-1 design for DBMS. Complete faculty details, session dates, and local PO/PSO mapping before submission.

---

## 0. Course identification 🟢

| Field | Entry |
|---|---|
| Faculty name | ‹…› |
| REVA ID | ‹…› |
| Email | ‹…› |
| Programme | B.Tech — AIDS / AIML / CSE |
| Course code | B25CS0302 |
| Course title | Data Base Management Systems |
| Category | HC |
| L-T-P-C | 1-1-1-3 |
| Contact hours / week | 5 |
| Semester | III |
| Section | ‹…› |
| Academic year | ‹…› |
| Course duration (sessions) | 5 contact hrs/week × ‹16 weeks› |
| Office / consultation hours | ‹…› |

**School vision / mission:** ‹standard text — unchanged›

---

## 1. Course description 🟢

This course introduces the fundamentals of database systems, focusing on relational modeling, SQL, normalization, query optimization, and transaction processing. Students learn to design robust schemas, write correct and efficient queries, and manage data integrity through an integrated theory–lab curriculum.

---

## 2. Course content (units & weightage) 🟢

| Unit | Syllabus | Weightage |
|---|---|---|
| 1 | Database systems overview, relational model, ER modeling, and relational algebra. | 25 |
| 2 | SQL DDL/DML, integrity constraints, views, joins, and basic query formulation. | 25 |
| 3 | Functional dependency, normalization, indexing, query execution, and optimization. | 25 |
| 4 | Transactions, concurrency control, recovery, security, and physical database design. | 25 |

---

## 3. 🔵 Dual-level scope of each unit (KEYSTONE)

| Unit | Awareness level — every student must reach (floor) | Advanced level — required to exceed 8 CGPA (ceiling) |
|---|---|---|
| 1 | Define database terminology, draw ER diagrams, and translate small problem statements into relational schemas. | Analyze schema choices and extend ER models to cover non-trivial constraints and business rules. |
| 2 | Write and run correct SQL queries for selection, projection, join, aggregation, and simple updates. | Debug complex SQL queries and construct multi-step reports using nested queries, set operations, and views. |
| 3 | Normalize schemas to 3NF and select appropriate indexing strategies for simple retrieval patterns. | Evaluate normalization trade-offs, design composite indexes, and reason about query plan behavior. |
| 4 | Explain transaction atomicity, consistency, isolation, and durability, and identify common concurrency and recovery issues. | Propose concurrency control and recovery strategies for a given workload, and justify security controls for a sample application. |

---

## 4. Course objectives 🟢

- Introduce relational database concepts and modeling techniques for structured data.
- Enable students to express data requirements with SQL and verify query results.
- Develop schema design skills that preserve data integrity and support maintainability.
- Teach transaction management and concurrency concepts to ensure consistent database behavior.
- Build practical competence through regular lab-based development and evaluation.

---

## 5. Course outcomes (COs) and PO/PSO mapping 🟢

| CO# | Course outcome | Bloom level 🔵 | Level (Awareness / Advanced / Both) 🔵 | POs | PSOs |
|---|---|---|---|---|---|
| CO1 | Describe database models, ER diagrams, and relational schemas for simple applications. | Understand | Awareness | PO1, PO2 | PSO1 |
| CO2 | Construct and execute SQL queries to retrieve, modify, and report relational data. | Apply | Awareness | PO1, PO2, PO3 | PSO1 |
| CO3 | Design normalized relational schemas and apply integrity constraints to preserve data correctness. | Apply | Both | PO2, PO3 | PSO1 |
| CO4 | Analyze query patterns and choose indexing and optimization strategies for performance. | Analyze | Advanced | PO3, PO4 | PSO1 |
| CO5 | Apply transaction, concurrency, and recovery principles to maintain database consistency. | Apply | Both | PO4, PO5 | PSO2 |
| CO6 | Evaluate database design trade-offs and propose improvements for maintainability, performance, and security. | Evaluate | Advanced | PO4, PO5, PO9 | PSO2 |

---

## 6. Pedagogy 🟢

This course uses an integrated theory–lab pedagogy. Each week combines a focused lecture, guided tutorial practice, and a hands-on lab exercise. Teaching includes direct instruction, worked examples, collaborative debugging, and problem-based learning with incremental implementation tasks.

---

## 7. Textbooks, references, e-resources 🟢

**Textbook(s):**
- Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems*.
- Korth, H. F., Silberschatz, A., & Sudarshan, S. (2019). *Database System Concepts*.

**References:**
- Ramakrishnan, R., & Gehrke, J. (2020). *Database Management Systems*.
- Ullman, J. D. (2009). *A First Course in Database Systems*.

**Web / e-books / NPTEL:**
- SQLZoo, W3Schools SQL Tutorial, GeeksforGeeks SQL Guide, DB-Fiddle.
- NPTEL Lectures on Database Management Systems.

---

## 8. 🔵 Differentiated instruction (mapped to the two levels)

**Reaching the floor (awareness level) — for students at risk:**
- Provide guided worksheets and step-by-step SQL labs for query construction.
- Use pair programming and peer review in lab sessions to support weaker students.
- Offer optional remediation clinics during tutorial hours focused on schema modeling and query debugging.

**Reaching the ceiling (advanced level) — for students aiming above 8 CGPA:**
- Assign stretch tasks on query optimization, indexing strategy comparison, and advanced view/materialized-view design.
- Offer optional case studies on transaction design for realistic business applications.
- Encourage advanced learners to critique schema designs and propose secure, maintainable alternatives.

---

## 9. Assignments 🟢

| Assignment | Units covered | Marks | Window |
|---|---|---|---|
| Assignment 1 | Unit 1 & 2 | 5 | Before IA-2 |
| Assignment 2 | Unit 3 & 4 | 5 | Before IA-3 |

---

## 10. Prerequisites / pre-reading 🟢

**Prerequisite courses:** Data Structures and Algorithms, Computer Organization.

**Pre-reading:** relational algebra basics, set theory review, and introductory programming constructs.

---

## 11. Lesson plan 🟢🔵

| S.No | Planned date | Exec. date | Unit / topic | Merrill phase 🔵 | Activity 🔵 | % compl. | Level (A/Adv) 🔵 | CO 🔵 | Remarks |
|---|---|---|---|---|---|---|---|---|---|
| 01 | ‹…› | | Unit 1 — Database concepts, applications, and architecture | Activation | Introduce DBMS vs file systems, relate to real data problems | 5% | A | CO1 | |
| 02 | ‹…› | | Unit 1 — ER modelling and relationship types | Demonstration | Build ER diagrams from textual requirements | 10% | A | CO1 | |
| 03 | ‹…› | | Unit 1 — Relational model and algebra | Application | Write relational algebra expressions for sample queries | 15% | A | CO1 | |
| 04 | ‹…› | | Unit 1 — Advanced schema modelling | Integration | Extend a schema with weak entities and multi-valued attributes | 20% | Adv | CO1 | |
| 05 | ‹…› | | Unit 2 — SQL DDL and DML basics | Demonstration | Create tables, insert/update/delete data in lab | 25% | A | CO2 | |
| 06 | ‹…› | | Unit 2 — SQL joins and aggregations | Application | Construct and test join queries with grouping | 30% | A | CO2 | |
| 07 | ‹…› | | Unit 2 — Constraints, views, and subqueries | Application | Implement constraints and use views in exercises | 35% | A | CO2 | |
| 08 | ‹…› | | Unit 2 — Advanced query formulation | Integration | Develop nested queries and set-operator solutions | 40% | Adv | CO2 | |
| 09 | ‹…› | | Unit 3 — Functional dependency and normalization | Activation | Identify dependencies and normalize a schema to 3NF | 45% | A | CO3 | |
| 10 | ‹…› | | Unit 3 — Indexing fundamentals | Demonstration | Compare simple indexes, clustered vs non-clustered | 50% | A | CO4 | |
| 11 | ‹…› | | Unit 3 — Query execution and cost | Application | Analyze simple query plans and estimate cost | 55% | A | CO4 | |
| 12 | ‹…› | | Unit 3 — Advanced performance design | Integration | Design index strategy for a given workload and justify choice | 60% | Adv | CO4 | |
| 13 | ‹…› | | Unit 4 — Transactions and ACID | Activation | Explain ACID and transaction life-cycle with examples | 65% | A | CO5 | |
| 14 | ‹…› | | Unit 4 — Concurrency control | Demonstration | Simulate schedule serializability and locking behavior | 70% | A | CO5 | |
| 15 | ‹…› | | Unit 4 — Recovery and durability | Application | Identify recovery actions after crash scenarios | 75% | A | CO5 | |
| 16 | ‹…› | | Unit 4 — Security and access control | Application | Configure role-based privileges and secure view access | 80% | A | CO6 | |
| 17 | ‹…› | | Unit 4 — Advanced transaction design | Integration | Propose a recovery and isolation strategy for a business case | 85% | Adv | CO6 | |
| 18 | ‹…› | | Revision — combined SQL and design problems | Integration | Complete a cumulative lab covering all units | 90% | Adv | CO3, CO4, CO5 | |
| 19 | ‹…› | | Pre-SEE practice | Application | Run mock lab exam and solve prior-question case studies | 95% | A | CO2, CO3, CO5 | |
| 20 | ‹…› | | Course wrap-up and review | Integration | Reflection on floor vs advanced outcomes, closing checklist | 100% | Adv | CO6 | |

---

## 12. ICT & digital support 🟢

- SQLZoo and DB-Fiddle for interactive SQL practice.
- DBVisualizer / DBeaver for schema design and query execution.
- NPTEL and YouTube lectures for supplementary concepts.
- Course LMS for lab instructions, sample databases, and assessment rubrics.

---

## 13. Academic integrity policy 🟢

All coursework, lab submissions, quizzes, and tests must be original and properly attributed. Any form of plagiarism or copying in evaluation components will result in zero marks for the affected component.

---

## 14. 🔵 Evaluation scheme — dual-level

| Sl | Component | Marks | Weight % | Awareness marks (floor) | Advanced marks (ceiling) | Date | COs |
|---|---|---|---|---|---|---|---|
| 1 | Test 1 (IA-1) | 20 | 20 | 14 | 6 | Week 6 | CO1–CO3 |
| | Test 2 (IA-2) | 20 | 20 | 14 | 6 | Week 12 | CO4–CO6 |
| | Assignment 1 | 5 | 5 | 3 | 2 | Week 8 | CO1–CO3 |
| | Assignment 2 | 5 | 5 | 3 | 2 | Week 14 | CO4–CO6 |
| 2 | SEE | 50 | 50 | 35 | 15 | End of semester | CO1–CO6 |
| **CIE Total** | | **50** | | | | | |
| **Grand Total** | | **100** | | | | | |

### 14.1 🔵 CGPA calibration check

| Check | Entry |
|---|---|
| Marks-to-CGPA conversion used | Standard REVA conversion where 70–74% corresponds to the 7.x band and 75%+ enters 8.0+ band. |
| Max % achievable from awareness marks alone | 70% |
| Grade band that % falls into | Below 8 CGPA band |
| Advanced marks needed to cross 8 CGPA | At least 10–12 of the advanced 30 marks |
| ✅ Calibration confirmed (awareness-only < 8 CGPA) | Yes |

### 14.2 Question-paper blueprint 🔵

| Instrument | Awareness questions (Bloom: R/U/Ap) | Advanced questions (Bloom: An/E/C) |
|---|---|---|
| IA-1 / IA-2 | Simple SQL writing, schema interpretation, normalization, transaction concepts | Complex query synthesis, debugging, indexing justification, recovery design |
| SEE | Standard question sets on all units with SQL and design tasks | At least one advanced analysis/design question per unit |

---

## 15. 🔵 Result analysis

| Exam | < 40% (below floor — remediate) | 40–75% (floor cleared) | > 75% (advanced attained) |
|---|---|---|---|
| IA-1 | | | |
| IA-2 | | | |
| SEE | | | |

---

## 16. Learner support tracking 🟢🔵

### 16.1 Remediation (students below floor)

| Sl | SRN | Name | IA | Gap identified | Remedial class dates | Re-assessment result |
|---|---|---|---|---|---|---|

### 16.2 Enrichment (students reaching for ceiling)

| Sl | SRN | Name | Advanced task assigned | Outcome |
|---|---|---|---|---|

---

## 17. 🔵 Track-advice signal

| Field | Entry |
|---|---|
| Prerequisite for a SIG track? | Yes — Advanced DBMS, Data Engineering, AI App Dev |
| % students at advanced level (> 75% / 8+ CGPA) | ‹…› |
| Domains where advanced performance clustered | Query optimization, schema design, transaction handling |
| Note to academic mentors | Students meeting the advanced level are strong candidates for data-engineering and backend systems SIGs. |

---

## 18. CO attainment 🟢

**Target:** 60%

| CO | IA1 | IA2 | A1 | A2 | SEE | Direct attainment | Level 🔵 |
|---|---|---|---|---|---|---|---|
| CO1 | | | | | | | A |
| CO2 | | | | | | | A |
| CO3 | | | | | | | Both |
| CO4 | | | | | | | Adv |
| CO5 | | | | | | | Both |
| CO6 | | | | | | | Adv |

---

## 19. CO–PO/PSO mapping & overall attainment 🟢

| CO | PO1 | PO2 | PO3 | PO4 | PO5 | PO6 | PO7 | PO8 | PO9 | PO10 | PO11 | PO12 | PSO1 | PSO2 | PSO3 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CO1 | X | X | | | | | | | | | | | X | | |
| CO2 | X | X | X | | | | | | | | | | X | | |
| CO3 | | X | X | | | | | | | | | | X | | |
| CO4 | | | X | X | | | | | | | | | | X | |
| CO5 | | | | X | X | | | | | | | | | | X |
| CO6 | | | | X | X | | | | | | | | | | X |

---

## 20. Course completion summary 🟢

| Unit | Planned date | Completion date | Remarks |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |
