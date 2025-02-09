---
id: windows.if
title: If
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
# if

> Performs conditional processing in batch scripts.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/if>.

- Execute the specified commands if the condition is true:

`if {{condition}} ({{echo Condition is true}})`

- Execute the specified commands if the condition is false:

`if not {{condition}} ({{echo Condition is true}})`

- Execute the first specified commands if the condition is true otherwise execute the second specified commands:

`if {{condition}} ({{echo Condition is true}}) else ({{echo Condition is false}})`

- Check whether `%errorlevel%` is greater than or equal to the specified exit code:

`if errorlevel {{2}} ({{echo Condition is true}})`

- Check whether two strings are equal:

`if %{{variable}}% == {{string}} ({{echo Condition is true}})`

- Check whether two strings are equal without respecting letter case:

`if /i %{{variable}}% == {{string}} ({{echo Condition is true}})`

- Check whether a file exist:

`if exist {{path\to\file}} ({{echo Condition is true}})`

