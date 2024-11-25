
# Microsoft Defender for Cloud Simulation Playbook

There are many ways to simulate an alert in Microsoft Defender for Cloud and if you just want a simple validation to get an alert, use the procedures described in [this article](https://docs.microsoft.com/en-us/azure/security-center/security-center-alert-validation). For a more scenario-based approach, you have the resources below that you can use to validate different threat detections capabilities available in Microsoft Defender for Cloud.

## Alert Simulation for  Defender for Servers (Azure and Non-Azure VMs - Windows)

- Download this [PDF](https://github.com/Azure/Microsoft-Defender-for-Cloud/blob/main/Simulations/Microsoft%20Defender%20for%20Cloud%20Security%20Alerts%20Playbook_v3.pdf) and follow the steps to configure a lab environment to test Windows VM-based threat detection.

- [Defender for Servers - Windows documentation](https://docs.microsoft.com/en-us/azure/security-center/security-center-alerts-iaas#windows-)

- [Defender for Servers - Windows Alerts](https://docs.microsoft.com/en-us/azure/security-center/alerts-reference#alerts-windows)

If you are testing the integration with MDE, use [this article](https://docs.microsoft.com/en-us/azure/security-center/security-center-wdatp#test-the-feature) to validate the alert integration. Make sure that the server that you are testing this procedure is already onboarded and using MDATP.

## Alert Simulation for  Defender for Servers (Azure and Non-Azure VMs - Linux)

- Download this [PDF](https://github.com/Azure/Microsoft-Defender-for-Cloud/blob/main/Simulations/Microsoft%20Defender%20for%20cloud%20Linux%20Detections%20V3.pdf) and follow the steps to configure a lab environment to test Linux VM-based threat detection.

- [Defender for Server - Linux documentation](https://docs.microsoft.com/en-us/azure/security-center/security-center-alerts-iaas#linux-)

- [Defender for Server - Linux Alerts](https://docs.microsoft.com/en-us/azure/security-center/alerts-reference#alerts-linux)


## Alert Simulation for  Defender for Containers
- [This article](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/how-to-demonstrate-the-new-containers-features-in-microsoft/ba-p/3281172) go over the steps to simulate alerts in Azure Kubernetes Services and Azure Container Registry.

- [Defender for Containers](https://docs.microsoft.com/en-us/azure/defender-for-cloud/defender-for-containers-introduction?tabs=defender-for-container-arch-aks)


## Alert Simulation for Defender for Storage
- [This article](https://techcommunity.microsoft.com/t5/azure-security-center/validating-atp-for-azure-storage-detections-in-azure-security/ba-p/1068131) go over the steps to simulate an upload of a test malware (EICAR) to an Azure Storage account that has Defender for Storage enabled.

- [Defender Storage](https://docs.microsoft.com/en-us/azure/security-center/defender-for-storage-introduction)

## Alert Simulation for Defender for Key Vault
- [This article](https://techcommunity.microsoft.com/t5/azure-security-center/validating-azure-key-vault-threat-detection-in-azure-security/ba-p/1220336) go over the steps to simulate an anonymizer access to the Key Vault using a TOR browser.

- [Defender for Key Vault](https://docs.microsoft.com/en-us/azure/security-center/defender-for-key-vault-introduction)

## Alert Simulation for Defender for Resource Manager
- [This article](https://techcommunity.microsoft.com/t5/azure-security-center/validating-azure-defender-for-resource-manager-alerts/ba-p/2227469) go over the steps to simulate an extension manipulation using Azure Resource Manager.

- [Defender for Resource Manager](https://docs.microsoft.com/en-us/azure/security-center/defender-for-resource-manager-introduction)

## Alert Simulation for Defender for DNS
- [This article](https://techcommunity.microsoft.com/t5/azure-security-center/validating-azure-defender-for-dns-alerts/ba-p/2227845) go over the steps to simulate an attack that can be identified by Azure Defender for DNS.

- [Defender for DNS](https://docs.microsoft.com/en-us/azure/security-center/defender-for-dns-introduction)

## Alert Simulation for Defender for App Service
- [This article](https://techcommunity.microsoft.com/t5/azure-security-center/azure-defender-poc-series-azure-defender-for-app-service/ba-p/2652443) go over the steps to simulate an attack that can be identified by Defender for App Service.

- [Defender for App Service](https://docs.microsoft.com/en-us/azure/security-center/defender-for-app-service-introduction)

## Alert Simulation for Defender for SQL on Machines
- [This article](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/validating-alerts-on-microsoft-defender-for-sql-on-machines/ba-p/3070714) go over the steps to simulate an attack that can be identified by Defender for SQL on Machines.

- [Defender for SQL on Machine](https://docs.microsoft.com/en-us/azure/defender-for-cloud/defender-for-sql-usage)

## Alert Simulation for Defender for APIs
- [This article](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/validating-microsoft-defender-for-apis-alerts/ba-p/3803874) covers the steps to simulate an attack on an API endpoint that can be identified by Defender for APIs.

- [Defender for APIs](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-apis-introduction)

## Threat Hunting in Microsoft Defender for Cloud and Log Analytics Workspace

- This simulation playbook go over a threat hunting scenario using Microsoft Defender for Cloud and searching for evidences of attack in Log Analtyics workspace.

- Download [this PDF](https://github.com/Azure/Microsoft-Defender-for-Cloud/blob/main/Simulations/Microsoft%20Defender%20for%20Cloud%20Hunting%20Playbook_V3.pdf) and follow the steps to configure a lab environment, simulate alerts in Windows and query data using KQL in Log Analytics workspace.
