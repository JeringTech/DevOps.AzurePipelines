# Jering.DevOps.AzurePipelines
Work in progress.
[![Build Status](https://dev.azure.com/JeringTech/DevOps.AzurePipelines/_apis/build/status/Jering.DevOps.AzurePipelines-CI?branchName=master)](https://dev.azure.com/JeringTech/DevOps.AzurePipelines/_build/latest?definitionId=6?branchName=master)

## Overview
Defines AzurePipelines templates for use by Netstandard and .Net Core Nuget packages:
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=vsts#using-other-repositories

## Features
- macOS, Linux and Windows test runs.
- Code coverage report generation and publishing.
- Versioning using a changelog, git tagging.
- Dependency caching.
- Publishing of CI builds

## Add Instructions For
- Symbols using source link.
- Allowing dotnet test from solution directory.
- Enabling xml documentation
- Adding an icon for nuget.org
  - PackageIconUrl
  - https://github.com/NuGet/Home/issues/352
- Customizing build number for CI builds - https://docs.microsoft.com/en-us/azure/devops/pipelines/build/options?view=vsts&tabs=yaml