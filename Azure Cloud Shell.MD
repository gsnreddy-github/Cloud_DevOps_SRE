create a new Linux virtual machine
<blockquote>
az vm create --resource-group [sandbox resource group name] --location westus --name SampleVM --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys --verbose
</blockquote>

Connecting to the VM with SSH
<blockquote>
ssh azureuser@<public-ip-address>
</blockquote>



This command returns a list of all the possible size configurations available in the resource group. 

az vm list-vm-resize-options --resource-group [sandbox resource group name] --name SampleVM --output table

To resize a VM
az vm resize --resource-group [sandbox resource group name] --name SampleVM --size Standard_D2s_v3
