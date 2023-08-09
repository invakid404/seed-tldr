---
id: linux.vkpurge
title: Vkpurge
desc: ''
updated: 1691590575026
created: 1691590575026
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vkpurge

> List or remove old kernel versions left behind by `xbps`.
> The `version` arguments support shell globs.
> More information: <https://man.voidlinux.org/vkpurge.8>.

- List all removable kernel versions (or those matching `version` if the argument is specified):

`vkpurge list {{version}}`

- Remove all unused kernels:

`vkpurge rm all`

- Remove kernel versions matching `version`:

`vkpurge rm {{version}}`

