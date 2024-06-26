# [go-sqlcmd](https://github.com/microsoft/go-sqlcmd) docker image

[![Docker](https://github.com/bonddim/go-sqlcmd/actions/workflows/docker.yaml/badge.svg?event=release)](https://github.com/bonddim/go-sqlcmd/actions/workflows/docker.yaml)
![Docker Image Size](https://img.shields.io/docker/image-size/bonddim/go-sqlcmd)
[![Docker Pulls](https://img.shields.io/docker/pulls/bonddim/go-sqlcmd)](https://hub.docker.com/r/bonddim/go-sqlcmd)
[![GitHub Release](https://img.shields.io/github/v/release/bonddim/go-sqlcmd)](https://github.com/bonddim/go-sqlcmd/releases/latest)
[![GitHub License](https://img.shields.io/github/license/bonddim/go-sqlcmd)](https://github.com/bonddim/go-sqlcmd?tab=MIT-1-ov-file)

## About

- Uses [gcr.io/distroless/static:nonroot](https://github.com/GoogleContainerTools/distroless) as image base
- Supported architectures: **amd64**, **arm64**, **s390x**
- Uses [released sqlcmd](https://github.com/microsoft/go-sqlcmd/releases) binary
- Automated release process

## Usage

```bash
# Pull image from Docker Hub
docker pull bonddim/go-sqlcmd
# Or GitHub Container Registry
docker pull ghcr.io/bonddim/go-sqlcmd
```

Refer to official [docs](https://docs.microsoft.com/sql/tools/go-sqlcmd-utility) for syntax and command line arguments

## License

Inherited from [microsoft/go-sqlcmd](https://github.com/microsoft/go-sqlcmd?tab=MIT-1-ov-file)
