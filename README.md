# Infrastructure as Code

Personal infrastructure for deploying my projects on a K3s cluster with ArgoCD.

## Stack

- Ansible
- K3s
- ArgoCD
- Helm

## Development

Run linters before pushing:

```bash
# Ansible
ansible-lint ansible/

# YAML
yamllint .

# Helm
helm lint argocd/charts/*/
```
