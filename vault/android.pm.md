---
id: android.pm
title: Pm
desc: ''
updated: 1672766194217
created: 1672766194217
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pm

> Display information about apps on an Android device.
> More information: <https://developer.android.com/studio/command-line/adb#pm>.

- List all installed apps:

`pm list packages`

- List all installed system apps:

`pm list packages -s`

- List all installed 3rd-Party apps:

`pm list packages -3`

- List apps matching specific keywords:

`pm list packages {{keyword1 keyword2 ...}}`

- Display a path of the APK of a specific app:

`pm path {{app}}`

