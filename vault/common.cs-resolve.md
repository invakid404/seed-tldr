---
id: common.cs-resolve
title: Cs Resolve
desc: ''
updated: 1673284741485
created: 1673284741485
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cs resolve

> Resolve lists the transitive dependencies of one or more other dependencies.
> More information: <https://get-coursier.io/docs/cli-resolve>.

- Resolve lists of transitive dependencies of two dependencies:

`cs resolve {{group_id1}}:{{artifact_id1}}:{{artifact_version1}} {{group_id2}}:{{artifact_id2}}:{{artifact_version2}}`

- Resolve lists of transitive dependencies of a package by the dependency tree:

`cs resolve --tree {{group_id}}:{{artifact_id}}:{{artifact_version}}`

- Resolve dependency tree in a reverse order (from a dependency to its dependencies):

`cs resolve --reverse-tree {{group_id}}:{{artifact_id}}:{{artifact_version}`

- Print all the libraries that depends on a specific library:

`cs resolve {{group_id}}:{{artifact_id}}:{{artifact_version}} --what-depends-on {{searched_group_id}}:{{searched_artifact_id}}`

- Print all the libraries that depends on a specific library version:

`cs resolve {{group_id}}:{{artifact_id}}:{{artifact_version}} --what-depends-on {{searched_group_id}}:{{searched_artifact_id}}{{searched_artifact_version}}`

- Print eventual conflicts between a set of packages:

`cs resolve --conflicts {{group_id1:artifact_id1:artifact_version1 group_id2:artifact_id2:artifact_version2 ...}}`

