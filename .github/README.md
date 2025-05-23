## TODOs:
- [ ] External Secret Store creating kv secrets
- [ ] Cert manager with a persistent volume
    - Will need to get cloudflare token from azure key vault
- [ ] Traefik for ingress
    - Gateway API
- [ ] Rancher

- [ ] Github Access for other repos
    - Application deployments I would like to keep in a separate private repo

## Notes
I'm not having good luck with ArgoCD managing the lifecycle of ArgoCD.
When deleting the Argocd Application, I find that the deletion hangs.
I'm evaluating whether to remove the ArgoCD app that references the ArgoCD installation.
I would continue to use the ArgoCD Application to apply customizations to the ArgoCD installation.
