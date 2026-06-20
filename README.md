# PipelineIQ Workflow Analyzer Service

Independent repository staging folder for the PipelineIQ workflow analyzer service.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-workflow-analyzer-service:v1.0.0 -f services/workflow-analyzer-service/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.
