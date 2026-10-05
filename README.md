### Harun Ercul — Senior AI Engineer, Istanbul

I build production AI infrastructure: multi-model orchestration, agentic systems,
and the unglamorous plumbing that makes LLMs cheap and reliable at scale.

---

**Shipped**

- **[JAI Portal](https://jaiportal.com)** — a global AI tools marketplace unifying 500+ models.
  Designed and built solo; serves users in 200+ countries at ~$60K monthly revenue.
  Hybrid inference across open-weight models, commercial APIs and in-house tools,
  with pay-per-use billing.

- **Chat.JAIPortal** — 100+ LLMs behind one interface. Chat Arena for side-by-side
  comparison of three models, an MCP-based agent that builds web apps without code,
  and 21+ native integrations.

- **[Libranotes](https://libranotes.ai)** — meeting intelligence. Bots that join
  Meet, Zoom and Teams from calendar events, diarized speech-to-text in 32 languages,
  and an agentic RAG layer that answers with cited sources. Built solo.

- **Reinforcement learning** — designed a custom RL model from scratch that became
  the technical core of a ~30M TL TÜBİTAK-funded R&D project.

- **50+ internal AI tools at Joygame** — automated marketing, ASO and live-ops
  across Wolfteam, Zula and mobile titles.

---

**Now building → [thriftllm](https://github.com/Harunercul/thriftllm)**

Cost-aware LLM routers rank models by `input_rate + output_rate`. Real workloads
aren't 1:1, and output is most of the bill. thriftllm computes the expected cost
of *this* request — forecast output length, tiered and cached rates — and picks
the cheapest provider that meets a quality and reliability policy.

Its cost model is verified against provider invoices, not just unit tests.
Pre-release; the benchmark is [pre-registered](https://github.com/Harunercul/thriftllm/blob/main/PRE-REGISTRATION.md)
before any number is published.

```bash
pip install thriftllm
```

---

Python · FastAPI · PyTorch · LLM orchestration · RAG · MCP · speech pipelines · Docker

[LinkedIn](https://www.linkedin.com/in/harun-ercul-5a49b8241)
