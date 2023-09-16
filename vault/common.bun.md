---
id: common.bun
title: Bun
desc: ''
updated: 1694902528557
created: 1694902528557
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bun

> JavaScript runtime and toolkit.
> Includes a bundler, a test runner, and a package manager.
> More information: <https://bun.sh>.

- Run a JavaScript file or a `package.json` script:

`bun run {{path/to/file|script_name}}`

- Run unit tests:

`bun test`

- Download and install all the packages listed as dependencies in `package.json`:

`bun install`

- Add a dependency to `package.json`:

`bun add {{module_name}}`

- Remove a dependency from `package.json`:

`bun remove {{module_name}}`

- Create a new Bun project in the current directory:

`bun init`

- Start a REPL (interactive shell):

`bun repl`

- Upgrade Bun to the latest version:

`bun upgrade`

