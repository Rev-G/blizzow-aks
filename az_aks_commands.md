# Azure AKS setup

## login

`az login --use-device-code`

## create cluster

`az aks create --name tiki-kube --resource-group blizzow-beach --tags "environment=sandbox" "lifecycle=non-production" --generate-ssh-keys`

## create kube config

`az aks get-credentials --resource-group blizzow-beach --name tiki-kube`

## delete cluster

`az aks delete --name tiki-kube --resource-group blizzow-beach`

https://learnk8s.io/terraform-aks

https://learn.microsoft.com/en-us/cli/azure/run-azure-cli-docker
