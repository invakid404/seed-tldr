---
id: sunos.svccfg
title: Svccfg
desc: ''
updated: 1676877466515
created: 1676877466515
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# svccfg

> Import, export, and modify service configurations.
> More information: <https://www.unix.com/man-page/linux/1m/svccfg>.

- Validate configuration file:

`svccfg validate {{path/to/smf_file.xml}}`

- Export service configurations to file:

`svccfg export {{servicename}} > {{path/to/smf_file.xml}}`

- Import/update service configurations from file:

`svccfg import {{path/to/smf_file.xml}}`

