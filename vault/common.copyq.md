---
id: common.copyq
title: Copyq
desc: ''
updated: 1681374078799
created: 1681374078799
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# copyq

> Clipboard manager with advanced features.
> More information: <https://copyq.readthedocs.io/en/latest/command-line.html>.

- Launch CopyQ to store clipboard history:

`copyq`

- Show current clipboard content:

`copyq clipboard`

- Insert raw text into the clipboard history:

`copyq add -- {{text1}} {{text2}} {{text3}}`

- Insert text containing escape sequences ('\\n', '\\t') into the clipboard history:

`copyq add {{firstline\nsecondline}}`

- Print the content of the first 3 items in the clipboard history:

`copyq read 0 1 2`

- Copy a file's contents into the clipboard:

`copyq copy < {{file.txt}}`

- Copy a JPEG image into the clipboard:

`copyq copy image/jpeg < {{image.jpg}}`

