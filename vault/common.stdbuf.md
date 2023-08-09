---
id: common.stdbuf
title: Stdbuf
desc: ''
updated: 1691562059088
created: 1691562059088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stdbuf

> Run a command with modified buffering operations for its standard streams.
> More information: <https://www.gnu.org/software/coreutils/stdbuf>.

- Change `stdin` buffer size to 512 KiB:

`stdbuf --input={{512K}} {{command}}`

- Change `stdout` buffer to line-buffered:

`stdbuf --output={{L}} {{command}}`

- Change `stderr` buffer to unbuffered:

`stdbuf --error={{0}} {{command}}`

