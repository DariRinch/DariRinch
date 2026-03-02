# Dari Rinch · KeyKeeper_42

**Founder, Fronesis Labs** — building deterministic audit infrastructure for agentic AI systems  
(**DCL · cryptographic verification · AI compliance**)

AI Systems Architect · Siberia, Russia  
Patent applicant (6 patent filings with Rospatent) · Independent researcher

---

## What I'm Building

Most agentic systems trust their agents on the output alone.  
I build the layer that checks whether the work was actually done.

**Core thesis:** An AI agent doesn't *execute* a task — it generates text that *looks like* execution. Without a deterministic verification layer, there is no difference between a completed task and a fabricated one.

This is not a model alignment problem. It is an architecture problem.

**Deterministic Commitment Layer (DCL)** addresses it by introducing three primitives:

- **Commitment Protocol** — cryptographic binding to inputs and declared tool use *before* execution begins
- **Execution Trace Verification** — independent signing of every tool call, decoupled from the agent's self-report
- **Cryptographic Audit Log** — an immutable chain linking commitment → trace → result, replayable and tamper-evident

If you can't replay the execution, you can't audit it.  
If you can't audit it, you can't deploy it in a regulated environment.

---

## Open Repositories

### [dcl-eval-pipeline-demo](https://github.com/KeyKeeper42/dcl-eval-pipeline-demo)

Working implementation of the DCL evaluation pipeline:
- Jupyter notebooks with end-to-end verification examples
- FastAPI endpoints for commitment and trace verification
- Docker containerization + CI/CD
- Python · FastAPI · Docker · GitHub Actions

---

## Intellectual Property

Six patent applications filed through Rospatent covering the DCL technology stack.  
IP terms negotiated: core DCL architecture remains author's property under license.

Representative systems:
- **DCL core** — deterministic commitment and trace verification protocol
- **Audit chain primitives** — cryptographic log construction for multi-agent pipelines
- **Compliance adapter layer** — mapping DCL outputs to FSTEK and regulated-industry requirements

---

## Writing

  *Deterministic verification layer vs. fabricated execution in agentic systems*

- CVE-HUM trilogy *(in progress)* — applying cybersecurity frameworks to analyze civilizational vulnerabilities. First volume: *No Threats Detected*. Submitted to Zer0 Books, MIT Press.

---

## Looking For

- **Pilot deployments** — regulated industries where agent auditability is a hard requirement (finance, legal, government)
- **Standards discussion** — researchers and architects working on deterministic governance or formal verification for AI
- **Whitepaper feedback** — DCL full technical specification in preparation, early access on request

---

## Connect

- 🐱 **GitHub**: [DariRinch](https://github.com/DariRinch)
- 📝 **Habr**: [@DariRinch](https://habr.com)
- 💼 **Fronesis Labs**: [github.com/Fronesis-Labs](https://github.com/Fronesis-Labs)
---

> Verification is not a feature.  
> It is a precondition for deployment.  
> — Dari Rinch
