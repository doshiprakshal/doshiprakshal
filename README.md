<!-- Header -->
<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ███████╗██████╗ ███████╗    ██╗███╗   ██╗██╗████████╗    ║
║   ██╔════╝██╔══██╗██╔════╝    ██║████╗  ██║██║╚══██╔══╝    ║
║   ███████╗██████╔╝█████╗      ██║██╔██╗ ██║██║   ██║       ║
║   ╚════██║██╔══██╗██╔══╝      ██║██║╚██╗██║██║   ██║       ║
║   ███████║██║  ██║███████╗    ██║██║ ╚████║██║   ██║       ║
║   ╚══════╝╚═╝  ╚═╝╚══════╝    ╚═╝╚═╝  ╚═══╝╚═╝   ╚═╝       ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

# `$ whoami` → **Prakshal Doshi** · DevOps / SRE Engineer

*keeping prod alive · chaos enjoyer · if it can break, i've already fixed it*

![Status](https://img.shields.io/badge/systems-nominal-39d353?style=flat-square&logo=statuspage&logoColor=white)
![Uptime](https://img.shields.io/badge/uptime-99.97%25-39d353?style=flat-square)
![MTTR](https://img.shields.io/badge/MTTR-%3C4min-79c0ff?style=flat-square)
![Open to work](https://img.shields.io/badge/open_to-SRE_%2F_Platform_%2F_Infra_roles-bc8cff?style=flat-square)

</div>

---

## `$ cat about.yaml`

```yaml
# -------------------------------------------------------
# profile: doshiprakshal
# updated: 2025
# -------------------------------------------------------

role:       DevOps / SRE Engineer
location:   Your City, Country
focus:
  - platform reliability
  - infrastructure-as-code
  - chaos engineering
  - developer experience

passion:    turning 3am pages into GitHub Actions

philosophy: "toil is a bug · automate or die"

currently_learning:
  - eBPF observability
  - platform engineering patterns
  - AI-assisted incident response

mttr:       "< 4 min"
availability: "99.97%"
pipelines_shipped: 400+
```

---

## `$ kubectl get stack --all-namespaces`

**Orchestration & Infrastructure**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**Cloud Platforms**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Observability & Reliability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PagerDuty](https://img.shields.io/badge/PagerDuty-06AC38?style=flat-square&logo=pagerduty&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)

**CI/CD & Automation**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square&logo=yaml&logoColor=white)

---

## `$ cat slo-dashboard.json`

<div align="center">

| metric | value | target |
|--------|-------|--------|
| 🟢 availability | **99.97%** | 99.9% |
| ⚡ MTTR | **< 4 min** | < 15 min |
| 🚀 deploy frequency | **12x / week** | daily |
| 🔁 pipelines shipped | **400+** | — |
| 🔥 incidents → runbooks | **100%** | 100% |

</div>

---

## `$ ls -la ./projects`

### ⚙ [k8s-autoscaler-policy](https://github.com/yourusername/k8s-autoscaler-policy)
> Custom HPA + KEDA rules that **cut cloud spend by 38%** during off-peak hours

```bash
$ kubectl apply -f autoscaler-policy.yaml
# → scaled 47 deployments · saved $2,400/mo
```
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![cost-optimization](https://img.shields.io/badge/-cost--opt-39d353?style=flat-square)

---

### ◈ [terraform-platform-modules](https://github.com/yourusername/terraform-platform-modules)
> Opinionated IaC modules — VPC, EKS, RDS — **zero-to-prod in 12 minutes**

```bash
$ terraform apply -target=module.platform
# → 47 resources created · 0 errors · 12m 03s
```
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![modules](https://img.shields.io/badge/-modules-79c0ff?style=flat-square)

---

### ◉ [chaos-runbook-bot](https://github.com/yourusername/chaos-runbook-bot)
> Slack bot that **auto-generates runbooks** from past incidents using LLMs + PagerDuty data

```bash
$ python bot.py --incident INC-4821
# → runbook generated · 3 similar incidents found · MTTR ↓ 40%
```
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Slack](https://img.shields.io/badge/-Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![LLM](https://img.shields.io/badge/-LLM-bc8cff?style=flat-square)

---

## `$ tail -f /var/log/github-stats.log`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&icon_color=39d353&text_color=8b949e)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=39d353&text_color=8b949e)

![GitHub Streak](https://streak-stats.demolab.com?user=yourusername&theme=github-dark-blue&hide_border=true&background=0d1117&ring=39d353&fire=39d353&currStreakLabel=39d353)

</div>

---

## `$ cat /etc/motd`

```
╔─────────────────────────────────────────────────────────────╗
│                                                             │
│   "The best on-call rotation is the one you never need."   │
│                                                             │
│   → automate the toil                                      │
│   → instrument everything                                   │
│   → write the runbook before the incident                  │
│   → blameless post-mortems, always                         │
│                                                             │
╚─────────────────────────────────────────────────────────────╝
```

---

## `$ ping connect`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)
[![Blog](https://img.shields.io/badge/Blog-39d353?style=for-the-badge&logo=hashnode&logoColor=white)](https://yourblog.dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:you@email.com)
[![Resume](https://img.shields.io/badge/Resume-79c0ff?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://yourresume.dev)

*open to SRE · platform engineering · infrastructure · DevOps roles*

![Visitor Count](https://komarev.com/ghpvc/?username=yourusername&color=39d353&style=flat-square&label=profile+views)

</div>

---

<div align="center">
<sub>⚙ systems nominal · uptime 99.97% · last deployed: today</sub>
</div>
