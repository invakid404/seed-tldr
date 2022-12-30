---
id: linux.autorandr
title: Autorandr
desc: ''
updated: 1672363466413
created: 1672363466413
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# autorandr

> Automatically change screen layout.
> More information: <https://github.com/phillipberndt/autorandr>.

- Save the current screen layout:

`autorandr --save {{profile_name}}`

- Show the saved profiles:

`autorandr`

- Load the first detected profile:

`autorandr --change`

- Load a specific profile:

`autorandr --load {{profile_name}}`

- Set the default profile:

`autorandr --default {{profile_name}}`

