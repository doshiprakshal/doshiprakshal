<div align="center">

![header](./header1.svg)
![terminal](./terminal1.svg)

<br/>

![Apple](https://img.shields.io/badge/Apple-SRE-f0f6fc?style=flat-square&logo=apple&logoColor=white)
![status](https://img.shields.io/badge/status-systems_nominal-39d353?style=flat-square)
![uptime](https://img.shields.io/badge/uptime-99.97%25-39d353?style=flat-square)
![tps](https://img.shields.io/badge/workload-20K+_TPS-79c0ff?style=flat-square)
![open](https://img.shields.io/badge/open_to-SRE_%2F_Platform_%2F_Infra-bc8cff?style=flat-square)

</div>

---

## `$ cat about.yaml`

```yaml
name:       Prakshal Doshi
role:       Site Reliability Engineer
company:    Apple
location:   United States

team_size:  11 SREs (global team lead)
workload:   20,000+ TPS across AppleCare + new product launches

focus:
  - LLM inference infrastructure & AI-powered agents (MCP)
  - Multi-region active-active deployments
  - ChatOps-based deployments (Slack + Ansible + AWS)
  - Cloud cost optimization & failover validation
  - GenAI initiatives across SRE

philosophy: "toil is a bug · automate or die"

education:
  degree:   MS Computer Science
  school:   San Diego State University
  gpa:      3.71 / 4.0
  year:     2023
```

---

## `$ cat slo-dashboard.json`

<div align="center">

| metric | value | impact |
|--------|-------|--------|
| 🟢 system availability | **99.97%** | AppleCare + product launches |
| ⚡ peak throughput | **20,000+ TPS** | Apple Cloud + AWS |
| 🔥 cert-related incidents | **↓ 95%** | automated renewals + alerting |
| 🚀 release rollout time | **↓ 30%** | ChatOps deployments |
| 📦 service interruptions | **↓ 25%** | zero-downtime K8s migration |
| 💸 infra cost reduction | **↓ 55%** | monolith → microservices (JPMC) |
| ⏱ deployment time (JPMC) | **3 hrs → 20 min** | parallel CI/CD pipelines |
| ⏱ deployment time (ADP) | **55 min → 18 min** | Jenkins + CloudFormation |
| 👥 team led | **11 SREs** | global, Apple |

</div>

---

## `$ kubectl get stack --all-namespaces`

**Cloud & Orchestration**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Kustomize](https://img.shields.io/badge/Kustomize-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**CI/CD**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Spinnaker](https://img.shields.io/badge/Spinnaker-139BB4?style=flat-square&logo=spinnaker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

**Observability**

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Groovy](https://img.shields.io/badge/Groovy-4298B8?style=flat-square&logo=apachegroovy&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**GenAI & MCP**

![LLM](https://img.shields.io/badge/LLM_Inference-Infrastructure-bc8cff?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Agent_Integrations-39d353?style=flat-square)
![GenAI](https://img.shields.io/badge/GenAI-SRE_Automation-79c0ff?style=flat-square)

---

## `$ ls -la ./highlights`

### 🤖 LLM Inference & AI-Powered Incident Triage — Apple
> Architected LLM inference infra and MCP-integrated AI agents to automate incident triage across Splunk, Grafana, Kubernetes, and Ansible

```bash
$ agent --trigger incident --sources splunk,grafana,k8s,ansible
# → root cause identified · runbook generated · MTTR ↓ significantly
# → part of company-wide GenAI SRE initiative
```
![LLM](https://img.shields.io/badge/-LLM_Infra-bc8cff?style=flat-square)
![MCP](https://img.shields.io/badge/-MCP-39d353?style=flat-square)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

---

### ⚙ ChatOps Deployments — Apple
> Designed Slack + Ansible + AWS pipeline deployments — rollout time **↓ 30%**, full release visibility

```bash
$ slack trigger deploy --env prod --app applecare
# → pipeline triggered · approvals collected · rollout complete
# → 30% faster than previous release process
```
![Slack](https://img.shields.io/badge/-Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![Ansible](https://img.shields.io/badge/-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

### ◈ Petabyte-Scale K8s Migration — Apple
> Led end-to-end migration of petabyte-scale customer feedback service to Kubernetes — **↓ 25% service interruptions**

```bash
$ kubectl apply -f customer-feedback-migration.yaml
# → namespace relocated · GSLB/DNS configured
# → zero downtime · 25% fewer service interruptions
```
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![HDFS](https://img.shields.io/badge/-HDFS-FF6B00?style=flat-square)
![big-data](https://img.shields.io/badge/-500TB_data-79c0ff?style=flat-square)

---

### ◉ Microservices Migration — J.P. Morgan Chase
> Monolith → microservices on Kubernetes — **↓ 55% operational cost**, **3 hrs → 20 min deployments**, **25 → 0 outages/month**

```bash
$ jenkins run pipeline --parallel --env prod
# → 9 services deployed in parallel · 0 downtime · cost ↓ 55%
# → P0/P1 incidents: authored RCA · presented to executives
```
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

---

## `$ tail -f /var/log/github-stats.log`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=8b949e&border_radius=8)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=8b949e&border_radius=8)

![GitHub Streak](https://streak-stats.demolab.com?user=yourusername&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39d353&fire=39d353&currStreakLabel=39d353)

</div>

---

## `$ cat certifications.txt`

![CKS](https://img.shields.io/badge/CKA-Certified_Kubernetes_Security_Specialist-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![CKA](https://img.shields.io/badge/CKA-Certified_Kubernetes_Administrator-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![CKAD](https://img.shields.io/badge/CKAD-Certified_Kubernetes_Developer-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Solutions_Architect-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-Associate_Developer-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-Cloud_Engineer-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

## `$ cat /etc/motd`

```
╔──────────────────────────────────────────────────────────────────╗
│                                                                  │
│   🏆 "Best Infrastructure" — Google Cloud                       │
│      highly secure, highly available large-scale infra           │
│                                                                  │
│   ⭐ "Star Performer of the Month" — Quantiphi Analytics        │
│      leading and delivering a cost-efficient project             │
│                                                                  │
│   → automate the toil        → instrument everything             │
│   → write the runbook first  → blameless post-mortems, always   │
│                                                                  │
╚──────────────────────────────────────────────────────────────────╝
```

---

## `$ ping connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@email.com)
[![Resume](https://img.shields.io/badge/Resume-79c0ff?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://yourresume.dev)

*open to SRE · platform engineering · infrastructure · DevOps · GenAI infra roles*

![Visitor Count](https://komarev.com/ghpvc/?username=yourusername&color=39d353&style=flat-square&label=profile+views)

</div>

[![footer](https://capsule-render.vercel.app/api?type=waving&color=0d1117&customColorList=0,2,2,5,30&height=100&section=footer)](https://github.com/yourusername)
