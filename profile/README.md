<p align="center">
  <img src="https://github.com/user-attachments/assets/ff43ca6a-ffde-4aff-9ff9-eec3897d0d02" alt="Rhesis AI Logo" height="80">
</p>

# Rhesis: Collaborative Testing for LLM & Agentic Applications

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

<h3 align="center">More than just evals.<br><strong>Collaborative agent testing for teams.</strong></h3>

<p align="center">
Generate tests from requirements, simulate conversation flows, detect adversarial behaviors, evaluate with 60+ metrics, and trace failures with OpenTelemetry. Engineers and domain experts, working together.
</p>

<p align="center">
  <a href="https://rhesis.ai/?video=open" target="_blank">
    <img src="https://raw.githubusercontent.com/rhesis-ai/rhesis/main/.github/images/GH_Short_Demo.png"
         loading="lazy"
         width="1080"
         alt="Rhesis Platform Overview - Click to watch demo">
  </a>
</p>

---

## What Rhesis does

<p align="center">
  <img src="https://raw.githubusercontent.com/rhesis-ai/rhesis/main/.github/images/GH_Features.png"
       loading="lazy"
       width="1080"
       alt="Rhesis Core Features">
</p>

| | |
|---|---|
| **Test generation** | Describe requirements in plain language. Rhesis generates hundreds of test scenarios, including edge cases and adversarial prompts, from your connected context sources. |
| **Conversation simulation** | **Penelope** runs realistic multi-turn dialogues to test context retention, role adherence, and coherence across extended interactions. |
| **Adversarial testing** | **Polyphemus** and [garak](https://github.com/leondz/garak) probe for jailbreaks, prompt injection, PII leakage, and harmful content generation. |
| **60+ pre-built metrics** | RAGAS, DeepEval, and Garak metrics, plus custom LLM-as-Judge evaluations — all with reasoning explanations. |
| **Traces & observability** | OpenTelemetry-based tracing, with automatic instrumentation for LangChain, LangGraph, Microsoft Agent Framework, and OpenInference frameworks. |
| **Bring your own model** | Any provider through [LiteLLM](https://github.com/BerriAI/litellm) — OpenAI, Anthropic, Gemini, Mistral, Ollama, vLLM, and 100+ more. |

Testing shouldn't be limited to engineers. Legal teams understand compliance requirements, marketing knows the brand guidelines, and domain experts spot the edge cases. Rhesis lets everyone contribute their expertise without writing code, then turns it into automated test runs via UI, SDK, or CI/CD.

---

## Get started

**Cloud** — [app.rhesis.ai](https://app.rhesis.ai). Managed service, just connect your app.

**Self-hosted** — Docker, in about five minutes:

```bash
git clone https://github.com/rhesis-ai/rhesis.git && cd rhesis && ./rh start
```

**Python SDK** — code-first testing inside your own pipeline:

```bash
pip install rhesis-sdk
```

Everything lives in the [rhesis monorepo](https://github.com/rhesis-ai/rhesis); full guides are in the [documentation](https://docs.rhesis.ai).

---

## Open source

[MIT licensed](https://github.com/rhesis-ai/rhesis/blob/main/LICENSE), with no plans to relicense core features. The enterprise edition lives in separate `ee/` folders.

We built Rhesis because existing LLM testing tools didn't meet our needs for testing agentic applications. If you face the same challenges, [contributions](https://github.com/rhesis-ai/rhesis/blob/main/CONTRIBUTING.md) are welcome.

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
