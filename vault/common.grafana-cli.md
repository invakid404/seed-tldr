---
id: common.grafana-cli
title: Grafana CLI
desc: ''
updated: 1659691256476
created: 1659691256476
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grafana-cli

> A small executable that is bundled with Grafana serve.
> More information: <https://grafana.com/docs/grafana/latest/cli/>.

- Install, update, or remove specific plugins:

`grafana-cli plugins {{install|update|remove}} {{plugin_id1 plugin_id2 ...}}`

- List all installed plugins:

`grafana-cli plugins ls`

