---
id: linux.prename
title: Prename
desc: ''
updated: 1656591837645
created: 1656591837645
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rename

> Rename multiple files.
> NOTE: this page refers to the command from the `prename` Fedora package.
> More information: <https://manned.org/man/prename>.

- Rename files using a Perl Common Regular Expression (substitute 'foo' with 'bar' wherever found):

`rename {{'s/foo/bar/'}} {{*}}`

- Dry-run - display which renames would occur without performing them:

`rename -n {{'s/foo/bar/'}} {{*}}`

- Force renaming even if the operation would remove existing destination files:

`rename -f {{'s/foo/bar/'}} {{*}}`

- Convert filenames to lower case (use `-f` in case-insensitive filesystems to prevent "already exists" errors):

`rename 'y/A-Z/a-z/' {{*}}`

- Replace whitespace with underscores:

`rename 's/\s+/_/g' {{*}}`

