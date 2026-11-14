### Steve Bolton

Platform and developer-experience engineer — 25 years, hands-on in Java. I make the
structure of existing systems explicit, and build processes that can be re-run rather than
events that have to go right.

Most of my recent work is public. Specifics, rather than a contribution graph:

**Agentic development**

- [`CLAUDE.md`](https://github.com/dotCMS/core/blob/main/CLAUDE.md) — I wrote the first
  commit of dotCMS's root agent context file (18 June 2025). Their engineers are still
  extending it, and per-module context files now sit throughout the monorepo.
- [`cicd-diagnostics` skill](https://github.com/dotCMS/core/commit/7ff333cb2ca5) — a reusable
  agent skill written as a versioned specification, with a changelog and its own
  best-practice self-assessment. Since folded into the team's catalogue as
  `dot-cicd-diagnose`.
- [`dotcms-utilities`](https://github.com/dotCMS/dotcms-utilities) — installable git
  extensions collapsing multi-step issue and branch handling into single commands, with JSON
  output and discovery flags so agents can drive them too. Built with AI from June 2024.

**Kubernetes and GitOps**

- [`helm-charts`](https://github.com/dotCMS/helm-charts) — I created this repository and
  its chart-linting CI, and contributed the production hardening: StatefulSet pod management
  and disruption budgets, ALB health checks, Prometheus scrape annotations and monitoring
  NetworkPolicies.

**CI/CD and release engineering**

- [Workflow architecture](https://github.com/dotCMS/core/tree/321450dae67c/.github/workflows)
  — the pipeline I designed and documented: merge queue, change-impact test selection,
  secretless pull-request builds. Pinned to the state it was in when I left.
- [`core-workflow-test`](https://github.com/dotCMS/core-workflow-test) — a governed fork I
  created so workflow changes could be tested without test commits landing in core.

**Earlier**

- [Jetty](https://github.com/jetty/jetty.project/issues/1785) — virtual-host connector
  matching (`vhost@connectorname`), contributed upstream in 2018.

Writing on engineering maturity and AI-assisted development:
**[boltn.com/thinking](https://boltn.com/thinking)**

---

Platform engineering · CI/CD and release · GitOps and multi-tenant Kubernetes ·
observability · agentic development

Java · Kubernetes · Helm · Argo CD · Terraform · AWS · OpenTelemetry · Elasticsearch

steve@boltn.com · [LinkedIn](https://linkedin.com/in/spbolton)

*Open to senior platform and developer-experience engineering roles.*
