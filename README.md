# Awesome-AI-Security-Posture-Management

# Top AI Security Posture Management (AI-SPM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Asset Inventory, Model Risk & Supply-Chain Security, LLM Posture, Guardrail Coverage & Continuous AI Security Assessment*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Security Posture Management (AI-SPM)**. These systems discover AI/ML assets (models, agents, endpoints, pipelines), assess configuration and supply-chain risk, map posture to frameworks (OWASP LLM Top 10, NIST AI RMF, MITRE ATLAS), and help organizations continuously improve AI security posture—analogous to CSPM for cloud, but for AI systems.

**Examples** include Protect AI, Lakera, HiddenLayer, Apex Security, NVIDIA AI Security, Robust Intelligence, CalypsoAI, Patronus AI, Fiddler AI, and Aporia (the category leaders and adjacent platforms).

**Open-source emphasis**: Full commercial AI-SPM platforms dominate enterprise inventory and governance. Open building blocks are strong for **model scanning** (ModelScan), **LLM red teaming** (garak), **guardrails**, and sample posture frameworks. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Protect AI](https://protectai.com/)**  
  AI security platform covering model scanning, supply-chain risk, MLOps security, and related posture and runtime capabilities for enterprise AI estates.

- **[HiddenLayer](https://www.hiddenlayer.com/)**  
  AI security focused on model integrity, adversarial risk, discovery, and runtime protection—supporting posture and defense across the AI lifecycle.

- **[Lakera, CalypsoAI, Robust Intelligence, Patronus AI](https://www.lakera.ai/)**  
  Platforms for LLM application security, evaluation, red teaming, and guardrail/posture controls that feed into broader AI risk management.

- **[Aporia, Fiddler AI](https://www.aporia.com/)**  
  ML and LLM observability platforms with monitoring, drift, and control features that contribute to ongoing AI security and reliability posture.

- **[NVIDIA AI Security / NeMo ecosystem](https://www.nvidia.com/)**  
  Enterprise AI stack with security tooling, guardrails, and guidance for securing deployed models and agents.

- **[Apex Security & other AI-SPM oriented vendors](https://protectai.com/)**  
  Additional solutions aimed at inventory, assessment, and governance of AI systems across the enterprise.

## Open-Source GitHub Projects

- **[ModelScan (Protect AI)](https://github.com/protectai/modelscan)**  
  Open-source scanner for model serialization attacks—checks Pickle, H5, SavedModel, and related formats for unsafe code before models are loaded in pipelines.

- **[garak (NVIDIA)](https://github.com/NVIDIA/garak)**  
  Open LLM vulnerability scanner and red-teaming framework—probes models for jailbreaks, leakage, and other failures aligned with security assessment workflows.

- **[AI scanner apps built on garak](https://github.com/0din-ai/ai-scanner)**  
  Open web applications that wrap garak-style probes for scheduled and on-demand model security assessments with scoring and reporting.

- **[AWS sample AI-SPM](https://github.com/aws-samples/sample-ai-security-posture-management)**  
  Open reference implementation of AI Security Posture Management patterns on AWS—discovery, posture rules (OWASP/NIST/MITRE-oriented), and defend integrations.

- **[NeMo Guardrails, LLM Guard, Guardrails AI](https://github.com/NVIDIA/NeMo-Guardrails)**  
  Open guardrail and filtering frameworks that enforce policy at runtime and form part of a measurable safety posture.

- **[Promptfoo & continuous LLM eval](https://github.com/promptfoo/promptfoo)**  
  Open evaluation and security testing in CI—useful for regression of safety and security posture over time.

- **[MLOps / model supply-chain open tools](https://github.com/search?q=model+security+OR+MLOps+security+OR+pickle+scan)**  
  Additional scanners and pipeline checks for model artifacts, dependencies, and training supply chain.

- **[AI threat modeling open modules](https://github.com/search?q=AI+threat+modeling+OR+LLM+threat+model+open+source)**  
  Open threat-modeling aids mapped to STRIDE, OWASP LLM Top 10, and similar frameworks for design-time posture.

### Additional Strong Open-Source Options

- **Model artifact security**: ModelScan before loading third-party or pipeline-produced models.
- **Adversarial assessment**: garak and derived scanners for ongoing LLM security posture checks.
- **Reference AI-SPM architectures**: Cloud-provider samples that map Observe → Govern → Defend.
- **Guardrail coverage as posture**: Track which apps have NeMo/LLM Guard–style controls enabled.
- **Composable stacks**: Inventory scripts + ModelScan + garak/Promptfoo + guardrails + SIEM for a DIY AI-SPM loop.
- Enterprise multi-cloud AI inventory, policy engines, and board-level reporting remain commercial strengths.

**Frameworks for building custom systems**:  
**ModelScan** + **garak** + **NeMo Guardrails / LLM Guard** + CI evaluation (**Promptfoo**) form a practical open posture toolkit.  
Cloud sample AI-SPM projects show how to structure discovery and policy.  
Commercial AI-SPM platforms (Protect AI, HiddenLayer, Lakera, CalypsoAI, etc.) deliver estate-wide inventory, continuous assessment, and governance workflows.  
Many organizations use open scanners in MLOps pipelines and commercial AI-SPM for visibility across business units. Fully open posture management is feasible for focused estates; large enterprises typically need commercial inventory and reporting.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI-SPM improves visibility and control but does not replace secure design, access control, or human oversight. Model scans and red-team scores are point-in-time; posture drifts as models and agents change.
- Open-source tools offer transparency and pipeline integration but require you to maintain inventory, policies, and response processes. Commercial platforms shift operational burden to the vendor. Align any approach with your AI governance and regulatory requirements.

---

**Made for AI security leads, MLOps engineers, and risk teams managing enterprise AI estates.**  
Let's expand open tools for AI security posture while recognizing the inventory depth and governance scale that leading commercial AI-SPM platforms deliver.
