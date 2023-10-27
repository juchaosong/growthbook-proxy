---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

<!-- Please use this template while reporting a bug and provide as much info as possible.
-->

#### What happened

#### What you expected to happen

#### How to reproduce it (as minimally and precisely as possible)

#### Are there any error messages in growthbook-proxy logs?

(e.g. `kubectl logs -n growthbook-proxy --selector=app=growthbook-proxy`)

#### Anything else we need to know?

#### Environment

- Kubernetes version (use `kubectl version --short`):
- Helm version (use `helm version`):
- growthbook-proxy version (use `kubectl -n growthbook-proxy exec deploy/growthbook-proxy -- ./backend version`)
- growthbook-proxy Helm Chart version (use `helm -n growthbook-proxy list`)
- Cloud provider or hardware configuration:
- Others:
