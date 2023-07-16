---
id: linux.authconfig
title: Authconfig
desc: ''
updated: 1689531679779
created: 1689531679779
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# authconfig

> Configure system authentication resources.
> More information: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system-level_authentication_guide/authconfig-install>.

- Display the current configuration (or dry run):

`authconfig --test`

- Configure the server to use a different password hashing algorithm:

`authconfig --update --passalgo={{algorithm}}`

- Enable LDAP authentication:

`authconfig --update --enableldapauth`

- Disable LDAP authentication:

`authconfig --update --disableldapauth`

- Enable Network Information Service (NIS):

`authconfig --update --enablenis`

- Enable Kerberos:

`authconfig --update --enablekrb5`

- Enable Winbind (Active Directory) authentication:

`authconfig --update --enablewinbindauth`

- Enable local authorization:

`authconfig --update --enablelocauthorize`

