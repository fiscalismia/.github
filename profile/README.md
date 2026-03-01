## Fiscalismia-Webservice

**Technical Overview:**
Fullstack Cloudservice consisting of frontend, backend, webscraper, HAproxy loadbalancer, NAT-Gateway, Lambda ETL, S3-storage, prometheus & grafana monitoring with their own respective repositories. Hosted in both Hetzner Cloud and AWS. Fully automated IaC via terraform and github actions.

**Purpose:**
Personal finance web service for visualizing, analyzing, aggregating, importing and exporting financial data with low friction and a high degree of automation.

## Repositories

### **https://github.com/orgs/fiscalismia/repositories**

**FRONTEND (React & Material UI)**        → https://github.com/fiscalismia/fiscalismia-frontend

**BACKEND (NodeJS Express REST API)**         → https://github.com/fiscalismia/fiscalismia-backend

**AWS & Hetzner Cloud Infrastructure**  → https://github.com/fiscalismia/fiscalismia-infrastructure

**HAProxy LoadBalancer**    → https://github.com/fiscalismia/fiscalismia-loadbalancer

**AWS Lambdas**         → https://github.com/fiscalismia/fiscalismia-lambdas

**Webscraper (Python Playwright)**         → https://github.com/fiscalismia/fiscalismia-webscraper

**Prometheus & Grafana Monitoring**      → https://github.com/fiscalismia/fiscalismia-monitoring

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
