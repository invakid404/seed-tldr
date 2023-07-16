---
id: common.vhs
title: Vhs
desc: ''
updated: 1689531679750
created: 1689531679750
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vhs

> Generate terminal gifs from a tape file.
> More information: <https://github.com/charmbracelet/vhs>.

- Create a tape file (add commands to the tape file using an editor):

`vhs new {{path/to/file.tape}}`

- Record inputs to a tape file (once done, exit the shell to create the tape):

`vhs record > {{path/to/file.tape}}`

- Record inputs to a tape file using a specific shell:

`vhs record --shell {{shell}} > {{path/to/file.tape}}`

- Validate the syntax of a tape file:

`vhs validate {{path/to/file.tape}}`

- Create a gif from a tape file:

`vhs < {{path/to/file.tape}}`

- Publish a gif to <https://vhs.charm.sh> and get a shareable URL:

`vhs publish {{path/to/file.gif}}`

