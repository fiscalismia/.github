## Fiscalismia-Webservice

**Technical Overview:**
Fiscalismia Webservice consisting of frontend, backend, loadbalancer, haproxy nat-gateway, prometheus & grafana monitoring with their own respective repositories. Hosted in both Hetzner Cloud and AWS. Fully automated IaC via terraform and github actions.

**Purpose:**
Personal finance web service for visualizing, analyzing, aggregating, importing and exporting financial data with low overhead and a high degree of automation.

## Repositories

### **https://github.com/orgs/fiscalismia/repositories**

**Backend**         → https://github.com/fiscalismia/fiscalismia-backend

**Frontend**        → https://github.com/fiscalismia/fiscalismia-frontend

**Infrastructure**  → https://github.com/fiscalismia/fiscalismia-infrastructure

**Lambdas**         → https://github.com/fiscalismia/fiscalismia-lambdas

**LoadBalancer**    → https://github.com/fiscalismia/fiscalismia-loadbalancer

**Monitoring**      → https://github.com/fiscalismia/fiscalismia-monitoring

---

## CI/CD Pipelines

**Backend Pipeline** → https://github.com/fiscalismia/fiscalismia-backend/actions/workflows/backend-pipeline.yml

**Frontend Pipeline** → https://github.com/fiscalismia/fiscalismia-frontend/actions/workflows/frontend-pipeline.yml

**Webservice Deployment Pipeline**  → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/webservice-deployment-pipeline.yml

**DNS TLS Certificate Validation**  → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/fetch-and-validate-tls-certs.yml

**Security-Evaluation HCLOUD**  → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/security-evaluation-hcloud.yml

**HCLOUD Terraform Pipeline** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-hcloud.yml

**AWS Terraform Pipeline** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-aws.yml

**TerraformModuleDestroyer Pipeline** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-module-destroyer.yml

**Lambdas Deployment Pipeline** → https://github.com/fiscalismia/fiscalismia-lambdas/actions/workflows/lambda-deployment.yml

**Loadbalancer Pipeline** → https://github.com/fiscalismia/fiscalismia-loadbalancer/actions/workflows/publish-haproxy-image.yml

**Monitoring Pipeline** → https://github.com/fiscalismia/fiscalismia-monitoring/actions/workflows/monitoring-pipeline.yml