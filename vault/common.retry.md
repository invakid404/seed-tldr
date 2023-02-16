---
id: common.retry
title: Retry
desc: ''
updated: 1676539127311
created: 1676539127311
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# retry

> Repeat command until it succeeds or a criterion is met.
> More information: <https://github.com/minfrin/retry>.

- Retry a command until it succeeds:

`retry {{command}}`

- Retry a command every n seconds until it succeeds:

`retry --delay={{n}} {{command}}`

- Give up after n attempts:

`retry --times={{n}} {{command}}`

