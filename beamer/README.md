Latex Beamer Template
=====================

Installation
------------
To use the provided latex beamer template, the Ubuntu font has to be available
for `mktexlsr`. For `latex` and `pdflatex` this can be a painful process to
install manually. We recommend using the following installation package:
[ubuntu-latex-fonts](https://github.com/tzwenn/ubuntu-latex-fonts). For `xetex`
and `luatex` the package `fontspec` makes this much easier, and no installation
is required.

Usage
-----

To use the, place the files `beamerthemeXal.sty`, `slide.png` and
`titlepage.png` in the same folder as the slide source file(s), and include
`\usetheme{Xal}` in the preamble.

Options
-------
The style will use the the package `ifluatex` to determine if `fontspec` should
be used, or if ubuntufont should be available in path. However if the default
doesn't work or `ifluatex` is missing, the font import strategy can be forced
using the options `\usetheme[fontspec]{Xal}` or `\usetheme[installed]{Xal}`.
