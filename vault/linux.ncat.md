---
id: linux.ncat
title: Ncat
desc: ''
updated: 1656591837638
created: 1656591837638
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ncat

> Use the normal `cat` functionality over networks.
> More information: <https://manned.org/ncat>.

- Listen for input on the specified port and write it to the specified file:

`ncat -l {{port}} > {{path/to/file}}`

- Accept multiple connections and keep ncat open after they have been closed:

`ncat -lk {{port}}`

- Write output of specified file to the specified host on the specified port:

`ncat {{address}} {{port}} < {{path/to/file}}`

