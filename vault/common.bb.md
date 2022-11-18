---
id: common.bb
title: Bb
desc: ''
updated: 1668736550447
created: 1668736550447
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bb

> Native Clojure interpreter for scripting.
> More information: <https://book.babashka.org/#usage>.

- [e]valuate an expression:

`bb -e "(+ 1 2 3)"`

- Evaluate a script [f]ile:

`bb -f {{path/to/script.clj}}`

- Bind input to a sequence of lines from stdin:

`printf "first\nsecond" | bb -i "(map clojure.string/capitalize *input*)"`

- Bind input to a sequence of EDN(Extensible Data Notation) values from stdin:

`echo "{:key 'val}" | bb -I "(:key (first *input*))"`

