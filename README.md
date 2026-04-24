<div align="center">

# Терёшин Матвей 👋
### DevOps Engineer · Kubernetes · GitOps · On-Prem Platform

<img src="https://readme-typing-svg.herokuapp.com?size=28&duration=3200&color=F59E0B&center=true&vCenter=true&width=980&lines=DevOps+Engineer;Kubernetes+%7C+Flux+%7C+Helm;Go+starter+templates+%7C+Vault+%7C+MetalLB+%7C+Traefik;Building+runnable+platform+labs+with+runbooks+and+drills" alt="Typing SVG" />

<br>

<a href="https://vk.com/id465453768">
  <img src="https://img.shields.io/badge/VK-0077FF?style=for-the-badge&logo=vk&logoColor=white" alt="VK" />
</a>
<a href="https://t.me/LDZHR">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
</a>
<a href="mailto:teriomta5@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<br><br>
<img src="https://komarev.com/ghpvc/?username=Mathias143000&style=flat-square&color=f59e0b" alt="Profile views" />

</div>

---

## 👨‍💻 Обо мне

Я DevOps Engineer с platform-minded фокусом на контейнерные платформы, Kubernetes-кластеры, GitOps, observability и эксплуатационную зрелость систем.  
Собираю production-style стенды целиком: от Linux-автоматизации, routing и secret delivery до логирования, метрик, трейсинга, rollback/recovery и runbooks.

Сейчас ядро портфолио состоит из `12` отдельных DevOps-репозиториев: platform labs, workload-стендов, observability/IaC/DR/DataOps/MLOps кейсов. Сильная сторона этой витрины в том, что проекты оформлены как runnable инженерные стенды: с README, архитектурной схемой, quick demo flow, runbooks, smoke/evidence path и понятными ограничениями.

Отдельно важно текущее состояние platform-линии: `platform-engineering-starter-kit` теперь показывает golden path не только для Python, но и для Go. Это усиливает портфолио не новым случайным языком, а platform enablement сигналом: service bootstrap, health/readiness/metrics contract, Docker pattern и минимальный CI под единым шаблоном.

Основные интересы:

- on-prem и hybrid Kubernetes-платформы
- GitOps и управляемый delivery flow
- monitoring / logging / tracing / SRE-практики
- отказоустойчивость, rollback и disaster recovery
- platform enablement, golden paths и service bootstrap
- внутренние platform-команды, enterprise и regulated-контуры

Для инфраструктурных вакансий наиболее релевантны мои стенды и enablement-репозитории:

- `enterprise-onprem-platform-lab`
- `micro-service-stand`
- `k8s-gitops-platform-lab`
- `monitoring-stack-demo`
- `terraform-cloud-foundation-lab`
- `postgres-dr-lab`
- `platform-engineering-starter-kit`

---

## 🛠 Основной стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,bash,docker,kubernetes,terraform,aws,postgres,redis,linux,nginx,githubactions&theme=light&perline=6" alt="Core stack" />
</p>

В иконках оставлен только core-стек, чтобы верхняя часть README не выглядела перегруженной. Полный набор технологий указан ниже по категориям.

### Технологии

- Linux / Bash / Python / Go / PowerShell / SQL
- Docker / Docker Compose / container runtime operations
- Kubernetes / `k3s` / `k3d` / Helm / Flux / Argo CD / cert-manager
- Nginx / Traefik / MetalLB / ingress / service exposure / reverse proxy
- Vault / External Secrets / SOPS / secret workflows
- Prometheus / Grafana / Alertmanager / Loki / Jaeger / Tempo / OpenTelemetry / Grafana Alloy / Promtail
- PostgreSQL / Redis / RabbitMQ / MinIO / pgBackRest / S3 / DynamoDB
- Terraform / AWS / IaC / GitHub Actions / backup-restore / runbooks / drills
- Django REST Framework / FastAPI / Socket.IO / SQLAlchemy / MLflow

### Что особенно релевантно для инфраструктурных вакансий

- multi-node Kubernetes clusters и reproducible bootstrap
- GitOps delivery, rollout и rollback
- platform starter templates и единый service contract для новых сервисов
- ingress routing, балансировка и north-south exposure
- секреты и конфигурация через Vault-подход
- observability не только на словах, а через metrics/logs/traces/evidence
- DR и recovery-мышление через отдельные backup/restore стенды

