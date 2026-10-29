# Product Backlog

Ordered by priority. Top items get pulled into the next sprint.
Estimates are in hours of focused work. Every sprint has three lanes: learning, career, project.
Detailed job pipeline and interview prep live in a private Notion database, not in this public repo.

## Lane A: Learning (Deep Learning Specialization)

| # | Item | Est (h) | Status |
|---|------|---------|--------|
| A1 | Course 4 (CNNs), weeks 1 and 2 | 13 | Sprint 01 |
| A2 | Course 4 (CNNs), weeks 3 and 4: object detection, face recognition, style transfer | 13 | Sprint 02 |
| A3 | Next remaining course in the specialization | 20 to 30 | Backlog |
| A4 | Add certificates and a short write-up to portfolio | 2 | Backlog |

## Lane B: Career (fixed slot every sprint)

| # | Item | Est (h) | Status |
|---|------|---------|--------|
| B1 | Apply to 3 roles per week with tailored resume | 2/wk | Every sprint |
| B2 | Prep for each interview (checklist lives in the private pipeline) | as needed | On demand |

## Lane C: Projects (one active at a time)

**Active:** AI phone assistant (`ai-phone-assistant` repo)

| # | Item | Est (h) | Status |
|---|------|---------|--------|
| C1 | Demo recording and README polish for portfolio | 2 | Sprint 01 |
| C2 | VIP contacts that always ring through (tests first) | 2 | Sprint 01 |
| C3 | Booking callbacks into the calendar, approved by SMS | 6 | Backlog |
| C4 | Agent templates for different kinds of offices | 6 | Backlog |
| C5 | Phone assistant case study and postmortem: problem, design, what broke, eval results, written for a non-technical reader | 3 | Sprint 02 |
| C6 | Second FDE-style project: RAG assistant over a messy document set, graded eval set, deployed with Docker on AWS | 12 | Backlog |

**Parking lot (not started, ranked):**
1. Resume micrograd (original roadmap)
2. Transformers from scratch

## Target role: Forward Deployed Engineer (FDE)

An FDE embeds with a customer, scopes a vague problem, builds a proof of concept, hardens it for production, and feeds what they learn back to the product team. The projects and learning above are chosen to build proof for that loop.

Search titles beyond "Forward Deployed Engineer": AI Solutions Engineer, Applied AI Engineer, Customer Engineer, Implementation Engineer, Solutions Architect (hands-on).

| Skill FDE roles ask for | Where I stand | Plan |
|---|---|---|
| Python, full-stack, APIs | Strong (4 years, Django) | Keep using it in projects |
| AWS | Strong (two certifications) | Deploy C6 on AWS |
| Shipped, tested, evaluated system | Phone assistant has CI and an eval suite | C1, C5 turn it into proof |
| LLM apps with common tools (RAG, agents, evals, vector search) | Gap (phone assistant runs local models) | C6 |
| Docker, CI/CD, monitoring | Partial | C6 includes Docker and logging |
| SQL and data pipelines | To check | Add to a learning sprint |
| Customer-facing: scope a vague problem, explain to non-technical people | Few written examples | C5 case study, practice decomposition out loud |

Interview shape to prepare for: behavioral stories about ownership (STAR), practical coding and data-heavy design, and an open-ended case study where I ask questions, scope an MVP and think out loud.

## Rules
- Only pull items into a sprint if they fit the lane hours.
- One active project at a time. Starting another means finishing or pausing the active one.
- New ideas go to the bottom of the backlog, not into the running sprint.
