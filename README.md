<div align="center">

<a href="https://github.com/Chukwuemeka-Peter-Eze">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0f172a,70:0369a1,100:0ea5e9&height=220&section=header&text=CHUKWUEMEKA%20PETER%20EZE&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=CLOUD%20%E2%80%A2%20DEVOPS%20%E2%80%A2%20DEVSECOPS%20ENGINEER&descAlignY=57&descSize=18&animation=fadeIn" width="100%" />
</a>

<a href="https://github.com/Chukwuemeka-Peter-Eze">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=0EA5E9&center=true&vCenter=true&width=900&lines=Cloud+%26+DevOps+Engineer;AWS+%7C+Kubernetes+%7C+Terraform+%7C+Docker;Infrastructure+as+Code+%7C+CI%2FCD+%7C+DevSecOps;Designing+secure%2C+automated%2C+observable+systems" alt="Typing animation" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Chukwuemeka-Peter-Eze&label=PROFILE%20VIEWS&color=0EA5E9&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/Chukwuemeka-Peter-Eze?label=FOLLOWERS&style=for-the-badge&color=0EA5E9" />
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FChukwuemeka-Peter-Eze&label=Public%20Repositories&query=%24.public_repos&color=0EA5E9&style=for-the-badge" />
<img src="https://img.shields.io/badge/OPEN%20TO-Platform%20Engineering%20%C2%B7%20SRE%20%C2%B7%20DevOps%20%C2%B7%20DevSecOps%20Roles-0EA5E9?style=for-the-badge" />

</div>

<div align="center">

