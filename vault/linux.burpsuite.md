---
id: linux.burpsuite
title: Burpsuite
desc: ''
updated: 1666370345856
created: 1666370345856
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# burpsuite

> A GUI based application mainly used in web application penetration testing.
> More information: <https://portswigger.net/burp/documentation/desktop/getting-started/launch-from-command-line>.

- Start Burp Suite:

`burpsuite`

- Start Burp Suite using the default configuration:

`burpsuite --use-defaults`

- Open a specific project file:

`burpsuite --project-file={{path/to/file}}`

- Load a specific configuration file:

`burpsuite --config-file={{path/to/file}}`

- Start without extensions:

`burpsuite --disable-extensions`

