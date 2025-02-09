---
id: windows.measure-object
title: Measure Object
desc: ''
updated: 1676881477679
created: 1676881477679
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Measure-Object

> Calculates the numeric properties of objects, and the characters, words, and lines in string objects, such as files of text.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/measure-object>.

- Count the files and folders in a directory:

`Get-ChildItem | Measure-Object`

- Pipe input to Measure-Command (objects that are piped to `Measure-Command` are available to the script block that is passed to the Expression parameter):

`"One", "Two", "Three", "Four" | Set-Content -Path "{{path\to\file}}"; Get-Content "{{path\to\file}}"; | Measure-Object -Character -Line -Word`

