az configure --defaults location=westus2
az group create --name azure-practice
az storage account create --name infyblobstorage  --resource-group azure-practice  --kind StorageV2 --sku Standard_LRS

