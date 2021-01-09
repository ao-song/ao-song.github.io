---
layout: post
title: reduce docker image size
category: work
---

Recently I have built a docker image based on ```python:3.8```, it was only a simple python script to be copied and run but the generated image size was 895MB, after I changed to ```python:3.8-alpine```, the image size has been reduced to 56.8 MB.

Further improvement could be using [multi-stage builds](https://docs.docker.com/develop/develop-images/multistage-build/), but in my case I only need copy and run one single file, there is no much difference by applying this. If you need compile source code or using pyinstaller to package the python scripts, this might be useful.
