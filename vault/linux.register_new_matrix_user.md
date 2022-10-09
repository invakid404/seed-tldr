---
id: linux.register_new_matrix_user
title: Register_new_matrix_user
desc: ''
updated: 1665319477581
created: 1665319477581
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# register_new_matrix_user

> Used to register new users with a given home server when registration has been disabled.
> More information: <https://manned.org/register_new_matrix_user>.

- Create a user interactively:

`register_new_matrix_user --config {{path/to/homeserver.yaml}}`

- Create an admin user interactively:

`register_new_matrix_user --config {{path/to/homeserver.yaml}} --admin`

- Create an admin user non-interactively (not recommended):

`register_new_matrix_user --config {{path/to/homeserver.yaml}} --user {{username}} --password {{password}} --admin`

