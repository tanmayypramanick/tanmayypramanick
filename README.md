<!-- =========================================================
     TANMAY PRAMANICK — GITHUB PROFILE
     Software Engineer • Full-Stack • AI • Product Systems
========================================================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:050505,45:171717,100:404040&text=TANMAY%20PRAMANICK&fontColor=ffffff&fontSize=43&fontAlignY=37&desc=Software%20Engineer%20%E2%80%A2%20Full-Stack%20%E2%80%A2%20AI%20%E2%80%A2%20Product%20Systems&descAlignY=58&descSize=16&animation=fadeIn" alt="Tanmay Pramanick"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2600&pause=800&color=BDBDBD&center=true&vCenter=true&width=900&lines=I+build+the+whole+thing.;Problem+%E2%86%92+Product+%E2%86%92+Architecture+%E2%86%92+Production;Full-Stack+%2B+AI+%2B+Data+%2B+Infrastructure;Building+systems+for+real+users+and+real+business+problems." alt="Typing animation"/>
</a>

<br/>

<a href="https://tanmaypramanick.vercel.app/"><img src="https://img.shields.io/badge/PORTFOLIO-111111?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/tanmayypramanick/"><img src="https://img.shields.io/badge/LINKEDIN-252525?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:tanmaypramanick06@gmail.com"><img src="https://img.shields.io/badge/EMAIL-383838?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.fyndit.me/"><img src="https://img.shields.io/badge/FYNDIT-LIVE-505050?style=for-the-badge&logo=vercel&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=tanmayypramanick&label=PROFILE+VIEWS&color=303030&style=flat-square" alt="Profile views"/>

</div>

---

## `tanmay@github:~$ whoami`

```yaml
name: Tanmay Pramanick
location: Chicago, IL
role: Software Engineer — Full-Stack, AI & Product Systems

I_build:
  - AI agents, RAG & local-first AI systems
  - full-stack web & mobile products
  - distributed systems & backend infrastructure
  - workflow automation & enterprise integrations
  - analytics, data pipelines & internal platforms

I_optimize_for:
  - real user problems
  - business impact
  - end-to-end ownership
  - pragmatic architecture
  - shipping, measuring, iterating

currently_exploring:
  - agentic AI
  - MCP & tool orchestration
  - local-first intelligence
  - memory / retrieval architectures
  - reliable AI infrastructure
```

> **My favorite kind of problem:** ambiguous, cross-functional, operationally painful, and important enough that somebody should just own it end-to-end.

---

## `> how_i_build`

<div align="center">

```text
                         ┌──────────────────────┐
                         │   USER / BUSINESS    │
                         │       PROBLEM        │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │   PRODUCT THINKING   │
                         │ workflows • metrics  │
                         └──────────┬───────────┘
                                    │
                                    ▼
                    ┌───────────────────────────────┐
                    │          ARCHITECTURE         │
                    └───────┬────────┬────────┬─────┘
                            │        │        │
                     ┌──────▼───┐ ┌──▼───┐ ┌──▼────────┐
                     │ FRONTEND │ │ APIs │ │ AI / DATA │
                     └──────┬───┘ └──┬───┘ └──┬────────┘
                            │        │        │
                            └────────┼────────┘
                                     ▼
                         ┌──────────────────────┐
                         │ CLOUD / INFRA / CI   │
                         └──────────┬───────────┘
                                    ▼
                         ┌──────────────────────┐
                         │      PRODUCTION      │
                         └──────────┬───────────┘
                                    ▼
                           MEASURE → ITERATE ↺
```

**I don't care where the boundary is. If solving the problem requires crossing it, I cross it.**

</div>

---

# `// FEATURED SYSTEMS`

<table>
<tr>
<td width="50%" valign="top">

## 🧠 Vesper
### Local-First Personal AI Memory System

`Python` `Ollama` `ChromaDB` `Whisper` `Piper` `Flask` `SSE`

A self-hosted AI memory system designed to turn fragmented personal context into an intelligent, searchable memory layer.

**System surface**
- Gmail
- WhatsApp
- iMessage
- Calendar
- Contacts
- Browser history
- Screen activity
- Voice interface
- Always-on kiosk

**Engineering**
- **12K+ indexed semantic memories**
- Local LLM + embeddings + STT + TTS
- Single-writer ChromaDB architecture
- Time-aware retrieval
- Multi-source ingestion
- Proactive briefings / alerts
- Built around a **2 GB Maxwell GPU**
- Voice first-response latency: **~25s → 1.5–1.7s**

**The interesting part:** making useful AI work privately on constrained hardware instead of solving every problem with another cloud API.

