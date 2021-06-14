# azure-aks-cluster

#creates AKS

### Create a file for each environment and run these commands according to your needs;

```
ENVIRONMENT=dev   make tf-fmt  tf-init  tf-plan  tf-apply
ENVIRONMENT=qa   make tf-fmt  tf-init  tf-plan  tf-apply
ENVIRONMENT=stage   make tf-fmt  tf-init  tf-plan  tf-apply
ENVIRONMENT=prod   make tf-fmt  tf-init  tf-plan  tf-apply

```
