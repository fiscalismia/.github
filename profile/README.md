## Fiscalismia-Webservice

**Technical Overview:**
Fiscalismia Webservice consisting of frontend, backend, loadbalancer, haproxy nat-gateway, prometheus & grafana monitoring with their own respective repositories. Hosted in both Hetzner Cloud and AWS. Fully automated IaC via terraform and github actions.

**Purpose:**
Personal finance web service for visualizing, analyzing, aggregating, importing and exporting financial data with low overhead and a high degree of automation.

## Repositories

### **https://github.com/orgs/fiscalismia/repositories**

**Express Backend**         → https://github.com/fiscalismia/fiscalismia-backend

**React & Material UI Frontend**        → https://github.com/fiscalismia/fiscalismia-frontend

**Cloud Infrastructure**  → https://github.com/fiscalismia/fiscalismia-infrastructure

**AWS Lambdas**         → https://github.com/fiscalismia/fiscalismia-lambdas

**HAProxy LoadBalancer**    → https://github.com/fiscalismia/fiscalismia-loadbalancer

**Prometheus & Grafana Monitoring**      → https://github.com/fiscalismia/fiscalismia-monitoring

---

## CI/CD Pipelines

### _OCI Container publishing_

- **Backend Pipeline** → [backend-pipeline.yml](https://github.com/fiscalismia/fiscalismia-backend/actions/workflows/backend-pipeline.yml)

- **Frontend Pipeline** → [frontend-pipeline.yml](https://github.com/fiscalismia/fiscalismia-frontend/actions/workflows/frontend-pipeline.yml)

- **Loadbalancer Pipeline** → [publish-haproxy-image.yml](https://github.com/fiscalismia/fiscalismia-loadbalancer/actions/workflows/publish-haproxy-image.yml)

- **Monitoring Pipeline** → [publish-prometheus-grafana-images.yml](https://github.com/fiscalismia/fiscalismia-monitoring/actions/workflows/publish-prometheus-grafana-images.yml)

### _Target Server Deployment_

- **Webservice Deployment Pipeline** → [webservice-deployment-pipeline.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/webservice-deployment-pipeline.yml)

### _Security & Networking_

- **DNS TLS Certificate Validation** → [fetch-and-validate-tls-certs.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/fetch-and-validate-tls-certs.yml)

- **Security-Evaluation HCLOUD** → [security-evaluation-hcloud.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/security-evaluation-hcloud.yml)

### _Cloud Infrastructure Provisioning_

- **HCLOUD Terraform Pipeline** → [terraform-apply-hcloud.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-hcloud.yml)

- **AWS Terraform Pipeline** → [terraform-apply-aws.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-aws.yml)

- **TerraformModuleDestroyer Pipeline** → [terraform-module-destroyer.yml](https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-module-destroyer.yml)

- **Lambdas Deployment Pipeline** → [lambda-deployment.yml](https://github.com/fiscalismia/fiscalismia-lambdas/actions/workflows/lambda-deployment.yml)
