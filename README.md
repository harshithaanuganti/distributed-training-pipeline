# Distributed Training Pipeline

Distributed ML training pipeline on AWS using Ray for distributed
compute, MLflow for experiment tracking, and Terraform for infrastructure.

## Status

- [ ] Ray Train: distributed training job (from scratch, CIFAR-10 image classifier) — local/Docker
- [ ] MLflow tracking (local, file-based)
- [ ] Containerize training job with Docker
- [ ] Terraform: EKS cluster + node groups
- [ ] KubeRay operator deployed
- [ ] MLflow tracking server (RDS + S3)
- [ ] Ray Tune: hyperparameter search
- [ ] End-to-end pipeline test (on EKS)
- [ ] Benchmark results documented

## Stack

Ray · KubeRay · MLflow · Terraform · AWS EKS · Python