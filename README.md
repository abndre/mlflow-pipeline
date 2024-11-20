# mlflow developer

# Comando

1. Build and run
```bash
docker compose --env-file config.env up -d --build
```

2. Access MLflow UI with http://localhost:5000

3. Access MinIO UI with http://localhost:9000

## Example

1. Install [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)


2. conda create -n mlflow

3. conda activate mlflow

4. conda install mlflow boto3