# notification-service

Sends emails and push notifications

## Getting started
```bash
docker build -t notification-service .
docker run -p 8080:8080 notification-service
```

## CI/CD

This repo has a GitHub Actions pipeline that builds and smoke-tests
the Docker image on every push to main.

---
*Provisioned by [IDP Platform](https://github.com/aftabkh4n/idp-platform)*