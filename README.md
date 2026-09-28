<h1>Ayaz Nasyrov</h1>

**Founder building AI for schools** · Dubai → London (UCL, 2026–27)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayaz_Nasyrov-0A66C2?style=flat-square)](https://www.linkedin.com/in/ayaz-nasyrov-0b8018383/)
[![BC One](https://img.shields.io/badge/BC_One-apps.bcacad.org-111111?style=flat-square)](https://apps.bcacad.org)
[![Email](https://img.shields.io/badge/Email-ayaz.n@becleveredu.com-555555?style=flat-square&logo=minutemailer&logoColor=white)](mailto:ayaz.n@becleveredu.com)

I build software that people in real schools use every day. My main project is
**[BC One](https://apps.bcacad.org)**, the school management platform running at
[BC Academy International School](https://bcacademy.ae) in Dubai. I also design
how AI is used across the school, from Claude plugins for teachers to custom
connectors for classroom tools.

I care about software that survives contact with real users: teachers who report
bugs, parents on phones, and children's data that has to be handled properly.

---

### 01 — Selected work

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

### 02 — BC One in numbers

<table>
  <tr>
    <td align="center"><h3>3,400+</h3>commits since March 2026<br/><sub>~85% mine, via the agents I direct</sub></td>
    <td align="center"><h3>~85k</h3>lines of backend Python<br/><sub>130+ modules</sub></td>
    <td align="center"><h3>~6,500</h3>automated tests<br/><sub>165 database migrations</sub></td>
  </tr>
</table>

In daily use by teachers, leadership, office staff and parents at a Nursery–Year 8 school.

---

### 03 — How I work

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

### 04 — Stack

<table>
  <tr>
    <td><b>AI</b></td>
    <td><img src="https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude API"/> <img src="https://img.shields.io/badge/MCP-1A1A1A?style=flat-square&logo=modelcontextprotocol&logoColor=white" alt="MCP"/> <img src="https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic SDK"/></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white" alt="Bun"/></td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Supabase-1C1C1C?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/></td>
  </tr>
  <tr>
    <td><b>Integrations</b></td>
    <td><img src="https://img.shields.io/badge/Google_Workspace-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Workspace"/> <img src="https://img.shields.io/badge/Google_Classroom-0F9D58?style=flat-square&logo=googleclassroom&logoColor=white" alt="Google Classroom"/></td>
  </tr>
  <tr>
    <td><b>Infra &amp; mobile</b></td>
    <td><img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers"/> <img src="https://img.shields.io/badge/Render-000000?style=flat-square&logo=render&logoColor=46E3B7" alt="Render"/> <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/> <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor"/></td>
  </tr>
</table>

---

### 05 — Also

**Be Clever Games** · Founder of an eco-educational board game company selling to schools.

---

<sub>ayaz.n@becleveredu.com · [LinkedIn](https://www.linkedin.com/in/ayaz-nasyrov-0b8018383/) · [apps.bcacad.org](https://apps.bcacad.org)</sub>
