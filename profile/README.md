## Fiscalismia-Webservice

**Technical Overview:**
Fiscalismia Webservice consisting of frontend, backend, loadbalancer, nat-gateway, monitoring and demo instances with their own respective repositories. Hosted in both Hetzner Cloud and AWS. Fully automated IaC via terraform and github actions.

**Purpose:**
Personal finance web service for visualizing, analyzing, aggregating, importing and exporting financial data with low overhead and a high degree of automation.

## Repositories

### **https://github.com/orgs/fiscalismia/repositories**

## Services

**Backend**         → https://github.com/fiscalismia/fiscalismia-backend

**Frontend**        → https://github.com/fiscalismia/fiscalismia-frontend

**Infrastructure**  → https://github.com/fiscalismia/fiscalismia-infrastructure

**Lambdas**         → https://github.com/fiscalismia/fiscalismia-lambdas

**LoadBalancer**    → https://github.com/fiscalismia/fiscalismia-loadbalancer

**Monitoring**      → https://github.com/fiscalismia/fiscalismia-monitoring

---

## CI/CD Pipelines

**Backend Pipeline** → https://github.com/fiscalismia/fiscalismia-backend/actions/workflows/pipeline.yml

**Frontend Pipeline** → https://github.com/fiscalismia/fiscalismia-frontend/actions/workflows/pipeline.yml

**Terraform HCLOUD** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply%20hcloud.yml

**Terraform AWS** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-apply-aws.yml

**Terraform Destroyer** → https://github.com/fiscalismia/fiscalismia-infrastructure/actions/workflows/terraform-module-destroyer.yml

**Lambda Deployment** → https://github.com/fiscalismia/fiscalismia-lambdas/actions/workflows/lambda-deployment.yml

**HAProxy Image** → https://github.com/fiscalismia/fiscalismia-loadbalancer/actions/workflows/publish-haproxy-image.yml

**Monitoring Images** → https://github.com/fiscalismia/fiscalismia-monitoring/actions/workflows/publish-monitoring-images.yml