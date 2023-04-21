---
id: common.charm
title: Charm
desc: ''
updated: 1682058094813
created: 1682058094813
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# charm

> Set of tools that makes adding a backend to your terminal-based applications, without worrying about user accounts, data storage and encryption.
> More information: <https://github.com/charmbracelet/charm>.

- Backup your Charm account keys:

`charm backup-keys`

- Backup Charm account keys to a specific location:

`charm backup-keys -o {{path/to/output_file.tar}}`

- Import previously backed up Charm account keys:

`charm import-keys "{{charm-keys-backup.tar}}"`

- Find where your `cloud.charm.sh` folder resides on your machine:

`charm where`

- Start your Charm server:

`charm serve`

- Print linked SSH keys:

`charm keys`

- Print your Charm ID:

`charm id`

