---
id: common.pop
title: Pop
desc: ''
updated: 1691252319863
created: 1691252319863
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pop

> Send emails from your terminal.
> More information: <https://github.com/charmbracelet/pop>.

- Launch the Text-based User Interface:

`pop`

- Send an email using the content of a Markdown file as body:

`pop < {{path/to/message.md}} --from {{me@example.com}} --to {{you@example.com}} --subject "{{On the Subject of Ducks...}}" --attach {{path/to/attachment}}`

- Display help and exit:

`pop --help`

