## lorig-style


Matt Lorig (https://mattlorig.yolasite.com/) has made a career out of producing beautiful latex documents. His stylistic choices have been compiled into this package. To use, simply place "lorig.sty" in your latex path and use \usepackage{lorig} to include.

 Optional arguments:

   Mutually exclusive argments:
	*__frenchmath__ OR __italics__   (default: frenchmath) -  defines option to be used for mathastext package

	*__toDVItoPDf__ OR __toPStoPDF__ (default: toPStoPDF)  -  the toDVItoPDf specifices 
		\RequirePackage[pdftex]{graphicx}\RequirePackage{epstopdf} 
		while toPStoPDF specifices  \RequirePackage{graphicx}

   Other options:
	*__draft__       - when specified, equation labels are shown on the left

	*__doublespace__ - when specified, document is doublespaced

Examples of this package in use: 
	[Approximate pricing of European and Barrier claims in a local-stochastic volatility setting](https://arxiv.org/pdf/1610.05728.pdf)
