---
id: common.ac
title: Ac
desc: ''
updated: 1665872670330
created: 1665872670330
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ac

> Print statistics on how long users have been connected.
> More information: <https://man.openbsd.org/ac>.

- Print how long the current user has been connected in hours:

`ac`

- Print how long users have been connected in hours:

`ac -p`

- Print how long a particular user has been connected in hours:

`ac -p {{username}}`

- Print how long a particular user has been connected in hours per day (with total):

`ac -dp {{username}}`

