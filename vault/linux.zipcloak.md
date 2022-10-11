---
id: linux.zipcloak
title: Zipcloak
desc: ''
updated: 1665463523251
created: 1665463523251
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipcloak

> Encrypt the contents within a zipfile.
> More information: <https://manned.org/zipcloak>.

- Encrypt the contents of a zipfile:

`zipcloak {{path/to/archive.zip}}`

- [d]ecrypt the contents of a zipfile:

`zipcloak -d {{path/to/archive.zip}}`

- [O]utput the encrypted contents into a new zipfile:

`zipcloak {{path/to/archive.zip}} -O {{path/to/encrypted.zip}}`

