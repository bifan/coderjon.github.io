coderjon.github.io
==================
####自动在本地重启、部署jekyll的批处理：
``` bat
@echo off
taskkill /fi "windowTitle eq jekyll"
title jekyll
cd C:\Users\FIVE-D\Documents\GitHub\coderjon.github.io
jekyll serve
cmd
```
bolg @ github
