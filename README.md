# DevSecOps Security Lab

## Overview

This project demonstrate a complete DevSecOps security pipeline integrating multiple security scanning tools within Github Actions.

---

## Security Tools Integrated

- Semgrep (SAST)
- Gitleaks (Secret Detection)
- npm audit (Dependency Scanning)
- Trivy (Container Scanning)
- OWASP ZAP (Dynamic Application Security Testing)

---

## CI/CD Pipeline

The security pipeline runs authomatically on every push and performs:

1. Static code analysis
2. Secret scanning
3. Dependency vulnerability detection
4. Container vulnerability scanning
5. Dynamic security testing

---

## Teck Stack

Node.js

Docker

Github Action

---

## Purpose

This lab demonstrates practical DevSecOps security automation techniques used in modern cloud-native environments

---

## Pipeline Architecture Diagram

Developer Push

&darr;

GitHub Actions Pipeline

&darr;

Semgrep (SAST)

&darr;

GitLeaks (Eecret)

&darr;

npm audit (Dependencies)

&darr;

Docker Build

&darr;

Trivy (Container Scan)

&darr;

OWASP ZAP (DAST)
