---
id: common.krunvm
title: Krunvm
desc: ''
updated: 1670599066249
created: 1670599066249
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# krunvm

> CLI-based utility for creating MicroVMs from OCI images.
> More information: <https://github.com/containers/krunvm>.

- Create MicroVM based on Fedora:

`krunvm create {{docker.io/fedora}} --cpus {{number_of_vcpus}} --mem {{memory_in_megabytes}} --name "{{name}}"`

- Start a specific image:

`krunvm start "{{image_name}}"`

- List images:

`krunvm list`

- Change a specific image:

`krunvm changevm --cpus {{number_of_vcpus}} --mem {{memory_in_megabytes}} --name "{{new_vm_name}}" "{{current_vm_name}}"`

- Delete a specific image:

`krunvm delete "{{image_name}}"`

