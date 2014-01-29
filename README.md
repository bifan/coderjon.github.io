Bolg
==================================

####The bat for reboot local jekyll：
```batch
@echo off
taskkill /fi "windowTitle eq jekyll"
title jekyll
cd C:\Users\FIVE-D\Documents\GitHub\coderjon.github.io
jekyll serve
cmd
```
