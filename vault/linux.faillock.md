---
id: linux.faillock
title: Faillock
desc: ''
updated: 1656591837621
created: 1656591837621
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# faillock

> Display and modify authentication failure record files.
> More information: <https://manned.org/faillock>.

- List login failures of all users:

`sudo faillock`

- List login failures of the specified user:

`sudo faillock --user {{user}}`

- Reset the failure records of the specified user:

`sudo faillock --user {{user}} --reset`

