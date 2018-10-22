# Jering.DevOps.AzurePipelines
TODO work in progress

## Overview
Defines AzurePipelines templates for use by other repositories:
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=vsts#using-other-repositories

## Notes
nuget-package.yml's last step is a script task. Note how the entire script is inlined. We do it this way because Azure Pipeline's [repositories feature](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/templates?view=vsts#using-other-repositories)
doesn't allow for standalone scripts.