## Fiscalismia-Webservice

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=aws&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?logo=hetzner&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?logo=podman&logoColor=white)
![Buildah](https://img.shields.io/badge/Buildah-CC0000?logo=buildah&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-003399?logo=haproxy&logoColor=white)
![nftables](https://img.shields.io/badge/nftables-005AF0?logo=nftables&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?logo=snyk&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

**Technical Overview:**
Fullstack Cloudservice consisting of frontend, backend, webscraper, HAproxy loadbalancer, NAT-Gateway, Lambda ETL, S3-storage, prometheus & grafana monitoring with their own respective repositories. Hosted in both Hetzner Cloud and AWS. Fully automated IaC via terraform and github actions.

**Purpose:**
Personal finance web service for visualizing, analyzing, aggregating, importing and exporting financial data with low friction and a high degree of automation.

## Repositories

### **https://github.com/orgs/fiscalismia/repositories**

**FRONTEND (React & Material UI)**        → https://github.com/fiscalismia/fiscalismia-frontend ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-frontend) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-frontend) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-frontend) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-frontend)

**BACKEND (NodeJS Express REST API)**         → https://github.com/fiscalismia/fiscalismia-backend ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-backend) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-backend) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-backend) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-backend)

**AWS & Hetzner Cloud Infrastructure**  → https://github.com/fiscalismia/fiscalismia-infrastructure ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-infrastructure) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-infrastructure) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-infrastructure) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-infrastructure)

**HAProxy LoadBalancer**    → https://github.com/fiscalismia/fiscalismia-loadbalancer ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-loadbalancer) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-loadbalancer) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-loadbalancer) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-loadbalancer)

**AWS Lambdas**         → https://github.com/fiscalismia/fiscalismia-lambdas ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-lambdas) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-lambdas) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-lambdas) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-lambdas)

**Webscraper (Python Playwright)**         → https://github.com/fiscalismia/fiscalismia-webscraper ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-webscraper) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-webscraper) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-webscraper) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-webscraper)

**Prometheus & Grafana Monitoring**      → https://github.com/fiscalismia/fiscalismia-monitoring ![](https://img.shields.io/github/repo-size/fiscalismia/fiscalismia-monitoring) ![](https://img.shields.io/github/languages/top/fiscalismia/fiscalismia-monitoring) ![](https://img.shields.io/github/last-commit/fiscalismia/fiscalismia-monitoring) ![](https://img.shields.io/github/commit-activity/y/fiscalismia/fiscalismia-monitoring)

---

## CI/CD Pipelines

### _OCI Image publishing_

- [![Frontend Pipeline](https://github.com/fiscalismia/fiscalismia-frontend/actions/workflows/frontend-pipeline.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-frontend/actions/workflows/frontend-pipeline.yml) ← [Dockerfile](https://github.com/fiscalismia/fiscalismia-frontend/blob/main/Dockerfile)

- [![Backend Pipeline](https://github.com/fiscalismia/fiscalismia-backend/actions/workflows/backend-pipeline.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-backend/actions/workflows/backend-pipeline.yml) ← [Dockerfile](https://github.com/fiscalismia/fiscalismia-backend/blob/main/Dockerfile)

- [![Webscraper Pipeline](https://github.com/fiscalismia/fiscalismia-webscraper/actions/workflows/webscraper-pipeline.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-webscraper/actions/workflows/webscraper-pipeline.yml) ← [Dockerfile](https://github.com/fiscalismia/fiscalismia-webscraper/blob/main/Dockerfile)

- [![Loadbalancer Pipeline](https://github.com/fiscalismia/fiscalismia-loadbalancer/actions/workflows/publish-haproxy-image.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-loadbalancer/actions/workflows/publish-haproxy-image.yml) ← [Dockerfile](https://github.com/fiscalismia/fiscalismia-loadbalancer/blob/main/Dockerfile)

- [![Monitoring Pipeline](https://github.com/fiscalismia/fiscalismia-monitoring/actions/workflows/publish-prometheus-grafana-images.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-monitoring/actions/workflows/publish-prometheus-grafana-images.yml) ← [Dockerfile.Prometheus](https://github.com/fiscalismia/fiscalismia-monitoring/blob/main/Dockerfile.Prometheus) [Dockerfile.Grafana](https://github.com/fiscalismia/fiscalismia-monitoring/blob/main/Dockerfile.Grafana)

### _Target Server Deployment_

- [![Webservice Deployment Pipeline](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/webservice-deployment-pipeline.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/webservice-deployment-pipeline.yml)

- [![Infrastructure Deployment Pipeline](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/infrastructure-deployment-pipeline.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/infrastructure-deployment-pipeline.yml)

### _Security & Networking_

- [![DNS TLS Certificate Validation](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/fetch-and-validate-tls-certs.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/fetch-and-validate-tls-certs.yml)

- [![Security-Evaluation HCLOUD](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/security-evaluation-hcloud.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/security-evaluation-hcloud.yml)

### _Cloud Infrastructure Provisioning_

- [![HCLOUD Terraform Pipeline](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-hcloud.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-hcloud.yml)

- [![AWS Terraform Pipeline](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-aws.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-aws.yml)

- [![TerraformModuleDestroyer Pipeline](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-module-destroyer.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-module-destroyer.yml)

- [![Lambdas Deployment Pipeline](https://github.com/fiscalismia/fiscalismia-lambdas/actions/workflows/lambda-deployment.yml/badge.svg)](https://github.com/fiscalismia/fiscalismia-lambdas/actions/workflows/lambda-deployment.yml)
