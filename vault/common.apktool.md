---
id: common.apktool
title: Apktool
desc: ''
updated: 1681453285392
created: 1681453285392
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apktool

> Reverse engineer APK files.
> More information: <https://ibotpeaches.github.io/Apktool/>.

- Decode an APK file:

`apktool d {{path/to/file.apk}}`

- Build an APK file from a directory:

`apktool b {{path/to/directory}}`

- Install and store a framework:

`apktool if {{path/to/framework.apk}}`

