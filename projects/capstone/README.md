# Capstone: [App name] on AWS

> One-paragraph summary: what the app does and what this project demonstrates.

**Status:** Not started · **Live demo / video:** [link]

## Architecture

![Architecture diagram](../../docs/diagrams/capstone-architecture.png)

Short explanation of the main pieces and how they connect.

## Stack
- App: [frontend / API / database]
- Infrastructure: Terraform (remote state in S3)
- Containers: Docker, Kubernetes (Helm), Argo CD
- CI/CD: GitHub Actions (OIDC to AWS, tests, Trivy and Gitleaks scans)
- Observability: Prometheus, Grafana, alerting, centralized logs

## Checklist
- [ ] Infrastructure fully in Terraform (modules, remote state, dev/prod)
- [ ] CI pipeline: lint, test, build, scan, push to ECR
- [ ] Keyless AWS login with OIDC (no stored keys)
- [ ] Deployment through Helm and Argo CD
- [ ] Secrets in AWS Secrets Manager, least-privilege IAM, non-root containers, HTTPS
- [ ] Dashboards and alert rules
- [ ] Load test showing autoscaling
- [ ] One planned failure with a post-mortem
- [ ] Tags, budget alarm, one-command teardown, monthly cost estimate

## How to deploy
```bash
# steps here
```

## How to tear down
```bash
# terraform destroy and any cleanup
```

## Key decisions
Why I chose each tool (short, or link to decision records).

## Cost estimate
Estimated monthly cost and how I kept the bill low.

## What went wrong
The honest list.

## What I'd do next
-
