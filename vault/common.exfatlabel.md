---
id: common.exfatlabel
title: Exfatlabel
desc: ''
updated: 1688919732373
created: 1688919732373
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# exfatlabel

> Get or set an exFAT filesystem label.
> More information: <https://manned.org/exfatlabel>.

- Display the current filesystem label:

`exfatlabel {{/dev/sda}}`

- Set the filesystem label:

`exfatlabel {{/dev/sda}} {{new_label}}`

