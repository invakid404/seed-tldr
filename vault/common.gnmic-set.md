---
id: common.gnmic-set
title: Gnmic Set
desc: ''
updated: 1662059876137
created: 1662059876137
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnmic set

> Modify gnmi network device configuration.
> More information: <https://gnmic.kmrd.dev/cmd/set>.

- Update the value of a path:

`gnmic --address {{ip:port}} set --update-path {{path}} --update-value {{value}}`

- Update the value of a path to match the contents of a json file:

`gnmic -a {{ip:port}} set --update-path {{path}} --update-file {{filepath}}`

- Replace the value of a path to match the contents of a json file:

`gnmic -a {{ip:port}} set --replace-path {{path}} --replace-file {{filepath}}`

- Delete the node at a given path:

`gnmic -a {{ip:port}} set --delete {{path}}`

