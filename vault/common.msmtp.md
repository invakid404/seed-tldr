---
id: common.msmtp
title: Msmtp
desc: ''
updated: 1691562059035
created: 1691562059035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# msmtp

> An SMTP client.
> It reads text from `stdin` and sends it to an SMTP server.
> More information: <https://marlam.de/msmtp>.

- Send an email using the default account configured in `~/.msmtprc`:

`echo "{{Hello world}}" | msmtp {{to@example.org}}`

- Send an email using a specific account configured in `~/.msmtprc`:

`echo "{{Hello world}}" | msmtp --account={{account_name}} {{to@example.org}}`

- Send an email without a configured account. The password should be specified in the `~/.msmtprc` file:

`echo "{{Hello world}}" | msmtp --host={{localhost}} --port={{999}} --from={{from@example.org}} {{to@example.org}}`

