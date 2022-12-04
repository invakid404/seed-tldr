---
id: common.alex
title: Alex
desc: ''
updated: 1670142130863
created: 1670142130863
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# alex

> A tool that catches insensitive, inconsiderate writing.
> It helps you find gender favouring, polarising, race related, religion inconsiderate, or other unequal phrasing in text.
> More information: <https://github.com/get-alex/alex>.

- Analyze text from `stdin`:

`echo {{His network looks good}} | alex --stdin`

- Analyze all files in the current directory:

`alex`

- Analyze a specific file:

`alex {{textfile.md}}`

- Analyze all Markdown files except `example.md`:

`alex *.md !{{example.md}}`

