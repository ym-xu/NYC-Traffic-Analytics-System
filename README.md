# NYC-Traffic-Analytics-System

## Problem Statement

## Dataset

## Architecture Diagram

## Technologies & Prerequisite (reproducibility)

### Requirements:
- Google Cloud SDK
- Terraform
- Conda

### GCP
- create a GCP project
- setup a service account & authentication for the project
    -   service account: Viewer, Storage Admin, Storage Object Admin, BigQuery Admin
        -   create a key for service account and download the auth-key (.json) file
- set environment variable to point GCP auth-key:

```
export GOOGLE_APPLICATION_CREDENTIALS="<absolute/path/to/your/service-account-auth-key.json>"

gcloud auth application-default login
```

### Terraform
```
cd terraform

terraform init
terraform plan
terraform apply
```

### Prefect
- start Prefect UI
```
prefect server start
```
- create a  GCP Credentials Block
![alt img](https://github.com/ym-xu/NYC-Traffic-Analytics-System/blob/main/imgs/Xnip2023-10-19_12-13-56.jpg)
- create a GCP Bucket Block
![alt img](https://github.com/ym-xu/NYC-Traffic-Analytics-System/blob/main/imgs/Xnip2023-10-19_12-13-59.jpg)


## Visualization

## Inference

## Source Code Reference