# Add a New NSG to an Existing Subnet

This template applies a newly created NSG to an existing subnet.

New-AzResourceGroup -Name <resource-group-name> -Location <resource-group-location> #use this command when you need to create a new resource group for your deployment<p>
New-AzResourceGroupDeployment -ResourceGroupName <resource-group-name> -TemplateUri https://raw.githubusercontent.com/gfk76/add-nsg-to-subnet/master/azuredeploy.json

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/gfk76/add-nsg-to-subnet/master/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/gfk76/add-nsg-to-subnet/master/azuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>