---
id: linux.larasail
title: Larasail
desc: ''
updated: 1689531679815
created: 1689531679815
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# larasail

> Manage Laravel on Digital Ocean servers.
> More information: <https://github.com/thedevdojo/larasail>.

- Set up the server with Laravel dependencies using the default PHP version:

`larasail setup`

- Set up the server with Laravel dependencies using a specific PHP version:

`larasail setup {{php71}}`

- Add a new Laravel site:

`larasail host {{domain}} {{path/to/site_directory}}`

- Retrieve the Larasail user password:

`larasail pass`

- Retrieve the Larasail MySQL password:

`larasail mysqlpass`

