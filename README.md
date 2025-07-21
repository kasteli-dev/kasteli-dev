
<h1 align="center">Hi there, I'm Kasteli 👋</h1>

<p align="center">
  <b>Full Stack Developer | Clean Architecture | Go · Java · Angular · Next.js · Docker · K8s · CI/CD</b>
</p>

---


🌍 Experienced full stack developer based in Spain, with 15+ years delivering robust solutions for fintech, insurance, and SaaS companies. Strong background in Java (Spring Boot), Angular, and DevOps (Docker, Kubernetes, CI/CD).

🚀 Now specializing in building modern backend systems with Go and web applications with Next.js, focusing on clean architecture, high-performance APIs, and seamless frontend-backend integration.

---


## 🏆 Featured Project

### TVTrackr API

A modern, hexagonal-architecture backend in Go to manage users and track TV series using TheTVDB and PostgreSQL.

> **Frontend coming soon:** TVTrackr tendrá también un frontend moderno en Next.js (React), con autenticación JWT, integración con la API y UI responsiva.

<details>
<summary>Show project details</summary>

#### Features
- 🔒 JWT authentication
- 📺 Search and follow TV series (TheTVDB integration)
- 👤 User registration & login
- 🗄️ PostgreSQL persistence
- 🧩 Hexagonal (ports & adapters) architecture
- 📝 OpenAPI-first design
- ♻️ Live reload for development (Air)
- 📦 Environment-based configuration
- 🚀 Database migrations with golang-migrate

#### Quickstart
```bash
git clone https://github.com/kasteli-dev/tvtrackr-go.git
cd tvtrackr-java
cp .env.example .env
# Edit .env with your TheTVDB API key and Postgres URL
migrate -path ./migrations -database "$POSTGRES_URL" up
go run ./cmd/main.go
```

#### API Reference
- OpenAPI spec: [`api/openapi.yaml`](./api/openapi.yaml)
- Main endpoints:
  - `POST /register` — Register user
  - `POST /login` — Login and get JWT
  - `GET /series/search?query=...` — Search series
  - `POST /series/follow` — Follow a series
  - `GET /series/followed` — List followed series

#### Tech Stack
- Go 1.21+
- [chi](https://github.com/go-chi/chi) (HTTP router)
- [pgx](https://github.com/jackc/pgx) (Postgres driver)
- [golang-migrate](https://github.com/golang-migrate/migrate) (DB migrations)
- [Air](https://github.com/cosmtrek/air) (live reload)
- [godotenv](https://github.com/joho/godotenv) (env vars)

</details>

---


## 🏢 Professional Experience

- **Senior Full Stack Developer**  
  *Fintech, SaaS & Consulting*  
  - Led backend and frontend development for high-availability platforms (Java, Spring Boot, Angular, React, Go, Docker, K8s)
  - Built and maintained Angular frontends and RESTful APIs
  - Designed and implemented CI/CD pipelines, reducing deployment times by 40%
  - Integrated PostgreSQL databases and automated testing
  - Mentored junior developers and led agile teams

---


## 🛠️ Skills

**Core skills:**  
Java (Spring Boot), Go (Golang), Angular, Next.js (React), Docker, Kubernetes, PostgreSQL, CI/CD, Team Leadership

**Frontend:**  
Angular, Next.js (React), HTML5, CSS3, TypeScript, Responsive Design

**Backend:**  
Go (Golang), Java (Spring Boot), REST/gRPC APIs, PostgreSQL

**Other:**  
Agile methodologies, TDD, Microservices, API Design, Cloud (AWS/GCP), GitHub Actions

---

## 🎓 Education & Certifications

- MSc in Computer Science
- Certified Kubernetes Application Developer (CKAD)
- Scrum Master (PSM I)

---

## 🌐 Languages

- Spanish (Native)
- English (Full professional proficiency)

---

## 📂 Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [`tvtrackr-go`](https://github.com/kasteli-dev/tvtrackr-go) | Modern hexagonal backend for TV series tracking (API + DB) | Go, chi, PostgreSQL, Docker |
| [`dev-setup`](https://github.com/kasteli-dev/dev-setup) _(coming soon)_ | My personal dotfiles, aliases, CLI tools, and Go setup | Bash, Git |

---

## 💡 Soft Skills

- Analytical thinking & problem solving
- Communication & adaptability
- Results-oriented mindset

---

## 📫 Let's connect!

- 🌐 Website: [kasteli.dev](https://kasteli.dev) _(coming soon)_
- 💼 LinkedIn: [linkedin.com/in/kasteli-dev](https://www.linkedin.com/in/kasteli-dev)
- 💻 GitHub: [github.com/kasteli-dev](https://github.com/kasteli-dev)

---

> “Build things. Break things. Learn fast.”  
> — Me, probably after Docker didn’t start 😅
