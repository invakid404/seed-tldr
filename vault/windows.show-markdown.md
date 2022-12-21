---
id: windows.show-markdown
title: Show Markdown
desc: ''
updated: 1671599771481
created: 1671599771481
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Show-Markdown

> Shows a Markdown file or string in the console in a friendly way using VT100 escape sequences or in a browser using HTML.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.utility/show-markdown>.

- Render markdown to console from a file:

`Show-Markdown -Path {{path/to/file}}`

- Render markdown to console from string:

`{{"# Markdown content"}} | Show-Markdown`

- Open Markdown file in a browser:

`Show-Markdown -Path {{path/to/file}} -UseBrowser`

