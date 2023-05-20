---
id: common.sha512sum
title: Sha512sum
desc: ''
updated: 1684549900169
created: 1684549900169
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sha512sum

> Calculate SHA512 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA512 checksum for one or more files:

`sha512sum {{path/to/file1 path/to/file2 ...}}`

- Calculate and save the list of SHA512 checksums to a file:

`sha512sum {{path/to/file1 path/to/file2 ...}} > {{path/to/file.sha512}}`

- Calculate a SHA512 checksum from `stdin`:

`{{command}} | sha512sum`

- Read a file of SHA512 sums and filenames and verify all files have matching checksums:

`sha512sum --check {{path/to/file.sha512}}`

- Only show a message for missing files or when verification fails:

`sha512sum --check --quiet {{path/to/file.sha512}}`

- Only show a message when verification fails, ignoring missing files:

`sha512sum --ignore-missing --check --quiet {{path/to/file.sha512}}`

