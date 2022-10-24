---
id: linux.treetime
title: Treetime
desc: ''
updated: 1666600896677
created: 1666600896677
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# treetime

> TreeTime provides routines for ancestral sequence reconstruction and inference of molecular-clock phylogenies.
> More information: <https://treetime.readthedocs.io/en/latest/tutorials.html>.

- Infer ancestral sequences maximizing the joint or marginal likelihood:

`treetime ancestral`

- Analyze patterns of recurrent mutations aka homoplasies:

`treetime homoplasy`

- Estimate molecular clock parameters and reroot the tree:

`treetime clock`

- Map discrete character such as host or country to the tree:

`treetime mugration`

