---
id: common.latexdiff
title: Latexdiff
desc: ''
updated: 1664130573314
created: 1664130573314
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# latexdiff

> Determine differences between two LaTeX files.
> More information: <https://ctan.org/pkg/latexdiff>.

- Determine changes between different versions of a LaTeX file (the resulting LaTeX file can be compiled to show differences underlined):

`latexdiff {{old.tex}} {{new.tex}} > {{diff.tex}}`

- Determine changes between different versions of a LaTeX file by highlighting differences in boldface:

`latexdiff --type=BOLD {{old.tex}} {{new.tex}} > {{diff.tex}}`

- Determine changes between different versions of a LaTeX file, and display minor changes in equations with both added and deleted graphics:

`latexdiff --math-markup=fine --graphics-markup=both {{old.tex}} {{new.tex}} > {{diff.tex}}`

