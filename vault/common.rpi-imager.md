---
id: common.rpi-imager
title: Rpi Imager
desc: ''
updated: 1664685762043
created: 1664685762043
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rpi-imager

> Flash images onto storage devices.
> More information: <https://github.com/raspberrypi/rpi-imager>.

- Write a specific image to a specific block device:

`rpi-imager --cli {{path/to/image.zip}} {{/dev/sdX}}`

- Write a specific image to a block device, disabling the checksum verification:

`rpi-imager --cli --disable-verify {{path/to/image.zip}} {{/dev/sdX}}`

- Write a specific image to a block device, which will expect a specific checksum when running the verification:

`rpi-imager --cli --sha256 {{expected_hash}} {{path/to/image.zip}} {{/dev/sdX}}`

