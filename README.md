# AWS Infrastructure Lifecycle Lab

A hands-on infrastructure engineering project using Terraform,
Ansible, Git, GitHub Actions, and AWS.

## Objectives

- Provision AWS networking and EC2 infrastructure using Terraform.
- Configure Linux services using Ansible.
- Implement Git branching and pull request workflows.
- Validate infrastructure changes using GitHub Actions.
- Practice controlled infrastructure deployments.
- Introduce an EBS data volume through a formal change request.

## Infrastructure

- AWS Region: us-east-2
- VPC: 10.60.0.0/16
- Public subnet: 10.60.1.0/24
- Ubuntu EC2 instance
- Nginx web server
- Grafana Alloy monitoring

## Development Workflow

Infrastructure changes are developed locally, committed to feature
branches, validated through CI, and reviewed before deployment.