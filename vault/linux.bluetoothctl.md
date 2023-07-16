---
id: linux.bluetoothctl
title: Bluetoothctl
desc: ''
updated: 1689531679781
created: 1689531679781
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bluetoothctl

> Manage Bluetooth devices.
> More information: <https://bitbucket.org/serkanp/bluetoothctl>.

- Enter the `bluetoothctl` shell:

`bluetoothctl`

- List all known devices:

`bluetoothctl devices`

- Power the Bluetooth controller on or off:

`bluetoothctl power {{on|off}}`

- Pair with a device:

`bluetoothctl pair {{mac_address}}`

- Remove a device:

`bluetoothctl remove {{mac_address}}`

- Connect to a paired device:

`bluetoothctl connect {{mac_address}}`

- Disconnect from a paired device:

`bluetoothctl disconnect {{mac_address}}`

- Display help:

`bluetoothctl help`

