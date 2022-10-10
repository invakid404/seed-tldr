---
id: linux.zipsplit
title: Zipsplit
desc: ''
updated: 1665415810409
created: 1665415810409
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zipsplit

> Read a zipfile and split it into smaller zipfiles.
> More information: <https://manned.org/zipsplit>.

- Split zipfile into pieces that are no larger than a particular size [n]&#x3A;

`zipsplit -n {{size}} {{path/to/archive.zip}}`

- [p]ause between the creation of each split zipfile:

`zipsplit -p -n {{size}} {{path/to/archive.zip}}`

- Output the split zipfiles into the `archive` directory:

`zipsplit -b {{archive}} -n {{size}} {{path/to/archive.zip}}`

