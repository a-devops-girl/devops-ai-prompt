# **DevOps AI Prompt Library**

A curated collection of AI prompts designed specifically for DevOps engineers, SREs, and Cloud practitioners to accelerate routine tasks.

This library acts as a DevOps Copilot Playbook, helping you troubleshoot faster, automate smarter, and adopt best practices consistently using structured AI prompts.

## 📖 **What is this?**

DevOps engineers often spend time repeating the same tasks:

* Debugging Kubernetes manifests
* Fixing Terraform configs
* Resolving CI/CD pipeline errors
* Investigating incidents
* Optimizing cloud costs

Instead of writing ad-hoc AI queries each time, this project provides ready-to-use prompt templates you can copy, fill in, and run with your AI assistant.

Think of it as your personal AI prompt cheat sheet for DevOps.

## ✨ **Features**

* 20+ production-ready prompts
* Covers Infrastructure, Kubernetes, CI/CD, Ops/Monitoring/Security
* Structured with context, role, and task sections
* Optimized for clarity, reproducibility, and real-world debugging
* Markdown-based → easy to copy-paste into ChatGPT, Claude, or other LLMs

## 📂 **Categories**

The prompt library is organized into 4 main categories:

### 🌐 **Infrastructure (Terraform / AWS / IaC)**

* Terraform Debugger
* AWS IAM Policy Generator
* Cloud Cost Optimizer
* nsible Playbook Fixer

### ☸️ **Kubernetes**

* Deployment Debugger
* Ingress & Networking Helper
* Autoscaling Advisor
* Helm Chart Debugger

### 🔄 **CI/CD**

* GitHub Actions Debugger
* GitLab CI/CD Fixer
* Jenkinsfile Debugger
* ArgoCD Sync Issue Fixer

### 📊 **Ops, Monitoring & Security**

* Incident RCA Assistant
* Log Query Helper
* Monitoring Dashboard Designer
* Security Vulnerability Fixer
* Secret Rotation Guide
* Performance Testing Advisor
* Chaos Engineering Planner
* Compliance & Audit Helper

## 🚀 H**ow to Use**

* Open the Prompts.md (or use the README cheat sheet).
* Copy the prompt template relevant to your task.
* Replace the [placeholders] with your context (YAML, logs, Terraform code, etc.).
* Paste into your AI tool (ChatGPT, Claude, Gemini, etc.).
* Get structured, actionable responses in seconds.

# 🚀 **DevOps AI Prompt Library – Cheat Sheet**

A structured set of ready-to-use AI prompts for routine DevOps tasks.
Fill in the blanks and paste into your AI assistant.

## 🌐 **Infrastructure (Terraform / AWS / IaC)**

### **1. Terraform Debugger**

```markdown
Role: You are a senior Terraform/IaC engineer.

Context:
- Provider: [AWS | GCP | Azure]
- Terraform version: [x.y.z]
- Code snippet: [paste here]
- Error output: [paste error]

Task:
1. Explain the root cause.
2. Provide corrected HCL snippet.
3. Suggest IaC best practice to avoid recurrence.
```

### **2. AWS IAM Policy Generator**

```markdown
Role: You are an AWS IAM policy expert.

Context:
- Service: [S3 | EKS | Lambda]
- Required action: [read-only | write | list]
- Security level: [least privilege | admin]

Task:
Generate a JSON IAM policy that:
- Grants exactly the requested permissions.
- Is minimal and follows AWS security best practices.
```

### **3. Cloud Cost Optimization**

```markdown
Role: You are a cloud FinOps specialist.

Context:
- Cloud provider: [AWS | GCP | Azure]
- Current resources: [EC2 t3.medium, RDS db.m5.large]
- Workload type: [stateless API, batch jobs, DB-heavy]

Task:
1. Suggest cost optimization opportunities.
2. Recommend reserved/on-demand/spot usage.
3. Highlight risks of each change.
```

### **4. Ansible Playbook Fixer**

```markdown
Role: You are an Ansible automation engineer.

Context:
- Playbook snippet: [paste here]
- Error logs: [paste output]
- Desired outcome: [install nginx, configure user]

Task:
1. Debug the playbook.
2. Provide fixed YAML.
3. Suggest role/structure improvements.
```

## ☸️ **Kubernetes**

### **5. K8s Deployment Debugger**

```markdown
Role: You are a Kubernetes SRE.

Context:
- Resource: [Deployment | StatefulSet | Job]
- YAML snippet: [paste here]
- Error: [kubectl logs/describe output]
- Expected behavior: [pods running]

Task:
1. Identify config error.
2. Provide corrected YAML.
3. Suggest future-proofing tip.
```

### **6. Ingress & Networking Helper**

```markdown
Role: You are a Kubernetes networking specialist.

Context:
- Ingress/Service YAML: [paste here]
- Controller: [NGINX | Traefik | Istio]
- Error: [404, timeout, SSL issue]

Task:
1. Debug networking misconfig.
2. Rewrite corrected YAML.
3. Suggest DNS/TLS best practice.
```

### **7. Autoscaling Advisor**

```markdown
Role: You are a Kubernetes autoscaling expert.

Context:
- Cluster workload: [CPU-bound | memory-heavy]
- Metrics: [avg CPU %, mem usage, req/sec]
- Current HPA/VPA YAML: [paste here]

Task:
1. Evaluate scaling config.
2. Suggest corrected HPA/VPA YAML.
3. Recommend scaling thresholds & limits.
```

