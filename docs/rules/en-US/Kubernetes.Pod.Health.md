---
severity: Important
online version: https://github.com/BernieWhite/PSRule.Rules.Kubernetes/blob/master/docs/rules/en-US/Kubernetes.Pod.Health.md
---

# Use probes

## SYNOPSIS

Containers should use liveness and readiness probes.

## DESCRIPTION

Just like any other application, container applications may take time to start, fail during startup or operation.
Kubernetes provides a way for the cluster to determine if each container is ready to respond to requests.
This is accomplished through liveness and readiness probes.

## RECOMMENDATION

Containers should use liveness and readiness probes.

## LINKS

- [Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/)