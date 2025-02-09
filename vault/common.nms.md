---
id: common.nms
title: Nms
desc: ''
updated: 1670142130970
created: 1670142130970
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nms

> Command-line tool that recreates the famous data decryption effect seen in the 1992 movie Sneakers from `stdin`.
> More information: <https://github.com/bartobri/no-more-secrets>.

- Decrypt text after a keystroke:

`echo "{{Hello, World!}}" | nms`

- Decrypt output immediately, without waiting for a keystroke:

`{{ls -la}} | nms -a`

- Decrypt the content of a file, with a custom output color:

`cat {{path/to/file}} | nms -a -f {{blue|white|yellow|black|magenta|green|red}}`

- Clear the screen before decrypting:

`{{command}} | nms -a -c`

