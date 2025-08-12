# LuaLaTeX

Definitions for the [LuaLaTeX](https://www.latex-project.org) library.

TeXLuaCats-Repository: https://github.com/TeXLuaCATS/LuaLaTeX (upstream)

LuaCats-Repository: https://github.com/LuaCATS/tex-lualatex (downstream)

## About the documented project

LuaTEX adds a number of engine-specific functions to TEX. Several of
these require set up that is best done in the kernel or need related
support functions. This file provides basic support for LuaTEX at the
LATEX 2ε kernel level plus as a loadable file which can be used with
plain TEX and LATEX.

This file contains code for both TEX (to be stored as part of the
format) and Lua (to be loaded at the start of each job). In the Lua
code, the kernel uses the namespace luatexbase.
[^manual]

[^manual]: https://mirrors.ctan.org/macros/latex/base/ltluatex.pdf

* Website: https://www.latex-project.org
* PDF-Manual: [ltluatex.pdf](https://mirrors.ctan.org/macros/latex/base/ltluatex.pdf) [source2e.pdf](https://ftp.gwdg.de/pub/ctan/macros/latex/base/source2e.pdf)
* Repository: [Github: latex3/latex2e](https://github.com/latex3/latex2e/blob/develop/base/ltluatex.dtx)
* CTAN: [latex-base](https://www.ctan.org/pkg/latex-base) [luatexbase](https://www.ctan.org/pkg/luatexbase) (old)
* LICENSE: [lppl1.3c](https://github.com/latex3/latex2e/blob/develop/LICENSE)
