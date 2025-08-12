# CI/CD Pipeline Templates

This repository contains centralized CI/CD pipeline templates for standardized build, test, security scanning, and deployment processes.

## Overview

These templates provide reusable CI/CD components that can be included in application pipelines to ensure consistent processes across projects.

## Available Templates

- `templates/docker-build.yml` - Template for building Docker images
- `templates/security-scan.yml` - Template for security scanning
- `templates/argocd-sync.yml` - Template for ArgoCD synchronization
- `templates/argocd-deployment.yml` - Template for ArgoCD deployments
- `templates/test.yml` - Template for running tests

## Usage

Include these templates in your project's CI/CD configuration:

```yaml
include:
  - project: 'cicd-pipeline-templates'
    file: 'templates/docker-build.yml'
```

## Contribution

1. Create a feature branch
2. Make your changes
3. Submit a merge request
4. Ensure CI passes before merging