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
az vm image list --publisher Microsoft --output table --all
</blockquote>

Location-specific images
<blockquote>
az vm image list --location eastus --output table
</blockquote>

<blockquote>

</blockquote>

<blockquote>

</blockquote>

<blockquote>

</blockquote>

<blockquote>

</blockquote>
