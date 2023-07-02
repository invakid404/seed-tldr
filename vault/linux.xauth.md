---
id: linux.xauth
title: Xauth
desc: ''
updated: 1688304045063
created: 1688304045063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xauth

> Edit and display the authorization information used in connecting to the X server.
> More information: <https://manned.org/xauth>.

- Start interactive mode with a specific authority file (defaults to `~/.Xauthority`):

`xauth -f {{path/to/file}}`

- Display information about the authority file:

`xauth info`

- Display authorization entries for all the displays:

`xauth list`

- Add an authorization for a specific display:

`xauth add {{display_name}} {{protocol_name}} {{key}}`

- Remove the authorization for a specific display:

`xauth remove {{display_name}}`

- Print the authorization entry for the current display to `stdout`:

`xauth extract - $DISPLAY`

- Merge the authorization entries from a specific file into the authorization database:

`cat {{path/to/file}} | xauth merge -`

- Display help:

`xauth --help`

