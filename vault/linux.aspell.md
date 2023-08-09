---
id: linux.aspell
title: Aspell
desc: ''
updated: 1691562059127
created: 1691562059127
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aspell

> Interactive spell checker.
> More information: <http://aspell.net/>.

- Spell check a single file:

`aspell check {{path/to/file}}`

- List misspelled words from `stdin`:

`cat {{path/to/file}} | aspell list`

- Show available dictionary languages:

`aspell dicts`

- Run `aspell` with a different language (takes two-letter ISO 639 language code):

`aspell --lang={{cs}}`

- List misspelled words from `stdin` and ignore words from personal word list:

`cat {{path/to/file}} | aspell --personal={{personal-word-list.pws}} list`

