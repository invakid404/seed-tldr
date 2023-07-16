---
id: common.gh-alias
title: Gh Alias
desc: ''
updated: 1689531679576
created: 1689531679576
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh alias

> Manage GitHub CLI command aliases.
> More information: <https://cli.github.com/manual/gh_alias>.

- Display the subcommand help:

`gh alias`

- List all the aliases `gh` is configured to use:

`gh alias list`

- Create a `gh` subcommand alias:

`gh alias set {{pv}} '{{pr view}}'`

- Set a shell command as a `gh` subcommand:

`gh alias set --shell {{alias_name}} {{command}}`

- Delete a command shortcut:

`gh alias delete {{alias_name}}`

