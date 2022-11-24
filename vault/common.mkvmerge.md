---
id: common.mkvmerge
title: Mkvmerge
desc: ''
updated: 1669254268024
created: 1669254268024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mkvmerge

> Merge and extract multimedia streams.
> More information: <https://mkvtoolnix.download/doc/mkvmerge.html>.

- Display information about a Matroska file:

`mkvmerge --identify {{path/to/file.mkv}}`

- Extract the audio from track 1 of a specific file:

`mkvextract tracks {{path/to/file.mkv}} {{1}}:{{path/to/output.webm}}`

- Extract the subtitle from track 3 of a specific file:

`mkvextract tracks {{path/to/file.mkv}} {{3}}:{{path/to/subs.srt}}`

- Add a subtitle track to a file:

`mkvmerge --output {{path/to/output.mkv}} {{path/to/file.mkv}} {{path/to/subs.srt}}`

