---
id: common.glab-repo
title: Glab Repo
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
# glab repo

> Work with GitLab repositories.
> More information: <https://glab.readthedocs.io/en/latest/repo/index.html#synopsis>.

- Create a new repository (if the repository name is not set, the default name will be the name of the current directory):

`glab repo create {{name}}`

- Clone a repository:

`glab repo clone {{owner}}/{{repository}}`

- Fork and clone a repository:

`glab repo fork {{owner}}/{{repository}} --clone`

- View a repository in the default web browser:

`glab repo view {{owner}}/{{repository}} --web`

- Search some repositories in the GitLab instance:

`glab repo search -s {{search_string}}`

