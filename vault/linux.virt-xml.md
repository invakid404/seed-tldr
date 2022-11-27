---
id: linux.virt-xml
title: Virt Xml
desc: ''
updated: 1669533416508
created: 1669533416508
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-xml

> Edit libvirt Domain XML files with explicit command line options.
> NOTE: 'domain' refers to the name, UUID or ID for the existing VMs (See: tldr virsh).
> More information: <https://github.com/virt-manager/virt-manager/blob/main/man/virt-xml.rst>.

- List all the suboptions for a specific option:

`virt-xml --{{option}}=?`

- List all the suboptions for disk, network, and boot:

`virt-xml --disk=? --network=? --boot=?`

- Edit a value for a specific domain:

`virt-xml {{domain}} --edit --{{option}} {{suboption}}={{new_value}}`

- Change the description for a specific domain:

`virt-xml {{domain}} --edit --metadata description="{{new_description}}"`

- Enable/Disable the boot device menu for a specific domain:

`virt-xml {{domain}} --edit --boot bootmenu={{on|off}}`

- Attach host USB hub to a running VM (See: tldr lsusb):

`virt-xml {{domain}} --update --add-device --hostdev {{bus}}.{{device}}`

