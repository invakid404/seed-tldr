---
id: common.clip-view
title: Clip View
desc: ''
updated: 1677674247029
created: 1677674247029
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# clip-view

> Command Line Interface Pages render.
> Render for a TlDr-like project with much a more extensive syntax and several render modes.
> More information: <https://github.com/command-line-interface-pages/v2-tooling/tree/main/clip-view>.

- Render specific local pages:

`clip-view {{path/to/page1.clip path/to/page2.clip ...}}`

- Render specific remote pages:

`clip-view {{page_name1 page_name2 ...}}`

- Render pages by a specific render:

`clip-view --render {{tldr|tldr-colorful|docopt|docopt-colorful}} {{page_name1 page_name2 ...}}`

- Render pages with a specific color theme:

`clip-view --theme {{path/to/local_theme.yaml|remote_theme_name}} {{page_name1 page_name2 ...}}`

- Clear a page or theme cache:

`clip-view --clear-{{page|theme}}-cache`

- Display help:

`clip-view --help`

- Display version:

`clip-view --version`

