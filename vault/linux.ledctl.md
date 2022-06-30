---
id: linux.ledctl
title: Ledctl
desc: ''
updated: 1656591837631
created: 1656591837631
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ledctl

> Intel(R) Enclosure LED Control Application.
> More information: <https://manned.org/ledctl>.

- Turn on the "Locate" LED for specified device(s):

`sudo ledctl locate={{/dev/sda,/dev/sdb,...}}`

- Turn off the "Locate" LED for specified device(s):

`sudo ledctl locate_off={{/dev/sda,/dev/sdb,...}}`

- Turn off the "Status" LED and "Failure" LED for specified device(s):

`sudo ledctl off={{/dev/sda,/dev/sdb,...}}`

- Turn off the "Status" LED, "Failure" LED and "Locate" LED for specified device(s):

`sudo ledctl normal={{/dev/sda,/dev/sdb,...}}`

