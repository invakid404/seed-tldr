---
id: common.tldr-generate
title: Tldr Generate
desc: ''
updated: 1665499012907
created: 1665499012907
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr generate

> Remake configuration files from information stored locally.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Remake the configuration file storing into a specific location:

`tlmgr generate --dest {{output_file}}`

- Remake the configuration file using a local configuration file:

`tlmgr generate --localcfg {{local_configuration_file}}`

- Run necessary programs after rebuilding configuration files:

`tlmgr generate --rebuild-sys`

