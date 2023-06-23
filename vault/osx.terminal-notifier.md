---
id: osx.terminal-notifier
title: Terminal Notifier
desc: ''
updated: 1687523785393
created: 1687523785393
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# terminal-notifier

> Send macOS User Notifications.
> More information: <https://github.com/julienXX/terminal-notifier>.

- Send a notification (only the message is required):

`terminal-notifier -group {{tldr-info}} -title {{TLDR}} -message '{{TLDR rocks}}'`

- Display piped data with a sound:

`echo '{{Piped Message Data!}}' | terminal-notifier -sound {{default}}`

- Open a URL when the notification is clicked:

`terminal-notifier -message '{{Check your Apple stock!}}' -open '{{http://finance.yahoo.com/q?s=AAPL}}'`

- Open an app when the notification is clicked:

`terminal-notifier -message '{{Imported 42 contacts.}}'  -activate {{com.apple.AddressBook}}`

