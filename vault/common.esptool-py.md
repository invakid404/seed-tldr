---
id: common.esptool-py
title: Esptool Py
desc: ''
updated: 1667074975043
created: 1667074975043
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# esptool.py

> Bootloader utility for Espressif chips (e.g. ESP8266).
> More information: <https://docs.espressif.com/projects/esptool/en/latest/esp32/>.

- Flash a firmware file to an ESP chip with a given port and baud rate:

`sudo esptool.py --port {{port}} --baud {{baud_rate}} write_flash 0x0 {{path/to/firmware.bin}}`

- Clear the flash of an ESP chip:

`sudo esptool.py --port {{port}} --baud {{baud_rate}} erase_flash`

