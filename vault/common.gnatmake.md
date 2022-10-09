---
id: common.gnatmake
title: Gnatmake
desc: ''
updated: 1665354274156
created: 1665354274156
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnatmake

> A low-level build tool for Ada programs (part of the GNAT toolchain).
> More information: <https://gcc.gnu.org/onlinedocs/gnat_ugn/Building-with-gnatmake.html>.

- Compile an executable:

`gnatmake {{source_file1.adb source_file2.adb ...}}`

- Set a custom executable name:

`gnatmake -o {{executable_name}} {{source_file.adb}}`

- [f]orce recompilation:

`gnatmake -f {{source_file.adb}}`

