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
| Roy Gottlieb | CEO & Co-founder | Hopper | Software supply chain security, zero-CVE open source distribution | Founded the first commercial "trusted registry" with full SUPPLYSHIELD model — zero-CVE, malware-free components from a secured, continuously maintained registry with 24-hour vulnerability remediation SLA; Fortune 500 deployments live | Launched SUPPLYSHIELD (April 3, 2026) — zero-CVE open source supply layer with full dependency tree coverage; 24-hour CVE remediation SLA; first product taking full commercial responsibility for software supply chain security | 2026-05-28 |
| Alexis Wales | CISO | GitHub | CI/CD supply chain security, developer infrastructure incident response | Named the Nx Console v18.95.0 poisoned extension as root cause of GitHub's internal intrusion (~3,800 repositories exfiltrated); first CISO to publicly identify downstream AI lab victims (OpenAI, Grafana Labs, Mistral AI) in a major developer supply chain incident | Publicly disclosed Nx Console root cause (May 21, 2026); named downstream victims; confirmed the 18-minute exposure window was sufficient for full GitHub internal CI/CD lateral movement and developer secret exfiltration | 2026-05-29 |

---

## ⚙️ Distributed Backend

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Stephane Erbrech | Principal Software Engineer | Microsoft Azure | Kubernetes fleet management, cloud-native infrastructure | Defined governance-over-reconciliation model for fleet-scale Kubernetes — articulates where GitOps must be supplemented | Interviewed by The New Stack (May 2026) on Azure Kubernetes Fleet Manager and fleet-scale management architecture | 2026-05-08 |
| Pranay Prakash | Head of Workflows | Vercel | Durable execution, serverless orchestration, agent infrastructure | Designed the Vercel Workflows "framework-defined infrastructure" model — eliminating the separate orchestration service layer for long-running distributed systems | Authored Vercel durable execution programming model blog (May 2026); shipped Workflows 4 stable; roadmap includes snapshot-based runtime, global deployment, and lock primitives for Workflows 5 | 2026-05-19 |
| Jeffrey Ying | Software Engineer | Google | Kubernetes API server scalability, large-cluster optimization | Authored KEP-5866 (server-side sharded list and watch for Kubernetes v1.36) — solving the bandwidth-multiplication scaling paradox for controllers watching high-cardinality AI cluster resources | Published Kubernetes v1.36 alpha feature blog post (May 6, 2026); designed the FNV-1a hash-range sharding mechanism and `shardSelector` ListOptions API | 2026-05-19 |
| Adrian Chung | Software Engineer | Google Kubernetes Engine | Autonomous Kubernetes operations, intent-driven infrastructure design | Co-designed Kube-Agents — the autonomous intent-driven presentation layer for Kubernetes combining natural language, specialized agents, and existing `kubectl`/YAML interfaces in a single cluster | Co-authored Google Open Source Blog post on Kube-Agents (May 21, 2026); three-agent architecture for different stakeholder personas on live production clusters | 2026-05-28 |
| Abdelfettah Sghiouar | Cloud Native Advocate | Google Kubernetes Engine | Kubernetes ecosystem, cloud-native advocacy, AI workload orchestration | Key contributor to Kube-Agents design and open-source release; translates GKE infrastructure innovations into community-accessible engineering patterns for AI-native K8s operations | Co-authored Kube-Agents open source release (May 21, 2026); active advocate for intent-driven Kubernetes orchestration at scale for AI workloads | 2026-05-28 |

---

