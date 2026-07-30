<p align="center">
  <img src="https://raw.githubusercontent.com/rhesis-ai/rhesis/main/.github/images/GH-collaborate.png"
       loading="lazy"
       width="1920"
       alt="Rhesis: Get the feedback you need to improve your agents">
</p>

<p align="center">
  <a href="https://github.com/rhesis-ai/rhesis/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT%20%2B%20Enterprise-blue" alt="License">
  </a>
  <a href="https://pypi.org/project/rhesis-sdk/">
    <img src="https://img.shields.io/pypi/v/rhesis-sdk" alt="PyPI Version">
  </a>
  <a href="https://pypi.org/project/rhesis-sdk/">
    <img src="https://img.shields.io/pypi/pyversions/rhesis-sdk" alt="Python Versions">
  </a>
  <a href="https://codecov.io/gh/rhesis-ai/rhesis">
    <img src="https://codecov.io/gh/rhesis-ai/rhesis/graph/badge.svg?token=1XQV983JEJ" alt="codecov">
  </a>
  <a href="https://discord.rhesis.ai">
    <img src="https://img.shields.io/discord/1340989671601209408?color=7289da&label=Discord&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://www.linkedin.com/company/rhesis-ai">
    <img src="https://img.shields.io/badge/LinkedIn-Rhesis_AI-blue?logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://huggingface.co/rhesis">
    <img src="https://img.shields.io/badge/🤗-Rhesis-yellow" alt="Hugging Face">
  </a>
  <a href="https://docs.rhesis.ai">
    <img src="https://img.shields.io/badge/docs-rhesis.ai-blue" alt="Documentation">
  </a>
</p>

<p align="center">
  <a href="https://rhesis.ai"><strong>Website</strong></a> ·
  <a href="https://docs.rhesis.ai"><strong>Docs</strong></a> ·
  <a href="https://discord.rhesis.ai"><strong>Discord</strong></a> ·
  <a href="https://github.com/rhesis-ai/rhesis/blob/main/CHANGELOG.md"><strong>Changelog</strong></a>
</p>

<h3 align="center">Structured feedback and evals for AI agents.<br>
<strong>Open source · SaaS or self-hosted · UI, SDK, and MCP</strong></h3>

<p align="center">
Connect the agent you are building, share the link with your team, and get structured feedback from the people who know the right answers.
</p>

---

## Why Rhesis?

Most tools start with tests or traces. Rhesis starts one step earlier: the people who know what the
agent should answer are not the people building it, and their feedback rarely arrives in a form you
can act on.

- **Feedback that stays attached** — Every review sits on the test case and the agent version that produced it, not in a Slack thread
- **One pass/fail bar** — The whole team reviews against the same tests, and you measure against them
- **UI for reviewers, SDK and MCP for builders** — Same data, three ways in
- **From feedback to CI** — Recurring feedback becomes tests and metrics that run on every change

---

## How it works

**1. Connect the agent you are building.** Paste a public REST URL, or use the SDK connector — your
process opens an outbound WebSocket, so the agent works from your laptop or your VPC with no public
URL.

**2. Share the Rhesis link with your stakeholders.** Domain experts, product managers, and
reviewers open it in a browser. Nothing to install, no code.

**3. They put the agent to work.** They chat with the live agent in the playground, turn interesting
conversations into tests, run test sets, and leave pass/fail verdicts and comments down to the
individual metric or conversation turn.

**4. Pull that feedback back into development.** Read it from the SDK or REST API, or work with it
from Cursor, Claude Code, and other MCP clients. Fix the agent, run the same tests again.

**5. Agree on what the agent has to get right.** Each cycle, feedback that arrived as prose becomes
tests and metrics that check the same thing automatically.

---

## Who it’s for

| Role | How they use Rhesis |
|------|---------------------|
| **AI engineers** | Connect the agent, pull feedback and reviewed test sets into the SDK, CI, and MCP while you build |
| **Domain experts** | Try the agent, review its answers, say what is wrong and what a correct answer looks like. UI, no code |
| **Product managers** | Turn scattered feedback into tests, and see whether the agent improves against the PRD. UI or MCP |

---

## Capabilities

<p align="center">
  <img src="https://raw.githubusercontent.com/rhesis-ai/rhesis/main/.github/images/GH-capabilities.png"
       loading="lazy"
       width="1920"
       alt="Start with the feedback you already have and expand from there — review test results, inspect annotations, gain insights">
</p>

Nobody can review every case by hand. Once the first feedback is in, you can grow coverage from it:

- **Test generation** from your requirements, a PRD, or an uploaded file
- **Conversation simulation** with Penelope; **adversarial probing** with Polyphemus and [garak](https://github.com/leondz/garak)
- **60+ metrics** — RAGAS, DeepEval, garak, and custom LLM-as-Judge evaluators
- **Traces** linked to test results via OpenTelemetry

Generated tests are only as good as the requirements behind them, so connect the tools your
requirements already live in — Notion, GitHub, Jira, Confluence — and Rhesis writes tests from the
real thing. See [Tools](https://docs.rhesis.ai/docs/tools).

---

## Get started

### Cloud

[app.rhesis.ai](https://app.rhesis.ai) — managed service, connect your agent and invite your team.

### Local (Docker)

```bash
git clone https://github.com/rhesis-ai/rhesis.git && cd rhesis && ./rh start
```

Frontend at `localhost:3000`, API at `localhost:8080/docs`. For production self-hosting, see the
[deployment docs](https://docs.rhesis.ai/docs/deployment).

### From your own tools

```bash
pip install rhesis-sdk              # Python SDK: connector, synthesizers, metrics, tracing
npx skills add rhesis-ai/rhesis     # MCP and skills for Cursor, Claude Code, and others
```

Everything lives in the [rhesis monorepo](https://github.com/rhesis-ai/rhesis); full guides are in
the [documentation](https://docs.rhesis.ai).

---

## Open source

[MIT licensed](https://github.com/rhesis-ai/rhesis/blob/main/LICENSE). No plans to relicense core features. Enterprise features live in `ee/` and remain separate.

We built Rhesis because the feedback that mattered most kept getting stuck outside the development
loop. If you face the same problem, [contributions](https://github.com/rhesis-ai/rhesis/blob/main/CONTRIBUTING.md) are welcome.

---

## Funding acknowledgment

This project is funded by the German Federal Ministry of Research, Technology and Space (BMFTR) under the StartUpSecure initiative.

<p align="center">
  <img src="https://rhesis.ai/logos/bmftr-light-mode.webp" alt="Gefördert durch das Bundesministerium für Forschung, Technologie und Raumfahrt" height="80">
</p>

<p align="center">
  <em>Das diesem Projekt zugrundeliegende Vorhaben wird mit Mitteln des Bundesministeriums für Forschung, Technologie und Raumfahrt gefördert. Die Verantwortung für den Inhalt dieser Veröffentlichung liegt bei der Rhesis AI GmbH.</em>
</p>

---

<p align="center">
  <strong>Made with <img src="https://github.com/user-attachments/assets/598c2d81-572c-46bd-b718-dee32cdc749c" height="16" alt="Rhesis logo"> in Potsdam, Germany 🇩🇪</strong>
</p>

<p align="center">
  <a href="https://rhesis.ai">Learn more at rhesis.ai</a>
</p>
