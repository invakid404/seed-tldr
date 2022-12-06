---
id: common.waifu2x-ncnn-vulkan
title: Waifu2x Ncnn Vulkan
desc: ''
updated: 1670310991894
created: 1670310991894
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# waifu2x-ncnn-vulkan

> Image upscaler for manga/anime-style images using NCNN neural network framework.
> More information: <https://github.com/nihui/waifu2x-ncnn-vulkan>.

- Upscale an image:

`waifu2x-ncnn-vulkan -i {{path/to/input_file}} -o {{path/to/output_file}}`

- Upscale an image by a custom scale factor and denoise it:

`waifu2x-ncnn-vulkan -i {{path/to/input_file}} -o {{path/to/output_file}} -s {{1|2|4|8|16|32}} -n {{-1|0|1|2|3}}`

- Save the upscaled image in a specific format:

`waifu2x-ncnn-vulkan -i {{path/to/input_file}} -o {{path/to/output_file}} -f {{jpg|png|webp}}`

