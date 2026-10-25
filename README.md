<div align="center">

<!-- Hero Dynamic Waving Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:004e92,50:0078D4,100:00D2FF&height=260&section=header&text=KSHITIJ%20VERMA&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=%E2%9A%A1%20Azure%20Cloud%20%26%20DevOps%20Engineer%20%7C%20Terraform%20%7C%20Kubernetes%20%7C%20Platform%20Engineering&descFontSize=17&descAlignY=58" width="100%" alt="Kshitij Verma Header Banner" />

<!-- Dynamic Animated Typing Subtitle -->
<a href="https://github.com/Kverma0089">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&duration=2600&pause=900&color=00D2FF&center=true&vCenter=true&width=840&lines=Azure+Cloud+%26+DevOps+Engineer;Terraform+IaC+%7C+AKS+%7C+Helm+%7C+GitOps;AZ-104+%7C+AZ-305+%7C+AZ-400+%7C+CKA+Certified;CI%2FCD+Pipelines+%7C+Shift-Left+DevSecOps;Policy-as-Code+%7C+Zero-Trust+%7C+FinOps" alt="Kshitij Verma Typing SVG" />
</a>

<br />

<!-- Quick Navigation Bar -->
<p align="center">
  <a href="#about"><b>About</b></a> •
  <a href="#impact"><b>Impact</b></a> •
  <a href="#blueprints"><b>Blueprints</b></a> •
  <a href="#arsenal"><b>Arsenal</b></a> •
  <a href="#certs"><b>Certifications</b></a> •
  <a href="#projects"><b>Projects</b></a> •
  <a href="#telemetry"><b>Stats</b></a> •
  <a href="#connect"><b>Connect</b></a>
</p>

<!-- Live Badges & Counters -->
<p align="center">
  <a href="https://komarev.com/ghpvc/?username=Kverma0089&style=for-the-badge&color=0078d4">
    <img src="https://komarev.com/ghpvc/?username=Kverma0089&style=for-the-badge&color=0078d4&label=PROFILE+VIEWS" alt="Profile Views" />
  </a>
  <a href="https://www.linkedin.com/in/kshitij-verma/">
    <img src="https://img.shields.io/badge/LinkedIn-Kshitij%20Verma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <img src="https://img.shields.io/badge/Certifications-8%20Active-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Certifications" />
  <img src="https://img.shields.io/badge/Focus-Azure%20%7C%20DevOps%20%7C%20Kubernetes-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Focus" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-28A745?style=for-the-badge" alt="Status" />
</p>

---

</div>

<a name="about"></a>
## 💻 Engineer Terminal

```bash
┌──(kshitij㉿azure-cloud)-[~/platform-engineering]
└─$ ./launch-cloud-inspection.sh --env production --mode full-audit

[✔] Microsoft Entra ID & RBAC Guardrails         : ACTIVE (Zero-Trust Enforced)
[✔] Azure Hub-and-Spoke Topology                  : ONLINE (Azure Firewall + NSG Active)
[✔] Terraform IaC State                           : ZERO DRIFT (Remote State on Azure Blob)
[✔] Shift-Left DevSecOps Gates                    : Checkov, Trivy, Gitleaks PASS (0 Criticals)
[✔] AKS Cluster Health                            : HEALTHY (Node Pools Autoscaling Active)
[✔] GitOps Engine (ArgoCD)                        : SYNCED (All Apps Green)
[✔] Monitoring Stack (Grafana + Prometheus)       : ONLINE (All Dashboards Active)
[✔] Target Availability                           : 99.9% | Multi-Region DR Configured
```

> *"Automate everything. Enforce Zero-Trust by default. Shift security left. And deliver infrastructure as reliable, versioned, auditable code."*

I am an **Azure Cloud & DevOps Engineer** specialising in **Infrastructure as Code, Kubernetes Platform Engineering, CI/CD Automation, and Cloud Security**. I design and operate production-grade cloud platforms on Microsoft Azure — from Landing Zone architecture to multi-cluster AKS deployments managed via GitOps.

My expertise spans the full DevOps lifecycle: provisioning infrastructure with Terraform, automating multi-stage pipelines with Azure DevOps and GitHub Actions, enforcing security with Policy-as-Code, and building observability stacks with Grafana and Prometheus.

---

<a name="impact"></a>
## ⚡ Quantified Impact & Scale

<div align="center">

