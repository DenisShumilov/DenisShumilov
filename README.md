# Denys Shumilov

I build **evidence-first, safety-gated AI tooling**. Core thesis: **the intelligence is in the scaffold, not the model** — reliability comes from rules, roles, gates, and runtime checks around the LLM, not from the LLM itself.

## Flagship — UAV Readiness & Evidence Copilot

**[Try the live demo (10 seconds, no install)](https://denisshumilov.github.io/uav-readiness-evidence-copilot/)** · [Repo](https://github.com/DenisShumilov/uav-readiness-evidence-copilot)

An evidence engine for UAV / robotics documentation: it derives each claim's status from evidence instead of trusting the reviewer's label.

- `no evidence -> locked` — and a derived cross-document contradiction blocks the verdict even when every row is hand-marked "verified" (the conflict demo scores **49/100 Blocked**)
- Runs on your own docs: `npx github:DenisShumilov/uav-readiness-evidence-copilot check ./docs`, or as a GitHub Action with SARIF output for code scanning
- Built by a scaffold of 10 Claude subagents, 7 skills, and a **tested runtime gate** that blocks unsafe edits — [how it was built](https://github.com/DenisShumilov/uav-readiness-evidence-copilot/blob/main/docs/scaffold.en.md)
- Self-audits its own documentation in CI with 10 derived checks: a stale score or a missing bilingual twin fails the build
- TypeScript monorepo · 94 tests · bilingual EN/UK · [standards crosswalk](https://github.com/DenisShumilov/uav-readiness-evidence-copilot/blob/main/docs/standards.en.md) to mil-tech documentation practice

## Also building

**[ChainPrompt AI](https://github.com/DenisShumilov/chainprompt-ai)** — a safety-scaffolded AI copilot for DAW insert chains (C++ / VST3). Same philosophy, different domain: fail-closed gates, AI output validated against the real installed-plugin inventory, user edits preserved.

## Currently

Open to roles in **AI tooling / agent infrastructure / defense-tech documentation & evidence systems** — especially teams in the Ukrainian and European defense-tech ecosystem.

## Contact

[LinkedIn](https://www.linkedin.com/in/denis-shumilov/) · shumilov1999@gmail.com
