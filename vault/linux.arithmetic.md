---
id: linux.arithmetic
title: Arithmetic
desc: ''
updated: 1684034192313
created: 1684034192313
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arithmetic

> Quiz on simple arithmetic problems.
> More information: <https://manpages.debian.org/latest/bsdgames/arithmetic.6.en.html>.

- Start an arithmetic quiz:

`arithmetic`

- Specify one or more arithmetic [o]peration symbols to get problems on them:

`arithmetic -o {{+|-|x|/}}`

- Specify a range. Addition and multiplication problems would feature numbers between 0 and range, inclusive. Subtraction and division problems would have required result and number to be operated on, between 0 and range:

`arithmetic -r {{7}}`

