---
id: linux.trace-cmd
title: Trace Cmd
desc: ''
updated: 1656591837656
created: 1656591837656
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trace-cmd

> Utility to interact with the Ftrace Linux kernel internal tracer.
> This utility only runs as root.
> More information: <https://manned.org/trace-cmd>.

- Display the status of tracing system:

`trace-cmd stat`

- List available tracers:

`trace-cmd list -t`

- Start tracing with a specific plugin:

`trace-cmd start -p {{timerlat|osnoise|hwlat|blk|mmiotrace|function_graph|wakeup_dl|wakeup_rt|wakeup|function|nop}}`

- View the trace output:

`trace-cmd show`

- Stop the tracing but retain the buffers:

`trace-cmd stop`

- Clear the trace buffers:

`trace-cmd clear`

- Clear the trace buffers and stop tracing:

`trace-cmd reset`

