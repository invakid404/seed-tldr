---
id: windows.robocopy
title: Robocopy
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
# robocopy

> Robust File and Folder Copy.
> By default files will only be copied if the source and destination have different time stamps or different file sizes.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/robocopy>.

- Copy all `.jpg` and `.bmp` files from one directory to another:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} {{*.jpg}} {{*.bmp}}`

- Copy all files and subdirectories, including empty ones:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} /E`

- Mirror/Sync a directory, deleting anything not in source and include all attributes and permissions:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} /MIR /COPYALL`

- Copy all files and subdirectories, excluding source files that are older than destination files:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} /E /XO`

- List all files 50 MB or larger instead of copying them:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} /MIN:{{52428800}} /L`

- Allow resuming if network connection is lost and limit retries to 5 and wait time to 15 sec:

`robocopy {{path\to\source_directory}} {{path\to\destination_directory}} /Z /R:5 /W:15`

- Display detailed usage information:

`robocopy /?`

