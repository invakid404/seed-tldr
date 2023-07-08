---
id: linux.swaplabel
title: Swaplabel
desc: ''
updated: 1688840469676
created: 1688840469676
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# swaplabel

> Print or change the label or UUID of a swap area.
> Note: `path/to/file` can either point to a regular file or a swap partition.
> More information: <https://manned.org/swaplabel>.

- Display the current label and UUID of a swap area:

`swaplabel {{path/to/file}}`

- Set the label of a swap area:

`swaplabel --label {{new_label}} {{path/to/file}}`

- Set the UUID of a swap area (you can generate a UUID using `uuidgen`):

`swaplabel --uuid {{new_uuid}} {{path/to/file}}`

