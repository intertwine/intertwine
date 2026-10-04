# Bryan Young

I build AI agent systems that have to hold up in production: memory, evaluation, permissions, and human review.

- **Work:** Principal Software Engineer at Expel, building low-latency services over millions of security events and the APIs that put AI into analysts' workflows. A device-health detection model I worked on cut false positives by 40%.
- **Before:** led a 12-person AI group at MITRE (health analytics, federated learning, differential privacy); director at Asymmetrik, where my team built the first secure open-source FHIR server.
- **Now also:** founder of [Intertwine AI](https://intertwinesys.com/), helping teams turn agents into workflows people can trust.
- **Writing:** [Code & Context](https://codeandcontext.ai/), field notes on agent memory, evals, and keeping humans in control.

## Start here

- **[dspy-agent-skills](https://github.com/intertwine/dspy-agent-skills)**: tested DSPy 3.2.x skills for Claude Code and Codex CLI (fundamentals, evaluation, GEPA, BetterTogether, RLM), with validated end-to-end examples. 278★.
- **[security-verifiers](https://github.com/intertwine/security-verifiers)**: reinforcement-learning environments for cybersecurity with executable rewards (network-log anomaly detection, config verification), built during Prime Intellect's RL Residency.
- **[sops-encrypted-envs-mac](https://github.com/intertwine/sops-encrypted-envs-mac)**: turn plaintext `.env` files into SOPS + age encrypted dotenvs backed by Keychain, with an agent skill and a written threat model.

## Field notes worth reading

- [The night memory stopped me from doing the wrong thing](https://codeandcontext.ai/the-night-memory-stopped-me-from-doing-the-wrong-thing/): an agent, an unauthorized production change, and why approval gates and memory matter.
- [Building ClawFleet Academy, an ops control plane for agent fleets](https://codeandcontext.ai/building-clawfleet-academy-agent-ops/)
- [What local encrypted dotenvs protect, and when to move up](https://codeandcontext.ai/security-boundaries-for-local-encrypted-dotenvs/): threat-modeling secrets for agent workflows.
- [AI memory depends on where the agent lives](https://codeandcontext.ai/ai-memory-depends-on-where-the-agent-lives/)

## Retired projects, and what they taught me

I archived two projects in September 2026 after native agent platforms caught up with what they did. That was the right outcome.

- **[observational-memory](https://github.com/intertwine/observational-memory)**: local-first shared memory across Claude Code, Codex, Grok, Hermes and others. Lesson: memory is only useful when it's bounded, inspectable, and tied to where the agent runs. Once the platforms shipped native memory, the right move was to point users there.
- **[hive-orchestrator](https://github.com/intertwine/hive-orchestrator)** (Agent Hive): vendor-agnostic orchestration using Markdown files as shared state, with human-in-the-loop gates on GitHub Actions. Lesson: the durable parts were the human approval gates and the audit trail, not the scheduler.

Both repos stay up, read-only, as reference.

---

Also a professional bassoonist ([bryanyoung.info](https://bryanyoung.info)). Glad to compare notes on agent security, evals, or memory.
