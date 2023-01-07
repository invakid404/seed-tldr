---
id: common.git-cvsexportcommit
title: Git Cvsexportcommit
desc: ''
updated: 1673094645920
created: 1673094645920
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git cvsexportcommit

> Export a single `Git` commit to a CVS checkout.
> More information: <https://git-scm.com/docs/git-cvsexportcommit>.

- Merge a specific patch into CVS:

`git cvsexportcommit -v -c -w {{path/to/project_cvs_checkout}} {{commit_sha1}}`

