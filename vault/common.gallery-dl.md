---
id: common.gallery-dl
title: Gallery Dl
desc: ''
updated: 1683599668549
created: 1683599668549
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gallery-dl

> Download image galleries and collections from several image hosting sites.
> More information: <https://github.com/mikf/gallery-dl>.

- Download images from the specified URL:

`gallery-dl "{{url}}"`

- Get the direct URL of an image from a site supporting authentication with username and password:

`gallery-dl --get-urls --username {{username}} --password {{password}} "{{url}}"`

- Filter manga chapters by chapter number and language:

`gallery-dl --chapter-filter "{{10 <= chapter < 20}}" --option "lang={{language_code}}" "{{url}}`