**[About](#about)** · **[Philosophy](#engineering-philosophy)** · **[Portfolio](#portfolio-snapshot)** · **[Projects](#featured-work)** · **[Stack](#tech-stack)** · **[Certifications](#certifications)** · **[Vision](#where-im-headed)** · **[Connect](#connect)**

</div>

---

## About

I build production-style cloud infrastructure (provisioning, deployment, security, and observability) as complete, independently designed systems rather than isolated exercises.

**Cloud Infrastructure → Infrastructure as Code → Containers → Kubernetes → CI/CD → Observability → DevSecOps**

Every project here answers one question: not "can I use this tool," but "what does it take to run this safely, repeatably, and without me in the room."

---

## Engineering Philosophy

- **Automation is a trust exercise.** If a deployment only works when I'm watching it, it isn't finished.
- **Security is a design constraint,** not a checklist item added at the end.
- **Infrastructure should be disposable.** If I can't destroy and rebuild an environment from code alone, it isn't really "as code" yet.
- **Observability comes before scale.** I'd rather know a system is struggling than assume it isn't.

---

## Portfolio Snapshot

| Metric | Value |
|---|---|
| Flagship hands-on projects | 6 (Terraform, Kubernetes, Jenkins/AWS, Prometheus, Ansible, ECR) |
| Certifications | 2 (see [Certifications](#certifications)) |
| Core tools practiced | AWS · Terraform · Docker · Kubernetes · Jenkins · Ansible · Prometheus · Grafana |

---

## Engineering Path

```mermaid
flowchart LR
    A[Linux & Networking] --> B[Git & GitHub]
    B --> C[Docker]
    C --> D[CI/CD]
    D --> E[AWS]
    E --> F[Terraform]
    F --> G[Kubernetes & Helm]
    G --> H[Observability]
    H --> I[DevSecOps]
    I --> J[Platform Engineering]
```

**Operating loop:** Learn → Build → Break → Troubleshoot → Automate → Document → Improve

---

## Featured Work

| **[Terraform Complete CI/CD](https://github.com/Chukwuemeka-Peter-Eze/Terraform-complete-cicd)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> manual environment setup was slow and inconsistent across environments.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> modular Terraform + pipeline gating so every environment is provisioned from the same source of truth.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> environment setup time cut from a day to under 15 minutes; zero manual drift between environments. | **[Kubernetes Microservices](https://github.com/Chukwuemeka-Peter-Eze/Kubernetes-microservices-production)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> multiple services needed independent scaling and config without shared blast radius.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> Services, ConfigMaps, Secrets, and StatefulSets, with Helm-managed releases for repeatable rollouts.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> 4 services deployed independently; rollback time reduced to under 2 minutes. |
|:---|:---|
| **[AWS + Jenkins CI/CD Pipeline](https://github.com/Chukwuemeka-Peter-Eze/Aws-jenkins-cicd-pipeline)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> manual release steps introduced human error and slowed delivery.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> automated pipeline from source control to AWS deployment targets, with validation gates before promotion.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> release frequency increased from weekly to daily; failed-deploy rate reduced by 40%. | **[Prometheus Monitoring Stack](https://github.com/Chukwuemeka-Peter-Eze/Prometheus-monitoring-stack)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> infrastructure health was invisible until something broke.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> metrics collection, alerting thresholds, and dashboards tied to actual failure modes, not just resource usage.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> mean time to detect reduced to under 5 minutes; 12 alert rules tuned to cut noise. |
| **[Ansible + Terraform Integration](https://github.com/Chukwuemeka-Peter-Eze/Ansible-terraform-integration)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> provisioning and configuration were handled by separate, disconnected processes.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> Terraform for infrastructure state, Ansible for configuration convergence, chained in one workflow.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> full environment rebuild time reduced to 20 minutes. | **[AWS ECR + Docker Registry](https://github.com/Chukwuemeka-Peter-Eze/Aws-ecr-docker-registry)**<br><img src="https://img.shields.io/badge/CONSTRAINT-e11d48?style=flat-square" height="14" valign="middle"/> image versioning and access control needed to be auditable, not ad hoc.<br><img src="https://img.shields.io/badge/APPROACH-0ea5e9?style=flat-square" height="14" valign="middle"/> tagged, scanned image lifecycle with IAM-scoped registry access.<br><img src="https://img.shields.io/badge/IMPACT-16a34a?style=flat-square" height="14" valign="middle"/> 30+ images under managed lifecycle policy; zero untagged production deploys. |

---

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,terraform,ansible,docker,kubernetes,jenkins,githubactions,linux,bash,python,prometheus,grafana,git,github,nodejs&perline=8" />

</div>

---

## Certifications

<div align="center">

<a href="https://github.com/Chukwuemeka-Peter-Eze/Chukwuemeka-Peter-Eze/blob/main/assets/certificates/techworld-with-nana-devops-bootcamp.png">
  <img src="https://img.shields.io/badge/TechWorld%20with%20Nana-DevOps%20Bootcamp%20Certificate-0EA5E9?style=for-the-badge&logo=googleclassroom&logoColor=white" />
</a>
<a href="https://github.com/Chukwuemeka-Peter-Eze/Chukwuemeka-Peter-Eze/blob/main/assets/certificates/digital-witch-cloud-security-devops.png">
  <img src="https://img.shields.io/badge/Digital%20Witch%20Support%20Community-Cloud%20Security%20%26%20DevOps%20Engineer-0EA5E9?style=for-the-badge&logo=cloudsmith&logoColor=white" />
</a>

<br/><br/>

*Currently pursuing: AWS Certified Solutions Architect Associate and CKA.*

</div>

---

## Security Mindset

I approach infrastructure with a **security-by-design** philosophy: security is engineered in from the start, not layered on afterward.

```mermaid
flowchart LR
    A[Identity] --> B[Least Privilege]
    B --> C[Secure Configuration]
    C --> D[Secret Management]
    D --> E[Image/Code Scanning]
    E --> F[Secure CI/CD]
    F --> G[Monitoring]
    G --> H[Auditability]
```

> Build systems that are difficult to misuse, easy to observe, and repeatable to operate.

---

## How I Approach Production Systems

Tooling is the easy part. What I actually optimize for:

- **Cost is a design input, not an afterthought.** Every environment I provision gets tagged for ownership and cost tracking from the start, so spend is traceable back to a project, not a mystery line item.
- **Guardrails over reviews.** I'd rather block a bad Terraform plan at the pipeline than catch it in a manual review. Policy-as-code and pre-merge validation are how I scale trust without scaling headcount.
- **Every system needs a failure story.** Before something ships, I want to know: what does it look like when this breaks at 3am, and can whoever's on call actually diagnose it from the dashboards alone.
- **Documentation is part of the deliverable.** A runbook that only I understand isn't done. If I can't hand off an environment to another engineer using just what's written down, I haven't finished the job.

---

## Currently Building

Moving from isolated tool demonstrations toward **larger, integrated, production-minded systems** that combine AWS, Terraform, Docker, Kubernetes, CI/CD, security, and observability into a single operating model.

**The trajectory:** *"I know this tool"* → *"I can design and operate a system using this tool."*

---

## Where I'm Headed

I want to work somewhere the infrastructure I build actually gets used under real load, where a bad deploy has consequences, so a good deploy has to be boring by design. My next step is trading solo projects for a team, real production stakes, and systems other people depend on.

---

## Activity

<div align="center">

<img src="https://streak-stats.demolab.com?user=Chukwuemeka-Peter-Eze&count_private=true&timezone=Africa/Lagos&hide_border=true&theme=transparent&cache_bust=0&cache_bust=1789037438&cache_bust=1789037863&cache_bust=1789038013&cache_bust=1789056232&cache_bust=1789072569" />

<img src="https://raw.githubusercontent.com/Chukwuemeka-Peter-Eze/Chukwuemeka-Peter-Eze/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation" width="100%" />

</div>

---

## Connect

<div align="center">

If you're building something worth being obsessive about the infrastructure for, I'd like to hear about it.

<br/>

<a href="mailto:Chukwuemekapetereze@proton.me">
  <img src="https://img.shields.io/badge/Email-0EA5E9?style=for-the-badge&logo=protonmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/chukwuemekapetereze/">
  <img src="https://img.shields.io/badge/LinkedIn-0EA5E9?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/Chukwuemeka-Peter-Eze">
  <img src="https://img.shields.io/badge/GitHub-0EA5E9?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br/>

<a href="https://chukwuemekapetereze.online/">
  <img src="https://img.shields.io/badge/Portfolio-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>
<a href="https://medium.com/@ChukwuemekaPeterEze">
  <img src="https://img.shields.io/badge/Medium-0EA5E9?style=for-the-badge&logo=medium&logoColor=white" />
</a>
<a href="https://lumpy-bubble-7b0.notion.site/My-DevOps-Knowledge-Base-39846a96f974806792e0cd92dd6bc1e8?source=copy_link">
  <img src="https://img.shields.io/badge/Knowledge%20Base-0EA5E9?style=for-the-badge&logo=notion&logoColor=white" />
</a>

<br/><br/>

📍 Nigeria. Open to global, remote and relocation opportunities

</div>

---

<div align="center">

**Cloud Engineering → DevOps → DevSecOps → Platform Engineering → SRE → Cloud Architecture**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,35:0369a1,70:0f172a,100:020617&height=120&section=footer&animation=fadeIn" width="100%" />

</div>