| Metric | Scale | Impact |
| :--- | :--- | :--- |
| 🏗️ **IaC Coverage** | **100% Terraform Governed** | All environments provisioned via modular Terraform with remote state, drift detection, and semantic versioning — zero manual click-ops. |
| 🐳 **Kubernetes Workloads** | **AKS Multi-Cluster** | Designed and managed AKS clusters with KEDA autoscaling, Workload Identity, OPA Gatekeeper, and ArgoCD GitOps — zero unplanned downtime. |
| 🛡️ **Shift-Left Security** | **Pre-Prod Gate Enforcement** | Embedded Checkov, Trivy, and Gitleaks into all PR pipelines — blocking vulnerabilities before they reach production environments. |
| 🔄 **CI/CD Automation** | **End-to-End Pipelines** | Built multi-stage Azure DevOps and GitHub Actions pipelines with Blue/Green deployments, rollback automation, and environment protection gates. |
| 📊 **Observability** | **Full Stack Monitoring** | Deployed Grafana + Prometheus + Azure Monitor stacks with custom dashboards, alerting, and Log Analytics Workspace integration. |
| 📜 **Certifications** | **8 Active Credentials** | AZ-104, AZ-305, AZ-400 (Expert), CKA, Terraform Associate, SC-900, AZ-900, GitHub Actions — active and validated. |

</div>

---

<a name="blueprints"></a>
## 🏛️ Architecture Blueprints

### 1. Enterprise Azure Landing Zone — Hub-and-Spoke Topology

```mermaid
flowchart TD
    classDef root fill:#0D1117,stroke:#58A6FF,stroke-width:2px,color:#fff;
    classDef mg fill:#161B22,stroke:#0078D4,stroke-width:2px,color:#fff;
    classDef hub fill:#004E92,stroke:#00D2FF,stroke-width:2px,color:#fff;
    classDef fw fill:#B91C1C,stroke:#EF4444,stroke-width:2px,color:#fff;
    classDef spoke fill:#064E3B,stroke:#10B981,stroke-width:2px,color:#fff;
    classDef paas fill:#78350F,stroke:#F59E0B,stroke-width:2px,color:#fff;

    subgraph EntraID[" Microsoft Entra ID Tenant "]
        TRG["Tenant Root Management Group"]:::root
    end

    subgraph MG[" Management Group Hierarchy — CAF "]
        PMG["Platform Management Group"]:::mg
        LMG["Landing Zones Group"]:::mg
        SMG["Sandbox & Decommissioned"]:::mg
        TRG --> PMG
        TRG --> LMG
        TRG --> SMG
        PMG --> SUB_ID["Identity Subscription (Entra ID / DNS)"]:::mg
        PMG --> SUB_MGMT["Management Subscription (Log Analytics)"]:::mg
        PMG --> SUB_CONN["Connectivity Subscription (Hub VNet)"]:::mg
        LMG --> CORP["Corp Subscriptions (Dev / UAT / Prod)"]:::mg
    end

    subgraph HubSpoke[" Zero-Trust Hub-and-Spoke Network "]
        subgraph HUB_VNET[" HUB VNet "]
            GW["GatewaySubnet (VPN Gateway)"]:::hub
            FW["Azure Firewall Premium (IDPS + TLS)"]:::fw
            DNS["Private DNS Zones"]:::hub
            BASTION["Azure Bastion"]:::hub
        end
        subgraph SPOKE1[" Spoke 1: AKS Workload VNet "]
            AKS["AKS Node Pools (System + User)"]:::spoke
            ACR["Azure Container Registry (Private)"]:::spoke
            PE["Private Endpoints (KV, Blob, ACR)"]:::paas
        end
        subgraph SPOKE2[" Spoke 2: DevOps Runners VNet "]
            RUNNERS["Self-Hosted Agents (ADO + GHA)"]:::spoke
            SCANNERS["Security Scanners (Trivy, Checkov)"]:::spoke
        end
    end

    GW <--> FW
    FW <==>|"VNet Peering + UDR"| SPOKE1
    FW <==>|"VNet Peering + UDR"| SPOKE2
    DNS -.->|"Private Link Resolution"| PE
```

---

### 2. Shift-Left DevSecOps CI/CD Pipeline

