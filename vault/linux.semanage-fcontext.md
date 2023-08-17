---
id: linux.semanage-fcontext
title: Semanage Fcontext
desc: ''
updated: 1692281659052
created: 1692281659052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# semanage fcontext

> Manage persistent SELinux security context rules on files/directories.
> See also: `semanage`, `restorecon`.
> More information: <https://manned.org/semanage-fcontext>.

- List all file labelling rules:

`sudo semanage fcontext --list`

- List all user-defined file labelling rules without headings:

`sudo semanage fcontext --list --locallist --noheading`

- Add a user-defined rule that labels any path which matches a PCRE regex:

`sudo semanage fcontext --add --type {{samba_share_t}} {{'/mnt/share(/.*)?'}}`

- Delete a user-defined rule using its PCRE regex:

`sudo semanage fcontext --delete {{'/mnt/share(/.*)?'}}`

- Relabel a directory recursively by applying the new rules:

`restorecon -R -v {{path/to/directory}}`

