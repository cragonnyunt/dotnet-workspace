# DotNet Workspace

[![DotNet Workspace CI](https://github.com/cragonnyunt/dotnet-workspace/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/cragonnyunt/dotnet-workspace/actions/workflows/main.yml)

DotNet Workspace Docker is built on top of the [development workspace docker](https://github.com/cragonnyunt/development-workspace). It contains the most used tools for .Net(Core) developers, and prepare environment configuration for developing .Net apps and websites.

Set of tools installed
- Everything installed on [development workspace docker](https://github.com/cragonnyunt/development-workspace)
- .Net (Core) SDK
- .Net (Core) Runtime
- ASP.Net Core SDK & Runtime
- Powershell

## Pulling the image

```
docker pull cragonnyunt/dotnet-workspace-docker:<<tag>>
```

## Running the image

```
docker run --rm -it \
    -v $(pwd):/workspace \
    cragonnyunt/dotnet-workspace-docker:<<tag>>
```
