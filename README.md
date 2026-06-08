# Awesome AI Security [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

> A curated list of tools, frameworks, papers, and resources for AI/ML security testing, adversarial machine learning, LLM red-teaming, and agentic AI safety.

Contributions welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## Contents

- [Frameworks](#frameworks)
- [LLM Red-Teaming Tools](#llm-red-teaming-tools)
- [Adversarial ML Libraries](#adversarial-ml-libraries)
- [Agentic AI Security](#agentic-ai-security)
- [Guardrails & Runtime Protection](#guardrails--runtime-protection)
- [Compliance & Governance](#compliance--governance)
- [Vulnerability Databases](#vulnerability-databases)
- [Standards & Guidelines](#standards--guidelines)
- [Research Papers](#research-papers)
- [Courses & Training](#courses--training)
- [Conferences & Events](#conferences--events)

---

## Frameworks

Comprehensive security testing frameworks that cover multiple attack categories.

| Tool | Stars | Coverage | License |
|------|-------|----------|---------|
| [**Tessera**](https://github.com/tessera-ops/tessera) | ![Stars](https://img.shields.io/github/stars/tessera-ops/tessera?style=flat) | 42 OWASP tests, 5 categories (MOD/APP/INF/DAT/AGT), full Agentic AI Top 10 | Apache 2.0 |
| [Garak](https://github.com/NVIDIA/garak) | ![Stars](https://img.shields.io/github/stars/NVIDIA/garak?style=flat) | LLM vulnerability probing | Apache 2.0 |
| [Counterfit](https://github.com/Azure/counterfit) | ![Stars](https://img.shields.io/github/stars/Azure/counterfit?style=flat) | Adversarial ML attack automation | MIT |
| [AIShield](https://github.com/bosch-aisecurity/aishield) | ![Stars](https://img.shields.io/github/stars/bosch-aisecurity/aishield?style=flat) | ML model security | Apache 2.0 |

## LLM Red-Teaming Tools

Tools specifically designed for testing Large Language Models.

| Tool | Stars | Focus | License |
|------|-------|-------|---------|
| [**Tessera**](https://github.com/tessera-ops/tessera) | ![Stars](https://img.shields.io/github/stars/tessera-ops/tessera?style=flat) | 14 APP tests + 10 AGT tests, 3-phase methodology | Apache 2.0 |
| [Garak](https://github.com/NVIDIA/garak) | ![Stars](https://img.shields.io/github/stars/NVIDIA/garak?style=flat) | LLM vulnerability probing and scanning | Apache 2.0 |
| [PyRIT](https://github.com/Azure/PyRIT) | ![Stars](https://img.shields.io/github/stars/Azure/PyRIT?style=flat) | Python Risk Identification Toolkit for GenAI (Microsoft) | MIT |
| [Agentic Radar](https://github.com/splx-ai/agentic-radar) | ![Stars](https://img.shields.io/github/stars/splx-ai/agentic-radar?style=flat) | Agentic workflow security scanner | Apache 2.0 |
| [ClawMoat](https://github.com/darfaz/clawmoat) | ![Stars](https://img.shields.io/github/stars/darfaz/clawmoat?style=flat) | Runtime security scanner for AI agents | MIT |
| [LLMFuzzer](https://github.com/mnns/LLMFuzzer) | ![Stars](https://img.shields.io/github/stars/mnns/LLMFuzzer?style=flat) | Fuzzing framework for LLMs | MIT |
| [Rebuff](https://github.com/protectai/rebuff) | ![Stars](https://img.shields.io/github/stars/protectai/rebuff?style=flat) | Prompt injection detection | Apache 2.0 |

## Adversarial ML Libraries

Libraries for adversarial attacks and defenses on ML models.

| Tool | Stars | Focus | License |
|------|-------|-------|---------|
| [IBM ART](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | ![Stars](https://img.shields.io/github/stars/Trusted-AI/adversarial-robustness-toolbox?style=flat) | Adversarial attacks, defenses, certifications | MIT |
| [Foolbox](https://github.com/bethgelab/foolbox) | ![Stars](https://img.shields.io/github/stars/bethgelab/foolbox?style=flat) | Adversarial perturbations | MIT |
| [CleverHans](https://github.com/cleverhans-lab/cleverhans) | ![Stars](https://img.shields.io/github/stars/cleverhans-lab/cleverhans?style=flat) | Adversarial examples for ML | MIT |
| [TextAttack](https://github.com/QData/TextAttack) | ![Stars](https://img.shields.io/github/stars/QData/TextAttack?style=flat) | NLP adversarial attacks | MIT |
| [AugLy](https://github.com/facebookresearch/AugLy) | ![Stars](https://img.shields.io/github/stars/facebookresearch/AugLy?style=flat) | Data augmentation for robustness testing | MIT |

## Agentic AI Security

Tools and resources specific to AI agent security — the OWASP Top 10 for Agentic Applications (ASI 2026).

| ASI Risk | Description | Test Tools |
|----------|-------------|------------|
| ASI-01 | Agent Goal Hijacking | [Tessera AGT-03](https://github.com/tessera-ops/tessera) |
| ASI-02 | Tool Misuse | [Tessera AGT-02](https://github.com/tessera-ops/tessera) |
| ASI-03 | Identity & Privilege Abuse | [Tessera AGT-05](https://github.com/tessera-ops/tessera) |
| ASI-04 | Agentic Supply Chain | [Tessera AGT-01](https://github.com/tessera-ops/tessera) |
| ASI-05 | Unexpected Code Execution | [Tessera AGT-06](https://github.com/tessera-ops/tessera) |
| ASI-06 | Memory & Context Poisoning | [Tessera AGT-04](https://github.com/tessera-ops/tessera) |
| ASI-07 | Insecure Inter-Agent Comms | [Tessera AGT-07](https://github.com/tessera-ops/tessera) |
| ASI-08 | Cascading Failures | [Tessera AGT-08](https://github.com/tessera-ops/tessera) |
| ASI-09 | Human-Agent Trust Exploitation | [Tessera AGT-09](https://github.com/tessera-ops/tessera) |
| ASI-10 | Rogue Agents | [Tessera AGT-10](https://github.com/tessera-ops/tessera) |

## Guardrails & Runtime Protection

Tools that protect AI systems at runtime.

| Tool | Stars | Focus | License |
|------|-------|-------|---------|
| [LLM Guard](https://github.com/protectai/llm-guard) | ![Stars](https://img.shields.io/github/stars/protectai/llm-guard?style=flat) | Input/output guardrails for LLMs | MIT |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | ![Stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails?style=flat) | Programmable guardrails for LLM apps | Apache 2.0 |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | ![Stars](https://img.shields.io/github/stars/guardrails-ai/guardrails?style=flat) | Input/output validation for LLMs | Apache 2.0 |
| [Lakera Guard](https://www.lakera.ai/) | — | Prompt injection detection API | SaaS |
| [Detoxify](https://github.com/unitaryai/detoxify) | ![Stars](https://img.shields.io/github/stars/unitaryai/detoxify?style=flat) | Toxicity detection | Apache 2.0 |

| [TWZRD Agent Intel](https://intel.twzrd.xyz) | — | On-chain wallet trust scoring for Solana agents before x402 micropayments. Free MCP tools: `score_agent`, `preflight_check`. | Free (x402 for receipts) |

## Compliance & Governance

Frameworks and tools for AI regulatory compliance.

| Resource | Type | Coverage |
|----------|------|----------|
| [**Tessera** `--format compliance`](https://github.com/tessera-ops/tessera) | Tool | EU AI Act (42-test mapping), NIST AI RMF, SOC 2, ISO 27001 |
| [EU AI Act](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) | Regulation | EU regulation on AI systems (deadline: Aug 2, 2026) |
| [NIST AI RMF](https://airc.nist.gov/AI_RMF_Interactivity) | Framework | US AI risk management framework |
| [ISO/IEC 42001](https://www.iso.org/standard/81230.html) | Standard | AI management system standard |
| [Fairlearn](https://github.com/fairlearn/fairlearn) | Tool | ML fairness assessment |
| [AI Verify](https://github.com/aiverify-foundation/aiverify) | Tool | AI governance testing framework (Singapore) |

## Vulnerability Databases

| Resource | Description |
|----------|-------------|
| [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Top 10 risks for LLM-based applications |
| [OWASP Top 10 for Agentic Applications (ASI 2026)](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Top 10 risks for AI agent systems |
| [MITRE ATLAS](https://atlas.mitre.org/) | Adversarial Threat Landscape for AI Systems |
| [AI Incident Database](https://incidentdatabase.ai/) | Database of AI-related incidents and failures |
| [AVID](https://avidml.org/) | AI Vulnerability Database |

## Standards & Guidelines

| Standard | Organization | Focus |
|----------|-------------|-------|
| [OWASP AI Testing Guide](https://owasp.org/www-project-ai-testing-guide/) | OWASP | AI security testing methodology |
| [NIST AI 100-2](https://csrc.nist.gov/pubs/ai/100/2/e2025/final) | NIST | Adversarial ML taxonomy |
| [ISO/IEC 27090](https://www.iso.org/standard/56581.html) | ISO | Cybersecurity for AI |
| [EU AI Act](https://artificialintelligenceact.eu/) | European Union | AI regulation |
| [Singapore AI Verify](https://aiverifyfoundation.sg/) | IMDA | AI governance framework |

## Research Papers

### Surveys
- [A Survey of Adversarial Machine Learning in Cybersecurity](https://arxiv.org/abs/2007.02407) — comprehensive overview of adversarial ML
- [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) — foundational prompt injection research
- [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483) — analysis of LLM jailbreak techniques

### Agentic AI Security
- [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://arxiv.org/abs/2407.19354)
- [Agent Security Bench (ASB): Formalizing and Benchmarking Attacks and Defenses in LLM-based Agents](https://arxiv.org/abs/2410.02644)

### Prompt Injection
- [Ignore This Title and HackAPrompt: Exposing Systemic Weaknesses of LLMs](https://arxiv.org/abs/2310.04451)
- [Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game](https://arxiv.org/abs/2311.01011)

## Courses & Training

| Course | Provider | Topic |
|--------|----------|-------|
| [AI Red Teaming](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/red-teaming) | Microsoft | Red teaming AI systems |
| [Adversarial Machine Learning](https://adversarial-ml-tutorial.org/) | Academic | Adversarial ML fundamentals |
| [LLM Security](https://llmsecurity.net/) | Community | LLM-specific security |
| [Damn Vulnerable LLM Agent](https://github.com/WithSecureLabs/damn-vulnerable-llm-agent) | WithSecure | Hands-on LLM agent security |

## Conferences & Events

| Event | Focus |
|-------|-------|
| [OWASP Global AppSec](https://owasp.org/events/) | Application security (AI track) |
| [DEF CON AI Village](https://aivillage.org/) | AI security research |
| [NeurIPS ML Safety Workshop](https://neurips.cc/) | ML safety and robustness |
| [IEEE SaTML](https://satml.org/) | Security and trustworthy ML |

---

## Contributing

Contributions welcome! Please submit a PR with:
- Tool name, link, and brief description
- Star badge if it's a GitHub project
- Correct category placement

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
