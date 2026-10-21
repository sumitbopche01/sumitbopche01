<a href="https://www.sumitbopche.com/"><img src="./banner.svg" width="100%" alt="Sumit Bopche, Senior Software and AI Engineer. Backends, GenAI, agents, retrieval, evals, and inference. Open to senior software, GenAI, and senior AI roles." /></a>

<div align="center">

<a href="https://www.sumitbopche.com/"><img alt="Website" src="https://img.shields.io/badge/sumitbopche.com-0D1117?style=for-the-badge&logo=googlechrome&logoColor=10B981" /></a>
<a href="https://www.sumitbopche.com/resume.pdf"><img alt="Resume" src="https://img.shields.io/badge/Resume-0D1117?style=for-the-badge&logo=adobeacrobatreader&logoColor=10B981" /></a>
<a href="https://www.linkedin.com/in/sumitbopche/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=10B981" /></a>
<a href="mailto:sumitbopche01@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=10B981" /></a>
<a href="https://sumitbopche01.medium.com/"><img alt="Medium" src="https://img.shields.io/badge/Medium-0D1117?style=for-the-badge&logo=medium&logoColor=10B981" /></a>
<a href="https://x.com/sumitbopche01"><img alt="X" src="https://img.shields.io/badge/X-0D1117?style=for-the-badge&logo=x&logoColor=10B981" /></a>

<sub><b>Jio</b> 2017 → <b>Freightify</b> 2019 → <b>Humber College, Toronto</b> 2022 → <b>Decentral</b> 2023 → <b>HariNext</b> 2026</sub>

</div>

---

### About

Senior software engineer, eight years in production, from backends at Jio and Freightify to GenAI systems at Decentral and HariNext. Open to **senior software**, **GenAI**, and **senior AI** roles.

Most of the agent orchestration is hand-built. The hard part is the budget on the loop, the retrieval when a vector hit is wrong, the eval before a model is trusted, and the service that has to stay up.

- **Decentral (2023–26), Senior Backend Engineer.**
  - Multi-agent orchestration in TypeScript: an orchestrator–worker retrieval loop, and a 9-role adversarial pipeline with convergence checks and human review. Caps on cycles, wall-clock time, and spend.
  - MCP on the official SDK, with dynamic tool discovery. Discovered tools and server health stored in Postgres.
  - Hybrid search over a Gmail-scale corpus (pgvector + Postgres full-text). Email ontology in Neo4j: 4 entity types, 8 relationship types.
  - Agent memory with a token budget, long-term vectors, and episodic snapshots. Evals: a golden set, LLM-as-judge, per-model token and cost telemetry.
  - Inference on an 8×H100 cluster. A multimodal assistant (Slack, email, speech, image) served with vLLM and Hugging Face TGI.
