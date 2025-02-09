---
id: windows.findstr
title: Findstr
desc: ''
updated: 1664897374261
created: 1664897374261
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# findstr

> Find specified text within one or more files.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/findstr>.

- Find space-separated string(s) in all files:

`findstr "{{query}}" *`

- Find space-separated string(s) in a piped command's output:

`{{dir}} | findstr "{{query}}"`

- Find space-separated string(s) in all files recur[s]ively:

`findstr /s "{{query}}" *`

- Find strings using a case-insensitive search:

`findstr /i "{{query}}" *"`

- Find strings in all files using regular expressions:

`findstr /r "{{expression}}" *`

- Find a literal string (containing spaces) in all text files:

`findstr /c:"{{query}}" *.txt`

- Display the line number before each matching line:

`findstr /n "{{query}}" *`

- Display only the filenames that contain a match:

`findstr /m "{{query}}" *`

