<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4285F4,25:EA4335,50:FBBC05,75:34A853,100:4285F4&height=200&section=header&text=Praneeth%20Srikurmadasu&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Application%20and%20Development%20Apprenticeship%20at%20Google&descAlignY=58&descSize=17" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=4285F4&center=true&vCenter=true&width=900&lines=Software+Application+%26+Development+Apprenticeship+%40+Google;Backend+Engineer+%7C+Python+%E2%80%A2+Java+%E2%80%A2+Angular;Distributed+Systems+%E2%80%A2+Databases+%E2%80%A2+Reliability;I+build+systems+that+stay+correct+when+things+fail." alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/praneeth-srikurmadasu-738bb922a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:srikurmadasupraneeth@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://leetcode.com/u/Srikurmadasu_Praneeth/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://github.com/praneeth-srikurmadasu"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=praneeth-srikurmadasu&style=for-the-badge&color=34A853&label=Profile+Views" alt="profile views"/>

</div>

---

## About Me

I'm part of the **Software Application & Development Apprenticeship** at **Google** (since March 2025). I enjoy the hard parts of backend engineering: storage engines, transactions, retries, idempotency and the edge cases that show up when real systems fail.

Outside work I build systems from first principles to understand how they really work: a relational **database engine** in pure Python, a fault-tolerant **workforce integration platform**, and a **Raft-based distributed key-value store**.

<table>
<tr>
<td width="58%" valign="middle">

```python
class Praneeth:
    role      = ("Software Application & Development "
                 "Apprenticeship @ Google")
    since     = "March 2025"
    languages = ["Python", "Java", "C++",
                 "JavaScript", "TypeScript", "SQL"]
    backend   = ["FastAPI", "SQLAlchemy", "Celery",
                 "PostgreSQL", "Redis"]
    frontend  = ["Angular", "React"]
    interests = ["Distributed Systems",
                 "Database Internals",
                 "System Design", "Reliability"]
    principle = "Correct first, then fast, then pretty."
```

</td>
<td width="42%" align="center" valign="middle">
<img src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="100%"/>
</td>
</tr>
</table>

<div align="center">

<table>
<tr>
<td align="center" width="25%"><h3>Google</h3><sub>Apprentice since Mar 2025</sub></td>
<td align="center" width="25%"><h3>1,500+</h3><sub>automated tests across my projects</sub></td>
<td align="center" width="25%"><h3>3</h3><sub>systems projects built from scratch</sub></td>
<td align="center" width="25%"><h3>220+</h3><sub>LeetCode problems solved</sub></td>
</tr>
</table>

</div>

> **Note:** This is my new GitHub account. I lost access to my previous account after a two-factor authentication lockout, so my commit history here starts in August 2025. I'm actively rebuilding and publishing my work on this profile.

---

## Experience

<table>
<tr>
<td width="90" align="center"><img src="https://www.vectorlogo.zone/logos/google/google-icon.svg" width="56"/></td>
<td>

### Google
**Software Application & Development Apprenticeship** &nbsp;|&nbsp; March 2025 – Present

- Develop and maintain application features across the stack using **Python**, **Java** and **Angular (TypeScript)**
- Build backend services and APIs in Python and Java, and responsive front-end features in Angular
- Work within Google's engineering practices: design docs, rigorous code review, unit and integration testing, and CI/CD
- Collaborate with senior engineers on production code, focusing on readability, test coverage and maintainability

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
</p>

</td>
</tr>
</table>

---

## Featured Projects

### [SyncForge](https://github.com/praneeth-srikurmadasu/syncforge) — Fault-tolerant workforce integration platform

Keeps employee data consistent across HR, Slack, Google Workspace and payroll. Every hire, transfer or exit becomes an event, and background workflows update each connected system in order, **staying correct even when those systems fail**.

- **Reliable delivery:** transactional outbox, leases, idempotent steps and idempotency keys protect against duplicate deliveries and worker crashes
- **Reliability engine:** failure classification, exponential backoff with jitter (respects `Retry-After`), per-connector circuit breakers and rate limits, and a dead-letter queue with authorized replay
- **Data integrity:** field-level source-of-truth policies, conflict recording instead of silent overwrites, ETag-based optimistic concurrency, and a database-enforced append-only audit log
- **Multi-tenant security:** org isolation via composite foreign keys, role-based access, Argon2id, JWTs with server-side revocation, and encrypted connector credentials
- **Admin UI:** Angular app with 16 areas, role-aware navigation, dark mode and automated WCAG AA checks
- **Engineering rigor:** 579 backend tests on real PostgreSQL, 60 frontend unit and 13 Playwright E2E tests in CI, and 21 architecture decision records

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

