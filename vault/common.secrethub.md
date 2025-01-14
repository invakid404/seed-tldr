---
id: common.secrethub
title: Secrethub
desc: ''
updated: 1670142131004
created: 1670142131004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# secrethub

> A tool to keep secrets out of config files.
> More information: <https://secrethub.io>.

- Print a secret to `stdout`:

`secrethub read {{path/to/secret}}`

- Generate a random value and store it as a new or updated secret:

`secrethub generate {{path/to/secret}}`

- Store a value from the clipboard as a new or updated secret:

`secrethub write --clip {{path/to/secret}}`

- Store a value supplied on `stdin` as a new or updated secret:

`echo "{{secret_value}}" | secrethub write {{path/to/secret}}`

- Audit a repository or secret:

`secrethub audit {{path/to/repo_or_secret}}`

