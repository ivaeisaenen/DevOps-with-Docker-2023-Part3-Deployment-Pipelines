## Build and Deploy express-app Docker image

... by pushing new commit to repository and ...

using github actions pipelines .github/workflows/deploy.yml
1. Checkout Github repository
2. Login Docker
3. Build and Push Docker image

## express-app

Access with browser http://localhost:8080

## Docker composite up

1. Pull the previously created image and deploy service
2. Use Wathtover to check if docker image is updated and pull & deploy if updated