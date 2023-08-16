---
id: common.jf
title: Jf
desc: ''
updated: 1692206038606
created: 1692206038606
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jf

> Interact with JFrog products like Artifactory, Xray, Distribution, Pipelines and Mission Control.
> More information: <https://jfrog.com/help/r/jfrog-cli/usage>.

- Add a new configuration:

`jf config add`

- Show the current configuration:

`jf config show`

- Search for artifacts within the given repository and directory:

`jf rt search --recursive {{repostiory_name}}/{{path}}/`

