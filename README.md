# REST APIs with FLASK (Based on the UDEMY e-course)

## Use docker during development

```sh
docker build -t rest-apis rest-apis-with-flask:1.0.0 .
docker run -dp 5000:5000 -w /app -v "$(pwd)":/app  --name rest-apis rest-apis-with-flask:1.0.0
```
