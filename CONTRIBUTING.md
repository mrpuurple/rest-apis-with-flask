# CONTRIBUTING

## How to run the Dockerfile locally

```sh
docker build -t rest-apis IMAGE_NAME:IMAGE_TAG .
docker run -dp 5000:5000 -w /app -v "$(pwd)":/app  --name rest-apis IMAGE_NAME:IMAGE_TAG sh -c "flask run"
```