### Enterprise-aligned focus

Практический hands-on в портфолио сейчас особенно сильный в связке:

- `Flux`
- `Vault`
- `MetalLB`
- `Traefik`
- `Jaeger`
- `MinIO`
- multi-node `k3d/k3s`

Параллельно хорошо понимаю место в enterprise-архитектуре для:

- `GitLab CI/CD`
- `Harbor`
- `Rancher`
- `Longhorn`
- service mesh patterns

---

## 🚀 Избранные проекты

| Проект | Роль в портфолио | Зачем нужен | Что показывает | Ключевой стек |
|---|---|---|---|---|
| [enterprise-onprem-platform-lab](https://github.com/Mathias143000/enterprise-onprem-platform-lab) | Enterprise / on-prem flagship | Нужен как главный мост к инфраструктурным, государственным и regulated-вакансиям с акцентом на внутренние платформы | multi-node `k3d/k3s`, `Flux`, `Helm`, `MetalLB`, `Traefik`, `Vault`, `External Secrets`, `MinIO`, `Prometheus`, `Grafana`, `Loki`, `Jaeger`, release → break → rollback drill | `k3s`, Flux, Helm, Vault, MetalLB, Traefik, MinIO, Jaeger |
| [micro-service-stand](https://github.com/Mathias143000/micro-service-stand) | Supporting service-platform lab | Нужен как стенд про workload topology: service extraction, edge, async dependencies, observability и backup/restore вокруг реальных сервисов | service extraction, `nginx` edge, observability stack, backup/restore, Python automation, recovery story, DoD-готовая витрина | Docker Compose, Nginx, PostgreSQL, Redis, RabbitMQ, MinIO, Prometheus, Grafana, Alertmanager, Loki, Tempo, OpenTelemetry |
| [k8s-gitops-platform-lab](https://github.com/Mathias143000/k8s-gitops-platform-lab) | Baseline Kubernetes / GitOps lab | Нужен как чистый cloud-native кейс про delivery lifecycle до более тяжёлого enterprise/on-prem сценария | `Helm`, Argo CD, ingress, TLS automation, HPA, GitOps rollout/rollback, secret flow и reproducible cluster bootstrap | Kubernetes, Helm, Argo CD, cert-manager, SOPS, GitOps |
| [monitoring-stack-demo](https://github.com/Mathias143000/monitoring-stack-demo) | Observability flagship | Нужен как отдельный SRE-слой для диагностики, алертов и инцидентного evidence | dashboards, alerting, centralized logs, traces, synthetic checks, incident evidence collection | Prometheus, Grafana, Alertmanager, Loki, Jaeger, Tempo |
| [terraform-cloud-foundation-lab](https://github.com/Mathias143000/terraform-cloud-foundation-lab) | IaC flagship | Нужен как отдельная история про инфраструктурное проектирование, remote state и environment lifecycle | reusable modules, remote state, IAM, networking, apply/destroy/import runbooks, evidence of locking and state workflow | Terraform, AWS, S3, DynamoDB, IAM, VPC |
| [postgres-dr-lab](https://github.com/Mathias143000/postgres-dr-lab) | Reliability / DR flagship | Нужен для демонстрации зрелости в recovery, а не только в выкладке сервисов | backup automation, restore drill, corruption simulation, verification, freshness metrics, recovery runbook | PostgreSQL, pgBackRest, Go, Bash, Python, Prometheus |
| [platform-engineering-starter-kit](https://github.com/Mathias143000/platform-engineering-starter-kit) | Platform enablement showcase | Нужен как отдельный кейс про internal developer platform и golden path для нового сервиса | единый starter path для `Python` и `Go`, health/readiness/liveness, `/metrics`, structured logging, Docker pattern, minimal CI, docs/runbook scaffolding | Go, Python, Docker, Prometheus, GitHub Actions, starter CLI |

### Остальные проекты

| Проект | Что дополняет | Стек |
|---|---|---|
| [service-desk-api](https://github.com/Mathias143000/service-desk-api) | Production-style workload для Kubernetes/GitOps/on-prem стендов: auth/RBAC, SLA-oriented API, health/metrics path | Django REST Framework, PostgreSQL, Redis, Celery, Docker, OpenTelemetry |
| [webhook-ingestion-service](https://github.com/Mathias143000/webhook-ingestion-service) | Event-driven слой: webhook intake, retries, idempotency, очереди, worker flow и observability | FastAPI, RabbitMQ, Redis, PostgreSQL, Prometheus, Tempo |
| [ShareChat](https://github.com/Mathias143000/share-chat) | Stateful / real-time workload: persistent connections, shared state, uploads, reverse proxying и reconnect behavior | Node.js, Socket.IO, Redis, MinIO, Nginx, Prometheus |
| [weather-etl-pipeline](https://github.com/Mathias143000/weather-etl-pipeline) | DataOps-покрытие: ETL orchestration, freshness, pipeline reliability и evidence-oriented data runtime | Python, SQLAlchemy, PostgreSQL, ETL tooling, quality gates |
| [eyewear-detection-pipeline](https://github.com/Mathias143000/eyewear-detection-pipeline) | MLOps-покрытие: model lifecycle, serving flow, artifacts, observability и inference operations | Python, FastAPI, MLflow, MinIO, PostgreSQL, Prometheus, Grafana, Loki |

---

## 📊 GitHub статистика

<p align="center">

<img height="170" src="https://streak-stats.demolab.com?user=Mathias143000&theme=default&hide_border=true&background=FFF7ED&ring=F59E0B&fire=F59E0B&currStreakLabel=C2410C&sideNums=D97706&sideLabels=9A3412&dates=7C2D12&stroke=FED7AA"/>

</p>

---

## 📈 Активность

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Mathias143000" alt="Profile summary" />

</div>

<br>

---

## 🏗 Архитектурный подход

Мне ближе platform-oriented инженерный стиль, где система оценивается не только по тому, запускается ли она, но и по тому, насколько её удобно выкатывать, наблюдать, балансировать, откатывать и восстанавливать.

### Что для меня важно

- delivery должен быть воспроизводимым, управляемым и понятным оператору
- новый сервис должен стартовать с понятного golden path, а не с импровизации
- сервисы и platform-компоненты должны иметь healthchecks, metrics, logs и traces
- ingress, балансировка, secrets, storage и routing должны быть частью архитектуры, а не “потом прикрутим”
- rollback, recovery и failure modes нужно продумывать заранее
- README, диаграммы, runbooks, evidence и known limitations должны быть оформлены явно

### Как я обычно подхожу к проектам

- проектирую сервисные и инфраструктурные границы
- собираю reproducible runtime через контейнеры, compose или Kubernetes
- там, где это уместно, закладываю reusable starter kit / service contract
- настраиваю CI/CD и, где нужно, GitOps delivery
- добавляю observability: metrics, logs, traces, dashboards, alerts
- оформляю smoke path, rollback/recovery flow и maintenance runbooks
- довожу проект до состояния `portfolio visible ready`

### Мой слой архитектуры

**Users / Internal teams**

**Delivery слой**  
CI/CD / GitOps / Helm / release flow / rollback

**Runtime слой**  
Docker / Kubernetes / `k3s` / Nginx / Traefik / ingress

**Platform capabilities**  
Vault / MetalLB / MinIO / storage / service exposure / health model

**Data и messaging**  
PostgreSQL / Redis / RabbitMQ / object storage

**Observability и reliability**  
Prometheus / Grafana / Loki / Jaeger / Tempo / runbooks / drills / DR

---

## 🎯 Сейчас ищу

Интересуют позиции:

- DevOps Engineer
- Platform Engineer
- Kubernetes Engineer
- Infrastructure Engineer
- SRE / Observability Engineer

Особенно интересны:

- государственные и инфраструктурные команды
- телеком, enterprise и regulated-контуры
- внутренние платформенные команды
- on-prem / hybrid environments
- роли, где важны Linux, Kubernetes, observability, rollback/recovery и operational maturity

---

<div align="center">

Спасибо, что заглянули в профиль 👀

</div>
