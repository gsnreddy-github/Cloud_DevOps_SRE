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
<br>az vm resize --resource-group [sandbox resource group name] --name SampleVM --size Standard_D2s_v3
</blockquote>

all virtual machines
<blockquote>
az vm list
</blockquote>

Output types
<blockquote>
az vm list --output table

<br>Along with table, you can specify json (the default), jsonc (colorized JSON), or tsv (Tab-Separated Values). Try a few variations with the preceding command to see the difference.
</blockquote>

Get the IP address
<blockquote>
az vm list-ip-addresses -n SampleVM -o table
</blockquote>

Get VM details
<blockquote>
az vm show --resource-group [sandbox resource group name] --name SampleVM
</blockquote>

Add filters to queries with JMESPath
<blockquote>
{
  "people": [
    {
      "name": "Fred",
      "age": 28
    },
    {
      "name": "Barney",
      "age": 25
    },
    {
      "name": "Wilma",
      "age": 27
    }
  ]
}

<br>
people[1] 
{
    "name": "Barney",
    "age": 25
}

<br>
people[?age > '25']
[
  {
    "name": "Fred",
    "age": 28
  },
  {
    "name": "Wilma",
    "age": 27
  }
]

<br>
people[?age > '25'].[name]
[
  [
    "Fred"
  ],
  [
    "Wilma"
  ]
]
</blockquote>

Filter your Azure CLI queries
<blockquote>
retrieve the admin username
az vm show --resource-group [sandbox resource group name] --name SampleVM --query "osProfile.adminUsername"

<br>
 get the size assigned to our VM
az vm show --resource-group ODL-azure-1224297 --name SampleVM --query hardwareProfile.vmSize

<br>
retrieve all the IDs for your network interfaces
az vm show --resource-group ODL-azure-1224297 --name SampleVM --query "networkProfile.networkInterfaces[].id"

az vm show --resource-group ODL-azure-1224297 --name SampleVM --query "networkProfile.networkInterfaces[].id" -o tsv
</blockquote>

Stop a VM
<blockquote>
az vm stop --name SampleVM --resource-group [sandbox resource group name]

<br>
verify the VM has stopped
az vm get-instance-view --name SampleVM --resource-group ODL-azure-1224297 --query "instanceView.statuses[?starts_with(code, 'PowerState/')].displayStatus" -o tsv
</blockquote>

Start a VM
<blockquote>
az vm start --name SampleVM --resource-group [sandbox resource group name]
</blockquote>

Restart a VM
<blockquote>
az vm restart  --name SampleVM --resource-group [sandbox resource group name] --no-wait
</blockquote>

<blockquote>
</blockquote>

<blockquote>
</blockquote>

<blockquote>
</blockquote>
