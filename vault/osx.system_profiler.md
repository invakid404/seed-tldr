---
id: osx.system_profiler
title: System_profiler
desc: ''
updated: 1691594336088
created: 1691594336088
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# system_profiler

> Report system hardware and software configuration.
> More information: <https://ss64.com/osx/system_profiler.html>.

- Display a report with specific details level (mini [no personal information], basic or full):

`system_profiler -detailLevel {{level}}`

- Display a full system profiler report which can be opened by `System Profiler.app`:

`system_profiler -xml > MyReport.spx`

- Display a hardware overview (Model, CPU, Memory, Serial, etc) and software data (System, Kernel, Name, Uptime, etc):

`system_profiler SPHardwareDataType SPSoftwareDataType`

- Print the system serial number:

`system_profiler SPHardwareDataType|grep "Serial Number (system)" | awk '{ print $4 }'`

