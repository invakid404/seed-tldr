---
id: common.mytop
title: Mytop
desc: ''
updated: 1687904232871
created: 1687904232871
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mytop

> Display MySQL server performance info like `top`.
> More information: <http://jeremy.zawodny.com/mysql/mytop/mytop.html>.

- Start `mytop`:

`mytop`

- Connect with a specified username and password:

`mytop -u {{user}} -p {{password}}`

- Connect with a specified username (the user will be prompted for a password):

`mytop -u {{user}} --prompt`

- Do not show any idle (sleeping) threads:

`mytop -u {{user}} -p {{password}} --noidle`

