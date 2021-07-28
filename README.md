# ArgoCD Helmfile

This Helmfile deploys `ArgoCD` resoure.

## Required environment

This Helmfile requires the following environment variables to be configured before running.

| Variable | Description |
| --- | --- |
| `KUBE_NAMESPACE` | Destination namespace |
| `ENV` | Kubernetes environment (normally matchs the cluster) |

## Running

* Execute `helmfile template` to get the templated values of this HelmChart.
* Execute `helmfile sync` to syncronize with the cluster.
* Execute `helmfile diff` to see the difference between the desired state and the canonical state.
* Execute `helmfile destroy` to remove this release.
