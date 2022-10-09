---
id: common.aws-history
title: Aws History
desc: ''
updated: 1665294081708
created: 1665294081708
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws history

> Print the command-line history for AWS CLI commands (the record of history of AWS CLI commands must be enabled).
> More information: <https://docs.aws.amazon.com/cli/latest/reference/history/>.

- List commands history with command IDs:

`aws history list`

- Display events related to a specific command given a command ID:

`aws history show {{command_id}}`

