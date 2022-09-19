---
id: common.transmission-edit
title: Transmission Edit
desc: ''
updated: 1663583284579
created: 1663583284579
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transmission-edit

> Modify announce URLs from torrent files.
> See also: `transmission`.
> More information: <https://manned.org/transmission-edit>.

- Add or remove a URL from a torrent's announce list:

`transmission-edit --{{add|delete}} {{http://example.com}} {{path/to/file.torrent}}`

- Update a tracker's passcode in a torrent file:

`transmission-edit --replace {{old-passcode}} {{new-passcode}} {{path/to/file.torrent}}`

