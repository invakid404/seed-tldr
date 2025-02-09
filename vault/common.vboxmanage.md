---
id: common.vboxmanage
title: Vboxmanage
desc: ''
updated: 1656591837587
created: 1656591837587
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# VBoxManage

> Command-line interface to VirtualBox.
> Includes all the functionality of the GUI and more.
> More information: <https://www.virtualbox.org/manual/ch08.html#vboxmanage-intro>.

- List all VirtualBox virtual machines:

`VBoxManage list vms`

- Show information about a particular virtual machine:

`VBoxManage showvminfo {{name|uuid}}`

- Start a virtual machine:

`VBoxManage startvm {{name|uuid}}`

- Start a virtual machine in headless mode:

`VBoxManage startvm {{name|uuid}} --type headless`

- Shutdown the virtual machine and save its current state:

`VBoxManage controlvm {{name|uuid}} savestate`

- Shutdown down the virtual machine without saving its state:

`VBoxManage controlvm {{name|uuid}} poweroff`

- Update VBox extension packs:

`VBoxManage extpack install --replace {{VboxExtensionPackFileName}}`