```mermaid
flowchart LR
    classDef trigger fill:#1E293B,stroke:#64748B,stroke-width:2px,color:#fff;
    classDef stage fill:#0F172A,stroke:#0284C7,stroke-width:2px,color:#fff;
    classDef sec fill:#450A0A,stroke:#DC2626,stroke-width:2px,color:#fff;
    classDef deploy fill:#0C4A6E,stroke:#0284C7,stroke-width:2px,color:#fff;
    classDef gate fill:#581C87,stroke:#9333EA,stroke-width:2px,color:#fff;

    DEV(["Developer Commit"]):::trigger --> PR["Pull Request Trigger"]:::trigger

    subgraph Stage1[" Stage 1: Validate & Lint "]
        LINT["tflint + terraform fmt"]:::stage
        VALIDATE["terraform validate"]:::stage
    end

    subgraph Stage2[" Stage 2: Shift-Left Security "]
        SECRETS["Secret Scanning (Gitleaks)"]:::sec
        SAST["IaC Scan (Checkov + Trivy)"]:::sec
        POLICY["Policy Gate (OPA + Azure Policy)"]:::sec
    end

    subgraph Stage3[" Stage 3: Plan & Review "]
        PLAN["terraform plan (Remote State Lock)"]:::stage
        COMMENT["PR Cost Comment (Infracost)"]:::stage
    end

    subgraph Stage4[" Stage 4: Deploy (Main Branch) "]
        APPLY["terraform apply --auto-approve"]:::deploy
        ARGO["ArgoCD Sync (GitOps)"]:::deploy
    end

    subgraph Stage5[" Stage 5: Post-Deploy Verify "]
        SMOKE["Smoke Tests + Health Checks"]:::gate
        DRIFT["Drift Detection (Scheduled)"]:::gate
    end

    PR --> Stage1 --> Stage2 --> Stage3 --> Stage4 --> Stage5
```

---

<a name="arsenal"></a>
## 🛠️ Tech Arsenal

### ☁️ Azure Cloud
<p align="center">
<img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Kubernetes_Service-0078D4?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Firewall-B91C1C?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Entra_ID-5E5E5E?style=for-the-badge&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</p>

### 🏗️ Infrastructure as Code
<p align="center">
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
<img src="https://img.shields.io/badge/Bicep-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
<img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>
</p>

### 🐳 Containers & GitOps
<p align="center">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
<img src="https://img.shields.io/badge/Flux_CD-5468FF?style=for-the-badge&logo=flux&logoColor=white"/>
</p>

### 🔄 CI/CD & DevSecOps
<p align="center">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Pipelines-2560E0?style=for-the-badge&logo=azuredevops&logoColor=white"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>
<img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aqua&logoColor=white"/>
<img src="https://img.shields.io/badge/Checkov-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</p>

### 📊 Monitoring & Observability
<p align="center">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</p>

### 💻 Scripting & Languages
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
<img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white"/>
</p>

---

<a name="certs"></a>
## 📜 Certification Wall

<div align="center">

| Certification | Issuer | Level | Year |
| :--- | :--- | :---: | :---: |
| **AZ-900** Azure Fundamentals | Microsoft | Associate | 2022 |
| **AZ-104** Azure Administrator Associate | Microsoft | Associate | 2022 |
| **SC-900** Security, Compliance & Identity | Microsoft | Fundamentals | 2022 |
| **AZ-400** Azure DevOps Engineer Expert | Microsoft | **Expert** | 2023 |
| **AZ-305** Azure Solutions Architect Expert | Microsoft | **Expert** | 2023 |
| **CKA** Certified Kubernetes Administrator | CNCF | Professional | 2023 |
| **Terraform Associate 003** | HashiCorp | Associate | 2024 |
| **GitHub Actions** Certification | GitHub | Associate | 2024 |

</div>

---

<a name="projects"></a>
## 🌟 Featured Projects

<div align="center">

[![Kshitij Cloud Portfolio](https://github-readme-stats.vercel.app/api/pin/?username=Kverma0089&repo=kshitij-cloud-portfolio&theme=tokyonight&bg_color=0D1117&title_color=00BCF2&text_color=C9D1D9&border_color=30363D&icon_color=0078D4)](https://github.com/Kverma0089/kshitij-cloud-portfolio)

</div>

---

<a name="telemetry"></a>
## 📊 GitHub Telemetry

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Kverma0089&show_icons=true&theme=tokyonight&bg_color=0D1117&title_color=00BCF2&text_color=C9D1D9&icon_color=0078D4&border_color=30363D&count_private=true" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Kverma0089&theme=tokyonight&background=0D1117&ring=0078D4&fire=00BCF2&currStreakLabel=00BCF2&border=30363D" />
</div>
<div align="center">
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kverma0089&layout=compact&theme=tokyonight&bg_color=0D1117&title_color=00BCF2&text_color=C9D1D9&border_color=30363D&langs_count=8" />
</div>
<div align="center">
  <img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=Kverma0089&theme=tokyo-night&bg_color=0D1117&color=00BCF2&line=0078D4&point=50E6FF&area=true" />
</div>
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Kverma0089&theme=tokyonight&no-bg=true&column=7&margin-w=8" />
</div>

---

<a name="connect"></a>
## 💬 Connect

<div align="center">

<a href="https://www.linkedin.com/in/kshitij-verma/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/Kverma0089">
  <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://kverma0089.github.io/kshitij-cloud-portfolio">
  <img src="https://img.shields.io/badge/Portfolio-Visit-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
</a>

<br /><br />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:004e92,50:0078D4,100:00D2FF&height=120&section=footer&animation=fadeIn" width="100%" alt="footer"/>

</div>
