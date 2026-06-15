# Hey, I'm Roey 👋
DevOps & Cloud Engineer at [Develeap](https://www.develeap.com/). <a href="https://www.linkedin.com/in/roey-wullman/" target="blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="20" width="25" /></a>

I build and harden AWS infrastructure — multi-account governance, IaC, security, cost control, and CI/CD — and I've taken a regulated production estate from vendor-dependent and manually-managed to least-privilege, Terraform-managed, and documented.

## What I Do
☁️ **Cloud Infrastructure & Security** — Embedded as DevOps/cloud architect on a publicly-traded production AWS estate: closed the network perimeter, built least-privilege IAM, adopted live infra into Terraform, ran zero-downtime RDS upgrades, and cut AWS spend ~33%.

🏢 **Multi-Account Governance** — Manage AWS Organizations across multiple OUs with Service Control Policies, automated account provisioning, cross-account cost enforcement, and serverless monitoring/reporting tooling I designed and built end-to-end.

🚀 **Platform & CI/CD** — Terraform IaC across greenfield and live-import workflows, hardened S3 remote state, and security-conscious GitHub Actions pipelines.

🎓 **Mentoring & Curriculum** — Mentored 4 cohorts through an AI-focused DevOps bootcamp at Develeap, and designed its Platform-for-AI track: EKS/Helm/ArgoCD, IRSA-based identity, and LLM-specific observability and CI patterns.

## Projects
Sanitized extracts of some production systems I've built and run, plus teaching material.

- **[aws-org-account-factory](https://github.com/roeyw5/aws-org-account-factory)** — Terraform + Lambda platform for cost-controlled, policy-bounded AWS accounts at scale. Daily budgets, four SCPs (region/instance-type/service guardrails + billing lockdown), nightly cross-account resource sweep, and event-driven budget-breach freeze.
- **[aws-org-sentry](https://github.com/roeyw5/aws-org-sentry)** — Multi-account idle-resource scanner. Assumes roles across the Org to scan 11 resource types over multiple regions, with Slack alerts, one-click stop actions, and HMAC-verified webhooks on an EventBridge cron.
- **[aws-cost-digest](https://github.com/roeyw5/aws-cost-digest)** — Weekly per-account cost reporting for multi-account Organizations. Recursively walks the OU hierarchy, aggregates Cost Explorer data, builds a multi-tab Excel workbook, and emails it via SES.
- **[claude-code-guide](https://github.com/roeyw5/claude-code-guide)** — A practical guide to Claude Code fundamentals: CLAUDE.md memory, context management, plan mode, skills, sub-agents, hooks, and settings. Used as teaching material in Develeap's DevOps bootcamps.
