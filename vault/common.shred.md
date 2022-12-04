---
id: common.shred
title: Shred
desc: ''
updated: 1670145407062
created: 1670145407062
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shred

> Overwrite files to securely delete data.
> More information: <https://www.gnu.org/software/coreutils/shred>.

- Overwrite a file:

`shred {{path/to/file}}`

- Overwrite a file, leaving zeroes instead of random data:

`shred --zero {{path/to/file}}`

- Overwrite a file 25 times:

`shred -n25 {{path/to/file}}`

- Overwrite a file and remove it:

`shred --remove {{path/to/file}}`

