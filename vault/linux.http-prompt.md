---
id: linux.http-prompt
title: HTTP Prompt
desc: ''
updated: 1694355155129
created: 1694355155129
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# http-prompt

> An interactive command-line HTTP client featuring autocomplete and syntax highlighting.
> More information: <https://github.com/httpie/http-prompt>.

- Launch a session targeting the default URL of <http://localhost:8000> or the previous session:

`http-prompt`

- Launch a session with a given URL:

`http-prompt {{http://example.com}}`

- Launch a session with some initial options:

`http-prompt {{localhost:8000/api}} --auth {{username:password}}`

