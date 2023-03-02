---
id: common.argocd
title: Argocd
desc: ''
updated: 1677774416106
created: 1677774416106
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# argocd

> Command-line interface to control a Argo CD server.
> Some subcommands such as `argocd app` have their own usage documentation.
> More information: <https://argo-cd.readthedocs.io/en/stable/user-guide/commands/argocd/>.

- Login to Argo CD server:

`argocd login --insecure --username {{user}} --password {{password}} {{argocd_server:port}}`

- List applications:

`argocd app list`

