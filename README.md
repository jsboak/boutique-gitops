# boutique-gitops

Argo CD applications and per-environment Helm values for Online Boutique.

- `argocd/projects`: the Argo CD project
- `argocd/applications`: one application per environment and component
- `environments/<env>/values.yaml`: Helm values for the `onlineboutique` chart
