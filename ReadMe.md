# Jering.DevOps.AzurePipelines
TODO work in progress

## Overview
Defines AzurePipelines templates for use by Netstandard and .Net Core Nuget packages:
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=vsts#using-other-repositories

## Features
- macOS, Linux and Windows test runs.
- Code coverage report generation and publishing.
- Versioning using a changelog, git tagging.
- Dependency caching.
- Symbols using source link.

## Notes
nuget-package.yml's last step is a script task. Note how the entire script is inlined. We do it this way because Azure Pipeline's [repositories feature](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=vsts#using-other-repositories)
doesn't allow for standalone scripts.