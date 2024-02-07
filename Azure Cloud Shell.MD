create a new Linux virtual machine
<blockquote>
az vm create --resource-group [sandbox resource group name] --location westus --name SampleVM --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys --verbose
</blockquote>

Connecting to the VM with SSH
<blockquote>
ssh azureuser@<public-ip-address>
</blockquote>


