---
id: linux.rpi-eeprom-update
title: Rpi Eeprom Update
desc: ''
updated: 1666779932590
created: 1666779932590
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rpi-eeprom-update

> Tool to update EEPROM and view other EEPROM information.
> More information: <https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#rpi-eeprom-update>.

- Print information about the current raspberry pi EEPROM installed:

`sudo rpi-eeprom-update`

- Update a raspberry pi EEPROM:

`sudo rpi-eeprom-update -a`

- Cancel the pending update:

`sudo rpi-eeprom-update -r`

- Display help:

`rpi-eeprom-update -h`

