# Summary
Prefill...
Decode...
Prefill is compute-bound workload, Decode is memory-bound workload


# Motivation


# Goal
* Support K8S-Native PD Disaggregated Serving with CRD
* Extensible to XpYd
* Consider RBAC, Namespace, observability, persistence...

# Proposal

CRD + Controller

## Architecture

## Request Flow

## Control Flow

## Implementation Plan

### Custom Resource

```yaml

```

# Alternative Approaches

## Helm + CRD

# References
https://github.com/vllm-project/production-stack/blob/main/tutorials/16-disagg-prefill.md