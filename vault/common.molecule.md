---
id: common.molecule
title: Molecule
desc: ''
updated: 1684257255204
created: 1684257255204
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# molecule

> Molecule helps testing Ansible roles.
> More information: <https://molecule.readthedocs.io>.

- Create a new Ansible role:

`molecule init role --role-name {{role_name}}`

- Run tests:

`molecule test`

- Start the instance:

`molecule create`

- Configure the instance:

`molecule converge`

- List scenarios of the instance:

`molecule matrix converge`

- Log in into the instance:

`molecule login`

