---
id: linux.systemd-path
title: Systemd Path
desc: ''
updated: 1692724448976
created: 1692724448976
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-path

> List and query system and user paths.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-path.html>.

- Display a list of known paths and their current values:

`systemd-path`

- Query the specified path and display its value:

`systemd-path "{{path_name}}"`

- Suffix printed paths with `suffix_string`:

`systemd-path --suffix {{suffix_string}}`

- Print a short version string and then exit:

`systemd-path --version`

