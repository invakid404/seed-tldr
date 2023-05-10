---
id: common.rarcrack
title: Rarcrack
desc: ''
updated: 1683695739557
created: 1683695739557
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rarcrack

> Password cracker for rar, zip and 7z archives.

- Brute force the password for an archive (tries to guess the archive type):

`rarcrack {{path/to/file.zip}}`

- Specify the archive type:

`rarcrack --type {{rar|zip|7z}} {{path/to/file.zip}}`

- Use multiple threads:

`rarcrack --threads {{6}} {{path/to/file.zip}}`

