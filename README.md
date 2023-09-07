# Example Project

## Introduction

TODO: Add project description

## Project Structure

- `.github` directory contains GitHub Actions workflow and custom GitHub Action implementations
- `app` directory contains application code for Google Cloud Function
- `scripts` directory contains one-off administrative shell scripts
- `terraform` directory contains IaC Terraform configuration and environment specific .tfvar files
- `deploy_cloud_function.yaml` file contains CloudBuild script to deploy Google Cloud Function
- `deploy_terraform.yaml` file contains CloudBuild script to deploy Terraform (IaC)

### Prerequisites

[pre-commit](https://pre-commit.com/) - A framework for managing and
maintaining multi-language pre-commit hooks

```bash
brew install pre-commit
```

### Installation

Install all dependencies used by pre-commit hooks.
To run all pre-commit hooks:

```bash
pre-commit run --all-files
```

### Latest releases

See CHANGELOG.md at the root of the project.
See `.github/workflows/workflow.yaml` for release pipeline definition.

### Build and Test

Pre-commit hooks are used to lint, validate, and run static code analysis for security best-practices.

## Contribute

TODO: Explain how other users and developers can contribute to make your code better.
