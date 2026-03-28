# DevSecOps CI/CD Security Pipeline

## Problem

Modern applications are deployed without proper security checks, leading to vulnerabilities.

## Solution

This project implements a secure CI/CD pipeline that integrates multiple security tools to detect vulnerabilities early.

## Tools used

- GitHub Action (CI/CD)
- Docker (containerization)
- Semgrep (SAST)
- Gitleaks (secret scanning)
- npm audit (dependency scanning)
- Trivy (container scanning)
- OWASP ZAP (DAST)

## Pipeline Flow

Developer Push

&darr;

GitHub Actions Pipeline

&darr;

Semgrep (SAST)

&darr;

GitLeaks (secret scan)

&darr;

npm audit (Dependencies scan)

&darr;

Docker Build

&darr;

Trivy (Container Scan)

&darr;

OWASP ZAP (DAST)

## Result

- Early detection of vulnerabilities
- Secure deployment pipeline
