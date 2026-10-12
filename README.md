<div align="center">

# Ipadeola O. Taiwo

### Cloud & DevOps Engineer

**Azure · Terraform · GitHub Actions · Infrastructure as Code**

[![Portfolio](https://img.shields.io/badge/Portfolio-taiwoipadeola.space-0066CC?style=flat-square)](https://www.taiwoipadeola.space)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ipadeola--taiwo-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ipadeola-taiwo/)
[![Dev.to](https://img.shields.io/badge/Dev.to-highpee1991-0A0A0A?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/highpee1991)
[![Hashnode](https://img.shields.io/badge/Hashnode-highpeedev-2962FF?style=flat-square&logo=hashnode&logoColor=white)](https://highpeedev.hashnode.dev)
[![Email](https://img.shields.io/badge/Email-ipadeola.it@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ipadeola.it@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=highpee1991&style=flat-square&color=0066CC)](https://github.com/highpee1991)

**Lagos, Nigeria · Remote-friendly · Open to opportunities**

</div>

---

## What I Do

I build and automate production-grade cloud infrastructure — from secure Azure virtual networks and Terraform module systems to GitHub Actions CI/CD pipelines that deploy infrastructure automatically on every merge to main.

Every project below was built in a live cloud environment, hit real production errors, and has a published article documenting exactly what happened and why.

---

## Featured Projects

| Project | Stack | What It Does |
|---|---|---|
| [**terraform-cicd-pipeline**](https://github.com/highpee1991/terraform-cicd-pipeline) | GitHub Actions · Terraform · Azure · Service Principal · cloud-init | Three-stage automated pipeline: validate → plan → apply. Triggered on push and PR. Deploys to Azure only on merge to main. Zero manual terraform commands in production. Nine real pipeline failures traced and fixed. |
| [**terraform-enterprise**](https://github.com/highpee1991/terraform-enterprise) | Terraform · Azure · Modules · Remote State · State Locking | Three isolated Azure environments (payments, analytics, platform) deployed from one reusable Terraform module. Remote state in Azure Blob Storage. Survived live network failure — state recovery documented. |
| [**terraform-IAC**](https://github.com/highpee1991/terraform-IAC) | Terraform · Azure VM · Azure Storage · Remote Backend | Full Azure VM stack with remote state and locking. State locking proven live with two-terminal concurrent-apply test. NSG association issue documented — the piece most tutorials skip. |
| [**Terraform-Virtual-Machine-Deployment**](https://github.com/highpee1991/Terraform-Virtual-Machine-Deployment) | Terraform · HCL · Azure VM · Ubuntu 22.04 · Nginx | End-to-end IaC from providers to a running web server. Five production errors diagnosed from first principles including silent NSG association failure. |
| [**azure-cli-lab**](https://github.com/highpee1991/azure-cli-lab) | Azure CLI · Bash · Ubuntu · Nginx · NSG · SCP | Live website deployed to Azure VM via CLI only — no portal. NSG priority conflict diagnosed and fixed. Bash provisioner for repeatable one-command redeploy. |

---

## Technical Stack

**Cloud Platform**

![Azure](https://img.shields.io/badge/Microsoft_Azure-0089D0?style=flat-square&logo=microsoft-azure&logoColor=white)
![Azure CLI](https://img.shields.io/badge/Azure_CLI-0089D0?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square&logo=terraform&logoColor=white)

**CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Containers & Cloud Native**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**OS & Tooling**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

## Azure Infrastructure Skills

```
Compute:      Virtual Machines · VM Scale Sets · Availability Sets
Networking:   VNet · Subnet · NSG · Azure Bastion · NAT Gateway
              VNet Peering · Public IP · NIC · Load Balancer
Storage:      Storage Accounts · Blob Storage · Static Web Hosting
Identity:     Microsoft Entra ID · Azure RBAC · Service Principals
              SSH Authentication · Managed Identity
IaC:          Terraform Modules · Remote State · State Locking
              locals · tfvars · multi-environment deployments
CI/CD:        GitHub Actions · Validate → Plan → Apply pipelines
              Artifact management · Controlled deployment
              cloud-init provisioning · GitHub Secrets
```

---

## Writing

I document every build — including the errors and how I fixed them. 10+ published technical articles across Dev.to and Hashnode.

Recent articles:
- [Building a Terraform CI/CD Pipeline With GitHub Actions](https://dev.to/highpee1991/building-a-terraform-cicd-pipeline-with-github-actions-and-debugging-every-single-thing-that-15bf)
- [Refactoring Terraform Into Reusable Modules](https://dev.to/highpee1991/refactoring-terraform-infrastructure-into-reusable-modules-multi-environment-one-codebase-39a)
- [Building Enterprise Azure Infrastructure With Remote State](https://dev.to/highpee1991/building-enterprise-azure-infrastructure-with-terraform-and-remote-state-5bm2)
- [Deploying a Live Website on Azure Using Only the CLI](https://dev.to/highpee1991/i-deployed-a-live-website-on-azure-using-only-the-cli-no-portal-no-clicking-4men)

→ All articles: [dev.to/highpee1991](https://dev.to/highpee1991) · [highpeedev.hashnode.dev](https://highpeedev.hashnode.dev)

---

## Certifications

- 🏅 **Cloud & DevOps Engineering Certificate** — Hagital Consulting, September 2026 *(6-month intensive project-based programme)*
- ✅ **LFS101** — Introduction to Linux, The Linux Foundation *(ID: LF-ocxio1nmwz)*
- ✅ **LFS158** — Introduction to Kubernetes, The Linux Foundation
- ✅ **LFS250** — Kubernetes & Cloud Native Essentials, The Linux Foundation
- ✅ **Google Cybersecurity Professional Certificate** — Google/Coursera
- ✅ **Microsoft AI Skills Fest 2026** — Microsoft

---

## Currently

- 🔧 Building a 3-tier containerised application — Docker, Terraform, GitHub Actions, HTTPS, custom domain
- 🌍 Open to **Junior Cloud Engineer**, **Junior DevOps Engineer**, **Azure Infrastructure Engineer**, and **Cloud Support Engineer** roles — remote or Lagos-based
- 📬 Reach me: [ipadeola.it@gmail.com](mailto:ipadeola.it@gmail.com) · [taiwoipadeola.space](https://www.taiwoipadeola.space)

---

<div align="center">

*"Infrastructure should fail loudly with a clear error rather than succeed silently with wrong values."*

**[View Portfolio](https://www.taiwoipadeola.space) · [Read Articles](https://dev.to/highpee1991) · [Connect on LinkedIn](https://www.linkedin.com/in/ipadeola-taiwo/)**

</div>
