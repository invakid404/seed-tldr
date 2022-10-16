---
id: common.rss2email
title: Rss2email
desc: ''
updated: 1665899329955
created: 1665899329955
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rss2email

> Tool for delivering news from RSS feeds to an email program.
> More information: <https://github.com/rss2email/rss2email>.

- List all feeds:

`r2e list`

- Convert RSS entries to email:

`r2e run`

- Add a feed:

`r2e add {{feed_address}}`

- Add a feed with a specific email address:

`r2e add {{feed_address}} {{new_email@example.com}}`

- Delete a specific feed:

`r2e delete {{number_of_feed_in_list}}`

- Display help:

`r2e -h`
