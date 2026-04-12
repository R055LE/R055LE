# A Wild R055LE Appears 🍍

Sr. DevSecOps Engineer | 13 years in IT | Biochemistry degree I've never used for biochemistry

I walk into environments with no documentation, no CI/CD, and no observability, and I leave behind infrastructure that actually works. Federal/DoD compliance, Iron Bank containers, Platform One deployments, and the less glamorous stuff — migrating legacy systems between clouds without losing data and untangling years of manual deployment processes.

## What I'm Working On

Hands-on labs and templates for secure, production-grade infrastructure.

- 🔒 [Container Hardening Lab](https://github.com/R055LE/container-hardening-lab) — CIS/Iron Bank-aligned container hardening — non-root builds, OPA/Kyverno policy enforcement, Cosign signing, SBOM generation, and Falco runtime detection
- 🏗️ [IaC Security Lab](https://github.com/R055LE/iac-security-lab) — Policy-as-code for Terraform — tfsec, Trivy, and OPA/Rego static analysis against CIS AWS Foundations Benchmark; no cloud credentials required
- ☸️ [K8s Bootstrap Lab](https://github.com/R055LE/k8s-bootstrap-lab) — Production-grade Kubernetes platform bootstrap: GitOps, observability, and runtime security from Kind to EKS
- 🤖 [MLOps Pipeline Lab](https://github.com/R055LE/mlops-pipeline-lab) — Production-grade MLOps deployment pipeline: container hardening, CI/CD, GitOps, observability, and Kyverno policy enforcement around a HuggingFace model
- 🚀 [Go Deploy Lab](https://github.com/R055LE/go-deploy-lab) — Go application through the full deployment lifecycle: multi-stage distroless builds, Kubernetes manifests, rolling updates, Kyverno policies, Prometheus metrics, Grafana dashboards, CI with Trivy + SBOM
- 📟 [SRE Observability Lab](https://github.com/R055LE/sre-observability-lab) — SLO-based alerting, error budget burn-rate math, chaos engineering with documented outcomes, runbooks linked from alerts, request ID correlation across services, promtool-tested alert rules

## How They Connect

```
IaC Security Lab                Container Hardening Lab
  Terraform policies              Dockerfile policies, Cosign signing,
  CIS AWS Benchmark               SBOM generation, Falco runtime
        │                                   │
        ▼                                   ▼
K8s Bootstrap Lab ◄──────────── MLOps Pipeline Lab
  Kind / EKS platform              HuggingFace model serving
  GitOps, observability,           CI/CD, GitOps, Kyverno
  runtime security                 policy enforcement
        ▲                                   
        │                                   
Go Deploy Lab ─────────────►  SRE Observability Lab
  Go app, deployment lifecycle      SLOs, burn-rate alerts,
  distroless, Kyverno, CI           chaos engineering, runbooks
```

The labs are designed to be read together. IaC Security hardens the infrastructure layer. Container Hardening secures the runtime. K8s Bootstrap provisions the platform. MLOps Pipeline deploys a real workload on top of it. Go Deploy Lab takes a Go application through the full deployment lifecycle. SRE Observability Lab builds on those patterns to demonstrate actually operating services — SLO definitions, multi-window burn-rate alerting, chaos scenarios, and runbooks.

## Outside the Stack

- 👾 [Horror Battler](https://github.com/R055LE/horror-battler) — Dark auto-battler demo; cursed creatures, grotesque synergies, watch them murder each other

## Toolkit

`Kubernetes` `Terraform` `Docker` `Helm` `ArgoCD` `Ansible` `GitLab CI/CD` `GitHub Actions` `HashiCorp Vault` `Grafana` `Prometheus` `Loki` `Alertmanager` `AWS` `Azure` `GCP` `Go` `Python` `Bash`

## Detroit, MI
