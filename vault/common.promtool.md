---
id: common.promtool
title: Promtool
desc: ''
updated: 1670142130991
created: 1670142130991
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# promtool

> Tooling for the Prometheus monitoring system.
> More information: <https://prometheus.io/docs/prometheus/latest/getting_started/>.

- Check if the config files are valid or not (if present report errors):

`promtool check config {{config_file.yml}}`

- Check if the rule files are valid or not (if present report errors):

`promtool check rules {{rules_file.yml}}`

- Pass Prometheus metrics over `stdin` to check them for consistency and correctness:

`curl --silent {{http://example.com:9090/metrics/}} | promtool check metrics`

- Unit tests for rules config:

`promtool test rules {{test_file.yml}}`

