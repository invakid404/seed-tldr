---
id: common.glab-mr-create
title: Glab Mr Create
desc: ''
updated: 1689531679601
created: 1689531679601
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glab mr create

> Manage GitLab merge requests.
> More information: <https://glab.readthedocs.io/en/latest/mr/create.html>.

- Interactively create a merge request:

`glab mr create`

- Create a merge request, determining the title and description from the commit messages of the current branch:

`glab mr create --fill`

- Create a draft merge request:

`glab mr create --draft`

- Create a merge request specifying the target branch, title, and description:

`glab mr create --target-branch {{target_branch}} --title "{{title}}" --description "{{description}}"`

- Start opening a merge request in the default web browser:

`glab mr create --web`

