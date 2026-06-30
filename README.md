# End-to-End CI/CD Pipeline with Jenkins, SonarQube & Nexus

## Project Overview

This project demonstrates how to build an automated Continuous Integration (CI) pipeline using Jenkins on AWS.

The pipeline automatically fetches source code from GitHub, builds the application using Maven, executes unit tests, performs static code analysis with SonarQube, validates the Quality Gate, publishes artifacts to Nexus Repository Manager, and sends build notifications to Slack.

## Architecture
<img width="1332" height="596" alt="architecture-diagram" src="https://github.com/user-attachments/assets/376d0267-c02c-4d75-be78-f6aeb01a5878" />

## CI Pipeline Workflow
Developer

↓

GitHub

↓

Jenkins

↓

Build

↓

Unit Test

↓

Checkstyle

↓

SonarQube Analysis

↓

Quality Gate

↓

Publish Artifact

↓

Nexus Repository

↓

Slack Notification

## Technologies Used
AWS EC2
Jenkins
Maven
Git
GitHub
SonarQube
Nexus Repository Manager
Slack
Java
Linux
Checkstyle

## Features
Pipeline as Code
Automated Build
Unit Testing
Code Quality Analysis
Quality Gates
Artifact Repository
Slack Notifications
Versioned Artifacts

## Jenkins Pipeline Stages
| Stage              | Purpose                   |
| ------------------ | ------------------------- |
| Fetch Code         | Clone project from GitHub |
| Build              | Build Java application    |
| Unit Test          | Execute tests             |
| Checkstyle         | Static code analysis      |
| SonarQube          | Analyze code quality      |
| Quality Gate       | Validate quality          |
| Publish Artifact   | Upload WAR to Nexus       |
| Slack Notification | Send build result         |

## Screenshots
01-aws-ec2-instances.png
02-security-groups.png
04-installed-plugins.png
05-pipeline-stage-view.png
06-sonarqube-dashboard.png
07-quality-gate-passed.png
08-nexus-repository.png
09-uploaded-artifact.png
10-slack-notification.png
11-build-history.png

## Skills Demonstrated
CI/CD
Jenkins
AWS
Linux
Maven
SonarQube
Nexus
Slack Integration
Pipeline as Code

## Future Improvements
Docker
Amazon ECR
Kubernetes
Terraform
Ansible
GitHub Actions
GitOps
Monitoring & Observability
