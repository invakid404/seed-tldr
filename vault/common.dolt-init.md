---
id: common.dolt-init
title: Dolt Init
desc: ''
updated: 1665876524691
created: 1665876524691
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dolt init

> Create an empty Dolt data repository.
> More information: <https://docs.dolthub.com/cli-reference/cli#dolt-init>.

- Initialize a new Dolt data repository in the current directory:

`dolt init`

- Initialize a new Dolt data repository creating a commit with the specified metadata:

`dolt init --name "{{name}}" --email "{{email}}" --date "{{2021-12-31T00:00:00}}" -b "{{branch_name}}"`

