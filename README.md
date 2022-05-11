# CI/CD with Kalix

This project is a sample Javascript project using Kalix Github Actions support for CI/CD

When pull request created:

- run tests
- build Docker image.

When GitHub release published:

- run tests
- authenticate to Docker Hub
- build Docker image tagged with GitHub release tag
- push Docker image to Docker Hub
- deploy Kalix service.

Fully parmaterized with:

- GitHub release tag
- Docker Hub username
- Docker Hub token
- Kalix token
- Kalix project ID

For more information: https://docs.kalix.io/projects/integrate-cicd-github-actions.html
