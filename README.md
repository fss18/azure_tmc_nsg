# Azure network security group for Alert Logic Threat Manager marketplace.

Use the provided link to deploy the NSG based on ARM template, this would be one click deployment of NSG prior to customer creating the VM from the Azure Marketplace.
Steps:
1. Customer login to Azure portal using their credentials.
2. Create one resource group for Alert Logic related resources.
3. Use the link to deploy the NSG: https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ffss18%2Fazure_tmc_nsg%2Fmaster%2Fazure_tmc_nsg_template.json
4. Choose the resource group that previously created on step 2.
5. Enter the required parameters:
6. Once the NSG has been deployed, follow the rest of instruction for Azure Marketplace deployment (https://docs.alertlogic.com/cloud/microsoft-azure-threat-manager-iaas-marketplace.htm)
