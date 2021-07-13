# NetCore Workspace

[![NetCore Workspace CI](https://github.com/cragonnyunt/netcore-workspace/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/cragonnyunt/netcore-workspace/actions/workflows/main.yml)

NetCore Workspace Docker is built on top of the [development workspace docker](https://github.com/cragonnyunt/development-workspace). It contains the most used tools for .NetCore developers, and prepare environment configuration for developing .NetCore apps and websites.

Set of tools installed
- Everything installed on [development workspace docker](https://github.com/cragonnyunt/development-workspace)
- .Net Core SDK
- .Net Core Runtime
- ASP.Net Core SDK & Runtime
- Powershell

## Pulling the image

```
docker pull cragonnyunt/netcore-workspace-docker:<<tag>>
```

## Running the image

```
docker run --rm -it \
    -v $(pwd):/workspace \
    cragonnyunt/netcore-workspace-docker:<<tag>>
```
