---
id: common.clj
title: Clj
desc: ''
updated: 1686680394341
created: 1686680394341
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# clj

> Clojure tool to start a REPL or invoke a specific function with data.
> All options can be defined in a `deps.edn` file.
> More information: <https://clojure.org/guides/deps_and_cli>.

- Start a REPL (interactive shell):

`clj`

- Execute a function:

`clj -X {{namespace/function_name}}`

- Run the main function of a specified namespace:

`clj -M -m {{namespace}} {{args}}`

- Prepare a project by resolving dependencies, downloading libraries, and making/caching classpaths:

`clj -P`

- Start an nREPL server with the CIDER middleware:

`clj -Sdeps '{:deps {nrepl {:mvn/version "0.7.0"} cider/cider-nrepl {:mvn/version "0.25.2"}}}' -m nrepl.cmdline --middleware '["cider.nrepl/cider-middleware"]' --interactive`

- Start a REPL for ClojureScript and open a web browser:

`clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "1.10.758"}}}' --main cljs.main --repl`

