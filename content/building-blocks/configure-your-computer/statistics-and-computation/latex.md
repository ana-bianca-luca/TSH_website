---
title: "LaTeX"
description: "LaTeX is a great typesetting system that includes a lot of features that allow to produce scientific documents."
keywords: "latex, tex, installation, software, configuration, paper, writing, text, typesetting"
date: 2020-11-11T22:02:51+05:30
draft: false
weight: 9
---

LaTeX is a great typesetting system that includes a lot of features that allow to produce scientific documents. Many researchers use LaTeX to produce their papers and presentations, and many journals require authors to hand in their articles in a LaTeX format.

## Installing a TeX distribution
LaTeX is free to use. To use the LaTeX system, a TeX distribution needs to be installed. Detailed instructions for the different platforms are provided below.

After following the instructions, check whether everything worked by checking the output of the following command:

```bash
tex --version
```

This should give an output similar to this one, where version numbers and details will change depending on your platform.

```bash
TeX 3.14159265 (TeX Live 2019/Debian)
kpathsea version 6.3.1
Copyright 2019 D.E. Knuth.
There is NO warranty.  Redistribution of this software is
covered by the terms of both the TeX copyright and
the Lesser GNU General Public License.
For more information about these matters, see the file
named COPYING and the TeX source.
Primary author of TeX: D.E. Knuth.
```

{{% warning %}}
**For Windows Users**

Download the file `install-tl-windows.exe` from [here](https://www.tug.org/texlive/acquire-netinstall.html) and follow the instructions.
{{% /warning %}}
{{% warning %}}
**For Mac Users**

You can install this using `Homebrew` or via the [official website](https://www.tug.org/mactex/):

```bash
brew cask install mactex
```
{{% /warning %}}
{{% warning %}}
**For Linux Users (Ubuntu-based)**

Install it from the terminal using:

```bash
sudo apt-get install texlive-latex-extra
```
{{% /warning %}}

Note that additional packages for Tex Live should be installed through the apt package manager as well (using `tlmgr` leads to problems due to different versions)