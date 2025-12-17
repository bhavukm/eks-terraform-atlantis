# eks-terraform-atlantis
AWS EKS Cluster with Terraform Gitlab Pipeline

To destroy the resources:

atlantis plan -d application/environments/dev -w default -- -destroy
