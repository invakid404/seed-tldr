---
id: common.cs-install
title: Cs Install
desc: ''
updated: 1686759714005
created: 1686759714005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cs install

> Install an application in the installation directory onfigured when installing `cs` (to enable the binary to be loaded add to your `.bash_profile` the `$ eval "$(cs install --env)"` command).
> More information: <https://get-coursier.io/docs/cli-install>.

- Install a specific application:

`cs install {{application_name}}`

- Install a specific version of an application:

`cs install {{application_name}}:{{application_version}}`

- Search an application by a specific name:

`cs search {{application_partial_name}}`

- Update a specific application if available:

`cs update {{application_name}}`

- Update all the installed applications:

`cs update`

- Uninstall a specific application:

`cs uninstall {{application_name}}`

- List all installed applications:

`cs list`

- Pass specific java options to an installed application:

`{{application_name}} {{-Jjava_option_name1=value1 -Jjava_option_name2=value2 ...}}`

