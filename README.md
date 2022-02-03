az extension add --name azure-batch-cli-extensions

- Create batch account before

az batch pool create --template pool.json --account-name batch --account-endpoint https://asdf.westeurope.batch.azure.com

az batch job create --template job.json --account-name batch --account-endpoint https://asdf.westeurope.batch.azure.com
