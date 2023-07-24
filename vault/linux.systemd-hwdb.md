---
id: linux.systemd-hwdb
title: Systemd Hwdb
desc: ''
updated: 1690225988922
created: 1690225988922
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-hwdb

> Hardware database management tool.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-hwdb.html>.

- Update the binary hardware database in `/etc/udev`:

`systemd-hwdb update`

- Query the hardware database and print the result for a specific modalias:

`systemd-hwdb query {{modalias}}`

- Update the binary hardware database, returning a non-zero exit value on any parsing error:

`systemd-hwdb --strict update`

- Update the binary hardware database in `/usr/lib/udev`:

`systemd-hwdb --usr update`

- Update the binary hardware database in the specified root path:

`systemd-hwdb --root={{path/to/root}} update`

