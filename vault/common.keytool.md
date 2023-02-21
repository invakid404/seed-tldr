---
id: common.keytool
title: Keytool
desc: ''
updated: 1676960612402
created: 1676960612402
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# keytool

> Keytool is a certificate management utility included with Java.
> More information: <https://docs.oracle.com/en/java/javase/19/docs/specs/man/keytool.html>.

- Create a keystore:

`keytool -genkeypair -v -keystore {{path/to/file.keystore}} -alias {{key_name}}`

- Change a keystore password:

`keytool -storepasswd -keystore {{path/to/file.keystore}}`

- Change a key's password inside a specific keystore:

`keytool -keypasswd  -alias {{key_name}} -keystore {{path/to/file.keystore}}`

