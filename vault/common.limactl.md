---
id: common.limactl
title: Limactl
desc: ''
updated: 1693948425559
created: 1693948425559
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# limactl

> Virtual machine manager for Linux guests, with multiple VM templates available.
> Can be used to run containers on macOS, but also for generic virtual machine use cases on macOS and Linux hosts.
> More information: <https://github.com/lima-vm/lima>.

- List VMs:

`limactl list`

- Create a VM using the default settings and optionally provide a name and/or a template (see `limactl create --list-templates` for available templates):

`limactl create --name {{vm_name}} template://{{debian|fedora|ubuntu|…}}`

- Start a VM (this might install some dependencies in it and take a few minutes):

`limactl start {{vm_name}}`

- Open a remote shell inside a VM:

`limactl shell {{vm_name}}`

- Run a command inside a VM:

`limactl shell {{vm_name}} {{command}}`

- Stop/shutdown a VM:

`limactl stop {{vm_name}}`

- Delete a VM:

`limactl remove {{vm_name}}`

