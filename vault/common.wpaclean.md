---
id: common.wpaclean
title: Wpaclean
desc: ''
updated: 1680390924285
created: 1680390924285
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wpaclean

> Clean capture files to get only the 4-way handshake and a beacon.
> Part of Aircrack-ng network software suite.
> More information: <https://manned.org/wpaclean.1>.

- Clean capture and save only the 4-way handshake and a beacon in the result:

`wpaclean {{path/to/result.cap}} {{path/to/capture.cap}}`

- Clean multiple captures and save 4-way handshakes and beacons in the result:

`wpaclean {{path/to/result.cap}} {{path/to/capture1.cap path/to/capture2.cap ...}}`

