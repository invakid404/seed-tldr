---
id: common.hledger
title: Hledger
desc: ''
updated: 1665415810170
created: 1665415810170
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hledger

> A plain text accounting software for the command-line.
> More information: <https://hledger.org>.

- Add transactions to your journal interactively:

`hledger add`

- Show the account hierarchy, using a specific journal file:

`hledger --file {{path/to/file.journal}} accounts --tree`

- Show a monthly income statement:

`hledger incomestatement --monthly --depth 2`

- Print the amount of cash spent on food:

`hledger print assets:cash | hledger -f- -I balance expenses:food --depth 2`

