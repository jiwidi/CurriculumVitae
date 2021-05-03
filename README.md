# Curriculum Vitae
[![Build LaTeX document](https://github.com/jiwidi/CurriculumVitae/actions/workflows/main.yml/badge.svg)](https://github.com/jiwidi/CurriculumVitae/actions/workflows/main.yml)

My personal CV, based on `AltaCV, yet another LaTeX CV/Résumé class`.

It's linked with overleaf to sync `.tex` files and has a github action listening to push events to build `cv.pdf` and push it to master. CD for your CV!

## Requirements and Compilation

* pdflatex + biber + pdflatex
* AltaCV uses [`fontawesome`](http://www.ctan.org/pkg/fontawesome) and [`academicons`](http://www.ctan.org/pkg/academicons); they're included in both TeX Live 2016 and MikTeX 2.9.
* Loading `academicons` is optional: enable it by adding the `academicons` option to `\documentclass`.
* Use the `normalphoto` option to get a normal (i.e. non-circular) photo.
* Use the `ragged2d` option to activate hyphenations while keeping text left-justified; line endings will thus be less jagged and more aesthetically pleasing.
* Can now be compiled with pdflatex, XeLaTeX and LuaLaTeX!
* However if you're using `academicons`, you _must_ use either XeLaTeX or LuaLaTeX. If the doc then compiles but the icons don't show up in the output PDF, try compiling with LuaLaTeX instead.
* The samples here use the [Lato](http://www.latofonts.com/lato-free-fonts/) font.
