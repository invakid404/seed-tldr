---
id: common.xml-unescape
title: Xml Unescape
desc: ''
updated: 1670142131035
created: 1670142131035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xml unescape

> Unescape special XML characters, e.g. `&lt;a1&gt;` → `<a1>`.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Unescape special XML characters from a string:

`xml unescape "{{&lt;a1&gt;}}"`

- Unescape special XML characters from `stdin`:

`echo  "{{&lt;a1&gt;}}" | xml unescape`

- Display help for the `unescape` subcommand:

`xml escape --help`

