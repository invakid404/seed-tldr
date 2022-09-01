---
id: common.adb-logcat
title: Adb Logcat
desc: ''
updated: 1662067187840
created: 1662067187840
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# adb-logcat

> Dump a log of system messages.
> More information: <https://developer.android.com/studio/command-line/logcat>.

- Display system logs:

`adb logcat`

- Display lines that match a regular expression:

`adb logcat -e {{regular_expression}}`

- Display logs for a tag in a specific mode ([V]erbose, [D]ebug, [I]nfo, [W]arning, [E]rror, [F]atal, [S]ilent), filtering other tags:

`adb logcat {{tag}}:{{mode}} *:S`

- Display logs for React Native applications in [V]erbose mode [S]ilencing other tags:

`adb logcat ReactNative:V ReactNativeJS:V *:S`

- Display logs for all tags with priority level [W]arning and higher:

`adb logcat *:W`

- Color the log (usually use with filters):

`adb logcat -v color`

