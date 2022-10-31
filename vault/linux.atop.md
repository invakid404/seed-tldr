---
id: linux.atop
title: Atop
desc: ''
updated: 1667229907381
created: 1667229907381
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atop

> Linux system and process monitor.
> More information: <https://manned.org/atop>.

- Start:

`atop`

- Start and display memory consumption for each process:

`atop -m`

- Start and display disk information:

`atop -d`

- Start and display background process information:

`atop -c`

- Start and display thread-specific resource utilization information:

`atop -y`

- Start and display the number of processes for each user:

`atop -au`

- Display help about interactive commands:

`?`

