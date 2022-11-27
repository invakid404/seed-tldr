---
id: common.feroxbuster
title: Feroxbuster
desc: ''
updated: 1669562307918
created: 1669562307918
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# feroxbuster

> Simple, fast, recursive content discovery tool written in Rust.
> Used to brute-force hidden paths on web servers and more.
> More information: <https://epi052.github.io/feroxbuster-docs/docs/>.

- Discover specific directories and files that match in the wordlist with extensions and 100 threads and a random user-agent:

`feroxbuster --url "{{https://example.com}}" --wordlist {{path/to/file}} --threads {{100}} --extensions "{{php,txt}}" --random-agent`

- Enumerate directories without recursion through a specific proxy:

`feroxbuster --url "{{https://example.com}}" --wordlist {{path/to/file}} --no-recursion --proxy "{{http://127.0.0.1:8080}}"`

- Find links in webpages:

`feroxbuster --url "{{https://example.com}}" --extract-links`

- Filter by a specific status code and a number of chars:

`feroxbuster --url "{{https://example.com}}" --filter-status {{301}} --filter-size {{4092}}`

