---
id: linux.zbarcam
title: Zbarcam
desc: ''
updated: 1688840469687
created: 1688840469687
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zbarcam

> Scans and decodes barcodes (and QR codes) from a video device.
> More information: <https://manned.org/zbarcam>.

- Continuously read barcodes and print them to standard output:

`zbarcam`

- Disable output video window while scanning:

`zbarcam --nodisplay`

- Print barcodes without type information:

`zbarcam --raw`

- Define capture device:

`zbarcam /dev/{{video_device}}`

