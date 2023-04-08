---
id: linux.mmdebstrap
title: Mmdebstrap
desc: ''
updated: 1680948954787
created: 1680948954787
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mmdebstrap

> Create a Debian chroot.
> Alternative to `debootstrap`.
> More information: <https://gitlab.mister-muffin.de/josch/mmdebstrap/>.

- Create a Debian Stable directory chroot:

`sudo mmdebstrap stable {{path/to/debian-root/}}`

- Create a Debian Bookworm tarball chroot using a mirror:

`mmdebstrap bookworm {{path/to/debian-bookworm.tar}} {{http://mirror.example.org/debian}}`

- Create a Debian Sid tarball chroot with additional packages:

`mmdebstrap sid {{path/to/debian-sid.tar}} --include={{pkg1,pkg2}}`

