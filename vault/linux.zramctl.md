---
id: linux.zramctl
title: Zramctl
desc: ''
updated: 1656591837669
created: 1656591837669
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zramctl

> Setup and control zram devices.
> Use `mkfs` or `mkswap` to format zram devices to partitions.
> More information: <https://manned.org/zramctl>.

- Check if zram is enabled:

`lsmod | grep -i zram`

- Enable zram with a dynamic number of devices (use `zramctl` to configure devices further):

`sudo modprobe zram`

- Enable zram with exactly 2 devices:

`sudo modprobe zram num_devices={{2}}`

- Find and initialize the next free zram device to a 2 GB virtual drive using LZ4 compression:

`sudo zramctl --find --size {{2GB}} --algorithm {{lz4}}`

- List currently initialized devices:

`zramctl`

