# Hi there, I'm Nachman Molko! 👋

**Infrastructure Automation Engineer · Microsoft, Tel Aviv**

I build the systems that build the infrastructure, self-service portals, automated provisioning pipelines, and AI-augmented operations tooling. My background spans military network operations (IDF 8200), enterprise VMware environments, and cloud-native AWS/Kubernetes deployments. I write infrastructure-as-code first, scripts second.

---

## What I'm Building Now

**vSphere Self-Service Portal** *(Microsoft, internal)*
A production internal developer platform for self-service VM and network provisioning in a VMware vSphere environment. Security-hardened split architecture: a DMZ-facing API gateway decoupled from an internal orchestrator that holds privileged vSphere credentials.

- **Frontend:** React / Vite
- **Backend:** FastAPI + RabbitMQ worker queue
- **IaC:** Terraform + Ansible
- **Deployment:** Kubernetes (Helm, KEDA autoscaling)

---

## Projects

### [AI Network Troubleshooter](https://github.com/NachmanM/ai-network-troubleshooter)
Closed-loop AI system for automated network incident response. Telegraf pulls real-time telemetry via Netconf → InfluxDB stores it → Grafana fires webhook alerts → FastAPI LLM agent (GPT-4o) diagnoses the issue → pyATS executes remediation commands on devices → Webex bot reports results.

`Python` `FastAPI` `OpenAI GPT-4o` `pyATS` `Telegraf` `InfluxDB` `Grafana` `Docker` `Cisco CML`

---

### [Auto-Location Scheduler](https://github.com/NachmanM/AutoWhatsappToCalendarToTasker)
AI pipeline for schedule-driven live location sharing. Google Calendar events trigger a Tasker automation on Android, Gemini processes the schedule, Lambda + S3 coordinate the workflow, and WhatsApp receives the live location — all without manual intervention.

`Python` `AWS Lambda` `S3` `Docker` `Gemini` `Tasker`

---

### [AWS Kubernetes Platform](https://github.com/NachmanM/aws-k8s-platform)
Fully automated, single-command Kubernetes cluster deployment on AWS. Wraps the full lifecycle - networking, node groups, IAM, into one idempotent execution.

`Terraform` `HCL` `AWS` `Kubernetes`

---

### [Status Page (K8s)](https://github.com/NachmanM/statuspage-k8s)
Production-grade status page running on a self-managed Kubernetes cluster on AWS. Full GitOps lifecycle with ArgoCD, CI/CD via GitHub Actions, Django + PostgreSQL + Redis backend, provisioned with Terraform.

`Python` `Django` `PostgreSQL` `Redis` `Kubernetes` `Terraform` `ArgoCD` `GitHub Actions`




### Verified Credentials



<table border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" valign="middle" width="140">
      <a href="https://www.credly.com/earner/earned/badge/8cacaea5-826a-456a-881f-64b4fb6c8b86">
        <img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="95" alt="AWS Certified Solutions Architect - Associate">
      </a>
    </td>
    <td align="center" valign="middle" width="140">
      <a href="https://www.credly.com/earner/earned/badge/aa7195b1-0733-4338-90b7-8d0ec188099e">
        <img src="https://github.com/NachmanM/NachmanM/raw/main/ccna_icon.png" width="120" alt="Cisco CCNA">
      </a>
    </td>
    <td align="center" valign="middle" width="140">
      <a href="https://www.credly.com/earner/earned/badge/ab82ead0-2668-4528-b2d8-4f9fea116ed7">
        <img src="https://github.com/NachmanM/NachmanM/raw/main/ccna_automation_icon.png" width="120" alt="CCNA Automation">
      </a>
    </td>
  </tr>
</table>
---

## Background

- **Infrastructure Automation Engineer:** Microsoft, Tel Aviv (2025–Present)
  Architecting secure self-service VMware portals; automating infrastructure provisioning with Terraform and Ansible; maintaining Azure-based asset management platforms.

- **Team Lead & Network Technician:** IDF 8200 (2023–2025)
  Led a 15-person team maintaining 24/7 critical network infrastructure. Advanced PowerShell/CMD diagnostics, Layer 1–4 troubleshooting, secure hardware operations.

- **Nitzanim To Tech** — 1,000-Hour DevOps Training Program (2025–2026)

---


<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/nachman-molko" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nachman-molko" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://circleci.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.rabbitmq.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>
