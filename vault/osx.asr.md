---
id: osx.asr
title: Asr
desc: ''
updated: 1676877466483
created: 1676877466483
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asr

> Restore (copy) a disk image onto a volume.
> The command name stands for Apple Software Restore.
> More information: <https://www.unix.com/man-page/osx/8/asr/>.

- Restore a disk image to a target volume:

`sudo asr restore --source {{image_file.dmg}} --target {{path/to/volume_file}}`

- Erase the target volume before restoring:

`sudo asr restore --source {{image_file.dmg}} --target {{path/to/volume_file}} --erase`

- Skip verification after restoring:

`sudo asr restore --source {{image_file.dmg}} --target {{path/to/volume_file}} --noverify`

- Clone volumes without the use of an intermediate disk image:

`sudo asr restore --source {{path/to/volume_file}} --target {{path/to/volume_file}}`

