---
id: windows.assoc
title: Assoc
desc: ''
updated: 1671503955972
created: 1671503955972
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# assoc

> Display or change associations between file extensions and file types.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/assoc>.

- List all associations between file extensions and file types:

`assoc`

- Display the associated file type for a specific extension:

`assoc {{.txt}}`

- Set the associated file type for a specific extension:

`assoc .{{txt}}={{txtfile}}`

- View the output of `assoc` one screen at a time:

`assoc | {{more}}`

