---
id: common.vale
title: Vale
desc: ''
updated: 1686594011896
created: 1686594011896
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

`vale {{path/to/file}}`

- Check the style of a file with a specified configuration:

`vale --config='{{path/to/.vale.ini}}' {{path/to/file}}`

- Output the results in JSON format:

`vale --output=JSON {{path/to/file}}`

- Check style issues at the specific severity and higher:

`vale --minAlertLevel={{suggestion|warning|error}} {{path/to/file}}`

- Check the style from `stdin`, specifying markup format:

`cat {{file.md}} | vale --ext=.md`

- List the current configuration:

`vale ls-config`

