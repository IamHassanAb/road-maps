# Deep Dive — DevOps / Cloud Engineer

---

## Career levels

=== "Junior (0–2 yrs)"
    **Focus:** Maintain CI/CD pipelines, respond to alerts, write basic scripts and IaC.

    `Linux & Bash` `Git` `Docker basics` `AWS / GCP fundamentals` `CI/CD (GitHub Actions)` `Basic monitoring (Grafana)` `Python scripting`

=== "Mid-level (2–5 yrs)"
    **Focus:** Build and own infrastructure, implement observability, improve deployment reliability.

    `Kubernetes (deployments, services)` `Terraform / Pulumi` `Prometheus & alerting` `Log aggregation (ELK / Loki)` `SRE practices` `Secrets management (Vault)` `Helm charts` `Incident response`

=== "Senior (5–10 yrs)"
    **Focus:** Design platform architecture, drive reliability standards, mentor the team on infra best practices.

    `Multi-cloud architecture` `GitOps (ArgoCD, Flux)` `Service mesh (Istio)` `Distributed tracing` `FinOps & cost optimization` `Chaos engineering` `Compliance (SOC2, ISO 27001)` `Capacity planning`

=== "Staff / Principal (10+ yrs)"
    **Focus:** Define the platform strategy, build internal developer platforms, drive org-wide reliability culture.

    `Platform engineering` `Developer experience (DX)` `Org-wide SLO frameworks` `AI/ML infrastructure strategy` `Build vs buy decisions` `Security architecture` `Cross-team technical leadership`

---

## Tools

=== "Containers & orchestration"
    | Tool | Priority |
    |------|----------|
    | Docker | ⭐ Core |
    | Kubernetes | ⭐ Core |
    | Helm | ⭐ Core |
    | containerd | Useful |
    | k3s | Useful |

=== "IaC"
    | Tool | Priority |
    |------|----------|
    | Terraform | ⭐ Core |
    | Pulumi | Useful |
    | Ansible | Useful |
    | AWS CDK | Useful |
    | Crossplane | Useful |

=== "CI/CD"
    | Tool | Priority |
    |------|----------|
    | GitHub Actions | ⭐ Core |
    | ArgoCD | ⭐ Core |
    | Jenkins | Useful |
    | Flux | Useful |
    | Tekton | Useful |

=== "Observability"
    | Tool | Priority |
    |------|----------|
    | Prometheus | ⭐ Core |
    | Grafana | ⭐ Core |
    | OpenTelemetry | ⭐ Core |
    | Datadog | Useful |
    | Loki | Useful |

=== "Cloud"
    | Tool | Priority |
    |------|----------|
    | AWS (EKS, RDS, S3) | ⭐ Core |
    | GCP | Useful |
    | Azure | Useful |
    | Cloudflare | Useful |

=== "AI/ML infra"
    | Tool | Priority |
    |------|----------|
    | vLLM | Useful |
    | Triton Inference Server | Useful |
    | Kubeflow | Useful |
    | NVIDIA CUDA | Useful |

---

## Learning path

1. **Linux fundamentals** *(1–2 months · Free)*
   "The Linux Command Line" book (free online). Practice daily — everything runs on Linux.

2. **Docker & containers** *(2–3 weeks · Free)*
   Official Docker getting started + build and ship a real app. Understand layers and networking.

3. **Kubernetes (CKA certification)** *(2–3 months · Paid)*
   Killer.sh + KodeKloud. CKA is the gold-standard cert for K8s practitioners.

4. **Terraform (IaC)** *(3–4 weeks · Free)*
   HashiCorp official tutorials + build a real AWS environment with VPC, EC2, RDS.

5. **AWS / GCP certification** *(2–3 months · Paid)*
   AWS Solutions Architect Associate or GCP Professional Cloud Architect.

6. **Observability (Prometheus + Grafana)** *(2–3 weeks · Free)*
   Grafana Labs tutorials + instrument a real service with custom metrics and dashboards.

7. **SRE practices** *(Ongoing · Free)*
   "Site Reliability Engineering" (Google SRE book) — free online. Understand SLOs/SLAs/error budgets.

---

## Interview topics

=== "Linux & networking"
    - Process management & signals
    - File permissions & ownership
    - TCP/IP, DNS, TLS explained
    - Load balancing strategies
    - Firewall & iptables basics

=== "Kubernetes"
    - Pod lifecycle & health probes
    - Services: ClusterIP vs NodePort vs LoadBalancer
    - RBAC & namespaces
    - HPA / VPA scaling
    - Debugging crashlooping pods

=== "Reliability"
    - SLO, SLA, error budget concepts
    - Blue/green vs canary deployments
    - Incident response process
    - Post-mortem culture
    - Chaos engineering principles

=== "IaC & cloud"
    - Terraform state management
    - Immutable vs mutable infrastructure
    - Cost optimization strategies
    - Multi-region architecture
    - Security: IAM least privilege

---

## Roles & salary

| Title | Experience | Salary (US) |
|-------|-----------|-------------|
| DevOps / SRE Engineer | 0–2 yrs | $85k–$120k |
| Senior DevOps / SRE | 3–6 yrs | $130k–$180k |
| Principal SRE | 6–10 yrs | $180k–$250k |
| Platform Engineer Lead | 8+ yrs | $220k–$320k+ |

---

## Related pages

- [Roadmap — DevOps](../roadmaps/devops.md)
- [AI Era — DevOps](../ai-era/devops.md)
