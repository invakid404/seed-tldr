---
id: common.aria2c
title: Aria2c
desc: ''
updated: 1670008517035
created: 1670008517035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aria2c

> Fast download utility.
> Supports HTTP(S), FTP, SFTP, BitTorrent, and Metalink.
> More information: <https://aria2.github.io>.

- Download a specific URI to a file:

`aria2c "{{url}}"`

- Download a file from a URI with a specific output name:

`aria2c --out={{path/to/file}} "{{url}}"`

- Download multiple different files in parallel:

`aria2c --force-sequential {{false}} "{{url1 url2 ...}}"`

- Download from multiple sources with each URI pointing to the same file:

`aria2c "{{url1 url2 ...}}"`

- Download the URIs listed in a file with a specific number of parallel downloads:

`aria2c --input-file={{path/to/file}} --max-concurrent-downloads={{number_of_downloads}}`

- Download with multiple connections:

`aria2c --split={{number_of_connections}} "{{url}}"`

- FTP download with username and password:

`aria2c --ftp-user={{username}} --ftp-passwd={{password}} "{{url}}"`

- Limit download speed in bytes/s:

`aria2c --max-download-limit={{speed}} "{{url}}"`

