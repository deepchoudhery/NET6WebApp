# .NET 8.0 Upgrade Plan

## Execution Steps

1. Validate that an .NET 8.0 SDK required for this upgrade is installed on the machine and if not, help to get it installed.
2. Ensure that the SDK version specified in global.json files is compatible with the .NET 8.0 upgrade.
3. Upgrade NET6WebApp\NET6WebApp.csproj
4. Run unit tests to validate upgrade in the projects listed below:
  - TestProject1\TestProject1.csproj

## Settings

This section contains settings and data used by execution steps.

### Excluded projects

| Project name                                   | Description                 |
|:-----------------------------------------------|:---------------------------:|

### Aggregate NuGet packages modifications across all projects

### Project upgrade details

#### NET6WebApp\NET6WebApp.csproj modifications

Project properties changes:
  - Target framework should be changed from `net5.0` to `net8.0`

NuGet packages changes:
  - None

Feature upgrades:
  - None

Other changes:
  - None
