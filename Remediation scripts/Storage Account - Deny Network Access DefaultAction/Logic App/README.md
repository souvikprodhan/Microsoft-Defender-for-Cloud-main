## Introduction
Use this deployment template to create a Logic App to set Deny as DefaultAction for storage acocunt NACLs. 
```json
"networkAcls": {
   "defaultAction": "Deny"
}
```
The Logic App iterates through all storage account in enabled subscriptions.
The Logic App is configured as scheduled trigger with frequency of once per day.
Day based schedule needs to be configured atleast 24 hours prior.

## Post Deployment
- Enable Logic App
- Enable System Manged Identity
- Assign System Managed Identity **Storage Account Contributor** role at subscription level

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
