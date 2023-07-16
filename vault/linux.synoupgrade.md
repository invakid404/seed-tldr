---
id: linux.synoupgrade
title: Synoupgrade
desc: ''
updated: 1689531679863
created: 1689531679863
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# synoupgrade

> Upgrade Synology DiskStation Manager (DSM) - the Synology NAS operating system.
> More information: <https://www.synology.com/dsm>.

- Check if upgrades are available:

`sudo synoupgrade --check`

- Check for patches without upgrading the DSM version:

`sudo synoupgrade --check-smallupdate`

- Download the latest upgrade available (use `--download-smallupdate` for patches):

`sudo synoupgrade --download`

- Start the upgrade process:

`sudo synoupgrade --start`

- Upgrade to the latest version automatically:

`sudo synoupgrade --auto`

- Apply patches without upgrading the DSM version automatically:

`sudo synoupgrade --auto-smallupdate`

- Upgrade the DSM using a patch file (should be an absolute path):

`sudo synoupgrade --patch {{/path/to/file.pat}}`

- Display help:

`synoupgrade`

