---
id: common.pytest
title: Pytest
desc: ''
updated: 1669454286313
created: 1669454286313
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pytest

> Run Python tests.
> More information: <https://docs.pytest.org/>.

- Run tests from specific files:

`pytest {{path/to/test_file1.py path/to/test_file2.py ...}}`

- Run tests with names matching a specific [k]eyword expression:

`pytest -k {{expression}}`

- Exit as soon as a test fails or encounters an error:

`pytest --exitfirst`

- Run tests matching or excluding markers:

`pytest -m {{marker_name1 and not marker_name2}}`

- Run until a test failure, continuing from the last failing test:

`pytest --stepwise`

- Run tests without capturing output:

`pytest --capture=no`

