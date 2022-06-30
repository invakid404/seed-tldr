---
id: linux.sa
title: Sa
desc: ''
updated: 1656591837651
created: 1656591837651
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sa

> Summarizes accounting information. Part of the acct package.
> Shows commands called by users, including basic info on CPU time spent processing and I/O rates.
> More information: <https://manned.org/man/sa.8>.

- Display executable invocations per user (username not displayed):

`sudo sa`

- Display executable invocations per user, showing responsible usernames:

`sudo sa --print-users`

- List resources used recently per user:

`sudo sa --user-summary`

