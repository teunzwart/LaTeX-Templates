LaTeX-Templates
===============
Various LaTeX templates. The homework template is based on
[this one](http://www.cs.cmu.edu/~ckingsf/class/02-714/hw-template.tex) by Carl
Kingsford. There is no BibTeX template because bibliographies are easier to
make using programs such as [BibDesk](http://bibdesk.sourceforge.net).

## More `siunitx` options

If you need non-SI units such as lightyear or femtobarn, you can define them
yourself. See the
[package manual](http://ctan.cs.uu.nl/macros/latex/contrib/siunitx/siunitx.pdf)
[PDF].


## Why no `pgfplots`?

[`pgfplots`](http://ctan.cs.uu.nl/graphics/pgf/contrib/pgfplots/doc/pgfplots.pdf) [PDF]
is a package for creating 2D and 3D plots directly in LaTeX. While this does
work, LaTeX was never designed to be good at plotting graphs and consequently is
quite slow (especially in 3D) when rendering them. It's quicker to make an image
and then include that.
