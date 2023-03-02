---
id: windows.prompt
title: Prompt
desc: ''
updated: 1677777453985
created: 1677777453985
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prompt

> Change the default DOS style prompt in a command window.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/prompt>.

- Reset the prompt to the default setting:

`prompt`

- Set a specific prompt:

`prompt {{prompt}}`

- Change the prompt to show the current date first:

`prompt $D $P$G`

- Change the prompt to show the current time first:

`prompt $T $P$G`

- Change the prompt by adding a specific text first:

`prompt {{text}} $P$G`

