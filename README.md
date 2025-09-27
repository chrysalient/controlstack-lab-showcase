# Control Stack Lab
**Enterprise-Grade AWS Kubernetes Deployment (EKS Architecture Lab)**  
by Chrysalient, LLC  

---

## Overview
Control Stack Lab is a guided, production-style environment for learning **enterprise cloud architecture on AWS**.  
It provisions a full **Amazon EKS cluster** with Terraform, Ansible, Helm, and CloudFormation.  

A sample 3-tier app is included to validate the architecture — but the real focus is the **infrastructure design**.

---

## Status
⚠️ **Work in Progress**  
This repository is actively being prepared for release. Documentation, architecture notes, and packaged deliverables will be added soon.  

---

## Quick Start (Preview)
To test the DevOps workstation image (when available):  
```bash
docker run -it --rm \
  -v $HOME/.aws:/home/controlstack/.aws \
  -v $(pwd):/workspace \
  chrysalient/controlstack:latest


