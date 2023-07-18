---
id: linux.mlabel
title: Mlabel
desc: ''
updated: 1689697454285
created: 1689697454285
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mlabel

> Set an MS-DOS volume label for FAT and VFAT filesystems.
> More information: <https://www.gnu.org/software/mtools/manual/mtools.html#mlabel>.

- Set a filesystem label:

`mlabel -i /dev/{{sda}} ::"{{new_label}}"`

