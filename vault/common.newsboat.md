---
id: common.newsboat
title: Newsboat
desc: ''
updated: 1687904232872
created: 1687904232872
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# newsboat

> An RSS/Atom feed reader for text terminals.
> More information: <https://newsboat.org/>.

- First import feed URLs from an OPML file:

`newsboat -i {{my-feeds.xml}}`

- Alternatively, add feeds manually:

`echo {{http://example.com/path/to/feed}} >> "${HOME}/.newsboat/urls"`

- Start Newsboat and refresh all feeds on startup:

`newsboat -r`

- Execute a space-separated list of commands in non-interactive mode:

`newsboat -x {{reload print-unread ...}}`

- See keyboard shortcuts (the most relevant are visible in the status line):

`?`

