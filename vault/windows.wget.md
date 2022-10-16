---
id: windows.wget
title: Wget
desc: ''
updated: 1665909064827
created: 1665909064827
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wget

> In PowerShell, this command may be an alias of `Invoke-WebRequest` when the original `wget` program (<https://www.gnu.org/software/wget>) is not properly installed.

- Check whether `wget` is properly installed by printing its version number. If this command evaluates into an error, PowerShell may have substituted this command with `Invoke-WebRequest`:

`curl --version`

- View documentation for the original `wget` command:

`tldr wget -p common`

- View documentation for the original `wget` command in older versions of `tldr` command-line client:

`tldr wget -o common`

- View documentation for PowerShell's `Invoke-WebRequest` command:

`tldr invoke-webrequest`

