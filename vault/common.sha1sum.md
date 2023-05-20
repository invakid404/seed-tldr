---
id: common.sha1sum
title: Sha1sum
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
# sha1sum

> Calculate SHA1 cryptographic checksums.
> More information: <https://www.gnu.org/software/coreutils/sha1sum>.

- Calculate the SHA1 checksum for one or more files:

`sha1sum {{path/to/file1 path/to/file2 ...}}`

- Calculate and save the list of SHA1 checksums to a file:

`sha1sum {{path/to/file1 path/to/file2 ...}} > {{path/to/file.sha1}}`

- Calculate a SHA1 checksum from `stdin`:

`{{command}} | sha1sum`

- Read a file of SHA1 sums and filenames and verify all files have matching checksums:

`sha1sum --check {{path/to/file.sha1}}`

- Only show a message for missing files or when verification fails:

`sha1sum --check --quiet {{path/to/file.sha1}}`

- Only show a message when verification fails, ignoring missing files:

`sha1sum --ignore-missing --check --quiet {{path/to/file.sha1}}`

