---
id: common.betty
title: Betty
desc: ''
updated: 1681186805983
created: 1681186805983
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# betty

> Use natural language to execute commands.
> More information: <https://github.com/pickhardt/betty>.

- Ask Betty something:

`betty {{what time is it}}`

- Download a file:

`betty download {{https://example.com/file.ext}} to {{path/to/output_file.ext}}`

- Compress a file or directory to one of the support archive formats:

`betty {{zip}} {{path/to/file_or_directory}}`

- Extract an archive into the current directory:

`betty {{unzip}} {{archive.tar.gz}}`

- Extract an archive into a specific directory:

`betty unarchive {{archive.tar.gz}} to {{path/to/directory}}`

- Play Spotify:

`betty play {{Spotify}}`

- Drive Betty to madness:

`betty go crazy`

- Display version:

`betty version`