---

### [PyDB](https://github.com/praneeth-srikurmadasu/PyDB) — A relational database engine built from scratch in pure Python

A disk-based relational database written using **only the Python standard library**, with SQL, B+ tree indexes, a cost-based query planner, ACID transactions with crash recovery, concurrent sessions, a TCP server and a DB-API driver.

- **Storage:** 4 KiB checksummed pages, free list, LRU buffer pool with pin counts and latches, slotted-page heaps
- **Indexing:** B+ trees with order-preserving key encoding, unique and composite keys, range scans
- **SQL:** DDL/DML, `INNER/LEFT JOIN`, `GROUP BY`/`HAVING`, aggregates, `ORDER BY`, `LIMIT`, three-valued NULL logic, parameterized queries and constraints
- **Query processing:** Volcano-style operators, three join algorithms (nested loop, index nested loop, hash), external merge sort, a System R–style cost model, and `EXPLAIN ANALYZE`
- **Transactions:** write-ahead log with **ARIES-style recovery** (redo with torn-page repair, logical undo, compensation records) and checkpoints, crash-tested by killing real processes
- **Concurrency:** serializable isolation via strict two-phase locking, waits-for graph deadlock detection, lock timeouts
- **Quality:** 850+ tests (Hypothesis model tests, a SQLite-checked query suite, threaded concurrency and crash tests), fully typed with `mypy --strict`

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/B%2B_Trees-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/WAL_%2F_ARIES-555555?style=flat-square"/>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
<img src="https://img.shields.io/badge/mypy_strict-2A6DB2?style=flat-square"/>
</p>

---

### [RaftKV](https://github.com/praneeth-srikurmadasu/raftkv) — Distributed key-value store on the Raft consensus algorithm *(in progress)*

<!-- TODO: replace with real details once shared -->
A replicated, fault-tolerant key-value store built on the Raft consensus protocol, with leader election, log replication and safety under node failures and network partitions.

---

## Problem Solving

<div align="center">

<a href="https://leetcode.com/u/Srikurmadasu_Praneeth/">
  <img src="https://leetcard.jacoblin.cool/Srikurmadasu_Praneeth?theme=dark&font=Fira%20Code" width="520"/>
</a>

</div>

- **220+ problems solved on LeetCode** across arrays, strings, hashing, trees, graphs and dynamic programming
- Earned the **Top SQL 50** badge
- Currently focused on medium/hard problems and system design

---

## Tech Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,java,cpp,js,ts,html,css&theme=dark" />

**Backend & Data**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,postgres,mysql,redis,mongodb&theme=dark" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=angular,react,tailwind,bootstrap&theme=dark" />

**Cloud, DevOps & Tools**
<br/>
<img src="https://skillicons.dev/icons?i=gcp,docker,githubactions,nginx,linux,git,postman,vscode&theme=dark" />

</div>

---

## Areas of Interest

| Area | What I've explored |
|:--|:--|
| **Database Internals** | Storage engines, B+ trees, buffer pools, WAL, ARIES recovery, query planning |
| **Distributed Systems** | Consensus (Raft), replication, idempotency, outbox pattern, failure handling |
| **Reliability Engineering** | Retries with backoff and jitter, circuit breakers, dead-letter queues, rate limiting |
| **Backend & APIs** | FastAPI, SQLAlchemy, Celery, multi-tenant design, auth and security |
| **Full-Stack** | Angular (signals, standalone components), React, accessible UI design |

---

<div align="center">

**Open to conversations about backend engineering, distributed systems and interesting problems.**
<br/>
Reach me at [srikurmadasupraneeth@gmail.com](mailto:srikurmadasupraneeth@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/praneeth-srikurmadasu-738bb922a/).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4285F4,25:EA4335,50:FBBC05,75:34A853,100:4285F4&height=120&section=footer" width="100%"/>

</div>
