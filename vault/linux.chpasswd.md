---
id: linux.chpasswd
title: Chpasswd
desc: ''
updated: 1670142131048
created: 1670142131048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chpasswd

> Change the passwords for multiple users by using `stdin`.
> More information: <https://manned.org/chpasswd.8>.

- Change the password for a specific user:

`printf "{{username}}:{{new_password}}" | sudo chpasswd`

- Change the passwords for multiple users (The input text must not contain any spaces.):

`printf "{{username_1}}:{{new_password_1}}\n{{username_2}}:{{new_password_2}}" | sudo chpasswd`

- Change the password for a specific user, and specify it in encrypted form:

`printf "{{username}}:{{new_encrypted_password}}" | sudo chpasswd --encrypted`

- Change the password for a specific user, and use a specific encryption for the stored password:

`printf "{{username}}:{{new_password}}" | sudo chpasswd --crypt-method {{NONE|DES|MD5|SHA256|SHA512}}`