[**Explore Vesper →**](https://github.com/tanmayypramanick/Vesper-AI-Second-Brain)

</td>
<td width="50%" valign="top">

## 🛕 ISKCON Chicago
### Community Operations Platform

`React Native` `Expo` `Supabase` `PostgreSQL` `RLS` `Edge Functions`

A multi-role iOS / Android product that turns fragmented community operations into one system.

**Product surface**
- Devotee profiles & directory
- Temple check-ins
- Seva scheduling / assignment
- QR-started service & attendance
- Messaging & sangas
- Announcements / newsletters
- Donations & sponsorships
- Community care workflows

**Architecture**
- Multi-role authorization
- Supabase Auth
- PostgreSQL row-level security
- Realtime updates
- Protected Edge Functions
- Storage + notifications
- Privacy-aware messaging behavior

**The interesting part:** permissions, privacy, communication, operations and mobile UX all become one architecture problem.

[**See my work →**]([https://tanmaypramanick.vercel.app/](https://github.com/tanmayypramanick/iskcon-chicago-community-app))

</td>
</tr>

<tr>
<td width="50%" valign="top">

## 🤖 MCP Support Orchestrator
### AI That Takes Actions

`FastMCP` `LLMs` `PostgreSQL` `SSE` `Docker` `AWS RDS`

Not another chatbot.

A support automation system where the model understands a request and coordinates tools to execute the workflow.

```text
Customer Request
       │
       ▼
      LLM
       │
       ▼
  MCP Orchestrator
   /     |      \
  ▼      ▼       ▼
Jira   Slack    Email
```

- Query classification
- Jira ticket generation
- Slack escalation
- Email drafting / actions
- SSE streaming
- Batch processing for **100+ queries**
- Modeled to eliminate **90% of manual triage**

[**Source →**](https://github.com/tanmayypramanick/MCP-based-CustomerSupport-Orchestrator) · [**Live →**](https://mcp-based-supportorchestrator.vercel.app/)

</td>
<td width="50%" valign="top">

## 🛒 Fyndit
### Student Marketplace + Housing

`Next.js` `TypeScript` `Firebase` `Mapbox`

Campus buying, selling and housing discovery was fragmented across WhatsApp groups.

So I built the product I wanted to exist.

```text
Fragmented Groups
       ↓
Verified Marketplace
       +
Housing Discovery
       +
Realtime Chat
       +
Location Search
```

- `.edu` verification
- Real-time messaging
- Location-aware discovery
- Marketplace + housing
- Built for actual campus workflows
- Grew to **100+ active students**

**The signal:** problem discovery → product → launch → real users.

[**Launch Fyndit →**](https://www.fyndit.me/)

</td>
</tr>

<tr>
<td width="50%" valign="top">

## 🌐 Decentralized P2P Pub/Sub
### Distributed Systems Lab

`Python` `DHT` `P2P` `Hypercube Routing`

Instead of implementing one architecture, I evolved the same pub/sub problem through three.

```text
Central Server
      ↓
Central Peer Index
      ↓
Distributed Hash Table
      ↓
Fully Decentralized P2P
```

- DHT-based topic ownership
- Hypercube peer topology
- Neighbor-only communication
- Latency benchmarking
- Throughput benchmarking
- Failure resilience
- Hash-distribution analysis

**The interesting part:** making the coordination / resilience / routing tradeoffs visible rather than hiding them behind a framework.

[**Source →**](https://github.com/tanmayypramanick/Decentralized-P2P-Pub-Sub-System)

</td>
<td width="50%" valign="top">

## 📊 Unified CPG Dashboard
### Enterprise Operations Intelligence

`React` `TypeScript` `Python` `Node.js` `Playwright`

Built a unified operating layer over fragmented commerce, supplier, distributor and advertising systems.

```text
NetSuite ───────┐
Amazon SP-API ──┤
Instacart Ads ──┼──► NORMALIZE ─► OPERATING VIEW
KeHE ───────────┤                  │
UNFI ───────────┘                  ├─ BI
                                  ├─ Forecasting
                                  └─ Inventory
```

APIs where possible. Browser automation where necessary.

**The interesting part:** architecture organized around the business question rather than source-system boundaries.

[**Portfolio →**](https://tanmaypramanick.vercel.app/)

</td>
</tr>
</table>

---

<details>
<summary><h2>🧪 <code>more_builds --expand</code></h2></summary>

<br/>

| Project | Problem / Engineering Signal | Stack |
|:--|:--|:--|
| **AI Interviewer** | Resume/JD-aware adaptive interviews with retrieval, conversational memory and voice | LLaMA 3, RAG, FAISS, TTS, React |
| **Chicago Crime Analysis & Predictive Modeling** | EDA, temporal/geospatial features, hotspot analysis, classification and evaluation | Python, Pandas, scikit-learn |
| **AI Email Assistant** | Inbox prioritization, thread understanding, context-aware replies and follow-up workflows | TypeScript, React, OpenAI, Microsoft Graph |
| **GitHub Analytics Dashboard** | Contributor activity, issues, deployments, velocity and engineering reporting | Next.js, TypeScript, GitHub API, Recharts |
| **Webpage Summarizer** | NLP / summarization pipeline | Python, Jupyter |
| **Disease Prediction & Recommendation** | ML prediction / recommendation exploration | Python, Jupyter |
| **Flutter Apps** | Mobile product experiments including flashcards, quiz and weather experiences | Flutter, Dart |
| **C++ Projects** | Systems / programming projects including translation and games | C++ |

<br/>

<div align="center">

[**Browse all repositories →**](https://github.com/tanmayypramanick?tab=repositories)

</div>

</details>

---

# `// ENGINEERING TOOLBOX`

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=python,ts,js,java,cpp,dart&theme=dark" alt="Languages"/>

### Product Engineering

<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,fastapi,spring,flutter&theme=dark" alt="Product engineering"/>

### Data + Infrastructure

<img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,firebase,supabase,aws,gcp,docker,linux,nginx,git&theme=dark" alt="Data and infrastructure"/>

<br/>

`LLMs` · `RAG` · `MCP` · `NLP` · `Embeddings` · `FAISS` · `ChromaDB` · `LangChain` · `Ollama` · `Whisper` · `TTS`

`REST` · `GraphQL` · `SSE` · `Microservices` · `CI/CD` · `Playwright` · `Power BI` · `Pandas`

</div>

---

# `// ENGINEERING TRAJECTORY`

```text
                    SOFTWARE
                    DEVELOPER
                        │
                        ▼
                 OPERATIONS +
                  AUTOMATION
                        │
                        ▼
                 FULL-STACK +
                  AI SYSTEMS
                        │
                        ▼
              PRODUCT-MINDED
             SOFTWARE ENGINEER
                        │
        ┌───────────────┼────────────────┐
        │               │                │
        ▼               ▼                ▼
   AI / AGENTS      WEB / MOBILE      DATA / INFRA
        │               │                │
        └───────────────┼────────────────┘
                        ▼
                 SHIPPED SYSTEMS
```

---

# `// GITHUB SIGNAL`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=tanmayypramanick&show_icons=true&hide_border=true&rank_icon=github&theme=transparent&title_color=ffffff&text_color=a8a8a8&icon_color=d0d0d0" alt="Tanmay's GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanmayypramanick&layout=compact&hide_border=true&theme=transparent&title_color=ffffff&text_color=a8a8a8&langs_count=8" alt="Top languages"/>

<br/>

<img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=tanmayypramanick&bg_color=00000000&color=bcbcbc&line=8b8b8b&point=ffffff&area=true&hide_border=true&custom_title=Contribution%20Signal" alt="Contribution activity graph"/>

</div>

> **Projects > vanity metrics.** These cards are decoration; shipped systems are the actual signal.

---

# `// SIDE QUEST`

<div align="center">

### 🐍 feeding the contribution graph...

<img src="https://raw.githubusercontent.com/tanmayypramanick/tanmayypramanick/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake"/>

<sub>The snake is generated automatically by the workflow in <code>.github/workflows/snake.yml</code>.</sub>

<br/><br/>

<a href="https://github.com/tanmayypramanick/Yahtzee-Game"><img src="https://img.shields.io/badge/🎲_EXPLORE_A_GAME-YAHTZEE-151515?style=for-the-badge"/></a>
<a href="https://www.fyndit.me/"><img src="https://img.shields.io/badge/⚡_TRY_A_REAL_PRODUCT-FYNDIT-303030?style=for-the-badge"/></a>

</div>

---

# `// CURRENTLY`

<div align="center">

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2400&pause=700&color=AFAFAF&center=true&vCenter=true&width=850&lines=%24+exploring+agentic+AI+%2B+MCP;%24+building+local-first+intelligence;%24+thinking+about+memory+%2B+retrieval;%24+shipping+products+for+real+users;%24+always+looking+for+the+next+hard+problem_" alt="Currently building animation"/>
</a>

</div>

```python
class Tanmay:
    location = "Chicago, IL"

    interests = [
        "AI systems",
        "full-stack products",
        "distributed systems",
        "automation",
        "product engineering",
    ]

    def solve(self, problem):
        understand_users(problem)
        identify_business_constraints(problem)
        architecture = design_pragmatically(problem)
        product = build_end_to_end(architecture)
        ship(product)
        measure(product)
        return iterate(product)
```

---

# `// LET'S BUILD`

<div align="center">

### Have an ambitious problem?

I like teams where engineers are close to users, close to the business, and trusted to own outcomes.

<br/>

<a href="https://tanmaypramanick.vercel.app/"><img src="https://img.shields.io/badge/EXPLORE_MY_WORK-PORTFOLIO-111111?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/tanmayypramanick/"><img src="https://img.shields.io/badge/LET'S_CONNECT-LINKEDIN-252525?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:tanmaypramanick06@gmail.com"><img src="https://img.shields.io/badge/BUILD_SOMETHING-EMAIL-3b3b3b?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<sub>Chicago, IL • Software Engineering • Full-Stack • AI • Product Systems</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=105&section=footer&color=0:404040,55:171717,100:050505" alt="Footer"/>

</div>
