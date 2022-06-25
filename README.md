# ARM-templates

This repo contains ARM templates that I am trying to build for a quicker deployment of any data analytics solution resource in Azure.

At this moment, the templates are separate entities. Template linking will be done once all the templates are in place. Once template linking is done, a complete data analytics resource group can be deployed with minimal effort.

## Usage

```powershell
New-AzResourceGroupDeployment -Name StorAcct -ResourceGroupName test-rg -TemplateFile .\storageAccount.json -TemplateParameterFile .\storageaccount.parameters.json
```

## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
