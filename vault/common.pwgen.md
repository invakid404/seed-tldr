---
id: common.pwgen
title: Pwgen
desc: ''
updated: 1656591837553
created: 1656591837553
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pwgen

> Generate pronounceable passwords.
> More information: <https://github.com/tytso/pwgen>.

- Generate random password with s[y]mbols:

`pwgen -y {{length}}`

- Generate secure, hard-to-memorize passwords:

`pwgen -s {{length}}`

- Generate password with at least one capital letter in them:

`pwgen -c {{length}}`

