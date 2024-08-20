# CONTRIBUTING

## how to run the Dockerfile locally

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME rest-apis-flask-python shc -c
""flask run --host 0.0.0.0"
```