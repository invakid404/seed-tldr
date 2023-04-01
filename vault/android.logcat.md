---
id: android.logcat
title: Logcat
desc: ''
updated: 1680390924116
created: 1680390924116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# logcat

> Dump a log of system messages, including stack traces when an error occurred, and information messages logged by applications.
> More information: <https://developer.android.com/studio/command-line/logcat>.

- Display system logs:

`logcat`

- Write system logs to a file:

`logcat -f {{path/to/file}}`

- Display lines that match a regular expression:

`logcat --regex {{regular_expression}}`

- Display logs for a specific PID:

`logcat --pid={{pid}}`

- Display logs for the process of a specific package:

`logcat --pid=$(pidof -s {{package}})`

