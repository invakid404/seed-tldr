---
id: common.iconv
title: Iconv
desc: ''
updated: 1670142130945
created: 1670142130945
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iconv

> Converts text from one encoding to another.
> More information: <https://manned.org/iconv>.

- Convert file to a specific encoding, and print to `stdout`:

`iconv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- Convert file to the current locale's encoding, and output to a file:

`iconv -f {{from_encoding}} {{input_file}} > {{output_file}}`

- List supported encodings:

`iconv -l`

