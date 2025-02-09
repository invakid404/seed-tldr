---
id: common.surfraw
title: Surfraw
desc: ''
updated: 1689531679731
created: 1689531679731
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# surfraw

> Query a variety of web search engines.
> Consists of a collection of elvi, each of which knows how to search a specific website.
> More information: <http://surfraw.org>.

- Display the list of supported website search scripts (elvi):

`surfraw -elvi`

- Open the elvi's results page for a specific search in the browser:

`surfraw {{elvi}} "{{search_terms}}"`

- Display an elvi description and its specific options:

`surfraw {{elvi}} -local-help`

- Search using an elvi with specific options and open the results page in the browser:

`surfraw {{elvi}} {{elvi_options}} "{{search_terms}}"`

- Display the URL to the elvi's results page for a specific search:

`surfraw -print {{elvi}} "{{search_terms}}"`

- Search using the alias:

`sr {{elvi}} "{{search_terms}}"`

