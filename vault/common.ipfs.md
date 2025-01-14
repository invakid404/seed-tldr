---
id: common.ipfs
title: Ipfs
desc: ''
updated: 1670310991811
created: 1670310991811
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipfs

> Inter Planetary File System.
> A peer-to-peer hypermedia protocol. Aims to make the web more open.
> More information: <https://ipfs.io>.

- Add a file from local to the filesystem, pin it and print the relative hash:

`ipfs add {{path/to/file}}`

- Add a directory and its files recursively from local to the filesystem and print the relative hash:

`ipfs add -r {{path/to/directory}}`

- Save a remote file and give it a name but not pin it:

`ipfs get {{hash}} -o {{path/to/file}}`

- Pin a remote file locally:

`ipfs pin add {{hash}}`

- Display pinned files:

`ipfs pin ls`

- Unpin a file from the local storage:

`ipfs pin rm {{hash}}`

- Remove unpinned files from local storage:

`ipfs repo gc`

