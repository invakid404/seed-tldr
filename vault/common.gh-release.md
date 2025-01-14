---
id: common.gh-release
title: Gh Release
desc: ''
updated: 1689531679578
created: 1689531679578
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh release

> Manage GitHub releases.
> More information: <https://cli.github.com/manual/gh_release>.

- List releases in a GitHub repository, limited to 30 items:

`gh release list`

- Display information about a specific release:

`gh release view {{tag}}`

- Create a new release:

`gh release create {{tag}}`

- Delete a specific release:

`gh release delete {{tag}}`

- Download assets from a specific release:

`gh release download {{tag}}`

- Upload assets to a specific release:

`gh release upload {{tag}} {{path/to/file1 path/to/file2 ...}}`

