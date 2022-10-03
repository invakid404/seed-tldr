---
id: linux.getcap
title: Getcap
desc: ''
updated: 1664801544663
created: 1664801544663
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# getcap

> Command to display the name and capabilities of each specified file.
> More information: <https://manned.org/getcap>.

- Get capabilities for the given files:

`getcap {{path/to/file1 path/to/file2 ...}}`

- Get capabilities for all the files recursively under the given directories:

`getcap -r {{path/to/directory1 path/to/directory2 ...}}`

- Displays all searched entries even if no capabilities are set:

`getcap -v {{path/to/file1 path/to/file2 ...}}`

