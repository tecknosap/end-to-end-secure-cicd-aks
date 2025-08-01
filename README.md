# Project 7: End-to-End Secure CI/CD Pipeline: Terraform → Docker → AKS

## Overview

This project encapsulates a real enterprise engagement to build a comprehensive, secure CI/CD pipeline automating infrastructure provisioning, container builds, security scanning, and application deployment on AKS.

## Business Problem Solved

Fragmented pipelines and manual handoffs create delays and security risks. Enterprises need integrated, automated pipelines that enforce compliance and reduce time to production.

## What You Will Build

- GitHub Actions workflows orchestrating:
  - Azure authentication via OIDC.
  - Terraform provisioning with remote backend.
  - Docker image build, scan (Trivy), and push to Azure Container Registry.
  - Helm deployment of microservice with runtime secrets.
- Branch protection, code review enforcement, and pipeline auditing.
- Deployment validations and automated rollback on failures.

## Enterprise Impact

- Delivers faster, safer software releases.
- Ensures end-to-end pipeline security and compliance.
- Provides reproducible infrastructure and application deployments.

## Step-by-Step

1. Set up GitHub Actions workflows for each pipeline stage.
2. Configure OIDC-based Azure login for CI.
3. Implement Terraform provisioning with secure state storage.
4. Add Docker build, Trivy scan, and ACR push steps.
5. Deploy microservice with Helm and secure runtime secrets.
6. Enable branch protections and pipeline audits.
7. Test and monitor pipeline executions.

## Prerequisites

- Azure subscription with required roles
- GitHub repository with Actions enabled
- Local CLI tools: Terraform, Docker, Helm

## References

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Azure Container Registry](https://learn.microsoft.com/en-us/azure/container-registry/)
