---
id: common.kcadm-sh
title: Kcadm Sh
desc: ''
updated: 1666779932389
created: 1666779932389
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kcadm.sh

> Perform administration tasks from the command-line interface (CLI).
> More information: <https://www.keycloak.org/docs/latest/server_admin/#admin-cli>.

- Start an authenticated session:

`kcadm.sh config credentials --server {{host}} --realm {{realm_name}} --user {{username}} --password {{password}}`

- Create a user:

`kcadm.sh create users -s username={{username}} -r {{realm_name}}`

- List all realms:

`kcadm.sh get realms`

- Update a realm with JSON config:

`kcadm.sh update realms/{{realm_name}} -f {{path/to/file.json}}`

