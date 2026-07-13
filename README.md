<h1 align="center">Andre Kanmegne</h1>

<p align="center">
  <b>Platform Engineer · AI Systems Builder · Fullstack Developer</b><br/>
  RNCP Niveau 7 — Expert en développement logiciel · Ynov Campus Paris<br/>
  Apprenti IT Operations & Automation Engineer @ HDI Global SE France<br/>
  📍 Paris, France
</p>

<p align="center">
  <a href="https://devandre.sbs"><img src="https://img.shields.io/badge/Portfolio-devandre.sbs-0A66C2?style=flat&logo=google-chrome&logoColor=white"/></a>
  <a href="https://andrelair-platform.github.io/minicloud-platform-docs/blog"><img src="https://img.shields.io/badge/Blog-Platform%20Runbooks-22C55E?style=flat&logo=docusaurus&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/andre-kanmegne-dev/"><img src="https://img.shields.io/badge/LinkedIn-andre--kanmegne--dev-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kanmegneandre@gmail.com"><img src="https://img.shields.io/badge/Email-kanmegneandre@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

## What I'm building

The [`andrelair-platform`](https://github.com/andrelair-platform) organization is my personal homelab running as real production infrastructure — built to gain hands-on experience with the full platform engineering lifecycle, from bare-metal provisioning to GitOps delivery and AI services. 5 laptops (4 ThinkPad X390s + 1 MacBook Pro 2012), zero managed cloud:

**Infrastructure layer**
- MAAS bare-metal provisioning (PXE boot, Ubuntu 22.04, cloud-init)
- k3s cluster (1 control-plane + 4 workers) behind Tailscale mesh
- Longhorn distributed storage · Velero backups → MinIO

**GitOps & delivery**
- ArgoCD app-of-apps · Kustomize base+overlays · 3-branch CI promotion (dev → staging → prod)
- Harbor private registry with cosign image signing + SBOM
- 8 custom service repos, each with full CI on GitHub Actions

**Platform services**
- SSO: Authentik OIDC protecting ArgoCD, Grafana, Harbor, Backstage, Vault, Open WebUI
- Secrets: HashiCorp Vault with Kubernetes auth + AWS KMS auto-unseal
- Admission control: OPA Gatekeeper in deny mode across 23 namespaces
- Observability: Prometheus · Grafana · Loki · Tempo · Alertmanager

**AI services**
- Self-hosted LLMs: Ollama + Open WebUI
- RAG pipeline: document ingestion → Docling/MarkItDown → chunking → embeddings → pgvector
- LLM eval & tracing: LiteLLM router + Langfuse · phi3-financial PromptOps pipeline

62 automated regression checks. 35+ phases completed.  
Full runbooks → [minicloud-platform-docs](https://andrelair-platform.github.io/minicloud-platform-docs/)

---

## Tech stack

| Layer | Technologies |
|---|---|
| **Languages** | TypeScript · Python · Go · C# · JavaScript · SQL |
| **Platform & Infra** | Kubernetes (k3s) · MAAS · ArgoCD · Helm · Kustomize · OpenTofu · Ansible · Tailscale |
| **CI/CD & Registry** | GitHub Actions · Harbor · cosign · Docker Buildx |
| **Observability** | Prometheus · Grafana · Loki · Tempo · Alertmanager · node_exporter |
| **Security** | Vault · OPA Gatekeeper · Authentik · cert-manager · NetworkPolicy |
| **AI / LLM** | Ollama · Open WebUI · LiteLLM · LangChain · Langfuse · pgvector · RAG · Prompt Engineering |
| **Backend** | NestJS · FastAPI · ASP.NET Core · Node.js |
| **Frontend** | React · Next.js · Tailwind CSS · Framer Motion |

---

## Experience

**IT Operations & Automation Engineer (Apprentice)** — HDI Global SE France, Paris *(Sep 2024 – Present)*  
Python batch automation (−70% processing time) · IAM/SharePoint/Power Automate · ServiceNow ITSM for 200+ employees

**Software Engineer Intern** — FedHub, Remote *(Jul–Aug 2024)*  
Python ETL pipelines · React/TypeScript/Laravel frontend refactor · Core Web Vitals optimization

---

## Education

**Expert en développement logiciel** *(RNCP 39583 · Niveau 7 · Bac+5)*  
Ynov Campus Paris · 2022–2027

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AndreLiar&show_icons=true&theme=tokyonight&hide_border=true" alt="Andre's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AndreLiar&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

<p align="center">
  🇫🇷 Français (natif) · 🇬🇧 English (C1) · 🇩🇪 Deutsch (B1)
</p>
