---
id: common.cs-complete-dep
title: Cs Complete Dep
desc: ''
updated: 1689531679532
created: 1689531679532
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cs complete dep

> Search for libraries without doing it directly on the web.
> More information: <https://get-coursier.io/docs/cli-complete>.

- Print which artifacts are published under a specific Maven group identifier:

`cs complete-dep {{group_id}}`

- List published library versions under a specific Maven group identifier and an artifact one:

`cs complete-dep {{group_id}}:{{artifact_id}}`

- Print which artifacts are pubblished under a given Maven groupId searching in the ivy2local:

`cs complete-dep {{group_id}} --repository ivy2local`

- List published artifacts under a Maven group identifier searching in a specific repository and credentials:

`cs complete-dep {{group_id}}:{{artifact_id}} --repository {{repository_url}} --credentials {{user}}:{{password}}`

