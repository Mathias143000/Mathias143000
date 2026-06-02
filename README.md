<div align="center">

# Терёшин Матвей 👋
### DevOps Engineer · Platform Engineering · Kubernetes · GitOps

<img src="https://readme-typing-svg.herokuapp.com?size=28&duration=3200&color=F59E0B&center=true&vCenter=true&width=980&lines=DevOps+Engineer;Kubernetes+%7C+GitOps+%7C+Helm;Docker+%7C+Observability+%7C+Security;Runnable+platform+labs+with+runbooks+and+evidence" alt="Typing SVG" />

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

## 👨‍💻 Обо Мне

Я DevOps Engineer с фокусом на Platform Engineering, Kubernetes, GitOps, observability, security и эксплуатационную зрелость систем. Собираю production-like labs так, чтобы их можно было проверить: README, runbooks, smoke tests, CI, evidence, rollback/restore flow и честные ограничения.

Портфолио не продается как реальный production ownership. Это набор воспроизводимых operational scenarios и sanitized evidence, которые показывают инженерное мышление вокруг runtime, delivery, надежности, безопасности и поддержки.

На рабочем месте дополнительно автоматизирую рутинные проверки и внутренние процессы: Outlook-макрос для обработки повторяющихся операций, Go-утилита для проверки сетевых policy-сценариев и разработка внутренней ИС для автоматизации отдела. Публично показываю только обезличенные технические паттерны без служебных данных.

Сейчас ядро витрины состоит из 5 pinned repos:

- `selfhosted-commerce-ops-lab` - flagship Kubernetes platform lab.
- `romanestate-platform-lab` - microservices runtime + AWS/EKS/OpenTofu/FinOps profile.
- `vpn-seller` - компактный stateful service lab.
- `sharechat-realtime-lab` - realtime runtime и capacity lab.
- `is-omir-showcase` - sanitized real-system context без публикации чувствительных данных.

Основные интересы:

- Kubernetes, Helm, GitOps и platform runtime.
- CI/CD, release, rollback и runtime smoke tests.
- Observability: metrics, logs, traces, alerts и incident diagnostics.
- Security и supply chain: dependency audit, Trivy, SBOM, secrets handling, image hygiene.
- Backup/restore, DR, runbooks и operational evidence.
- Cloud/IaC/FinOps boundaries: OpenTofu, AWS/EKS plan-only profile, budgets, tags, cost risks и destroy flow.

---

## 🛠 Основной Стек

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,docker,kubernetes,terraform,aws,postgres,redis,linux,nginx,githubactions,nodejs&theme=light&perline=6" alt="Core stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Runtime-Docker%20%7C%20Compose%20%7C%20Kubernetes-f59e0b?style=flat-square" alt="Runtime" />
  <img src="https://img.shields.io/badge/Delivery-GitHub%20Actions%20%7C%20Helm%20%7C%20Flux-2563eb?style=flat-square" alt="Delivery" />
  <img src="https://img.shields.io/badge/Observability-Prometheus%20%7C%20Grafana%20%7C%20Loki-16a34a?style=flat-square" alt="Observability" />
  <img src="https://img.shields.io/badge/Security-Trivy%20%7C%20SBOM%20%7C%20Secrets-b91c1c?style=flat-square" alt="Security" />
</p>

### Skill Matrix

| Домен | Уверенно применяю | Где видно |
| --- | --- | --- |
| Runtime | Linux, Bash, PowerShell, Docker, Docker Compose, healthchecks, `.dockerignore`, image hygiene | `vpn-seller`, `sharechat-realtime-lab`, `romanestate-platform-lab` |
| Kubernetes Platform | `k3d`, Helm, Flux, probes, requests/limits, securityContext, NetworkPolicy/guardrails | `selfhosted-commerce-ops-lab` |
| CI/CD & Supply Chain | GitHub Actions, dependency audit, Trivy, SBOM, SHA-pinned actions, smoke checks | все runnable pinned repos |
| Observability | Prometheus, Grafana, Loki, Jaeger/Tempo, Alertmanager, runtime diagnostics | `selfhosted-commerce-ops-lab`, `sharechat-realtime-lab` |
| Data & State | PostgreSQL, Redis, MinIO, migrations, backup/restore, restore checks | `vpn-seller`, `romanestate-platform-lab`, `sharechat-realtime-lab` |
| Reliability | runbooks, incident drills, release/rollback, DR boundaries, evidence summaries | `selfhosted-commerce-ops-lab`, `romanestate-platform-lab` |
| Work Automation | Go operator tooling, Outlook macro automation, internal service workflows | `ops-automation-scripts`, `is-omir-showcase` |

