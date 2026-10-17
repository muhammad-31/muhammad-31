# Muhammad Bin Amir

**DevOps & Cloud Engineer · Certified Kubernetes Administrator (CKA) · Microsoft Certified: DevOps Engineer Expert (AZ-400)**

I build and run production infrastructure for a healthcare platform, and
automate data pipelines and audit analytics in banking. My focus: AWS and
Terraform, Kubernetes with GitOps, CI/CD pipelines that scan every change
before it ships, and monitoring that alerts on what users actually feel.

## Featured projects

| Project | What it shows |
|---|---|
| [aws-ecs-fargate-terraform](https://github.com/muhammad-31/aws-ecs-fargate-terraform) | Containerised app on AWS: VPC, ALB + WAF, ECS Fargate, RDS PostgreSQL, alarms. Terraform modules with unit tests, GitHub Actions deploys over OIDC (no stored keys). |
| [gitops-argocd-platform](https://github.com/muhammad-31/gitops-argocd-platform) | Kubernetes platform reconciled by Argo CD: Envoy Gateway, cert-manager, Kyverno CEL policies with tests, a hardened Helm chart, end-to-end CI on kind. |
| [k8s-observability-stack](https://github.com/muhammad-31/k8s-observability-stack) | Prometheus, Alertmanager, Grafana, Loki and Alloy. SLO burn-rate alerts with promtool tests, tested alert routing, runbooks, dashboards as code. |
| [ansible-docker-host](https://github.com/muhammad-31/ansible-docker-host) | Ansible roles that turn a fresh Ubuntu server into a hardened Docker host with Nginx, Let's Encrypt and restic backups. Molecule-tested and idempotent. |
| [devsecops-eks-blog-platform](https://github.com/muhammad-31/devsecops-eks-blog-platform) | Full-stack app on EKS Auto Mode with a gated DevSecOps pipeline (ESLint, npm audit, Checkov, Hadolint, Trivy) and Argo CD. |

## Certifications

- **Certified Kubernetes Administrator (CKA)**, The Linux Foundation
- **Microsoft Certified: DevOps Engineer Expert (AZ-400)**, Microsoft

## Tools I work with

**Cloud:** AWS (ECS, EKS, RDS, VPC, IAM, CloudWatch, WAF), Azure DevOps<br>
**IaC and config:** Terraform / OpenTofu, Ansible, Helm, Kustomize<br>
**Containers:** Docker, Kubernetes, Argo CD, Gateway API<br>
**CI/CD and security:** GitHub Actions, Checkov, Trivy, Kyverno, OIDC federation<br>
**Observability:** Prometheus, Grafana, Loki, Alertmanager

## How I work

- Infrastructure is code, reviewed in pull requests and tested before it is applied.
- Security checks block the pipeline instead of producing reports nobody reads.
- Every alert links to a runbook. If nobody would act on it, it is not an alert.
- Clear documentation and a clean handover, so your team can run what I build.
