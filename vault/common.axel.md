---
id: common.axel
title: Axel
desc: ''
updated: 1670310991735
created: 1670310991735
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# axel

> Download accelerator.
> Supports HTTP, HTTPS, and FTP.
> More information: <https://github.com/axel-download-accelerator/axel>.

- Download a URL to a file:

`axel {{url}}`

- Download and specify filename:

`axel {{url}} -o {{path/to/file}}`

- Download with multiple connections:

`axel -n {{connections_num}} {{url}}`

- Search for mirrors:

`axel -S {{mirrors_num}} {{url}}`

- Limit download speed (bytes per second):

`axel -s {{speed}} {{url}}`

