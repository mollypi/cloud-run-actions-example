# Creating a CI/CD Environment for Serverless Containers on Google Cloud Run

[![Git](https://app.soluble.cloud/api/v1/public/badges/96f3f115-ec54-4d81-b34b-48b715e10ebd.svg?orgId=561911742905)](https://app.soluble.cloud/repos/details/github.com/mollypi/cloud-run-actions-example?orgId=561911742905)  

![cover](images/cover.png)

This repository is a complement to my medium article. If you wanna follow step by step, check [my writing]().

## Architecture

This is how our infrastructure works:

## Golang

Running:

```bash
$ go run server.go
```

Running tests:

```bash
$ go test -v
```

Running Dockerfile:

```bash
$ docker build . -t example

$ docker run -p 8000:8000 --env PORT=8000 example
```