- **HariNext (2026–), Senior Software & AI Engineer.** Three live products, architecture through monitoring. [Portfolio](https://www.sumitbopche.com/).
  - [The CEO](https://the-ceo.harinext.com/) — a streaming assistant that runs the app through multi-step tool calls: tasks, inbox, navigation.
  - [Market Pulse](https://newsletter.harinext.com/) — 100 email editions and 58 reels published unattended, for 1,000+ investors and traders. Ingestion across hundreds of sources.
  - Options research — NSE strategies on live capital. About 50 evaluators across 21 families. Risk plane with loss limits, cooldowns, a kill switch, and idempotent routing. A strategy is promoted only after backtest, paper, and shadow eval.
- **Freightify (2019–22), Senior Software Engineer.** Owned the Go services that replaced a PHP monolith. API response time down 40%. CQRS cut freight-rate processing time 30%. Node services under TDD, production defects down 25%. Invoicing automation from a day to seconds. 100K+ requests a day.
- **Jio (2017–19).** Migrated the Jio Music backend to Node.js on a platform with 100M+ users. Google Home across 10M+ devices. Real-time systems on Socket.io and Elasticsearch. An internal CI/CD platform adopted across engineering teams.

---

### Building now

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://the-ceo.harinext.com/"><img src="./assets/the-ceo.jpg" alt="The CEO command center: today's tasks, a focus timer, and a live session" /></a>
      <br/><br/>
      <b>🗂️ <a href="https://the-ceo.harinext.com/">The CEO</a></b> &nbsp; <img alt="Live" src="https://img.shields.io/badge/live-10B981?style=flat-square" />
      <br/>
      A streaming assistant that runs the app through multi-step tool calls: tasks, inbox, and navigation. Eisenhower focus, Pomodoro, and learning paths stay free; chat and voice are optional.
      <br/>
      <sub><code>Next.js</code> <code>Supabase</code> <code>Tool calling</code> <code>SSE</code></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://newsletter.harinext.com/"><img src="./assets/market-pulse.jpg" alt="Market Pulse: a daily Indian, US, and Asian markets briefing" /></a>
      <br/><br/>
      <b>📈 <a href="https://newsletter.harinext.com/">Market Pulse</a></b> &nbsp; <img alt="Live" src="https://img.shields.io/badge/live-10B981?style=flat-square" />
      <br/>
      A daily markets briefing for 1,000+ investors and traders, plus <a href="https://www.instagram.com/marketpulse.live/">Instagram reels</a>. 100 email editions and 58 reels published with no hand edits. One gated pipeline: fetch → verify → narrate → QC → render → publish. Provenance envelopes mean estimated data never renders as fact, and a failed QC gate drops the output.
      <br/>
      <sub><code>TypeScript</code> <code>Bull/Redis</code> <code>Supabase</code> <code>OpenAI</code></sub>
    </td>
  </tr>
</table>

<br/>

**🥊 [Fit Fighter](https://youtu.be/r8Xz8QA-eko)** &nbsp; ![Beta](https://img.shields.io/badge/beta-F5A623?style=flat-square)\
A camera-based fitness game: moves tracked with on-device pose detection fuel the gameplay. v1 is out with a small user group. [Pitch](https://youtu.be/r8Xz8QA-eko) · [Privacy policy](https://sumitbopche01.github.io/fitfighter-legal/privacy/)\
<sub>`Flutter` `Pose detection` `On-device ML`</sub>

**📊 Options research platform** &nbsp; ![Private](https://img.shields.io/badge/private-6E7681?style=flat-square)\
NSE options on live capital. About 50 strategy evaluators across 21 families, with LightGBM walk-forward validation. Promotion only after backtest, paper, and shadow eval. Risk plane: loss limits, cooldowns, a kill switch, and idempotent routing.\
<sub>`FastAPI` `LightGBM` `WebSockets`</sub>

---

### Open source

**🔎 [beyond-vector-search](https://github.com/sumitbopche01/beyond-vector-search)** &nbsp;·&nbsp; Python\
The retrieval work, in public. The model lists files, greps, reads the lines it needs, and follows cross-references. A vector index is optional, and the trace of tool calls is the debugging tool. Essay: [*Beyond Vector Search*](https://sumitbopche01.medium.com/beyond-vector-search-how-claude-and-openai-agents-actually-find-information-in-documents-ce41336ab5b3).

### Writing

**GenAI**

- [*Beyond Vector Search: How Claude and OpenAI Agents Actually Find Information in Documents*](https://sumitbopche01.medium.com/beyond-vector-search-how-claude-and-openai-agents-actually-find-information-in-documents-ce41336ab5b3)
- [*Integrating Mistral AI with Dynamic Function Calls*](https://sumitbopche01.medium.com/integrating-mistral-ai-with-dynamic-function-calls-a-step-by-step-guide-db56fc7d1d79)

**Software engineering**

- [*Mastering State in React: Redux from First Principles*](https://sumitbopche01.medium.com/mastering-state-in-react-a-complete-guide-to-redux-from-first-principles-to-modern-patterns-b3254c101d37)
- [*JSON Web Tokens (JWT): The Ultimate Guide for Developers*](https://sumitbopche01.medium.com/json-web-tokens-jwt-the-ultimate-guide-for-developers-a527ea0dfd4d)
- [*Understanding Strings, Bytes, and Runes in Golang*](https://sumitbopche01.medium.com/understanding-strings-bytes-and-runes-in-golang-6800f0f8b2e4)
- [*Understanding SOLID Principles*](https://sumitbopche01.medium.com/understanding-solid-principles-the-key-to-clean-and-maintainable-code-daf9ba682df2)
- [*Sockets in Operating System*](https://sumitbopche01.medium.com/sockets-in-operating-system-bee34d6f5d72)
- [*Run a Golang Binary as a Daemon Service*](https://sumitbopche01.medium.com/run-golang-executable-binary-as-daemon-service-ce306c740cca)
- [*TypeScript Cheatsheet*](https://sumitbopche01.medium.com/typescript-cheatsheet-8e2819254383)
- [*Basics of the Aggregation Pipeline in MongoDB*](https://sumitbopche01.medium.com/basics-of-aggregation-pipeline-in-mongodb-17c3279f1764)
- [*Understanding QR Codes*](https://sumitbopche01.medium.com/understanding-qr-codes-a-detailed-exploration-ca62fa767a65)

**Latest posts**
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

---

### How I build

| Principle | Where it shows up |
|---|---|
| **Bounded over open-ended.** Every agent loop gets a budget and a stop condition. | Plan-execute-review loops at Decentral with hard caps on cycles, wall-clock time, and spend |
| **Pipelines over mega-agents.** Small contracted stages are debuggable. | Market Pulse's fetch → verify → narrate → gate → publish stages |
| **Fail closed.** A skipped output beats a confidently wrong one. | Fail-closed QC gates on generated reel scripts; provenance so estimates never pass as facts |
| **Measure before trusting.** | Golden sets, LLM-as-judge, and per-model cost/token telemetry |
| **Retrieval is a system, not a vector DB.** | Hybrid pgvector + Postgres FTS with RRF, LLM-built Neo4j graphs, agentic search |

---

### Stack

**AI layer**

| | |
|---|---|
| **Agents** | Hand-built multi-agent orchestration · MCP with dynamic tool discovery · tool calling · bounded plan-execute-review · trigger.dev · LangChain · LangGraph |
| **Retrieval** | pgvector · Postgres full-text search · reciprocal rank fusion · Neo4j · agentic search |
| **Evals** | Golden sets · LLM-as-judge · per-model cost and token telemetry |
| **Inference** | vLLM · Hugging Face TGI · PyTorch · 8×H100 serving · LightGBM |

**Backend and platform**

| | |
|---|---|
| **Languages** | Go · Python · TypeScript |
| **Services** | FastAPI · NestJS · Next.js · React · Flutter · WebSockets · CQRS |
| **Data** | PostgreSQL · Redis · Bull · MongoDB · Elasticsearch · Supabase |
| **Platform** | AWS · GCP · Docker · Kubernetes · GitHub Actions · NGINX · Grafana / Loki |

---

<div align="center">

**Open to senior software, GenAI, and senior AI roles.** [Résumé](https://www.sumitbopche.com/resume.pdf) · [Email](mailto:sumitbopche01@gmail.com)

</div>
