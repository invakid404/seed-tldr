---
id: common.infection
title: Infection
desc: ''
updated: 1656591837499
created: 1656591837499
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# infection

> A mutation testing framework for PHP.
> More information: <https://infection.github.io>.

- Analyze code using the configuration file (or create one if it does not exist):

`infection`

- Use a specific number of threads:

`infection --threads {{number_of_threads}}`

- Specify a minimum Mutation Score Indicator (MSI):

`infection --min-msi {{percentage}}`

- Specify a minimum covered code MSI:

`infection --min-covered-msi {{percentage}}`

- Use a specific test framework (defaults to PHPUnit):

`infection --test-framework {{phpunit|phpspec}}`

- Only mutate lines of code that are covered by tests:

`infection --only-covered`

- Display the mutation code that has been applied:

`infection --show-mutations`

- Specify the log verbosity:

`infection --log-verbosity {{default|all|none}}`

