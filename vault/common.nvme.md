---
id: common.nvme
title: Nvme
desc: ''
updated: 1680754800402
created: 1680754800402
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nvme

> NVMe storage user space utility.
> More information: <https://github.com/linux-nvme/nvme-cli>.

- List all nvme devices:

`sudo nvme list`

- Show device information:

`sudo nvme smart-log {{device}}`

