---
id: common.composer-require-checker
title: Composer Require Checker
desc: ''
updated: 1656591837436
created: 1656591837436
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# composer-require-checker

> A CLI tool to analyze Composer dependencies for soft dependencies.
> More information: <https://github.com/maglnet/ComposerRequireChecker>.

- Analyze a Composer JSON file:

`composer-require-checker check {{path/to/composer.json}}`

- Analyze a Composer JSON file with a specific configuration:

`composer-require-checker check --config-file {{path/to/config.json}} {{path/to/composer.json}}`

