---
id: common.asciinema
title: Asciinema
desc: ''
updated: 1670325347059
created: 1670325347059
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asciinema

> Record and replay terminal sessions, and optionally share them on asciinema.org.
> More information: <https://asciinema.org/docs/usage>.

- Associate the local install of `asciinema` with an asciinema.org account:

`asciinema auth`

- Make a new recording (once finished, user will be prompted to upload it or save it locally):

`asciinema rec`

- Make a new recording and save it to a local file:

`asciinema rec {{path/to/file}}.cast`

- Replay a terminal recording from a local file:

`asciinema play {{path/to/file}}.cast`

- Replay a terminal recording hosted on asciinema.org:

`asciinema play https://asciinema.org/a/{{cast_id}}`

- Make a new recording, limiting any idle time to at most 2.5 seconds:

`asciinema rec -i {{2.5}}`

- Print the full output of a locally saved recording:

`asciinema cat {{path/to/file}}.cast`

- Upload a locally saved terminal session to asciinema.org:

`asciinema upload {{path/to/file}}.cast`

