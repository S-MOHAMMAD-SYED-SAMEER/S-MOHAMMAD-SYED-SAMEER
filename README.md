# S Mohammad Syed Sameer

### AI / GenAI Engineer

I build production-oriented AI systems — RAG applications, AI agents,
document intelligence, voice AI, and business automation — with a focus
on reliability, evaluation, and real-world workflows.

---

## What I Build

- **AI & GenAI Systems** — LLM-backed applications built for reliability, not demos
- **RAG / Retrieval** — hybrid search, reranking, citation validation, honest abstention
- **Document Intelligence** — structured extraction with deterministic validation outside the model
- **Voice AI** — real-time speech pipelines with tool-calling and calendar integration
- **AI Automation** — multi-step agents with human approval gates on consequential actions

---

## Featured Engineering

### [KnowledgeOS](https://github.com/S-MOHAMMAD-SYED-SAMEER/knowledgeos)
Retrieval-grounded Q&A over internal documents — hybrid PostgreSQL + pgvector
search, a local reranker, and citations checked against the source document
before an answer is ever shown.
*Demonstrates: retrieval evaluation methodology, citation validation, honest abstention.*

### [DocIntel](https://github.com/S-MOHAMMAD-SYED-SAMEER/docintel)
Extracts invoices and purchase orders into validated schemas, checking every
field deterministically — arithmetic, dates, currency codes — outside the
model, then routes anything uncertain to a human review queue.
*Demonstrates: deterministic validation layered on LLM output, confidence-scored human review.*

### [VoiceDesk](https://github.com/S-MOHAMMAD-SYED-SAMEER/voicedesk)
An AI phone receptionist — real-time speech-to-text, tool-calling, and
calendar booking against a real PostgreSQL-backed schedule, with a browser
test harness for development without phone costs.
*Demonstrates: real-time voice pipelines, tool-calling agents, human escalation rules.*

### [Explainable ATS](https://github.com/S-MOHAMMAD-SYED-SAMEER/explainable-ats)
Ranks candidates against a job spec using only evidence quoted verbatim from
their resume, with personal details redacted before the model ever sees the
text and every recruiter decision kept on an append-only audit trail.
*Demonstrates: explainable AI, evidence grounding and verification, auditable decisions.*

### [Inbox CRM Agent](https://github.com/S-MOHAMMAD-SYED-SAMEER/inbox-crm-agent)
Reads inbound business email, resolves it against CRM records, and drafts
the next action — with a human approval gate on anything consequential and
outbound sending disabled until a real provider is wired in.
*Demonstrates: multi-step agent orchestration, human-in-the-loop safety, idempotent state changes.*

### [Sales Recovery Agent](https://github.com/S-MOHAMMAD-SYED-SAMEER/sales-recovery-agent)
A support agent for e-commerce stores that separates "what the policy says"
(RAG) from "what's true right now" (live tool calls), with proactive-signal
detection and guardrails constraining what it's allowed to claim.
*Demonstrates: RAG + tool-calling agent design, evaluation harness, guardrail engineering.*

---

## Engineering Stack

| | |
|---|---|
| **AI / GenAI** | LLMs (Claude, Gemini) · RAG · Embeddings · Vector Search (pgvector) · Tool-calling Agents · Evaluation |
| **Backend** | Python · FastAPI · Node.js · TypeScript · PostgreSQL · SQLite |
| **Frontend** | React · TypeScript · Vite · Tailwind CSS |
| **Infrastructure** | Docker · GitHub Actions · CI/CD |

---

## Engineering Approach

- **Evidence grounding** — citations and quotes checked against the source, not trusted from the model
- **Deterministic validation over model trust** — business rules verified in code
- **Evaluation as a first-class artifact** — dedicated evaluation harnesses
- **Observability** — measurable request behavior such as cost and latency
- **Human review where it matters** — confidence-routed review queues and approval gates

---

## Available For

- AI / GenAI Engineering
- AI Workflow Automation
- RAG Applications
- AI Agents
- Document Intelligence
- Business Process Automation

---

## Current Focus

Building reliable AI systems that hold up past the demo — with the
evaluation and validation layers that make them trustworthy enough to
hand over.

---

## Connect

- **LinkedIn:** https://www.linkedin.com/in/mohammad-syed-sameer-s
- **Portfolio:** https://porfolio-sigma-woad.vercel.app/
- **GitHub:** https://github.com/S-MOHAMMAD-SYED-SAMEER
