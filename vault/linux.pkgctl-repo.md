---
id: linux.pkgctl-repo
title: Pkgctl Repo
desc: ''
updated: 1692008215319
created: 1692008215319
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pkgctl repo

> Manage Git packaging repositories and their configuration for Arch Linux.
> See also: `pkgctl`.
> More information: <https://man.archlinux.org/man/pkgctl-repo.1>.

- Clone a package repository (requires setting an SSH key in your Arch Linux GitLab account):

`pkgctl repo clone {{pkgname}}`

- Clone a package repository over HTTPS&#x3A;

`pkgctl repo clone --protocol=https {{pkgname}}`

- Create a new GitLab package repository and clone it after creation (requires valid GitLab API authentication):

`pkgctl repo create {{pkgbase}}`

- Switch a package repository to a specified version:

`pkgctl repo switch {{version}} {{pkgbase}}`

- Open a package repository's website:

`pkgctl repo web {{pkgbase}}`

