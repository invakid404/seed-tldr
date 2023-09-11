---
id: common.l2ping
title: L2ping
desc: ''
updated: 1694438414628
created: 1694438414628
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# l2ping

> Send an L2CAP echo request and receive an answer.
> More information: <https://manned.org/l2ping>.

- Ping a Bluetooth device:

`sudo l2ping {{mac_address}}`

- Reverse ping a Bluetooth device:

`sudo l2ping -r {{mac_address}}`

- Ping a Bluetooth device from a specified interface:

`sudo l2ping -i {{hci0}} {{mac_address}}`

- Ping Bluetooth device with a specified sized data package:

`sudo l2ping -s {{byte_count}} {{mac_address}}`

- Ping flood a Bluetooth device:

`sudo l2ping -f {{mac_address}}`

- Ping a Bluetooth device a specified amount of times:

`sudo l2ping -c {{amount}} {{mac_address}}`

- Ping a Bluetooth device with a specified delay between requests:

`sudo l2ping -d {{seconds}} {{mac_address}}`

