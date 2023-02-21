---
id: common.act
title: Act
desc: ''
updated: 1676953371960
created: 1676953371960
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# act

> Execute GitHub Actions locally using Docker.
> More information: <https://github.com/nektos/act>.

- List the available actions:

`act -l`

- Run the default event:

`act`

- Run a specific event:

`act {{event_type}}`

- Run a specific action:

`act -a {{action_id}}`

- Do not actually run the actions (i.e. a dry run):

`act -n`

- Show verbose logs:

`act -v`

- Run a specific workflow:

`act push -W {{path/to/workflow}}`

