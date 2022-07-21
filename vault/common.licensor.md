---
id: common.licensor
title: Licensor
desc: ''
updated: 1658334712145
created: 1658334712145
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# licensor

> Write licenses to stdout.
> More information: <https://github.com/raftario/licensor>.

- Write the MIT license to a file named `LICENSE`:

`licensor {{MIT}} > {{LICENSE}}`

- Write the MIT license with a [p]laceholder copyright notice to a file named `LICENSE`:

`licensor -p {{MIT}} > {{LICENSE}}`

- Specify a copyright holder named Bobby Tables:

`licensor {{MIT}} {{"Bobby Tables"}} > {{LICENSE}}`

- Specify licence exceptions with a WITH expression:

`licensor "{{Apache-2.0 WITH LLVM-exception}}" > {{LICENSE}}`

- List all available licenses:

`licensor --licenses`

- List all available exceptions:

`licensor --exceptions`
