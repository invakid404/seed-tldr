---
id: linux.jobs
title: Jobs
desc: ''
updated: 1687018788483
created: 1687018788483
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jobs

> Shell builtin for viewing information about processes spawned by the current shell.
> Options other than `-l` and `-p` are exclusive to `bash`.
> More information: <https://manned.org/jobs>.

- View jobs spawned by the current shell:

`jobs`

- List jobs and their process IDs:

`jobs -l`

- Display information about jobs with changed status:

`jobs -n`

- Display only process IDs:

`jobs -p`

- Display running processes:

`jobs -r`

- Display stopped processes:

`jobs -s`

