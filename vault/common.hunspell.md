---
id: common.hunspell
title: Hunspell
desc: ''
updated: 1666678868388
created: 1666678868388
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hunspell

> Check spelling.
> More information: <https://github.com/hunspell/hunspell>.

- Check the spelling of a file:

`hunspell {{path/to/file}}`

- Check the spelling of a file with the en_US dictionary:

`hunspell -d {{en_US}} {{path/to/file}}`

- List misspelled words in a file:

`hunspell -l {{path/to/file}}`

