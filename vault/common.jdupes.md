---
id: common.jdupes
title: Jdupes
desc: ''
updated: 1670145406998
created: 1670145406998
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jdupes

> A powerful duplicate file finder and an enhanced fork of fdupes.
> More information: <https://github.com/jbruchon/jdupes>.

- Search a single directory:

`jdupes {{path/to/directory}}`

- Search multiple directories:

`jdupes {{directory1}} {{directory2}}`

- Search all directories recursively:

`jdupes --recurse {{path/to/directory}}`

- Search directory recursively and let user choose files to preserve:

`jdupes --delete --recurse {{path/to/directory}}`

- Search multiple directories and follow subdirectores under directory2, not directory1:

`jdupes {{directory1}} --recurse: {{directory2}}`

- Search multiple directories and keep the directory order in result:

`jdupes -O {{directory1}} {{directory2}} {{directory3}}`

