---
id: linux.nmon
title: Nmon
desc: ''
updated: 1687904232973
created: 1687904232973
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmon

> A system administrator, tuner, and benchmark tool.
> More information: <https://manned.org/nmon>.

- Start `nmon`:

`nmon`

- Save records to file ("-s 300 -c 288" by default):

`nmon -f`

- Save records to file with a total of 240 measurements, by taking 30 seconds between each measurement:

`nmon -f -s {{30}} -c {{240}}`

