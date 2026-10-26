<h1 align="center">Daniil Isaverdov</h1>

<p align="center">
  <b>Go Backend Developer</b> · Moscow · open to remote
</p>

<p align="center">
  <a href="https://t.me/disawithgod"><img src="https://img.shields.io/badge/Telegram-@disawithgod-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:daniil.isaverdov@gmail.com"><img src="https://img.shields.io/badge/Email-daniil.isaverdov@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/mrdisa"><img src="https://img.shields.io/badge/LinkedIn-mrdisa-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://drive.google.com/file/d/1SIX2tka5pg-MbJSoKNWrbef5z-KhvSAf/view"><img src="https://img.shields.io/badge/Resume-PDF-111111?style=flat-square&logo=readdotcv&logoColor=white" alt="Resume"></a>
</p>

---

### About

Go backend developer on a product team at **Gouve**. I build services in Go and PostgreSQL: transactions and concurrent data access, real-time over Server-Sent Events, tests that hit a real database. Studying C → Go at **School 21**. Looking for a **Junior / Junior+ Go Backend** role.

### 💼 Experience

**Go Backend Developer · Gouve** &nbsp;—&nbsp; *Sep 2026 – present*  
Product team of 6 · Telegram bot and Mini App for time, task and habit tracking

- **Fixed data exports breaking at the 15-second mark.** Traced it to an HTTP middleware wrapper without `Unwrap()`, which silently disabled `Flush` and write-deadline extension. The fix turned on streaming responses across the whole API.
- **Shipped real-time updates over SSE with ~1 s latency.** Pub/sub on a change feed, non-blocking fan-out through buffered channels; streams are isolated from the DB connection pool and don't affect API latency.
- **Built kanban boards with race-free drag-and-drop** under concurrent editing — ordering is recomputed in one transaction with `SELECT … FOR UPDATE`; story points, priorities, filtered and paginated history.
- **Designed a data model for tasks living in several lists without duplication:** a flag with a partial index, read/write permissions split at the SQL level, atomic numbering via CTE.
- **Added per-user time zones:** day boundaries, stats and reminders computed in local time.

### 🚀 Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| **[Prolongo](https://github.com/mrDisa/Prolongo)** | Churn-risk analyzer for a hosting provider — who may not renew, why, and how much revenue is at risk. Hackathon case by Aéza. **My part:** Go core — risk model, API, SSE, Prometheus metrics, auth and SSO. | Go · chi · pgx · PostgreSQL · Prometheus · Grafana · Keycloak |
| **[Raspy](https://github.com/mrDisa/Raspy)** | Telegram Mini App with a personal college timetable. In production: [@raspy_smk_bot](https://t.me/raspy_smk_bot) | Go · chi · pgx · PostgreSQL · Docker · Nginx |
| **[LinkSpider](https://github.com/mrDisa/LinkSpider)** | Concurrent broken-link checker CLI: worker pool, bounded parallelism, timeouts via `context`. | Go |
| **[DevSpace](https://github.com/mrDisa/Devspace)** | Social network for developers, team of 2: REST API with JWT and role-based permissions. | Python · Django REST · PostgreSQL |

### 🛠 Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=go,postgres,docker,githubactions,nginx,prometheus,grafana,linux,bash,git,python,django&perline=12" alt="Go, PostgreSQL, Docker, GitHub Actions, Nginx, Prometheus, Grafana, Linux, Bash, Git, Python, Django">
</p>

**Also:** net/http · chi · pgx · golang-migrate · Server-Sent Events · REST · Telegram Bot API · goroutines & channels · table-driven tests
