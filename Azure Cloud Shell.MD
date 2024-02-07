create a new Linux virtual machine
<blockquote>
az vm create --resource-group [sandbox resource group name] --location westus --name SampleVM --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys --verbose
</blockquote>

Connecting to the VM with SSH
<blockquote>
ssh azureuser@<public-ip-address>
</blockquote>

Listing images
<blockquote>
az vm image list --output table
</blockquote>

Getting all images
<blockquote>
az vm image list --sku Wordpress --output table --all
<br>az vm image list --publisher Microsoft --output table --all
</blockquote>

Location-specific images
<blockquote>
az vm image list --location eastus --output table
</blockquote>

list of the available sizes
<blockquote>
az vm list-sizes --location eastus --output table
</blockquote>

Specify a size during VM creation
<blockquote>
az vm create --resource-group [sandbox resource group name] --name SampleVM2 --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys --verbose --size "Standard_DS2_v2"
</blockquote>

Resize an existing VM
<blockquote>
az vm list-vm-resize-options --resource-group [sandbox resource group name] --name SampleVM --output table
<br>az vm resize \
    --resource-group [sandbox resource group name] \
    --name SampleVM \
    --size Standard_D2s_v3
</blockquote>

<blockquote>

</blockquote>
