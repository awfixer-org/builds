# builds
monorepo for building images and pushing them to our registaries (do, ghcr, docker, k8s, quay, etc)

We are automating some of the commits to this repo and it builds all of the items on a schedule. you are able to look at the [workflows folder](.github/workflows) which provides you with all of the workflows that we use, and there will be documentation on this repo eventually

this repo is a key part of our CI setup as it makes sure there are fresh container builds to be used in other parts of our infra
