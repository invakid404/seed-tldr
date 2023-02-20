---
id: windows.replace
title: Replace
desc: ''
updated: 1676881477682
created: 1676881477682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# replace

> Replace files.
> See also: `robocopy`, `move`, `copy`, and `del`.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/replace>.

- Replace the destination file with the one from the source directory:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}}`

- Add files to the destination directory instead of replacing existing files:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /a`

- Interactively copy multiple files, with a prompt before replacing or adding a destination file:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /p`

- Replace even read only files:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /r`

- Wait for you to insert a disk before it replaces files (originally to allow inserting a floppy disk):

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /w`

- Replace all files in subdirectories of the destination:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /s`

- Replace only files in the destination directory which are older than the files in the source directory:

`replace {{path\to\file_or_directory}} {{path\to\destination_directory}} /u`

- Display detailed usage information:

`replace /?`

