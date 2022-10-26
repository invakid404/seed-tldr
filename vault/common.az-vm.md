---
id: common.az-vm
title: Az Vm
desc: ''
updated: 1666757584501
created: 1666757584501
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az vm

> Manage virtual machines in Azure.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/vm>.

- List details of available Virtual Machines:

`az vm list`

- Create a virtual machine using the default Ubuntu image and generate ssh keys:

`az vm create --resource-group {{rg}} --name {{vm_name}} --image {{UbuntuLTS}} --admin-user {{azureuser}} --generate-ssh-keys`

- Stop a Virtual Machine:

`az vm stop --resource-group {{rg}} --name {{vm_name}}`

- Deallocate a Virtual Machine:

`az vm deallocate --resource-group {{rg}} --name {{vm_name}}`

- Start a Virtual Machine:

`az vm start --resource-group {{rg}} --name {{vm_name}}`

- Restart a Virtual Machine:

`az vm restart --resource-group {{rg}} --name {{vm_name}}`

- List VM images available in the Azure Marketplace:

`az vm image list`

