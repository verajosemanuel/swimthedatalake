---
title: Easy Rstudio add-in management with addinslist package
author: jvera
date: '2017-07-17'
slug: easy-rstudio-add-in-management-with-addinslist-package
categories:
  - packages
tags: []
---

When started using Rstudio (some time ago) I had been wondering where the Rstudio Addins were located. There’s a menu option, but It was empty on my machine. Seeking an easy way to install some addins I’ve found “addinslist”

```r
install.packages (“addinslist”)
```
Or using pacman:

```r
pacman::p_load(addinslist)
```
After installation, a wizard is available for everybody to choose among a lot of add-ins for Rstudio. Some of them extremely useful. You can watch videos of some of them running.
There’s addins for generating histograms with ggplot2 by just choosing factors, to recode categorical variables, for programming cron scripts, code formatters …..