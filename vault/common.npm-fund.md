---
id: common.npm-fund
title: Npm Fund
desc: ''
updated: 1663554779490
created: 1663554779490
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# npm fund

> Retrieve funding information from packages.
> More information: <https://docs.npmjs.com/cli/v8/commands/npm-fund>.

- List dependencies with funding URL for the project in the current directory:

`npm fund`

- Open the funding URL for a specific package in the default web browser:

`npm fund {{package}}`

- List dependencies with a funding URL for a specific [w]orkspace for the project in the current directory:

`npm fund -w {{workspace}}`

