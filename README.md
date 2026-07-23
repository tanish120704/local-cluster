# Platform GitOps Lab

Local kind-based Kubernetes lab for learning Argo CD, Helm, Crossplane, and platform components.

## Layout

- `charts/` — Helm charts we author or compose.
- `environments/local/` — local kind values/overrides.
- `bootstrap/` — later: Argo CD root application and child application definitions.
- `apps/` — later: Argo CD application manifests.

The initial Kubernetes context is `kind-platform-lab`.
