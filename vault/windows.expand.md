---
id: windows.expand
title: Expand
desc: ''
updated: 1676881477678
created: 1676881477678
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# expand

> Uncompress one or more Windows Cabinet files.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/expand>.

- Uncompress a single-file Cabinet file to the specified directory:

`expand {{path\to\file.cab}} {{path\to\directory}}`

- Display the list of files in a source Cabinet file:

`expand {{path\to\file.cab}} {{path\to\directory}} -d`

- Uncompress all files from the Cabinet file:

`expand {{path\to\file.cab}} {{path\to\directory}} -f:*`

- Uncompress a specific file from a Cabinet file:

`expand {{path\to\file.cab}} {{path\to\directory}} -f:{{path\to\file}}`

- Ignore the directory structure when uncompressing, and add them to a single directory:

`expand {{path\to\file.cab}} {{path\to\directory}} -i`

