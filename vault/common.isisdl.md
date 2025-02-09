---
id: common.isisdl
title: Isisdl
desc: ''
updated: 1656591837501
created: 1656591837501
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# isisdl

> A downloading utility for ISIS of TU-Berlin. Download all your files and videos from ISIS.
> More information: <https://github.com/Emily3403/isisdl>.

- Start the synchronization process:

`isisdl`

- Limit the download rate to 20 MiB/s and download with 5 threads:

`isisdl --download-rate {{20}} --max-num-threads {{5}}`

- Run the initialization configuration wizard:

`isisdl --init`

- Run the additional configuration wizard:

`isisdl --config`

- Initiate a full synchronization of the database and compute the checksum of every file:

`isisdl --sync`

- Start ffmpeg to compress downloaded videos:

`isisdl --compress`

