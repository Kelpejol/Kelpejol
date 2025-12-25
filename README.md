# 👋 Hi, I’m Kelpejol

### Software Engineer — Distributed Systems | AI Infrastructure

I build **infrastructure systems** with a focus on **control, reliability, observability, and correctness**.  
My work centers on making complex, stateful systems — especially AI-driven ones — *operable* in the real world.

---

## 🧠 Engineering Focus

I care deeply about:
- **Control planes and orchestration** for complex systems  
- **Durable state, replayability, and auditability**  
- **Operational safety**: retries, fallbacks, policies, and human intervention  
- **Clear system boundaries and explicit tradeoffs**

I tend to work close to the metal of system behavior: execution flow, failure modes, state transitions, and observability.

---

## 🛠️ Technical Stack

**Languages**
- Python (primary)
- TypeScript / JavaScript
- Solidity
- Go (working proficiency)

**Systems & Tooling**
- Node.js, Docker
- CI/CD with GitHub Actions
- Structured logging & tracing
- API and workflow orchestration

**Domains**
- AI / LLM tooling and runtime controls  
- Distributed execution & workflow systems  
- On-chain → off-chain data pipelines  

---

## 📌 Current Core Project

### **Terra — Agent & Tool Control Plane**

Terra is a **decoupled control plane** for orchestrating and operating tools and agents.

It focuses on problems that show up *after* agents exist:
- Reliable execution
- Durable run state
- Retries, fallbacks, and recovery
- Human-in-the-loop approvals
- Full observability and deterministic replay

**Engineering emphasis**
- Explicit state modeling  
- Append-only execution traces  
- Runtime decision orchestration  
- Policy-backed execution controls  

This project reflects how I approach systems design: start from failure modes, operational needs, and observability — not just happy-path execution.

---

## 🧩 Other Notable Work

| Project | Description | Focus |
|-------|-------------|-------|
| **policy-aware-prompt-compression** | Prompt transformation with policy enforcement | Safety, cost control |
| **prompt-quality-gate** | LLM output validation & drift detection | Reliability |
| **eth-event-indexer** | Ethereum event indexing pipeline | Data correctness |
| **onchain-action-guard** | Policy-enforced smart contract example | Constraints & safety |
| **agent-control-plane-notes** | Design notes on orchestration systems | System design |

These projects are intentionally scoped and experimental — they exist to explore specific system concerns rather than to be full products.

---

## 📐 How I Think About Systems

- Prefer **explicit state** over implicit behavior  
- Design for **debuggability before scale**  
- Treat retries, failures, and human actions as first-class  
- Avoid hidden magic — systems should be explainable under pressure  

I value clarity over cleverness.

---

## 📊 GitHub Snapshot

![Metrics](https://metrics.lecoq.io/kelpejol)

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=kelpejol&theme=github-compact)

---

## 📫 Contact

- X / Twitter: https://x.com/kelpejol  
- Writing: https://medium.com/@kelpejol  

Open to conversations around **infrastructure-heavy engineering work**, system design, and difficult orchestration problems.

---

> *I enjoy working on the parts of systems that only matter once things start breaking.*
