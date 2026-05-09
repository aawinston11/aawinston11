# Andre Winston II

Security operations engineer (8 years), CISSP. Building AI-augmented detection and response — agentic triage, prompt-injection-resistant copilots, MCP-driven SecOps tooling, and the detection-as-code and host hardening that hold it up.

**Currently:** open to **Senior Security Operations / Security Engineering** roles where AI-augmented detection and response is part of the brief.

---

## 🔧 Flagship: [security-engineering-portfolio](https://github.com/aawinston11/security-engineering-portfolio)

Three pillars — agents, detection, foundations. AI-assisted, human-validated. Synthetic data only; nothing here references any employer system or production telemetry.

![MCP demo: spawn server, exercise 5 SecOps tools, structured output prints](https://raw.githubusercontent.com/aawinston11/security-engineering-portfolio/main/agents/mcp-security-tooling/docs/demo.gif)

| Project | Headline |
|---|---|
| [**MCP Security Tooling Server**](https://github.com/aawinston11/security-engineering-portfolio/tree/main/agents/mcp-security-tooling) | MCP server exposing a synthetic SIEM/EDR API to LLM agents over stdio. **5 read tools**, HMAC-chained tamper-evident audit log, 18/18 tests. |
| [**LLM Alert Triage**](https://github.com/aawinston11/security-engineering-portfolio/tree/main/agents/llm-alert-triage) | Hybrid Anthropic + OpenAI agent over the MCP server. Untuned baseline: Anthropic **67% verdict accuracy / $0.26**, OpenAI 53% / $0.06. Three-iteration prompt-tuning arc surfaced a provider-asymmetric regression — [writeup](https://github.com/aawinston11/security-engineering-portfolio/blob/main/notes/writeups/cross-provider-prompt-asymmetry.md). |
| [**IR Copilot**](https://github.com/aawinston11/security-engineering-portfolio/tree/main/agents/ir-copilot) | Single-turn copilot that turns Slack-style incident transcripts into structured IR docs. Three-layer prompt-injection defense: **6/6 red-team cases held on both Anthropic + OpenAI**, 100% status accuracy on the happy path. |
| [**Detection-as-Code**](https://github.com/aawinston11/security-engineering-portfolio/tree/main/detection/detection-as-code) | 5 Sigma rules across 5 ATT&CK tactics with positive + negative log fixtures. In-process Sigma evaluator + purple-team runner. **15/15 positives matched, 0/14 false negatives.** ATT&CK Navigator coverage export, Splunk SPL conversion. |
| [**Linux Hardening Role**](https://github.com/aawinston11/security-engineering-portfolio/tree/main/foundations/linux-hardening-role) | Idempotent Ansible role for Ubuntu 22.04: SSH, UFW, PAM, auditd, fail2ban, kernel sysctl. Lynis baseline/post evidence + safe rollback. |

**Posture (post `/cso` audit, 2026-05-08):** SHA-pinned CI actions across all jobs · weekly Dependabot · gitleaks pre-commit hook · `main` branch-protected with required CI checks · 0 CVEs across all 4 Python projects · audit report committed.

---

## 📜 Credentials

- **CISSP** )https://www.credly.com/badges/5b34975a-f896-496c-b89e-d4bdda03f20a/public_url)
- [CompTIA Security+](https://www.credly.com/badges/49045bde-2514-4fd0-a440-6adefb3340c2/public_url)
- [Google Cybersecurity Professional](https://www.coursera.org/account/accomplishments/specialization/9VQ8ZZYCMCBR)

---

## 📨 Connect

- Email — winstoniiandre@gmail.com
<!-- TODO: add personal site URL if one is current -->
