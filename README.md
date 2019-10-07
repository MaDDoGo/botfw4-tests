# Bot Framework V4 PoC

This repository will contain all tests done agains the .net version of the Bot Framework v4 SDK

## Install

dotnet restore

## Run on Docker

### Build Docker image

> docker build -t botfw4/poc .

### Run Docker image

> docker run --name <container_name> botfw4/poc

## Run Development (AutoReload and Watch for file changes)

dotnet watch run

## Run (Without AutoReload)

dotnet run

## Resources

.net Core 3 resources:
- https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30?view=aspnetcore-3.0&tabs=visual-studio#prerequisites
- https://devblogs.microsoft.com/dotnet/announcing-net-core-3-0/


