# Hi, I'm Ayaz 👋

**Founder building AI for schools** · Dubai → London (UCL, 2026–27)

I build software that people in real schools use every day. My main project is
**[BC One](https://apps.bcacad.org)**, the school management platform running at
[BC Academy International School](https://bcacademy.ae) in Dubai. I also design
how AI is used across the school, from Claude plugins for teachers to custom
connectors for classroom tools.

I care about software that survives contact with real users: teachers who report
bugs, parents on phones, and children's data that has to be handled properly.

---

### 🔨 What I've built

| Project | What it is | Stack |
|---|---|---|
| **[BC One](https://github.com/ayaz-oss/bc-one-showcase)** | School management platform, live in production: timetables, attendance, lesson planning, reports, EYFS observations, parent portal, in-app AI agent | Python · FastAPI · Postgres (Supabase) · Claude API · Google Workspace APIs |
| **[Google Classroom MCP](https://github.com/ayaz-oss/classroom-mcp-showcase)** | Custom connector that lets teachers use their own Google Classroom from inside Claude, with per-teacher OAuth and safe defaults | TypeScript · Cloudflare Workers · MCP · OAuth 2.0 |
| **[Claude for Schools](https://github.com/ayaz-oss/claude-for-schools)** | School-wide AI rollout: 3 staff plugins, 14 skills and 4 agents for teachers, leadership and the office | Claude Team · plugins · skills · agents |
| **[ai-news-feed](https://github.com/ayaz-oss/ai-news-feed)** | Daily AI news digest (dev + education) sent to Telegram, fully automated | TypeScript · Bun · GitHub Actions |

> Most of my work lives in a private organisation because it handles school data.
> The showcase repos above explain what each system does and how it's built,
> without the source code.

---

### 📈 In numbers (BC One, since March 2026)

- **3,400+ commits**, about 85% of them mine: written and shipped through the Claude coding agents I direct, alongside a small team of developers
- **~85,000 lines** of backend Python across 130+ modules
- **~6,500 automated tests** and **165 database migrations**
- In use by teachers, leadership and office staff at a Nursery–Year 8 school

---

### 🧠 How I work

- **AI-agent engineering.** I run several Claude coding agents in parallel, each in
  its own git worktree, behind protected branches, CI and an AI review gate before
  anything reaches production.
- **Measure first.** Before building a feature, I check the real data. When leaders
  asked for a table ranking teachers by activity, the data showed most teachers
  hadn't started yet, so a ranking would've been meaningless. We built a view that
  shows which children and classes are missing observations instead.
- **Safety by design.** Least-privilege OAuth, drafts by default, audit trails, and a
  DPIA and AI acceptable-use policy written alongside the code.

---

### 🛠 Tools I use

`Python` `FastAPI` `TypeScript` `PostgreSQL` `Supabase` `Redis` `Cloudflare Workers`
`Claude API` `MCP` `Google Workspace APIs` `GitHub Actions` `Render` `Capacitor`

---

### 🌱 Also

- **Be Clever Games**: founder of an eco-educational board game company selling to schools

---

📫 **Contact:** ayaz.n@becleveredu.com · [LinkedIn](https://www.linkedin.com/in/ayaz-nasyrov-0b8018383/) · [apps.bcacad.org](https://apps.bcacad.org)
