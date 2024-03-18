# Microservices

Run all microservices: `skaffold dev`

## Skaffold
To install Skaffold, follow the following installation guide `https://skaffold.dev/docs/install/`

If for some reason when you run `skaffold dev` you get an error that says a docker image cannot be found or cannot be pulled, go to `skaffold.yaml` and change `push` from `false` to `true`, then try again. Don't forget to return it to `false`