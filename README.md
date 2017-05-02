## lorig-style


Matt Lorig (https://mattlorig.yolasite.com/) has made a career out of producing beautiful latex documents. His stylistic choices have been compiled into this package. To use, simply place "lorig.sty" in your latex path and use \usepackage{lorig} to include.

 Optional arguments:

   Mutually exclusive argments:
		frenchmath OR italics   (default: frenchmath) -  defines option to be used for mathastext package
		toDVItoPDf OR toPStoPDF (default: toPStoPDF)  -  the toDVItoPDf specifices \RequirePackage[pdftex]{graphicx}\RequirePackage{epstopdf} while toPStoPDF specifices  \RequirePackage{graphicx}
   Other options:
		draft       - when specified, equation labels are shown on the left
		doublespace - when specified, document is doublespaced

Examples of this package in use:
	https://arxiv.org/abs/1610.05728
