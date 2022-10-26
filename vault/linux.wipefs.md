---
id: linux.wipefs
title: Wipefs
desc: ''
updated: 1666750046497
created: 1666750046497
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wipefs

> Wipe filesystem, raid, or partition-table signatures from a device.
> More information: <https://manned.org/wipefs>.

- Display signatures for specified device:

`sudo wipefs {{/dev/sdX}}`

- Wipe all available signature types for a specific device with no recursion into partitions:

`sudo wipefs --all {{/dev/sdX}}`

- Wipe all available signature types for the device and partitions using a glob pattern:

`sudo wipefs --all {{/dev/sdX}}*`

- Perform dry run:

`sudo wipefs --all --no-act {{/dev/sdX}}`

- Force wipe, even if the filesystem is mounted:

`sudo wipefs --all --force {{/dev/sdX}}`

