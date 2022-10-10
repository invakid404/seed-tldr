---
id: common.vale
title: Vale
desc: ''
updated: 1665415810289
created: 1665415810289
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vale

> Extensible style checker that supports multiple markup formats, such as Markdown and AsciiDoc.
> More information: <https://vale.sh>.

- Check the style of a file:

`vale {{file}}`

- Check the style of a file with a specified configuration:

`vale --config='{{path/to/.vale.ini}}' {{file}}`

- Output the results in JSON format:

`vale --output=JSON {{file}}`

- Check style issues at the specific severity and higher:

`vale --minAlertLeve={{suggestion|warning|error}} {{file}}`

- Check the style from stdin, specifying markup format:

`cat {{file.md}} | vale --ext=.md`

- List the current configuration:

`vale ls-config`

