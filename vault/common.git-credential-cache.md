---
id: common.git-credential-cache
title: Git Credential Cache
desc: ''
updated: 1683184574410
created: 1683184574410
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git credential-cache

> Git helper to temporarily store passwords in memory.
> More information: <https://git-scm.com/docs/git-credential-cache>.

- Store Git credentials for a specific amount of time:

`git config credential.helper 'cache --timeout={{time_in_seconds}}'`

