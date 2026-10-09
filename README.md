# DevSecOps Pipeline - Jenkins, Docker & Trivy

CI/CD with security gates - SAST, SCA, IaC scanning.

## Pipeline
Jenkins -> SonarQube SAST -> Trivy SCA (blocks HIGH/CRITICAL) -> Checkov IaC -> Docker build (distroless) -> EKS deploy via Helm

## Security
- SonarQube quality gate
- Trivy - no HIGH/CRITICAL CVE
- Checkov 100%
- Distroless images

Tech: Jenkins, GitHub Actions, Docker, Kubernetes EKS, Helm, Trivy, Checkov, Python/Bash

Author: Venugopala Reddy Bhimireddy - Hounslow, UK - Graduate Visa till 7 March 2028 - SOC 2136
