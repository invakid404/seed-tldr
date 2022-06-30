---
id: linux.cloud-init
title: Cloud Init
desc: ''
updated: 1656591837610
created: 1656591837610
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cloud-init

> Command line tool for managing cloud instance initialization.
> More information: <https://cloudinit.readthedocs.io>.

- Display the status of the most recent cloud-init run:

`cloud-init status`

- Wait for cloud-init to finish running and then report status:

`cloud-init status --wait`

- List available top-level metadata keys to query:

`cloud-init query --list-keys`

- Query cached instance metadata for data:

`cloud-init query {{dot_delimited_variable_path}}`

- Clean logs and artifacts to allow cloud-init to rerun:

`cloud-init clean`

