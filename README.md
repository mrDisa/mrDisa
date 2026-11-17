# Daniil Isaverdov

**Go Backend Developer**  
Building backend services with a focus on reliability, concurrency, and clean architecture.

[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/disawithgod)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:daniil.isaverdov@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mrdisa)
[![Resume](https://img.shields.io/badge/Resume-334155?style=flat-square&logoColor=white)](https://drive.google.com/file/d/1AEOvpR_CZOdJoDOwtjraPnuhAjcPIoi6/view)

---

## About

I'm a backend developer working primarily with **Go and PostgreSQL**. I enjoy building APIs, designing data models, and solving problems where correctness and performance matter.

I contribute to a six-person product team, and I also build and deploy my own applications. Currently studying at **ITHub** and **School 21**.

**Open to Junior Go Backend opportunities.**

## Experience

### Gouve <sub>· Go Backend Developer · Aug 2026 – present</sub>

*Telegram bot and Mini App for task, habit, and time tracking.*

My work spans API development, database logic, and real-time functionality:

- **Concurrent data operations** — built kanban board ordering with PostgreSQL transactions and `SELECT FOR UPDATE` to handle simultaneous changes.
- **Real-time communication** — implemented updates over SSE with pub/sub and buffered Go channels, keeping long-lived streams independent of database connections.
- **HTTP reliability** — investigated streaming export failures and traced the issue to middleware that didn't expose `Unwrap()`, affecting response flushing.
- **Data and time handling** — worked on schema migrations, SQL modeling, user time zones, calendar boundaries, and tests for edge cases.

I collaborate through task tracking, feature branches, pull requests, and code reviews.

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,postgres,docker,linux,git,githubactions,nginx,python,django&perline=9" alt="Go, PostgreSQL, Docker, Linux, Git, GitHub Actions, Nginx, Python, Django"/>
</p>

| Backend | Data | Infrastructure |
| :--- | :--- | :--- |
| Go · `net/http` · chi | PostgreSQL · pgx | Docker Compose · Linux |
| REST · SSE · goroutines | SQL · transactions | Nginx · GitHub Actions |
| Table-driven tests | Migrations · indexes | Git · pull requests |

---

<sub>See the pinned repositories below for projects and source code.</sub>
