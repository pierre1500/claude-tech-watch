# 👥 Key People — Decision Makers & Influencers

> Updated daily by the watch agent. Covers all 8 monitored domains. People are organized by sector. Each entry represents an active personality identified in the last 24h.
>
> **Domains:** Advanced DevSecOps • Distributed Backend • AI Engineering • Cybersecurity • Cloud • Realtime Systems • Data Engineering • AI Agents

---

## 🔐 Advanced DevSecOps

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Greg Ose | Principal Security Engineer | GitHub | CI/CD security, supply chain | Authored GitHub Actions 2026 security roadmap — defining the Layer-7 egress firewall and scoped secrets model that sets the CI/CD security standard | Co-published GitHub Actions 2026 security roadmap (March 26, 2026) — first native network perimeter control for CI/CD runners | 2026-05-09 |
| Stephen Glass | Security Engineering | GitHub | CI/CD security, workflow governance | Co-authored the roadmap establishing GitHub Actions' secure-by-default model with scoped secrets and runner endpoint monitoring | Co-published GitHub Actions 2026 security roadmap (March 26, 2026) alongside Greg Ose | 2026-05-09 |
| Dan Lorenc | CEO & Co-founder | Chainguard | CI/CD supply chain security, secure open-source artifact delivery | Launched Chainguard Actions and Chainguard Repository — AI-native continuous CI/CD security with SBOM + provenance attestation and automatic drift correction; first to apply reconciliation model to the CI/CD workflow layer | Announced Chainguard Actions and Chainguard Repository (March 17, 2026); 73,000+ Chainguard-built JS packages; AI-assisted security remediation for GitHub Actions continuously applied | 2026-05-20 |

---

## ⚙️ Distributed Backend

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Stephane Erbrech | Principal Software Engineer | Microsoft Azure | Kubernetes fleet management, cloud-native infrastructure | Defined governance-over-reconciliation model for fleet-scale Kubernetes — articulates where GitOps must be supplemented | Interviewed by The New Stack (May 2026) on Azure Kubernetes Fleet Manager and fleet-scale management architecture | 2026-05-08 |
| Pranay Prakash | Head of Workflows | Vercel | Durable execution, serverless orchestration, agent infrastructure | Designed the Vercel Workflows "framework-defined infrastructure" model — eliminating the separate orchestration service layer for long-running distributed systems | Authored Vercel durable execution programming model blog (May 2026); shipped Workflows 4 stable; roadmap includes snapshot-based runtime, global deployment, and lock primitives for Workflows 5 | 2026-05-19 |
| Jeffrey Ying | Software Engineer | Google | Kubernetes API server scalability, large-cluster optimization | Authored KEP-5866 (server-side sharded list and watch for Kubernetes v1.36) — solving the bandwidth-multiplication scaling paradox for controllers watching high-cardinality AI cluster resources | Published Kubernetes v1.36 alpha feature blog post (May 6, 2026); designed the FNV-1a hash-range sharding mechanism and `shardSelector` ListOptions API | 2026-05-19 |

---

## 🤖 AI Engineering

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Adam Karon | COO & GM Cloud Technology | Akamai | Distributed AI inference, edge cloud infrastructure | Executing Akamai's strategic pivot to AI inference — the $1.8B / 7-year Anthropic deal validates edge-distributed inference as a frontier architecture | Led Akamai Q1 2026 results and AI cloud strategy; $1.8B Anthropic inference deal announced May 8-9, 2026 | 2026-05-09 |
| Junchen Jiang | Researcher / LMCache Lead | University of Chicago / LMCache | Inference-time data infrastructure, KV cache architecture | First to articulate "Inference State Object" as a new abstraction replacing the "KV cache" framing — redefining how systems teams think about persistence, governance, and economics of LLM serving | Published "Stop Calling It KV Cache" (April 28, 2026); presented at NVIDIA GTC first-ever KV cache industry tutorial; LMCache integration with Amazon SageMaker HyperPod shipped | 2026-05-19 |

---

