---
id: linux.ifmetric
title: Ifmetric
desc: ''
updated: 1680858961906
created: 1680858961906
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ifmetric

> An IPv4 route metrics manipulation tool.
> More information: <https://0pointer.de/lennart/projects/ifmetric/>.

- Set the priority of the specified network interface (a higher number indicates lower priority):

`sudo ifmetric {{interface}} {{value}}`

- Reset the priority of the specified network interface:

`sudo ifmetric {{interface}} {{0}}`

