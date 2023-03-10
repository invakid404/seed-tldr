---
id: linux.stegsnow
title: Stegsnow
desc: ''
updated: 1678486627296
created: 1678486627296
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stegsnow

> Steganography tool for concealing and extracting messages in text files encoded as tabs and spaces.
> More information: <https://darkside.com.au/snow/manual.html>.

- Extract [m]essage from file:

`stegsnow {{path/to/file.txt}}`

- Extract [C]ompressed and [p]assword protected [m]essage from file:

`stegsnow -C -p {{password}} {{path/to/file.txt}}`

- Determine approximate [S]torage capacity with line [l]ength less than 72 for file:

`stegsnow -S -l 72 {{path/to/file.txt}}`

- Conceal [m]essage in text from file and save to result:

`stegsnow -m '{{message}}' {{path/to/file.txt}} {{path/to/result.txt}}`

- Conceal message [f]ile content [C]ompressed in text from file and save to result:

`stegsnow -C -f '{{path/to/message.txt}}' {{path/to/file.txt}} {{path/to/result.txt}}`

- Conceal [m]essage [C]ompressed and [p]assword protected in text from file and save to result:

`stegsnow -C -p {{password}} -m '{{message}}' {{path/to/file.txt}} {{path/to/result.txt}}`

