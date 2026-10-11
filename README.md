<h1 align="center">Zhuoheng (Felix) Li</h1>

<p align="center">
  <b>Product Manager · AI Products · 0→1 Builder</b><br/>
  M.S. Management & Analytics @ NYU · New York<br/>
  <sub>产品经理 / AI 产品 · 从 0 到 1 独立做产品 · 现居纽约</sub>
</p>

<p align="center">
  <a href="https://lizhuoheng.com/?utm_source=github"><img src="https://img.shields.io/badge/Website-lizhuoheng.com-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://www.linkedin.com/in/zhuoheng-li-3365b5351/"><img src="https://img.shields.io/badge/LinkedIn-Zhuoheng%20Li-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:zhuohengli03@gmail.com"><img src="https://img.shields.io/badge/Email-zhuohengli03%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://lingxian.app"><img src="https://img.shields.io/badge/Live%20product-lingxian.app-8B5A2B?style=flat-square" alt="Lingxian"/></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Zhuohengli03&hide_border=true&theme=dark"/>
    <img src="https://streak-stats.demolab.com?user=Zhuohengli03&hide_border=true" alt="GitHub streak"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Zhuohengli03/Zhuohengli03/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/Zhuohengli03/Zhuohengli03/output/github-snake.svg" width="100%" alt="Snake animation eating my GitHub contribution graph"/>
  </picture>
</p>

---

### About me

- I build products end to end: talk to users, write the spec, ship it with AI-assisted coding, then read the data and decide what to fix next.
- M.S. in Management & Analytics (STEM) at NYU, graduating **Jan 2027**. Open to full-time **PM / AI PM** roles (NYC and SF preferred, open to anywhere in the US).
- B.A. in Music Performance before that, which is how I ended up building software for musicians.
- Interested in AI agents, evals, human-in-the-loop design, and turning messy domain content into structured data.

### Featured project: [Lingxian](https://lingxian.app)

A notation-editing SaaS for the guqin, a traditional Chinese string instrument. Teachers and students were sharing scores through hand copies and phone photos; I defined, built and launched a structured score editor with cloud sync and PDF export. Solo, from zero, currently in invite-only beta.

| | |
|---|---|
| **Traction** | 94 users created 160 scores and exported 144 PDFs in 7 months; 20.7% week-2 retention |
| **Activation** | Built a 5-step funnel, found that 53% of creators never produced a usable score, shipped faster input with live preview; that drop-off fell to 35% |
| **Auto-transcription** | A rule engine generates valid options and beam search picks the best full-piece sequence; users can override, and ~3,800 corrections have been logged as ranking-model training data |
| **AI editing agent** | Natural-language assistant inside the editor. 74-case eval set, prompt iterations v1.0 → v1.4, **96% intent accuracy, 100% valid JSON, zero high-risk false triggers** |

How the agent avoids bad edits: the LLM only understands the request; deterministic tools do every calculation and write.

```mermaid
flowchart LR
    A[User request] --> B[LLM parses intent]
    B --> C[Check against current score]
    C --> D[Preview change]
    D --> E{User confirms?}
    E -- yes --> F[Deterministic tool executes]
    E -- no --> A
    F --> G[One-click undo]
```

### Toolbox

**Product:** user research · PRDs · MVP scoping · funnel & event-tracking design · prioritization<br/>
**AI product:** agent task design · prompt iteration · eval sets · human-in-the-loop · preference data

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square" alt="SQL"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square" alt="Tableau"/>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor"/>
</p>

### Off the clock

1,500+ hours in *Squad*, currently deep into *Wardogs* · board games · photography · trying every new AI agent tool I can get my hands on.

---

<p align="center">
  <img src="banner.jpg" width="100%" alt="Felix at his desk in New York: laptop, guqin, camera and the city at night"/>
</p>
