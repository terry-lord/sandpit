# Release Notes

**Solution :** #{SolutionName}#

**Release Date :** #{ReleaseDate}#

**Version :** #{Version}#

## Plugin Information
The following plugins are listed in the solution.

#{plugins}#

## Dependencies

The following solution dependencies were identified and will need to be deployed beforehand.

#{SolutionDependencies}#

## Deployment Notes

> Any steps that may need to be carried out before or after the deployment of this solution.

<!--DeploymentContent-->
<!--EndDeploymentContent-->

## New Features

<!--NewFeaturesContent-->
<!--EndNewFeaturesContent-->

## Bug Fixes

<!--BugFixesContent-->
<!--EndBugFixesContent-->

## Patches

Patches that have been rolled up into this solution.

<!--PatchesContent-->
ems-testpatch1
ems-testpatch2
<!--EndPatchesContent-->

## Managed solution settings

These settings are used during the deployment of the '#{SolutionName}#' solution to upstream Dynamics environments.

The settings have been taken from the '#{SolutionName}#' solution settings file.

> Note: Any setting value that's surrounded with !#{ *value* }#! are secrets.  These are retrieved at runtime during deployment from the relevant keyvault.

#{SolutionSettings}#

#{Environments}#

## Commits 

#{Commits}#