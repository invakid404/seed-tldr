---
id: common.gyb
title: Gyb
desc: ''
updated: 1666107123398
created: 1666107123398
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gyb

> Command line tool for locally backing up Gmail messages using Gmail's API over HTTPS.
> More information: <https://github.com/GAM-team/got-your-back>.

- Estimate the number and the size of all emails on your Gmail account:

`gyb --email {{email@gmail.com}} --action estimate`

- Backup a Gmail account to a specific directory:

`gyb --email {{email@gmail.com}} --action backup --local-folder {{path/to/directory}}`

- Backup only important or starred emails from a Gmail account to the default local folder:

`gyb --email {{email@gmail.com}} --search "{{is:important OR is:starred}}"`

- Restore from a local folder to a Gmail account:

`gyb --email {{email@gmail.com}} --action restore --local-folder {{path/to/directory}}`

