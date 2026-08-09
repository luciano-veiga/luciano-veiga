# Olá, sou o Luciano Veiga 👋
[#ola-eu-sou-o-luciano](#ola-eu-sou-o-luciano)

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Network+%26+Infrastructure+Manager;ISP+%7C+Cloud+%7C+DevOps;AWS+Certified+Solutions+Architect;Construindo+solu%C3%A7%C3%B5es+em+SecDevOps)](https://git.io/typing-svg)



## Sobre Mim 👨‍💻

Profissional de Tecnologia da Informação com experiência em Infraestrutura, Redes, Suporte e Gestão de TI, expandindo continuamente minha atuação em Cloud Computing (AWS), automação e desenvolvimento.

Acredito que tecnologia deve resolver problemas reais. Por isso, gosto de entender a causa dos desafios, automatizar processos repetitivos e construir soluções escaláveis, da administração de ambientes Linux e redes até arquiteturas em nuvem.

Redes, servidores e infra que não podem cair.

### 🌐 ISP & Redes

[#-isp--redes](#-isp--redes)

- 📡 Gerencio a operação de um ISP (provedor de internet)
- 🎧 Já passei pelo NOC, então sei o que é resolver problema com o cliente online e o rádio caindo
- 📶 Experiência prática com MikroTik (RouterOS, BGP, roteamento, QoS)
- 🏗️ Montagem e manutenção física de hacks de datacenter (cabeamento, energia, climatização, organização de sala)

### 🏠 Homelab & Infraestrutura

[#-homelab--infraestrutura](#-homelab--infraestrutura)

- 🔧 Mantenho um homelab estruturado para testar e validar antes de levar pra produção
- 🐳 Orquestração de containers com Docker
- ☁️ Expandindo conhecimento em AWS (migração de workloads on-prem/homelab para nuvem)
- 🔄 Automatizando o que antes era manual de provisionamento a configuração

### 💻 Desenvolvimento

[#-desenvolvimento](#-desenvolvimento)

- 🛠️ Construo ferramentas para resolver problema de infra, não só configuro na mão
* 📦 Projeto atual: [RouterForge NOC](https://github.com/luciano-veiga/mikrotik-failover-generator)  gerador web de scripts `.rsc` para MikroTik com failover automático entre até 3 links WAN, 100% client-side (HTML/CSS/JS puro, sem backend)
## 🚀 Objetivos Atuais

[#-objetivos-atuais](#-objetivos-atuais)

- ☁️ Aprofundar AWS e arquiteturas híbridas (homelab + nuvem)
- 🐋 Evoluir para Kubernetes, saindo do Docker puro
- 📊 Implementar monitoramento de meu HomeLAB (Grafana + Prometheus) já uso essas ferramentas na operação do ISP
- 📝 Documentar mais o que já sei na prática de config de MikroTik a decisões de arquitetura de datacenter

## 🛠️ Tecnologias

[#-tecnologias](#-tecnologias)

- 🌐 **Redes:** MikroTik/RouterOS, BGP, montagem de datacenter
- ☁️ **Cloud:** AWS
- 🐳 **Infra:** Docker, IaC (em evolução)
- 💻 **Dev:** C#, ASP.NET Core, VueJS
- 🐧 **SO:** Linux

## 📚 Estudo
[#-Estudo](#-estudo)

💡 Atualmente estudo e desenvolvo projetos práticos envolvendo:

Cloud Computing (AWS)
Linux e Automação
Redes e Infraestrutura
Containers e Virtualização
DevOps e Observabilidade
Python e Automação com IA
Agentes de IA e Automação de Fluxos (n8n)

🎯 Meu objetivo é evoluir para desafios em Cloud, DevOps e SRE, unindo a experiência adquirida em infraestrutura tradicional às práticas modernas de engenharia de plataformas.

Aqui você encontrará laboratórios, estudos, projetos, automações e experimentos que fazem parte da minha evolução contínua.

📍 Sempre aberto a aprender, compartilhar conhecimento e construir conexões com profissionais de tecnologia.

<p align="left">
  <a href="https://www.linkedin.com/in/lucianoveiga-ti/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:veiga.luciano@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://wa.me/5577981509804" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
</p>

---

---

## 🚀 Projetos em Destaque

| Projeto | Problema | Solução | Stack Principal |
|---------|----------|---------|-----------------|
| 🔧 **[devops-home-lab](https://github.com/luciano-veiga/devops-home-lab)** | Lab DevOps completo exige múltiplos `docker run` manuais | Stack única via `docker compose up -d` com GitLab, Zabbix, Grafana, MiniStack (AWS local) | Docker Compose, GitLab, Zabbix, Grafana, Prometheus, MinIO, MiniStack |
| 🛡️ **[devsecops-task-manager](https://github.com/luciano-veiga/devsecops-task-manager)** | Pipelines CI/CD sem segurança nativa | Pipeline com SAST (Semgrep), DAST (OWASP ZAP), Container Scan (Trivy), quality gates | GitLab CI, Semgrep, ZAP, Trivy, Node.js, Docker, Kind |
| 📡 **[isp-monitoring-dashboard](https://github.com/luciano-veiga/isp-monitoring-dashboard)** | ISPs operam cegos — Zabbix isolado, sem visão unificada de SLA | API + Dashboard consolida Zabbix → SLA/uptime por PoP, torre, OLT, core + alertas de link | Python, FastAPI, Zabbix API, Prometheus, Grafana, PostgreSQL |
| ☁️ **[aws-terraform-localstack-lab](https://github.com/luciano-veiga/aws-terraform-localstack-lab)** | Testar IaC na AWS real gera custo/risco | Módulos Terraform (VPC, EC2, S3, IAM) com Terratest + Checkov no CI, 100% LocalStack | Terraform, LocalStack, Terratest (Go), Checkov, GitHub Actions |
| 📊 **[homelab-monitoring](https://github.com/luciano-veiga/homelab-monitoring)** | Observabilidade caseira sem alertas, regras nem runbooks | Stack completa: Prometheus + Alertmanager + Grafana + Node Exporter + ServiceMonitors + alertas + runbooks | Prometheus, Alertmanager, Grafana, Node Exporter, Prometheus Operator |
| 🔒 **[linux-hardening-toolkit](https://github.com/luciano-veiga/linux-hardening-toolkit)** | Hardening Linux (CIS) manual, propenso a erro, difícil auditar | Scripts Shell idempotentes + checklist automatizado + validação OpenSCAP em CI (Ubuntu/Alpine) | Shell, OpenSCAP, CIS Benchmarks, Docker, GitHub Actions |

---

## 📜 Certificações

**AWS**
- [AWS Certified Cloud Practitioner](https://www.credly.com/badges/0e405322-90f5-4801-b4dc-8f801d961ffb/public_url)
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/9777f540-902f-4aaf-97aa-985d760590b5/public_url)

**Google / Coursera**
- [Google IT Support Professional Certificate](https://www.credly.com/badges/5ca2644b-9beb-43b2-b668-0e4488cafbdf/public_url)
- [Google Data Analytics Professional Certificate](https://www.credly.com/badges/562e3b4b-0d52-49cb-be49-53a18f25c0c5/public_url)
- [Google Cybersecurity Professional Certificate (v.2)](https://www.credly.com/badges/9a0ea508-c87b-49cc-8876-f906bab91716/public_url)
- [Google AI Essentials](https://www.credly.com/badges/332bf185-6ce1-441f-be0b-aff044d89520/public_url)
- [Google Prompting Essentials](https://www.credly.com/badges/9b498d1a-4bfc-4682-9741-e604fe2ee83c/public_url)

---

## 💻 Linguagens Mais Utilizadas

![](https://github-readme-stats.shion.dev/api/top-langs/?username=luciano-veiga&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)


## 📊 GitHub Stats
[![GitHub Streak](https://streak-stats.demolab.com?user=luciano-veiga&theme=dark&locale=pt_BR)](https://git.io/streak-stats)

---

## 📊 Atividade no GitHub
![Atividade no GitHub](https://raw.githubusercontent.com/luciano-veiga/luciano-veiga/main/profile/activity-graph.svg)



## 👀 Profile Views

![](https://komarev.com/ghpvc/?username=luciano-veiga&color=0e75b6&style=flat-square)

---
