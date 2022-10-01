---
id: linux.size
title: Size
desc: ''
updated: 1664637955083
created: 1664637955083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# size

> Displays the sizes of sections inside binary files.
> More information: <https://sourceware.org/binutils/docs/binutils/size.html>.

- Display the size of sections in a given object or executable file:

`size {{path/to/file}}`

- Display the size of sections in a given object or executable file in [o]ctal:

`size {{-o|--radix=8}} {{path/to/file}}`

- Display the size of sections in a given object or executable file in [d]ecimal:

`size {{-d|--radix=10}} {{path/to/file}}`

- Display the size of sections in a given object or executable file in he[x]adecimal:

`size {{-x|--radix=16}} {{path/to/file}}`

