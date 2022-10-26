---
id: common.pyats-shell
title: Pyats Shell
desc: ''
updated: 1666794439943
created: 1666794439943
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pyats shell

> Start a pre-loaded pyATS interactive Python Shell to save time in prototyping.
> More information: <https://pubhub.devnetcloud.com/media/genie-docs/docs/cli/genie_shell.html>.

- Open pyATS shell with a defined Testbed file:

`pyats shell --testbed-file {{path/to/testbed.yaml}}`

- Open pyATS shell with a defined Pickle file:

`pyats shell --pickle-file {{path/to/pickle.file}}`

- Open pyATS with IPython disabled:

`pyats shell --no-ipython`

