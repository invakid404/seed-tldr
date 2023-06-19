---
id: linux.dirbuster
title: Dirbuster
desc: ''
updated: 1687184159070
created: 1687184159070
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dirbuster

> Brute force directories and filenames on servers.
> More information: <https://www.kali.org/tools/dirbuster/>.

- Start in GUI mode:

`dirbuster -u {{http://example.com}}`

- Start in headless (no GUI) mode:

`dirbuster -H -u {{http://example.com}}`

- Set the file extension list:

`dirbuster -e {{txt,html}}`

- Enable verbose output:

`dirbuster -v`

- Set the report location:

`dirbuster -r {{path/to/report.txt}}`

