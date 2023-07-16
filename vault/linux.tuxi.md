---
id: linux.tuxi
title: Tuxi
desc: ''
updated: 1689531679867
created: 1689531679867
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tuxi

> Scrape Google search results and SERPs and provide instant and concise answers.
> More information: <https://github.com/Bugswriter/tuxi>.

- Make a search using Google:

`tuxi {{search_terms}}`

- Display the search results in [r]aw format (no pretty output, no colors):

`tuxi -r {{search_terms}}`

- Display only search results (silences "Did you mean?", greetings and usage):

`tuxi -q {{search_terms}}`

- Display help:

`tuxi -h`

