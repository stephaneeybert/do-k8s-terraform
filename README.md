# do-k8s-terraform

A first timer Kubernetes cluster deployed with Terraform on DigitalOcean droplets

Deploying the cluster
```
cd env/dev/;
terraform plan -out plan-`date +'%s'`.plan;
```