### Средний Уровень

`Linux` · `Bash` · `PowerShell` · `Python automation` · `Go basics for tooling` · `Docker` · `Docker Compose` · `Kubernetes local labs` · `k3d` · `Helm` · `Flux` · `GitHub Actions` · `Trivy` · `SBOM` · `Prometheus` · `Grafana` · `Loki` · `PostgreSQL` · `Redis` · `MinIO` · `Nginx` · `runbooks` · `backup/restore` · `rollback`

### Базовый Уровень

`AWS/EKS` · `OpenTofu/Terraform` · `VPC` · `IAM/OIDC/IRSA` · `ECR` · `CloudWatch` · `Infracost` · `Vault` · `External Secrets` · `SOPS` · `Kyverno` · `cosign/provenance concepts` · `Checkov` · `TFLint` · `GitLab CI` · `Jenkins` · `Harbor` · `Rancher` · `Longhorn`

### Как Я Это Применяю

- Автоматизирую повторяющиеся проверки и ручные операции, чтобы снижать зависимость от “ручного клика” и повышать повторяемость результата.
- Оформляю сервисы так, чтобы техлид мог быстро проверить запуск, health, smoke, rollback и known limitations.
- Добавляю observability и evidence не как украшение, а как путь диагностики: что сломалось, где смотреть, как откатывать.
- Не смешиваю публичное портфолио с чувствительными рабочими данными: приватные детали заменяю sanitized architecture/evidence.

---

## 🚀 Избранные Проекты

| Проект | Роль В Портфолио | Что Показывает | Ключевой Стек |
| --- | --- | --- | --- |
| [selfhosted-commerce-ops-lab](https://github.com/Mathias143000/selfhosted-commerce-ops-lab) | Flagship Kubernetes platform lab | k3d, Helm, Flux, Vault/External Secrets, Kyverno, observability, release/break/rollback, incident drill | Kubernetes, Helm, Flux, Prometheus, Grafana, Loki, Jaeger, Alertmanager |
| [romanestate-platform-lab](https://github.com/Mathias143000/romanestate-platform-lab) | Runtime + cloud/FinOps profile | Compose runtime, observability, DR, AWS/EKS/OpenTofu plan-only profile, Infracost/Budgets/tags/destroy flow | Docker Compose, OpenTofu, AWS/EKS, PostgreSQL, Trivy, Checkov |
| [vpn-seller](https://github.com/Mathias143000/vpn-seller) | Compact stateful service lab | Docker, PostgreSQL, migrations, health/readiness, tests, GHCR/cosign/SBOM boundary | Python, PostgreSQL, Docker, GitHub Actions, Trivy, SBOM |
| [sharechat-realtime-lab](https://github.com/Mathias143000/sharechat-realtime-lab) | Realtime runtime and capacity lab | Redis fan-out, MinIO, Nginx, metrics, strict smoke, load/capacity evidence | Node.js, Socket.IO, Redis, MinIO, Nginx, Prometheus |
| [is-omir-showcase](https://github.com/Mathias143000/is-omir-showcase) | Sanitized real-system evidence | Internal operations context, security/data boundaries, RBAC/audit, safe publication rules | Docker/DB/runtime concepts, security, runbooks, data safety |

---

## 📊 GitHub Статистика

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

## 🏗 Архитектурный Подход

Мне близок platform-oriented стиль: система оценивается не только по тому, запускается ли она, но и по тому, насколько ее удобно выкатывать, наблюдать, диагностировать, откатывать и восстанавливать.

Что для меня важно:

- delivery должен быть воспроизводимым, управляемым и понятным оператору;
- сервисы должны иметь health/readiness, smoke path, metrics/logs/traces и runbook;
- secrets, storage, ingress, resource limits и securityContext должны быть частью runtime-дизайна;
- rollback, restore и failure modes нужно продумывать заранее;
- claims в README должны проверяться файлами, командами, CI или evidence.

---

## 🎯 Сейчас Ищу

Интересуют позиции:

- DevOps Engineer
- Platform Engineer
- Kubernetes Engineer
- Infrastructure Engineer
- SRE / Observability Engineer

Особенно интересны:

- инфраструктурные и platform-команды;
- on-prem / hybrid / regulated environments;
- роли, где важны Linux, Kubernetes, CI/CD, observability, security, rollback/recovery и operational maturity.

---

<div align="center">

Спасибо, что заглянули в профиль 👀

</div>
