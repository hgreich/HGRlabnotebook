---
layout: post
title: making a cv in Rmarkdown
date: '2021-06-23'
categories: Protocols
tags: Rmarkdown, Github, CV
---

date started 20210623;
date last revised 20210623 hgr post creation

# I want to remake my CV in Rmarkdown using one of the following packages
- https://pkg.mitchelloharawild.com/vitae/
- http://nickstrayer.me/datadrivencv/

# other useful links
- vitae cran documentation: https://cran.r-project.org/web/packages/vitae/vitae.pdf
- powerpoint on vitae package: https://slides.mitchelloharawild.com/vitae/#1

# first roadblock after trying to knit rmarkdown file = pandoc package
- the pandoc package is a document converter
- error message:
>pandoc: unrecognized option --lua-filter
Try pandoc --help for more information.
Error: pandoc document conversion failed with error 2
In addition: Warning message:
Detected pandoc version 1.19.2.1, which may cause issues with bibliography_entries().
Please update pandoc if you have any issues knitting bibliographies (this can be done by updating RStudio).
-xecution halted

#### tried to install package
> install.packages('pandoc')
>Warning in install.packages : package ‘pandoc’ is not available for this version of R

#### ways to install r packages that "aren't available for version x of R"
- stack overflow sources: https://stackoverflow.com/questions/25721884/how-should-i-deal-with-package-xxx-is-not-available-for-r-version-x-y-z-wa

##### failed attempt, the install.pandoc() function is for windows
- from "pandoc r package" [google search](https://rdrr.io/cran/installr/man/install.pandoc.html)... install_pandoc() function inside of installr() #this resource is for windows
- tried to install pandoc:
  install.packages("installr")
  library(installr)
  suppressPackageStartupMessages(library(installr))
  install.pandoc(keep_install_file=TRUE)
- permission denied
  sh: /var/folders/mh/pw7rz3zx2rv03w136sjn33480000gn/T//Rtmp7Wgj9E/pandoc-2.14.0.3-windows-x86_64.msi: Permission denied
- used terminal to navigate to mysterious directory
  cd /var/folders/mh/pw7rz3zx2rv03w136sjn33480000gn/T//Rtmp7Wgj9E/
- changed permissions on everything
  ls -lh
  chmod u+x *
  ls -lh
- tried to re-install pandoc
  install.pandoc(keep_install_file=TRUE)
  sh: /var/folders/mh/pw7rz3zx2rv03w136sjn33480000gn/T//Rtmp7Wgj9E/pandoc-2.14.0.3-windows-x86_64.msi: cannot execute binary file

# Alas, All I had to do was install pandoc for mac. No command line. No R. Just a simple installer.
- [the simple link I needed all along](https://pandoc.org/installing.html)
- this is the resource that gave the clue to install pandoc before goofing around in R. Sigh. https://bookdown.org/yihui/rmarkdown/format-custom.html
