---
id: common.jmeter
title: Jmeter
desc: ''
updated: 1661358604497
created: 1661358604497
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jmeter

> Open source java application designed for load testing functional behavior and measure performance.
> More information: <https://jmeter.apache.org>.

- Run a specific test plan in nongui mode:

`jmeter --nongui --testfile {{path/to/file}}.jmx`

- Run a test plan in nongui mode using a specific log file:

`jmeter --nogui --testfile {{path/to/file}}.jmx --logfile {{path/to/logfile}}.jtl`

- Run a test plan in nongui mode using a specific proxy:

`jmeter --nongui --testfile {{path/to/file}}.jmx --proxyHost {{127.0.0.1}} --proxyPort {{8888}}`

- Run a test plan in nongui mode using a specific JMeter property:

`jmeter --jmeterproperty {{key}}='{{value}}' --nongui --testfile {{path/to/file}}.jmx`

