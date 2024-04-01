# Description

Demo that does the following:
- Deploys a VPC with an EKS cluster
- Deploys nginx ingress controller
- Deploys ArgoCD in the EKS cluster and configures an nginx ingress to expose the ArgoCD UI via the AWS public LB
- Deploys the ArgoCD project and apps
- Runs some basic tests
  


# Repos used

- Terraform infra.tfvars per environment: https://github.com/luisllm/environments.git

- Helm charts and custom values files: https://github.com/luisllm/demo-argocd-datree-config.git


# References

ArgoCD:
- https://www.youtube.com/watch?v=AvLuplh1skA&list=PLTiQErIEf8SZsSwdDqITSPJvMDBGVJX-d&index=1
- https://www.youtube.com/watch?v=17894DTru2Y&list=PLTiQErIEf8SZsSwdDqITSPJvMDBGVJX-d&index=2

Apps deployed with ArgoCD:
- https://github.com/LukeMwila/microservice-products
- https://github.com/LukeMwila/microservice-orders
- https://github.com/LukeMwila/microservice-graphql-server
- https://github.com/LukeMwila/microservice-example-helm-charts

Datree:
- https://github.com/datreeio/helm-datree
- https://medium.com/@KushanJanith/prevent-kubernetes-misconfigurations-with-datree-ca1caa8b0e4


