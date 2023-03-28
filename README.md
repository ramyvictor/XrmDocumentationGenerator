# XrmSimplSyntaxGeneratorCLI
Welcome to the XrmSimplSyntaxGeneratorCLI repository!

The primary purpose of this repository is to showcase the output of the CLI. Here, you can find an example of documents that have been generated from a solution containing Account and Case tables.



## Install
[XrmDocumentationGeneratorCoreCLI  Nuget URL](https://www.nuget.org/packages/XrmDocumentationGeneratorCoreCLI/)
```sh
dotnet tool install --g XrmDocumentationGeneratorCoreCLI
```
## Run command

```sh
XrmDocumentationGeneratorCoreCLI generate -connection $connectionString -solution $solutionName -out $outputPath -documentType $documentType
```
## Azure DevOps Extension Marketplace
[Xrm PowerApps Toolset Extension](https://marketplace.visualstudio.com/items?itemName=xrm-world.xrm-powerapps-tools)
```sh
- task: XrmDocumentationGenerator@1
  displayName: 'Generate XRM Documentation'
  inputs:
    connectionString: 'AuthType=ClientSecret;url=https://$(Url).dynamics.com;ClientId=$(ClientId);ClientSecret=$(ClientSecret)'
    solutionName: '$(SolutionName)'
    outputPath: $(Build.SourcesDirectory)\$(OutputPath)
```
# Examples
## Account
1. [Table diagram](Docs/Account/Mermaid.md)
1. [Account](Docs/Account/Forms/Account.md)
## Case
1. [Table diagram](Docs/Case/Mermaid.md)
1. [Case](Docs/Case/Forms/Case.md)


# Author

Ramy Victor

[!["Buy Me A Coffee"](https://raw.githubusercontent.com/ramyvictor/CommonFiles/main/assets/images/orange_img.webp)](https://www.buymeacoffee.com/ramyv)

# License

This project is licensed under the MIT License.
