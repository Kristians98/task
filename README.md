# Task
## Step 1
I have created two virtual machines in a single Resource group in Azure
![vm](./.attachments/vm.png)

## Step 2
Installed Rancher un VM1
![rancher](./.attachments/rancher.png)

## Step 3
Used Rancher to deploy k3s cluster on VM2
![cluster](./.attachments/cluster.png)

## Step 4
Used terraform to install ArgoCD on VM2 cluster
![terraform](./.attachments/terraform.png)
![argocd](./.attachments/argocd.png)

## Step 5
Installed Prometheus and Trivy using ArgoCD and created necessary repository structure
![prometheus](./.attachments/prometheus.png)

## Step 6
Added dummy Helm chart and installed it with ArgoCD
![dummy helm chart](./.attachments/helm.png)
