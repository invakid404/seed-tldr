---
id: common.sha224sum
title: Sha224sum
desc: ''
updated: 1684491440586
created: 1684491440586
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sha224sum

> Calculate SHA224 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA224 checksum for one or more files:

`sha224sum {{path/to/file1 path/to/file2 ...}}`

- Calculate and save the list of SHA224 checksums to a file:

`sha224sum {{path/to/file1 path/to/file2 ...}} > {{path/to/file.sha224}}`

- Calculate a SHA224 checksum from `stdin`:

`{{some_command}} | sha224sum`

- Read a file of SHA224 sums and filenames and verify all files have matching checksums:

`sha224sum --check {{path/to/file.sha224}}`

- Only show a message for missing files or when verification fails:

`sha224sum --check --quiet {{path/to/file.sha224}}`

- Only show a message when verification fails, ignoring missing files:

`sha224sum --ignore-missing --check --quiet {{path/to/file.sha224}}`

