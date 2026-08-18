<div align="center">

# Akash Sengar

**Engineering Leader · AI Infrastructure · TypeScript**

Founding Member at [Xhipment](https://www.xhipment.com) · Creator of [Agentium](https://agentium.in)

<br/>

[![Website](https://img.shields.io/badge/Website-akashsengar.dev-111827?style=flat-square)](https://www.akashsengar.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-akashsengar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akashsengar)
[![YouTube](https://img.shields.io/badge/YouTube-akashsengar-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCk9JLSJrC5W1XmJwaxcxKVQ)
[![GitHub](https://img.shields.io/badge/GitHub-aakashsengar-181717?style=flat-square&logo=github)](https://github.com/aakashsengar)

</div>

<br/>

I build production AI systems — agent runtimes, orchestration layers, and the infrastructure that keeps them reliable. My work sits at the intersection of TypeScript, LLM tooling, and systems that have to run in the real world: memory, tools, cost controls, and human oversight.

Currently shipping **[Agentium](https://github.com/agentiumOS/agentium)**, a TypeScript-native framework for multi-agent systems on Node.js.

```ts
const engineer = {
  name: "Akash Sengar",
  role: "Engineering Leader",
  company: "Xhipment",
  focus: ["AI agent systems", "TypeScript", "open source infrastructure"],
  building: "Agentium — TypeScript-native agent orchestration for Node.js",
  contributing: "agno-agi/agno",
  education: "Computer Science, VIT Vellore",
} as const;
```

---

## Agentium

A TypeScript-native agent orchestration framework for Node.js. Model-agnostic, batteries-included, and designed for production — not demos.

[![npm](https://img.shields.io/npm/v/@agentium/core?style=flat-square&label=%40agentium%2Fcore&color=CB3837)](https://www.npmjs.com/package/@agentium/core)
[![GitHub](https://img.shields.io/github/stars/agentiumOS/agentium?style=flat-square&logo=github&label=stars)](https://github.com/agentiumOS/agentium)
[![Docs](https://img.shields.io/badge/docs-docs.agentium.in-4F46E5?style=flat-square)](https://docs.agentium.in)
[![Website](https://img.shields.io/badge/web-agentium.in-111827?style=flat-square)](https://agentium.in)

```ts
import { Agent, openai } from "@agentium/core";

const researcher = new Agent({
  name: "researcher",
  model: openai("gpt-4o"),
  instructions: "Research thoroughly and cite sources.",
});

const result = await researcher.run("Summarize Q4 market trends");
```

<table>
<tr>
<td width="50%" valign="top">

**Agents & memory**
- Tools with Zod schemas and function calling
- Session, user, and long-term memory
- RAG with hybrid search
- Guardrails, hooks, and human-in-the-loop

</td>
<td width="50%" valign="top">

**Teams & runtime**
- Coordinate, route, broadcast, and collaborate
- Workflows with retries and parallel steps
- Express, Socket.IO, voice, and browser agents
- PostgreSQL, MongoDB, Redis, SQLite, and BullMQ

</td>
</tr>
</table>

Production concerns are first-class: cost tracking, semantic cache, audit trails, sandbox execution, and multi-tenant isolation.

**[Documentation](https://docs.agentium.in)** · **[GitHub](https://github.com/agentiumOS/agentium)** · **[npm](https://www.npmjs.com/org/agentium)** · **[Website](https://agentium.in)**

---

## Stack

| Area | Technologies |
| :--- | :--- |
| Languages | TypeScript, JavaScript, Python |
| AI | LLM APIs, agent architecture, RAG, MCP, A2A |
| Runtime | Node.js, React, Socket.IO, Playwright |
| Data | PostgreSQL, MongoDB, Redis, BullMQ |
| Infra | Linux, Git, REST, WebSockets |

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
</p>

---

## Open source

**[agno-agi/agno](https://github.com/agno-agi/agno)** &nbsp; [![Stars](https://img.shields.io/github/stars/agno-agi/agno?style=flat-square)](https://github.com/agno-agi/agno)

Contributor to one of the most widely used open-source agent frameworks — features, fixes, and production-oriented improvements.

I also publish occasional walkthroughs on agent architecture, TypeScript internals, and system design on [YouTube](https://www.youtube.com/channel/UCk9JLSJrC5W1XmJwaxcxKVQ).

---

## GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aakashsengar&show_icons=true&hide_border=true&bg_color=0d1117&title_color=818CF8&icon_color=818CF8&text_color=c9d1d9&count_private=true" height="160" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aakashsengar&layout=compact&hide_border=true&bg_color=0d1117&title_color=818CF8&text_color=c9d1d9" height="160" alt="Top languages" />

</div>

---

<div align="center">

Open to collaborations on AI infrastructure, agent systems, and open source.

[LinkedIn](https://www.linkedin.com/in/akashsengar) · [Website](https://www.akashsengar.dev) · [Agentium](https://agentium.in) · [GitHub](https://github.com/aakashsengar)

</div>
