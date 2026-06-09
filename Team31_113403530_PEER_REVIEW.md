# Peer Review Report

## Your Details

| Field          | Your answer |
| -------------- | ----------- |
| Full Name      | 欉家誼         |
| Student ID     | 113403530   |
| Team ID        | Team31      |
| Date submitted | 2026-06-10  |

---

## Section A — Self-Assessment

### A1. What did you personally implement?

I was primarily responsible for the relational database component of the project. I designed the relational database schema (schema.sql), implemented the PostgreSQL query functions for availability, fares, seat management, user information, bookings, and authentication, and developed the PostgreSQL seeding script (seed_postgres.py). I also authored the ER Diagram and Normalisation Justification sections of the design document.

---

### A2. What challenges did you face?

One challenge was designing a relational database schema that could support multiple modules, including user management, bookings, payments, metro operations, and national rail operations while maintaining proper normalization. Another challenge was integrating the relational database with the graph database and vector database components. I addressed these issues through iterative testing, schema refinement, and collaboration with teammates responsible for Neo4j and RAG functionality.

---

### A3. Self-rating

| Criterion                                                   | Rating (1–5) | Justification (1–2 sentences)                                                                                           |
| ----------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| I delivered the tasks assigned to me in the work allocation | 5            | I completed all relational database tasks and documentation sections assigned to me.                                    |
| The quality of my work was satisfactory                     | 4            | The database schema and query functions met the project requirements and integrated successfully with other components. |
| I communicated well and kept the team informed              | 4            | I regularly communicated progress and coordinated integration work with teammates.                                      |
| I met deadlines agreed within the team                      | 5            | All assigned tasks were completed within the agreed schedule.                                                           |
| **Overall self-rating**                                     | **4**        | I completed my assigned responsibilities successfully and contributed significantly to the project.                     |

---

### A4. Estimated contribution percentage

My estimated contribution: **40%**

---

## Section B — Peer Assessments

### B1. Assessment of Teammate 1

| Field                 | Your answer |
| --------------------- | ----------- |
| Teammate's full name  | 戴睿真         |
| Teammate's student ID | 113403525   |

#### What did this teammate deliver?

戴睿真 was primarily responsible for the Vector/RAG extension. This included implementing pgvector integration, policy document retrieval, embedding generation, semantic search functionality, and seed_vectors.py. They also supported relational query review, SQL optimization, and graph query integration. In the design document, they authored the Vector / RAG Design section and the Optional Extension section.

#### Did their actual contribution match the agreed work allocation?

Yes. Their work matched the agreed allocation and they successfully completed the vector database and RAG implementation.

#### Peer rating for this teammate

| Criterion                                           | Rating (1–5) | Justification (1–2 sentences)                                                                 |
| --------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------- |
| Delivered the tasks assigned in the work allocation | 5            | All assigned vector database and RAG tasks were completed.                                    |
| Quality of their work was satisfactory              | 5            | The implemented functionality worked as intended and integrated well with the overall system. |
| Communicated well and kept the team informed        | 4            | Communication was consistent throughout the project.                                          |
| Met deadlines agreed within the team                | 5            | Assigned tasks were completed on schedule.                                                    |
| **Overall rating for this teammate**                | **5**        | Delivered high-quality work and contributed effectively to the project.                       |

#### Estimated contribution percentage for this teammate

My estimate of their contribution: **30%**

---

### B2. Assessment of Teammate 2

| Field                 | Your answer |
| --------------------- | ----------- |
| Teammate's full name  | 蕭彤恩         |
| Teammate's student ID | 113403526   |

#### What did this teammate deliver?

蕭彤恩 was primarily responsible for the Neo4j graph database component. This included graph database design, graph data seeding, graph relationships, and implementation of graph query functions. They also authored the Graph Database Design Rationale section of the design document.

#### Did their actual contribution match the agreed work allocation?

Yes. Their work matched the agreed allocation and all graph database tasks were completed successfully.

#### Peer rating for this teammate

| Criterion                                           | Rating (1–5) | Justification (1–2 sentences)                                                                              |
| --------------------------------------------------- | ------------ | ---------------------------------------------------------------------------------------------------------- |
| Delivered the tasks assigned in the work allocation | 4            | Completed all assigned Neo4j tasks.                                                                        |
| Quality of their work was satisfactory              | 5            | The graph database implementation functioned correctly and supported the required route-planning features. |
| Communicated well and kept the team informed        | 4            | Maintained communication during development and integration.                                               |
| Met deadlines agreed within the team                | 5            | Completed assigned work within the agreed timeline.                                                        |
| **Overall rating for this teammate**                | **5**        | Successfully delivered the graph database component and contributed positively to the project.             |

#### Estimated contribution percentage for this teammate

My estimate of their contribution: **30%**

---

## Section C — Contribution Percentage Summary

| Member         | Your estimated % | Notes                                                                              |
| -------------- | ---------------- | ---------------------------------------------------------------------------------- |
| Yourself (欉家誼) | 40%              | Relational database design, PostgreSQL queries, seeding, ER diagram, normalisation |
| 戴睿真            | 30%              | Vector database, RAG implementation, integration support                           |
| 蕭彤恩            | 30%              | Neo4j graph database design, seeding, and query implementation                     |
| **Total**      | **100%**         |                                                                                    |

---

## Section D — Overall Team Reflection

### D1. What went well in the team's collaboration?

The team divided responsibilities clearly across relational, graph, and vector database components. Each member focused on a specific area while still supporting integration and testing efforts. Communication was effective and allowed us to successfully combine multiple database technologies into a working transportation assistant system.

---

### D2. What would you do differently if you did this project again?

If we were to repeat the project, we would begin integration testing earlier and establish a more structured schedule for combining the relational, graph, and vector database components. This would reduce debugging effort and make final integration smoother.

---

### D3. Is there anything else the markers should know about team dynamics or individual contributions?

Nothing to add.

---

## Declaration

I confirm that this peer review reflects my honest and independent assessment. I understand it will be kept confidential from my teammates.

**Signed:** 欉家誼

**Date:** 2026-06-10
