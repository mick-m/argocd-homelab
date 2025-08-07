# ArgoCD Homelab

Follows the "app of apps" pattern:
- "apps/templates" is where all Helm deployments live, along with the ‘root’ app for K8s manifests.
- "charts/argocd" is how ArgoCD is bootstrapped and declared for the cluster
- "yamls" is where all K8s manifests will be deployed from



Source: https://www.micahbird.com/p/how-to-setup-argocd-the-homelab-way
