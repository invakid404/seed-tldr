---
id: linux.cam
title: Cam
desc: ''
updated: 1690222936926
created: 1690222936926
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cam

> Frontend tool for `libcamera`.
> More information: <https://libcamera.org/docs.html>.

- List available cameras:

`cam --list`

- List controls of a camera:

`cam --camera {{camera_index}} --list-controls`

- Write frames to a folder:

`cam --camera {{camera_index}} --capture={{frames_to_capture}} --file`

- Display camera feed in a window:

`cam --camera {{camera_index}} --capture --sdl`

