---
id: common.virt-sparsify
title: Virt Sparsify
desc: ''
updated: 1658926036848
created: 1658926036848
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-sparsify

> Make virtual machine drive images thin-provisioned.
> NOTE: Use only for offline machines to avoid data corruption.
> More information: <https://libguestfs.org>.

- Create a sparsified compressed image without snapshots from an unsparsified one:

`virt-sparsify --compress {{path/to/image.qcow2}} {{path/to/image_new.qcow2}}`

- Sparsify an image in-place:

`virt-sparsify --in-place {{path/to/image.img}}`

