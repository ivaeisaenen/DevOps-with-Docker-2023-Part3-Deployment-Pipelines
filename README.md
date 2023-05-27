## Build and Deploy express-app Docker image

... by pushing new commit to repository and ...

```
using github actions pipelines .github/workflows/deploy.yml
1. Checkouts Github repository
2. Logins Docker
3. Builds and Pushes Docker image for express-app (Dockerfile-build-express-app)
```

## express-app

Copied from: https://github.com/docker-hy/material-applications/tree/main/express-app

Access with browser http://localhost:8080

## Docker composite up

 ... -f docker-composite.yml

```
1. Pulls the previously created image and deploys service
2. Uses Watchtower to check if docker image is updated and pull & deploy if updated
```