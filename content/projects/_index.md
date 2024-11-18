---
title: ""
date: 2024-08-30T12:30:59+02:00
draft: false
---

## Relevant Projects

You can find interesting repositories pinned on my [github home page](https://github.com/mbovo).

Except for the first one, this is a list of projects that cannot be shared as public repositories. If you are looking for more details, feel free to reach out to me.

### PDH - Pagerduty for Humans

- [github.com/mbovo/pdh](https://github.com/mbovo/pdh)
- Python CLI tool to help managing PagerDuty activities and dealing with alarms and services, currently used by many on-call engineers @Sysdig.
- Operate on PagerDuty alarms from command line.
- Support custom rules to implement reactive behavior to alarms.
- Easy incident management for on-call engineers, improved Time to Resolve by 60% for most trivial alarms.

### Autodoc operator

- Private Repository @Sysdig
- Kubernetes operator that merges OpenApi spec files from various sources to generate a single, unified, spec file for the whole cluster; then serve the HTML documentation on a web server.
- Automatic retrieval of OpenApi specs from various services and deep merge of OpenApi specifications.
- Reduced friction for developers to access documentation of services actually deployed on a given cluster.

### SDC-Admin Operator

- Private Repository @Sysdig
- Kubernetes operator that helps managing admin users of a Sysdig Installation following as-code (gitops), self-service approach with managers' reviews and temporary privilege escalation support.
- Self-healing and self-reconciliation, avoiding manual intervention.
- Reduced setup and maintenance from hours-long to 5mins Pull Requests.

### GitOps CD Pipeline

- Private Repository @Sysdig but for the concept, you can refer to [my lab](https://github.com/mbovo/proxmox_homelab)
- Design and implementation of a Continuous Delivery pipeline based on GitOps principles with FluxCD.
- Currently used by all infrastructure components across all Kubernetes clusters on different cloud providers.
- GitOps: you have an immediate snapshot of what is running in your clusters, simply looking at the main branch.
- Fully reconciled: manual changes on the clusters are automatically reverted to the desired state.
- Reduced maintenance and setup times by a 10x factor.
