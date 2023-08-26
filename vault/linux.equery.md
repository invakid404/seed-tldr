---
id: linux.equery
title: Equery
desc: ''
updated: 1693073888628
created: 1693073888628
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# equery

> View information about Portage packages.
> More information: <https://wiki.gentoo.org/wiki/Equery>.

- List all installed packages:

`equery list '*'`

- Search for installed packages in the Portage tree and in overlays:

`equery list -po {{package1 package2 ...}}`

- List all packages that depend on a given package:

`equery depends {{package}}`

- List all packages that a given package depends on:

`equery depgraph {{package}}`

- List all files installed by a package:

`equery files --tree {{package}}`

