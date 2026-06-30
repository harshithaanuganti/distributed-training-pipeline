# Distributed Training Pipeline

Distributed ML training pipeline on AWS using Ray for distributed
compute, MLflow for experiment tracking, and Terraform for infrastructure.

## Status

- [ ] Terraform: EKS cluster + node groups
- [ ] KubeRay operator deployed
- [ ] Ray Train: distributed training job (from scratch, CIFAR-10 image classifier)
- [ ] MLflow tracking server (RDS + S3)
- [ ] Ray Tune: hyperparameter search
- [ ] End-to-end pipeline test
- [ ] Benchmark results documented

## Stack

Ray · KubeRay · MLflow · Terraform · AWS EKS · Python