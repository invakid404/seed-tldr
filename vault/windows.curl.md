---
id: windows.curl
title: Curl
desc: ''
updated: 1657677698736
created: 1657677698736
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# curl

> In PowerShell, this command may be an alias of `Invoke-WebRequest` when the original `curl` program (<https://curl.se>) is not properly installed.

- Check whether `curl` is properly installed by printing its version number. If this command evaluates into an error, PowerShell may have substituted this command with `Invoke-WebRequest`:

`curl --version`

- View documentation for the original `curl` command:

`tldr curl -p common`

- View documentation for PowerShell's `Invoke-WebRequest` command:

`tldr invoke-webrequest`

