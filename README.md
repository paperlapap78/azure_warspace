create a resource group

`azure group create -n <ResourceGroupName> -l "australia southeast"`

deploy template into resource group

`azure group deployment create -f ./azuredeploy.json -g <ResourceGroupName> -n ExampleDeployment`