## 🛡️ Cybersecurity

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Dario Amodei | CEO & Co-founder | Anthropic | AI safety, frontier AI governance | Led announcement of Mythos Preview + Project Glasswing — the most significant public AI cybersecurity action by any lab | Announced Claude Mythos Preview and Project Glasswing (Apr 7, 2026); detailed follow-up on offensive/defensive AI capabilities | 2026-05-08 |
| Derek Manky | Chief Security Strategist & Global VP Threat Intelligence | Fortinet FortiGuard Labs | Threat intelligence, AI-enabled cybercrime | Published Fortinet 2026 Global Threat Landscape Report — 389% YoY increase in ransomware victims tied to agentic AI | Published 2026 Global Threat Landscape Report (May 8, 2026) | 2026-05-08 |
| Roi Nisimi | Security Researcher | Orca Security | AI agent security, supply chain security | Discovered critical structural attack primitives in AI agent skills marketplace (bait-and-switch, nested injection, delayed weaponization) | Published "Skill Issues" research (May 5, 2026) — 3 end-to-end attack flows passing platform security audits | 2026-05-08 |
| Hyunwoo Kim (@v4bel) | Independent Security Researcher | — | Linux kernel security, page-cache vulnerability research | Discovered Dirty Frag (CVE-2026-43284 + CVE-2026-43500) — second universal Linux LPE in 10 days; CopyFail mitigation does NOT protect against this chain | Disclosed Dirty Frag on oss-security (May 7, 2026); published full PoC + technical writeup at dirtyfrag.io after embargo was broken by 3rd party | 2026-05-09 |
| John Hultquist | Chief Analyst | Google Threat Intelligence Group (GTIG) | AI-assisted threat intelligence, cybercrime analysis | Led the GTIG report documenting the first confirmed AI-generated zero-day exploit — defining the AI cybersecurity arms race narrative with operational evidence rather than speculation | Published GTIG AI threat report (May 11, 2026); coined "industrial-scale application of generative models within adversarial workflows"; quoted on criminal AI zero-day operational implications | 2026-05-19 |
| Rob Thomas | SVP Software & Chief Commercial Officer | IBM | AI-powered enterprise security, hybrid cloud security at scale | Leading IBM's AI-era security portfolio expansion including IBM Concert (unified app/infra/network signals) and IBM Autonomous Security multi-agent service; key architect of IBM's Project Glasswing contribution model | Announced IBM Concert, IBM Autonomous Security multi-agent service, and IBM's Glasswing membership (May 19, 2026); leads coordinated disclosure and upstream open-source patching for critical infrastructure | 2026-05-20 |
| Taesoo Kim | VP, Security Research (Agentic Security) | Microsoft | Autonomous vulnerability discovery, AI-driven offensive security, large-scale code analysis | Built and published MDASH — the first 100+ multi-agent system achieving zero-false-positive production vulnerability discovery in Windows-class codebases; DARPA AIxCC $6M winner (Team Atlanta at Georgia Tech) | Published MDASH system (May 12, 2026); found 16 Windows vulnerabilities including 4 critical RCEs in TCP/IP/IKEv2/Netlogon/DNS; enterprise preview June 2026; authored "durable advantage is in the agentic system" principle | 2026-05-21 |
| Marc Spitler | Senior Risk Analyst / DBIR Co-author | Verizon Business | Large-scale breach analysis, threat intelligence, vulnerability exploitation patterns | Co-authored the 2026 DBIR — the definitive annual breach dataset; key analyst behind the finding that vulnerability exploitation overtook credential abuse as #1 initial access vector for first time in 19-year DBIR history | Published 2026 DBIR (May 20, 2026); co-authored findings on 31% exploitation vs 13% credential abuse and CISA KEV remediation rate decline (38% → 26%) | 2026-05-21 |

---

## ☁️ Cloud

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Peter Griffiths | Chairman | Argyll Data Development | Sovereign AI infrastructure, UK digital independence | Launched the first UK sovereign AI inference cloud using non-GPU (SambaNova RDU) architecture with renewable energy | Launched Argyll sovereign AI cloud (May 7, 2026) — UK-jurisdiction AI inference for regulated industries | 2026-05-08 |
| Matthew Prince | Co-founder & CEO | Cloudflare | Agentic AI infrastructure, cloud operations strategy | First major tech CEO to publicly restructure a company's workforce around agentic AI productivity — +600% internal AI usage in 3 months → 1,100 layoffs | Announced Q1 2026 earnings + 12% workforce reduction (May 8, 2026); co-authored "agentic era" restructuring letter | 2026-05-09 |
| Michelle Zatlyn | Co-founder & COO | Cloudflare | Platform strategy, agentic AI operations | Co-architect of Cloudflare's agentic-first operational model; first COO to frame a major workforce restructuring explicitly as an AI operational model transition | Co-authored internal memo + public letter on Cloudflare's AI-first restructuring (May 8, 2026) | 2026-05-09 |

---

## ⚡ Realtime Systems

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|

---

## 📊 Data Engineering

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|

---

## 🧠 AI Agents

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Idit Levine | Founder & CEO | Solo.io | Agentic infrastructure governance, cloud-native AI | Built and donated agentregistry to CNCF; launched agentevals — first to contribute all four layers of a coherent CNCF agentic governance stack | Announced agentregistry CNCF contribution + agentevals launch at KubeCon Amsterdam (March 25, 2026) | 2026-05-09 |
| Geoffrey Mattson | CEO | SecureAuth | Zero-trust identity for AI agents, Agent Detection and Response (ADR) | Launched the Agentic Authority Platform — first enterprise zero-trust control layer for AI agents with behavioral baselines, drift detection, and automatic revocation; introduced ADR as a distinct security category mirroring EDR for agents | Announced Agentic Authority Platform (May 19, 2026); defines the governance architecture above MCP: no standing privileges, federated credentials, real-time context-aware authorization | 2026-05-20 |
| Mark van Oppen | Chief Revenue Officer | SecureAuth | Enterprise identity security, cloud-native infrastructure at scale (IBM, Heptio, VMware, FusionAuth) | Appointed to scale enterprise adoption of zero-trust agent identity security; brings commercial rigor across cloud, Kubernetes, and identity to the agent governance market at the moment enterprises must govern AI agent behavior | Appointed CRO at SecureAuth (May 19, 2026); will lead global sales for Agentic Authority Platform across workforce, customer, and AI agent security | 2026-05-20 |