## 🤖 AI Engineering

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Adam Karon | COO & GM Cloud Technology | Akamai | Distributed AI inference, edge cloud infrastructure | Executing Akamai's strategic pivot to AI inference — the $1.8B / 7-year Anthropic deal validates edge-distributed inference as a frontier architecture | Led Akamai Q1 2026 results and AI cloud strategy; $1.8B Anthropic inference deal announced May 8-9, 2026 | 2026-05-09 |
| Junchen Jiang | Researcher / LMCache Lead | University of Chicago / LMCache | Inference-time data infrastructure, KV cache architecture | First to articulate "Inference State Object" as a new abstraction replacing the "KV cache" framing — redefining how systems teams think about persistence, governance, and economics of LLM serving | Published "Stop Calling It KV Cache" (April 28, 2026); presented at NVIDIA GTC first-ever KV cache industry tutorial; LMCache integration with Amazon SageMaker HyperPod shipped | 2026-05-19 |
| Nishith Sinha | Head of AI Product Security & AI Red Team | Databricks | LLM security, model safety, AI infrastructure security, secure training pipelines | First security leader to move from Amazon's foundational AI model security (Amazon Nova) to define AI red team practice at Databricks at scale; 8 AI security patents spanning identity-aware access control and secure model artifact storage | Joined Databricks January 2026 to lead AI Product Security and AI Red Team; previously secured Amazon Nova foundation models and AWS GenAI Services across 50+ internal teams and petabytes of training data | 2026-05-28 |

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
| Stuart Beck (@Stuub) | Independent Security Researcher | — | AI inference server security, GGUF model format attack vectors | Discovered CVE-2026-5760 (CVSS 9.8) — the first publicly documented RCE via malicious GGUF model file in SGLang; defined the "poisoned model file as attack vector" class for AI inference infrastructure | Disclosed CVE-2026-5760 in SGLang (April 2026); published proof-of-concept on GitHub showing full server compromise via Hugging Face-hosted malicious GGUF; JPCERT/CC advisory issued May 26, 2026 | 2026-05-28 |
| Adam Meyers | SVP Counter Adversary Operations | CrowdStrike | Supply chain threat intelligence, coordinated botnet disruption operations | Led the simultaneous four-channel Glassworm C2 takedown (Solana blockchain, BitTorrent DHT, Google Calendar, VPS) — first documented simultaneous multi-channel developer-targeting botnet disruption; articulated the "compounding cascade" model for developer supply chain attacks | Led Glassworm botnet takedown (May 26, 2026); co-coordinated with Google GTIG and Shadowserver Foundation; published sinkhole IP 164.92.88.210 and YARA rules; quoted extensively on adversarial supply chain escalation | 2026-05-29 |

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
| Alex Stephen | Software Engineer, Lakehouse | Google | Apache Iceberg ecosystem, open lakehouse architecture | Authored the official Apache Iceberg 1.11.0 release announcement for the Google Open Source Blog; key contributor to the DynamicIcebergSink and server-side scan planning features that complete enterprise lakehouse architecture | Published Apache Iceberg 1.11.0 release blog (May 27, 2026); explains DynamicIcebergSink (one-sink-many-tables with runtime schema evolution), server-side REST catalog scan planning, and native table encryption | 2026-05-28 |
| Talat Uyarer | Software Engineer, Lakehouse | Google | Apache Iceberg, Flink integration, streaming lakehouse architectures | Co-authored Iceberg 1.11.0 release blog; contributor to Flink 2.1 integration and DynamicIcebergSink development in 1.11.0 — enabling single-sink multi-table streaming writes at runtime | Co-authored Apache Iceberg 1.11.0 release blog (May 27, 2026); led Flink CDC + DynamicIcebergSink architectural work enabling on-demand table creation with runtime schema evolution in streaming pipelines | 2026-05-28 |

---

## 🧠 AI Agents

| Name | Role | Organization | Influence Area | Why Important | Recent Activity | Date Added |
|---|---|---|---|---|---|---|
| Idit Levine | Founder & CEO | Solo.io | Agentic infrastructure governance, cloud-native AI | Built and donated agentregistry to CNCF; launched agentevals — first to contribute all four layers of a coherent CNCF agentic governance stack | Announced agentregistry CNCF contribution + agentevals launch at KubeCon Amsterdam (March 25, 2026) | 2026-05-09 |
| Geoffrey Mattson | CEO | SecureAuth | Zero-trust identity for AI agents, Agent Detection and Response (ADR) | Launched the Agentic Authority Platform — first enterprise zero-trust control layer for AI agents with behavioral baselines, drift detection, and automatic revocation; introduced ADR as a distinct security category mirroring EDR for agents | Announced Agentic Authority Platform (May 19, 2026); defines the governance architecture above MCP: no standing privileges, federated credentials, real-time context-aware authorization | 2026-05-20 |
| Mark van Oppen | Chief Revenue Officer | SecureAuth | Enterprise identity security, cloud-native infrastructure at scale (IBM, Heptio, VMware, FusionAuth) | Appointed to scale enterprise adoption of zero-trust agent identity security; brings commercial rigor across cloud, Kubernetes, and identity to the agent governance market at the moment enterprises must govern AI agent behavior | Appointed CRO at SecureAuth (May 19, 2026); will lead global sales for Agentic Authority Platform across workforce, customer, and AI agent security | 2026-05-20 |
| Jason Robert | Open Source Engineer | Microsoft | Deterministic multi-agent orchestration, AI workflow architecture | Designed and open-sourced Microsoft Conductor — the first deterministic YAML-based multi-agent orchestration framework from a major tech company; defines the production-grade architectural alternative to dynamic LLM-planned orchestration | Published Conductor announcement on Microsoft Open Source Blog (May 14, 2026); MIT license release in Microsoft org; introduced evaluator-optimizer loop pattern at zero routing token cost and per-agent session isolation to prevent context drift | 2026-05-28 |
| David Soria Parra | Lead Maintainer (MCP Specification) | Anthropic | Model Context Protocol architecture, stateless transport design, agentic protocol standards | Co-lead of the largest MCP revision since launch; drove the stateless transport rework (six coordinated SEPs) enabling MCP to run on commodity HTTP infrastructure without session affinity; shepherded extensions framework and formal deprecation governance | Co-authored and locked MCP 2026-07-28 Release Candidate (May 21, 2026); 22+ SEPs merged; final specification ships July 28, 2026; 10-week Tier 1 SDK validation window begins | 2026-05-29 |
| Den Delimarsky | Lead Maintainer (MCP Specification) | Microsoft | Developer experience, protocol documentation, SDK tier governance, HTTP header standardization | Co-lead of MCP 2026-07-28 RC; authored the RC blog announcement and stateless topology diagrams; led HTTP header standardization (SEP-2243) enabling load-balancer-aware MCP routing; drives SDK tier conformance system | Co-authored MCP 2026-07-28 Release Candidate (May 21, 2026); primary author of spec announcement; leads SDK tier system requiring Tier 1 SDKs to ship support within 10-week validation window | 2026-05-29 |