### **8. Helm Chart Debugging**

```markdown
Role: You are a Helm charts expert.

Context:
- Helm chart values.yaml: [paste snippet]
- Error: [helm install/upgrade error]
- Expected behavior: [service up & running]

Task:
1. Explain error cause.
2. Suggest corrected values.yaml.
3. Suggest chart organization best practice.
```

## 🔄 **CI/CD**

### **9. GitHub Actions Debugger**

```markdown
Role: You are a CI/CD engineer specializing in GitHub Actions.

Context:
- Workflow YAML: [paste here]
- Error logs: [paste failure log]
- Expected outcome: [tests pass, build succeeds]

Task:
1. Identify pipeline issue.
2. Provide corrected YAML snippet.
3. Suggest optimization for speed/caching.
```

### **10. GitLab CI/CD Debugger**

```markdown
Role: You are a GitLab CI/CD expert.

Context:
- .gitlab-ci.yml: [paste snippet]
- Error output: [paste job failure log]
- Expected behavior: [build/test/deploy success]

Task:
1. Explain the root cause.
2. Provide corrected snippet.
3. Suggest pipeline restructuring if needed.
```

### **11. Jenkinsfile Fixer**

```markdown
Role: You are a Jenkins pipeline expert.

Context:
- Jenkinsfile: [paste snippet]
- Error logs: [paste console log]
- Expected outcome: [build/test/deploy]

Task:
1. Debug Groovy syntax/pipeline error.
2. Provide corrected Jenkinsfile snippet.
3. Suggest pipeline optimization.
```

### **12. ArgoCD Sync Issue Fixer**

```markdown
Role: You are an ArgoCD GitOps expert.

Context:
- Git repo YAML: [paste snippet]
- ArgoCD app logs: [paste error]
- Cluster state: [kubectl get all -n xyz]

Task:
1. Identify sync issue.
2. Provide corrected config.
3. Suggest GitOps best practice.
```

## 📊 **Ops, Monitoring & Security**

## **13. Incident Root Cause Analysis**

```markdown
Role: You are an SRE doing post-incident analysis.

Context:
- Incident type: [API latency, pod crashloop, DB spike]
- Logs/metrics: [paste here]
- Timeline: [timestamps]
- Impact: [user-facing downtime, slow response]

Task:
1. Summarize incident in plain English.
2. Suggest 2–3 probable root causes.
3. Recommend immediate fixes.
4. Suggest monitoring improvements.
```

### **14. Log Query Assistant**

```markdown
Role: You are a log query expert (PromQL, CloudWatch, Elasticsearch, Loki).

Context:
- Query system: [Prometheus | Loki | CloudWatch]
- Current query: [paste query]
- Desired output: [avg CPU, 95th percentile latency]

Task:
1. Correct the query.
2. Explain the logic.
3. Suggest useful variations.
```

### **15. Monitoring Dashboard Designer**

```markdown
Role: You are a Grafana dashboarding expert.

Context:
- Workload type: [API | DB | Worker queue]
- Metrics available: [CPU, mem, req/sec, errors]
- Goal: [SRE-friendly, easy troubleshooting]

Task:
1. Suggest dashboard layout.
2. Recommend key graphs/alerts.
3. Provide example PromQL/queries.
```

### **16. Security Vulnerability Fixer**

```markdown
Role: You are a DevSecOps engineer.

Context:
- Vulnerability scan tool: [Trivy | Snyk | Aqua]
- Report snippet: [paste here]
- Target: [Docker image, Node.js app, etc.]

Task:
1. Explain vulnerabilities found.
2. Suggest safe remediation (patch, upgrade, config).
3. Provide fixed config/Dockerfile snippet.
```

### **17. Secret Rotation Helper**

```markdown
Role: You are a DevOps engineer managing secrets.

Context:
- Secrets manager: [AWS Secrets Manager | Vault | K8s Secrets]
- Current state: [describe issue]
- Goal: [rotate API keys every 30 days, auto-inject]

Task:
1. Suggest secret rotation process.
2. Provide config example.
3. Suggest automation (cron, GitHub Actions, Vault agent).
```

### **18. Performance Testing Advisor**

```markdown
Role: You are a DevOps performance engineer.

Context:
- Workload: [REST API | gRPC | DB-heavy service]
- Tool: [k6 | JMeter | Locust]
- Current config: [paste snippet]
- Problem: [low throughput, high latency]

Task:
1. Analyze current test config.
2. Suggest improved test plan.
3. Provide corrected script snippet.
```

### **19. Chaos Engineering Planner**

```markdown
Role: You are a Chaos Engineering expert.

Context:
- Platform: [K8s with Litmus/Chaos Mesh, AWS FIS]
- Workload: [API, DB, queue]
- Goal: [test resiliency of scaling, failover]

Task:
1. Suggest safe chaos experiments.
2. Provide example config.
3. Recommend monitoring checks during chaos.
```

### **20. Compliance & Audit Helper**

```markdown
Role: You are a compliance-aware DevOps engineer.

Context:
- Industry: [Finance | Healthcare | SaaS]
- Requirement: [SOC2 | HIPAA | PCI-DSS]
- Current setup: [cloud + CI/CD stack]

Task:
1. Map requirement to DevOps processes.
2. Suggest config/policy changes.
3. Provide audit checklist for compliance.
```

✅ That’s your ready-to-use DevOps Copilot Playbook in Markdown.