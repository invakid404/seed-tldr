---
id: common.pint
title: Pint
desc: ''
updated: 1664613092182
created: 1664613092182
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Pint

> An opinionated PHP code style fixer based on PHP-CS-Fixer.
> More information: <https://laravel.com/docs/pint>.

- Execute code style fixing:

`pint`

- Display all files that are changed:

`pint -v`

- Execute code style linting without applying changes:

`pint --test`

- Execute code style fixes using a specific config file:

`pint --config {{path/to/pint.json}}`

- Execute code style fixes using a specific preset:

`pint --preset {{psr12}}`

